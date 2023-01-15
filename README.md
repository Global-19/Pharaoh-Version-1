-- Pharaoh V1 Script and Gui Made By Barak A. Global#5515 (Krypt Pyramid Script)
-- Early Beta (Testing Only)
-- Coding Language (LUA)

-- Instances:

local Pharoahv1 = Instance.new("ScreenGui")
local main = Instance.new("Frame")
local TextLabel = Instance.new("TextLabel")
local TaserBypass = Instance.new("TextButton")
local CriminalBase = Instance.new("TextButton")
local Neutral = Instance.new("TextButton")
local Criminal = Instance.new("TextButton")
local TextLabel_2 = Instance.new("TextLabel")
local Teleports = Instance.new("TextLabel")
local Nexus = Instance.new("TextButton")
local Yard = Instance.new("TextButton")
local LunchRoom = Instance.new("TextButton")
local TextLabel_3 = Instance.new("TextLabel")
local TextLabel_4 = Instance.new("TextLabel")
local Police = Instance.new("TextButton")
local Sewer = Instance.new("TextButton")
local OutsidePrison = Instance.new("TextButton")
local PoliceRoom = Instance.new("TextButton")
local RemoveDoors = Instance.new("TextButton")
local GiveM4 = Instance.new("TextButton")
local GiveRemington = Instance.new("TextButton")
local GiveM9 = Instance.new("TextButton")
local GiveAk = Instance.new("TextButton")
local CrashServer = Instance.new("TextButton")
local Pyramid = Instance.new("TextButton")
local ArrestCrims = Instance.new("TextButton")
local Close = Instance.new("TextButton")
local Inmates = Instance.new("TextButton")
local TextLabel_5 = Instance.new("TextLabel")
local OnePunch = Instance.new("TextButton")
local Invisible = Instance.new("TextButton")
local Btools = Instance.new("TextButton")
local Fling = Instance.new("TextButton")
local Open = Instance.new("TextButton")

--Properties:

Pharoahv1.Name = "Pharoah v1"
Pharoahv1.Parent = game.CoreGui
Pharoahv1.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

main.Name = "main"
main.Parent = Pharoahv1
main.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
main.Position = UDim2.new(0.241902828, 0, 0.050343249, 0)
main.Size = UDim2.new(0, 591, 0, 352)
main.Visible = false
main.Active = true
main.Draggable = true

TextLabel.Parent = main
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.Size = UDim2.new(0, 503, 0, 72)
TextLabel.Font = Enum.Font.SciFi
TextLabel.Text = "Pharaoh v1"
TextLabel.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.TextSize = 30.000

TaserBypass.Name = "Taser Bypass"
TaserBypass.Parent = main
TaserBypass.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TaserBypass.Position = UDim2.new(0.214165241, 0, 0.319571137, 0)
TaserBypass.Size = UDim2.new(0, 161, 0, 27)
TaserBypass.Font = Enum.Font.SourceSans
TaserBypass.Text = "Taser Bypass"
TaserBypass.TextColor3 = Color3.fromRGB(0, 0, 0)
TaserBypass.TextSize = 14.000

CriminalBase.Name = "Criminal Base"
CriminalBase.Parent = main
CriminalBase.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
CriminalBase.Position = UDim2.new(0.740668118, 0, 0.708764076, 0)
CriminalBase.Size = UDim2.new(0, 153, 0, 23)
CriminalBase.Font = Enum.Font.SourceSans
CriminalBase.Text = "Criminal Base"
CriminalBase.TextColor3 = Color3.fromRGB(0, 0, 0)
CriminalBase.TextSize = 14.000
CriminalBase.MouseButton1Down:connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-943, 96, 2055)
end)

Neutral.Name = "Neutral"
Neutral.Parent = main
Neutral.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Neutral.Position = UDim2.new(0, 0, 0.398086548, 0)
Neutral.Size = UDim2.new(0, 125, 0, 34)
Neutral.Font = Enum.Font.SourceSans
Neutral.Text = "NEUTRAL"
Neutral.TextColor3 = Color3.fromRGB(0, 0, 0)
Neutral.TextSize = 14.000
Neutral.MouseButton1Down:connect(function()
	Workspace.Remote.TeamEvent:FireServer("Medium stone grey")
end)

