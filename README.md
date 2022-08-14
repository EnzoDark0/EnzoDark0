
local BotHub = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local Simplity = Instance.new("TextButton")
local UICorner = Instance.new("UICorner")
local BackdoorV8 = Instance.new("TextButton")
local UICorner_2 = Instance.new("UICorner")
local UICorner_3 = Instance.new("UICorner")
local Youtubelife = Instance.new("TextButton")
local UICorner_4 = Instance.new("UICorner")
local MurderMystery = Instance.new("TextButton")
local UICorner_5 = Instance.new("UICorner")
local BedwarsScript = Instance.new("TextButton")
local UICorner_6 = Instance.new("UICorner")
local Personlife = Instance.new("TextButton")
local UICorner_7 = Instance.new("UICorner")
local DomainX = Instance.new("TextButton")
local UICorner_8 = Instance.new("UICorner")
local TextLabel = Instance.new("TextLabel")
local Premuim = Instance.new("ImageButton")
local Frame_2 = Instance.new("Frame")
local PlayerImage = Instance.new("ImageLabel")
local UICorner_9 = Instance.new("UICorner")
local PlayerName = Instance.new("TextLabel")
local UITextSizeConstraint = Instance.new("UITextSizeConstraint")
local Petsimx = Instance.new("TextButton")
local UICorner_10 = Instance.new("UICorner")
local Trollingui = Instance.new("TextButton")
local UICorner_11 = Instance.new("UICorner")
local TappingSim = Instance.new("TextButton")
local UICorner_12 = Instance.new("UICorner")
local UIAspectRatioConstraint = Instance.new("UIAspectRatioConstraint")
local Autoreport = Instance.new("TextButton")
local UICorner_13 = Instance.new("UICorner")
local UIAspectRatioConstraint = Instance.new("UIAspectRatioConstraint")
local Arsenal = Instance.new("TextButton")
local UICorner_14 = Instance.new("UICorner")
local Grabknife = Instance.new("TextButton")
local UICorner_15 = Instance.new("UICorner")
local UIAspectRatioConstraint = Instance.new("UIAspectRatioConstraint")

--Properties:

BotHub.Name = "Bot Hub"
BotHub.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
BotHub.ZIndexBehavior = Enum.ZIndexBehavior.Sibling
BotHub.ResetOnSpawn = false

Frame.Parent = BotHub
Frame.BackgroundColor3 = Color3.fromRGB(34, 34, 34)
Frame.Position = UDim2.new(0.205371261, 0, 0.196078435, 0)
Frame.Size = UDim2.new(0, 814, 0, 359)
Simplity.Name = "Simplity"
Simplity.Parent = Frame
Simplity.BackgroundColor3 = Color3.fromRGB(63, 63, 63)
Simplity.Position = UDim2.new(0.00859950855, 0, 0.438992888, 0)
Simplity.Size = UDim2.new(0, 84, 0, 43)
Simplity.Style = Enum.ButtonStyle.RobloxButton
Simplity.Font = Enum.Font.SourceSansBold
Simplity.Text = "Simplity"
Simplity.TextColor3 = Color3.fromRGB(255, 255, 255)
Simplity.TextSize = 15.000
Simplity.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
Simplity.MouseButton1Down:Connect(function()

	loadstring(game:HttpGet("https://raw.githubusercontent.com/HeyGyt/simpleopensource/main/main"))()

end)
UICorner.Parent = Simplity

BackdoorV8.Name = "Backdoor V8"
BackdoorV8.Parent = Frame
BackdoorV8.BackgroundColor3 = Color3.fromRGB(63, 63, 63)
BackdoorV8.Position = UDim2.new(0.00859950855, 0, 0.301687181, 0)
BackdoorV8.Size = UDim2.new(0.103194103, 0, 0.111398965, 0)
BackdoorV8.Style = Enum.ButtonStyle.RobloxButton
BackdoorV8.Font = Enum.Font.SourceSansBold
BackdoorV8.Text = "Backdoor V8"
BackdoorV8.TextColor3 = Color3.fromRGB(255, 255, 255)
BackdoorV8.TextSize = 15.000
BackdoorV8.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
BackdoorV8.MouseButton1Down:Connect(function()

	loadstring(game:HttpGet("https://raw.githubusercontent.com/iK4oS/backdoor.exe/v8/src/main.lua"))();
end)
UICorner_2.Parent = BackdoorV8

UICorner_3.Parent = Frame

