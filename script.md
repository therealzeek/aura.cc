local ScreenGui = Instance.new("ScreenGui")
local ImageLabelUI = Instance.new("ImageLabel")
local Frame = Instance.new("Frame")
local TextLabel = Instance.new("TextLabel")
local TextLabel_2 = Instance.new("TextLabel")
local dot = Instance.new("TextButton")
local textbutton = Instance.new("TextButton")
local TextButton = Instance.new("TextButton")
local TextButton_2 = Instance.new("TextButton")
local hi22 = Instance.new("TextButton")
local Frame_2 = Instance.new("Frame")
local miscUI = Instance.new("ImageLabel")
local TextButton_3 = Instance.new("TextButton")
local TextButton_4 = Instance.new("TextButton")
local TextButton_5 = Instance.new("TextButton")
local hi = Instance.new("TextButton")
local Frame_3 = Instance.new("Frame")
local Frame_4 = Instance.new("Frame")
local TextLabel_3 = Instance.new("TextLabel")
local TextLabel_4 = Instance.new("TextLabel")
local Frame_5 = Instance.new("Frame")
local toggla = Instance.new("ImageButton")

--Properties:

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

ImageLabelUI.Name = "ImageLabelUI"
ImageLabelUI.Parent = ScreenGui
ImageLabelUI.Active = true
ImageLabelUI.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
ImageLabelUI.BorderColor3 = Color3.fromRGB(0, 0, 0)
ImageLabelUI.BorderSizePixel = 0
ImageLabelUI.Position = UDim2.new(0.353474081, 0, 0.27263999, 0)
ImageLabelUI.Size = UDim2.new(0, 236, 0, 195)
ImageLabelUI.Image = "rbxassetid://6073763717"
ImageLabelUI.ImageColor3 = Color3.fromRGB(56, 56, 56)
ImageLabelUI.ScaleType = Enum.ScaleType.Crop

Frame.Parent = ImageLabelUI
Frame.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
Frame.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame.BorderSizePixel = 0
Frame.Position = UDim2.new(0.0514441021, 0, 0.327422947, 0)
Frame.Size = UDim2.new(0, 91, 0, 107)

TextLabel.Parent = ImageLabelUI
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.BorderSizePixel = 0
TextLabel.Position = UDim2.new(0.0706461221, 0, 0.347414136, 0)
TextLabel.Size = UDim2.new(0, 81, 0, 22)
TextLabel.Font = Enum.Font.Unknown
TextLabel.Text = "Aimlocks"
TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.TextSize = 14.000

TextLabel_2.Parent = ImageLabelUI
TextLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.BackgroundTransparency = 1.000
TextLabel_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_2.BorderSizePixel = 0
TextLabel_2.Position = UDim2.new(0.0514444299, 0, -0.00138213416, 0)
TextLabel_2.Size = UDim2.new(0, 139, 0, 27)
TextLabel_2.Font = Enum.Font.SourceSans
TextLabel_2.Text = "Aura.cc Rewrite [whitelisted]"
TextLabel_2.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.TextSize = 14.000

dot.Name = "dot"
dot.Parent = ImageLabelUI
dot.BackgroundColor3 = Color3.fromRGB(80, 80, 80)
dot.BorderColor3 = Color3.fromRGB(0, 0, 0)
dot.BorderSizePixel = 0
dot.Position = UDim2.new(0.0619646497, 0, 0.461258948, 0)
dot.Size = UDim2.new(0, 85, 0, 15)
dot.Font = Enum.Font.SourceSans
dot.Text = "Dot"
dot.TextColor3 = Color3.fromRGB(255, 255, 255)
dot.TextSize = 14.000

textbutton.Name = "textbutton"
textbutton.Parent = ImageLabelUI
textbutton.BackgroundColor3 = Color3.fromRGB(71, 71, 71)
textbutton.BorderColor3 = Color3.fromRGB(0, 0, 0)
textbutton.BorderSizePixel = 0
textbutton.Position = UDim2.new(-0.00300297677, 0, 0.153298408, 0)
textbutton.Size = UDim2.new(0, 55, 0, 25)
textbutton.Font = Enum.Font.Merriweather
textbutton.Text = "Main"
textbutton.TextColor3 = Color3.fromRGB(0, 0, 0)
textbutton.TextSize = 14.000