Criminal.Name = "Criminal"
Criminal.Parent = main
Criminal.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Criminal.Position = UDim2.new(0, 0, 0.494677454, 0)
Criminal.Size = UDim2.new(0, 125, 0, 29)
Criminal.Font = Enum.Font.SourceSans
Criminal.Text = "CRIMINAL"
Criminal.TextColor3 = Color3.fromRGB(0, 0, 0)
Criminal.TextSize = 14.000
Criminal.MouseButton1Down:connect(function()
	weld02 = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-919.958, 95.327, 2138.189)
	wait(0.075)
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(weld02)
end)

TextLabel_2.Parent = main
TextLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.Position = UDim2.new(0, 0, 0.776945889, 0)
TextLabel_2.Size = UDim2.new(0, 289, 0, 78)
TextLabel_2.Font = Enum.Font.SourceSans
TextLabel_2.Text = "Script and Gui Made By SimsFileShare Global#5515"
TextLabel_2.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_2.TextSize = 15.000

Teleports.Name = "Teleports"
Teleports.Parent = main
Teleports.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Teleports.Position = UDim2.new(0.740667999, 0, 0.20413886, 0)
Teleports.Size = UDim2.new(0, 153, 0, 36)
Teleports.Font = Enum.Font.SourceSans
Teleports.Text = "TELEPORTS, MORE SOON!"
Teleports.TextColor3 = Color3.fromRGB(0, 0, 0)
Teleports.TextSize = 14.000

Nexus.Name = "Nexus"
Nexus.Parent = main
Nexus.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Nexus.Position = UDim2.new(0.740668118, 0, 0.306411564, 0)
Nexus.Size = UDim2.new(0, 152, 0, 23)
Nexus.Font = Enum.Font.SourceSans
Nexus.Text = "Nexus"
Nexus.TextColor3 = Color3.fromRGB(0, 0, 0)
Nexus.TextSize = 14.000
Nexus.MouseButton1Down:connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(918, 97.73, 2447)
end)

Yard.Name = "Yard"
Yard.Parent = main
Yard.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Yard.Position = UDim2.new(0.740668118, 0, 0.372518361, 0)
Yard.Size = UDim2.new(0, 152, 0, 24)
Yard.Font = Enum.Font.SourceSans
Yard.Text = "Yard"
Yard.TextColor3 = Color3.fromRGB(0, 0, 0)
Yard.TextSize = 14.000
Yard.MouseButton1Down:connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(779.092, 96.001, 2451.114)
end)

LunchRoom.Name = "Lunch Room"
LunchRoom.Parent = main
LunchRoom.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
LunchRoom.Position = UDim2.new(0.740667939, 0, 0.439587295, 0)
LunchRoom.Size = UDim2.new(0, 153, 0, 24)
LunchRoom.Font = Enum.Font.SourceSans
LunchRoom.Text = "Lunch Room"
LunchRoom.TextColor3 = Color3.fromRGB(0, 0, 0)
LunchRoom.TextSize = 14.000
LunchRoom.MouseButton1Down:connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(930, 97.54, 2291)
end)

TextLabel_3.Parent = main
TextLabel_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_3.Position = UDim2.new(0.214165241, 0, 0.204545453, 0)
TextLabel_3.Size = UDim2.new(0, 309, 0, 40)
TextLabel_3.Font = Enum.Font.SourceSans
TextLabel_3.Text = "RANDOM"
TextLabel_3.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_3.TextSize = 14.000

TextLabel_4.Parent = main
TextLabel_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_4.Position = UDim2.new(0, 0, 0.206979752, 0)
TextLabel_4.Size = UDim2.new(0, 125, 0, 67)
TextLabel_4.Font = Enum.Font.SourceSans
TextLabel_4.Text = "TEAM CHANGE"
TextLabel_4.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_4.TextSize = 14.000

Police.Name = "Police"
Police.Parent = main
Police.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Police.Position = UDim2.new(0, 0, 0.577063799, 0)
Police.Size = UDim2.new(0, 125, 0, 33)
Police.Font = Enum.Font.SourceSans
Police.Text = "POLICE"
Police.TextColor3 = Color3.fromRGB(0, 0, 0)
Police.TextSize = 14.000
Police.MouseButton1Down:connect(function()
	Workspace.Remote.TeamEvent:FireServer("Bright blue")
end)

