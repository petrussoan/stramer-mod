	if script.Parent.Text == "Streamer Mode" then
		script.Parent.Text = "UnStreamer Mode"
		script.Parent.Parent.blur.Visible = true
	else
		script.Parent.Text = "Streamer Mode"
		script.Parent.Parent.blur.Visible = false
	end