TextButton.Parent = ImageLabelUI
TextButton.BackgroundColor3 = Color3.fromRGB(71, 71, 71)
TextButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton.BorderSizePixel = 0
TextButton.Position = UDim2.new(0.69856286, 0, 0.153298408, 0)
TextButton.Size = UDim2.new(0, 71, 0, 25)
TextButton.Font = Enum.Font.Merriweather
TextButton.Text = "Cred"
TextButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton.TextSize = 14.000

TextButton_2.Parent = ImageLabelUI
TextButton_2.BackgroundColor3 = Color3.fromRGB(71, 71, 71)
TextButton_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_2.BorderSizePixel = 0
TextButton_2.Position = UDim2.new(0.40040046, 0, 0.153298408, 0)
TextButton_2.Size = UDim2.new(0, 70, 0, 25)
TextButton_2.Font = Enum.Font.Merriweather
TextButton_2.Text = "Rage"
TextButton_2.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton_2.TextSize = 14.000

hi22.Name = "hi22"
hi22.Parent = ImageLabelUI
hi22.BackgroundColor3 = Color3.fromRGB(71, 71, 71)
hi22.BorderColor3 = Color3.fromRGB(0, 0, 0)
hi22.BorderSizePixel = 0
hi22.Position = UDim2.new(0.190905303, 0, 0.153298408, 0)
hi22.Size = UDim2.new(0, 64, 0, 25)
hi22.Font = Enum.Font.Merriweather
hi22.Text = "Misc"
hi22.TextColor3 = Color3.fromRGB(0, 0, 0)
hi22.TextSize = 14.000

Frame_2.Parent = ImageLabelUI
Frame_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Frame_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame_2.BorderSizePixel = 0
Frame_2.Position = UDim2.new(0, 0, 0.152542353, 0)
Frame_2.Size = UDim2.new(0, 236, 0, 1)

miscUI.Name = "miscUI"
miscUI.Parent = ImageLabelUI
miscUI.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
miscUI.BorderColor3 = Color3.fromRGB(0, 0, 0)
miscUI.BorderSizePixel = 0
miscUI.Position = UDim2.new(1.04227948, 0, -0.00159317406, 0)
miscUI.Size = UDim2.new(0, 235, 0, 192)
miscUI.Visible = false
miscUI.Image = "rbxassetid://6073763717"
miscUI.ImageColor3 = Color3.fromRGB(56, 56, 56)

TextButton_3.Parent = miscUI
TextButton_3.BackgroundColor3 = Color3.fromRGB(71, 71, 71)
TextButton_3.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_3.BorderSizePixel = 0
TextButton_3.Position = UDim2.new(0.464151591, 0, 0.16371505, 0)
TextButton_3.Size = UDim2.new(0, 62, 0, 23)
TextButton_3.Font = Enum.Font.Merriweather
TextButton_3.Text = "Rage"
TextButton_3.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton_3.TextSize = 14.000

TextButton_4.Parent = miscUI
TextButton_4.BackgroundColor3 = Color3.fromRGB(71, 71, 71)
TextButton_4.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_4.BorderSizePixel = 0
TextButton_4.Position = UDim2.new(0.228445753, 0, 0.153298378, 0)
TextButton_4.Size = UDim2.new(0, 55, 0, 25)
TextButton_4.Font = Enum.Font.Merriweather
TextButton_4.Text = "Misc"
TextButton_4.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton_4.TextSize = 14.000

TextButton_5.Parent = miscUI
TextButton_5.BackgroundColor3 = Color3.fromRGB(71, 71, 71)
TextButton_5.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_5.BorderSizePixel = 0
TextButton_5.Position = UDim2.new(0.726318121, 0, 0.16371505, 0)
TextButton_5.Size = UDim2.new(0, 55, 0, 23)
TextButton_5.Font = Enum.Font.Merriweather
TextButton_5.Text = "Cred"
TextButton_5.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton_5.TextSize = 14.000

hi.Name = "hi"
hi.Parent = miscUI
hi.BackgroundColor3 = Color3.fromRGB(71, 71, 71)
hi.BorderColor3 = Color3.fromRGB(0, 0, 0)
hi.BorderSizePixel = 0
hi.Position = UDim2.new(-0.00134147482, 0, 0.16371505, 0)
hi.Size = UDim2.new(0, 55, 0, 23)
hi.Font = Enum.Font.Merriweather
hi.Text = "Main"
hi.TextColor3 = Color3.fromRGB(0, 0, 0)
hi.TextSize = 14.000

