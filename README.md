-- generated from "dominant"
local Players = game:GetService("Players")
local PlayerGui = Players.LocalPlayer:WaitForChild("PlayerGui")

local dominant = Instance.new("ScreenGui")
dominant.Name = "dominant"
dominant.Enabled = true
dominant.Parent = PlayerGui
local topbar = Instance.new("Frame")
topbar.Name = "topbar"
topbar.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
topbar.BackgroundTransparency = 0
topbar.BorderColor3 = Color3.fromRGB(0, 0, 0)
topbar.BorderSizePixel = 0
topbar.Size = UDim2.new(0, 520, 0, 30)
topbar.Position = UDim2.new(0.25325512886047363, 0, 0.057831324636936188, 0)
topbar.AnchorPoint = Vector2.new(0, 0)
topbar.Rotation = 0
topbar.Visible = true
topbar.ZIndex = 1
topbar.AutomaticSize = Enum.AutomaticSize.None
topbar.ClipsDescendants = false
topbar.LayoutOrder = 0
topbar.Active = true
topbar.Selectable = false
topbar.Parent = dominant
-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.LocalScript"

local back = Instance.new("Frame")
back.Name = "back"
back.BackgroundColor3 = Color3.fromRGB(240, 240, 240)
back.BackgroundTransparency = 0
back.BorderColor3 = Color3.fromRGB(0, 0, 0)
back.BorderSizePixel = 0
back.Size = UDim2.new(0, 520, 0, 370)
back.Position = UDim2.new(0, 0, 1, 0)
back.AnchorPoint = Vector2.new(0, 0)
back.Rotation = 0
back.Visible = true
back.ZIndex = 1
back.AutomaticSize = Enum.AutomaticSize.None
back.ClipsDescendants = false
back.LayoutOrder = 0
back.Active = true
back.Selectable = false
back.Parent = topbar
local executor = Instance.new("Frame")
executor.Name = "executor"
executor.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
executor.BackgroundTransparency = 0
executor.BorderColor3 = Color3.fromRGB(205, 205, 205)
executor.BorderSizePixel = 1
executor.Size = UDim2.new(0, 514, 0, 345)
executor.Position = UDim2.new(0, 3, 0.067999929189682007, 0)
executor.AnchorPoint = Vector2.new(0, 0)
executor.Rotation = 0
executor.Visible = true
executor.ZIndex = 1
executor.AutomaticSize = Enum.AutomaticSize.None
executor.ClipsDescendants = false
executor.LayoutOrder = 0
executor.Active = true
executor.Selectable = false
executor.Parent = back
local executor_2 = Instance.new("TextButton")
executor_2.Name = "executor"
executor_2.Text = "Executor"
executor_2.TextColor3 = Color3.fromRGB(0, 0, 0)
executor_2.TextTransparency = 0
executor_2.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
executor_2.TextStrokeTransparency = 1
executor_2.TextSize = 14
executor_2.Font = Enum.Font.SourceSans
executor_2.RichText = false
executor_2.TextWrapped = false
executor_2.TextScaled = false
executor_2.TextXAlignment = Enum.TextXAlignment.Center
executor_2.TextYAlignment = Enum.TextYAlignment.Center
executor_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
executor_2.BackgroundTransparency = 0
executor_2.BorderColor3 = Color3.fromRGB(205, 205, 205)
executor_2.BorderSizePixel = 1
executor_2.Size = UDim2.new(0, 53, 0, 19)
executor_2.Position = UDim2.new(0, 0, -0.057000000029802322, 1)
executor_2.AnchorPoint = Vector2.new(0, 0)
executor_2.Rotation = 0
executor_2.Visible = true
executor_2.ZIndex = 1
executor_2.AutomaticSize = Enum.AutomaticSize.None
executor_2.ClipsDescendants = false
executor_2.LayoutOrder = 0
executor_2.Active = true
executor_2.Selectable = true
executor_2.Modal = false
executor_2.Parent = executor

local bar = Instance.new("Frame")
bar.Name = "bar"
bar.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
bar.BackgroundTransparency = 0
bar.BorderColor3 = Color3.fromRGB(0, 0, 0)
bar.BorderSizePixel = 0
bar.Size = UDim2.new(0, 514, 0, 1)
bar.Position = UDim2.new(0, 0, 0, 0)
bar.AnchorPoint = Vector2.new(0, 0)
bar.Rotation = 0
bar.Visible = true
bar.ZIndex = 1
bar.AutomaticSize = Enum.AutomaticSize.None
bar.ClipsDescendants = false
bar.LayoutOrder = 0
bar.Active = true
bar.Selectable = false
bar.Parent = executor

local package = Instance.new("TextButton")
package.Name = "package"
package.Text = "Packages"
package.TextColor3 = Color3.fromRGB(0, 0, 0)
package.TextTransparency = 0
package.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
package.TextStrokeTransparency = 1
package.TextSize = 14
package.Font = Enum.Font.SourceSans
package.RichText = false
package.TextWrapped = false
package.TextScaled = false
package.TextXAlignment = Enum.TextXAlignment.Center
package.TextYAlignment = Enum.TextYAlignment.Center
package.BackgroundColor3 = Color3.fromRGB(240, 240, 240)
package.BackgroundTransparency = 0
package.BorderColor3 = Color3.fromRGB(205, 205, 205)
package.BorderSizePixel = 1
package.Size = UDim2.new(0, 53, 0, 16)
package.Position = UDim2.new(0.1031128391623497, 0, -0.04540582001209259, 0)
package.AnchorPoint = Vector2.new(0, 0)
package.Rotation = 0
package.Visible = true
package.ZIndex = 1
package.AutomaticSize = Enum.AutomaticSize.None
package.ClipsDescendants = false
package.LayoutOrder = 0
package.Active = true
package.Selectable = true
package.Modal = false
package.Parent = executor
-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.package.LocalScript"


local scrollbarback = Instance.new("Frame")
scrollbarback.Name = "scrollbarback"
scrollbarback.BackgroundColor3 = Color3.fromRGB(240, 240, 240)
scrollbarback.BackgroundTransparency = 0
scrollbarback.BorderColor3 = Color3.fromRGB(0, 0, 0)
scrollbarback.BorderSizePixel = 0
scrollbarback.Size = UDim2.new(0, 16, 0, 205)
scrollbarback.Position = UDim2.new(0.73540854454040527, 0, 0.034782607108354568, 0)
scrollbarback.AnchorPoint = Vector2.new(0, 0)
scrollbarback.Rotation = 0
scrollbarback.Visible = true
scrollbarback.ZIndex = 1
scrollbarback.AutomaticSize = Enum.AutomaticSize.None
scrollbarback.ClipsDescendants = false
scrollbarback.LayoutOrder = 0
scrollbarback.Active = true
scrollbarback.Selectable = false
scrollbarback.Parent = executor

local textboxback = Instance.new("ScrollingFrame")
textboxback.Name = "textboxback"
textboxback.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
textboxback.BackgroundTransparency = 1
textboxback.BorderColor3 = Color3.fromRGB(0, 0, 0)
textboxback.BorderSizePixel = 0
textboxback.Size = UDim2.new(0, 381, 0, 205)
textboxback.Position = UDim2.new(0.011673151515424252, 0, 0.034782607108354568, 0)
textboxback.AnchorPoint = Vector2.new(0, 0)
textboxback.Rotation = 0
textboxback.Visible = true
textboxback.ZIndex = 1
textboxback.AutomaticSize = Enum.AutomaticSize.None
textboxback.ClipsDescendants = true
textboxback.LayoutOrder = 0
textboxback.Active = true
textboxback.Selectable = true
textboxback.CanvasSize = UDim2.new(0, 0, 0, 0)
textboxback.CanvasPosition = Vector2.new(0, 0)
textboxback.ScrollingDirection = Enum.ScrollingDirection.XY
textboxback.ScrollBarThickness = 2
textboxback.Parent = executor
local textbox = Instance.new("TextBox")
textbox.Name = "textbox"
textbox.Text = ""
textbox.TextColor3 = Color3.fromRGB(0, 0, 0)
textbox.TextTransparency = 0
textbox.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
textbox.TextStrokeTransparency = 1
textbox.TextSize = 14
textbox.Font = Enum.Font.Code
textbox.RichText = false
textbox.TextWrapped = false
textbox.TextScaled = false
textbox.TextXAlignment = Enum.TextXAlignment.Left
textbox.TextYAlignment = Enum.TextYAlignment.Top
textbox.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
textbox.BackgroundTransparency = 1
textbox.BorderColor3 = Color3.fromRGB(0, 0, 0)
textbox.BorderSizePixel = 0
textbox.Size = UDim2.new(0, 372, 0, 205)
textbox.Position = UDim2.new(0, 0, 1.4886623489474005e-07, 0)
textbox.AnchorPoint = Vector2.new(0, 0)
textbox.Rotation = 0
textbox.Visible = true
textbox.ZIndex = 1
textbox.AutomaticSize = Enum.AutomaticSize.Y
textbox.ClipsDescendants = true
textbox.LayoutOrder = 0
textbox.Active = true
textbox.Selectable = true
textbox.Parent = textboxback
-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.textboxback.textbox.LocalScript"



local stroke = Instance.new("Frame")
stroke.Name = "stroke"
stroke.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
stroke.BackgroundTransparency = 1
stroke.BorderColor3 = Color3.fromRGB(0, 0, 0)
stroke.BorderSizePixel = 0
stroke.Size = UDim2.new(0, 388, 0, 205)
stroke.Position = UDim2.new(0.011673151515424252, 0, 0.034782607108354568, 0)
stroke.AnchorPoint = Vector2.new(0, 0)
stroke.Rotation = 0
stroke.Visible = true
stroke.ZIndex = 1
stroke.AutomaticSize = Enum.AutomaticSize.None
stroke.ClipsDescendants = false
stroke.LayoutOrder = 0
stroke.Active = true
stroke.Selectable = false
stroke.Parent = executor
local UIStroke = Instance.new("UIStroke")
UIStroke.Name = "UIStroke"
UIStroke.Enabled = true
UIStroke.ZIndex = 1
UIStroke.Parent = stroke


local stroke_2 = Instance.new("Frame")
stroke_2.Name = "stroke"
stroke_2.BackgroundColor3 = Color3.fromRGB(54, 54, 54)
stroke_2.BackgroundTransparency = 0
stroke_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
stroke_2.BorderSizePixel = 0
stroke_2.Size = UDim2.new(0, 1, 0, 206)
stroke_2.Position = UDim2.new(0.012000000104308128, -1, 0.032000001519918442, 0)
stroke_2.AnchorPoint = Vector2.new(0, 0)
stroke_2.Rotation = 0
stroke_2.Visible = true
stroke_2.ZIndex = 1
stroke_2.AutomaticSize = Enum.AutomaticSize.None
stroke_2.ClipsDescendants = false
stroke_2.LayoutOrder = 0
stroke_2.Active = true
stroke_2.Selectable = false
stroke_2.Parent = executor

local buttons = Instance.new("Frame")
buttons.Name = "buttons"
buttons.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
buttons.BackgroundTransparency = 1
buttons.BorderColor3 = Color3.fromRGB(0, 0, 0)
buttons.BorderSizePixel = 0
buttons.Size = UDim2.new(0, 139, 0, 120)
buttons.Position = UDim2.new(0.010000028647482395, 0, 0.65200001001358032, -3)
buttons.AnchorPoint = Vector2.new(0, 0)
buttons.Rotation = 0
buttons.Visible = true
buttons.ZIndex = 1
buttons.AutomaticSize = Enum.AutomaticSize.None
buttons.ClipsDescendants = false
buttons.LayoutOrder = 0
buttons.Active = true
buttons.Selectable = false
buttons.Parent = executor
local UIGridLayout = Instance.new("UIGridLayout")
UIGridLayout.Name = "UIGridLayout"
UIGridLayout.FillDirection = Enum.FillDirection.Horizontal
UIGridLayout.HorizontalAlignment = Enum.HorizontalAlignment.Left
UIGridLayout.VerticalAlignment = Enum.VerticalAlignment.Top
UIGridLayout.SortOrder = Enum.SortOrder.LayoutOrder
UIGridLayout.CellSize = UDim2.new(0, 139, 0, 34)
UIGridLayout.CellPadding = UDim2.new(0, 5, 0, 7)
UIGridLayout.Parent = buttons

local exe = Instance.new("TextButton")
exe.Name = "exe"
exe.Text = "Execute"
exe.TextColor3 = Color3.fromRGB(0, 0, 0)
exe.TextTransparency = 0
exe.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
exe.TextStrokeTransparency = 1
exe.TextSize = 15
exe.Font = Enum.Font.SourceSans
exe.RichText = false
exe.TextWrapped = true
exe.TextScaled = false
exe.TextXAlignment = Enum.TextXAlignment.Center
exe.TextYAlignment = Enum.TextYAlignment.Center
exe.BackgroundColor3 = Color3.fromRGB(240, 240, 240)
exe.BackgroundTransparency = 0
exe.BorderColor3 = Color3.fromRGB(205, 205, 205)
exe.BorderSizePixel = 1
exe.Size = UDim2.new(0, 200, 0, 50)
exe.Position = UDim2.new(0, 0, 0, 0)
exe.AnchorPoint = Vector2.new(0, 0)
exe.Rotation = 0
exe.Visible = true
exe.ZIndex = 1
exe.AutomaticSize = Enum.AutomaticSize.None
exe.ClipsDescendants = false
exe.LayoutOrder = 0
exe.Active = true
exe.Selectable = true
exe.Modal = false
exe.Parent = buttons
-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.buttons.exe.LocalScript"

-- script preserved: "convert"
-- original path: "StarterGui.dominant.topbar.back.executor.buttons.exe.convert"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.buttons.exe.LocalScript"

local RemoteEvent = Instance.new("RemoteEvent")
RemoteEvent.Name = "RemoteEvent"
RemoteEvent.Parent = exe


local clr = Instance.new("TextButton")
clr.Name = "clr"
clr.Text = "Clear"
clr.TextColor3 = Color3.fromRGB(0, 0, 0)
clr.TextTransparency = 0
clr.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
clr.TextStrokeTransparency = 1
clr.TextSize = 15
clr.Font = Enum.Font.SourceSans
clr.RichText = false
clr.TextWrapped = false
clr.TextScaled = false
clr.TextXAlignment = Enum.TextXAlignment.Center
clr.TextYAlignment = Enum.TextYAlignment.Center
clr.BackgroundColor3 = Color3.fromRGB(240, 240, 240)
clr.BackgroundTransparency = 0
clr.BorderColor3 = Color3.fromRGB(205, 205, 205)
clr.BorderSizePixel = 1
clr.Size = UDim2.new(0, 200, 0, 50)
clr.Position = UDim2.new(0, 0, 0, 0)
clr.AnchorPoint = Vector2.new(0, 0)
clr.Rotation = 0
clr.Visible = true
clr.ZIndex = 1
clr.AutomaticSize = Enum.AutomaticSize.None
clr.ClipsDescendants = false
clr.LayoutOrder = 0
clr.Active = true
clr.Selectable = true
clr.Modal = false
clr.Parent = buttons
-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.buttons.clr.LocalScript"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.buttons.clr.LocalScript"


local inj = Instance.new("TextButton")
inj.Name = "inj"
inj.Text = "Inject"
inj.TextColor3 = Color3.fromRGB(0, 0, 0)
inj.TextTransparency = 0
inj.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
inj.TextStrokeTransparency = 1
inj.TextSize = 15
inj.Font = Enum.Font.SourceSans
inj.RichText = false
inj.TextWrapped = false
inj.TextScaled = false
inj.TextXAlignment = Enum.TextXAlignment.Center
inj.TextYAlignment = Enum.TextYAlignment.Center
inj.BackgroundColor3 = Color3.fromRGB(240, 240, 240)
inj.BackgroundTransparency = 0
inj.BorderColor3 = Color3.fromRGB(205, 205, 205)
inj.BorderSizePixel = 1
inj.Size = UDim2.new(0, 200, 0, 50)
inj.Position = UDim2.new(0, 0, 0, 0)
inj.AnchorPoint = Vector2.new(0, 0)
inj.Rotation = 0
inj.Visible = true
inj.ZIndex = 1
inj.AutomaticSize = Enum.AutomaticSize.None
inj.ClipsDescendants = false
inj.LayoutOrder = 0
inj.Active = true
inj.Selectable = true
inj.Modal = false
inj.Parent = buttons
-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.buttons.inj.LocalScript"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.buttons.inj.LocalScript"



local scrollbarback_2 = Instance.new("Frame")
scrollbarback_2.Name = "scrollbarback"
scrollbarback_2.BackgroundColor3 = Color3.fromRGB(240, 240, 240)
scrollbarback_2.BackgroundTransparency = 0
scrollbarback_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
scrollbarback_2.BorderSizePixel = 0
scrollbarback_2.Size = UDim2.new(0, 16, 0, 115)
scrollbarback_2.Position = UDim2.new(0.73540854454040527, 0, 0.64330434799194336, 0)
scrollbarback_2.AnchorPoint = Vector2.new(0, 0)
scrollbarback_2.Rotation = 0
scrollbarback_2.Visible = true
scrollbarback_2.ZIndex = 1
scrollbarback_2.AutomaticSize = Enum.AutomaticSize.None
scrollbarback_2.ClipsDescendants = false
scrollbarback_2.LayoutOrder = 0
scrollbarback_2.Active = true
scrollbarback_2.Selectable = false
scrollbarback_2.Parent = executor

local logsback = Instance.new("ScrollingFrame")
logsback.Name = "logsback"
logsback.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
logsback.BackgroundTransparency = 1
logsback.BorderColor3 = Color3.fromRGB(0, 0, 0)
logsback.BorderSizePixel = 0
logsback.Size = UDim2.new(0, 238, 0, 115)
logsback.Position = UDim2.new(0.28793773055076599, 0, 0.64330434799194336, 0)
logsback.AnchorPoint = Vector2.new(0, 0)
logsback.Rotation = 0
logsback.Visible = true
logsback.ZIndex = 1
logsback.AutomaticSize = Enum.AutomaticSize.None
logsback.ClipsDescendants = true
logsback.LayoutOrder = 0
logsback.Active = true
logsback.Selectable = true
logsback.CanvasSize = UDim2.new(0, 0, 0, 0)
logsback.CanvasPosition = Vector2.new(0, 0)
logsback.ScrollingDirection = Enum.ScrollingDirection.XY
logsback.ScrollBarThickness = 2
logsback.Parent = executor
local logs = Instance.new("TextLabel")
logs.Name = "logs"
logs.Text = ""
logs.TextColor3 = Color3.fromRGB(0, 0, 0)
logs.TextTransparency = 0
logs.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
logs.TextStrokeTransparency = 1
logs.TextSize = 15
logs.Font = Enum.Font.SourceSans
logs.RichText = false
logs.TextWrapped = false
logs.TextScaled = false
logs.TextXAlignment = Enum.TextXAlignment.Left
logs.TextYAlignment = Enum.TextYAlignment.Top
logs.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
logs.BackgroundTransparency = 0
logs.BorderColor3 = Color3.fromRGB(0, 0, 0)
logs.BorderSizePixel = 0
logs.Size = UDim2.new(0, 230, 0, 115)
logs.Position = UDim2.new(0, 0, 0, 0)
logs.AnchorPoint = Vector2.new(0, 0)
logs.Rotation = 0
logs.Visible = true
logs.ZIndex = 1
logs.AutomaticSize = Enum.AutomaticSize.Y
logs.ClipsDescendants = true
logs.LayoutOrder = 0
logs.Active = false
logs.Selectable = false
logs.Parent = logsback
-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.logsback.logs.LocalScript"



local stroke_3 = Instance.new("Frame")
stroke_3.Name = "stroke"
stroke_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
stroke_3.BackgroundTransparency = 1
stroke_3.BorderColor3 = Color3.fromRGB(0, 0, 0)
stroke_3.BorderSizePixel = 0
stroke_3.Size = UDim2.new(0, 245, 0, 114)
stroke_3.Position = UDim2.new(0.28988325595855713, 0, 0.64330434799194336, 0)
stroke_3.AnchorPoint = Vector2.new(0, 0)
stroke_3.Rotation = 0
stroke_3.Visible = true
stroke_3.ZIndex = 1
stroke_3.AutomaticSize = Enum.AutomaticSize.None
stroke_3.ClipsDescendants = false
stroke_3.LayoutOrder = 0
stroke_3.Active = true
stroke_3.Selectable = false
stroke_3.Parent = executor
local UIStroke_2 = Instance.new("UIStroke")
UIStroke_2.Name = "UIStroke"
UIStroke_2.Enabled = true
UIStroke_2.ZIndex = 1
UIStroke_2.Parent = stroke_3


local stroke_4 = Instance.new("Frame")
stroke_4.Name = "stroke"
stroke_4.BackgroundColor3 = Color3.fromRGB(54, 54, 54)
stroke_4.BackgroundTransparency = 0
stroke_4.BorderColor3 = Color3.fromRGB(0, 0, 0)
stroke_4.BorderSizePixel = 0
stroke_4.Size = UDim2.new(0, 388, 0, 1)
stroke_4.Position = UDim2.new(0.011673151515424252, 0, 0.031884059309959412, 0)
stroke_4.AnchorPoint = Vector2.new(0, 0)
stroke_4.Rotation = 0
stroke_4.Visible = true
stroke_4.ZIndex = 1
stroke_4.AutomaticSize = Enum.AutomaticSize.None
stroke_4.ClipsDescendants = false
stroke_4.LayoutOrder = 0
stroke_4.Active = true
stroke_4.Selectable = false
stroke_4.Parent = executor

local scrollbarback_3 = Instance.new("Frame")
scrollbarback_3.Name = "scrollbarback"
scrollbarback_3.BackgroundColor3 = Color3.fromRGB(240, 240, 240)
scrollbarback_3.BackgroundTransparency = 0
scrollbarback_3.BorderColor3 = Color3.fromRGB(0, 0, 0)
scrollbarback_3.BorderSizePixel = 0
scrollbarback_3.Size = UDim2.new(0, 10, 0, 326)
scrollbarback_3.Position = UDim2.new(0.96303504705429077, 0, 0.034608703106641769, 0)
scrollbarback_3.AnchorPoint = Vector2.new(0, 0)
scrollbarback_3.Rotation = 0
scrollbarback_3.Visible = true
scrollbarback_3.ZIndex = 1
scrollbarback_3.AutomaticSize = Enum.AutomaticSize.None
scrollbarback_3.ClipsDescendants = false
scrollbarback_3.LayoutOrder = 0
scrollbarback_3.Active = true
scrollbarback_3.Selectable = false
scrollbarback_3.Parent = executor

local scripts = Instance.new("ScrollingFrame")
scripts.Name = "scripts"
scripts.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
scripts.BackgroundTransparency = 1
scripts.BorderColor3 = Color3.fromRGB(0, 0, 0)
scripts.BorderSizePixel = 0
scripts.Size = UDim2.new(0, 92, 0, 324)
scripts.Position = UDim2.new(0.78793776035308838, 0, 0.034782607108354568, 0)
scripts.AnchorPoint = Vector2.new(0, 0)
scripts.Rotation = 0
scripts.Visible = true
scripts.ZIndex = 1
scripts.AutomaticSize = Enum.AutomaticSize.None
scripts.ClipsDescendants = true
scripts.LayoutOrder = 0
scripts.Active = true
scripts.Selectable = true
scripts.CanvasSize = UDim2.new(0, 0, 0, 0)
scripts.CanvasPosition = Vector2.new(0, 0)
scripts.ScrollingDirection = Enum.ScrollingDirection.XY
scripts.ScrollBarThickness = 2
scripts.Parent = executor
-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.LocalScript"

local UIGridLayout_2 = Instance.new("UIGridLayout")
UIGridLayout_2.Name = "UIGridLayout"
UIGridLayout_2.FillDirection = Enum.FillDirection.Horizontal
UIGridLayout_2.HorizontalAlignment = Enum.HorizontalAlignment.Left
UIGridLayout_2.VerticalAlignment = Enum.VerticalAlignment.Top
UIGridLayout_2.SortOrder = Enum.SortOrder.LayoutOrder
UIGridLayout_2.CellSize = UDim2.new(0, 90, 0, 13)
UIGridLayout_2.CellPadding = UDim2.new(0, 5, 0, 0)
UIGridLayout_2.Parent = scripts