Youtubelife.Name = "Youtube life"
Youtubelife.Parent = Frame
Youtubelife.BackgroundColor3 = Color3.fromRGB(63, 63, 63)
Youtubelife.BorderColor3 = Color3.fromRGB(27, 42, 53)
Youtubelife.Position = UDim2.new(0, 8, 0, 213)
Youtubelife.Size = UDim2.new(0.103194103, 0, 0.111398965, 0)
Youtubelife.Style = Enum.ButtonStyle.RobloxButton
Youtubelife.Font = Enum.Font.SourceSansBold
Youtubelife.Text = "Youtube life "
Youtubelife.TextColor3 = Color3.fromRGB(255, 255, 255)
Youtubelife.TextSize = 15.000
Youtubelife.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
Youtubelife.MouseButton1Down:Connect(function()

	loadstring(game:HttpGet("https://raw.githubusercontent.com/RegularVynixu/Scripts/main/YouTube%20Life/Auto%20Farm.lua"))()

end)
UICorner_4.Parent = Youtubelife

MurderMystery.Name = "Murder Mystery"
MurderMystery.Parent = Frame
MurderMystery.BackgroundColor3 = Color3.fromRGB(63, 63, 63)
MurderMystery.BorderColor3 = Color3.fromRGB(27, 42, 53)
MurderMystery.Position = UDim2.new(0, 8, 0, 263)
MurderMystery.Size = UDim2.new(0.103194103, 0, 0.111398965, 0)
MurderMystery.Style = Enum.ButtonStyle.RobloxButton
MurderMystery.Font = Enum.Font.SourceSansBold
MurderMystery.Text = "Murder Mystery"
MurderMystery.TextColor3 = Color3.fromRGB(255, 255, 255)
MurderMystery.TextSize = 13.000
MurderMystery.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
MurderMystery.MouseButton1Down:Connect(function()

	loadstring(game:GetObjects("rbxassetid://4001118261")[1].Source)()

end)
UICorner_5.Parent = MurderMystery

BedwarsScript.Name = "Bedwars Script"
BedwarsScript.Parent = Frame
BedwarsScript.BackgroundColor3 = Color3.fromRGB(63, 63, 63)
BedwarsScript.BorderColor3 = Color3.fromRGB(27, 42, 53)
BedwarsScript.Position = UDim2.new(0, 8, 0, 314)
BedwarsScript.Size = UDim2.new(0.103194103, 0, 0.111398965, 0)
BedwarsScript.Style = Enum.ButtonStyle.RobloxButton
BedwarsScript.Font = Enum.Font.SourceSansBold
BedwarsScript.Text = "Bedwars"
BedwarsScript.TextColor3 = Color3.fromRGB(255, 255, 255)
BedwarsScript.TextSize = 15.000
BedwarsScript.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
BedwarsScript.MouseButton1Down:Connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/7GrandDadPGN/VapeV4ForRoblox/main/NewMainScript.lua", true))()

end)
UICorner_6.Parent = BedwarsScript

Personlife.Name = "Person life"
Personlife.Parent = Frame
Personlife.BackgroundColor3 = Color3.fromRGB(63, 63, 63)
Personlife.BorderColor3 = Color3.fromRGB(27, 42, 53)
Personlife.Position = UDim2.new(0, 8, 0, 57)
Personlife.Size = UDim2.new(0.103194103, 0, 0.111398965, 0)
Personlife.Style = Enum.ButtonStyle.RobloxButton
Personlife.Font = Enum.Font.SourceSansBold
Personlife.Text = "Prison life"
Personlife.TextColor3 = Color3.fromRGB(255, 255, 255)
Personlife.TextSize = 15.000
Personlife.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
Personlife.MouseButton1Down:Connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/GwnStefano/NexusHub/main/Main", true))()
end) 
UICorner_7.Parent = Personlife

DomainX.Name = "Domain X"
DomainX.Parent = Frame
DomainX.BackgroundColor3 = Color3.fromRGB(63, 63, 63)
DomainX.BorderColor3 = Color3.fromRGB(27, 42, 53)
DomainX.Position = UDim2.new(0, 8, 0, 11)
DomainX.Size = UDim2.new(0.103194103, 0, 0.111398965, 0)
DomainX.Style = Enum.ButtonStyle.RobloxButton
DomainX.Font = Enum.Font.SourceSansBold
DomainX.Text = "Domain X"
DomainX.TextColor3 = Color3.fromRGB(255, 255, 255)
DomainX.TextSize = 15.000
DomainX.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
DomainX.MouseButton1Down:Connect(function()
	loadstring(game:HttpGet('https://raw.githubusercontent.com/shlexware/DomainX/main/source',true))()
end)
UICorner_8.Parent = DomainX

