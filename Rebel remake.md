-- Gui to Lua
-- Version: 3.2

-- Instances:

local Rebel = Instance.new("ScreenGui")
local Main = Instance.new("Frame")
local Program = Instance.new("Frame")
local Label = Instance.new("TextLabel")
local ExecteBox = Instance.new("TextBox")
local Execute = Instance.new("TextButton")
local Clear = Instance.new("TextButton")
local Open = Instance.new("TextButton")
local Attach = Instance.new("TextButton")
local Label_2 = Instance.new("TextLabel")
local Script = Instance.new("TextButton")
local ScriptMain = Instance.new("Frame")
local Script1 = Instance.new("TextButton")
local TextButton = Instance.new("TextButton")
local Exit = Instance.new("TextButton")
local M = Instance.new("TextButton")
local N = Instance.new("TextButton")
local Script2 = Instance.new("TextButton")
local NBu = Instance.new("TextButton")
local UICorner = Instance.new("UICorner")

--Properties:

Rebel.Name = "Rebel"
Rebel.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
Rebel.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Main.Name = "Main"
Main.Parent = Rebel
Main.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Main.BorderColor3 = Color3.fromRGB(0, 0, 0)
Main.BorderSizePixel = 0
Main.Position = UDim2.new(0, 239, 0, 177)
Main.Size = UDim2.new(0, 500, 0, 326)

Program.Name = "Program"
Program.Parent = Main
Program.BackgroundColor3 = Color3.fromRGB(240, 240, 240)
Program.BorderColor3 = Color3.fromRGB(0, 0, 0)
Program.BorderSizePixel = 0
Program.Position = UDim2.new(0, -1, 0, 0)
Program.Size = UDim2.new(0, 500, 0, 30)

Label.Name = "Label"
Label.Parent = Program
Label.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Label.BackgroundTransparency = 1.000
Label.BorderColor3 = Color3.fromRGB(0, 0, 0)
Label.BorderSizePixel = 0
Label.Size = UDim2.new(0, 117, 0, 30)
Label.Font = Enum.Font.SourceSans
Label.Text = "Rebel Remake"
Label.TextColor3 = Color3.fromRGB(0, 0, 0)
Label.TextSize = 14.000

ExecteBox.Name = "Execte Box"
ExecteBox.Parent = Main
ExecteBox.BackgroundColor3 = Color3.fromRGB(240, 240, 240)
ExecteBox.BorderColor3 = Color3.fromRGB(0, 0, 0)
ExecteBox.BorderSizePixel = 0
ExecteBox.Position = UDim2.new(0, 6, 0, 58)
ExecteBox.Size = UDim2.new(0, 487, 0, 208)
ExecteBox.Font = Enum.Font.SourceSans
ExecteBox.Text = ""
ExecteBox.TextColor3 = Color3.fromRGB(0, 0, 0)
ExecteBox.TextSize = 14.000
ExecteBox.TextXAlignment = Enum.TextXAlignment.Left
ExecteBox.TextYAlignment = Enum.TextYAlignment.Top

Execute.Name = "Execute"
Execute.Parent = Main
Execute.BackgroundColor3 = Color3.fromRGB(240, 240, 240)
Execute.BorderColor3 = Color3.fromRGB(0, 0, 0)
Execute.BorderSizePixel = 0
Execute.Position = UDim2.new(0, 13, 0, 282)
Execute.Size = UDim2.new(0, 91, 0, 27)
Execute.Font = Enum.Font.SourceSans
Execute.Text = "Execute"
Execute.TextColor3 = Color3.fromRGB(0, 0, 0)
Execute.TextSize = 14.000

Clear.Name = "Clear"
Clear.Parent = Main
Clear.BackgroundColor3 = Color3.fromRGB(240, 240, 240)
Clear.BorderColor3 = Color3.fromRGB(0, 0, 0)
Clear.BorderSizePixel = 0
Clear.Position = UDim2.new(0, 115, 0, 282)
Clear.Size = UDim2.new(0, 91, 0, 27)
Clear.Font = Enum.Font.SourceSans
Clear.Text = "Clear"
Clear.TextColor3 = Color3.fromRGB(0, 0, 0)
Clear.TextSize = 14.000

Open.Name = "Open"
Open.Parent = Main
Open.BackgroundColor3 = Color3.fromRGB(240, 240, 240)
Open.BorderColor3 = Color3.fromRGB(0, 0, 0)
Open.BorderSizePixel = 0
Open.Position = UDim2.new(0, 221, 0, 282)
Open.Size = UDim2.new(0, 91, 0, 27)
Open.Font = Enum.Font.SourceSans
Open.Text = "Open"
Open.TextColor3 = Color3.fromRGB(0, 0, 0)
Open.TextSize = 14.000