local Acebow = Instance.new("TextButton")
Acebow.Name = "Acebow"
Acebow.Text = "Ace's Bow V2.lua"
Acebow.TextColor3 = Color3.fromRGB(0, 0, 0)
Acebow.TextTransparency = 0
Acebow.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
Acebow.TextStrokeTransparency = 1
Acebow.TextSize = 14
Acebow.Font = Enum.Font.SourceSans
Acebow.RichText = false
Acebow.TextWrapped = false
Acebow.TextScaled = false
Acebow.TextXAlignment = Enum.TextXAlignment.Left
Acebow.TextYAlignment = Enum.TextYAlignment.Center
Acebow.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Acebow.BackgroundTransparency = 0
Acebow.BorderColor3 = Color3.fromRGB(0, 0, 0)
Acebow.BorderSizePixel = 0
Acebow.Size = UDim2.new(0, 200, 0, 50)
Acebow.Position = UDim2.new(0, 0, 0, 0)
Acebow.AnchorPoint = Vector2.new(0, 0)
Acebow.Rotation = 0
Acebow.Visible = true
Acebow.ZIndex = 1
Acebow.AutomaticSize = Enum.AutomaticSize.None
Acebow.ClipsDescendants = false
Acebow.LayoutOrder = 0
Acebow.Active = true
Acebow.Selectable = true
Acebow.Modal = false
Acebow.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.Acebow.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.Acebow.LocalScript"


local Dsword = Instance.new("TextButton")
Dsword.Name = "Dsword"
Dsword.Text = "DSword.lua"
Dsword.TextColor3 = Color3.fromRGB(0, 0, 0)
Dsword.TextTransparency = 0
Dsword.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
Dsword.TextStrokeTransparency = 1
Dsword.TextSize = 14
Dsword.Font = Enum.Font.SourceSans
Dsword.RichText = false
Dsword.TextWrapped = false
Dsword.TextScaled = false
Dsword.TextXAlignment = Enum.TextXAlignment.Left
Dsword.TextYAlignment = Enum.TextYAlignment.Center
Dsword.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Dsword.BackgroundTransparency = 0
Dsword.BorderColor3 = Color3.fromRGB(0, 0, 0)
Dsword.BorderSizePixel = 0
Dsword.Size = UDim2.new(0, 200, 0, 50)
Dsword.Position = UDim2.new(0, 0, 0, 0)
Dsword.AnchorPoint = Vector2.new(0, 0)
Dsword.Rotation = 0
Dsword.Visible = true
Dsword.ZIndex = 1
Dsword.AutomaticSize = Enum.AutomaticSize.None
Dsword.ClipsDescendants = false
Dsword.LayoutOrder = 0
Dsword.Active = true
Dsword.Selectable = true
Dsword.Modal = false
Dsword.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.Dsword.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.Dsword.LocalScript"


local LHSV2 = Instance.new("TextButton")
LHSV2.Name = "LHSV2"
LHSV2.Text = "Lost Hope Scythe V2.lua"
LHSV2.TextColor3 = Color3.fromRGB(0, 0, 0)
LHSV2.TextTransparency = 0
LHSV2.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
LHSV2.TextStrokeTransparency = 1
LHSV2.TextSize = 14
LHSV2.Font = Enum.Font.SourceSans
LHSV2.RichText = false
LHSV2.TextWrapped = false
LHSV2.TextScaled = false
LHSV2.TextXAlignment = Enum.TextXAlignment.Left
LHSV2.TextYAlignment = Enum.TextYAlignment.Center
LHSV2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
LHSV2.BackgroundTransparency = 0
LHSV2.BorderColor3 = Color3.fromRGB(0, 0, 0)
LHSV2.BorderSizePixel = 0
LHSV2.Size = UDim2.new(0, 200, 0, 50)
LHSV2.Position = UDim2.new(0, 0, 0, 0)
LHSV2.AnchorPoint = Vector2.new(0, 0)
LHSV2.Rotation = 0
LHSV2.Visible = true
LHSV2.ZIndex = 1
LHSV2.AutomaticSize = Enum.AutomaticSize.None
LHSV2.ClipsDescendants = false
LHSV2.LayoutOrder = 0
LHSV2.Active = true
LHSV2.Selectable = true
LHSV2.Modal = false
LHSV2.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.LHSV2.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.LHSV2.LocalScript"


local absolom = Instance.new("TextButton")
absolom.Name = "absolom"
absolom.Text = "Absolom.lua"
absolom.TextColor3 = Color3.fromRGB(0, 0, 0)
absolom.TextTransparency = 0
absolom.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
absolom.TextStrokeTransparency = 1
absolom.TextSize = 14
absolom.Font = Enum.Font.SourceSans
absolom.RichText = false
absolom.TextWrapped = false
absolom.TextScaled = false
absolom.TextXAlignment = Enum.TextXAlignment.Left
absolom.TextYAlignment = Enum.TextYAlignment.Center
absolom.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
absolom.BackgroundTransparency = 0
absolom.BorderColor3 = Color3.fromRGB(0, 0, 0)
absolom.BorderSizePixel = 0
absolom.Size = UDim2.new(0, 200, 0, 50)
absolom.Position = UDim2.new(0, 0, 0, 0)
absolom.AnchorPoint = Vector2.new(0, 0)
absolom.Rotation = 0
absolom.Visible = true
absolom.ZIndex = 1
absolom.AutomaticSize = Enum.AutomaticSize.None
absolom.ClipsDescendants = false
absolom.LayoutOrder = 0
absolom.Active = true
absolom.Selectable = true
absolom.Modal = false
absolom.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.absolom.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.absolom.LocalScript"


local absolute = Instance.new("TextButton")
absolute.Name = "absolute"
absolute.Text = "Absolute.lua"
absolute.TextColor3 = Color3.fromRGB(0, 0, 0)
absolute.TextTransparency = 0
absolute.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
absolute.TextStrokeTransparency = 1
absolute.TextSize = 14
absolute.Font = Enum.Font.SourceSans
absolute.RichText = false
absolute.TextWrapped = false
absolute.TextScaled = false
absolute.TextXAlignment = Enum.TextXAlignment.Left
absolute.TextYAlignment = Enum.TextYAlignment.Center
absolute.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
absolute.BackgroundTransparency = 0
absolute.BorderColor3 = Color3.fromRGB(0, 0, 0)
absolute.BorderSizePixel = 0
absolute.Size = UDim2.new(0, 200, 0, 50)
absolute.Position = UDim2.new(0, 0, 0, 0)
absolute.AnchorPoint = Vector2.new(0, 0)
absolute.Rotation = 0
absolute.Visible = true
absolute.ZIndex = 1
absolute.AutomaticSize = Enum.AutomaticSize.None
absolute.ClipsDescendants = false
absolute.LayoutOrder = 0
absolute.Active = true
absolute.Selectable = true
absolute.Modal = false
absolute.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.absolute.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.absolute.LocalScript"


local abyss = Instance.new("TextButton")
abyss.Name = "abyss"
abyss.Text = "Abyss Chakram Brawler.lua"
abyss.TextColor3 = Color3.fromRGB(0, 0, 0)
abyss.TextTransparency = 0
abyss.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
abyss.TextStrokeTransparency = 1
abyss.TextSize = 14
abyss.Font = Enum.Font.SourceSans
abyss.RichText = false
abyss.TextWrapped = false
abyss.TextScaled = false
abyss.TextXAlignment = Enum.TextXAlignment.Left
abyss.TextYAlignment = Enum.TextYAlignment.Center
abyss.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
abyss.BackgroundTransparency = 0
abyss.BorderColor3 = Color3.fromRGB(0, 0, 0)
abyss.BorderSizePixel = 0
abyss.Size = UDim2.new(0, 200, 0, 50)
abyss.Position = UDim2.new(0, 0, 0, 0)
abyss.AnchorPoint = Vector2.new(0, 0)
abyss.Rotation = 0
abyss.Visible = true
abyss.ZIndex = 1
abyss.AutomaticSize = Enum.AutomaticSize.None
abyss.ClipsDescendants = false
abyss.LayoutOrder = 0
abyss.Active = true
abyss.Selectable = true
abyss.Modal = false
abyss.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.abyss.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.abyss.LocalScript"


local acecamosniper = Instance.new("TextButton")
acecamosniper.Name = "acecamosniper"
acecamosniper.Text = "Ace's Camo Sniper.lua"
acecamosniper.TextColor3 = Color3.fromRGB(0, 0, 0)
acecamosniper.TextTransparency = 0
acecamosniper.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
acecamosniper.TextStrokeTransparency = 1
acecamosniper.TextSize = 14
acecamosniper.Font = Enum.Font.SourceSans
acecamosniper.RichText = false
acecamosniper.TextWrapped = false
acecamosniper.TextScaled = false
acecamosniper.TextXAlignment = Enum.TextXAlignment.Left
acecamosniper.TextYAlignment = Enum.TextYAlignment.Center
acecamosniper.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
acecamosniper.BackgroundTransparency = 0
acecamosniper.BorderColor3 = Color3.fromRGB(0, 0, 0)
acecamosniper.BorderSizePixel = 0
acecamosniper.Size = UDim2.new(0, 200, 0, 50)
acecamosniper.Position = UDim2.new(0, 0, 0, 0)
acecamosniper.AnchorPoint = Vector2.new(0, 0)
acecamosniper.Rotation = 0
acecamosniper.Visible = true
acecamosniper.ZIndex = 1
acecamosniper.AutomaticSize = Enum.AutomaticSize.None
acecamosniper.ClipsDescendants = false
acecamosniper.LayoutOrder = 0
acecamosniper.Active = true
acecamosniper.Selectable = true
acecamosniper.Modal = false
acecamosniper.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.acecamosniper.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.acecamosniper.LocalScript"


local acidgun = Instance.new("TextButton")
acidgun.Name = "acidgun"
acidgun.Text = "ACID GUN.lua"
acidgun.TextColor3 = Color3.fromRGB(0, 0, 0)
acidgun.TextTransparency = 0
acidgun.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
acidgun.TextStrokeTransparency = 1
acidgun.TextSize = 14
acidgun.Font = Enum.Font.SourceSans
acidgun.RichText = false
acidgun.TextWrapped = false
acidgun.TextScaled = false
acidgun.TextXAlignment = Enum.TextXAlignment.Left
acidgun.TextYAlignment = Enum.TextYAlignment.Center
acidgun.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
acidgun.BackgroundTransparency = 0
acidgun.BorderColor3 = Color3.fromRGB(0, 0, 0)
acidgun.BorderSizePixel = 0
acidgun.Size = UDim2.new(0, 200, 0, 50)
acidgun.Position = UDim2.new(0, 0, 0, 0)
acidgun.AnchorPoint = Vector2.new(0, 0)
acidgun.Rotation = 0
acidgun.Visible = true
acidgun.ZIndex = 1
acidgun.AutomaticSize = Enum.AutomaticSize.None
acidgun.ClipsDescendants = false
acidgun.LayoutOrder = 0
acidgun.Active = true
acidgun.Selectable = true
acidgun.Modal = false
acidgun.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.acidgun.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.acidgun.LocalScript"


local acidgunv2 = Instance.new("TextButton")
acidgunv2.Name = "acidgunv2"
acidgunv2.Text = "ACID GUN V2.lua"
acidgunv2.TextColor3 = Color3.fromRGB(0, 0, 0)
acidgunv2.TextTransparency = 0
acidgunv2.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
acidgunv2.TextStrokeTransparency = 1
acidgunv2.TextSize = 14
acidgunv2.Font = Enum.Font.SourceSans
acidgunv2.RichText = false
acidgunv2.TextWrapped = false
acidgunv2.TextScaled = false
acidgunv2.TextXAlignment = Enum.TextXAlignment.Left
acidgunv2.TextYAlignment = Enum.TextYAlignment.Center
acidgunv2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
acidgunv2.BackgroundTransparency = 0
acidgunv2.BorderColor3 = Color3.fromRGB(0, 0, 0)
acidgunv2.BorderSizePixel = 0
acidgunv2.Size = UDim2.new(0, 200, 0, 50)
acidgunv2.Position = UDim2.new(0, 0, 0, 0)
acidgunv2.AnchorPoint = Vector2.new(0, 0)
acidgunv2.Rotation = 0
acidgunv2.Visible = true
acidgunv2.ZIndex = 1
acidgunv2.AutomaticSize = Enum.AutomaticSize.None
acidgunv2.ClipsDescendants = false
acidgunv2.LayoutOrder = 0
acidgunv2.Active = true
acidgunv2.Selectable = true
acidgunv2.Modal = false
acidgunv2.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.acidgunv2.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.acidgunv2.LocalScript"


local advancingfortress = Instance.new("TextButton")
advancingfortress.Name = "advancingfortress"
advancingfortress.Text = "Advancing Fortress Fighter.lua"
advancingfortress.TextColor3 = Color3.fromRGB(0, 0, 0)
advancingfortress.TextTransparency = 0
advancingfortress.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
advancingfortress.TextStrokeTransparency = 1
advancingfortress.TextSize = 14
advancingfortress.Font = Enum.Font.SourceSans
advancingfortress.RichText = false
advancingfortress.TextWrapped = false
advancingfortress.TextScaled = false
advancingfortress.TextXAlignment = Enum.TextXAlignment.Left
advancingfortress.TextYAlignment = Enum.TextYAlignment.Center
advancingfortress.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
advancingfortress.BackgroundTransparency = 0
advancingfortress.BorderColor3 = Color3.fromRGB(0, 0, 0)
advancingfortress.BorderSizePixel = 0
advancingfortress.Size = UDim2.new(0, 200, 0, 50)
advancingfortress.Position = UDim2.new(0, 0, 0, 0)
advancingfortress.AnchorPoint = Vector2.new(0, 0)
advancingfortress.Rotation = 0
advancingfortress.Visible = true
advancingfortress.ZIndex = 1
advancingfortress.AutomaticSize = Enum.AutomaticSize.None
advancingfortress.ClipsDescendants = false
advancingfortress.LayoutOrder = 0
advancingfortress.Active = true
advancingfortress.Selectable = true
advancingfortress.Modal = false
advancingfortress.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.advancingfortress.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.advancingfortress.LocalScript"


local aero_blade = Instance.new("TextButton")
aero_blade.Name = "aero blade"
aero_blade.Text = "Aero Blade.lua"
aero_blade.TextColor3 = Color3.fromRGB(0, 0, 0)
aero_blade.TextTransparency = 0
aero_blade.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
aero_blade.TextStrokeTransparency = 1
aero_blade.TextSize = 14
aero_blade.Font = Enum.Font.SourceSans
aero_blade.RichText = false
aero_blade.TextWrapped = false
aero_blade.TextScaled = false
aero_blade.TextXAlignment = Enum.TextXAlignment.Left
aero_blade.TextYAlignment = Enum.TextYAlignment.Center
aero_blade.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
aero_blade.BackgroundTransparency = 0
aero_blade.BorderColor3 = Color3.fromRGB(0, 0, 0)
aero_blade.BorderSizePixel = 0
aero_blade.Size = UDim2.new(0, 200, 0, 50)
aero_blade.Position = UDim2.new(0, 0, 0, 0)
aero_blade.AnchorPoint = Vector2.new(0, 0)
aero_blade.Rotation = 0
aero_blade.Visible = true
aero_blade.ZIndex = 1
aero_blade.AutomaticSize = Enum.AutomaticSize.None
aero_blade.ClipsDescendants = false
aero_blade.LayoutOrder = 0
aero_blade.Active = true
aero_blade.Selectable = true
aero_blade.Modal = false
aero_blade.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.aero blade.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.aero blade.LocalScript"


local aero_board = Instance.new("TextButton")
aero_board.Name = "aero board"
aero_board.Text = "Aero Board.lua"
aero_board.TextColor3 = Color3.fromRGB(0, 0, 0)
aero_board.TextTransparency = 0
aero_board.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
aero_board.TextStrokeTransparency = 1
aero_board.TextSize = 14
aero_board.Font = Enum.Font.SourceSans
aero_board.RichText = false
aero_board.TextWrapped = false
aero_board.TextScaled = false
aero_board.TextXAlignment = Enum.TextXAlignment.Left
aero_board.TextYAlignment = Enum.TextYAlignment.Center
aero_board.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
aero_board.BackgroundTransparency = 0
aero_board.BorderColor3 = Color3.fromRGB(0, 0, 0)
aero_board.BorderSizePixel = 0
aero_board.Size = UDim2.new(0, 200, 0, 50)
aero_board.Position = UDim2.new(0, 0, 0, 0)
aero_board.AnchorPoint = Vector2.new(0, 0)
aero_board.Rotation = 0
aero_board.Visible = true
aero_board.ZIndex = 1
aero_board.AutomaticSize = Enum.AutomaticSize.None
aero_board.ClipsDescendants = false
aero_board.LayoutOrder = 0
aero_board.Active = true
aero_board.Selectable = true
aero_board.Modal = false
aero_board.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.aero board.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.aero board.LocalScript"


local aeroshuriken = Instance.new("TextButton")
aeroshuriken.Name = "aeroshuriken"
aeroshuriken.Text = "Aero Shuriken.lua"
aeroshuriken.TextColor3 = Color3.fromRGB(0, 0, 0)
aeroshuriken.TextTransparency = 0
aeroshuriken.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
aeroshuriken.TextStrokeTransparency = 1
aeroshuriken.TextSize = 14
aeroshuriken.Font = Enum.Font.SourceSans
aeroshuriken.RichText = false
aeroshuriken.TextWrapped = false
aeroshuriken.TextScaled = false
aeroshuriken.TextXAlignment = Enum.TextXAlignment.Left
aeroshuriken.TextYAlignment = Enum.TextYAlignment.Center
aeroshuriken.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
aeroshuriken.BackgroundTransparency = 0
aeroshuriken.BorderColor3 = Color3.fromRGB(0, 0, 0)
aeroshuriken.BorderSizePixel = 0
aeroshuriken.Size = UDim2.new(0, 200, 0, 50)
aeroshuriken.Position = UDim2.new(0, 0, 0, 0)
aeroshuriken.AnchorPoint = Vector2.new(0, 0)
aeroshuriken.Rotation = 0
aeroshuriken.Visible = true
aeroshuriken.ZIndex = 1
aeroshuriken.AutomaticSize = Enum.AutomaticSize.None
aeroshuriken.ClipsDescendants = false
aeroshuriken.LayoutOrder = 0
aeroshuriken.Active = true
aeroshuriken.Selectable = true
aeroshuriken.Modal = false
aeroshuriken.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.aeroshuriken.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.aeroshuriken.LocalScript"


local aetherflyingring = Instance.new("TextButton")
aetherflyingring.Name = "aetherflyingring"
aetherflyingring.Text = "Aether Flying Ring.lua"
aetherflyingring.TextColor3 = Color3.fromRGB(0, 0, 0)
aetherflyingring.TextTransparency = 0
aetherflyingring.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
aetherflyingring.TextStrokeTransparency = 1
aetherflyingring.TextSize = 14
aetherflyingring.Font = Enum.Font.SourceSans
aetherflyingring.RichText = false
aetherflyingring.TextWrapped = false
aetherflyingring.TextScaled = false
aetherflyingring.TextXAlignment = Enum.TextXAlignment.Left
aetherflyingring.TextYAlignment = Enum.TextYAlignment.Center
aetherflyingring.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
aetherflyingring.BackgroundTransparency = 0
aetherflyingring.BorderColor3 = Color3.fromRGB(0, 0, 0)
aetherflyingring.BorderSizePixel = 0
aetherflyingring.Size = UDim2.new(0, 200, 0, 50)
aetherflyingring.Position = UDim2.new(0, 0, 0, 0)
aetherflyingring.AnchorPoint = Vector2.new(0, 0)
aetherflyingring.Rotation = 0
aetherflyingring.Visible = true
aetherflyingring.ZIndex = 1
aetherflyingring.AutomaticSize = Enum.AutomaticSize.None
aetherflyingring.ClipsDescendants = false
aetherflyingring.LayoutOrder = 0
aetherflyingring.Active = true
aetherflyingring.Selectable = true
aetherflyingring.Modal = false
aetherflyingring.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.aetherflyingring.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.aetherflyingring.LocalScript"


local angelblade = Instance.new("TextButton")
angelblade.Name = "angelblade"
angelblade.Text = "Angel Blade.lua"
angelblade.TextColor3 = Color3.fromRGB(0, 0, 0)
angelblade.TextTransparency = 0
angelblade.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
angelblade.TextStrokeTransparency = 1
angelblade.TextSize = 14
angelblade.Font = Enum.Font.SourceSans
angelblade.RichText = false
angelblade.TextWrapped = false
angelblade.TextScaled = false
angelblade.TextXAlignment = Enum.TextXAlignment.Left
angelblade.TextYAlignment = Enum.TextYAlignment.Center
angelblade.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
angelblade.BackgroundTransparency = 0
angelblade.BorderColor3 = Color3.fromRGB(0, 0, 0)
angelblade.BorderSizePixel = 0
angelblade.Size = UDim2.new(0, 200, 0, 50)
angelblade.Position = UDim2.new(0, 0, 0, 0)
angelblade.AnchorPoint = Vector2.new(0, 0)
angelblade.Rotation = 0
angelblade.Visible = true
angelblade.ZIndex = 1
angelblade.AutomaticSize = Enum.AutomaticSize.None
angelblade.ClipsDescendants = false
angelblade.LayoutOrder = 0
angelblade.Active = true
angelblade.Selectable = true
angelblade.Modal = false
angelblade.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.angelblade.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.angelblade.LocalScript"


local angelbow = Instance.new("TextButton")
angelbow.Name = "angelbow"
angelbow.Text = "Angel Bow.lua"
angelbow.TextColor3 = Color3.fromRGB(0, 0, 0)
angelbow.TextTransparency = 0
angelbow.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
angelbow.TextStrokeTransparency = 1
angelbow.TextSize = 14
angelbow.Font = Enum.Font.SourceSans
angelbow.RichText = false
angelbow.TextWrapped = false
angelbow.TextScaled = false
angelbow.TextXAlignment = Enum.TextXAlignment.Left
angelbow.TextYAlignment = Enum.TextYAlignment.Center
angelbow.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
angelbow.BackgroundTransparency = 0
angelbow.BorderColor3 = Color3.fromRGB(0, 0, 0)
angelbow.BorderSizePixel = 0
angelbow.Size = UDim2.new(0, 200, 0, 50)
angelbow.Position = UDim2.new(0, 0, 0, 0)
angelbow.AnchorPoint = Vector2.new(0, 0)
angelbow.Rotation = 0
angelbow.Visible = true
angelbow.ZIndex = 1
angelbow.AutomaticSize = Enum.AutomaticSize.None
angelbow.ClipsDescendants = false
angelbow.LayoutOrder = 0
angelbow.Active = true
angelbow.Selectable = true
angelbow.Modal = false
angelbow.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.angelbow.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.angelbow.LocalScript"


local angelofdarkness = Instance.new("TextButton")
angelofdarkness.Name = "angelofdarkness"
angelofdarkness.Text = "Angel of Darkness.lua"
angelofdarkness.TextColor3 = Color3.fromRGB(0, 0, 0)
angelofdarkness.TextTransparency = 0
angelofdarkness.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
angelofdarkness.TextStrokeTransparency = 1
angelofdarkness.TextSize = 14
angelofdarkness.Font = Enum.Font.SourceSans
angelofdarkness.RichText = false
angelofdarkness.TextWrapped = false
angelofdarkness.TextScaled = false
angelofdarkness.TextXAlignment = Enum.TextXAlignment.Left
angelofdarkness.TextYAlignment = Enum.TextYAlignment.Center
angelofdarkness.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
angelofdarkness.BackgroundTransparency = 0
angelofdarkness.BorderColor3 = Color3.fromRGB(0, 0, 0)
angelofdarkness.BorderSizePixel = 0
angelofdarkness.Size = UDim2.new(0, 200, 0, 50)
angelofdarkness.Position = UDim2.new(0, 0, 0, 0)
angelofdarkness.AnchorPoint = Vector2.new(0, 0)
angelofdarkness.Rotation = 0
angelofdarkness.Visible = true
angelofdarkness.ZIndex = 1
angelofdarkness.AutomaticSize = Enum.AutomaticSize.None
angelofdarkness.ClipsDescendants = false
angelofdarkness.LayoutOrder = 0
angelofdarkness.Active = true
angelofdarkness.Selectable = true
angelofdarkness.Modal = false
angelofdarkness.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.angelofdarkness.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.angelofdarkness.LocalScript"


