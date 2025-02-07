local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()

local Window = OrionLib:MakeWindow({Name = "Premium HUB/UNIVERSAL SOONðŸ”œ", HidePremium = false, SaveConfig = true, ConfigFolder = "OrionTest"})
local Tab = Window:MakeTab({
	Name = "Op Function",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = True
})
Tab:AddButton({
	Name = "Op cd",
	Callback = function()
      		print("button pressed")
  	end    
})
Tab:AddButton({
	Name = "Reset",
	Callback = function()
      		print("button pressed")
  	end    
})
local Tab = Window:MakeTab({
	Name = "Op function",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = True
})
OrionLib:MakeNotification({
	Name = "Op premium",
	Content = "Version Premium",
	Image = "rbxassetid://4483345998",
	Time = 5
})
Tab:AddButton({
	Name = "Give item",
	Callback = function()
      		print("button pressed")
  	end    
})