Frame_3.Parent = miscUI
Frame_3.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
Frame_3.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame_3.BorderSizePixel = 0
Frame_3.Position = UDim2.new(0.0635248721, 0, 0.33263126, 0)
Frame_3.Size = UDim2.new(0, 204, 0, 107)

Frame_4.Parent = miscUI
Frame_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Frame_4.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame_4.BorderSizePixel = 0
Frame_4.Position = UDim2.new(-0.000576847175, 0, 0.162878916, 0)
Frame_4.Size = UDim2.new(0, 236, 0, 1)

TextLabel_3.Parent = miscUI
TextLabel_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_3.BackgroundTransparency = 1.000
TextLabel_3.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_3.BorderSizePixel = 0
TextLabel_3.Position = UDim2.new(0.0466300808, 0, 0.00879414845, 0)
TextLabel_3.Size = UDim2.new(0, 139, 0, 27)
TextLabel_3.Font = Enum.Font.SourceSans
TextLabel_3.Text = "Aura.cc Rewrite [whitelisted]"
TextLabel_3.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_3.TextSize = 14.000

TextLabel_4.Parent = miscUI
TextLabel_4.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
TextLabel_4.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_4.BorderSizePixel = 0
TextLabel_4.Position = UDim2.new(0.0466300808, 0, 0.375293732, 0)
TextLabel_4.Size = UDim2.new(0, 207, 0, 98)
TextLabel_4.Font = Enum.Font.Merriweather
TextLabel_4.Text = "Ill add stuff soon jus dm me @qbds"
TextLabel_4.TextColor3 = Color3.fromRGB(175, 175, 175)
TextLabel_4.TextSize = 14.000

Frame_5.Parent = ScreenGui
Frame_5.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Frame_5.BackgroundTransparency = 1.000
Frame_5.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame_5.BorderSizePixel = 0
Frame_5.Position = UDim2.new(0.157466888, 0, 0.244336575, 0)
Frame_5.Size = UDim2.new(0, -1, 0, 100)

toggla.Name = "toggla"
toggla.Parent = Frame_5
toggla.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
toggla.BorderColor3 = Color3.fromRGB(0, 0, 0)
toggla.BorderSizePixel = 0
toggla.Position = UDim2.new(-44.0000076, 0, -0.360000014, 0)
toggla.Size = UDim2.new(0, 36, 0, 37)
toggla.Image = "rbxassetid://16588217582"

-- Scripts:

local function XENBLA_fake_script() -- dot.LocalScript 
	local script = Instance.new('LocalScript', dot)

	dot.MouseButton1Click:Connect(function()
		loadstring(game:HttpGet("https://pastefy.app/bAftFejN/raw", true))()
	end)
	