local animesky = Instance.new("TextButton")
animesky.Name = "animesky"
animesky.Text = "Anime Animated Skybox.lua"
animesky.TextColor3 = Color3.fromRGB(0, 0, 0)
animesky.TextTransparency = 0
animesky.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
animesky.TextStrokeTransparency = 1
animesky.TextSize = 14
animesky.Font = Enum.Font.SourceSans
animesky.RichText = false
animesky.TextWrapped = false
animesky.TextScaled = false
animesky.TextXAlignment = Enum.TextXAlignment.Left
animesky.TextYAlignment = Enum.TextYAlignment.Center
animesky.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
animesky.BackgroundTransparency = 0
animesky.BorderColor3 = Color3.fromRGB(0, 0, 0)
animesky.BorderSizePixel = 0
animesky.Size = UDim2.new(0, 200, 0, 50)
animesky.Position = UDim2.new(0, 0, 0, 0)
animesky.AnchorPoint = Vector2.new(0, 0)
animesky.Rotation = 0
animesky.Visible = true
animesky.ZIndex = 1
animesky.AutomaticSize = Enum.AutomaticSize.None
animesky.ClipsDescendants = false
animesky.LayoutOrder = 0
animesky.Active = true
animesky.Selectable = true
animesky.Modal = false
animesky.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.animesky.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.animesky.LocalScript"


local anonymoushackerman = Instance.new("TextButton")
anonymoushackerman.Name = "anonymoushackerman"
anonymoushackerman.Text = "Anonymous Hackerman.lua"
anonymoushackerman.TextColor3 = Color3.fromRGB(0, 0, 0)
anonymoushackerman.TextTransparency = 0
anonymoushackerman.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
anonymoushackerman.TextStrokeTransparency = 1
anonymoushackerman.TextSize = 14
anonymoushackerman.Font = Enum.Font.SourceSans
anonymoushackerman.RichText = false
anonymoushackerman.TextWrapped = false
anonymoushackerman.TextScaled = false
anonymoushackerman.TextXAlignment = Enum.TextXAlignment.Left
anonymoushackerman.TextYAlignment = Enum.TextYAlignment.Center
anonymoushackerman.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
anonymoushackerman.BackgroundTransparency = 0
anonymoushackerman.BorderColor3 = Color3.fromRGB(0, 0, 0)
anonymoushackerman.BorderSizePixel = 0
anonymoushackerman.Size = UDim2.new(0, 200, 0, 50)
anonymoushackerman.Position = UDim2.new(0, 0, 0, 0)
anonymoushackerman.AnchorPoint = Vector2.new(0, 0)
anonymoushackerman.Rotation = 0
anonymoushackerman.Visible = true
anonymoushackerman.ZIndex = 1
anonymoushackerman.AutomaticSize = Enum.AutomaticSize.None
anonymoushackerman.ClipsDescendants = false
anonymoushackerman.LayoutOrder = 0
anonymoushackerman.Active = true
anonymoushackerman.Selectable = true
anonymoushackerman.Modal = false
anonymoushackerman.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.anonymoushackerman.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.anonymoushackerman.LocalScript"


local anonymousparticle = Instance.new("TextButton")
anonymousparticle.Name = "anonymousparticle"
anonymousparticle.Text = "Anonymous Particles.lua"
anonymousparticle.TextColor3 = Color3.fromRGB(0, 0, 0)
anonymousparticle.TextTransparency = 0
anonymousparticle.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
anonymousparticle.TextStrokeTransparency = 1
anonymousparticle.TextSize = 14
anonymousparticle.Font = Enum.Font.SourceSans
anonymousparticle.RichText = false
anonymousparticle.TextWrapped = false
anonymousparticle.TextScaled = false
anonymousparticle.TextXAlignment = Enum.TextXAlignment.Left
anonymousparticle.TextYAlignment = Enum.TextYAlignment.Center
anonymousparticle.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
anonymousparticle.BackgroundTransparency = 0
anonymousparticle.BorderColor3 = Color3.fromRGB(0, 0, 0)
anonymousparticle.BorderSizePixel = 0
anonymousparticle.Size = UDim2.new(0, 200, 0, 50)
anonymousparticle.Position = UDim2.new(0, 0, 0, 0)
anonymousparticle.AnchorPoint = Vector2.new(0, 0)
anonymousparticle.Rotation = 0
anonymousparticle.Visible = true
anonymousparticle.ZIndex = 1
anonymousparticle.AutomaticSize = Enum.AutomaticSize.None
anonymousparticle.ClipsDescendants = false
anonymousparticle.LayoutOrder = 0
anonymousparticle.Active = true
anonymousparticle.Selectable = true
anonymousparticle.Modal = false
anonymousparticle.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.anonymousparticle.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.anonymousparticle.LocalScript"


local antibow = Instance.new("TextButton")
antibow.Name = "antibow"
antibow.Text = "Anti's Bow.lua"
antibow.TextColor3 = Color3.fromRGB(0, 0, 0)
antibow.TextTransparency = 0
antibow.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
antibow.TextStrokeTransparency = 1
antibow.TextSize = 14
antibow.Font = Enum.Font.SourceSans
antibow.RichText = false
antibow.TextWrapped = false
antibow.TextScaled = false
antibow.TextXAlignment = Enum.TextXAlignment.Left
antibow.TextYAlignment = Enum.TextYAlignment.Center
antibow.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
antibow.BackgroundTransparency = 0
antibow.BorderColor3 = Color3.fromRGB(0, 0, 0)
antibow.BorderSizePixel = 0
antibow.Size = UDim2.new(0, 200, 0, 50)
antibow.Position = UDim2.new(0, 0, 0, 0)
antibow.AnchorPoint = Vector2.new(0, 0)
antibow.Rotation = 0
antibow.Visible = true
antibow.ZIndex = 1
antibow.AutomaticSize = Enum.AutomaticSize.None
antibow.ClipsDescendants = false
antibow.LayoutOrder = 0
antibow.Active = true
antibow.Selectable = true
antibow.Modal = false
antibow.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.antibow.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.antibow.LocalScript"


local aoinoyami = Instance.new("TextButton")
aoinoyami.Name = "aoinoyami"
aoinoyami.Text = "Aoi No Yami.lua"
aoinoyami.TextColor3 = Color3.fromRGB(0, 0, 0)
aoinoyami.TextTransparency = 0
aoinoyami.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
aoinoyami.TextStrokeTransparency = 1
aoinoyami.TextSize = 14
aoinoyami.Font = Enum.Font.SourceSans
aoinoyami.RichText = false
aoinoyami.TextWrapped = false
aoinoyami.TextScaled = false
aoinoyami.TextXAlignment = Enum.TextXAlignment.Left
aoinoyami.TextYAlignment = Enum.TextYAlignment.Center
aoinoyami.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
aoinoyami.BackgroundTransparency = 0
aoinoyami.BorderColor3 = Color3.fromRGB(0, 0, 0)
aoinoyami.BorderSizePixel = 0
aoinoyami.Size = UDim2.new(0, 200, 0, 50)
aoinoyami.Position = UDim2.new(0, 0, 0, 0)
aoinoyami.AnchorPoint = Vector2.new(0, 0)
aoinoyami.Rotation = 0
aoinoyami.Visible = true
aoinoyami.ZIndex = 1
aoinoyami.AutomaticSize = Enum.AutomaticSize.None
aoinoyami.ClipsDescendants = false
aoinoyami.LayoutOrder = 0
aoinoyami.Active = true
aoinoyami.Selectable = true
aoinoyami.Modal = false
aoinoyami.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.aoinoyami.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.aoinoyami.LocalScript"


local ar_15 = Instance.new("TextButton")
ar_15.Name = "ar-15"
ar_15.Text = "AR-15.lua"
ar_15.TextColor3 = Color3.fromRGB(0, 0, 0)
ar_15.TextTransparency = 0
ar_15.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
ar_15.TextStrokeTransparency = 1
ar_15.TextSize = 14
ar_15.Font = Enum.Font.SourceSans
ar_15.RichText = false
ar_15.TextWrapped = false
ar_15.TextScaled = false
ar_15.TextXAlignment = Enum.TextXAlignment.Left
ar_15.TextYAlignment = Enum.TextYAlignment.Center
ar_15.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ar_15.BackgroundTransparency = 0
ar_15.BorderColor3 = Color3.fromRGB(0, 0, 0)
ar_15.BorderSizePixel = 0
ar_15.Size = UDim2.new(0, 200, 0, 50)
ar_15.Position = UDim2.new(0, 0, 0, 0)
ar_15.AnchorPoint = Vector2.new(0, 0)
ar_15.Rotation = 0
ar_15.Visible = true
ar_15.ZIndex = 1
ar_15.AutomaticSize = Enum.AutomaticSize.None
ar_15.ClipsDescendants = false
ar_15.LayoutOrder = 0
ar_15.Active = true
ar_15.Selectable = true
ar_15.Modal = false
ar_15.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.ar-15.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.ar-15.LocalScript"


local balloon = Instance.new("TextButton")
balloon.Name = "balloon"
balloon.Text = "Balloon Flight.lua"
balloon.TextColor3 = Color3.fromRGB(0, 0, 0)
balloon.TextTransparency = 0
balloon.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
balloon.TextStrokeTransparency = 1
balloon.TextSize = 14
balloon.Font = Enum.Font.SourceSans
balloon.RichText = true
balloon.TextWrapped = false
balloon.TextScaled = false
balloon.TextXAlignment = Enum.TextXAlignment.Left
balloon.TextYAlignment = Enum.TextYAlignment.Center
balloon.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
balloon.BackgroundTransparency = 0
balloon.BorderColor3 = Color3.fromRGB(0, 0, 0)
balloon.BorderSizePixel = 0
balloon.Size = UDim2.new(0, 200, 0, 50)
balloon.Position = UDim2.new(0, 0, 0, 0)
balloon.AnchorPoint = Vector2.new(0, 0)
balloon.Rotation = 0
balloon.Visible = true
balloon.ZIndex = 1
balloon.AutomaticSize = Enum.AutomaticSize.None
balloon.ClipsDescendants = false
balloon.LayoutOrder = 0
balloon.Active = true
balloon.Selectable = true
balloon.Modal = false
balloon.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.balloon.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.balloon.LocalScript"


local banana = Instance.new("TextButton")
banana.Name = "banana"
banana.Text = "Banana.lua"
banana.TextColor3 = Color3.fromRGB(0, 0, 0)
banana.TextTransparency = 0
banana.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
banana.TextStrokeTransparency = 1
banana.TextSize = 14
banana.Font = Enum.Font.SourceSans
banana.RichText = false
banana.TextWrapped = false
banana.TextScaled = false
banana.TextXAlignment = Enum.TextXAlignment.Left
banana.TextYAlignment = Enum.TextYAlignment.Center
banana.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
banana.BackgroundTransparency = 0
banana.BorderColor3 = Color3.fromRGB(0, 0, 0)
banana.BorderSizePixel = 0
banana.Size = UDim2.new(0, 200, 0, 50)
banana.Position = UDim2.new(0, 0, 0, 0)
banana.AnchorPoint = Vector2.new(0, 0)
banana.Rotation = 0
banana.Visible = true
banana.ZIndex = 1
banana.AutomaticSize = Enum.AutomaticSize.None
banana.ClipsDescendants = false
banana.LayoutOrder = 0
banana.Active = true
banana.Selectable = true
banana.Modal = false
banana.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.banana.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.banana.LocalScript"


local banhammer = Instance.new("TextButton")
banhammer.Name = "banhammer"
banhammer.Text = "Ban Hammer.lua"
banhammer.TextColor3 = Color3.fromRGB(0, 0, 0)
banhammer.TextTransparency = 0
banhammer.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
banhammer.TextStrokeTransparency = 1
banhammer.TextSize = 14
banhammer.Font = Enum.Font.SourceSans
banhammer.RichText = true
banhammer.TextWrapped = false
banhammer.TextScaled = false
banhammer.TextXAlignment = Enum.TextXAlignment.Left
banhammer.TextYAlignment = Enum.TextYAlignment.Center
banhammer.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
banhammer.BackgroundTransparency = 0
banhammer.BorderColor3 = Color3.fromRGB(0, 0, 0)
banhammer.BorderSizePixel = 0
banhammer.Size = UDim2.new(0, 200, 0, 50)
banhammer.Position = UDim2.new(0, 0, 0, 0)
banhammer.AnchorPoint = Vector2.new(0, 0)
banhammer.Rotation = 0
banhammer.Visible = true
banhammer.ZIndex = 1
banhammer.AutomaticSize = Enum.AutomaticSize.None
banhammer.ClipsDescendants = false
banhammer.LayoutOrder = 0
banhammer.Active = true
banhammer.Selectable = true
banhammer.Modal = false
banhammer.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.banhammer.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.banhammer.LocalScript"


local barricade = Instance.new("TextButton")
barricade.Name = "barricade"
barricade.Text = "A.X.R Barricade.lua"
barricade.TextColor3 = Color3.fromRGB(0, 0, 0)
barricade.TextTransparency = 0
barricade.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
barricade.TextStrokeTransparency = 1
barricade.TextSize = 14
barricade.Font = Enum.Font.SourceSans
barricade.RichText = false
barricade.TextWrapped = false
barricade.TextScaled = false
barricade.TextXAlignment = Enum.TextXAlignment.Left
barricade.TextYAlignment = Enum.TextYAlignment.Center
barricade.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
barricade.BackgroundTransparency = 0
barricade.BorderColor3 = Color3.fromRGB(0, 0, 0)
barricade.BorderSizePixel = 0
barricade.Size = UDim2.new(0, 200, 0, 50)
barricade.Position = UDim2.new(0, 0, 0, 0)
barricade.AnchorPoint = Vector2.new(0, 0)
barricade.Rotation = 0
barricade.Visible = true
barricade.ZIndex = 1
barricade.AutomaticSize = Enum.AutomaticSize.None
barricade.ClipsDescendants = false
barricade.LayoutOrder = 0
barricade.Active = true
barricade.Selectable = true
barricade.Modal = false
barricade.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.barricade.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.barricade.LocalScript"


local becomecake = Instance.new("TextButton")
becomecake.Name = "becomecake"
becomecake.Text = "Become a Cake.lua"
becomecake.TextColor3 = Color3.fromRGB(0, 0, 0)
becomecake.TextTransparency = 0
becomecake.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
becomecake.TextStrokeTransparency = 1
becomecake.TextSize = 14
becomecake.Font = Enum.Font.SourceSans
becomecake.RichText = false
becomecake.TextWrapped = false
becomecake.TextScaled = false
becomecake.TextXAlignment = Enum.TextXAlignment.Left
becomecake.TextYAlignment = Enum.TextYAlignment.Center
becomecake.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
becomecake.BackgroundTransparency = 0
becomecake.BorderColor3 = Color3.fromRGB(0, 0, 0)
becomecake.BorderSizePixel = 0
becomecake.Size = UDim2.new(0, 200, 0, 50)
becomecake.Position = UDim2.new(0, 0, 0, 0)
becomecake.AnchorPoint = Vector2.new(0, 0)
becomecake.Rotation = 0
becomecake.Visible = true
becomecake.ZIndex = 1
becomecake.AutomaticSize = Enum.AutomaticSize.None
becomecake.ClipsDescendants = false
becomecake.LayoutOrder = 0
becomecake.Active = true
becomecake.Selectable = true
becomecake.Modal = false
becomecake.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.becomecake.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.becomecake.LocalScript"


local becomeduck = Instance.new("TextButton")
becomeduck.Name = "becomeduck"
becomeduck.Text = "Become a Duck.lua"
becomeduck.TextColor3 = Color3.fromRGB(0, 0, 0)
becomeduck.TextTransparency = 0
becomeduck.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
becomeduck.TextStrokeTransparency = 1
becomeduck.TextSize = 14
becomeduck.Font = Enum.Font.SourceSans
becomeduck.RichText = false
becomeduck.TextWrapped = false
becomeduck.TextScaled = false
becomeduck.TextXAlignment = Enum.TextXAlignment.Left
becomeduck.TextYAlignment = Enum.TextYAlignment.Center
becomeduck.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
becomeduck.BackgroundTransparency = 0
becomeduck.BorderColor3 = Color3.fromRGB(0, 0, 0)
becomeduck.BorderSizePixel = 0
becomeduck.Size = UDim2.new(0, 200, 0, 50)
becomeduck.Position = UDim2.new(0, 0, 0, 0)
becomeduck.AnchorPoint = Vector2.new(0, 0)
becomeduck.Rotation = 0
becomeduck.Visible = true
becomeduck.ZIndex = 1
becomeduck.AutomaticSize = Enum.AutomaticSize.None
becomeduck.ClipsDescendants = false
becomeduck.LayoutOrder = 0
becomeduck.Active = true
becomeduck.Selectable = true
becomeduck.Modal = false
becomeduck.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.becomeduck.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.becomeduck.LocalScript"


local becomeevilduck = Instance.new("TextButton")
becomeevilduck.Name = "becomeevilduck"
becomeevilduck.Text = "Become a Evil Duck.lua"
becomeevilduck.TextColor3 = Color3.fromRGB(0, 0, 0)
becomeevilduck.TextTransparency = 0
becomeevilduck.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
becomeevilduck.TextStrokeTransparency = 1
becomeevilduck.TextSize = 14
becomeevilduck.Font = Enum.Font.SourceSans
becomeevilduck.RichText = false
becomeevilduck.TextWrapped = false
becomeevilduck.TextScaled = false
becomeevilduck.TextXAlignment = Enum.TextXAlignment.Left
becomeevilduck.TextYAlignment = Enum.TextYAlignment.Center
becomeevilduck.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
becomeevilduck.BackgroundTransparency = 0
becomeevilduck.BorderColor3 = Color3.fromRGB(0, 0, 0)
becomeevilduck.BorderSizePixel = 0
becomeevilduck.Size = UDim2.new(0, 200, 0, 50)
becomeevilduck.Position = UDim2.new(0, 0, 0, 0)
becomeevilduck.AnchorPoint = Vector2.new(0, 0)
becomeevilduck.Rotation = 0
becomeevilduck.Visible = true
becomeevilduck.ZIndex = 1
becomeevilduck.AutomaticSize = Enum.AutomaticSize.None
becomeevilduck.ClipsDescendants = false
becomeevilduck.LayoutOrder = 0
becomeevilduck.Active = true
becomeevilduck.Selectable = true
becomeevilduck.Modal = false
becomeevilduck.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.becomeevilduck.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.becomeevilduck.LocalScript"


local becomeharambe = Instance.new("TextButton")
becomeharambe.Name = "becomeharambe"
becomeharambe.Text = "Become a Harambe.lua"
becomeharambe.TextColor3 = Color3.fromRGB(0, 0, 0)
becomeharambe.TextTransparency = 0
becomeharambe.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
becomeharambe.TextStrokeTransparency = 1
becomeharambe.TextSize = 14
becomeharambe.Font = Enum.Font.SourceSans
becomeharambe.RichText = false
becomeharambe.TextWrapped = false
becomeharambe.TextScaled = false
becomeharambe.TextXAlignment = Enum.TextXAlignment.Left
becomeharambe.TextYAlignment = Enum.TextYAlignment.Center
becomeharambe.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
becomeharambe.BackgroundTransparency = 0
becomeharambe.BorderColor3 = Color3.fromRGB(0, 0, 0)
becomeharambe.BorderSizePixel = 0
becomeharambe.Size = UDim2.new(0, 200, 0, 50)
becomeharambe.Position = UDim2.new(0, 0, 0, 0)
becomeharambe.AnchorPoint = Vector2.new(0, 0)
becomeharambe.Rotation = 0
becomeharambe.Visible = true
becomeharambe.ZIndex = 1
becomeharambe.AutomaticSize = Enum.AutomaticSize.None
becomeharambe.ClipsDescendants = false
becomeharambe.LayoutOrder = 0
becomeharambe.Active = true
becomeharambe.Selectable = true
becomeharambe.Modal = false
becomeharambe.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.becomeharambe.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.becomeharambe.LocalScript"


local becomesonic = Instance.new("TextButton")
becomesonic.Name = "becomesonic"
becomesonic.Text = "Become a Sonic.lua"
becomesonic.TextColor3 = Color3.fromRGB(0, 0, 0)
becomesonic.TextTransparency = 0
becomesonic.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
becomesonic.TextStrokeTransparency = 1
becomesonic.TextSize = 14
becomesonic.Font = Enum.Font.SourceSans
becomesonic.RichText = false
becomesonic.TextWrapped = false
becomesonic.TextScaled = false
becomesonic.TextXAlignment = Enum.TextXAlignment.Left
becomesonic.TextYAlignment = Enum.TextYAlignment.Center
becomesonic.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
becomesonic.BackgroundTransparency = 0
becomesonic.BorderColor3 = Color3.fromRGB(0, 0, 0)
becomesonic.BorderSizePixel = 0
becomesonic.Size = UDim2.new(0, 200, 0, 50)
becomesonic.Position = UDim2.new(0, 0, 0, 0)
becomesonic.AnchorPoint = Vector2.new(0, 0)
becomesonic.Rotation = 0
becomesonic.Visible = true
becomesonic.ZIndex = 1
becomesonic.AutomaticSize = Enum.AutomaticSize.None
becomesonic.ClipsDescendants = false
becomesonic.LayoutOrder = 0
becomesonic.Active = true
becomesonic.Selectable = true
becomesonic.Modal = false
becomesonic.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.becomesonic.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.becomesonic.LocalScript"


local bigboss = Instance.new("TextButton")
bigboss.Name = "bigboss"
bigboss.Text = "Big Boss.lua"
bigboss.TextColor3 = Color3.fromRGB(0, 0, 0)
bigboss.TextTransparency = 0
bigboss.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
bigboss.TextStrokeTransparency = 1
bigboss.TextSize = 14
bigboss.Font = Enum.Font.SourceSans
bigboss.RichText = false
bigboss.TextWrapped = false
bigboss.TextScaled = false
bigboss.TextXAlignment = Enum.TextXAlignment.Left
bigboss.TextYAlignment = Enum.TextYAlignment.Center
bigboss.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
bigboss.BackgroundTransparency = 0
bigboss.BorderColor3 = Color3.fromRGB(0, 0, 0)
bigboss.BorderSizePixel = 0
bigboss.Size = UDim2.new(0, 200, 0, 50)
bigboss.Position = UDim2.new(0, 0, 0, 0)
bigboss.AnchorPoint = Vector2.new(0, 0)
bigboss.Rotation = 0
bigboss.Visible = true
bigboss.ZIndex = 1
bigboss.AutomaticSize = Enum.AutomaticSize.None
bigboss.ClipsDescendants = false
bigboss.LayoutOrder = 0
bigboss.Active = true
bigboss.Selectable = true
bigboss.Modal = false
bigboss.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.bigboss.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.bigboss.LocalScript"


local blackdragon = Instance.new("TextButton")
blackdragon.Name = "blackdragon"
blackdragon.Text = "Black Dragon.lua"
blackdragon.TextColor3 = Color3.fromRGB(0, 0, 0)
blackdragon.TextTransparency = 0
blackdragon.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
blackdragon.TextStrokeTransparency = 1
blackdragon.TextSize = 14
blackdragon.Font = Enum.Font.SourceSans
blackdragon.RichText = false
blackdragon.TextWrapped = false
blackdragon.TextScaled = false
blackdragon.TextXAlignment = Enum.TextXAlignment.Left
blackdragon.TextYAlignment = Enum.TextYAlignment.Center
blackdragon.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
blackdragon.BackgroundTransparency = 0
blackdragon.BorderColor3 = Color3.fromRGB(0, 0, 0)
blackdragon.BorderSizePixel = 0
blackdragon.Size = UDim2.new(0, 200, 0, 50)
blackdragon.Position = UDim2.new(0, 0, 0, 0)
blackdragon.AnchorPoint = Vector2.new(0, 0)
blackdragon.Rotation = 0
blackdragon.Visible = true
blackdragon.ZIndex = 1
blackdragon.AutomaticSize = Enum.AutomaticSize.None
blackdragon.ClipsDescendants = false
blackdragon.LayoutOrder = 0
blackdragon.Active = true
blackdragon.Selectable = true
blackdragon.Modal = false
blackdragon.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.blackdragon.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.blackdragon.LocalScript"