TextLabel.Parent = Frame
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.Position = UDim2.new(0.00737100746, 0, 0, 0)
TextLabel.Size = UDim2.new(0, 820, 0, 28)
TextLabel.Font = Enum.Font.SourceSans
TextLabel.Text = "Bot Hub"
TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.TextSize = 20.000
TextLabel.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)

Premuim.Name = "Premuim"
Premuim.Parent = Frame
Premuim.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Premuim.BackgroundTransparency = 1.000
Premuim.Position = UDim2.new(0.55282557, 0, -0.00278551527, 0)
Premuim.Size = UDim2.new(0, 30, 0, 28)
Premuim.Image = "http://www.roblox.com/asset/?id=10395263188"

Frame_2.Parent = Frame
Frame_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Frame_2.BackgroundTransparency = 1.000
Frame_2.Position = UDim2.new(0.0814159289, 0, 0.600000024, 0)
Frame_2.Size = UDim2.new(0, 114, 0, 145)

PlayerImage.Name = "PlayerImage"
PlayerImage.Parent = Frame_2
PlayerImage.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
PlayerImage.BackgroundTransparency = 1.000
PlayerImage.Position = UDim2.new(0.307017565, 0, 0.732316494, 0)
PlayerImage.Size = UDim2.new(0, 24, 0, 24)
PlayerImage.Image = "rbxasset://textures/ui/GuiImagePlaceholder.png"

UICorner_9.CornerRadius = UDim.new(12222222, 0)
UICorner_9.Parent = PlayerImage

PlayerName.Name = "PlayerName"
PlayerName.Parent = Frame_2
PlayerName.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
PlayerName.BackgroundTransparency = 1.000
PlayerName.Position = UDim2.new(0, 69, 0, 108)
PlayerName.Size = UDim2.new(0, 119, 0, 19)
PlayerName.Font = Enum.Font.Ubuntu
PlayerName.TextColor3 = Color3.fromRGB(255, 255, 255)
PlayerName.TextScaled = true
PlayerName.TextSize = 22.000
PlayerName.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
PlayerName.TextWrapped = true

UITextSizeConstraint.Parent = PlayerName
UITextSizeConstraint.MaxTextSize = 20

Petsimx.Name = "Petsimx"
Petsimx.Parent = Frame
Petsimx.BackgroundColor3 = Color3.fromRGB(63, 63, 63)
Petsimx.BorderColor3 = Color3.fromRGB(27, 42, 53)
Petsimx.Position = UDim2.new(0, 101, 0, 11)
Petsimx.Size = UDim2.new(0.103194103, 0, 0.111398965, 0)
Petsimx.Style = Enum.ButtonStyle.RobloxButton
Petsimx.Font = Enum.Font.SourceSansBold
Petsimx.Text = "Pet sim "
Petsimx.TextColor3 = Color3.fromRGB(255, 255, 255)
Petsimx.TextSize = 15.000
Petsimx.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
Petsimx.MouseButton1Down:Connect(function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/ZaRdoOx/Ultra-Hub/main/Pet-Simulator-X"))()
end)
UICorner_10.Parent = Petsimx

Trollingui.Name = "Trollingui"
Trollingui.Parent = Frame
Trollingui.BackgroundColor3 = Color3.fromRGB(63, 63, 63)
Trollingui.BorderColor3 = Color3.fromRGB(27, 42, 53)
Trollingui.Position = UDim2.new(0, 101, 0, 57)
Trollingui.Size = UDim2.new(0.103194103, 0, 0.111398965, 0)
Trollingui.Style = Enum.ButtonStyle.RobloxButton
Trollingui.Font = Enum.Font.SourceSansBold
Trollingui.Text = "Trolling gui"
Trollingui.TextColor3 = Color3.fromRGB(255, 255, 255)
Trollingui.TextSize = 15.000
Trollingui.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
Trollingui.MouseButton1Down:Connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/killermaster9999mega/UTG-V3/main/FE%20UTG%20V3.txt"))()
end)
UICorner_11.Parent = Trollingui

