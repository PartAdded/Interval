-- Gui to Lua
-- Version: 3.2

-- Instances:

local IntervalMAIN = Instance.new("ScreenGui")
local TempFolder = Instance.new("Folder")
local Frame = Instance.new("Frame")
local Title = Instance.new("TextLabel")
local Close = Instance.new("TextButton")
local Mainframe = Instance.new("Frame")
local Detail = Instance.new("Frame")
local Holder = Instance.new("Frame")
local FakeDetail = Instance.new("Frame")
local Switch1 = Instance.new("TextButton")
local Switch2 = Instance.new("TextButton")
local Title_2 = Instance.new("TextLabel")
local Pages = Instance.new("Frame")
local Page1 = Instance.new("Folder")
local Button = Instance.new("TextButton")

--Properties:

IntervalMAIN.Name = "IntervalMAIN"
IntervalMAIN.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
IntervalMAIN.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

TempFolder.Name = "TempFolder"
TempFolder.Parent = IntervalMAIN

Frame.Parent = IntervalMAIN
Frame.BackgroundColor3 = Color3.fromRGB(97, 97, 97)
Frame.BorderSizePixel = 0
Frame.Position = UDim2.new(0.315948695, 0, 0.570434034, 0)
Frame.Size = UDim2.new(0.330013394, 0, 0.021293886, 0)

Title.Name = "Title"
Title.Parent = Frame
Title.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Title.BackgroundTransparency = 1.000
Title.Position = UDim2.new(0.0198245831, 0, 0, 0)
Title.Size = UDim2.new(0.230834574, 0, 1, 0)
Title.Font = Enum.Font.Fondamento
Title.Text = "Interval v1.0.0"
Title.TextColor3 = Color3.fromRGB(255, 255, 255)
Title.TextScaled = true
Title.TextSize = 14.000
Title.TextWrapped = true
Title.TextXAlignment = Enum.TextXAlignment.Left

Close.Name = "Close"
Close.Parent = Frame
Close.BackgroundColor3 = Color3.fromRGB(255, 82, 82)
Close.BorderSizePixel = 0
Close.Position = UDim2.new(1.00000024, 0, 0, 0)
Close.Size = UDim2.new(0.04140779, 0, 0.999999881, 0)
Close.Font = Enum.Font.SourceSans
Close.Text = "X"
Close.TextColor3 = Color3.fromRGB(255, 255, 255)
Close.TextScaled = true
Close.TextSize = 14.000
Close.TextWrapped = true

Mainframe.Name = "Mainframe"
Mainframe.Parent = Frame
Mainframe.BackgroundColor3 = Color3.fromRGB(79, 79, 79)
Mainframe.BorderSizePixel = 0
Mainframe.Position = UDim2.new(-0.000788857811, 0, 0.962560534, 0)
Mainframe.Size = UDim2.new(1.04219699, 0, 11.3597584, 0)

Detail.Name = "Detail"
Detail.Parent = Mainframe
Detail.BackgroundColor3 = Color3.fromRGB(99, 99, 99)
Detail.BorderSizePixel = 0
Detail.Position = UDim2.new(0.0175812095, 0, 0.0355506651, 0)
Detail.Size = UDim2.new(0.963731885, 0, 0.925393462, 0)

Holder.Name = "Holder"
Holder.Parent = Detail
Holder.BackgroundColor3 = Color3.fromRGB(74, 74, 74)
Holder.BorderSizePixel = 0
Holder.Position = UDim2.new(0.170365065, 0, 0.216659412, 0)
Holder.Size = UDim2.new(0.659575284, 0, 0.738796651, 0)

FakeDetail.Name = "FakeDetail"
FakeDetail.Parent = Detail
FakeDetail.BackgroundColor3 = Color3.fromRGB(74, 74, 74)
FakeDetail.BorderSizePixel = 0
FakeDetail.Position = UDim2.new(0.126021713, 0, 0.0359999985, 0)
FakeDetail.Size = UDim2.new(0.748509109, 0, 0.129613101, 0)