local bladeddarktitan = Instance.new("TextButton")
bladeddarktitan.Name = "bladeddarktitan"
bladeddarktitan.Text = "Bladed Dark Titan.lua"
bladeddarktitan.TextColor3 = Color3.fromRGB(0, 0, 0)
bladeddarktitan.TextTransparency = 0
bladeddarktitan.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
bladeddarktitan.TextStrokeTransparency = 1
bladeddarktitan.TextSize = 14
bladeddarktitan.Font = Enum.Font.SourceSans
bladeddarktitan.RichText = false
bladeddarktitan.TextWrapped = false
bladeddarktitan.TextScaled = false
bladeddarktitan.TextXAlignment = Enum.TextXAlignment.Left
bladeddarktitan.TextYAlignment = Enum.TextYAlignment.Center
bladeddarktitan.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
bladeddarktitan.BackgroundTransparency = 0
bladeddarktitan.BorderColor3 = Color3.fromRGB(0, 0, 0)
bladeddarktitan.BorderSizePixel = 0
bladeddarktitan.Size = UDim2.new(0, 200, 0, 50)
bladeddarktitan.Position = UDim2.new(0, 0, 0, 0)
bladeddarktitan.AnchorPoint = Vector2.new(0, 0)
bladeddarktitan.Rotation = 0
bladeddarktitan.Visible = true
bladeddarktitan.ZIndex = 1
bladeddarktitan.AutomaticSize = Enum.AutomaticSize.None
bladeddarktitan.ClipsDescendants = false
bladeddarktitan.LayoutOrder = 0
bladeddarktitan.Active = true
bladeddarktitan.Selectable = true
bladeddarktitan.Modal = false
bladeddarktitan.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.bladeddarktitan.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.bladeddarktitan.LocalScript"


local blastblade = Instance.new("TextButton")
blastblade.Name = "blastblade"
blastblade.Text = "Blast Blade.lua"
blastblade.TextColor3 = Color3.fromRGB(0, 0, 0)
blastblade.TextTransparency = 0
blastblade.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
blastblade.TextStrokeTransparency = 1
blastblade.TextSize = 14
blastblade.Font = Enum.Font.SourceSans
blastblade.RichText = false
blastblade.TextWrapped = false
blastblade.TextScaled = false
blastblade.TextXAlignment = Enum.TextXAlignment.Left
blastblade.TextYAlignment = Enum.TextYAlignment.Center
blastblade.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
blastblade.BackgroundTransparency = 0
blastblade.BorderColor3 = Color3.fromRGB(0, 0, 0)
blastblade.BorderSizePixel = 0
blastblade.Size = UDim2.new(0, 200, 0, 50)
blastblade.Position = UDim2.new(0, 0, 0, 0)
blastblade.AnchorPoint = Vector2.new(0, 0)
blastblade.Rotation = 0
blastblade.Visible = true
blastblade.ZIndex = 1
blastblade.AutomaticSize = Enum.AutomaticSize.None
blastblade.ClipsDescendants = false
blastblade.LayoutOrder = 0
blastblade.Active = true
blastblade.Selectable = true
blastblade.Modal = false
blastblade.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.blastblade.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.blastblade.LocalScript"


local blockofire = Instance.new("TextButton")
blockofire.Name = "blockofire"
blockofire.Text = "Block O Fire.lua"
blockofire.TextColor3 = Color3.fromRGB(0, 0, 0)
blockofire.TextTransparency = 0
blockofire.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
blockofire.TextStrokeTransparency = 1
blockofire.TextSize = 14
blockofire.Font = Enum.Font.SourceSans
blockofire.RichText = false
blockofire.TextWrapped = false
blockofire.TextScaled = false
blockofire.TextXAlignment = Enum.TextXAlignment.Left
blockofire.TextYAlignment = Enum.TextYAlignment.Center
blockofire.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
blockofire.BackgroundTransparency = 0
blockofire.BorderColor3 = Color3.fromRGB(0, 0, 0)
blockofire.BorderSizePixel = 0
blockofire.Size = UDim2.new(0, 200, 0, 50)
blockofire.Position = UDim2.new(0, 0, 0, 0)
blockofire.AnchorPoint = Vector2.new(0, 0)
blockofire.Rotation = 0
blockofire.Visible = true
blockofire.ZIndex = 1
blockofire.AutomaticSize = Enum.AutomaticSize.None
blockofire.ClipsDescendants = false
blockofire.LayoutOrder = 0
blockofire.Active = true
blockofire.Selectable = true
blockofire.Modal = false
blockofire.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.blockofire.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.blockofire.LocalScript"


local bridgetool = Instance.new("TextButton")
bridgetool.Name = "bridgetool"
bridgetool.Text = "Bridge Tools.lua"
bridgetool.TextColor3 = Color3.fromRGB(0, 0, 0)
bridgetool.TextTransparency = 0
bridgetool.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
bridgetool.TextStrokeTransparency = 1
bridgetool.TextSize = 14
bridgetool.Font = Enum.Font.SourceSans
bridgetool.RichText = false
bridgetool.TextWrapped = false
bridgetool.TextScaled = false
bridgetool.TextXAlignment = Enum.TextXAlignment.Left
bridgetool.TextYAlignment = Enum.TextYAlignment.Center
bridgetool.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
bridgetool.BackgroundTransparency = 0
bridgetool.BorderColor3 = Color3.fromRGB(0, 0, 0)
bridgetool.BorderSizePixel = 0
bridgetool.Size = UDim2.new(0, 200, 0, 50)
bridgetool.Position = UDim2.new(0, 0, 0, 0)
bridgetool.AnchorPoint = Vector2.new(0, 0)
bridgetool.Rotation = 0
bridgetool.Visible = true
bridgetool.ZIndex = 1
bridgetool.AutomaticSize = Enum.AutomaticSize.None
bridgetool.ClipsDescendants = false
bridgetool.LayoutOrder = 0
bridgetool.Active = true
bridgetool.Selectable = true
bridgetool.Modal = false
bridgetool.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.bridgetool.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.bridgetool.LocalScript"


local bulldog = Instance.new("TextButton")
bulldog.Name = "bulldog"
bulldog.Text = "A.X.R Bulldog.lua"
bulldog.TextColor3 = Color3.fromRGB(0, 0, 0)
bulldog.TextTransparency = 0
bulldog.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
bulldog.TextStrokeTransparency = 1
bulldog.TextSize = 14
bulldog.Font = Enum.Font.SourceSans
bulldog.RichText = false
bulldog.TextWrapped = false
bulldog.TextScaled = false
bulldog.TextXAlignment = Enum.TextXAlignment.Left
bulldog.TextYAlignment = Enum.TextYAlignment.Center
bulldog.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
bulldog.BackgroundTransparency = 0
bulldog.BorderColor3 = Color3.fromRGB(0, 0, 0)
bulldog.BorderSizePixel = 0
bulldog.Size = UDim2.new(0, 200, 0, 50)
bulldog.Position = UDim2.new(0, 0, 0, 0)
bulldog.AnchorPoint = Vector2.new(0, 0)
bulldog.Rotation = 0
bulldog.Visible = true
bulldog.ZIndex = 1
bulldog.AutomaticSize = Enum.AutomaticSize.None
bulldog.ClipsDescendants = false
bulldog.LayoutOrder = 0
bulldog.Active = true
bulldog.Selectable = true
bulldog.Modal = false
bulldog.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.bulldog.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.bulldog.LocalScript"


local crater = Instance.new("TextButton")
crater.Name = "crater"
crater.Text = "A.X.R Crater.lua"
crater.TextColor3 = Color3.fromRGB(0, 0, 0)
crater.TextTransparency = 0
crater.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
crater.TextStrokeTransparency = 1
crater.TextSize = 14
crater.Font = Enum.Font.SourceSans
crater.RichText = false
crater.TextWrapped = false
crater.TextScaled = false
crater.TextXAlignment = Enum.TextXAlignment.Left
crater.TextYAlignment = Enum.TextYAlignment.Center
crater.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
crater.BackgroundTransparency = 0
crater.BorderColor3 = Color3.fromRGB(0, 0, 0)
crater.BorderSizePixel = 0
crater.Size = UDim2.new(0, 200, 0, 50)
crater.Position = UDim2.new(0, 0, 0, 0)
crater.AnchorPoint = Vector2.new(0, 0)
crater.Rotation = 0
crater.Visible = true
crater.ZIndex = 1
crater.AutomaticSize = Enum.AutomaticSize.None
crater.ClipsDescendants = false
crater.LayoutOrder = 0
crater.Active = true
crater.Selectable = true
crater.Modal = false
crater.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.crater.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.crater.LocalScript"


local dancingskeleton = Instance.new("TextButton")
dancingskeleton.Name = "dancingskeleton"
dancingskeleton.Text = "Dancing Skeleton Skybox.lua"
dancingskeleton.TextColor3 = Color3.fromRGB(0, 0, 0)
dancingskeleton.TextTransparency = 0
dancingskeleton.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
dancingskeleton.TextStrokeTransparency = 1
dancingskeleton.TextSize = 14
dancingskeleton.Font = Enum.Font.SourceSans
dancingskeleton.RichText = false
dancingskeleton.TextWrapped = false
dancingskeleton.TextScaled = false
dancingskeleton.TextXAlignment = Enum.TextXAlignment.Left
dancingskeleton.TextYAlignment = Enum.TextYAlignment.Center
dancingskeleton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
dancingskeleton.BackgroundTransparency = 0
dancingskeleton.BorderColor3 = Color3.fromRGB(0, 0, 0)
dancingskeleton.BorderSizePixel = 0
dancingskeleton.Size = UDim2.new(0, 200, 0, 50)
dancingskeleton.Position = UDim2.new(0, 0, 0, 0)
dancingskeleton.AnchorPoint = Vector2.new(0, 0)
dancingskeleton.Rotation = 0
dancingskeleton.Visible = true
dancingskeleton.ZIndex = 1
dancingskeleton.AutomaticSize = Enum.AutomaticSize.None
dancingskeleton.ClipsDescendants = false
dancingskeleton.LayoutOrder = 0
dancingskeleton.Active = true
dancingskeleton.Selectable = true
dancingskeleton.Modal = false
dancingskeleton.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.dancingskeleton.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.dancingskeleton.LocalScript"


local devo = Instance.new("TextButton")
devo.Name = "devo"
devo.Text = "Devoyance Glitcher V4.txt"
devo.TextColor3 = Color3.fromRGB(0, 0, 0)
devo.TextTransparency = 0
devo.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
devo.TextStrokeTransparency = 1
devo.TextSize = 14
devo.Font = Enum.Font.SourceSans
devo.RichText = false
devo.TextWrapped = false
devo.TextScaled = false
devo.TextXAlignment = Enum.TextXAlignment.Left
devo.TextYAlignment = Enum.TextYAlignment.Center
devo.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
devo.BackgroundTransparency = 0
devo.BorderColor3 = Color3.fromRGB(0, 0, 0)
devo.BorderSizePixel = 0
devo.Size = UDim2.new(0, 200, 0, 50)
devo.Position = UDim2.new(0, 0, 0, 0)
devo.AnchorPoint = Vector2.new(0, 0)
devo.Rotation = 0
devo.Visible = true
devo.ZIndex = 1
devo.AutomaticSize = Enum.AutomaticSize.None
devo.ClipsDescendants = false
devo.LayoutOrder = 0
devo.Active = true
devo.Selectable = true
devo.Modal = false
devo.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.devo.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.devo.LocalScript"


local dogearmy = Instance.new("TextButton")
dogearmy.Name = "dogearmy"
dogearmy.Text = "Doge Army.txt"
dogearmy.TextColor3 = Color3.fromRGB(0, 0, 0)
dogearmy.TextTransparency = 0
dogearmy.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
dogearmy.TextStrokeTransparency = 1
dogearmy.TextSize = 14
dogearmy.Font = Enum.Font.SourceSans
dogearmy.RichText = false
dogearmy.TextWrapped = false
dogearmy.TextScaled = false
dogearmy.TextXAlignment = Enum.TextXAlignment.Left
dogearmy.TextYAlignment = Enum.TextYAlignment.Center
dogearmy.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
dogearmy.BackgroundTransparency = 0
dogearmy.BorderColor3 = Color3.fromRGB(0, 0, 0)
dogearmy.BorderSizePixel = 0
dogearmy.Size = UDim2.new(0, 200, 0, 50)
dogearmy.Position = UDim2.new(0, 0, 0, 0)
dogearmy.AnchorPoint = Vector2.new(0, 0)
dogearmy.Rotation = 0
dogearmy.Visible = true
dogearmy.ZIndex = 1
dogearmy.AutomaticSize = Enum.AutomaticSize.None
dogearmy.ClipsDescendants = false
dogearmy.LayoutOrder = 0
dogearmy.Active = true
dogearmy.Selectable = true
dogearmy.Modal = false
dogearmy.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.dogearmy.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.dogearmy.LocalScript"


local dominusking = Instance.new("TextButton")
dominusking.Name = "dominusking"
dominusking.Text = "Dominus King.lua"
dominusking.TextColor3 = Color3.fromRGB(0, 0, 0)
dominusking.TextTransparency = 0
dominusking.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
dominusking.TextStrokeTransparency = 1
dominusking.TextSize = 14
dominusking.Font = Enum.Font.SourceSans
dominusking.RichText = false
dominusking.TextWrapped = false
dominusking.TextScaled = false
dominusking.TextXAlignment = Enum.TextXAlignment.Left
dominusking.TextYAlignment = Enum.TextYAlignment.Center
dominusking.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
dominusking.BackgroundTransparency = 0
dominusking.BorderColor3 = Color3.fromRGB(0, 0, 0)
dominusking.BorderSizePixel = 0
dominusking.Size = UDim2.new(0, 200, 0, 50)
dominusking.Position = UDim2.new(0, 0, 0, 0)
dominusking.AnchorPoint = Vector2.new(0, 0)
dominusking.Rotation = 0
dominusking.Visible = true
dominusking.ZIndex = 1
dominusking.AutomaticSize = Enum.AutomaticSize.None
dominusking.ClipsDescendants = false
dominusking.LayoutOrder = 0
dominusking.Active = true
dominusking.Selectable = true
dominusking.Modal = false
dominusking.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.dominusking.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.dominusking.LocalScript"


local draw_tool = Instance.new("TextButton")
draw_tool.Name = "draw tool"
draw_tool.Text = "Draw Tool.lua"
draw_tool.TextColor3 = Color3.fromRGB(0, 0, 0)
draw_tool.TextTransparency = 0
draw_tool.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
draw_tool.TextStrokeTransparency = 1
draw_tool.TextSize = 14
draw_tool.Font = Enum.Font.SourceSans
draw_tool.RichText = false
draw_tool.TextWrapped = false
draw_tool.TextScaled = false
draw_tool.TextXAlignment = Enum.TextXAlignment.Left
draw_tool.TextYAlignment = Enum.TextYAlignment.Center
draw_tool.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
draw_tool.BackgroundTransparency = 0
draw_tool.BorderColor3 = Color3.fromRGB(0, 0, 0)
draw_tool.BorderSizePixel = 0
draw_tool.Size = UDim2.new(0, 200, 0, 50)
draw_tool.Position = UDim2.new(0, 0, 0, 0)
draw_tool.AnchorPoint = Vector2.new(0, 0)
draw_tool.Rotation = 0
draw_tool.Visible = true
draw_tool.ZIndex = 1
draw_tool.AutomaticSize = Enum.AutomaticSize.None
draw_tool.ClipsDescendants = false
draw_tool.LayoutOrder = 0
draw_tool.Active = true
draw_tool.Selectable = true
draw_tool.Modal = false
draw_tool.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.draw tool.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.draw tool.LocalScript"


local excavator = Instance.new("TextButton")
excavator.Name = "excavator"
excavator.Text = "Excavator.txt"
excavator.TextColor3 = Color3.fromRGB(0, 0, 0)
excavator.TextTransparency = 0
excavator.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
excavator.TextStrokeTransparency = 1
excavator.TextSize = 14
excavator.Font = Enum.Font.SourceSans
excavator.RichText = false
excavator.TextWrapped = false
excavator.TextScaled = false
excavator.TextXAlignment = Enum.TextXAlignment.Left
excavator.TextYAlignment = Enum.TextYAlignment.Center
excavator.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
excavator.BackgroundTransparency = 0
excavator.BorderColor3 = Color3.fromRGB(0, 0, 0)
excavator.BorderSizePixel = 0
excavator.Size = UDim2.new(0, 200, 0, 50)
excavator.Position = UDim2.new(0, 0, 0, 0)
excavator.AnchorPoint = Vector2.new(0, 0)
excavator.Rotation = 0
excavator.Visible = true
excavator.ZIndex = 1
excavator.AutomaticSize = Enum.AutomaticSize.None
excavator.ClipsDescendants = false
excavator.LayoutOrder = 0
excavator.Active = true
excavator.Selectable = true
excavator.Modal = false
excavator.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.excavator.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.excavator.LocalScript"


local futuredestroyer = Instance.new("TextButton")
futuredestroyer.Name = "futuredestroyer"
futuredestroyer.Text = "Future Destroyer.lua"
futuredestroyer.TextColor3 = Color3.fromRGB(0, 0, 0)
futuredestroyer.TextTransparency = 0
futuredestroyer.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
futuredestroyer.TextStrokeTransparency = 1
futuredestroyer.TextSize = 14
futuredestroyer.Font = Enum.Font.SourceSans
futuredestroyer.RichText = false
futuredestroyer.TextWrapped = false
futuredestroyer.TextScaled = false
futuredestroyer.TextXAlignment = Enum.TextXAlignment.Left
futuredestroyer.TextYAlignment = Enum.TextYAlignment.Center
futuredestroyer.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
futuredestroyer.BackgroundTransparency = 0
futuredestroyer.BorderColor3 = Color3.fromRGB(0, 0, 0)
futuredestroyer.BorderSizePixel = 0
futuredestroyer.Size = UDim2.new(0, 200, 0, 50)
futuredestroyer.Position = UDim2.new(0, 0, 0, 0)
futuredestroyer.AnchorPoint = Vector2.new(0, 0)
futuredestroyer.Rotation = 0
futuredestroyer.Visible = true
futuredestroyer.ZIndex = 1
futuredestroyer.AutomaticSize = Enum.AutomaticSize.None
futuredestroyer.ClipsDescendants = false
futuredestroyer.LayoutOrder = 0
futuredestroyer.Active = true
futuredestroyer.Selectable = true
futuredestroyer.Modal = false
futuredestroyer.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.futuredestroyer.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.futuredestroyer.LocalScript"


local galaxytitan = Instance.new("TextButton")
galaxytitan.Name = "galaxytitan"
galaxytitan.Text = "Galaxy Titan.lua"
galaxytitan.TextColor3 = Color3.fromRGB(0, 0, 0)
galaxytitan.TextTransparency = 0
galaxytitan.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
galaxytitan.TextStrokeTransparency = 1
galaxytitan.TextSize = 14
galaxytitan.Font = Enum.Font.SourceSans
galaxytitan.RichText = false
galaxytitan.TextWrapped = false
galaxytitan.TextScaled = false
galaxytitan.TextXAlignment = Enum.TextXAlignment.Left
galaxytitan.TextYAlignment = Enum.TextYAlignment.Center
galaxytitan.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
galaxytitan.BackgroundTransparency = 0
galaxytitan.BorderColor3 = Color3.fromRGB(0, 0, 0)
galaxytitan.BorderSizePixel = 0
galaxytitan.Size = UDim2.new(0, 200, 0, 50)
galaxytitan.Position = UDim2.new(0, 0, 0, 0)
galaxytitan.AnchorPoint = Vector2.new(0, 0)
galaxytitan.Rotation = 0
galaxytitan.Visible = true
galaxytitan.ZIndex = 1
galaxytitan.AutomaticSize = Enum.AutomaticSize.None
galaxytitan.ClipsDescendants = false
galaxytitan.LayoutOrder = 0
galaxytitan.Active = true
galaxytitan.Selectable = true
galaxytitan.Modal = false
galaxytitan.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.galaxytitan.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.galaxytitan.LocalScript"


local gkv1 = Instance.new("TextButton")
gkv1.Name = "gkv1"
gkv1.Text = "Grab Knife V1.lua"
gkv1.TextColor3 = Color3.fromRGB(0, 0, 0)
gkv1.TextTransparency = 0
gkv1.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
gkv1.TextStrokeTransparency = 1
gkv1.TextSize = 14
gkv1.Font = Enum.Font.SourceSans
gkv1.RichText = false
gkv1.TextWrapped = false
gkv1.TextScaled = false
gkv1.TextXAlignment = Enum.TextXAlignment.Left
gkv1.TextYAlignment = Enum.TextYAlignment.Center
gkv1.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
gkv1.BackgroundTransparency = 0
gkv1.BorderColor3 = Color3.fromRGB(0, 0, 0)
gkv1.BorderSizePixel = 0
gkv1.Size = UDim2.new(0, 200, 0, 50)
gkv1.Position = UDim2.new(0, 0, 0, 0)
gkv1.AnchorPoint = Vector2.new(0, 0)
gkv1.Rotation = 0
gkv1.Visible = true
gkv1.ZIndex = 1
gkv1.AutomaticSize = Enum.AutomaticSize.None
gkv1.ClipsDescendants = false
gkv1.LayoutOrder = 0
gkv1.Active = true
gkv1.Selectable = true
gkv1.Modal = false
gkv1.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.gkv1.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.gkv1.LocalScript"


local gkv2 = Instance.new("TextButton")
gkv2.Name = "gkv2"
gkv2.Text = "Grab Knife V2.lua"
gkv2.TextColor3 = Color3.fromRGB(0, 0, 0)
gkv2.TextTransparency = 0
gkv2.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
gkv2.TextStrokeTransparency = 1
gkv2.TextSize = 14
gkv2.Font = Enum.Font.SourceSans
gkv2.RichText = false
gkv2.TextWrapped = false
gkv2.TextScaled = false
gkv2.TextXAlignment = Enum.TextXAlignment.Left
gkv2.TextYAlignment = Enum.TextYAlignment.Center
gkv2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
gkv2.BackgroundTransparency = 0
gkv2.BorderColor3 = Color3.fromRGB(0, 0, 0)
gkv2.BorderSizePixel = 0
gkv2.Size = UDim2.new(0, 200, 0, 50)
gkv2.Position = UDim2.new(0, 0, 0, 0)
gkv2.AnchorPoint = Vector2.new(0, 0)
gkv2.Rotation = 0
gkv2.Visible = true
gkv2.ZIndex = 1
gkv2.AutomaticSize = Enum.AutomaticSize.None
gkv2.ClipsDescendants = false
gkv2.LayoutOrder = 0
gkv2.Active = true
gkv2.Selectable = true
gkv2.Modal = false
gkv2.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.gkv2.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.gkv2.LocalScript"


local gkv3 = Instance.new("TextButton")
gkv3.Name = "gkv3"
gkv3.Text = "Grab Knife V3.lua"
gkv3.TextColor3 = Color3.fromRGB(0, 0, 0)
gkv3.TextTransparency = 0
gkv3.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
gkv3.TextStrokeTransparency = 1
gkv3.TextSize = 14
gkv3.Font = Enum.Font.SourceSans
gkv3.RichText = false
gkv3.TextWrapped = false
gkv3.TextScaled = false
gkv3.TextXAlignment = Enum.TextXAlignment.Left
gkv3.TextYAlignment = Enum.TextYAlignment.Center
gkv3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
gkv3.BackgroundTransparency = 0
gkv3.BorderColor3 = Color3.fromRGB(0, 0, 0)
gkv3.BorderSizePixel = 0
gkv3.Size = UDim2.new(0, 200, 0, 50)
gkv3.Position = UDim2.new(0, 0, 0, 0)
gkv3.AnchorPoint = Vector2.new(0, 0)
gkv3.Rotation = 0
gkv3.Visible = true
gkv3.ZIndex = 1
gkv3.AutomaticSize = Enum.AutomaticSize.None
gkv3.ClipsDescendants = false
gkv3.LayoutOrder = 0
gkv3.Active = true
gkv3.Selectable = true
gkv3.Modal = false
gkv3.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.gkv3.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.gkv3.LocalScript"