Attach.Name = "Attach"
Attach.Parent = Main
Attach.BackgroundColor3 = Color3.fromRGB(240, 240, 240)
Attach.BorderColor3 = Color3.fromRGB(0, 0, 0)
Attach.BorderSizePixel = 0
Attach.Position = UDim2.new(0, 388, 0, 282)
Attach.Size = UDim2.new(0, 91, 0, 27)
Attach.Font = Enum.Font.SourceSans
Attach.Text = "Attach"
Attach.TextColor3 = Color3.fromRGB(0, 0, 0)
Attach.TextSize = 14.000

Label_2.Name = "Label"
Label_2.Parent = Main
Label_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Label_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
Label_2.BorderSizePixel = 0
Label_2.Position = UDim2.new(0, 13, 0, 30)
Label_2.Size = UDim2.new(0, 48, 0, 28)
Label_2.Font = Enum.Font.SourceSans
Label_2.Text = "Rebel"
Label_2.TextColor3 = Color3.fromRGB(0, 0, 0)
Label_2.TextSize = 14.000

Script.Name = "Script"
Script.Parent = Main
Script.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Script.BorderColor3 = Color3.fromRGB(0, 0, 0)
Script.BorderSizePixel = 0
Script.Position = UDim2.new(0, 97, 0, 30)
Script.Size = UDim2.new(0, 38, 0, 28)
Script.Font = Enum.Font.SourceSans
Script.Text = "Script"
Script.TextColor3 = Color3.fromRGB(0, 0, 0)
Script.TextSize = 14.000

ScriptMain.Name = "ScriptMain"
ScriptMain.Parent = Main
ScriptMain.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ScriptMain.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScriptMain.BorderSizePixel = 0
ScriptMain.Position = UDim2.new(0, 97, 0, 56)
ScriptMain.Size = UDim2.new(0, 122, 0, 100)
ScriptMain.Visible = false

Script1.Name = "Script 1"
Script1.Parent = ScriptMain
Script1.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Script1.BorderColor3 = Color3.fromRGB(0, 0, 0)
Script1.BorderSizePixel = 0
Script1.Size = UDim2.new(0, 122, 0, 19)
Script1.Font = Enum.Font.SourceSans
Script1.Text = "Admin Script"
Script1.TextColor3 = Color3.fromRGB(0, 0, 0)
Script1.TextSize = 14.000

TextButton.Parent = Main
TextButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton.BorderSizePixel = 0
TextButton.Position = UDim2.new(0, 59, 0, 30)
TextButton.Size = UDim2.new(0, 38, 0, 28)
TextButton.Font = Enum.Font.SourceSans
TextButton.Text = "View"
TextButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton.TextSize = 14.000

Exit.Name = "Exit"
Exit.Parent = Main
Exit.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Exit.BackgroundTransparency = 1.000
Exit.BorderColor3 = Color3.fromRGB(0, 0, 0)
Exit.BorderSizePixel = 0
Exit.Position = UDim2.new(0, 460, 0, 0)
Exit.Size = UDim2.new(0, 39, 0, 30)
Exit.Font = Enum.Font.SourceSans
Exit.Text = "X"
Exit.TextColor3 = Color3.fromRGB(0, 0, 0)
Exit.TextSize = 14.000

M.Name = "M"
M.Parent = Main
M.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
M.BackgroundTransparency = 1.000
M.BorderColor3 = Color3.fromRGB(0, 0, 0)
M.BorderSizePixel = 0
M.Position = UDim2.new(0, 423, 0, 0)
M.Size = UDim2.new(0, 37, 0, 30)
M.Font = Enum.Font.SourceSans
M.Text = "M"
M.TextColor3 = Color3.fromRGB(0, 0, 0)
M.TextSize = 14.000

N.Name = "N"
N.Parent = Main
N.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
N.BackgroundTransparency = 1.000
N.BorderColor3 = Color3.fromRGB(0, 0, 0)
N.BorderSizePixel = 0
N.Position = UDim2.new(0, 386, 0, 0)
N.Size = UDim2.new(0, 37, 0, 30)
N.Font = Enum.Font.SourceSans
N.Text = "-"
N.TextColor3 = Color3.fromRGB(0, 0, 0)
N.TextSize = 14.000

