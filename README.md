-- Gui to Lua
-- Version: 3.2

-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local Frame_2 = Instance.new("Frame")
local ImageLabel = Instance.new("ImageLabel")
local TextBox = Instance.new("TextBox")
local ImageLabel1 = Instance.new("ImageLabel")
local ScrollingFrame = Instance.new("ScrollingFrame")
local Execute = Instance.new("TextButton")
local Clear = Instance.new("TextButton")
local Attach = Instance.new("TextButton")
local Load = Instance.new("TextButton")
local Save = Instance.new("TextButton")
local KillRoblox = Instance.new("TextButton")
local TextLabel = Instance.new("TextLabel")
local TextLabel1 = Instance.new("TextLabel")
local Close = Instance.new("TextButton")

--Properties:

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.fromRGB(0, 0, 255)
Frame.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame.BorderSizePixel = 0
Frame.Position = UDim2.new(0.120751992, 0, 0.136227533, 0)
Frame.Size = UDim2.new(0, 584, 0, 267)

Frame_2.Parent = Frame
Frame_2.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Frame_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame_2.BorderSizePixel = 0
Frame_2.Position = UDim2.new(0, 0, 0.187594175, 0)
Frame_2.Size = UDim2.new(0, 584, 0, 216)

ImageLabel.Parent = Frame_2
ImageLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
ImageLabel.BorderSizePixel = 0
ImageLabel.Position = UDim2.new(0, 10, 0, 10)
ImageLabel.Size = UDim2.new(0, 420, 0, 167)
ImageLabel.Image = "rbxassetid://112430682269451"

TextBox.Parent = Frame_2
TextBox.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextBox.BackgroundTransparency = 1.000
TextBox.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextBox.BorderSizePixel = 0
TextBox.Position = UDim2.new(0.0171232875, 0, 0.0462962948, 0)
TextBox.Size = UDim2.new(0, 420, 0, 167)
TextBox.Font = Enum.Font.SourceSansBold
TextBox.Text = ""
TextBox.TextColor3 = Color3.fromRGB(0, 0, 255)
TextBox.TextSize = 14.000
TextBox.TextWrapped = true
TextBox.TextXAlignment = Enum.TextXAlignment.Left
TextBox.TextYAlignment = Enum.TextYAlignment.Top

ImageLabel1.Name = "ImageLabel1"
ImageLabel1.Parent = Frame_2
ImageLabel1.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageLabel1.BorderColor3 = Color3.fromRGB(0, 0, 0)
ImageLabel1.BorderSizePixel = 0
ImageLabel1.Position = UDim2.new(0.75, 0, 0.0462962948, 0)
ImageLabel1.Size = UDim2.new(0, 138, 0, 167)
ImageLabel1.Image = "rbxassetid://124499349840358"

ScrollingFrame.Parent = Frame_2
ScrollingFrame.Active = true
ScrollingFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ScrollingFrame.BackgroundTransparency = 1.000
ScrollingFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScrollingFrame.BorderSizePixel = 0
ScrollingFrame.Position = UDim2.new(0.75, 0, 0.0462962948, 0)
ScrollingFrame.Size = UDim2.new(0, 138, 0, 167)

Execute.Name = "Execute"
Execute.Parent = Frame_2
Execute.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Execute.BorderColor3 = Color3.fromRGB(255, 255, 255)
Execute.Position = UDim2.new(0, 0, 0.842592597, 0)
Execute.Size = UDim2.new(0, 90, 0, 34)
Execute.Font = Enum.Font.SourceSansBold
Execute.Text = "Execute"
Execute.TextColor3 = Color3.fromRGB(0, 0, 255)
Execute.TextSize = 16.000

Clear.Name = "Clear"
Clear.Parent = Frame_2
Clear.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Clear.BorderColor3 = Color3.fromRGB(255, 255, 255)
Clear.Position = UDim2.new(0.19178082, 0, 0.842592597, 0)
Clear.Size = UDim2.new(0, 65, 0, 34)
Clear.Font = Enum.Font.SourceSansBold
Clear.Text = "Clear"
Clear.TextColor3 = Color3.fromRGB(0, 0, 255)
Clear.TextSize = 16.000

Attach.Name = "Attach"
Attach.Parent = Frame_2
Attach.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Attach.BorderColor3 = Color3.fromRGB(255, 255, 255)
Attach.Position = UDim2.new(0.871575356, 0, 0.842592597, 0)
Attach.Size = UDim2.new(0, 75, 0, 34)
Attach.Font = Enum.Font.SourceSansBold
Attach.Text = "Attach"
Attach.TextColor3 = Color3.fromRGB(0, 0, 255)
Attach.TextSize = 16.000