local gkv4 = Instance.new("TextButton")
gkv4.Name = "gkv4"
gkv4.Text = "Grab Knife V4.lua"
gkv4.TextColor3 = Color3.fromRGB(0, 0, 0)
gkv4.TextTransparency = 0
gkv4.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
gkv4.TextStrokeTransparency = 1
gkv4.TextSize = 14
gkv4.Font = Enum.Font.SourceSans
gkv4.RichText = false
gkv4.TextWrapped = false
gkv4.TextScaled = false
gkv4.TextXAlignment = Enum.TextXAlignment.Left
gkv4.TextYAlignment = Enum.TextYAlignment.Center
gkv4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
gkv4.BackgroundTransparency = 0
gkv4.BorderColor3 = Color3.fromRGB(0, 0, 0)
gkv4.BorderSizePixel = 0
gkv4.Size = UDim2.new(0, 200, 0, 50)
gkv4.Position = UDim2.new(0, 0, 0, 0)
gkv4.AnchorPoint = Vector2.new(0, 0)
gkv4.Rotation = 0
gkv4.Visible = true
gkv4.ZIndex = 1
gkv4.AutomaticSize = Enum.AutomaticSize.None
gkv4.ClipsDescendants = false
gkv4.LayoutOrder = 0
gkv4.Active = true
gkv4.Selectable = true
gkv4.Modal = false
gkv4.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.gkv4.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.gkv4.LocalScript"


local goner = Instance.new("TextButton")
goner.Name = "goner"
goner.Text = "Goner.lua"
goner.TextColor3 = Color3.fromRGB(0, 0, 0)
goner.TextTransparency = 0
goner.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
goner.TextStrokeTransparency = 1
goner.TextSize = 14
goner.Font = Enum.Font.SourceSans
goner.RichText = false
goner.TextWrapped = false
goner.TextScaled = false
goner.TextXAlignment = Enum.TextXAlignment.Left
goner.TextYAlignment = Enum.TextYAlignment.Center
goner.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
goner.BackgroundTransparency = 0
goner.BorderColor3 = Color3.fromRGB(0, 0, 0)
goner.BorderSizePixel = 0
goner.Size = UDim2.new(0, 200, 0, 50)
goner.Position = UDim2.new(0, 0, 0, 0)
goner.AnchorPoint = Vector2.new(0, 0)
goner.Rotation = 0
goner.Visible = true
goner.ZIndex = 1
goner.AutomaticSize = Enum.AutomaticSize.None
goner.ClipsDescendants = false
goner.LayoutOrder = 0
goner.Active = true
goner.Selectable = true
goner.Modal = false
goner.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.goner.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.goner.LocalScript"


local grandosla = Instance.new("TextButton")
grandosla.Name = "grandosla"
grandosla.Text = "Grandosla Tower.lua"
grandosla.TextColor3 = Color3.fromRGB(0, 0, 0)
grandosla.TextTransparency = 0
grandosla.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
grandosla.TextStrokeTransparency = 1
grandosla.TextSize = 14
grandosla.Font = Enum.Font.SourceSans
grandosla.RichText = false
grandosla.TextWrapped = false
grandosla.TextScaled = false
grandosla.TextXAlignment = Enum.TextXAlignment.Left
grandosla.TextYAlignment = Enum.TextYAlignment.Center
grandosla.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
grandosla.BackgroundTransparency = 0
grandosla.BorderColor3 = Color3.fromRGB(0, 0, 0)
grandosla.BorderSizePixel = 0
grandosla.Size = UDim2.new(0, 200, 0, 50)
grandosla.Position = UDim2.new(0, 0, 0, 0)
grandosla.AnchorPoint = Vector2.new(0, 0)
grandosla.Rotation = 0
grandosla.Visible = true
grandosla.ZIndex = 1
grandosla.AutomaticSize = Enum.AutomaticSize.None
grandosla.ClipsDescendants = false
grandosla.LayoutOrder = 0
grandosla.Active = true
grandosla.Selectable = true
grandosla.Modal = false
grandosla.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.grandosla.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.grandosla.LocalScript"


local guitar = Instance.new("TextButton")
guitar.Name = "guitar"
guitar.Text = "Guitar.lua"
guitar.TextColor3 = Color3.fromRGB(0, 0, 0)
guitar.TextTransparency = 0
guitar.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
guitar.TextStrokeTransparency = 1
guitar.TextSize = 14
guitar.Font = Enum.Font.SourceSans
guitar.RichText = false
guitar.TextWrapped = false
guitar.TextScaled = false
guitar.TextXAlignment = Enum.TextXAlignment.Left
guitar.TextYAlignment = Enum.TextYAlignment.Center
guitar.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
guitar.BackgroundTransparency = 0
guitar.BorderColor3 = Color3.fromRGB(0, 0, 0)
guitar.BorderSizePixel = 0
guitar.Size = UDim2.new(0, 200, 0, 50)
guitar.Position = UDim2.new(0, 0, 0, 0)
guitar.AnchorPoint = Vector2.new(0, 0)
guitar.Rotation = 0
guitar.Visible = true
guitar.ZIndex = 1
guitar.AutomaticSize = Enum.AutomaticSize.None
guitar.ClipsDescendants = false
guitar.LayoutOrder = 0
guitar.Active = true
guitar.Selectable = true
guitar.Modal = false
guitar.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.guitar.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.guitar.LocalScript"


local guns = Instance.new("TextButton")
guns.Name = "guns"
guns.Text = "Guns.txt"
guns.TextColor3 = Color3.fromRGB(0, 0, 0)
guns.TextTransparency = 0
guns.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
guns.TextStrokeTransparency = 1
guns.TextSize = 14
guns.Font = Enum.Font.SourceSans
guns.RichText = false
guns.TextWrapped = false
guns.TextScaled = false
guns.TextXAlignment = Enum.TextXAlignment.Left
guns.TextYAlignment = Enum.TextYAlignment.Center
guns.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
guns.BackgroundTransparency = 0
guns.BorderColor3 = Color3.fromRGB(0, 0, 0)
guns.BorderSizePixel = 0
guns.Size = UDim2.new(0, 200, 0, 50)
guns.Position = UDim2.new(0, 0, 0, 0)
guns.AnchorPoint = Vector2.new(0, 0)
guns.Rotation = 0
guns.Visible = true
guns.ZIndex = 1
guns.AutomaticSize = Enum.AutomaticSize.None
guns.ClipsDescendants = false
guns.LayoutOrder = 0
guns.Active = true
guns.Selectable = true
guns.Modal = false
guns.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.guns.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.guns.LocalScript"


local halosword = Instance.new("TextButton")
halosword.Name = "halosword"
halosword.Text = "AAA Halo Sword.lua"
halosword.TextColor3 = Color3.fromRGB(0, 0, 0)
halosword.TextTransparency = 0
halosword.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
halosword.TextStrokeTransparency = 1
halosword.TextSize = 14
halosword.Font = Enum.Font.SourceSans
halosword.RichText = false
halosword.TextWrapped = false
halosword.TextScaled = false
halosword.TextXAlignment = Enum.TextXAlignment.Left
halosword.TextYAlignment = Enum.TextYAlignment.Center
halosword.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
halosword.BackgroundTransparency = 0
halosword.BorderColor3 = Color3.fromRGB(0, 0, 0)
halosword.BorderSizePixel = 0
halosword.Size = UDim2.new(0, 200, 0, 50)
halosword.Position = UDim2.new(0, 0, 0, 0)
halosword.AnchorPoint = Vector2.new(0, 0)
halosword.Rotation = 0
halosword.Visible = true
halosword.ZIndex = 1
halosword.AutomaticSize = Enum.AutomaticSize.None
halosword.ClipsDescendants = false
halosword.LayoutOrder = 0
halosword.Active = true
halosword.Selectable = true
halosword.Modal = false
halosword.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.halosword.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.halosword.LocalScript"


local hexblade = Instance.new("TextButton")
hexblade.Name = "hexblade"
hexblade.Text = "A.X.R HexBlade.lua"
hexblade.TextColor3 = Color3.fromRGB(0, 0, 0)
hexblade.TextTransparency = 0
hexblade.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
hexblade.TextStrokeTransparency = 1
hexblade.TextSize = 14
hexblade.Font = Enum.Font.SourceSans
hexblade.RichText = false
hexblade.TextWrapped = false
hexblade.TextScaled = false
hexblade.TextXAlignment = Enum.TextXAlignment.Left
hexblade.TextYAlignment = Enum.TextYAlignment.Center
hexblade.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
hexblade.BackgroundTransparency = 0
hexblade.BorderColor3 = Color3.fromRGB(0, 0, 0)
hexblade.BorderSizePixel = 0
hexblade.Size = UDim2.new(0, 200, 0, 50)
hexblade.Position = UDim2.new(0, 0, 0, 0)
hexblade.AnchorPoint = Vector2.new(0, 0)
hexblade.Rotation = 0
hexblade.Visible = true
hexblade.ZIndex = 1
hexblade.AutomaticSize = Enum.AutomaticSize.None
hexblade.ClipsDescendants = false
hexblade.LayoutOrder = 0
hexblade.Active = true
hexblade.Selectable = true
hexblade.Modal = false
hexblade.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.hexblade.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.hexblade.LocalScript"


local hk416 = Instance.new("TextButton")
hk416.Name = "hk416"
hk416.Text = "HK416.lua"
hk416.TextColor3 = Color3.fromRGB(0, 0, 0)
hk416.TextTransparency = 0
hk416.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
hk416.TextStrokeTransparency = 1
hk416.TextSize = 14
hk416.Font = Enum.Font.SourceSans
hk416.RichText = false
hk416.TextWrapped = false
hk416.TextScaled = false
hk416.TextXAlignment = Enum.TextXAlignment.Left
hk416.TextYAlignment = Enum.TextYAlignment.Center
hk416.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
hk416.BackgroundTransparency = 0
hk416.BorderColor3 = Color3.fromRGB(0, 0, 0)
hk416.BorderSizePixel = 0
hk416.Size = UDim2.new(0, 200, 0, 50)
hk416.Position = UDim2.new(0, 0, 0, 0)
hk416.AnchorPoint = Vector2.new(0, 0)
hk416.Rotation = 0
hk416.Visible = true
hk416.ZIndex = 1
hk416.AutomaticSize = Enum.AutomaticSize.None
hk416.ClipsDescendants = false
hk416.LayoutOrder = 0
hk416.Active = true
hk416.Selectable = true
hk416.Modal = false
hk416.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.hk416.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.hk416.LocalScript"


local icecreamsword = Instance.new("TextButton")
icecreamsword.Name = "icecreamsword"
icecreamsword.Text = "Ice Cream Sword.lua"
icecreamsword.TextColor3 = Color3.fromRGB(0, 0, 0)
icecreamsword.TextTransparency = 0
icecreamsword.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
icecreamsword.TextStrokeTransparency = 1
icecreamsword.TextSize = 14
icecreamsword.Font = Enum.Font.SourceSans
icecreamsword.RichText = false
icecreamsword.TextWrapped = false
icecreamsword.TextScaled = false
icecreamsword.TextXAlignment = Enum.TextXAlignment.Left
icecreamsword.TextYAlignment = Enum.TextYAlignment.Center
icecreamsword.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
icecreamsword.BackgroundTransparency = 0
icecreamsword.BorderColor3 = Color3.fromRGB(0, 0, 0)
icecreamsword.BorderSizePixel = 0
icecreamsword.Size = UDim2.new(0, 200, 0, 50)
icecreamsword.Position = UDim2.new(0, 0, 0, 0)
icecreamsword.AnchorPoint = Vector2.new(0, 0)
icecreamsword.Rotation = 0
icecreamsword.Visible = true
icecreamsword.ZIndex = 1
icecreamsword.AutomaticSize = Enum.AutomaticSize.None
icecreamsword.ClipsDescendants = false
icecreamsword.LayoutOrder = 0
icecreamsword.Active = true
icecreamsword.Selectable = true
icecreamsword.Modal = false
icecreamsword.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.icecreamsword.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.icecreamsword.LocalScript"


local illuminati = Instance.new("TextButton")
illuminati.Name = "illuminati"
illuminati.Text = "The Illuminati.lua"
illuminati.TextColor3 = Color3.fromRGB(0, 0, 0)
illuminati.TextTransparency = 0
illuminati.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
illuminati.TextStrokeTransparency = 1
illuminati.TextSize = 14
illuminati.Font = Enum.Font.SourceSans
illuminati.RichText = false
illuminati.TextWrapped = false
illuminati.TextScaled = false
illuminati.TextXAlignment = Enum.TextXAlignment.Left
illuminati.TextYAlignment = Enum.TextYAlignment.Center
illuminati.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
illuminati.BackgroundTransparency = 0
illuminati.BorderColor3 = Color3.fromRGB(0, 0, 0)
illuminati.BorderSizePixel = 0
illuminati.Size = UDim2.new(0, 200, 0, 50)
illuminati.Position = UDim2.new(0, 0, 0, 0)
illuminati.AnchorPoint = Vector2.new(0, 0)
illuminati.Rotation = 0
illuminati.Visible = true
illuminati.ZIndex = 1
illuminati.AutomaticSize = Enum.AutomaticSize.None
illuminati.ClipsDescendants = false
illuminati.LayoutOrder = 0
illuminati.Active = true
illuminati.Selectable = true
illuminati.Modal = false
illuminati.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.illuminati.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.illuminati.LocalScript"


local infblade = Instance.new("TextButton")
infblade.Name = "infblade"
infblade.Text = "AAA infinity Blade.lua"
infblade.TextColor3 = Color3.fromRGB(0, 0, 0)
infblade.TextTransparency = 0
infblade.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
infblade.TextStrokeTransparency = 1
infblade.TextSize = 14
infblade.Font = Enum.Font.SourceSans
infblade.RichText = false
infblade.TextWrapped = false
infblade.TextScaled = false
infblade.TextXAlignment = Enum.TextXAlignment.Left
infblade.TextYAlignment = Enum.TextYAlignment.Center
infblade.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
infblade.BackgroundTransparency = 0
infblade.BorderColor3 = Color3.fromRGB(0, 0, 0)
infblade.BorderSizePixel = 0
infblade.Size = UDim2.new(0, 200, 0, 50)
infblade.Position = UDim2.new(0, 0, 0, 0)
infblade.AnchorPoint = Vector2.new(0, 0)
infblade.Rotation = 0
infblade.Visible = true
infblade.ZIndex = 1
infblade.AutomaticSize = Enum.AutomaticSize.None
infblade.ClipsDescendants = false
infblade.LayoutOrder = 0
infblade.Active = true
infblade.Selectable = true
infblade.Modal = false
infblade.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.infblade.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.infblade.LocalScript"


local johndoe = Instance.new("TextButton")
johndoe.Name = "johndoe"
johndoe.Text = "John Doe.lua"
johndoe.TextColor3 = Color3.fromRGB(0, 0, 0)
johndoe.TextTransparency = 0
johndoe.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
johndoe.TextStrokeTransparency = 1
johndoe.TextSize = 14
johndoe.Font = Enum.Font.SourceSans
johndoe.RichText = false
johndoe.TextWrapped = false
johndoe.TextScaled = false
johndoe.TextXAlignment = Enum.TextXAlignment.Left
johndoe.TextYAlignment = Enum.TextYAlignment.Center
johndoe.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
johndoe.BackgroundTransparency = 0
johndoe.BorderColor3 = Color3.fromRGB(0, 0, 0)
johndoe.BorderSizePixel = 0
johndoe.Size = UDim2.new(0, 200, 0, 50)
johndoe.Position = UDim2.new(0, 0, 0, 0)
johndoe.AnchorPoint = Vector2.new(0, 0)
johndoe.Rotation = 0
johndoe.Visible = true
johndoe.ZIndex = 1
johndoe.AutomaticSize = Enum.AutomaticSize.None
johndoe.ClipsDescendants = false
johndoe.LayoutOrder = 0
johndoe.Active = true
johndoe.Selectable = true
johndoe.Modal = false
johndoe.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.johndoe.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.johndoe.LocalScript"


local kdv2 = Instance.new("TextButton")
kdv2.Name = "kdv2"
kdv2.Text = "Krystal Dance V2.lua"
kdv2.TextColor3 = Color3.fromRGB(0, 0, 0)
kdv2.TextTransparency = 0
kdv2.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
kdv2.TextStrokeTransparency = 1
kdv2.TextSize = 14
kdv2.Font = Enum.Font.SourceSans
kdv2.RichText = false
kdv2.TextWrapped = false
kdv2.TextScaled = false
kdv2.TextXAlignment = Enum.TextXAlignment.Left
kdv2.TextYAlignment = Enum.TextYAlignment.Center
kdv2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
kdv2.BackgroundTransparency = 0
kdv2.BorderColor3 = Color3.fromRGB(0, 0, 0)
kdv2.BorderSizePixel = 0
kdv2.Size = UDim2.new(0, 200, 0, 50)
kdv2.Position = UDim2.new(0, 0, 0, 0)
kdv2.AnchorPoint = Vector2.new(0, 0)
kdv2.Rotation = 0
kdv2.Visible = true
kdv2.ZIndex = 1
kdv2.AutomaticSize = Enum.AutomaticSize.None
kdv2.ClipsDescendants = false
kdv2.LayoutOrder = 0
kdv2.Active = true
kdv2.Selectable = true
kdv2.Modal = false
kdv2.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.kdv2.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.kdv2.LocalScript"


local lamb_hover_bike = Instance.new("TextButton")
lamb_hover_bike.Name = "lamb hover bike"
lamb_hover_bike.Text = "A.X.R LAMB Hover Bile Class Cruiser.lua "
lamb_hover_bike.TextColor3 = Color3.fromRGB(0, 0, 0)
lamb_hover_bike.TextTransparency = 0
lamb_hover_bike.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
lamb_hover_bike.TextStrokeTransparency = 1
lamb_hover_bike.TextSize = 14
lamb_hover_bike.Font = Enum.Font.SourceSans
lamb_hover_bike.RichText = false
lamb_hover_bike.TextWrapped = false
lamb_hover_bike.TextScaled = false
lamb_hover_bike.TextXAlignment = Enum.TextXAlignment.Left
lamb_hover_bike.TextYAlignment = Enum.TextYAlignment.Center
lamb_hover_bike.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
lamb_hover_bike.BackgroundTransparency = 0
lamb_hover_bike.BorderColor3 = Color3.fromRGB(0, 0, 0)
lamb_hover_bike.BorderSizePixel = 0
lamb_hover_bike.Size = UDim2.new(0, 200, 0, 50)
lamb_hover_bike.Position = UDim2.new(0, 0, 0, 0)
lamb_hover_bike.AnchorPoint = Vector2.new(0, 0)
lamb_hover_bike.Rotation = 0
lamb_hover_bike.Visible = true
lamb_hover_bike.ZIndex = 1
lamb_hover_bike.AutomaticSize = Enum.AutomaticSize.None
lamb_hover_bike.ClipsDescendants = false
lamb_hover_bike.LayoutOrder = 0
lamb_hover_bike.Active = true
lamb_hover_bike.Selectable = true
lamb_hover_bike.Modal = false
lamb_hover_bike.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.lamb hover bike.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.lamb hover bike.LocalScript"


local luahammer = Instance.new("TextButton")
luahammer.Name = "luahammer"
luahammer.Text = "Lua Hammer.lua"
luahammer.TextColor3 = Color3.fromRGB(0, 0, 0)
luahammer.TextTransparency = 0
luahammer.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
luahammer.TextStrokeTransparency = 1
luahammer.TextSize = 14
luahammer.Font = Enum.Font.SourceSans
luahammer.RichText = false
luahammer.TextWrapped = false
luahammer.TextScaled = false
luahammer.TextXAlignment = Enum.TextXAlignment.Left
luahammer.TextYAlignment = Enum.TextYAlignment.Center
luahammer.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
luahammer.BackgroundTransparency = 0
luahammer.BorderColor3 = Color3.fromRGB(0, 0, 0)
luahammer.BorderSizePixel = 0
luahammer.Size = UDim2.new(0, 200, 0, 50)
luahammer.Position = UDim2.new(0, 0, 0, 0)
luahammer.AnchorPoint = Vector2.new(0, 0)
luahammer.Rotation = 0
luahammer.Visible = true
luahammer.ZIndex = 1
luahammer.AutomaticSize = Enum.AutomaticSize.None
luahammer.ClipsDescendants = false
luahammer.LayoutOrder = 0
luahammer.Active = true
luahammer.Selectable = true
luahammer.Modal = false
luahammer.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.luahammer.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.luahammer.LocalScript"


local mace = Instance.new("TextButton")
mace.Name = "mace"
mace.Text = "AAA Mace.lua"
mace.TextColor3 = Color3.fromRGB(0, 0, 0)
mace.TextTransparency = 0
mace.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
mace.TextStrokeTransparency = 1
mace.TextSize = 14
mace.Font = Enum.Font.SourceSans
mace.RichText = false
mace.TextWrapped = false
mace.TextScaled = false
mace.TextXAlignment = Enum.TextXAlignment.Left
mace.TextYAlignment = Enum.TextYAlignment.Center
mace.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
mace.BackgroundTransparency = 0
mace.BorderColor3 = Color3.fromRGB(0, 0, 0)
mace.BorderSizePixel = 0
mace.Size = UDim2.new(0, 200, 0, 50)
mace.Position = UDim2.new(0, 0, 0, 0)
mace.AnchorPoint = Vector2.new(0, 0)
mace.Rotation = 0
mace.Visible = true
mace.ZIndex = 1
mace.AutomaticSize = Enum.AutomaticSize.None
mace.ClipsDescendants = false
mace.LayoutOrder = 0
mace.Active = true
mace.Selectable = true
mace.Modal = false
mace.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.mace.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.mace.LocalScript"


local marksmanpistol = Instance.new("TextButton")
marksmanpistol.Name = "marksmanpistol"
marksmanpistol.Text = "Aces Marksman Pistol.lua"
marksmanpistol.TextColor3 = Color3.fromRGB(0, 0, 0)
marksmanpistol.TextTransparency = 0
marksmanpistol.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
marksmanpistol.TextStrokeTransparency = 1
marksmanpistol.TextSize = 14
marksmanpistol.Font = Enum.Font.SourceSans
marksmanpistol.RichText = false
marksmanpistol.TextWrapped = false
marksmanpistol.TextScaled = false
marksmanpistol.TextXAlignment = Enum.TextXAlignment.Left
marksmanpistol.TextYAlignment = Enum.TextYAlignment.Center
marksmanpistol.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
marksmanpistol.BackgroundTransparency = 0
marksmanpistol.BorderColor3 = Color3.fromRGB(0, 0, 0)
marksmanpistol.BorderSizePixel = 0
marksmanpistol.Size = UDim2.new(0, 200, 0, 50)
marksmanpistol.Position = UDim2.new(0, 0, 0, 0)
marksmanpistol.AnchorPoint = Vector2.new(0, 0)
marksmanpistol.Rotation = 0
marksmanpistol.Visible = true
marksmanpistol.ZIndex = 1
marksmanpistol.AutomaticSize = Enum.AutomaticSize.None
marksmanpistol.ClipsDescendants = false
marksmanpistol.LayoutOrder = 0
marksmanpistol.Active = true
marksmanpistol.Selectable = true
marksmanpistol.Modal = false
marksmanpistol.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.marksmanpistol.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.marksmanpistol.LocalScript"


