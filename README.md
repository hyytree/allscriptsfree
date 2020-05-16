-- Gui to Lua
-- Version: 3.2

-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local main = Instance.new("Frame")
local bar1 = Instance.new("TextLabel")
local Scrolling = Instance.new("ScrollingFrame")
local IGHOULX = Instance.new("TextButton")
local ProjectX = Instance.new("TextButton")
local JailsBreak = Instance.new("TextButton")
local off = Instance.new("TextButton")
local bar3 = Instance.new("TextLabel")
local bar4 = Instance.new("TextLabel")
local opengui = Instance.new("Frame")
local user = Instance.new("TextBox")
local pass = Instance.new("TextBox")
local login = Instance.new("TextButton")
local bar7 = Instance.new("TextLabel")

--Properties:

ScreenGui.Parent = game.CoreGui
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

main.Name = "main"
main.Parent = ScreenGui
main.BackgroundColor3 = Color3.fromRGB(30, 30, 30)
main.Position = UDim2.new(0.0361945108, 0, -0.0338924453, 0)
main.Size = UDim2.new(0, 1153, 0, 718)
main.Visible = false
main.Active = true
main.Draggable = true

bar1.Name = "bar1"
bar1.Parent = main
bar1.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
bar1.BackgroundTransparency = 1.000
bar1.Position = UDim2.new(0.341922075, 0, 0, 0)
bar1.Size = UDim2.new(0, 364, 0, 50)
bar1.Font = Enum.Font.SourceSans
bar1.Text = "Scripts Free All Excute"
bar1.TextColor3 = Color3.fromRGB(85, 255, 255)
bar1.TextSize = 23.000

Scrolling.Name = "Scrolling"
Scrolling.Parent = main
Scrolling.Active = true
Scrolling.BackgroundColor3 = Color3.fromRGB(30, 30, 30)
Scrolling.Position = UDim2.new(0.013227378, 0, 0.0806880519, 0)
Scrolling.Size = UDim2.new(0, 1116, 0, 597)

IGHOULX.Name = "IGHOULX"
IGHOULX.Parent = Scrolling
IGHOULX.BackgroundColor3 = Color3.fromRGB(170, 0, 0)
IGHOULX.Size = UDim2.new(0, 156, 0, 50)
IGHOULX.Font = Enum.Font.SourceSans
IGHOULX.Text = "I GHOUL X"
IGHOULX.TextColor3 = Color3.fromRGB(255, 170, 255)
IGHOULX.TextSize = 21.000
IGHOULX.MouseButton1Down:connect(function()
loadstring(game:HttpGet(('https://ghostbin.co/paste/5zbom/raw')))()
end)

ProjectX.Name = "Project X"
ProjectX.Parent = Scrolling
ProjectX.BackgroundColor3 = Color3.fromRGB(170, 0, 0)
ProjectX.Position = UDim2.new(0, 0, 0.0502318405, 0)
ProjectX.Size = UDim2.new(0, 156, 0, 50)
ProjectX.Font = Enum.Font.SourceSans
ProjectX.Text = "Project X"
ProjectX.TextColor3 = Color3.fromRGB(255, 170, 255)
ProjectX.TextSize = 21.000
ProjectX.MouseButton1Down:connect(function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/HimikoToga1474/Ahegao-Hub/master/Main.Lua"))()
end)

JailsBreak.Name = "Jails Break"
JailsBreak.Parent = Scrolling
JailsBreak.BackgroundColor3 = Color3.fromRGB(170, 0, 0)
JailsBreak.Position = UDim2.new(0, 0, 0.102009274, 0)
JailsBreak.Size = UDim2.new(0, 156, 0, 50)
JailsBreak.Font = Enum.Font.SourceSans
JailsBreak.Text = "Jails Break"
JailsBreak.TextColor3 = Color3.fromRGB(255, 170, 255)
JailsBreak.TextSize = 21.000
JailsBreak.MouseButton1Down:connect(function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/linsonder6/Tesla/master/TeslaMain.lua"))();
end)