Sewer.Name = "Sewer"
Sewer.Parent = main
Sewer.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Sewer.Position = UDim2.new(0.740667939, 0, 0.507431507, 0)
Sewer.Size = UDim2.new(0, 153, 0, 24)
Sewer.Font = Enum.Font.SourceSans
Sewer.Text = "Sewer"
Sewer.TextColor3 = Color3.fromRGB(0, 0, 0)
Sewer.TextSize = 14.000
Sewer.MouseButton1Down:connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(917.174, 76.406, 2426.199)
end)

OutsidePrison.Name = "Outside Prison"
OutsidePrison.Parent = main
OutsidePrison.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
OutsidePrison.Position = UDim2.new(0.740667999, 0, 0.576605558, 0)
OutsidePrison.Size = UDim2.new(0, 153, 0, 24)
OutsidePrison.Font = Enum.Font.SourceSans
OutsidePrison.Text = "Outside Prison"
OutsidePrison.TextColor3 = Color3.fromRGB(0, 0, 0)
OutsidePrison.TextSize = 14.000
OutsidePrison.MouseButton1Down:connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(288.452, 69.999, 2206.731)
end)

PoliceRoom.Name = "Police Room"
PoliceRoom.Parent = main
PoliceRoom.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
PoliceRoom.Position = UDim2.new(0.740667999, 0, 0.642604828, 0)
PoliceRoom.Size = UDim2.new(0, 153, 0, 24)
PoliceRoom.Font = Enum.Font.SourceSans
PoliceRoom.Text = "Police Room"
PoliceRoom.TextColor3 = Color3.fromRGB(0, 0, 0)
PoliceRoom.TextSize = 14.000
PoliceRoom.MouseButton1Down:connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(834.972, 99.989, 2275.318)
end)

RemoveDoors.Name = "Remove Doors"
RemoveDoors.Parent = main
RemoveDoors.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
RemoveDoors.Position = UDim2.new(0.488476038, 0, 0.319571137, 0)
RemoveDoors.Size = UDim2.new(0, 147, 0, 26)
RemoveDoors.Font = Enum.Font.SourceSans
RemoveDoors.Text = "Remove Doors"
RemoveDoors.TextColor3 = Color3.fromRGB(0, 0, 0)
RemoveDoors.TextSize = 14.000
RemoveDoors.MouseButton1Down:connect(function()
	game.Workspace.Doors:Destroy()
end)

GiveM4.Name = "Give M4"
GiveM4.Parent = main
GiveM4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
GiveM4.Position = UDim2.new(0.214165241, 0, 0.398086548, 0)
GiveM4.Size = UDim2.new(0, 161, 0, 23)
GiveM4.Font = Enum.Font.SourceSans
GiveM4.Text = "Give M4"
GiveM4.TextColor3 = Color3.fromRGB(0, 0, 0)
GiveM4.TextSize = 14.000
GiveM4.MouseButton1Down:connect(function()
	local M4A1 = {"M4A1"}
	for i, v in pairs(game.Workspace["Prison_ITEMS"].giver:GetChildren()) do
		for j, k in pairs(M4A1) do
			if v.Name == k then
				v:MoveTo(game.Players.LocalPlayer.Character.Torso.Position)
			end
		end
	end
end)

GiveRemington.Name = "Give Remington"
GiveRemington.Parent = main
GiveRemington.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
GiveRemington.Position = UDim2.new(0.491158158, 0, 0.398086548, 0)
GiveRemington.Size = UDim2.new(0, 146, 0, 23)
GiveRemington.Font = Enum.Font.SourceSans
GiveRemington.Text = "Give Remington"
GiveRemington.TextColor3 = Color3.fromRGB(0, 0, 0)
GiveRemington.TextSize = 14.000
GiveRemington.MouseButton1Down:connect(function()
	local Remington870 = {"Remington 870"}
	for i, v in pairs(game.Workspace["Prison_ITEMS"].giver:GetChildren()) do
		for j, k in pairs(Remington870) do
			if v.Name == k then
				v:MoveTo(game.Players.LocalPlayer.Character.Torso.Position)
			end
		end
	end
end)

