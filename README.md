# 🖼 • UIDraggableFrame (Dark and Transparent)
```
local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Frame.Parent = ScreenGui
Frame.BackgroundTransparency = 0.5
Frame.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Frame.Position = UDim2.new(0.5, 0, 0.5, 0)
Frame.Size = UDim2.new(0.3, 0, 0.3, 0)
Frame.AnchorPoint = Vector2.new(0.5, 0.5)
Frame.Active = true
Frame.Draggable = true

local UICorner = Instance.new("UICorner")
UICorner.CornerRadius = UDim.new(0, 20)
UICorner.Parent = Frame
```
# 🖼 • UIDraggableFrame (White and Transparent)
```
local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Frame.Parent = ScreenGui
Frame.BackgroundTransparency = 0.5
Frame.BackgroundColor3 = Color3.fromRGB(255, 255, 255) -- Alterado para branco (@ArrabalDev)
Frame.Position = UDim2.new(0.5, 0, 0.5, 0)
Frame.Size = UDim2.new(0.3, 0, 0.3, 0)
Frame.AnchorPoint = Vector2.new(0.5, 0.5)
Frame.Active = true
Frame.Draggable = true

local UICorner = Instance.new("UICorner")
UICorner.CornerRadius = UDim.new(0, 20)
UICorner.Parent = Frame
```
# 🖼 • UIDraggableFrame (Blue and Transparent)
```
local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Frame.Parent = ScreenGui
Frame.BackgroundTransparency = 0.5
Frame.BackgroundColor3 = Color3.fromRGB(0, 122, 255) -- Alterado para azul (@ArrabalDev)
Frame.Position = UDim2.new(0.5, 0, 0.5, 0)
Frame.Size = UDim2.new(0.3, 0, 0.3, 0)
Frame.AnchorPoint = Vector2.new(0.5, 0.5)
Frame.Active = true
Frame.Draggable = true

local UICorner = Instance.new("UICorner")
UICorner.CornerRadius = UDim.new(0, 20)
UICorner.Parent = Frame
```
# 🖼 • UIDraggableFrame (Pink and Transparent)
```
local gui = Instance.new("ScreenGui")
local frame = Instance.new("Frame")

gui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
gui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

frame.Parent = gui
frame.BackgroundTransparency = 0.5
frame.BackgroundColor3 = Color3.fromRGB(255, 0, 127) -- Rosa (@ArrabalDev)
frame.Position = UDim2.new(0.5, 0, 0.5, 0)
frame.Size = UDim2.new(0.3, 0, 0.3, 0)
frame.AnchorPoint = Vector2.new(0.5, 0.5)
frame.Active = true
frame.Draggable = true

local corner = Instance.new("UICorner")
corner.CornerRadius = UDim.new(0, 20)
corner.Parent = frame
```