Script2.Name = "Script2"
Script2.Parent = Main
Script2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Script2.BorderColor3 = Color3.fromRGB(0, 0, 0)
Script2.BorderSizePixel = 0
Script2.Position = UDim2.new(0, 97, 0, 30)
Script2.Size = UDim2.new(0, 38, 0, 28)
Script2.Visible = false
Script2.Font = Enum.Font.SourceSans
Script2.Text = "Script"
Script2.TextColor3 = Color3.fromRGB(0, 0, 0)
Script2.TextSize = 14.000

NBu.Name = "N Bu"
NBu.Parent = Rebel
NBu.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
NBu.BorderColor3 = Color3.fromRGB(0, 0, 0)
NBu.BorderSizePixel = 0
NBu.Position = UDim2.new(0, 134, 0, -43)
NBu.Size = UDim2.new(0, 38, 0, 36)
NBu.Visible = false
NBu.Font = Enum.Font.SourceSans
NBu.Text = "Rebel"
NBu.TextColor3 = Color3.fromRGB(0, 0, 0)
NBu.TextSize = 14.000

UICorner.CornerRadius = UDim.new(10, 10)
UICorner.Parent = NBu

-- Scripts:

local function OGVRGGR_fake_script() -- Execute.LocalScript 
	local script = Instance.new('LocalScript', Execute)

	local Button = script.Parent
	local Executor = script.Parent.Parent["Execte Box"]
	
	Button.MouseButton1Click:Connect(function()
		loadstring(Executor.Text)()
	end)
end
coroutine.wrap(OGVRGGR_fake_script)()
local function JVBLNG_fake_script() -- Clear.LocalScript 
	local script = Instance.new('LocalScript', Clear)

	local Button = script.Parent
	local Executor = script.Parent.Parent["Execte Box"]
	
	Button.MouseButton1Click:Connect(function()
		Executor.Text = "";
	end)
end
coroutine.wrap(JVBLNG_fake_script)()
local function FVWIUPG_fake_script() -- Main.LocalScript 
	local script = Instance.new('LocalScript', Main)

	script.Parent.Draggable = true
	script.Parent.Active = true
end
coroutine.wrap(FVWIUPG_fake_script)()
local function FEARTH_fake_script() -- Script.LocalScript 
	local script = Instance.new('LocalScript', Script)

	local Button = script.Parent
	local Button2 =	Button.Parent.Script2
	Button.MouseButton1Click:Connect(function()
		script.Parent.Parent.ScriptMain.Visible = true
		Button.Visible = false
		Button2.Visible = true
	end)
end
coroutine.wrap(FEARTH_fake_script)()
local function DWHRF_fake_script() -- Script1.LocalScript 
	local script = Instance.new('LocalScript', Script1)

	local Button = script.Parent
	Button.MouseButton1Click:Connect(function()
		loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
	end)
end
coroutine.wrap(DWHRF_fake_script)()
local function UBBDFH_fake_script() -- Exit.LocalScript 
	local script = Instance.new('LocalScript', Exit)

	local Button = script.Parent
	local main = script.Parent.Parent.Parent.Main
	
	Button.MouseButton1Click:Connect(function()
		main.Visible = false
	end)
end
coroutine.wrap(UBBDFH_fake_script)()
local function CZJT_fake_script() -- N.LocalScript 
	local script = Instance.new('LocalScript', N)

	local Button = script.Parent
	local Main = script.Parent.Parent
	local N = script.Parent.Parent.Parent["N Bu"]
	
	Button.MouseButton1Click:Connect(function()
		Main.Visible = false
		N.Visible = true
	end)
end
coroutine.wrap(CZJT_fake_script)()
local function IRJHZ_fake_script() -- Script2.LocalScript 
	local script = Instance.new('LocalScript', Script2)

	local Button = script.Parent
	local Button2 = Button.Parent.Script
	Button.MouseButton1Click:Connect(function()
		script.Parent.Parent.ScriptMain.Visible = false
		Button.Visible = false
		Button2.Visible = true
	end)
end
coroutine.wrap(IRJHZ_fake_script)()
local function GCHXI_fake_script() -- NBu.LocalScript 
	local script = Instance.new('LocalScript', NBu)

	local Button = script.Parent
	local N = script.Parent.Parent.Main
	
	Button.MouseButton1Click:Connect(function()
		Button.Visible = false
		N.Visible = true
	end)
end
coroutine.wrap(GCHXI_fake_script)()