GiveM9.Name = "Give M9"
GiveM9.Parent = main
GiveM9.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
GiveM9.Position = UDim2.new(0.214165241, 0, 0.465836972, 0)
GiveM9.Size = UDim2.new(0, 161, 0, 25)
GiveM9.Font = Enum.Font.SourceSans
GiveM9.Text = "GIVE M9"
GiveM9.TextColor3 = Color3.fromRGB(0, 0, 0)
GiveM9.TextSize = 14.000
GiveM9.MouseButton1Down:connect(function()
	local M9 = {"M9"}
	for i, v in pairs(game.Workspace["Prison_ITEMS"].giver:GetChildren()) do
		for j, k in pairs(M9) do
			if v.Name == k then
				v:MoveTo(game.Players.LocalPlayer.Character.Torso.Position)
			end
		end
	end
end)

GiveAk.Name = "Give Ak"
GiveAk.Parent = main
GiveAk.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
GiveAk.Position = UDim2.new(0.491158187, 0, 0.465836942, 0)
GiveAk.Size = UDim2.new(0, 147, 0, 26)
GiveAk.Font = Enum.Font.SourceSans
GiveAk.Text = "Give AK"
GiveAk.TextColor3 = Color3.fromRGB(0, 0, 0)
GiveAk.TextSize = 14.000
GiveAk.MouseButton1Down:connect(function()
	local AK47 = {"AK-47"}
	for i, v in pairs(game.Workspace["Prison_ITEMS"].giver:GetChildren()) do
		for j, k in pairs(AK47) do
			if v.Name == k then
				v:MoveTo(game.Players.LocalPlayer.Character.Torso.Position)
			end
		end
	end
end)

CrashServer.Name = "Crash Server"
CrashServer.Parent = main
CrashServer.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
CrashServer.Position = UDim2.new(0.214165241, 0, 0.538681507, 0)
CrashServer.Size = UDim2.new(0, 162, 0, 83)
CrashServer.Font = Enum.Font.SourceSans
CrashServer.Text = "Crash Server "
CrashServer.TextColor3 = Color3.fromRGB(0, 0, 0)
CrashServer.TextSize = 14.000
CrashServer.MouseButton1Down:connect(function()
	local PackageSize = 10000 -- How many bullets is sent through in one remote call.
	local SendPackageAmountOfTimes = 5 -- How many times the remote should be called.

	local ReplicatedStorage = game:GetService("ReplicatedStorage")
	local Players = game:GetService("Players")
	local LocalPlayer = Players.LocalPlayer

	local ItemHandler = workspace:WaitForChild("Remote").ItemHandler
	local ShootEvent = ReplicatedStorage:WaitForChild("ShootEvent")

	ItemHandler:InvokeServer(workspace.Prison_ITEMS.giver["Remington 870"].ITEMPICKUP)
	local Tool = Players.LocalPlayer.Backpack["Remington 870"]

	local Packet = {
		RayObject = Ray.new(Vector3.new(-1, -1, -1), Vector3.new(1, 1, 1)),
		Distance = 2048,
		Cframe = CFrame.new(0, 0, 0),
		Hit = workspace:FindFirstChildOfClass("Part")
	}

	local Package = {}

	for i = 1, PackageSize do
		Package[i] = Packet
	end

	for i = 1, SendPackageAmountOfTimes do
		ShootEvent:FireServer(Package, Tool)
	end
end)

Pyramid.Name = "Pyramid"
Pyramid.Parent = main
Pyramid.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Pyramid.Position = UDim2.new(0.815566838, 0, 0.890582263, 0)
Pyramid.Size = UDim2.new(0, 109, 0, 38)
Pyramid.Font = Enum.Font.SourceSans
Pyramid.Text = "Pyramid (cred.Krypt)"
Pyramid.TextColor3 = Color3.fromRGB(0, 0, 0)
Pyramid.TextSize = 14.000
Pyramid.MouseButton1Click:connect(function()
	local plr = game.Players.LocalPlayer
	game:GetService("RunService").Stepped:Connect(function()
		setsimulationradius(9e9,9e9)
		plr.ReplicationFocus = workspace
		settings().Physics.AllowSleep = false
	end)

	local runservice=game:service"RunService";
	local player=game:service"Players"["LocalPlayer"];
	local character=player["Character"];
	local blacklisted="Head Torso HumanoidRootPart";
	local limbs={};

	character["Humanoid"].HipHeight=2;
	--character["Head"]:FindFirstChildOfClass"SpecialMesh":Destroy();

	for i,v in next,character:children() do
		if (v.ClassName=="Part") and not blacklisted:find(v.Name) then
			v:BreakJoints();
			limbs[v.Name]=v;
		end
	end

	while runservice["Heartbeat"]:Wait() do
		limbs["Left Leg"].CFrame=character["HumanoidRootPart"].CFrame*CFrame.new(-1,-2,0);
		limbs["Right Leg"].CFrame=character["HumanoidRootPart"].CFrame*CFrame.new(1,-2,0);
		limbs["Left Arm"].CFrame=character["Left Leg"].CFrame*CFrame.new(-1,-2,0);
		limbs["Right Arm"].CFrame=character["Right Leg"].CFrame*CFrame.new(1,-2,0);
	end
end)