TappingSim.Name = "TappingSim"
TappingSim.Parent = Frame
TappingSim.BackgroundColor3 = Color3.fromRGB(63, 63, 63)
TappingSim.BorderColor3 = Color3.fromRGB(27, 42, 53)
TappingSim.Position = UDim2.new(0, 101, 0, 108)
TappingSim.Size = UDim2.new(0.103194103, 0, 0.111398965, 0)
TappingSim.Style = Enum.ButtonStyle.RobloxButton
TappingSim.Font = Enum.Font.SourceSansBold
TappingSim.Text = "Tapping Sim"
TappingSim.TextColor3 = Color3.fromRGB(255, 255, 255)
TappingSim.TextSize = 15.000
TappingSim.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
TappingSim.MouseButton1Down:Connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/Blukez/Scripts/main/UTG%20V3%20RAW"))()
end)
UICorner_12.Parent = TappingSim

UIAspectRatioConstraint.Parent = BotHub
UIAspectRatioConstraint.AspectRatio = 1.910

Autoreport.Name = "Auto report"
Autoreport.Parent = Frame
Autoreport.BackgroundColor3 = Color3.fromRGB(63, 63, 63)
Autoreport.BorderColor3 = Color3.fromRGB(27, 42, 53)
Autoreport.Position = UDim2.new(0, 101, 0, 157)
Autoreport.Size = UDim2.new(0.103194103, 0, 0.111398965, 0)
Autoreport.Style = Enum.ButtonStyle.RobloxButton
Autoreport.Font = Enum.Font.SourceSansBold
Autoreport.Text = "Auto Report"
Autoreport.TextColor3 = Color3.fromRGB(255, 255, 255)
Autoreport.TextSize = 15.000
Autoreport.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
Autoreport.MouseButton1Down:Connect(function()
loadstring(game:HttpGet('https://raw.githubusercontent.com/joeengo/Future/main/loadstring.lua', true))()
end)
UICorner_13.Parent = Autoreport

Arsenal.Name = "Arsenal"
Arsenal.Parent = Frame
Arsenal.BackgroundColor3 = Color3.fromRGB(63, 63, 63)
Arsenal.BorderColor3 = Color3.fromRGB(27, 42, 53)
Arsenal.Position = UDim2.new(0, 101, 0, 213)
Arsenal.Size = UDim2.new(0.103194103, 0, 0.111398965, 0)
Arsenal.Style = Enum.ButtonStyle.RobloxButton
Arsenal.Font = Enum.Font.SourceSansBold
Arsenal.Text = "Arsenal"
Arsenal.TextColor3 = Color3.fromRGB(255, 255, 255)
Arsenal.TextSize = 15.000
Arsenal.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
Arsenal.MouseButton1Down:Connect(function()
loadstring(game:HttpGet('https://raw.githubusercontent.com/fusiongreg/BoltsHubV5/main/Main', true))()
end)
UICorner_14.Parent = Arsenal

Grabknife.Name = "Grab knife"
Grabknife.Parent = Frame
Grabknife.BackgroundColor3 = Color3.fromRGB(63, 63, 63)
Grabknife.BorderColor3 = Color3.fromRGB(27, 42, 53)
Grabknife.Position = UDim2.new(0, 101, 0, 263)
Grabknife.Size = UDim2.new(0.103194103, 0, 0.111398965, 0)
Grabknife.Style = Enum.ButtonStyle.RobloxButton
Grabknife.Font = Enum.Font.SourceSansBold
Grabknife.Text = "Grab Knife [FE]"
Grabknife.TextColor3 = Color3.fromRGB(255, 255, 255)
Grabknife.TextSize = 14.000
Grabknife.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
Grabknife.MouseButton1Down:Connect(function()
loadstring(game:HttpGet('https://raw.githubusercontent.com/EnzoDark0/EnzoDark0/517da2533882998a020b3ed9d032fdb3652b00dd/WORKING%20Grabknifv4.txt', true))()
end)
UICorner_15.Parent = Grabknife


UIAspectRatioConstraint.Parent = BotHub
UIAspectRatioConstraint.AspectRatio = 1.910
-- Scripts:

local function MLLCO_fake_script() -- Frame_2.LocalScript 
	local script = Instance.new('LocalScript', Frame_2)

	local frame = script.Parent
	
	
	
	local player = game.Players.LocalPlayer
	
	
	
	local userId = player.UserId
	
	local thumbType = Enum.ThumbnailType.AvatarBust
	
	local thumbSize = Enum.ThumbnailSize.Size420x420
	
	local content, isReady = game.Players:GetUserThumbnailAsync(userId, thumbType, thumbSize)

	
	
	
	
	frame.PlayerImage.Image = content
	
	frame.PlayerName.Text = player.Name
	
end
coroutine.wrap(MLLCO_fake_script)()

Frame.Active = true
Frame.Draggable = true  