off.Name = "off"
off.Parent = main
off.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
off.Position = UDim2.new(0.00346921058, 0, 0.930362105, 0)
off.Size = UDim2.new(0, 200, 0, 50)
off.Font = Enum.Font.SourceSans
off.Text = "Off Gui"
off.TextColor3 = Color3.fromRGB(85, 255, 255)
off.TextSize = 31.000
off.MouseButton1Down:connect(function()
main.Visible = false
end)

bar3.Name = "bar3"
bar3.Parent = main
bar3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
bar3.BackgroundTransparency = 1.000
bar3.Position = UDim2.new(0.826539457, 0, 0.930362105, 0)
bar3.Size = UDim2.new(0, 200, 0, 50)
bar3.Font = Enum.Font.SourceSans
bar3.Text = "Credits: Crazy Cat-Kuns"
bar3.TextColor3 = Color3.fromRGB(85, 255, 255)
bar3.TextSize = 23.000

bar4.Name = "bar4"
bar4.Parent = main
bar4.BackgroundColor3 = Color3.fromRGB(170, 0, 0)
bar4.Position = UDim2.new(0, 0, 0.914970696, 0)
bar4.Size = UDim2.new(0, 1153, 0, 11)
bar4.Font = Enum.Font.SourceSans
bar4.Text = ""
bar4.TextColor3 = Color3.fromRGB(0, 0, 0)
bar4.TextSize = 14.000

opengui.Name = "opengui"
opengui.Parent = ScreenGui
opengui.BackgroundColor3 = Color3.fromRGB(30, 30, 30)
opengui.Position = UDim2.new(0.327707469, 0, 0.208456486, 0)
opengui.Size = UDim2.new(0, 282, 0, 351)
opengui.Active = true
opengui.Draggable = true

user.Name = "user"
user.Parent = opengui
user.BackgroundColor3 = Color3.fromRGB(30, 30, 30)
user.Position = UDim2.new(0.145390064, 0, 0.290598303, 0)
user.Size = UDim2.new(0, 200, 0, 50)
user.Font = Enum.Font.SourceSans
user.PlaceholderColor3 = Color3.fromRGB(85, 255, 255)
user.PlaceholderText = "USER"
user.Text = ""
user.TextColor3 = Color3.fromRGB(85, 255, 255)
user.TextSize = 25.000

pass.Name = "pass"
pass.Parent = opengui
pass.BackgroundColor3 = Color3.fromRGB(30, 30, 30)
pass.Position = UDim2.new(0.145390064, 0, 0.547008574, 0)
pass.Size = UDim2.new(0, 200, 0, 50)
pass.Font = Enum.Font.SourceSans
pass.PlaceholderColor3 = Color3.fromRGB(85, 255, 255)
pass.PlaceholderText = "Password"
pass.Text = ""
pass.TextColor3 = Color3.fromRGB(0, 0, 0)
pass.TextSize = 24.000

login.Name = "login"
login.Parent = opengui
login.BackgroundColor3 = Color3.fromRGB(30, 30, 30)
login.Position = UDim2.new(0.145390064, 0, 0.792022765, 0)
login.Size = UDim2.new(0, 200, 0, 50)
login.Font = Enum.Font.SourceSans
login.Text = "Login"
login.TextColor3 = Color3.fromRGB(85, 255, 255)
login.TextSize = 23.000
login.MouseButton1Down:connect(function()
main.Visible = true
end)

bar7.Name = "bar7"
bar7.Parent = opengui
bar7.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
bar7.BackgroundTransparency = 1.000
bar7.Position = UDim2.new(0.145390064, 0, 0.051282052, 0)
bar7.Size = UDim2.new(0, 200, 0, 50)
bar7.Font = Enum.Font.SourceSans
bar7.Text = "PLS LOGIN"
bar7.TextColor3 = Color3.fromRGB(85, 255, 255)
bar7.TextSize = 22.000