ArrestCrims.Name = "Arrest Crims"
ArrestCrims.Parent = main
ArrestCrims.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ArrestCrims.Position = UDim2.new(0.815566838, 0, 0.778409064, 0)
ArrestCrims.Size = UDim2.new(0, 109, 0, 39)
ArrestCrims.Font = Enum.Font.SourceSans
ArrestCrims.Text = "Arrest Crims "
ArrestCrims.TextColor3 = Color3.fromRGB(0, 0, 0)
ArrestCrims.TextSize = 14.000
ArrestCrims.MouseButton1Down:connect(function()
	local Player = game.Players.LocalPlayer
	local cpos = Player.Character.HumanoidRootPart.CFrame
	for i,v in pairs(game.Teams.Criminals:GetPlayers()) do
		if v.Name ~= Player.Name then
			local i = 10
			repeat
				wait()
				i = i-1
				game.Workspace.Remote.arrest:InvokeServer(v.Character.HumanoidRootPart)
				Player.Character.HumanoidRootPart.CFrame = v.Character.HumanoidRootPart.CFrame * CFrame.new(0, 0, 1)
			until i == 0
		end
	end
	Player.Character.HumanoidRootPart.CFrame = cpos
	Notify("you've arrested all crims")
end)

Close.Name = "Close"
Close.Parent = main
Close.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Close.Position = UDim2.new(0.852364123, 0, 0, 0)
Close.Size = UDim2.new(0, 87, 0, 71)
Close.Font = Enum.Font.SourceSans
Close.Text = "CLOSE GUI"
Close.TextColor3 = Color3.fromRGB(0, 0, 0)
Close.TextSize = 14.000

Inmates.Name = "Inmates"
Inmates.Parent = main
Inmates.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Inmates.Position = UDim2.new(0, 0, 0.673716009, 0)
Inmates.Size = UDim2.new(0, 125, 0, 36)
Inmates.Font = Enum.Font.SourceSans
Inmates.Text = "INMATES"
Inmates.TextColor3 = Color3.fromRGB(0, 0, 0)
Inmates.TextSize = 14.000
Inmates.MouseButton1Down:connect(function()
	workspace.Remote.TeamEvent:FireServer("Bright orange")
end)

TextLabel_5.Parent = main
TextLabel_5.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_5.Position = UDim2.new(0.490693748, 0, 0.539700568, 0)
TextLabel_5.Size = UDim2.new(0, 147, 0, 82)
TextLabel_5.Font = Enum.Font.SourceSans
TextLabel_5.Text = "Coming Soon! "
TextLabel_5.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_5.TextSize = 14.000

OnePunch.Name = "One Punch"
OnePunch.Parent = main
OnePunch.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
OnePunch.Position = UDim2.new(0.491158158, 0, 0.776945889, 0)
OnePunch.Size = UDim2.new(0, 99, 0, 40)
OnePunch.Font = Enum.Font.SourceSans
OnePunch.Text = "One Punch"
OnePunch.TextColor3 = Color3.fromRGB(0, 0, 0)
OnePunch.TextSize = 14.000
OnePunch.MouseButton1Down:connect(function()
	mainRemotes = game.ReplicatedStorage meleeRemote = mainRemotes['meleeEvent'] mouse = game.Players.LocalPlayer:GetMouse() punching = false cooldown = false function punch() cooldown = true local part = Instance.new("Part", game.Players.LocalPlayer.Character) part.Transparency = 1 part.Size = Vector3.new(5, 2, 3) part.CanCollide = false local w1 = Instance.new("Weld", part) w1.Part0 = game.Players.LocalPlayer.Character.Torso w1.Part1 = part w1.C1 = CFrame.new(0,0,2) part.Touched:connect(function(hit) if game.Players:FindFirstChild(hit.Parent.Name) then local plr = game.Players:FindFirstChild(hit.Parent.Name) if plr.Name ~= game.Players.LocalPlayer.Name then part:Destroy() for i = 1,100 do meleeRemote:FireServer(plr) end end end end) wait(1) cooldown = false part:Destroy() end mouse.KeyDown:connect(function(key) if cooldown == false then if key:lower() == "f" then punch() end end end)
end)