local mashstick = Instance.new("TextButton")
mashstick.Name = "mashstick"
mashstick.Text = "AAA MASHSTICK.lua"
mashstick.TextColor3 = Color3.fromRGB(0, 0, 0)
mashstick.TextTransparency = 0
mashstick.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
mashstick.TextStrokeTransparency = 1
mashstick.TextSize = 14
mashstick.Font = Enum.Font.SourceSans
mashstick.RichText = false
mashstick.TextWrapped = false
mashstick.TextScaled = false
mashstick.TextXAlignment = Enum.TextXAlignment.Left
mashstick.TextYAlignment = Enum.TextYAlignment.Center
mashstick.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
mashstick.BackgroundTransparency = 0
mashstick.BorderColor3 = Color3.fromRGB(0, 0, 0)
mashstick.BorderSizePixel = 0
mashstick.Size = UDim2.new(0, 200, 0, 50)
mashstick.Position = UDim2.new(0, 0, 0, 0)
mashstick.AnchorPoint = Vector2.new(0, 0)
mashstick.Rotation = 0
mashstick.Visible = true
mashstick.ZIndex = 1
mashstick.AutomaticSize = Enum.AutomaticSize.None
mashstick.ClipsDescendants = false
mashstick.LayoutOrder = 0
mashstick.Active = true
mashstick.Selectable = true
mashstick.Modal = false
mashstick.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.mashstick.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.mashstick.LocalScript"


local otherguns = Instance.new("TextButton")
otherguns.Name = "otherguns"
otherguns.Text = "Other Guns.txt"
otherguns.TextColor3 = Color3.fromRGB(0, 0, 0)
otherguns.TextTransparency = 0
otherguns.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
otherguns.TextStrokeTransparency = 1
otherguns.TextSize = 14
otherguns.Font = Enum.Font.SourceSans
otherguns.RichText = false
otherguns.TextWrapped = false
otherguns.TextScaled = false
otherguns.TextXAlignment = Enum.TextXAlignment.Left
otherguns.TextYAlignment = Enum.TextYAlignment.Center
otherguns.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
otherguns.BackgroundTransparency = 0
otherguns.BorderColor3 = Color3.fromRGB(0, 0, 0)
otherguns.BorderSizePixel = 0
otherguns.Size = UDim2.new(0, 200, 0, 50)
otherguns.Position = UDim2.new(0, 0, 0, 0)
otherguns.AnchorPoint = Vector2.new(0, 0)
otherguns.Rotation = 0
otherguns.Visible = true
otherguns.ZIndex = 1
otherguns.AutomaticSize = Enum.AutomaticSize.None
otherguns.ClipsDescendants = false
otherguns.LayoutOrder = 0
otherguns.Active = true
otherguns.Selectable = true
otherguns.Modal = false
otherguns.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.otherguns.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.otherguns.LocalScript"


local pandasword = Instance.new("TextButton")
pandasword.Name = "pandasword"
pandasword.Text = "Panda Sword.lua"
pandasword.TextColor3 = Color3.fromRGB(0, 0, 0)
pandasword.TextTransparency = 0
pandasword.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
pandasword.TextStrokeTransparency = 1
pandasword.TextSize = 14
pandasword.Font = Enum.Font.SourceSans
pandasword.RichText = false
pandasword.TextWrapped = false
pandasword.TextScaled = false
pandasword.TextXAlignment = Enum.TextXAlignment.Left
pandasword.TextYAlignment = Enum.TextYAlignment.Center
pandasword.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
pandasword.BackgroundTransparency = 0
pandasword.BorderColor3 = Color3.fromRGB(0, 0, 0)
pandasword.BorderSizePixel = 0
pandasword.Size = UDim2.new(0, 200, 0, 50)
pandasword.Position = UDim2.new(0, 0, 0, 0)
pandasword.AnchorPoint = Vector2.new(0, 0)
pandasword.Rotation = 0
pandasword.Visible = true
pandasword.ZIndex = 1
pandasword.AutomaticSize = Enum.AutomaticSize.None
pandasword.ClipsDescendants = false
pandasword.LayoutOrder = 0
pandasword.Active = true
pandasword.Selectable = true
pandasword.Modal = false
pandasword.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.pandasword.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.pandasword.LocalScript"


local piercer = Instance.new("TextButton")
piercer.Name = "piercer"
piercer.Text = "A.X.R X-2 PIERCER.lua"
piercer.TextColor3 = Color3.fromRGB(0, 0, 0)
piercer.TextTransparency = 0
piercer.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
piercer.TextStrokeTransparency = 1
piercer.TextSize = 14
piercer.Font = Enum.Font.SourceSans
piercer.RichText = false
piercer.TextWrapped = false
piercer.TextScaled = false
piercer.TextXAlignment = Enum.TextXAlignment.Left
piercer.TextYAlignment = Enum.TextYAlignment.Center
piercer.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
piercer.BackgroundTransparency = 0
piercer.BorderColor3 = Color3.fromRGB(0, 0, 0)
piercer.BorderSizePixel = 0
piercer.Size = UDim2.new(0, 200, 0, 50)
piercer.Position = UDim2.new(0, 0, 0, 0)
piercer.AnchorPoint = Vector2.new(0, 0)
piercer.Rotation = 0
piercer.Visible = true
piercer.ZIndex = 1
piercer.AutomaticSize = Enum.AutomaticSize.None
piercer.ClipsDescendants = false
piercer.LayoutOrder = 0
piercer.Active = true
piercer.Selectable = true
piercer.Modal = false
piercer.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.piercer.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.piercer.LocalScript"


local polygoner = Instance.new("TextButton")
polygoner.Name = "polygoner"
polygoner.Text = "Poly Goner.txt"
polygoner.TextColor3 = Color3.fromRGB(0, 0, 0)
polygoner.TextTransparency = 0
polygoner.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
polygoner.TextStrokeTransparency = 1
polygoner.TextSize = 14
polygoner.Font = Enum.Font.SourceSans
polygoner.RichText = false
polygoner.TextWrapped = false
polygoner.TextScaled = false
polygoner.TextXAlignment = Enum.TextXAlignment.Left
polygoner.TextYAlignment = Enum.TextYAlignment.Center
polygoner.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
polygoner.BackgroundTransparency = 0
polygoner.BorderColor3 = Color3.fromRGB(0, 0, 0)
polygoner.BorderSizePixel = 0
polygoner.Size = UDim2.new(0, 200, 0, 50)
polygoner.Position = UDim2.new(0, 0, 0, 0)
polygoner.AnchorPoint = Vector2.new(0, 0)
polygoner.Rotation = 0
polygoner.Visible = true
polygoner.ZIndex = 1
polygoner.AutomaticSize = Enum.AutomaticSize.None
polygoner.ClipsDescendants = false
polygoner.LayoutOrder = 0
polygoner.Active = true
polygoner.Selectable = true
polygoner.Modal = false
polygoner.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.polygoner.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.polygoner.LocalScript"


local powsikle = Instance.new("TextButton")
powsikle.Name = "powsikle"
powsikle.Text = "AAAAAA Powsikle.lua"
powsikle.TextColor3 = Color3.fromRGB(0, 0, 0)
powsikle.TextTransparency = 0
powsikle.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
powsikle.TextStrokeTransparency = 1
powsikle.TextSize = 14
powsikle.Font = Enum.Font.SourceSans
powsikle.RichText = false
powsikle.TextWrapped = false
powsikle.TextScaled = false
powsikle.TextXAlignment = Enum.TextXAlignment.Left
powsikle.TextYAlignment = Enum.TextYAlignment.Center
powsikle.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
powsikle.BackgroundTransparency = 0
powsikle.BorderColor3 = Color3.fromRGB(0, 0, 0)
powsikle.BorderSizePixel = 0
powsikle.Size = UDim2.new(0, 200, 0, 50)
powsikle.Position = UDim2.new(0, 0, 0, 0)
powsikle.AnchorPoint = Vector2.new(0, 0)
powsikle.Rotation = 0
powsikle.Visible = true
powsikle.ZIndex = 1
powsikle.AutomaticSize = Enum.AutomaticSize.None
powsikle.ClipsDescendants = false
powsikle.LayoutOrder = 0
powsikle.Active = true
powsikle.Selectable = true
powsikle.Modal = false
powsikle.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.powsikle.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.powsikle.LocalScript"


local primadon = Instance.new("TextButton")
primadon.Name = "primadon"
primadon.Text = "Primadon.txt"
primadon.TextColor3 = Color3.fromRGB(0, 0, 0)
primadon.TextTransparency = 0
primadon.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
primadon.TextStrokeTransparency = 1
primadon.TextSize = 14
primadon.Font = Enum.Font.SourceSans
primadon.RichText = false
primadon.TextWrapped = false
primadon.TextScaled = false
primadon.TextXAlignment = Enum.TextXAlignment.Left
primadon.TextYAlignment = Enum.TextYAlignment.Center
primadon.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
primadon.BackgroundTransparency = 0
primadon.BorderColor3 = Color3.fromRGB(0, 0, 0)
primadon.BorderSizePixel = 0
primadon.Size = UDim2.new(0, 200, 0, 50)
primadon.Position = UDim2.new(0, 0, 0, 0)
primadon.AnchorPoint = Vector2.new(0, 0)
primadon.Rotation = 0
primadon.Visible = true
primadon.ZIndex = 1
primadon.AutomaticSize = Enum.AutomaticSize.None
primadon.ClipsDescendants = false
primadon.LayoutOrder = 0
primadon.Active = true
primadon.Selectable = true
primadon.Modal = false
primadon.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.primadon.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.primadon.LocalScript"


local project_2 = Instance.new("TextButton")
project_2.Name = "project 2"
project_2.Text = "AAA PROJECT 2.lua"
project_2.TextColor3 = Color3.fromRGB(0, 0, 0)
project_2.TextTransparency = 0
project_2.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
project_2.TextStrokeTransparency = 1
project_2.TextSize = 14
project_2.Font = Enum.Font.SourceSans
project_2.RichText = false
project_2.TextWrapped = false
project_2.TextScaled = false
project_2.TextXAlignment = Enum.TextXAlignment.Left
project_2.TextYAlignment = Enum.TextYAlignment.Center
project_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
project_2.BackgroundTransparency = 0
project_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
project_2.BorderSizePixel = 0
project_2.Size = UDim2.new(0, 200, 0, 50)
project_2.Position = UDim2.new(0, 0, 0, 0)
project_2.AnchorPoint = Vector2.new(0, 0)
project_2.Rotation = 0
project_2.Visible = true
project_2.ZIndex = 1
project_2.AutomaticSize = Enum.AutomaticSize.None
project_2.ClipsDescendants = false
project_2.LayoutOrder = 0
project_2.Active = true
project_2.Selectable = true
project_2.Modal = false
project_2.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.project 2.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.project 2.LocalScript"


local ravengerclaws = Instance.new("TextButton")
ravengerclaws.Name = "ravengerclaws"
ravengerclaws.Text = "Ravenger Claws.lua"
ravengerclaws.TextColor3 = Color3.fromRGB(0, 0, 0)
ravengerclaws.TextTransparency = 0
ravengerclaws.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
ravengerclaws.TextStrokeTransparency = 1
ravengerclaws.TextSize = 14
ravengerclaws.Font = Enum.Font.SourceSans
ravengerclaws.RichText = false
ravengerclaws.TextWrapped = false
ravengerclaws.TextScaled = false
ravengerclaws.TextXAlignment = Enum.TextXAlignment.Left
ravengerclaws.TextYAlignment = Enum.TextYAlignment.Center
ravengerclaws.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ravengerclaws.BackgroundTransparency = 0
ravengerclaws.BorderColor3 = Color3.fromRGB(0, 0, 0)
ravengerclaws.BorderSizePixel = 0
ravengerclaws.Size = UDim2.new(0, 200, 0, 50)
ravengerclaws.Position = UDim2.new(0, 0, 0, 0)
ravengerclaws.AnchorPoint = Vector2.new(0, 0)
ravengerclaws.Rotation = 0
ravengerclaws.Visible = true
ravengerclaws.ZIndex = 1
ravengerclaws.AutomaticSize = Enum.AutomaticSize.None
ravengerclaws.ClipsDescendants = false
ravengerclaws.LayoutOrder = 0
ravengerclaws.Active = true
ravengerclaws.Selectable = true
ravengerclaws.Modal = false
ravengerclaws.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.ravengerclaws.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.ravengerclaws.LocalScript"


local reminton700 = Instance.new("TextButton")
reminton700.Name = "reminton700"
reminton700.Text = "Remington 700.lua"
reminton700.TextColor3 = Color3.fromRGB(0, 0, 0)
reminton700.TextTransparency = 0
reminton700.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
reminton700.TextStrokeTransparency = 1
reminton700.TextSize = 14
reminton700.Font = Enum.Font.SourceSans
reminton700.RichText = false
reminton700.TextWrapped = false
reminton700.TextScaled = false
reminton700.TextXAlignment = Enum.TextXAlignment.Left
reminton700.TextYAlignment = Enum.TextYAlignment.Center
reminton700.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
reminton700.BackgroundTransparency = 0
reminton700.BorderColor3 = Color3.fromRGB(0, 0, 0)
reminton700.BorderSizePixel = 0
reminton700.Size = UDim2.new(0, 200, 0, 50)
reminton700.Position = UDim2.new(0, 0, 0, 0)
reminton700.AnchorPoint = Vector2.new(0, 0)
reminton700.Rotation = 0
reminton700.Visible = true
reminton700.ZIndex = 1
reminton700.AutomaticSize = Enum.AutomaticSize.None
reminton700.ClipsDescendants = false
reminton700.LayoutOrder = 0
reminton700.Active = true
reminton700.Selectable = true
reminton700.Modal = false
reminton700.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.reminton700.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.reminton700.LocalScript"


local roxploit6 = Instance.new("TextButton")
roxploit6.Name = "roxploit6"
roxploit6.Text = "Ro Xploit V6(Bit Broken).lua"
roxploit6.TextColor3 = Color3.fromRGB(0, 0, 0)
roxploit6.TextTransparency = 0
roxploit6.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
roxploit6.TextStrokeTransparency = 1
roxploit6.TextSize = 14
roxploit6.Font = Enum.Font.SourceSans
roxploit6.RichText = false
roxploit6.TextWrapped = false
roxploit6.TextScaled = false
roxploit6.TextXAlignment = Enum.TextXAlignment.Left
roxploit6.TextYAlignment = Enum.TextYAlignment.Center
roxploit6.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
roxploit6.BackgroundTransparency = 0
roxploit6.BorderColor3 = Color3.fromRGB(0, 0, 0)
roxploit6.BorderSizePixel = 0
roxploit6.Size = UDim2.new(0, 200, 0, 50)
roxploit6.Position = UDim2.new(0, 0, 0, 0)
roxploit6.AnchorPoint = Vector2.new(0, 0)
roxploit6.Rotation = 0
roxploit6.Visible = true
roxploit6.ZIndex = 1
roxploit6.AutomaticSize = Enum.AutomaticSize.None
roxploit6.ClipsDescendants = false
roxploit6.LayoutOrder = 0
roxploit6.Active = true
roxploit6.Selectable = true
roxploit6.Modal = false
roxploit6.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.roxploit6.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.roxploit6.LocalScript"


local sbshotgun = Instance.new("TextButton")
sbshotgun.Name = "sbshotgun"
sbshotgun.Text = "SB Shotgun.lua"
sbshotgun.TextColor3 = Color3.fromRGB(0, 0, 0)
sbshotgun.TextTransparency = 0
sbshotgun.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
sbshotgun.TextStrokeTransparency = 1
sbshotgun.TextSize = 14
sbshotgun.Font = Enum.Font.SourceSans
sbshotgun.RichText = false
sbshotgun.TextWrapped = false
sbshotgun.TextScaled = false
sbshotgun.TextXAlignment = Enum.TextXAlignment.Left
sbshotgun.TextYAlignment = Enum.TextYAlignment.Center
sbshotgun.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
sbshotgun.BackgroundTransparency = 0
sbshotgun.BorderColor3 = Color3.fromRGB(0, 0, 0)
sbshotgun.BorderSizePixel = 0
sbshotgun.Size = UDim2.new(0, 200, 0, 50)
sbshotgun.Position = UDim2.new(0, 0, 0, 0)
sbshotgun.AnchorPoint = Vector2.new(0, 0)
sbshotgun.Rotation = 0
sbshotgun.Visible = true
sbshotgun.ZIndex = 1
sbshotgun.AutomaticSize = Enum.AutomaticSize.None
sbshotgun.ClipsDescendants = false
sbshotgun.LayoutOrder = 0
sbshotgun.Active = true
sbshotgun.Selectable = true
sbshotgun.Modal = false
sbshotgun.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.sbshotgun.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.sbshotgun.LocalScript"


local sender = Instance.new("TextButton")
sender.Name = "sender"
sender.Text = "A.X.R FS-627-SENDER.lua"
sender.TextColor3 = Color3.fromRGB(0, 0, 0)
sender.TextTransparency = 0
sender.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
sender.TextStrokeTransparency = 1
sender.TextSize = 14
sender.Font = Enum.Font.SourceSans
sender.RichText = false
sender.TextWrapped = false
sender.TextScaled = false
sender.TextXAlignment = Enum.TextXAlignment.Left
sender.TextYAlignment = Enum.TextYAlignment.Center
sender.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
sender.BackgroundTransparency = 0
sender.BorderColor3 = Color3.fromRGB(0, 0, 0)
sender.BorderSizePixel = 0
sender.Size = UDim2.new(0, 200, 0, 50)
sender.Position = UDim2.new(0, 0, 0, 0)
sender.AnchorPoint = Vector2.new(0, 0)
sender.Rotation = 0
sender.Visible = true
sender.ZIndex = 1
sender.AutomaticSize = Enum.AutomaticSize.None
sender.ClipsDescendants = false
sender.LayoutOrder = 0
sender.Active = true
sender.Selectable = true
sender.Modal = false
sender.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.sender.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.sender.LocalScript"


local shedletskyrage = Instance.new("TextButton")
shedletskyrage.Name = "shedletskyrage"
shedletskyrage.Text = "Shedletsky Rage.lua"
shedletskyrage.TextColor3 = Color3.fromRGB(0, 0, 0)
shedletskyrage.TextTransparency = 0
shedletskyrage.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
shedletskyrage.TextStrokeTransparency = 1
shedletskyrage.TextSize = 14
shedletskyrage.Font = Enum.Font.SourceSans
shedletskyrage.RichText = false
shedletskyrage.TextWrapped = false
shedletskyrage.TextScaled = false
shedletskyrage.TextXAlignment = Enum.TextXAlignment.Left
shedletskyrage.TextYAlignment = Enum.TextYAlignment.Center
shedletskyrage.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
shedletskyrage.BackgroundTransparency = 0
shedletskyrage.BorderColor3 = Color3.fromRGB(0, 0, 0)
shedletskyrage.BorderSizePixel = 0
shedletskyrage.Size = UDim2.new(0, 200, 0, 50)
shedletskyrage.Position = UDim2.new(0, 0, 0, 0)
shedletskyrage.AnchorPoint = Vector2.new(0, 0)
shedletskyrage.Rotation = 0
shedletskyrage.Visible = true
shedletskyrage.ZIndex = 1
shedletskyrage.AutomaticSize = Enum.AutomaticSize.None
shedletskyrage.ClipsDescendants = false
shedletskyrage.LayoutOrder = 0
shedletskyrage.Active = true
shedletskyrage.Selectable = true
shedletskyrage.Modal = false
shedletskyrage.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.shedletskyrage.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.shedletskyrage.LocalScript"


local sindragon = Instance.new("TextButton")
sindragon.Name = "sindragon"
sindragon.Text = "Sin Dragon.lua"
sindragon.TextColor3 = Color3.fromRGB(0, 0, 0)
sindragon.TextTransparency = 0
sindragon.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
sindragon.TextStrokeTransparency = 1
sindragon.TextSize = 14
sindragon.Font = Enum.Font.SourceSans
sindragon.RichText = false
sindragon.TextWrapped = false
sindragon.TextScaled = false
sindragon.TextXAlignment = Enum.TextXAlignment.Left
sindragon.TextYAlignment = Enum.TextYAlignment.Center
sindragon.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
sindragon.BackgroundTransparency = 0
sindragon.BorderColor3 = Color3.fromRGB(0, 0, 0)
sindragon.BorderSizePixel = 0
sindragon.Size = UDim2.new(0, 200, 0, 50)
sindragon.Position = UDim2.new(0, 0, 0, 0)
sindragon.AnchorPoint = Vector2.new(0, 0)
sindragon.Rotation = 0
sindragon.Visible = true
sindragon.ZIndex = 1
sindragon.AutomaticSize = Enum.AutomaticSize.None
sindragon.ClipsDescendants = false
sindragon.LayoutOrder = 0
sindragon.Active = true
sindragon.Selectable = true
sindragon.Modal = false
sindragon.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.sindragon.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.sindragon.LocalScript"


local spiderbot = Instance.new("TextButton")
spiderbot.Name = "spiderbot"
spiderbot.Text = "Spider Bot.lua"
spiderbot.TextColor3 = Color3.fromRGB(0, 0, 0)
spiderbot.TextTransparency = 0
spiderbot.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
spiderbot.TextStrokeTransparency = 1
spiderbot.TextSize = 14
spiderbot.Font = Enum.Font.SourceSans
spiderbot.RichText = false
spiderbot.TextWrapped = false
spiderbot.TextScaled = false
spiderbot.TextXAlignment = Enum.TextXAlignment.Left
spiderbot.TextYAlignment = Enum.TextYAlignment.Center
spiderbot.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
spiderbot.BackgroundTransparency = 0
spiderbot.BorderColor3 = Color3.fromRGB(0, 0, 0)
spiderbot.BorderSizePixel = 0
spiderbot.Size = UDim2.new(0, 200, 0, 50)
spiderbot.Position = UDim2.new(0, 0, 0, 0)
spiderbot.AnchorPoint = Vector2.new(0, 0)
spiderbot.Rotation = 0
spiderbot.Visible = true
spiderbot.ZIndex = 1
spiderbot.AutomaticSize = Enum.AutomaticSize.None
spiderbot.ClipsDescendants = false
spiderbot.LayoutOrder = 0
spiderbot.Active = true
spiderbot.Selectable = true
spiderbot.Modal = false
spiderbot.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.spiderbot.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.spiderbot.LocalScript"


local stummy_gun = Instance.new("TextButton")
stummy_gun.Name = "stummy gun"
stummy_gun.Text = "Stummy Guns.txt"
stummy_gun.TextColor3 = Color3.fromRGB(0, 0, 0)
stummy_gun.TextTransparency = 0
stummy_gun.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
stummy_gun.TextStrokeTransparency = 1
stummy_gun.TextSize = 14
stummy_gun.Font = Enum.Font.SourceSans
stummy_gun.RichText = false
stummy_gun.TextWrapped = false
stummy_gun.TextScaled = false
stummy_gun.TextXAlignment = Enum.TextXAlignment.Left
stummy_gun.TextYAlignment = Enum.TextYAlignment.Center
stummy_gun.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
stummy_gun.BackgroundTransparency = 0
stummy_gun.BorderColor3 = Color3.fromRGB(0, 0, 0)
stummy_gun.BorderSizePixel = 0
stummy_gun.Size = UDim2.new(0, 200, 0, 50)
stummy_gun.Position = UDim2.new(0, 0, 0, 0)
stummy_gun.AnchorPoint = Vector2.new(0, 0)
stummy_gun.Rotation = 0
stummy_gun.Visible = true
stummy_gun.ZIndex = 1
stummy_gun.AutomaticSize = Enum.AutomaticSize.None
stummy_gun.ClipsDescendants = false
stummy_gun.LayoutOrder = 0
stummy_gun.Active = true
stummy_gun.Selectable = true
stummy_gun.Modal = false
stummy_gun.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.stummy gun.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.stummy gun.LocalScript"


