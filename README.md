local ScreenGui = Instance.new("ScreenGui")
local ImageLabelUI = Instance.new("ImageLabel")
local Frame = Instance.new("Frame")
local ImageLabel = Instance.new("ImageLabel")
local Frame_2 = Instance.new("Frame")
local ImageLabel_2 = Instance.new("ImageLabel")
local Frame_3 = Instance.new("Frame")
local TextLabel = Instance.new("TextLabel")
local TextLabel_2 = Instance.new("TextLabel")
local TextLabel_3 = Instance.new("TextLabel")
local dot = Instance.new("TextButton")
local Frame_4 = Instance.new("Frame")
local toggla = Instance.new("ImageButton")

--Properties:

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

ImageLabelUI.Name = "ImageLabelUI"
ImageLabelUI.Parent = ScreenGui
ImageLabelUI.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
ImageLabelUI.BorderColor3 = Color3.fromRGB(0, 0, 0)
ImageLabelUI.BorderSizePixel = 0
ImageLabelUI.Position = UDim2.new(0.393514127, 0, 0.293675601, 0)
ImageLabelUI.Size = UDim2.new(0, 212, 0, 176)
ImageLabelUI.Image = "rbxassetid://6071575925"
ImageLabelUI.ImageColor3 = Color3.fromRGB(56, 56, 56)

Frame.Parent = ImageLabelUI
Frame.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
Frame.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame.BorderSizePixel = 0
Frame.Position = UDim2.new(0.497409463, 0, 0.158192083, 0)
Frame.Size = UDim2.new(0, 97, 0, 133)

ImageLabel.Parent = Frame
ImageLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageLabel.BackgroundTransparency = 1.000
ImageLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
ImageLabel.BorderSizePixel = 0
ImageLabel.Size = UDim2.new(0, 97, 0, 133)
ImageLabel.Image = "rbxassetid://5553946656"
ImageLabel.ImageColor3 = Color3.fromRGB(56, 56, 56)

Frame_2.Parent = ImageLabelUI
Frame_2.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
Frame_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame_2.BorderSizePixel = 0
Frame_2.Position = UDim2.new(0.0377358496, 0, 0.158192083, 0)
Frame_2.Size = UDim2.new(0, 91, 0, 100)

ImageLabel_2.Parent = Frame_2
ImageLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageLabel_2.BackgroundTransparency = 1.000
ImageLabel_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
ImageLabel_2.BorderSizePixel = 0
ImageLabel_2.Position = UDim2.new(0, 0, -0.00999999978, 0)
ImageLabel_2.Size = UDim2.new(0, 91, 0, 100)
ImageLabel_2.Image = "rbxassetid://5553946656"
ImageLabel_2.ImageColor3 = Color3.fromRGB(56, 56, 56)

Frame_3.Parent = ImageLabelUI
Frame_3.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Frame_3.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame_3.BorderSizePixel = 0
Frame_3.Position = UDim2.new(0, 0, 0.152542368, 0)
Frame_3.Size = UDim2.new(0, 212, 0, 1)

TextLabel.Parent = ImageLabelUI
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.BorderSizePixel = 0
TextLabel.Position = UDim2.new(0.0613207556, 0, 0.152542368, 0)
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

TextLabel_3.Parent = ImageLabelUI
TextLabel_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_3.BackgroundTransparency = 1.000
TextLabel_3.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_3.BorderSizePixel = 0
TextLabel_3.Position = UDim2.new(0.533018887, 0, 0.146860644, 0)
TextLabel_3.Size = UDim2.new(0, 81, 0, 22)
TextLabel_3.Font = Enum.Font.Unknown
TextLabel_3.Text = "Soon"
TextLabel_3.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_3.TextSize = 14.000

dot.Name = "dot"
dot.Parent = ImageLabelUI
dot.BackgroundColor3 = Color3.fromRGB(80, 80, 80)
dot.BorderColor3 = Color3.fromRGB(0, 0, 0)
dot.BorderSizePixel = 0
dot.Position = UDim2.new(0.0518867932, 0, 0.276643574, 0)
dot.Size = UDim2.new(0, 85, 0, 15)
dot.Font = Enum.Font.SourceSans
dot.Text = "Dot"
dot.TextColor3 = Color3.fromRGB(255, 255, 255)
dot.TextSize = 14.000

Frame_4.Parent = ScreenGui
Frame_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Frame_4.BackgroundTransparency = 1.000
Frame_4.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame_4.BorderSizePixel = 0
Frame_4.Position = UDim2.new(0.157466888, 0, 0.244336575, 0)
Frame_4.Size = UDim2.new(0, -1, 0, 100)

toggla.Name = "toggla"
toggla.Parent = Frame_4
toggla.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
toggla.BorderColor3 = Color3.fromRGB(0, 0, 0)
toggla.BorderSizePixel = 0
toggla.Position = UDim2.new(-44.0000076, 0, -0.360000014, 0)
toggla.Size = UDim2.new(0, 36, 0, 37)
toggla.Image = "rbxassetid://16588217582"

-- Scripts:

local function LRNE_fake_script() -- dot.LocalScript 
	local script = Instance.new('LocalScript', dot)

	dot.MouseButton1Click:Connect(function()
		loadstring(game:HttpGet("https://pastefy.app/bAftFejN/raw", true))()
	end)
	
end
coroutine.wrap(LRNE_fake_script)()
local function YTZOXLB_fake_script() -- toggla.LocalScript 
	local script = Instance.new('LocalScript', toggla)

	local toggla = script.Parent
	
	toggla.MouseButton1Click:connect(function()
		local ImageLabelUi = 
			toggla.Parent.Parent.ImageLabelUI
		 ImageLabelUi.Visible = not ImageLabelUi.Visible
	end)
	
end
coroutine.wrap(YTZOXLB_fake_script)()