Switch1.Name = "Switch1"
Switch1.Parent = Detail
Switch1.BackgroundColor3 = Color3.fromRGB(164, 206, 118)
Switch1.BorderSizePixel = 0
Switch1.Position = UDim2.new(0.0250839796, 0, 0.428075045, 0)
Switch1.Size = UDim2.new(0.120999999, 0, 0.300000012, 0)
Switch1.Font = Enum.Font.JosefinSans
Switch1.Text = "<"
Switch1.TextColor3 = Color3.fromRGB(255, 255, 255)
Switch1.TextScaled = true
Switch1.TextSize = 14.000
Switch1.TextWrapped = true

Switch2.Name = "Switch2"
Switch2.Parent = Detail
Switch2.BackgroundColor3 = Color3.fromRGB(164, 206, 118)
Switch2.BorderSizePixel = 0
Switch2.Position = UDim2.new(0.857488275, 0, 0.433563232, 0)
Switch2.Size = UDim2.new(0.120675132, 0, 0.300000042, 0)
Switch2.Font = Enum.Font.JosefinSans
Switch2.Text = ">"
Switch2.TextColor3 = Color3.fromRGB(255, 255, 255)
Switch2.TextScaled = true
Switch2.TextSize = 14.000
Switch2.TextWrapped = true

Title_2.Name = "Title"
Title_2.Parent = Detail
Title_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Title_2.BackgroundTransparency = 1.000
Title_2.Position = UDim2.new(0.129980326, 0, 0.0329288393, 0)
Title_2.Size = UDim2.new(0.744551063, 0, 0.132684216, 0)
Title_2.Font = Enum.Font.Fantasy
Title_2.Text = "Waiting..."
Title_2.TextColor3 = Color3.fromRGB(255, 255, 255)
Title_2.TextScaled = true
Title_2.TextSize = 14.000
Title_2.TextWrapped = true

Pages.Name = "Pages"
Pages.Parent = IntervalMAIN
Pages.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Pages.Size = UDim2.new(0, 100, 0, 100)
Pages.Visible = false

Page1.Name = "Page1"
Page1.Parent = Pages

Button.Name = "Button"
Button.Parent = Page1
Button.BackgroundColor3 = Color3.fromRGB(188, 217, 133)
Button.Position = UDim2.new(0.155578896, 0, 0.133712724, 0)
Button.Size = UDim2.new(0, 200, 0, 97)
Button.Font = Enum.Font.SourceSans
Button.Text = "Collect All"
Button.TextColor3 = Color3.fromRGB(255, 255, 255)
Button.TextScaled = true
Button.TextSize = 14.000
Button.TextWrapped = true

-- Scripts:

local function ZJQK_fake_script() -- TempFolder.PickupAll 
	local script = Instance.new('LocalScript', TempFolder)

	function getall()
		wait(3)
		while _G.a == true do
			wait()
			for i,v in pairs(game:GetService("Workspace").Collectable:GetChildren()) do
				wait()
				if v:IsA("Part") or v:IsA("MeshPart") or v:IsA("UnionOperation") then
					v.CFrame = game.Players.LocalPlayer.Character.PrimaryPart.CFrame
				end
			end
		end
	end
	
	script.Parent.Parent.Pages.Page1.Button.MouseButton1Click:Connect(function()
		_G.a = not _G.a
		getall()
	end)
	
end
coroutine.wrap(ZJQK_fake_script)()
local function MVNT_fake_script() -- TempFolder.Setup 
	local script = Instance.new('LocalScript', TempFolder)

	local Gui = script.Parent.Parent
	local main = Gui.Frame
	local detail = main.Mainframe.Detail
	local CloseX = main.Close
	
	wait(1)
	script.Parent.Parent.Pages.Page1.Parent = script.Parent.Parent.Frame.Mainframe.Detail.Holder
	
	CloseX.MouseButton1Down:Connect(function()
		Gui:Destroy()
	end)
end
coroutine.wrap(MVNT_fake_script)()