local t0pk3k3_0 = Instance.new("TextButton")
t0pk3k3_0.Name = "t0pk3k3.0"
t0pk3k3_0.Text = "T0PK3K V3.lua"
t0pk3k3_0.TextColor3 = Color3.fromRGB(0, 0, 0)
t0pk3k3_0.TextTransparency = 0
t0pk3k3_0.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
t0pk3k3_0.TextStrokeTransparency = 1
t0pk3k3_0.TextSize = 14
t0pk3k3_0.Font = Enum.Font.SourceSans
t0pk3k3_0.RichText = false
t0pk3k3_0.TextWrapped = false
t0pk3k3_0.TextScaled = false
t0pk3k3_0.TextXAlignment = Enum.TextXAlignment.Left
t0pk3k3_0.TextYAlignment = Enum.TextYAlignment.Center
t0pk3k3_0.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
t0pk3k3_0.BackgroundTransparency = 0
t0pk3k3_0.BorderColor3 = Color3.fromRGB(0, 0, 0)
t0pk3k3_0.BorderSizePixel = 0
t0pk3k3_0.Size = UDim2.new(0, 200, 0, 50)
t0pk3k3_0.Position = UDim2.new(0, 0, 0, 0)
t0pk3k3_0.AnchorPoint = Vector2.new(0, 0)
t0pk3k3_0.Rotation = 0
t0pk3k3_0.Visible = true
t0pk3k3_0.ZIndex = 1
t0pk3k3_0.AutomaticSize = Enum.AutomaticSize.None
t0pk3k3_0.ClipsDescendants = false
t0pk3k3_0.LayoutOrder = 0
t0pk3k3_0.Active = true
t0pk3k3_0.Selectable = true
t0pk3k3_0.Modal = false
t0pk3k3_0.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.t0pk3k3.0.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.t0pk3k3.0.LocalScript"


local thedarkness = Instance.new("TextButton")
thedarkness.Name = "thedarkness"
thedarkness.Text = "AAAAAAAAA The Darkness.lua"
thedarkness.TextColor3 = Color3.fromRGB(0, 0, 0)
thedarkness.TextTransparency = 0
thedarkness.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
thedarkness.TextStrokeTransparency = 1
thedarkness.TextSize = 14
thedarkness.Font = Enum.Font.SourceSans
thedarkness.RichText = false
thedarkness.TextWrapped = false
thedarkness.TextScaled = false
thedarkness.TextXAlignment = Enum.TextXAlignment.Left
thedarkness.TextYAlignment = Enum.TextYAlignment.Center
thedarkness.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
thedarkness.BackgroundTransparency = 0
thedarkness.BorderColor3 = Color3.fromRGB(0, 0, 0)
thedarkness.BorderSizePixel = 0
thedarkness.Size = UDim2.new(0, 200, 0, 50)
thedarkness.Position = UDim2.new(0, 0, 0, 0)
thedarkness.AnchorPoint = Vector2.new(0, 0)
thedarkness.Rotation = 0
thedarkness.Visible = true
thedarkness.ZIndex = 1
thedarkness.AutomaticSize = Enum.AutomaticSize.None
thedarkness.ClipsDescendants = false
thedarkness.LayoutOrder = 0
thedarkness.Active = true
thedarkness.Selectable = true
thedarkness.Modal = false
thedarkness.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.thedarkness.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.thedarkness.LocalScript"


local thomas = Instance.new("TextButton")
thomas.Name = "thomas"
thomas.Text = "Thomas The Dank Engine.lua"
thomas.TextColor3 = Color3.fromRGB(0, 0, 0)
thomas.TextTransparency = 0
thomas.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
thomas.TextStrokeTransparency = 1
thomas.TextSize = 14
thomas.Font = Enum.Font.SourceSans
thomas.RichText = false
thomas.TextWrapped = false
thomas.TextScaled = false
thomas.TextXAlignment = Enum.TextXAlignment.Left
thomas.TextYAlignment = Enum.TextYAlignment.Center
thomas.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
thomas.BackgroundTransparency = 0
thomas.BorderColor3 = Color3.fromRGB(0, 0, 0)
thomas.BorderSizePixel = 0
thomas.Size = UDim2.new(0, 200, 0, 50)
thomas.Position = UDim2.new(0, 0, 0, 0)
thomas.AnchorPoint = Vector2.new(0, 0)
thomas.Rotation = 0
thomas.Visible = true
thomas.ZIndex = 1
thomas.AutomaticSize = Enum.AutomaticSize.None
thomas.ClipsDescendants = false
thomas.LayoutOrder = 0
thomas.Active = true
thomas.Selectable = true
thomas.Modal = false
thomas.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.thomas.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.thomas.LocalScript"


local timeblast = Instance.new("TextButton")
timeblast.Name = "timeblast"
timeblast.Text = "Time Blast.lua"
timeblast.TextColor3 = Color3.fromRGB(0, 0, 0)
timeblast.TextTransparency = 0
timeblast.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
timeblast.TextStrokeTransparency = 1
timeblast.TextSize = 14
timeblast.Font = Enum.Font.SourceSans
timeblast.RichText = false
timeblast.TextWrapped = false
timeblast.TextScaled = false
timeblast.TextXAlignment = Enum.TextXAlignment.Left
timeblast.TextYAlignment = Enum.TextYAlignment.Center
timeblast.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
timeblast.BackgroundTransparency = 0
timeblast.BorderColor3 = Color3.fromRGB(0, 0, 0)
timeblast.BorderSizePixel = 0
timeblast.Size = UDim2.new(0, 200, 0, 50)
timeblast.Position = UDim2.new(0, 0, 0, 0)
timeblast.AnchorPoint = Vector2.new(0, 0)
timeblast.Rotation = 0
timeblast.Visible = true
timeblast.ZIndex = 1
timeblast.AutomaticSize = Enum.AutomaticSize.None
timeblast.ClipsDescendants = false
timeblast.LayoutOrder = 0
timeblast.Active = true
timeblast.Selectable = true
timeblast.Modal = false
timeblast.Parent = scripts
-- script preserved: "button"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.timeblast.button"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.executor.scripts.timeblast.LocalScript"



local stroke_5 = Instance.new("Frame")
stroke_5.Name = "stroke"
stroke_5.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
stroke_5.BackgroundTransparency = 1
stroke_5.BorderColor3 = Color3.fromRGB(0, 0, 0)
stroke_5.BorderSizePixel = 0
stroke_5.Size = UDim2.new(0, 100, 0, 324)
stroke_5.Position = UDim2.new(0.78793776035308838, 0, 0.034782607108354568, 0)
stroke_5.AnchorPoint = Vector2.new(0, 0)
stroke_5.Rotation = 0
stroke_5.Visible = true
stroke_5.ZIndex = 1
stroke_5.AutomaticSize = Enum.AutomaticSize.None
stroke_5.ClipsDescendants = false
stroke_5.LayoutOrder = 0
stroke_5.Active = true
stroke_5.Selectable = false
stroke_5.Parent = executor
local UIStroke_3 = Instance.new("UIStroke")
UIStroke_3.Name = "UIStroke"
UIStroke_3.Enabled = true
UIStroke_3.ZIndex = 1
UIStroke_3.Parent = stroke_5


local scrollbarback_4 = Instance.new("Frame")
scrollbarback_4.Name = "scrollbarback"
scrollbarback_4.BackgroundColor3 = Color3.fromRGB(240, 240, 240)
scrollbarback_4.BackgroundTransparency = 0
scrollbarback_4.BorderColor3 = Color3.fromRGB(0, 0, 0)
scrollbarback_4.BorderSizePixel = 0
scrollbarback_4.Size = UDim2.new(0, 7, 0, 326)
scrollbarback_4.Position = UDim2.new(0.94941633939743042, 0, 0.034608703106641769, 0)
scrollbarback_4.AnchorPoint = Vector2.new(0, 0)
scrollbarback_4.Rotation = 0
scrollbarback_4.Visible = true
scrollbarback_4.ZIndex = 1
scrollbarback_4.AutomaticSize = Enum.AutomaticSize.None
scrollbarback_4.ClipsDescendants = false
scrollbarback_4.LayoutOrder = 0
scrollbarback_4.Active = true
scrollbarback_4.Selectable = false
scrollbarback_4.Parent = executor

local stroke_6 = Instance.new("Frame")
stroke_6.Name = "stroke"
stroke_6.BackgroundColor3 = Color3.fromRGB(104, 104, 104)
stroke_6.BackgroundTransparency = 0
stroke_6.BorderColor3 = Color3.fromRGB(0, 0, 0)
stroke_6.BorderSizePixel = 0
stroke_6.Size = UDim2.new(0, 388, 0, 1)
stroke_6.Position = UDim2.new(0.012000000104308128, 0, 0.032000001519918442, 1)
stroke_6.AnchorPoint = Vector2.new(0, 0)
stroke_6.Rotation = 0
stroke_6.Visible = true
stroke_6.ZIndex = 1
stroke_6.AutomaticSize = Enum.AutomaticSize.None
stroke_6.ClipsDescendants = false
stroke_6.LayoutOrder = 0
stroke_6.Active = true
stroke_6.Selectable = false
stroke_6.Parent = executor

local stroke_7 = Instance.new("Frame")
stroke_7.Name = "stroke"
stroke_7.BackgroundColor3 = Color3.fromRGB(104, 104, 104)
stroke_7.BackgroundTransparency = 0
stroke_7.BorderColor3 = Color3.fromRGB(0, 0, 0)
stroke_7.BorderSizePixel = 0
stroke_7.Size = UDim2.new(0, 1, 0, 206)
stroke_7.Position = UDim2.new(0.012000000104308128, 0, 0.032000001519918442, 0)
stroke_7.AnchorPoint = Vector2.new(0, 0)
stroke_7.Rotation = 0
stroke_7.Visible = true
stroke_7.ZIndex = 1
stroke_7.AutomaticSize = Enum.AutomaticSize.None
stroke_7.ClipsDescendants = false
stroke_7.LayoutOrder = 0
stroke_7.Active = true
stroke_7.Selectable = false
stroke_7.Parent = executor


local package_2 = Instance.new("Frame")
package_2.Name = "package"
package_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
package_2.BackgroundTransparency = 0
package_2.BorderColor3 = Color3.fromRGB(205, 205, 205)
package_2.BorderSizePixel = 1
package_2.Size = UDim2.new(0, 514, 0, 345)
package_2.Position = UDim2.new(-1.173753005900835e-07, 3, 0.065297387540340424, 0)
package_2.AnchorPoint = Vector2.new(0, 0)
package_2.Rotation = 0
package_2.Visible = false
package_2.ZIndex = 1
package_2.AutomaticSize = Enum.AutomaticSize.None
package_2.ClipsDescendants = false
package_2.LayoutOrder = 0
package_2.Active = true
package_2.Selectable = false
package_2.Parent = back
local scrollbarback_5 = Instance.new("Frame")
scrollbarback_5.Name = "scrollbarback"
scrollbarback_5.BackgroundColor3 = Color3.fromRGB(240, 240, 240)
scrollbarback_5.BackgroundTransparency = 0
scrollbarback_5.BorderColor3 = Color3.fromRGB(0, 0, 0)
scrollbarback_5.BorderSizePixel = 0
scrollbarback_5.Size = UDim2.new(0, 16, 0, 338)
scrollbarback_5.Position = UDim2.new(0.64980542659759521, 0, 0.011594114825129509, 0)
scrollbarback_5.AnchorPoint = Vector2.new(0, 0)
scrollbarback_5.Rotation = 0
scrollbarback_5.Visible = true
scrollbarback_5.ZIndex = 1
scrollbarback_5.AutomaticSize = Enum.AutomaticSize.None
scrollbarback_5.ClipsDescendants = false
scrollbarback_5.LayoutOrder = 0
scrollbarback_5.Active = true
scrollbarback_5.Selectable = false
scrollbarback_5.Parent = package_2

local package_3 = Instance.new("ScrollingFrame")
package_3.Name = "package"
package_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
package_3.BackgroundTransparency = 1
package_3.BorderColor3 = Color3.fromRGB(0, 0, 0)
package_3.BorderSizePixel = 0
package_3.Size = UDim2.new(0, 336, 0, 333)
package_3.Position = UDim2.new(0.013618676923215389, 0, 0.011594114825129509, 0)
package_3.AnchorPoint = Vector2.new(0, 0)
package_3.Rotation = 0
package_3.Visible = true
package_3.ZIndex = 1
package_3.AutomaticSize = Enum.AutomaticSize.None
package_3.ClipsDescendants = true
package_3.LayoutOrder = 0
package_3.Active = true
package_3.Selectable = true
package_3.CanvasSize = UDim2.new(0, 0, 0, 0)
package_3.CanvasPosition = Vector2.new(0, 0)
package_3.ScrollingDirection = Enum.ScrollingDirection.XY
package_3.ScrollBarThickness = 2
package_3.Parent = package_2
local UIGridLayout_3 = Instance.new("UIGridLayout")
UIGridLayout_3.Name = "UIGridLayout"
UIGridLayout_3.FillDirection = Enum.FillDirection.Horizontal
UIGridLayout_3.HorizontalAlignment = Enum.HorizontalAlignment.Left
UIGridLayout_3.VerticalAlignment = Enum.VerticalAlignment.Top
UIGridLayout_3.SortOrder = Enum.SortOrder.LayoutOrder
UIGridLayout_3.CellSize = UDim2.new(0, 327, 0, 30)
UIGridLayout_3.CellPadding = UDim2.new(0, 5, 0, 5)
UIGridLayout_3.Parent = package_3

local anonymousify = Instance.new("TextButton")
anonymousify.Name = "anonymousify"
anonymousify.Text = "Anonymousify"
anonymousify.TextColor3 = Color3.fromRGB(0, 0, 0)
anonymousify.TextTransparency = 0
anonymousify.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
anonymousify.TextStrokeTransparency = 1
anonymousify.TextSize = 15
anonymousify.Font = Enum.Font.SourceSansBold
anonymousify.RichText = false
anonymousify.TextWrapped = false
anonymousify.TextScaled = false
anonymousify.TextXAlignment = Enum.TextXAlignment.Center
anonymousify.TextYAlignment = Enum.TextYAlignment.Center
anonymousify.BackgroundColor3 = Color3.fromRGB(240, 240, 240)
anonymousify.BackgroundTransparency = 0
anonymousify.BorderColor3 = Color3.fromRGB(205, 205, 205)
anonymousify.BorderSizePixel = 1
anonymousify.Size = UDim2.new(0, 200, 0, 50)
anonymousify.Position = UDim2.new(0, 0, 0, 0)
anonymousify.AnchorPoint = Vector2.new(0, 0)
anonymousify.Rotation = 0
anonymousify.Visible = true
anonymousify.ZIndex = 1
anonymousify.AutomaticSize = Enum.AutomaticSize.None
anonymousify.ClipsDescendants = false
anonymousify.LayoutOrder = 0
anonymousify.Active = true
anonymousify.Selectable = true
anonymousify.Modal = false
anonymousify.Parent = package_3
-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.package.package.anonymousify.LocalScript"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.package.package.anonymousify.LocalScript"


local stummy = Instance.new("TextButton")
stummy.Name = "stummy"
stummy.Text = "Stummy Guns"
stummy.TextColor3 = Color3.fromRGB(0, 0, 0)
stummy.TextTransparency = 0
stummy.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
stummy.TextStrokeTransparency = 1
stummy.TextSize = 15
stummy.Font = Enum.Font.SourceSansBold
stummy.RichText = false
stummy.TextWrapped = false
stummy.TextScaled = false
stummy.TextXAlignment = Enum.TextXAlignment.Center
stummy.TextYAlignment = Enum.TextYAlignment.Center
stummy.BackgroundColor3 = Color3.fromRGB(240, 240, 240)
stummy.BackgroundTransparency = 0
stummy.BorderColor3 = Color3.fromRGB(205, 205, 205)
stummy.BorderSizePixel = 1
stummy.Size = UDim2.new(0, 200, 0, 50)
stummy.Position = UDim2.new(0, 0, 0, 0)
stummy.AnchorPoint = Vector2.new(0, 0)
stummy.Rotation = 0
stummy.Visible = true
stummy.ZIndex = 1
stummy.AutomaticSize = Enum.AutomaticSize.None
stummy.ClipsDescendants = false
stummy.LayoutOrder = 0
stummy.Active = true
stummy.Selectable = true
stummy.Modal = false
stummy.Parent = package_3
-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.package.package.stummy.LocalScript"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.package.package.stummy.LocalScript"


local nucleardetonation = Instance.new("TextButton")
nucleardetonation.Name = "nucleardetonation"
nucleardetonation.Text = "Nuclear Detonation"
nucleardetonation.TextColor3 = Color3.fromRGB(0, 0, 0)
nucleardetonation.TextTransparency = 0
nucleardetonation.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
nucleardetonation.TextStrokeTransparency = 1
nucleardetonation.TextSize = 15
nucleardetonation.Font = Enum.Font.SourceSansBold
nucleardetonation.RichText = false
nucleardetonation.TextWrapped = false
nucleardetonation.TextScaled = false
nucleardetonation.TextXAlignment = Enum.TextXAlignment.Center
nucleardetonation.TextYAlignment = Enum.TextYAlignment.Center
nucleardetonation.BackgroundColor3 = Color3.fromRGB(240, 240, 240)
nucleardetonation.BackgroundTransparency = 0
nucleardetonation.BorderColor3 = Color3.fromRGB(205, 205, 205)
nucleardetonation.BorderSizePixel = 1
nucleardetonation.Size = UDim2.new(0, 200, 0, 50)
nucleardetonation.Position = UDim2.new(0, 0, 0, 0)
nucleardetonation.AnchorPoint = Vector2.new(0, 0)
nucleardetonation.Rotation = 0
nucleardetonation.Visible = true
nucleardetonation.ZIndex = 1
nucleardetonation.AutomaticSize = Enum.AutomaticSize.None
nucleardetonation.ClipsDescendants = false
nucleardetonation.LayoutOrder = 0
nucleardetonation.Active = true
nucleardetonation.Selectable = true
nucleardetonation.Modal = false
nucleardetonation.Parent = package_3
-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.package.package.nucleardetonation.LocalScript"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.package.package.nucleardetonation.LocalScript"


local polaria = Instance.new("TextButton")
polaria.Name = "polaria"
polaria.Text = "Polaria Hub"
polaria.TextColor3 = Color3.fromRGB(0, 0, 0)
polaria.TextTransparency = 0
polaria.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
polaria.TextStrokeTransparency = 1
polaria.TextSize = 15
polaria.Font = Enum.Font.SourceSansBold
polaria.RichText = false
polaria.TextWrapped = false
polaria.TextScaled = false
polaria.TextXAlignment = Enum.TextXAlignment.Center
polaria.TextYAlignment = Enum.TextYAlignment.Center
polaria.BackgroundColor3 = Color3.fromRGB(240, 240, 240)
polaria.BackgroundTransparency = 0
polaria.BorderColor3 = Color3.fromRGB(205, 205, 205)
polaria.BorderSizePixel = 1
polaria.Size = UDim2.new(0, 200, 0, 50)
polaria.Position = UDim2.new(0, 0, 0, 0)
polaria.AnchorPoint = Vector2.new(0, 0)
polaria.Rotation = 0
polaria.Visible = true
polaria.ZIndex = 1
polaria.AutomaticSize = Enum.AutomaticSize.None
polaria.ClipsDescendants = false
polaria.LayoutOrder = 0
polaria.Active = true
polaria.Selectable = true
polaria.Modal = false
polaria.Parent = package_3
-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.package.package.polaria.LocalScript"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.package.package.polaria.LocalScript"


local dual_railgun_ = Instance.new("TextButton")
dual_railgun_.Name = "dual railgun "
dual_railgun_.Text = "Dual Railgun Tentacle Demon"
dual_railgun_.TextColor3 = Color3.fromRGB(0, 0, 0)
dual_railgun_.TextTransparency = 0
dual_railgun_.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
dual_railgun_.TextStrokeTransparency = 1
dual_railgun_.TextSize = 15
dual_railgun_.Font = Enum.Font.SourceSansBold
dual_railgun_.RichText = false
dual_railgun_.TextWrapped = false
dual_railgun_.TextScaled = false
dual_railgun_.TextXAlignment = Enum.TextXAlignment.Center
dual_railgun_.TextYAlignment = Enum.TextYAlignment.Center
dual_railgun_.BackgroundColor3 = Color3.fromRGB(240, 240, 240)
dual_railgun_.BackgroundTransparency = 0
dual_railgun_.BorderColor3 = Color3.fromRGB(205, 205, 205)
dual_railgun_.BorderSizePixel = 1
dual_railgun_.Size = UDim2.new(0, 200, 0, 50)
dual_railgun_.Position = UDim2.new(0, 0, 0, 0)
dual_railgun_.AnchorPoint = Vector2.new(0, 0)
dual_railgun_.Rotation = 0
dual_railgun_.Visible = true
dual_railgun_.ZIndex = 1
dual_railgun_.AutomaticSize = Enum.AutomaticSize.None
dual_railgun_.ClipsDescendants = false
dual_railgun_.LayoutOrder = 0
dual_railgun_.Active = true
dual_railgun_.Selectable = true
dual_railgun_.Modal = false
dual_railgun_.Parent = package_3
-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.package.package.dual railgun .LocalScript"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.package.package.dual railgun .LocalScript"


local Thomas = Instance.new("TextButton")
Thomas.Name = "Thomas"
Thomas.Text = "Thomas The Dank Engine"
Thomas.TextColor3 = Color3.fromRGB(0, 0, 0)
Thomas.TextTransparency = 0
Thomas.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
Thomas.TextStrokeTransparency = 1
Thomas.TextSize = 15
Thomas.Font = Enum.Font.SourceSansBold
Thomas.RichText = false
Thomas.TextWrapped = false
Thomas.TextScaled = false
Thomas.TextXAlignment = Enum.TextXAlignment.Center
Thomas.TextYAlignment = Enum.TextYAlignment.Center
Thomas.BackgroundColor3 = Color3.fromRGB(240, 240, 240)
Thomas.BackgroundTransparency = 0
Thomas.BorderColor3 = Color3.fromRGB(205, 205, 205)
Thomas.BorderSizePixel = 1
Thomas.Size = UDim2.new(0, 200, 0, 50)
Thomas.Position = UDim2.new(0, 0, 0, 0)
Thomas.AnchorPoint = Vector2.new(0, 0)
Thomas.Rotation = 0
Thomas.Visible = true
Thomas.ZIndex = 1
Thomas.AutomaticSize = Enum.AutomaticSize.None
Thomas.ClipsDescendants = false
Thomas.LayoutOrder = 0
Thomas.Active = true
Thomas.Selectable = true
Thomas.Modal = false
Thomas.Parent = package_3
-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.package.package.Thomas.LocalScript"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.package.package.Thomas.LocalScript"


local duckall = Instance.new("TextButton")
duckall.Name = "duckall"
duckall.Text = "Duck All"
duckall.TextColor3 = Color3.fromRGB(0, 0, 0)
duckall.TextTransparency = 0
duckall.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
duckall.TextStrokeTransparency = 1
duckall.TextSize = 15
duckall.Font = Enum.Font.SourceSansBold
duckall.RichText = false
duckall.TextWrapped = false
duckall.TextScaled = false
duckall.TextXAlignment = Enum.TextXAlignment.Center
duckall.TextYAlignment = Enum.TextYAlignment.Center
duckall.BackgroundColor3 = Color3.fromRGB(240, 240, 240)
duckall.BackgroundTransparency = 0
duckall.BorderColor3 = Color3.fromRGB(205, 205, 205)
duckall.BorderSizePixel = 1
duckall.Size = UDim2.new(0, 200, 0, 50)
duckall.Position = UDim2.new(0, 0, 0, 0)
duckall.AnchorPoint = Vector2.new(0, 0)
duckall.Rotation = 0
duckall.Visible = true
duckall.ZIndex = 1
duckall.AutomaticSize = Enum.AutomaticSize.None
duckall.ClipsDescendants = false
duckall.LayoutOrder = 0
duckall.Active = true
duckall.Selectable = true
duckall.Modal = false
duckall.Parent = package_3
-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.package.package.duckall.LocalScript"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.package.package.duckall.LocalScript"