Invisible.Name = "Invisible"
Invisible.Parent = main
Invisible.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Invisible.Position = UDim2.new(0.490693748, 0, 0.889204562, 0)
Invisible.Size = UDim2.new(0, 99, 0, 38)
Invisible.Font = Enum.Font.SourceSans
Invisible.Text = "Invisible"
Invisible.TextColor3 = Color3.fromRGB(0, 0, 0)
Invisible.TextSize = 14.000
Invisible.MouseButton1Down:connect(function()
	local player = game.Players.LocalPlayer
	position     = player.Character.HumanoidRootPart.Position
	wait(0.1)
	player.Character:MoveTo(position + Vector3.new(0, 1000000, 0))
	wait(0.1)
	humanoidrootpart = player.Character.HumanoidRootPart:clone()
	wait(0.1)
	player.Character.HumanoidRootPart:Destroy()
	humanoidrootpart.Parent = player.Character
	player.Character:MoveTo(position)
	wait()
end)

Btools.Name = "Btools"
Btools.Parent = main
Btools.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Btools.Position = UDim2.new(0.661590517, 0, 0.778409064, 0)
Btools.Size = UDim2.new(0, 91, 0, 39)
Btools.Font = Enum.Font.SourceSans
Btools.Text = "Btools"
Btools.TextColor3 = Color3.fromRGB(0, 0, 0)
Btools.TextSize = 14.000
Btools.MouseButton1Down:connect(function()
	local tool1   = Instance.new("HopperBin",game.Players.LocalPlayer.Backpack)
	tool1.BinType = "Hammer"
end)

Fling.Name = "Fling"
Fling.Parent = main
Fling.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Fling.Position = UDim2.new(0.661590517, 0, 0.890582263, 0)
Fling.Size = UDim2.new(0, 91, 0, 38)
Fling.Font = Enum.Font.SourceSans
Fling.Text = "Fling"
Fling.TextColor3 = Color3.fromRGB(0, 0, 0)
Fling.TextSize = 14.000
Fling.MouseButton1Down:connect(function()
	
       power = 350 -- change this to make it more or less powerful

	game:GetService('RunService').Stepped:connect(function()
		game.Players.LocalPlayer.Character.Head.CanCollide = false
		game.Players.LocalPlayer.Character.Torso.CanCollide = false
		game.Players.LocalPlayer.Character["Left Leg"].CanCollide = false
		game.Players.LocalPlayer.Character["Right Leg"].CanCollide = false
	end)

	wait(.1)
	local bambam = Instance.new("BodyThrust")
	bambam.Parent = game.Players.LocalPlayer.Character.HumanoidRootPart
	bambam.Force = Vector3.new(power,0,power)
	bambam.Location = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
end)

Open.Name = "Open"
Open.Parent = Pharoahv1
Open.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Open.Position = UDim2.new(0.00910931267, 0, 0.855835259, 0)
Open.Size = UDim2.new(0, 200, 0, 50)
Open.Font = Enum.Font.SourceSans
Open.Text = "OPEN "
Open.TextColor3 = Color3.fromRGB(0, 0, 0)
Open.TextSize = 14.000

-- Scripts:

local function FZYHZYN_fake_script() -- Close.LocalScript 
	local script = Instance.new('LocalScript', Close)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.Visible = false
	end)
	
end
coroutine.wrap(FZYHZYN_fake_script)()
local function UCMOFX_fake_script() -- Open.LocalScript 
	local script = Instance.new('LocalScript', Open)

	local frame = script.Parent.Parent.main  
	local open = false
	
	script.Parent.MouseButton1Click:Connect(function()
		if frame.Visible == false then
			frame.Visible = true
		end
	end)
	
	
end
coroutine.wrap(UCMOFX_fake_script)()
