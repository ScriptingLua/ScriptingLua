local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()

local Window = OrionLib:MakeWindow({Name = "🍃Leaf Hub | Ohio🍃", HidePremium = false, SaveConfig = true, ConfigFolder = "OrionTest"})

local FarmTab = Window:MakeTab({
	Name = "🔥Farm🔥",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

local Section = FarmTab:AddSection({
	Name = "Farming"
})

local TeleportTab = Window:MakeTab({
	Name = "🌟Teleport🌟",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

local Section = TeleportTab:AddSection({
	Name = "Locations"
})

TeleportTab:AddButton({
	Name = "Bank",
	Callback = function()
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1086, 6, -412)
  	end    
})

TeleportTab:AddButton({
	Name = "BankVault",
	Callback = function()
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1061, 9, -344)
  	end    
})

TeleportTab:AddButton({
	Name = "Gas Station",
	Callback = function()
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1078, 6, -620)
  	end    
})

TeleportTab:AddButton({
	Name = "Armory",
	Callback = function()
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(676, 6, -652)
  	end    
})

TeleportTab:AddButton({
	Name = "Funiture",
	Callback = function()
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(385, -6, -391)
  	end    
})

TeleportTab:AddButton({
	Name = "Skater Park",
	Callback = function()
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1609, 6, -160)
  	end    
})

TeleportTab:AddButton({
	Name = "Gym",
	Callback = function()
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1574, 6, -319)
  	end    
})

TeleportTab:AddButton({
	Name = "Hospital",
	Callback = function()
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1112, 6, -970)
  	end    
})

TeleportTab:AddButton({
	Name = "Police Station",
	Callback = function()
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(642, 9, -897)
  	end    
})

TeleportTab:AddButton({
	Name = "Millitary Base",
	Callback = function()
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(843, 25, -1402)
  	end    
})

TeleportTab:AddButton({
	Name = "Black Dealer",
	Callback = function()
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(711, -23, -115)
  	end    
})

TeleportTab:AddButton({
	Name = "Secret Spot",
	Callback = function()
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(606, 42, -693)
  	end    
})

TeleportTab:AddButton({
	Name = "Casino",
	Callback = function()
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1559, 9, -790)
  	end    
})

TeleportTab:AddButton({
	Name = "Equipment",
	Callback = function()
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(181, -4, -189)
  	end    
})

TeleportTab:AddButton({
	Name = "Jewelry",
	Callback = function()
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1546, 6, -684)
  	end    
})

FarmTab:AddLabel("NOTE: YOU NEED A LOCKPICK TO UNLOCK THE SAFES!")

FarmTab:AddButton({
	Name = "Vault-1",
	Callback = function()
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1060, 9, -359)
  	end    
})

FarmTab:AddButton({
	Name = "Vault-2",
	Callback = function()
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1054, 9, -337)
  	end    
})

FarmTab:AddButton({
	Name = "Vault-3",
	Callback = function()
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1620, 8, -722)
  	end    
})

FarmTab:AddButton({
	Name = "Vault-4",
	Callback = function()
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1637, 9, -735)
  	end    
})

FarmTab:AddButton({
	Name = "Vault-5",
	Callback = function()
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1660, 9, -728)
  	end    
})

FarmTab:AddButton({
	Name = "Vault-6",
	Callback = function()
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1646, 11, -768)
  	end    
})

local MiscTab = Window:MakeTab({
	Name = "🎲Misc🎲",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

local Section = MiscTab:AddSection({
	Name = "Join the Disocrd :)"
})

MiscTab:AddButton({
	Name = "https://discord.gg/7zdJx48u",
	Callback = function()
        setclipboard("https://discord.gg/7zdJx48u")
        toclipboard("https://discord.gg/7zdJx48u")
  	end    
})