local jimcarrey = Instance.new("TextButton")
jimcarrey.Name = "jimcarrey"
jimcarrey.Text = "Jim Carrey Face All"
jimcarrey.TextColor3 = Color3.fromRGB(0, 0, 0)
jimcarrey.TextTransparency = 0
jimcarrey.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
jimcarrey.TextStrokeTransparency = 1
jimcarrey.TextSize = 15
jimcarrey.Font = Enum.Font.SourceSansBold
jimcarrey.RichText = false
jimcarrey.TextWrapped = false
jimcarrey.TextScaled = false
jimcarrey.TextXAlignment = Enum.TextXAlignment.Center
jimcarrey.TextYAlignment = Enum.TextYAlignment.Center
jimcarrey.BackgroundColor3 = Color3.fromRGB(240, 240, 240)
jimcarrey.BackgroundTransparency = 0
jimcarrey.BorderColor3 = Color3.fromRGB(205, 205, 205)
jimcarrey.BorderSizePixel = 1
jimcarrey.Size = UDim2.new(0, 200, 0, 50)
jimcarrey.Position = UDim2.new(0, 0, 0, 0)
jimcarrey.AnchorPoint = Vector2.new(0, 0)
jimcarrey.Rotation = 0
jimcarrey.Visible = true
jimcarrey.ZIndex = 1
jimcarrey.AutomaticSize = Enum.AutomaticSize.None
jimcarrey.ClipsDescendants = false
jimcarrey.LayoutOrder = 0
jimcarrey.Active = true
jimcarrey.Selectable = true
jimcarrey.Modal = false
jimcarrey.Parent = package_3
-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.package.package.jimcarrey.LocalScript"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.package.package.jimcarrey.LocalScript"


local snoopdog = Instance.new("TextButton")
snoopdog.Name = "snoopdog"
snoopdog.Text = "Snoop Dog Face All"
snoopdog.TextColor3 = Color3.fromRGB(0, 0, 0)
snoopdog.TextTransparency = 0
snoopdog.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
snoopdog.TextStrokeTransparency = 1
snoopdog.TextSize = 15
snoopdog.Font = Enum.Font.SourceSansBold
snoopdog.RichText = false
snoopdog.TextWrapped = false
snoopdog.TextScaled = false
snoopdog.TextXAlignment = Enum.TextXAlignment.Center
snoopdog.TextYAlignment = Enum.TextYAlignment.Center
snoopdog.BackgroundColor3 = Color3.fromRGB(240, 240, 240)
snoopdog.BackgroundTransparency = 0
snoopdog.BorderColor3 = Color3.fromRGB(205, 205, 205)
snoopdog.BorderSizePixel = 1
snoopdog.Size = UDim2.new(0, 200, 0, 50)
snoopdog.Position = UDim2.new(0, 0, 0, 0)
snoopdog.AnchorPoint = Vector2.new(0, 0)
snoopdog.Rotation = 0
snoopdog.Visible = true
snoopdog.ZIndex = 1
snoopdog.AutomaticSize = Enum.AutomaticSize.None
snoopdog.ClipsDescendants = false
snoopdog.LayoutOrder = 0
snoopdog.Active = true
snoopdog.Selectable = true
snoopdog.Modal = false
snoopdog.Parent = package_3
-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.package.package.snoopdog.LocalScript"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.package.package.snoopdog.LocalScript"


local acidgun_2 = Instance.new("TextButton")
acidgun_2.Name = "acidgun"
acidgun_2.Text = "Acid Gun"
acidgun_2.TextColor3 = Color3.fromRGB(0, 0, 0)
acidgun_2.TextTransparency = 0
acidgun_2.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
acidgun_2.TextStrokeTransparency = 1
acidgun_2.TextSize = 15
acidgun_2.Font = Enum.Font.SourceSansBold
acidgun_2.RichText = false
acidgun_2.TextWrapped = false
acidgun_2.TextScaled = false
acidgun_2.TextXAlignment = Enum.TextXAlignment.Center
acidgun_2.TextYAlignment = Enum.TextYAlignment.Center
acidgun_2.BackgroundColor3 = Color3.fromRGB(240, 240, 240)
acidgun_2.BackgroundTransparency = 0
acidgun_2.BorderColor3 = Color3.fromRGB(205, 205, 205)
acidgun_2.BorderSizePixel = 1
acidgun_2.Size = UDim2.new(0, 200, 0, 50)
acidgun_2.Position = UDim2.new(0, 0, 0, 0)
acidgun_2.AnchorPoint = Vector2.new(0, 0)
acidgun_2.Rotation = 0
acidgun_2.Visible = true
acidgun_2.ZIndex = 1
acidgun_2.AutomaticSize = Enum.AutomaticSize.None
acidgun_2.ClipsDescendants = false
acidgun_2.LayoutOrder = 0
acidgun_2.Active = true
acidgun_2.Selectable = true
acidgun_2.Modal = false
acidgun_2.Parent = package_3
-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.package.package.acidgun.LocalScript"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.package.package.acidgun.LocalScript"


local icecream = Instance.new("TextButton")
icecream.Name = "icecream"
icecream.Text = "Ice Cream Sword"
icecream.TextColor3 = Color3.fromRGB(0, 0, 0)
icecream.TextTransparency = 0
icecream.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
icecream.TextStrokeTransparency = 1
icecream.TextSize = 15
icecream.Font = Enum.Font.SourceSansBold
icecream.RichText = false
icecream.TextWrapped = false
icecream.TextScaled = false
icecream.TextXAlignment = Enum.TextXAlignment.Center
icecream.TextYAlignment = Enum.TextYAlignment.Center
icecream.BackgroundColor3 = Color3.fromRGB(240, 240, 240)
icecream.BackgroundTransparency = 0
icecream.BorderColor3 = Color3.fromRGB(205, 205, 205)
icecream.BorderSizePixel = 1
icecream.Size = UDim2.new(0, 200, 0, 50)
icecream.Position = UDim2.new(0, 0, 0, 0)
icecream.AnchorPoint = Vector2.new(0, 0)
icecream.Rotation = 0
icecream.Visible = true
icecream.ZIndex = 1
icecream.AutomaticSize = Enum.AutomaticSize.None
icecream.ClipsDescendants = false
icecream.LayoutOrder = 0
icecream.Active = true
icecream.Selectable = true
icecream.Modal = false
icecream.Parent = package_3
-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.package.package.icecream.LocalScript"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.package.package.icecream.LocalScript"



local text = Instance.new("TextLabel")
text.Name = "text"
text.Text = "--------------Player--------------"
text.TextColor3 = Color3.fromRGB(0, 0, 0)
text.TextTransparency = 0
text.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
text.TextStrokeTransparency = 1
text.TextSize = 15
text.Font = Enum.Font.SourceSansBold
text.RichText = false
text.TextWrapped = false
text.TextScaled = false
text.TextXAlignment = Enum.TextXAlignment.Center
text.TextYAlignment = Enum.TextYAlignment.Center
text.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
text.BackgroundTransparency = 0
text.BorderColor3 = Color3.fromRGB(0, 0, 0)
text.BorderSizePixel = 0
text.Size = UDim2.new(0, 148, 0, 22)
text.Position = UDim2.new(0.69649803638458252, 0, 0.011594203300774097, 0)
text.AnchorPoint = Vector2.new(0, 0)
text.Rotation = 0
text.Visible = true
text.ZIndex = 1
text.AutomaticSize = Enum.AutomaticSize.None
text.ClipsDescendants = false
text.LayoutOrder = 0
text.Active = false
text.Selectable = false
text.Parent = package_2

local r6 = Instance.new("TextButton")
r6.Name = "r6"
r6.Text = "R6"
r6.TextColor3 = Color3.fromRGB(0, 0, 0)
r6.TextTransparency = 0
r6.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
r6.TextStrokeTransparency = 1
r6.TextSize = 15
r6.Font = Enum.Font.SourceSansBold
r6.RichText = false
r6.TextWrapped = false
r6.TextScaled = false
r6.TextXAlignment = Enum.TextXAlignment.Center
r6.TextYAlignment = Enum.TextYAlignment.Center
r6.BackgroundColor3 = Color3.fromRGB(240, 240, 240)
r6.BackgroundTransparency = 0
r6.BorderColor3 = Color3.fromRGB(205, 205, 205)
r6.BorderSizePixel = 1
r6.Size = UDim2.new(0, 65, 0, 31)
r6.Position = UDim2.new(0.69649803638458252, 0, 0.098550722002983093, 0)
r6.AnchorPoint = Vector2.new(0, 0)
r6.Rotation = 0
r6.Visible = true
r6.ZIndex = 1
r6.AutomaticSize = Enum.AutomaticSize.None
r6.ClipsDescendants = false
r6.LayoutOrder = 0
r6.Active = true
r6.Selectable = true
r6.Modal = false
r6.Parent = package_2
-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.package.r6.LocalScript"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.package.r6.LocalScript"

-- script preserved: "R6"
-- original path: "StarterGui.dominant.topbar.back.package.r6.R6"


local re = Instance.new("TextButton")
re.Name = "re"
re.Text = "RE"
re.TextColor3 = Color3.fromRGB(0, 0, 0)
re.TextTransparency = 0
re.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
re.TextStrokeTransparency = 1
re.TextSize = 15
re.Font = Enum.Font.SourceSansBold
re.RichText = false
re.TextWrapped = false
re.TextScaled = false
re.TextXAlignment = Enum.TextXAlignment.Center
re.TextYAlignment = Enum.TextYAlignment.Center
re.BackgroundColor3 = Color3.fromRGB(240, 240, 240)
re.BackgroundTransparency = 0
re.BorderColor3 = Color3.fromRGB(205, 205, 205)
re.BorderSizePixel = 1
re.Size = UDim2.new(0, 65, 0, 31)
re.Position = UDim2.new(0.85797667503356934, 0, 0.098550722002983093, 0)
re.AnchorPoint = Vector2.new(0, 0)
re.Rotation = 0
re.Visible = true
re.ZIndex = 1
re.AutomaticSize = Enum.AutomaticSize.None
re.ClipsDescendants = false
re.LayoutOrder = 0
re.Active = true
re.Selectable = true
re.Modal = false
re.Parent = package_2
-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.package.re.LocalScript"

-- script preserved: "Script"
-- original path: "StarterGui.dominant.topbar.back.package.re.Script"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.package.re.LocalScript"

local RemoteEvent_2 = Instance.new("RemoteEvent")
RemoteEvent_2.Name = "RemoteEvent"
RemoteEvent_2.Parent = re


local text_2 = Instance.new("TextLabel")
text_2.Name = "text"
text_2.Text = "--------------Server--------------"
text_2.TextColor3 = Color3.fromRGB(0, 0, 0)
text_2.TextTransparency = 0
text_2.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
text_2.TextStrokeTransparency = 1
text_2.TextSize = 15
text_2.Font = Enum.Font.SourceSansBold
text_2.RichText = false
text_2.TextWrapped = false
text_2.TextScaled = false
text_2.TextXAlignment = Enum.TextXAlignment.Center
text_2.TextYAlignment = Enum.TextYAlignment.Center
text_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
text_2.BackgroundTransparency = 0
text_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
text_2.BorderSizePixel = 0
text_2.Size = UDim2.new(0, 148, 0, 22)
text_2.Position = UDim2.new(0.69649803638458252, 0, 0.27536231279373169, 0)
text_2.AnchorPoint = Vector2.new(0, 0)
text_2.Rotation = 0
text_2.Visible = true
text_2.ZIndex = 1
text_2.AutomaticSize = Enum.AutomaticSize.None
text_2.ClipsDescendants = false
text_2.LayoutOrder = 0
text_2.Active = false
text_2.Selectable = false
text_2.Parent = package_2

local sky = Instance.new("TextButton")
sky.Name = "sky"
sky.Text = "Skybox"
sky.TextColor3 = Color3.fromRGB(0, 0, 0)
sky.TextTransparency = 0
sky.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
sky.TextStrokeTransparency = 1
sky.TextSize = 15
sky.Font = Enum.Font.SourceSansBold
sky.RichText = false
sky.TextWrapped = false
sky.TextScaled = false
sky.TextXAlignment = Enum.TextXAlignment.Center
sky.TextYAlignment = Enum.TextYAlignment.Center
sky.BackgroundColor3 = Color3.fromRGB(240, 240, 240)
sky.BackgroundTransparency = 0
sky.BorderColor3 = Color3.fromRGB(205, 205, 205)
sky.BorderSizePixel = 1
sky.Size = UDim2.new(0, 65, 0, 31)
sky.Position = UDim2.new(0.69649803638458252, 0, 0.36231884360313416, 0)
sky.AnchorPoint = Vector2.new(0, 0)
sky.Rotation = 0
sky.Visible = true
sky.ZIndex = 1
sky.AutomaticSize = Enum.AutomaticSize.None
sky.ClipsDescendants = false
sky.LayoutOrder = 0
sky.Active = true
sky.Selectable = true
sky.Modal = false
sky.Parent = package_2
-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.package.sky.LocalScript"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.package.sky.LocalScript"


local decal = Instance.new("TextButton")
decal.Name = "decal"
decal.Text = "Decalspam"
decal.TextColor3 = Color3.fromRGB(0, 0, 0)
decal.TextTransparency = 0
decal.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
decal.TextStrokeTransparency = 1
decal.TextSize = 15
decal.Font = Enum.Font.SourceSansBold
decal.RichText = false
decal.TextWrapped = false
decal.TextScaled = false
decal.TextXAlignment = Enum.TextXAlignment.Center
decal.TextYAlignment = Enum.TextYAlignment.Center
decal.BackgroundColor3 = Color3.fromRGB(240, 240, 240)
decal.BackgroundTransparency = 0
decal.BorderColor3 = Color3.fromRGB(205, 205, 205)
decal.BorderSizePixel = 1
decal.Size = UDim2.new(0, 65, 0, 31)
decal.Position = UDim2.new(0.85797667503356934, 0, 0.36231884360313416, 0)
decal.AnchorPoint = Vector2.new(0, 0)
decal.Rotation = 0
decal.Visible = true
decal.ZIndex = 1
decal.AutomaticSize = Enum.AutomaticSize.None
decal.ClipsDescendants = false
decal.LayoutOrder = 0
decal.Active = true
decal.Selectable = true
decal.Modal = false
decal.Parent = package_2
-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.package.decal.LocalScript"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.package.decal.LocalScript"


local Object = Instance.new("TextButton")
Object.Name = "1x1x1x1"
Object.Text = "1x1x1x1"
Object.TextColor3 = Color3.fromRGB(0, 0, 0)
Object.TextTransparency = 0
Object.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
Object.TextStrokeTransparency = 1
Object.TextSize = 15
Object.Font = Enum.Font.SourceSansBold
Object.RichText = false
Object.TextWrapped = false
Object.TextScaled = false
Object.TextXAlignment = Enum.TextXAlignment.Center
Object.TextYAlignment = Enum.TextYAlignment.Center
Object.BackgroundColor3 = Color3.fromRGB(240, 240, 240)
Object.BackgroundTransparency = 0
Object.BorderColor3 = Color3.fromRGB(205, 205, 205)
Object.BorderSizePixel = 1
Object.Size = UDim2.new(0, 65, 0, 31)
Object.Position = UDim2.new(0.69649803638458252, 0, 0.47536233067512512, 0)
Object.AnchorPoint = Vector2.new(0, 0)
Object.Rotation = 0
Object.Visible = true
Object.ZIndex = 1
Object.AutomaticSize = Enum.AutomaticSize.None
Object.ClipsDescendants = false
Object.LayoutOrder = 0
Object.Active = true
Object.Selectable = true
Object.Modal = false
Object.Parent = package_2
-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.package.1x1x1x1.LocalScript"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.package.1x1x1x1.LocalScript"


local Object_2 = Instance.new("TextButton")
Object_2.Name = "666"
Object_2.Text = "666"
Object_2.TextColor3 = Color3.fromRGB(0, 0, 0)
Object_2.TextTransparency = 0
Object_2.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
Object_2.TextStrokeTransparency = 1
Object_2.TextSize = 15
Object_2.Font = Enum.Font.SourceSansBold
Object_2.RichText = false
Object_2.TextWrapped = false
Object_2.TextScaled = false
Object_2.TextXAlignment = Enum.TextXAlignment.Center
Object_2.TextYAlignment = Enum.TextYAlignment.Center
Object_2.BackgroundColor3 = Color3.fromRGB(240, 240, 240)
Object_2.BackgroundTransparency = 0
Object_2.BorderColor3 = Color3.fromRGB(205, 205, 205)
Object_2.BorderSizePixel = 1
Object_2.Size = UDim2.new(0, 65, 0, 31)
Object_2.Position = UDim2.new(0.85797667503356934, 0, 0.47536233067512512, 0)
Object_2.AnchorPoint = Vector2.new(0, 0)
Object_2.Rotation = 0
Object_2.Visible = true
Object_2.ZIndex = 1
Object_2.AutomaticSize = Enum.AutomaticSize.None
Object_2.ClipsDescendants = false
Object_2.LayoutOrder = 0
Object_2.Active = true
Object_2.Selectable = true
Object_2.Modal = false
Object_2.Parent = package_2
-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.package.666.LocalScript"

-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.package.666.LocalScript"


local executor_3 = Instance.new("TextButton")
executor_3.Name = "executor"
executor_3.Text = "Executor"
executor_3.TextColor3 = Color3.fromRGB(0, 0, 0)
executor_3.TextTransparency = 0
executor_3.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
executor_3.TextStrokeTransparency = 1
executor_3.TextSize = 14
executor_3.Font = Enum.Font.SourceSans
executor_3.RichText = false
executor_3.TextWrapped = false
executor_3.TextScaled = false
executor_3.TextXAlignment = Enum.TextXAlignment.Center
executor_3.TextYAlignment = Enum.TextYAlignment.Center
executor_3.BackgroundColor3 = Color3.fromRGB(240, 240, 240)
executor_3.BackgroundTransparency = 0
executor_3.BorderColor3 = Color3.fromRGB(205, 205, 205)
executor_3.BorderSizePixel = 1
executor_3.Size = UDim2.new(0, 53, 0, 16)
executor_3.Position = UDim2.new(0, 0, -0.048304349184036255, 1)
executor_3.AnchorPoint = Vector2.new(0, 0)
executor_3.Rotation = 0
executor_3.Visible = true
executor_3.ZIndex = 1
executor_3.AutomaticSize = Enum.AutomaticSize.None
executor_3.ClipsDescendants = false
executor_3.LayoutOrder = 0
executor_3.Active = true
executor_3.Selectable = true
executor_3.Modal = false
executor_3.Parent = package_2
-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.back.package.executor.LocalScript"


local package_4 = Instance.new("TextButton")
package_4.Name = "package"
package_4.Text = "Packages"
package_4.TextColor3 = Color3.fromRGB(0, 0, 0)
package_4.TextTransparency = 0
package_4.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
package_4.TextStrokeTransparency = 1
package_4.TextSize = 14
package_4.Font = Enum.Font.SourceSans
package_4.RichText = false
package_4.TextWrapped = false
package_4.TextScaled = false
package_4.TextXAlignment = Enum.TextXAlignment.Center
package_4.TextYAlignment = Enum.TextYAlignment.Center
package_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
package_4.BackgroundTransparency = 0
package_4.BorderColor3 = Color3.fromRGB(205, 205, 205)
package_4.BorderSizePixel = 1
package_4.Size = UDim2.new(0, 53, 0, 19)
package_4.Position = UDim2.new(0.1031128391623497, 0, -0.054101474583148956, 0)
package_4.AnchorPoint = Vector2.new(0, 0)
package_4.Rotation = 0
package_4.Visible = true
package_4.ZIndex = 1
package_4.AutomaticSize = Enum.AutomaticSize.None
package_4.ClipsDescendants = false
package_4.LayoutOrder = 0
package_4.Active = true
package_4.Selectable = true
package_4.Modal = false
package_4.Parent = package_2

local bar_2 = Instance.new("Frame")
bar_2.Name = "bar"
bar_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
bar_2.BackgroundTransparency = 0
bar_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
bar_2.BorderSizePixel = 0
bar_2.Size = UDim2.new(0, 514, 0, 1)
bar_2.Position = UDim2.new(0, 0, 0, 0)
bar_2.AnchorPoint = Vector2.new(0, 0)
bar_2.Rotation = 0
bar_2.Visible = true
bar_2.ZIndex = 1
bar_2.AutomaticSize = Enum.AutomaticSize.None
bar_2.ClipsDescendants = false
bar_2.LayoutOrder = 0
bar_2.Active = true
bar_2.Selectable = false
bar_2.Parent = package_2



local icon = Instance.new("ImageLabel")
icon.Name = "icon"
icon.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
icon.BackgroundTransparency = 1
icon.BorderColor3 = Color3.fromRGB(0, 0, 0)
icon.BorderSizePixel = 0
icon.Size = UDim2.new(0, 18, 0, 18)
icon.Position = UDim2.new(0.004999999888241291, 3, 0.20000000298023224, 0)
icon.AnchorPoint = Vector2.new(0, 0)
icon.Rotation = 0
icon.Visible = true
icon.ZIndex = 1
icon.Image = "rbxassetid://114185476822531"
icon.ImageColor3 = Color3.fromRGB(255, 255, 255)
icon.ImageTransparency = 0
icon.ImageRectOffset = Vector2.new(0, 0)
icon.ImageRectSize = Vector2.new(0, 0)
icon.ScaleType = Enum.ScaleType.Stretch
icon.AutomaticSize = Enum.AutomaticSize.None
icon.ClipsDescendants = false
icon.LayoutOrder = 0
icon.Active = true
icon.Selectable = false
icon.Parent = topbar

local title = Instance.new("TextLabel")
title.Name = "title"
title.Text = "Dominant Executor"
title.TextColor3 = Color3.fromRGB(0, 0, 0)
title.TextTransparency = 0
title.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
title.TextStrokeTransparency = 1
title.TextSize = 14
title.Font = Enum.Font.SourceSans
title.RichText = false
title.TextWrapped = false
title.TextScaled = false
title.TextXAlignment = Enum.TextXAlignment.Center
title.TextYAlignment = Enum.TextYAlignment.Center
title.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
title.BackgroundTransparency = 1
title.BorderColor3 = Color3.fromRGB(0, 0, 0)
title.BorderSizePixel = 0
title.Size = UDim2.new(0, 115, 0, 30)
title.Position = UDim2.new(0.038333363831043243, 0, 0, 0)
title.AnchorPoint = Vector2.new(0, 0)
title.Rotation = 0
title.Visible = true
title.ZIndex = 1
title.AutomaticSize = Enum.AutomaticSize.None
title.ClipsDescendants = false
title.LayoutOrder = 0
title.Active = true
title.Selectable = false
title.Parent = topbar
-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.topbar.title.LocalScript"


local shadow = Instance.new("Frame")
shadow.Name = "shadow"
shadow.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
shadow.BackgroundTransparency = 1
shadow.BorderColor3 = Color3.fromRGB(0, 0, 0)
shadow.BorderSizePixel = 0
shadow.Size = UDim2.new(0, 520, 0, 400)
shadow.Position = UDim2.new(0, 0, 0, 0)
shadow.AnchorPoint = Vector2.new(0, 0)
shadow.Rotation = 0
shadow.Visible = true
shadow.ZIndex = 1
shadow.AutomaticSize = Enum.AutomaticSize.None
shadow.ClipsDescendants = false
shadow.LayoutOrder = 0
shadow.Active = true
shadow.Selectable = false
shadow.Parent = topbar
local UIStroke_4 = Instance.new("UIStroke")
UIStroke_4.Name = "UIStroke"
UIStroke_4.Enabled = true
UIStroke_4.ZIndex = 1
UIStroke_4.Parent = shadow

local UIStroke_5 = Instance.new("UIStroke")
UIStroke_5.Name = "UIStroke"
UIStroke_5.Enabled = true
UIStroke_5.ZIndex = 1
UIStroke_5.Parent = shadow



local outline = Instance.new("Frame")
outline.Name = "outline"
outline.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
outline.BackgroundTransparency = 1
outline.BorderColor3 = Color3.fromRGB(0, 0, 0)
outline.BorderSizePixel = 0
outline.Size = UDim2.new(0, 520, 0, 400)
outline.Position = UDim2.new(0.094932191073894501, 0, 0.11445783078670502, 0)
outline.AnchorPoint = Vector2.new(0, 0)
outline.Rotation = 0
outline.Visible = false
outline.ZIndex = 1
outline.AutomaticSize = Enum.AutomaticSize.None
outline.ClipsDescendants = false
outline.LayoutOrder = 0
outline.Active = true
outline.Selectable = false
outline.Parent = dominant
-- script preserved: "LocalScript"
-- original path: "StarterGui.dominant.outline.LocalScript"

local UIStroke_6 = Instance.new("UIStroke")
UIStroke_6.Name = "UIStroke"
UIStroke_6.Enabled = true
UIStroke_6.ZIndex = 1
UIStroke_6.Parent = outline