end
coroutine.wrap(XENBLA_fake_script)()
local function WYRXVW_fake_script() -- dot.LocalScript 
	local script = Instance.new('LocalScript', dot)

	dot.MouseButton1Click:Connect(function()
		-- Configuration
		local Settings = {
			SmoothingFactor = 0.449,
			MaxLockDistance = 1000,
			PredictionMultiplier = 10,
			PredictionOffset = Vector3.new(0, 0.26, 0) --// (X, Y, Z)
		}
	
		-- Controls
		local Controls = {
			ControllerKey = Enum.KeyCode.ButtonY,
			KeyboardKey = Enum.KeyCode.C,
		}
	
		-- Services
		local UserInputService = game:GetService("UserInputService")
		local RunService = game:GetService("RunService")
	
		-- Variables
		local Camera = game.Workspace.CurrentCamera
		local isTargetLocked = false
		local targetPlayer = nil
	
		-- Functions
		local function FindClosestPlayer()
			local closestDistance = Settings.MaxLockDistance
			local closestPlayer = nil
			local myPosition = game.Players.LocalPlayer.Character.PrimaryPart.Position
			for _, player in pairs(game.Players:GetPlayers()) do
				if player ~= game.Players.LocalPlayer and player.Character and player.Character:FindFirstChild("HumanoidRootPart") then
					local targetPosition = player.Character.PrimaryPart.Position
					local distance = (targetPosition - myPosition).magnitude
					if distance < closestDistance then
						closestDistance = distance
						closestPlayer = player
					end
				end
			end
			return closestPlayer
		end
	
		local function PredictTargetPosition(targetPosition, speed)
			local timeToReachHorizontal = math.abs((targetPosition.X - Camera.CFrame.Position.X) / speed)
			local timeToReachVertical = math.abs((targetPosition.Y - Camera.CFrame.Position.Y) / speed)
			local predictedX = targetPosition.X + targetPlayer.Character.HumanoidRootPart.Velocity.X * timeToReachHorizontal
			local predictedY = targetPosition.Y + targetPlayer.Character.HumanoidRootPart.Velocity.Y * timeToReachVertical
			local predictedZ = targetPosition.Z + targetPlayer.Character.HumanoidRootPart.Velocity.Z * timeToReachHorizontal
			local predictedPosition = Vector3.new(predictedX, predictedY, predictedZ) + Settings.PredictionOffset
			return predictedPosition
		end
	
		-- Additional Function
		local function ShowNotification(playerName)
			game.StarterGui:SetCore("SendNotification", {
				Title = "context.sh",
				Text = "Locked: " .. playerName,
				Duration = 5
			})
		end
	
		-- Input Handlers
		UserInputService.InputBegan:Connect(function(input)
			if input.UserInputType == Enum.UserInputType.Gamepad1 and input.KeyCode == Controls.ControllerKey then
				isTargetLocked = not isTargetLocked
				if isTargetLocked then
					targetPlayer = FindClosestPlayer()
					if targetPlayer then
						ShowNotification(targetPlayer.DisplayName)
					end
				else
					targetPlayer = nil
				end
			elseif input.KeyCode == Controls.KeyboardKey then
				isTargetLocked = not isTargetLocked
				if isTargetLocked then
					targetPlayer = FindClosestPlayer()
					ShowNotification(targetPlayer.DisplayName)
				else
					targetPlayer = nil
				end
			end
		end)
	
		-- Camera Update
		RunService.Heartbeat:Connect(function()
			if isTargetLocked and targetPlayer and targetPlayer.Character and targetPlayer.Character:FindFirstChild("HumanoidRootPart") then
				local targetPosition = targetPlayer.Character.PrimaryPart.Position
				local speed = targetPlayer.Character.Humanoid.WalkSpeed * Settings.PredictionMultiplier
				targetPosition = PredictTargetPosition(targetPosition, speed)
				local cameraPosition = Camera.CFrame.Position
				local offsetDirection = (targetPosition - cameraPosition).unit
				local newCameraPosition = targetPosition - offsetDirection
				Camera.CFrame = Camera.CFrame:Lerp(CFrame.new(newCameraPosition, targetPosition), Settings.SmoothingFactor)
			end
		end)
	end)
	
end
coroutine.wrap(WYRXVW_fake_script)()
local function GMNO_fake_script() -- hi22.LocalScript 
	local script = Instance.new('LocalScript', hi22)

	local hi22 = script.Parent
	
	hi22.MouseButton1Click:connect(function()
		local miscUI = 
			hi22.Parent.Parent.ImageLabelUI
		miscUI.Visible = not ImageLabelUi.Visible
	end)
	
end
coroutine.wrap(GMNO_fake_script)()
local function KSABT_fake_script() -- hi.LocalScript 
	local script = Instance.new('LocalScript', hi)

	local hi = script.Parent
	
	hi.MouseButton1Click:connect(function()
		local ImageLabelUi = 
			hi.Parent.Parent.miscUI
		ImageLabelUi.Visible = not miscUI.Visible
	end)
	
	
end
coroutine.wrap(KSABT_fake_script)()
local function UZEPJC_fake_script() -- toggla.LocalScript 
	local script = Instance.new('LocalScript', toggla)

	local toggla = script.Parent
	
	toggla.MouseButton1Click:connect(function()
		local ImageLabelUi = 
			toggla.Parent.Parent.ImageLabelUI
		 ImageLabelUi.Visible = not ImageLabelUi.Visible
	end)
	
end
coroutine.wrap(UZEPJC_fake_script)()
local function TUFR_fake_script() -- ScreenGui.LocalScript 
	local script = Instance.new('LocalScript', ScreenGui)

	local function createGUI()
		local screenGui =
			Instance.new("ScreenGui")
		screenGui.Parent = 
			game.Players.LocalPlayer:WaitForChild("PlayerGui")
		
	end
	local function ()
		OnPlayerRespawn()
		createGUI()
	end
	
	createGUI()
	
	game.Players.LocalPlayer.CharacterAdded:Connect(OnPlayerRespawn)
end
coroutine.wrap(TUFR_fake_script)()