Load.Name = "Load"
Load.Parent = Frame_2
Load.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Load.BorderColor3 = Color3.fromRGB(255, 255, 255)
Load.Position = UDim2.new(0.777397275, 0, 0.842592597, 0)
Load.Size = UDim2.new(0, 44, 0, 34)
Load.Font = Enum.Font.SourceSansBold
Load.Text = "Load"
Load.TextColor3 = Color3.fromRGB(0, 0, 255)
Load.TextSize = 16.000

Save.Name = "Save"
Save.Parent = Frame_2
Save.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Save.BorderColor3 = Color3.fromRGB(255, 255, 255)
Save.Position = UDim2.new(0.635273993, 0, 0.842592597, 0)
Save.Size = UDim2.new(0, 67, 0, 34)
Save.Font = Enum.Font.SourceSansBold
Save.Text = "Save"
Save.TextColor3 = Color3.fromRGB(0, 0, 255)
Save.TextSize = 16.000

KillRoblox.Name = "Kill Roblox"
KillRoblox.Parent = Frame_2
KillRoblox.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
KillRoblox.BorderColor3 = Color3.fromRGB(255, 255, 255)
KillRoblox.Position = UDim2.new(0.416095883, 0, 0.842592597, 0)
KillRoblox.Size = UDim2.new(0, 87, 0, 34)
KillRoblox.Font = Enum.Font.SourceSansBold
KillRoblox.Text = "Kill Roblox"
KillRoblox.TextColor3 = Color3.fromRGB(0, 0, 255)
KillRoblox.TextSize = 16.000

TextLabel.Parent = Frame
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.BorderSizePixel = 0
TextLabel.Position = UDim2.new(0.0736301392, 0, 0, 0)
TextLabel.Size = UDim2.new(0, 200, 0, 50)
TextLabel.Font = Enum.Font.Unknown
TextLabel.Text = "Sabuza1M"
TextLabel.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.TextSize = 20.000

TextLabel1.Name = "TextLabel1"
TextLabel1.Parent = Frame
TextLabel1.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel1.BackgroundTransparency = 1.000
TextLabel1.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel1.BorderSizePixel = 0
TextLabel1.Position = UDim2.new(0.457191795, 0, 0, 0)
TextLabel1.Size = UDim2.new(0, 200, 0, 50)
TextLabel1.Font = Enum.Font.Unknown
TextLabel1.Text = "Private Edition"
TextLabel1.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel1.TextSize = 20.000

Close.Name = "Close"
Close.Parent = Frame
Close.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Close.BackgroundTransparency = 1.000
Close.BorderColor3 = Color3.fromRGB(0, 0, 0)
Close.BorderSizePixel = 0
Close.Position = UDim2.new(0.871575356, 0, 0, 0)
Close.Size = UDim2.new(0, 75, 0, 50)
Close.Font = Enum.Font.SourceSansBold
Close.Text = "X"
Close.TextColor3 = Color3.fromRGB(0, 0, 0)
Close.TextSize = 30.000

-- Scripts:

local function OTZORP_fake_script() -- Execute.LocalScript 
	local script = Instance.new('LocalScript', Execute)

	local button = script.Parent
	local textbox = script.Parent.Parent.TextBox
	button.MouseButton1Click:Connect(function()
		loadstring(textbox.Text)()
	end)
end
coroutine.wrap(OTZORP_fake_script)()
local function EHGRMU_fake_script() -- Clear.LocalScript1 
	local script = Instance.new('LocalScript', Clear)

	local button = script.Parent
	local textbox = script.Parent.Parent.TextBox
	button.MouseButton1Click:Connect(function()
		textbox.Text = ""
	end)
end
coroutine.wrap(EHGRMU_fake_script)()
local function LXGMIO_fake_script() -- Close.LocalScript 
	local script = Instance.new('LocalScript', Close)

	
		script.Parent.MouseButton1Click:Connect(function()
			script.Parent.Parent.Visible = false 
		end)
	
	
end
coroutine.wrap(LXGMIO_fake_script)()
local function XSMHYOM_fake_script() -- Frame.LocalScript 
	local script = Instance.new('LocalScript', Frame)

	local UserInputService = game:GetService("UserInputService")
	
	local gui = script.Parent
	
	local dragging
	local dragInput
	local dragStart
	local startPos
	
	local function update(input)
		local delta = input.Position - dragStart
		gui.Position = UDim2.new(startPos.X.Scale, startPos.X.Offset + delta.X, startPos.Y.Scale, startPos.Y.Offset + delta.Y)
	end
	
	gui.InputBegan:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch then
			dragging = true
			dragStart = input.Position
			startPos = gui.Position
			
			input.Changed:Connect(function()
				if input.UserInputState == Enum.UserInputState.End then
					dragging = false
				end
			end)
		end
	end)
	
	gui.InputChanged:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
			dragInput = input
		end
	end)
	
	UserInputService.InputChanged:Connect(function(input)
		if input == dragInput and dragging then
			update(input)
		end
	end)
end
coroutine.wrap(XSMHYOM_fake_script)()
