-- Init script


-- Alacritty hide/unhide shortcut
hs.hotkey.bind({"option"}, "`", function()
		alacritty = hs.application.find('alacritty')
		if alacritty ~= nil and alacritty:isFrontmost() then
			alacritty:hide()
		else
			hs.application.launchOrFocus("/Applications/Alacritty.app")
			local alacritty = hs.application.find('alacritty')
			alacritty.setFrontMost(alacritty)
			alacritty.activate(alacritty)
		end
	end
)
