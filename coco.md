coco.

local CocoHub = Instance.new("ScreenGui")
local ButtonFrame = Instance.new("Frame")
local OpenBG = Instance.new("ImageLabel")
local OpenButton = Instance.new("TextButton")
local HubFrame = Instance.new("Frame")
local Logo = Instance.new("ImageLabel")
local Logo_2 = Instance.new("ImageLabel")
local Logo_3 = Instance.new("ImageLabel")
local Execute1Frame = Instance.new("ScrollingFrame")
local UIGridLayout = Instance.new("UIGridLayout")
local _43 = Instance.new("TextButton")
local _44 = Instance.new("TextButton")
local _45 = Instance.new("TextButton")
local _46 = Instance.new("TextButton")
local _1 = Instance.new("TextButton")
local _2 = Instance.new("TextButton")
local _3 = Instance.new("TextButton")
local _4 = Instance.new("TextButton")
local _5 = Instance.new("TextButton")
local _6 = Instance.new("TextButton")
local _7 = Instance.new("TextButton")
local _8 = Instance.new("TextButton")
local _49 = Instance.new("TextButton")
local _10 = Instance.new("TextButton")
local _11 = Instance.new("TextButton")
local _12 = Instance.new("TextButton")
local _13 = Instance.new("TextButton")
local _14 = Instance.new("TextButton")
local _15 = Instance.new("TextButton")
local _16 = Instance.new("TextButton")
local _17 = Instance.new("TextButton")
local _18 = Instance.new("TextButton")
local _19 = Instance.new("TextButton")
local _20 = Instance.new("TextButton")
local _21 = Instance.new("TextButton")
local _22 = Instance.new("TextButton")
local _23 = Instance.new("TextButton")
local _24 = Instance.new("TextButton")
local _25 = Instance.new("TextButton")
local _26 = Instance.new("TextButton")
local _27 = Instance.new("TextButton")
local _28 = Instance.new("TextButton")
local _29 = Instance.new("TextButton")
local _30 = Instance.new("TextButton")
local _31 = Instance.new("TextButton")
local _32 = Instance.new("TextButton")
local _33 = Instance.new("TextButton")
local _34 = Instance.new("TextButton")
local _35 = Instance.new("TextButton")
local _36 = Instance.new("TextButton")
local _37 = Instance.new("TextButton")
local _38 = Instance.new("TextButton")
local _39 = Instance.new("TextButton")
local _40 = Instance.new("TextButton")
local _41 = Instance.new("TextButton")
local _42 = Instance.new("TextButton")
local _47 = Instance.new("TextButton")
local _48 = Instance.new("TextButton")
local Execute2Frame = Instance.new("ScrollingFrame")
local UIGridLayout_2 = Instance.new("UIGridLayout")
local _1_2 = Instance.new("TextButton")
local _2_2 = Instance.new("TextButton")
local _3_2 = Instance.new("TextButton")
local _4_2 = Instance.new("TextButton")
local _5_2 = Instance.new("TextButton")
local _6_2 = Instance.new("TextButton")
local Execute3Frame = Instance.new("ScrollingFrame")
local UIGridLayout_3 = Instance.new("UIGridLayout")
local _4_3 = Instance.new("TextButton")
local _3_3 = Instance.new("TextButton")
local _2_3 = Instance.new("TextButton")
local _1_3 = Instance.new("TextButton")
local TopbarFrame = Instance.new("Frame")
local Title = Instance.new("TextButton")
local SidebarFrame = Instance.new("ImageLabel")
local B1 = Instance.new("TextButton")
local B2 = Instance.new("TextButton")
local B3 = Instance.new("TextButton")
local B4 = Instance.new("TextButton")
local Logo_4 = Instance.new("ImageLabel")
local Exit = Instance.new("TextButton")
local Minimize = Instance.new("TextButton")
local Execute4Frame = Instance.new("ScrollingFrame")
local UIGridLayout_4 = Instance.new("UIGridLayout")
local _1_4 = Instance.new("TextButton")
local _2_4 = Instance.new("TextButton")
local _3_4 = Instance.new("TextButton")
local _4_4 = Instance.new("TextButton")
local _5_3 = Instance.new("TextButton")
local HubWorkGameFrame = Instance.new("Frame")
local GameFrame = Instance.new("ScrollingFrame")
local UIGridLayout_5 = Instance.new("UIGridLayout")
local _1_5 = Instance.new("TextLabel")
local _2_5 = Instance.new("TextLabel")
local _3_5 = Instance.new("TextLabel")
local _4_5 = Instance.new("TextLabel")
local _5_4 = Instance.new("TextLabel")
local _6_3 = Instance.new("TextLabel")
local _7_2 = Instance.new("TextLabel")
local _8_2 = Instance.new("TextLabel")
local TopbarFrame_2 = Instance.new("ImageLabel")
local Exit_2 = Instance.new("TextButton")
local Credits = Instance.new("TextLabel")
local IntroHubFrame = Instance.new("Frame")
local IntroFrame = Instance.new("ImageLabel")
local CocoLogo = Instance.new("ImageLabel")

CocoHub.Name = "CocoHub"
CocoHub.Parent = game.CoreGui
CocoHub.ResetOnSpawn = false

ButtonFrame.Name = "ButtonFrame"
ButtonFrame.Parent = CocoHub
ButtonFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ButtonFrame.BackgroundTransparency = 1.000
ButtonFrame.BorderSizePixel = 0
ButtonFrame.ClipsDescendants = true
ButtonFrame.Position = UDim2.new(1, -50, 2, -50)
ButtonFrame.Size = UDim2.new(0, 40, 0, 40)

OpenBG.Name = "OpenBG"
OpenBG.Parent = ButtonFrame
OpenBG.Active = true
OpenBG.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
OpenBG.BackgroundTransparency = 1.000
OpenBG.Selectable = true
OpenBG.Size = UDim2.new(1, 0, 1, 0)
OpenBG.Image = "rbxassetid://3570695787"
OpenBG.ImageColor3 = Color3.fromRGB(43, 43, 43)
OpenBG.ScaleType = Enum.ScaleType.Slice
OpenBG.SliceCenter = Rect.new(100, 100, 100, 100)

OpenButton.Name = "OpenButton"
OpenButton.Parent = ButtonFrame
OpenButton.BackgroundColor3 = Color3.fromRGB(35, 35, 35)
OpenButton.BackgroundTransparency = 1.000
OpenButton.BorderSizePixel = 0
OpenButton.Size = UDim2.new(1, 0, 1, 0)
OpenButton.Font = Enum.Font.GothamBold
OpenButton.Text = "<"
OpenButton.TextColor3 = Color3.fromRGB(255, 255, 255)
OpenButton.TextSize = 20.000

HubFrame.Name = "HubFrame"
HubFrame.Parent = CocoHub
HubFrame.AnchorPoint = Vector2.new(0.5, 0.5)
HubFrame.BackgroundColor3 = Color3.fromRGB(43, 43, 43)
HubFrame.BorderSizePixel = 0
HubFrame.ClipsDescendants = true
HubFrame.Position = UDim2.new(0.5, 0, 2, 0)
HubFrame.Size = UDim2.new(0, 717, 0, 393)

Logo.Name = "Logo"
Logo.Parent = HubFrame
Logo.AnchorPoint = Vector2.new(0.5, 0.5)
Logo.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Logo.BackgroundTransparency = 1.000
Logo.BorderSizePixel = 0
Logo.Position = UDim2.new(0.894656718, 0, 0.837043881, 0)
Logo.Size = UDim2.new(0, 237, 0, 237)
Logo.Image = "http://www.roblox.com/asset/?id=5114898244"
Logo.ImageTransparency = 0.500

Logo_2.Name = "Logo"
Logo_2.Parent = HubFrame
Logo_2.AnchorPoint = Vector2.new(0.5, 0.5)
Logo_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Logo_2.BackgroundTransparency = 1.000
Logo_2.BorderSizePixel = 0
Logo_2.Position = UDim2.new(0.622690201, 0, 0.150020957, 0)
Logo_2.Size = UDim2.new(0, 237, 0, 237)
Logo_2.Image = "http://www.roblox.com/asset/?id=5114898244"
Logo_2.ImageTransparency = 0.500

Logo_3.Name = "Logo"
Logo_3.Parent = HubFrame
Logo_3.AnchorPoint = Vector2.new(0.5, 0.5)
Logo_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Logo_3.BackgroundTransparency = 1.000
Logo_3.BorderSizePixel = 0
Logo_3.Position = UDim2.new(0.25727877, 0, 0.898112535, 0)
Logo_3.Size = UDim2.new(0, 237, 0, 237)
Logo_3.Image = "http://www.roblox.com/asset/?id=5114898244"
Logo_3.ImageTransparency = 0.500

Execute1Frame.Name = "Execute1Frame"
Execute1Frame.Parent = HubFrame
Execute1Frame.Active = true
Execute1Frame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Execute1Frame.BackgroundTransparency = 1.000
Execute1Frame.BorderSizePixel = 0
Execute1Frame.Position = UDim2.new(0.0906555057, 0, 0.127226457, 0)
Execute1Frame.Size = UDim2.new(0.909344494, 0, 0.872773528, 0)
Execute1Frame.ScrollBarThickness = 5

UIGridLayout.Parent = Execute1Frame
UIGridLayout.HorizontalAlignment = Enum.HorizontalAlignment.Center
UIGridLayout.SortOrder = Enum.SortOrder.LayoutOrder
UIGridLayout.CellSize = UDim2.new(0, 150, 0, 50)

_43.Name = "43"
_43.Parent = Execute1Frame
_43.BackgroundColor3 = Color3.fromRGB(64, 64, 64)
_43.BorderSizePixel = 0
_43.Size = UDim2.new(0, 200, 0, 50)
_43.Font = Enum.Font.GothamBold
_43.Text = "Vehicle Simulator"
_43.TextColor3 = Color3.fromRGB(255, 255, 255)
_43.TextSize = 20.000
_43.TextWrapped = true

_44.Name = "44"
_44.Parent = Execute1Frame
_44.BackgroundColor3 = Color3.fromRGB(64, 64, 64)
_44.BorderSizePixel = 0
_44.Size = UDim2.new(0, 200, 0, 50)
_44.Font = Enum.Font.GothamBold
_44.Text = "Work at a Pizza Place"
_44.TextColor3 = Color3.fromRGB(255, 255, 255)
_44.TextSize = 20.000
_44.TextWrapped = true

_45.Name = "45"
_45.Parent = Execute1Frame
_45.BackgroundColor3 = Color3.fromRGB(64, 64, 64)
_45.BorderSizePixel = 0
_45.Size = UDim2.new(0, 200, 0, 50)
_45.Font = Enum.Font.GothamBold
_45.Text = "Zombie Rush"
_45.TextColor3 = Color3.fromRGB(255, 255, 255)
_45.TextSize = 20.000
_45.TextWrapped = true

_46.Name = "46"
_46.Parent = Execute1Frame
_46.BackgroundColor3 = Color3.fromRGB(64, 64, 64)
_46.BorderSizePixel = 0
_46.Size = UDim2.new(0, 200, 0, 50)
_46.Font = Enum.Font.GothamBold
_46.Text = "Zombie Strike"
_46.TextColor3 = Color3.fromRGB(255, 255, 255)
_46.TextSize = 20.000
_46.TextWrapped = true

_1.Name = "1"
_1.Parent = Execute1Frame
_1.BackgroundColor3 = Color3.fromRGB(64, 64, 64)
_1.BorderSizePixel = 0
_1.Size = UDim2.new(0, 200, 0, 50)
_1.Font = Enum.Font.GothamBold
_1.Text = "A Bizzare Day"
_1.TextColor3 = Color3.fromRGB(255, 255, 255)
_1.TextSize = 20.000
_1.TextWrapped = true

_2.Name = "2"
_2.Parent = Execute1Frame
_2.BackgroundColor3 = Color3.fromRGB(64, 64, 64)
_2.BorderSizePixel = 0
_2.Size = UDim2.new(0, 200, 0, 50)
_2.Font = Enum.Font.GothamBold
_2.Text = "Arsenal"
_2.TextColor3 = Color3.fromRGB(255, 255, 255)
_2.TextSize = 20.000
_2.TextWrapped = true

_3.Name = "3"
_3.Parent = Execute1Frame
_3.BackgroundColor3 = Color3.fromRGB(64, 64, 64)
_3.BorderSizePixel = 0
_3.Size = UDim2.new(0, 200, 0, 50)
_3.Font = Enum.Font.GothamBold
_3.Text = "Assassin!"
_3.TextColor3 = Color3.fromRGB(255, 255, 255)
_3.TextSize = 20.000
_3.TextWrapped = true

_4.Name = "4"
_4.Parent = Execute1Frame
_4.BackgroundColor3 = Color3.fromRGB(64, 64, 64)
_4.BorderSizePixel = 0
_4.Size = UDim2.new(0, 200, 0, 50)
_4.Font = Enum.Font.GothamBold
_4.Text = "Balloon Simulator 2"
_4.TextColor3 = Color3.fromRGB(255, 255, 255)
_4.TextSize = 20.000
_4.TextWrapped = true

_5.Name = "5"
_5.Parent = Execute1Frame
_5.BackgroundColor3 = Color3.fromRGB(64, 64, 64)
_5.BorderSizePixel = 0
_5.Size = UDim2.new(0, 200, 0, 50)
_5.Font = Enum.Font.GothamBold
_5.Text = "BIG Paintball"
_5.TextColor3 = Color3.fromRGB(255, 255, 255)
_5.TextSize = 20.000
_5.TextWrapped = true

_6.Name = "6"
_6.Parent = Execute1Frame
_6.BackgroundColor3 = Color3.fromRGB(64, 64, 64)
_6.BorderSizePixel = 0
_6.Size = UDim2.new(0, 200, 0, 50)
_6.Font = Enum.Font.GothamBold
_6.Text = "Blox Hunt"
_6.TextColor3 = Color3.fromRGB(255, 255, 255)
_6.TextSize = 20.000
_6.TextWrapped = true

_7.Name = "7"
_7.Parent = Execute1Frame
_7.BackgroundColor3 = Color3.fromRGB(64, 64, 64)
_7.BorderSizePixel = 0
_7.Size = UDim2.new(0, 200, 0, 50)
_7.Font = Enum.Font.GothamBold
_7.Text = "Blox Piece"
_7.TextColor3 = Color3.fromRGB(255, 255, 255)
_7.TextSize = 20.000
_7.TextWrapped = true

_8.Name = "8"
_8.Parent = Execute1Frame
_8.BackgroundColor3 = Color3.fromRGB(64, 64, 64)
_8.BorderSizePixel = 0
_8.Size = UDim2.new(0, 200, 0, 50)
_8.Font = Enum.Font.GothamBold
_8.Text = "Booga Booga"
_8.TextColor3 = Color3.fromRGB(255, 255, 255)
_8.TextSize = 20.000
_8.TextWrapped = true

_49.Name = "49"
_49.Parent = Execute1Frame
_49.BackgroundColor3 = Color3.fromRGB(64, 64, 64)
_49.BorderSizePixel = 0
_49.Size = UDim2.new(0, 200, 0, 50)
_49.Font = Enum.Font.GothamBold
_49.Text = "Word Bomb"
_49.TextColor3 = Color3.fromRGB(255, 255, 255)
_49.TextSize = 20.000
_49.TextWrapped = true

_10.Name = "10"
_10.Parent = Execute1Frame
_10.BackgroundColor3 = Color3.fromRGB(64, 64, 64)
_10.BorderSizePixel = 0
_10.Size = UDim2.new(0, 200, 0, 50)
_10.Font = Enum.Font.GothamBold
_10.Text = "Breaking Point"
_10.TextColor3 = Color3.fromRGB(255, 255, 255)
_10.TextSize = 20.000
_10.TextWrapped = true

_11.Name = "11"
_11.Parent = Execute1Frame
_11.BackgroundColor3 = Color3.fromRGB(64, 64, 64)
_11.BorderSizePixel = 0
_11.Size = UDim2.new(0, 200, 0, 50)
_11.Font = Enum.Font.GothamBold
_11.Text = "Bubble Gum Simulator"
_11.TextColor3 = Color3.fromRGB(255, 255, 255)
_11.TextSize = 20.000
_11.TextWrapped = true

_12.Name = "12"
_12.Parent = Execute1Frame
_12.BackgroundColor3 = Color3.fromRGB(64, 64, 64)
_12.BorderSizePixel = 0
_12.Size = UDim2.new(0, 200, 0, 50)
_12.Font = Enum.Font.GothamBold
_12.Text = "Build a Boat for Treasure"
_12.TextColor3 = Color3.fromRGB(255, 255, 255)
_12.TextSize = 20.000
_12.TextWrapped = true

_13.Name = "13"
_13.Parent = Execute1Frame
_13.BackgroundColor3 = Color3.fromRGB(64, 64, 64)
_13.BorderSizePixel = 0
_13.Size = UDim2.new(0, 200, 0, 50)
_13.Font = Enum.Font.GothamBold
_13.Text = "Counter Blox"
_13.TextColor3 = Color3.fromRGB(255, 255, 255)
_13.TextSize = 20.000
_13.TextWrapped = true

_14.Name = "14"
_14.Parent = Execute1Frame
_14.BackgroundColor3 = Color3.fromRGB(64, 64, 64)
_14.BorderSizePixel = 0
_14.Size = UDim2.new(0, 200, 0, 50)
_14.Font = Enum.Font.GothamBold
_14.Text = "Da Hood"
_14.TextColor3 = Color3.fromRGB(255, 255, 255)
_14.TextSize = 20.000
_14.TextWrapped = true

_15.Name = "15"
_15.Parent = Execute1Frame
_15.BackgroundColor3 = Color3.fromRGB(64, 64, 64)
_15.BorderSizePixel = 0
_15.Size = UDim2.new(0, 200, 0, 50)
_15.Font = Enum.Font.GothamBold
_15.Text = "D-DAY"
_15.TextColor3 = Color3.fromRGB(255, 255, 255)
_15.TextSize = 20.000
_15.TextWrapped = true

_16.Name = "16"
_16.Parent = Execute1Frame
_16.BackgroundColor3 = Color3.fromRGB(64, 64, 64)
_16.BorderSizePixel = 0
_16.Size = UDim2.new(0, 200, 0, 50)
_16.Font = Enum.Font.GothamBold
_16.Text = "Family Paradise"
_16.TextColor3 = Color3.fromRGB(255, 255, 255)
_16.TextSize = 20.000
_16.TextWrapped = true

_17.Name = "17"
_17.Parent = Execute1Frame
_17.BackgroundColor3 = Color3.fromRGB(64, 64, 64)
_17.BorderSizePixel = 0
_17.Size = UDim2.new(0, 200, 0, 50)
_17.Font = Enum.Font.GothamBold
_17.Text = "Island Royale"
_17.TextColor3 = Color3.fromRGB(255, 255, 255)
_17.TextSize = 20.000
_17.TextWrapped = true

_18.Name = "18"
_18.Parent = Execute1Frame
_18.BackgroundColor3 = Color3.fromRGB(64, 64, 64)
_18.BorderSizePixel = 0
_18.Size = UDim2.new(0, 200, 0, 50)
_18.Font = Enum.Font.GothamBold
_18.Text = "Isle, 8"
_18.TextColor3 = Color3.fromRGB(255, 255, 255)
_18.TextSize = 20.000
_18.TextWrapped = true

_19.Name = "19"
_19.Parent = Execute1Frame
_19.BackgroundColor3 = Color3.fromRGB(64, 64, 64)
_19.BorderSizePixel = 0
_19.Size = UDim2.new(0, 200, 0, 50)
_19.Font = Enum.Font.GothamBold
_19.Text = "JailBreak"
_19.TextColor3 = Color3.fromRGB(255, 255, 255)
_19.TextSize = 20.000
_19.TextWrapped = true

_20.Name = "20"
_20.Parent = Execute1Frame
_20.BackgroundColor3 = Color3.fromRGB(64, 64, 64)
_20.BorderSizePixel = 0
_20.Size = UDim2.new(0, 200, 0, 50)
_20.Font = Enum.Font.GothamBold
_20.Text = "Knife Ability Test"
_20.TextColor3 = Color3.fromRGB(255, 255, 255)
_20.TextSize = 20.000
_20.TextWrapped = true

_21.Name = "21"
_21.Parent = Execute1Frame
_21.BackgroundColor3 = Color3.fromRGB(64, 64, 64)
_21.BorderSizePixel = 0
_21.Size = UDim2.new(0, 200, 0, 50)
_21.Font = Enum.Font.GothamBold
_21.Text = "Lost"
_21.TextColor3 = Color3.fromRGB(255, 255, 255)
_21.TextSize = 20.000
_21.TextWrapped = true

_22.Name = "22"
_22.Parent = Execute1Frame
_22.BackgroundColor3 = Color3.fromRGB(64, 64, 64)
_22.BorderSizePixel = 0
_22.Size = UDim2.new(0, 200, 0, 50)
_22.Font = Enum.Font.GothamBold
_22.Text = "Lumber Tycoon 2"
_22.TextColor3 = Color3.fromRGB(255, 255, 255)
_22.TextSize = 20.000
_22.TextWrapped = true

_23.Name = "23"
_23.Parent = Execute1Frame
_23.BackgroundColor3 = Color3.fromRGB(64, 64, 64)
_23.BorderSizePixel = 0
_23.Size = UDim2.new(0, 200, 0, 50)
_23.Font = Enum.Font.GothamBold
_23.Text = "Mad City"
_23.TextColor3 = Color3.fromRGB(255, 255, 255)
_23.TextSize = 20.000
_23.TextWrapped = true

_24.Name = "24"
_24.Parent = Execute1Frame
_24.BackgroundColor3 = Color3.fromRGB(64, 64, 64)
_24.BorderSizePixel = 0
_24.Size = UDim2.new(0, 200, 0, 50)
_24.Font = Enum.Font.GothamBold
_24.Text = "Mad Paintball"
_24.TextColor3 = Color3.fromRGB(255, 255, 255)
_24.TextSize = 20.000
_24.TextWrapped = true

_25.Name = "25"
_25.Parent = Execute1Frame
_25.BackgroundColor3 = Color3.fromRGB(64, 64, 64)
_25.BorderSizePixel = 0
_25.Size = UDim2.new(0, 200, 0, 50)
_25.Font = Enum.Font.GothamBold
_25.Text = "Make a Cake"
_25.TextColor3 = Color3.fromRGB(255, 255, 255)
_25.TextSize = 20.000
_25.TextWrapped = true

_26.Name = "26"
_26.Parent = Execute1Frame
_26.BackgroundColor3 = Color3.fromRGB(64, 64, 64)
_26.BorderSizePixel = 0
_26.Size = UDim2.new(0, 200, 0, 50)
_26.Font = Enum.Font.GothamBold
_26.Text = "Murder Mystery 2"
_26.TextColor3 = Color3.fromRGB(255, 255, 255)
_26.TextSize = 20.000
_26.TextWrapped = true

_27.Name = "27"
_27.Parent = Execute1Frame
_27.BackgroundColor3 = Color3.fromRGB(64, 64, 64)
_27.BorderSizePixel = 0
_27.Size = UDim2.new(0, 200, 0, 50)
_27.Font = Enum.Font.GothamBold
_27.Text = "Natural Disaster Survival"
_27.TextColor3 = Color3.fromRGB(255, 255, 255)
_27.TextSize = 20.000
_27.TextWrapped = true

_28.Name = "28"
_28.Parent = Execute1Frame
_28.BackgroundColor3 = Color3.fromRGB(64, 64, 64)
_28.BorderSizePixel = 0
_28.Size = UDim2.new(0, 200, 0, 50)
_28.Font = Enum.Font.GothamBold
_28.Text = "Ninja Legends"
_28.TextColor3 = Color3.fromRGB(255, 255, 255)
_28.TextSize = 20.000
_28.TextWrapped = true

_29.Name = "29"
_29.Parent = Execute1Frame
_29.BackgroundColor3 = Color3.fromRGB(64, 64, 64)
_29.BorderSizePixel = 0
_29.Size = UDim2.new(0, 200, 0, 50)
_29.Font = Enum.Font.GothamBold
_29.Text = "Notoriety"
_29.TextColor3 = Color3.fromRGB(255, 255, 255)
_29.TextSize = 20.000
_29.TextWrapped = true

_30.Name = "30"
_30.Parent = Execute1Frame
_30.BackgroundColor3 = Color3.fromRGB(64, 64, 64)
_30.BorderSizePixel = 0
_30.Size = UDim2.new(0, 200, 0, 50)
_30.Font = Enum.Font.GothamBold
_30.Text = "Phantom Forces"
_30.TextColor3 = Color3.fromRGB(255, 255, 255)
_30.TextSize = 20.000
_30.TextWrapped = true

_31.Name = "31"
_31.Parent = Execute1Frame
_31.BackgroundColor3 = Color3.fromRGB(64, 64, 64)
_31.BorderSizePixel = 0
_31.Size = UDim2.new(0, 200, 0, 50)
_31.Font = Enum.Font.GothamBold
_31.Text = "Piggy"
_31.TextColor3 = Color3.fromRGB(255, 255, 255)
_31.TextSize = 20.000
_31.TextWrapped = true

_32.Name = "32"
_32.Parent = Execute1Frame
_32.BackgroundColor3 = Color3.fromRGB(64, 64, 64)
_32.BorderSizePixel = 0
_32.Size = UDim2.new(0, 200, 0, 50)
_32.Font = Enum.Font.GothamBold
_32.Text = "Prison Life"
_32.TextColor3 = Color3.fromRGB(255, 255, 255)
_32.TextSize = 20.000
_32.TextWrapped = true

_33.Name = "33"
_33.Parent = Execute1Frame
_33.BackgroundColor3 = Color3.fromRGB(64, 64, 64)
_33.BorderSizePixel = 0
_33.Size = UDim2.new(0, 200, 0, 50)
_33.Font = Enum.Font.GothamBold
_33.Text = "Project Jojo"
_33.TextColor3 = Color3.fromRGB(255, 255, 255)
_33.TextSize = 20.000
_33.TextWrapped = true

_34.Name = "34"
_34.Parent = Execute1Frame
_34.BackgroundColor3 = Color3.fromRGB(64, 64, 64)
_34.BorderSizePixel = 0
_34.Size = UDim2.new(0, 200, 0, 50)
_34.Font = Enum.Font.GothamBold
_34.Text = "Redwood Prison"
_34.TextColor3 = Color3.fromRGB(255, 255, 255)
_34.TextSize = 20.000
_34.TextWrapped = true

_35.Name = "35"
_35.Parent = Execute1Frame
_35.BackgroundColor3 = Color3.fromRGB(64, 64, 64)
_35.BorderSizePixel = 0
_35.Position = UDim2.new(0.503834367, 0, 0.494169086, 0)
_35.Size = UDim2.new(0, 150, 0, 50)
_35.Font = Enum.Font.GothamBold
_35.Text = "My Restaurant"
_35.TextColor3 = Color3.fromRGB(255, 255, 255)
_35.TextSize = 20.000
_35.TextWrapped = true

_36.Name = "36"
_36.Parent = Execute1Frame
_36.BackgroundColor3 = Color3.fromRGB(64, 64, 64)
_36.BorderSizePixel = 0
_36.Size = UDim2.new(0, 200, 0, 50)
_36.Font = Enum.Font.GothamBold
_36.Text = "RoCitizens"
_36.TextColor3 = Color3.fromRGB(255, 255, 255)
_36.TextSize = 20.000
_36.TextWrapped = true

_37.Name = "37"
_37.Parent = Execute1Frame
_37.BackgroundColor3 = Color3.fromRGB(64, 64, 64)
_37.BorderSizePixel = 0
_37.Size = UDim2.new(0, 200, 0, 50)
_37.Font = Enum.Font.GothamBold
_37.Text = "Ro Ghoul"
_37.TextColor3 = Color3.fromRGB(255, 255, 255)
_37.TextSize = 20.000
_37.TextWrapped = true

_38.Name = "38"
_38.Parent = Execute1Frame
_38.BackgroundColor3 = Color3.fromRGB(64, 64, 64)
_38.BorderSizePixel = 0
_38.Size = UDim2.new(0, 200, 0, 50)
_38.Font = Enum.Font.GothamBold
_38.Text = "Saber Simulator"
_38.TextColor3 = Color3.fromRGB(255, 255, 255)
_38.TextSize = 20.000
_38.TextWrapped = true

_39.Name = "39"
_39.Parent = Execute1Frame
_39.BackgroundColor3 = Color3.fromRGB(64, 64, 64)
_39.BorderSizePixel = 0
_39.Size = UDim2.new(0, 200, 0, 50)
_39.Font = Enum.Font.GothamBold
_39.Text = "SharkBite"
_39.TextColor3 = Color3.fromRGB(255, 255, 255)
_39.TextSize = 20.000
_39.TextWrapped = true

_40.Name = "40"
_40.Parent = Execute1Frame
_40.BackgroundColor3 = Color3.fromRGB(64, 64, 64)
_40.BorderSizePixel = 0
_40.Size = UDim2.new(0, 200, 0, 50)
_40.Font = Enum.Font.GothamBold
_40.Text = "Strucid"
_40.TextColor3 = Color3.fromRGB(255, 255, 255)
_40.TextSize = 20.000
_40.TextWrapped = true

_41.Name = "41"
_41.Parent = Execute1Frame
_41.BackgroundColor3 = Color3.fromRGB(64, 64, 64)
_41.BorderSizePixel = 0
_41.Size = UDim2.new(0, 200, 0, 50)
_41.Font = Enum.Font.GothamBold
_41.Text = "Super Power Training Simulator"
_41.TextColor3 = Color3.fromRGB(255, 255, 255)
_41.TextScaled = true
_41.TextSize = 20.000
_41.TextWrapped = true

_42.Name = "42"
_42.Parent = Execute1Frame
_42.BackgroundColor3 = Color3.fromRGB(64, 64, 64)
_42.BorderSizePixel = 0
_42.Size = UDim2.new(0, 200, 0, 50)
_42.Font = Enum.Font.GothamBold
_42.Text = "Thick Legends"
_42.TextColor3 = Color3.fromRGB(255, 255, 255)
_42.TextSize = 20.000
_42.TextWrapped = true

_47.Name = "47"
_47.Parent = Execute1Frame
_47.BackgroundColor3 = Color3.fromRGB(64, 64, 64)
_47.BorderSizePixel = 0
_47.Size = UDim2.new(0, 200, 0, 50)
_47.Font = Enum.Font.GothamBold
_47.Text = "Thick Legends"
_47.TextColor3 = Color3.fromRGB(255, 255, 255)
_47.TextSize = 20.000
_47.TextWrapped = true

_48.Name = "48"
_48.Parent = Execute1Frame
_48.BackgroundColor3 = Color3.fromRGB(64, 64, 64)
_48.BorderSizePixel = 0
_48.Size = UDim2.new(0, 200, 0, 50)
_48.Font = Enum.Font.GothamBold
_48.Text = "Project Jojo"
_48.TextColor3 = Color3.fromRGB(255, 255, 255)
_48.TextSize = 20.000
_48.TextWrapped = true

Execute2Frame.Name = "Execute2Frame"
Execute2Frame.Parent = HubFrame
Execute2Frame.Active = true
Execute2Frame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Execute2Frame.BackgroundTransparency = 1.000
Execute2Frame.BorderSizePixel = 0
Execute2Frame.Position = UDim2.new(0.0909999982, 0, 1, 0)
Execute2Frame.Size = UDim2.new(0.909344494, 0, 0.872773528, 0)
Execute2Frame.CanvasSize = UDim2.new(0, 0, 1, 0)
Execute2Frame.ScrollBarThickness = 5

UIGridLayout_2.Parent = Execute2Frame
UIGridLayout_2.HorizontalAlignment = Enum.HorizontalAlignment.Center
UIGridLayout_2.SortOrder = Enum.SortOrder.LayoutOrder
UIGridLayout_2.CellSize = UDim2.new(0, 150, 0, 50)

_1_2.Name = "1"
_1_2.Parent = Execute2Frame
_1_2.BackgroundColor3 = Color3.fromRGB(64, 64, 64)
_1_2.BorderSizePixel = 0
_1_2.Size = UDim2.new(0, 200, 0, 50)
_1_2.Font = Enum.Font.GothamBold
_1_2.Text = "Zyrex Hub"
_1_2.TextColor3 = Color3.fromRGB(255, 255, 255)
_1_2.TextSize = 20.000
_1_2.TextWrapped = true

_2_2.Name = "2"
_2_2.Parent = Execute2Frame
_2_2.BackgroundColor3 = Color3.fromRGB(64, 64, 64)
_2_2.BorderSizePixel = 0
_2_2.Size = UDim2.new(0, 200, 0, 50)
_2_2.Font = Enum.Font.GothamBold
_2_2.Text = "Auratus Hub (Press Z to Open)"
_2_2.TextColor3 = Color3.fromRGB(255, 255, 255)
_2_2.TextScaled = true
_2_2.TextSize = 20.000
_2_2.TextWrapped = true

_3_2.Name = "3"
_3_2.Parent = Execute2Frame
_3_2.BackgroundColor3 = Color3.fromRGB(64, 64, 64)
_3_2.BorderSizePixel = 0
_3_2.Size = UDim2.new(0, 200, 0, 50)
_3_2.Font = Enum.Font.GothamBold
_3_2.Text = "Potato Hub"
_3_2.TextColor3 = Color3.fromRGB(255, 255, 255)
_3_2.TextSize = 20.000
_3_2.TextWrapped = true

_4_2.Name = "4"
_4_2.Parent = Execute2Frame
_4_2.BackgroundColor3 = Color3.fromRGB(64, 64, 64)
_4_2.BorderSizePixel = 0
_4_2.Size = UDim2.new(0, 200, 0, 50)
_4_2.Font = Enum.Font.GothamBold
_4_2.Text = "Fathom Hub"
_4_2.TextColor3 = Color3.fromRGB(255, 255, 255)
_4_2.TextSize = 20.000
_4_2.TextWrapped = true

_5_2.Name = "5"
_5_2.Parent = Execute2Frame
_5_2.BackgroundColor3 = Color3.fromRGB(64, 64, 64)
_5_2.BorderSizePixel = 0
_5_2.Size = UDim2.new(0, 200, 0, 50)
_5_2.Font = Enum.Font.GothamBold
_5_2.Text = "101 Hub"
_5_2.TextColor3 = Color3.fromRGB(255, 255, 255)
_5_2.TextSize = 20.000
_5_2.TextWrapped = true

_6_2.Name = "6"
_6_2.Parent = Execute2Frame
_6_2.BackgroundColor3 = Color3.fromRGB(64, 64, 64)
_6_2.BorderSizePixel = 0
_6_2.Size = UDim2.new(0, 200, 0, 50)
_6_2.Font = Enum.Font.GothamBold
_6_2.Text = "Dark Hub"
_6_2.TextColor3 = Color3.fromRGB(255, 255, 255)
_6_2.TextSize = 20.000
_6_2.TextWrapped = true

Execute3Frame.Name = "Execute3Frame"
Execute3Frame.Parent = HubFrame
Execute3Frame.Active = true
Execute3Frame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Execute3Frame.BackgroundTransparency = 1.000
Execute3Frame.BorderSizePixel = 0
Execute3Frame.Position = UDim2.new(0.0909999982, 0, 1, 0)
Execute3Frame.Size = UDim2.new(0.909344494, 0, 0.872773528, 0)
Execute3Frame.CanvasSize = UDim2.new(0, 0, 1, 0)
Execute3Frame.ScrollBarThickness = 5

UIGridLayout_3.Parent = Execute3Frame
UIGridLayout_3.HorizontalAlignment = Enum.HorizontalAlignment.Center
UIGridLayout_3.SortOrder = Enum.SortOrder.LayoutOrder
UIGridLayout_3.CellSize = UDim2.new(0, 150, 0, 50)

_4_3.Name = "4"
_4_3.Parent = Execute3Frame
_4_3.BackgroundColor3 = Color3.fromRGB(64, 64, 64)
_4_3.BorderSizePixel = 0
_4_3.Size = UDim2.new(0, 200, 0, 50)
_4_3.Font = Enum.Font.GothamBold
_4_3.Text = "CMD-X (Type CMDS)"
_4_3.TextColor3 = Color3.fromRGB(255, 255, 255)
_4_3.TextSize = 20.000
_4_3.TextWrapped = true

_3_3.Name = "3"
_3_3.Parent = Execute3Frame
_3_3.BackgroundColor3 = Color3.fromRGB(64, 64, 64)
_3_3.BorderSizePixel = 0
_3_3.Size = UDim2.new(0, 200, 0, 50)
_3_3.Font = Enum.Font.GothamBold
_3_3.Text = "Ultimate Admin"
_3_3.TextColor3 = Color3.fromRGB(255, 255, 255)
_3_3.TextSize = 20.000
_3_3.TextWrapped = true

_2_3.Name = "2"
_2_3.Parent = Execute3Frame
_2_3.BackgroundColor3 = Color3.fromRGB(64, 64, 64)
_2_3.BorderSizePixel = 0
_2_3.Size = UDim2.new(0, 200, 0, 50)
_2_3.Font = Enum.Font.GothamBold
_2_3.Text = "Reviz Admin"
_2_3.TextColor3 = Color3.fromRGB(255, 255, 255)
_2_3.TextSize = 20.000
_2_3.TextWrapped = true

_1_3.Name = "1"
_1_3.Parent = Execute3Frame
_1_3.BackgroundColor3 = Color3.fromRGB(64, 64, 64)
_1_3.BorderSizePixel = 0
_1_3.Size = UDim2.new(0, 200, 0, 50)
_1_3.Font = Enum.Font.GothamBold
_1_3.Text = "Infinite Yield"
_1_3.TextColor3 = Color3.fromRGB(255, 255, 255)
_1_3.TextSize = 20.000
_1_3.TextWrapped = true

TopbarFrame.Name = "TopbarFrame"
TopbarFrame.Parent = HubFrame
TopbarFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TopbarFrame.BackgroundTransparency = 1.000
TopbarFrame.BorderSizePixel = 0
TopbarFrame.ClipsDescendants = true
TopbarFrame.Position = UDim2.new(0.116457462, 0, 0, 0)
TopbarFrame.Size = UDim2.new(0, 614, 0, 49)

Title.Name = "Title"
Title.Parent = TopbarFrame
Title.BackgroundColor3 = Color3.fromRGB(32, 32, 35)
Title.BackgroundTransparency = 1.000
Title.BorderSizePixel = 0
Title.Position = UDim2.new(0.00713109225, 0, -0.000445300393, 0)
Title.Size = UDim2.new(0, 167, 0, 50)
Title.Font = Enum.Font.GothamBold
Title.Text = "Games"
Title.TextColor3 = Color3.fromRGB(255, 255, 255)
Title.TextSize = 20.000
Title.TextWrapped = true
Title.TextXAlignment = Enum.TextXAlignment.Left

SidebarFrame.Name = "SidebarFrame"
SidebarFrame.Parent = HubFrame
SidebarFrame.Active = true
SidebarFrame.AnchorPoint = Vector2.new(0.5, 0.5)
SidebarFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
SidebarFrame.BackgroundTransparency = 1.000
SidebarFrame.BorderSizePixel = 0
SidebarFrame.ClipsDescendants = true
SidebarFrame.Position = UDim2.new(0.0449999981, 0, 0.500005126, 0)
SidebarFrame.Selectable = true
SidebarFrame.Size = UDim2.new(0.0910000056, 0, 0.944010317, 22)
SidebarFrame.Image = "http://www.roblox.com/asset/?id=4499763366"

B1.Name = "B1"
B1.Parent = SidebarFrame
B1.BackgroundColor3 = Color3.fromRGB(255, 84, 84)
B1.BackgroundTransparency = 1.000
B1.BorderSizePixel = 0
B1.Position = UDim2.new(0.0129826469, 0, 0.171119511, 0)
B1.Size = UDim2.new(0, 65, 0, 25)
B1.Font = Enum.Font.Gotham
B1.Text = "Games"
B1.TextColor3 = Color3.fromRGB(255, 255, 255)
B1.TextSize = 15.000
B1.TextWrapped = true

B2.Name = "B2"
B2.Parent = SidebarFrame
B2.BackgroundColor3 = Color3.fromRGB(255, 84, 84)
B2.BackgroundTransparency = 1.000
B2.BorderSizePixel = 0
B2.Position = UDim2.new(-0.00240196823, 0, 0.234732747, 0)
B2.Size = UDim2.new(0, 65, 0, 25)
B2.Font = Enum.Font.Gotham
B2.Text = "Hubs"
B2.TextColor3 = Color3.fromRGB(255, 255, 255)
B2.TextSize = 15.000
B2.TextWrapped = true

B3.Name = "B3"
B3.Parent = SidebarFrame
B3.BackgroundColor3 = Color3.fromRGB(255, 84, 84)
B3.BackgroundTransparency = 1.000
B3.BorderSizePixel = 0
B3.Position = UDim2.new(0.0129826469, 0, 0.298345983, 0)
B3.Size = UDim2.new(0, 65, 0, 25)
B3.Font = Enum.Font.Gotham
B3.Text = "Admin"
B3.TextColor3 = Color3.fromRGB(255, 255, 255)
B3.TextSize = 15.000
B3.TextWrapped = true

B4.Name = "B4"
B4.Parent = SidebarFrame
B4.BackgroundColor3 = Color3.fromRGB(255, 84, 84)
B4.BackgroundTransparency = 1.000
B4.BorderSizePixel = 0
B4.Position = UDim2.new(0.0129826469, 0, 0.361959219, 0)
B4.Size = UDim2.new(0, 65, 0, 25)
B4.Font = Enum.Font.Gotham
B4.Text = "Trolling"
B4.TextColor3 = Color3.fromRGB(255, 255, 255)
B4.TextSize = 15.000
B4.TextWrapped = true

Logo_4.Name = "Logo"
Logo_4.Parent = SidebarFrame
Logo_4.AnchorPoint = Vector2.new(0.5, 0.5)
Logo_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Logo_4.BackgroundTransparency = 1.000
Logo_4.BorderSizePixel = 0
Logo_4.Position = UDim2.new(0.507692337, 0, 0.0814249367, 0)
Logo_4.Size = UDim2.new(0, 45, 0, 45)
Logo_4.Image = "http://www.roblox.com/asset/?id=5114898244"

Exit.Name = "Exit"
Exit.Parent = SidebarFrame
Exit.BackgroundColor3 = Color3.fromRGB(255, 84, 84)
Exit.BackgroundTransparency = 1.000
Exit.BorderSizePixel = 0
Exit.Position = UDim2.new(-0.00240196823, 0, 0.896310329, 0)
Exit.Size = UDim2.new(0, 65, 0, 20)
Exit.Font = Enum.Font.Gotham
Exit.Text = "X"
Exit.TextColor3 = Color3.fromRGB(255, 255, 255)
Exit.TextSize = 20.000

Minimize.Name = "Minimize"
Minimize.Parent = SidebarFrame
Minimize.BackgroundColor3 = Color3.fromRGB(244, 208, 83)
Minimize.BackgroundTransparency = 1.000
Minimize.BorderSizePixel = 0
Minimize.Position = UDim2.new(0, 0, 0.947201014, 0)
Minimize.Size = UDim2.new(0, 66, 0, 20)
Minimize.Font = Enum.Font.Gotham
Minimize.Text = "-"
Minimize.TextColor3 = Color3.fromRGB(255, 255, 255)
Minimize.TextSize = 20.000

Execute4Frame.Name = "Execute4Frame"
Execute4Frame.Parent = HubFrame
Execute4Frame.Active = true
Execute4Frame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Execute4Frame.BackgroundTransparency = 1.000
Execute4Frame.BorderSizePixel = 0
Execute4Frame.Position = UDim2.new(0.0909999982, 0, 1, 0)
Execute4Frame.Size = UDim2.new(0.909344494, 0, 0.872773528, 0)
Execute4Frame.CanvasSize = UDim2.new(0, 0, 1, 0)
Execute4Frame.ScrollBarThickness = 5

UIGridLayout_4.Parent = Execute4Frame
UIGridLayout_4.HorizontalAlignment = Enum.HorizontalAlignment.Center
UIGridLayout_4.SortOrder = Enum.SortOrder.LayoutOrder
UIGridLayout_4.CellSize = UDim2.new(0, 150, 0, 50)

_1_4.Name = "1"
_1_4.Parent = Execute4Frame
_1_4.BackgroundColor3 = Color3.fromRGB(64, 64, 64)
_1_4.BorderSizePixel = 0
_1_4.Size = UDim2.new(0, 200, 0, 50)
_1_4.Font = Enum.Font.GothamBold
_1_4.Text = "Invisible Flinger"
_1_4.TextColor3 = Color3.fromRGB(255, 255, 255)
_1_4.TextSize = 20.000
_1_4.TextWrapped = true

_2_4.Name = "2"
_2_4.Parent = Execute4Frame
_2_4.BackgroundColor3 = Color3.fromRGB(64, 64, 64)
_2_4.BorderSizePixel = 0
_2_4.Size = UDim2.new(0, 200, 0, 50)
_2_4.Font = Enum.Font.GothamBold
_2_4.Text = "Brick Script"
_2_4.TextColor3 = Color3.fromRGB(255, 255, 255)
_2_4.TextSize = 20.000
_2_4.TextWrapped = true

_3_4.Name = "3"
_3_4.Parent = Execute4Frame
_3_4.BackgroundColor3 = Color3.fromRGB(64, 64, 64)
_3_4.BorderSizePixel = 0
_3_4.Size = UDim2.new(0, 200, 0, 50)
_3_4.Font = Enum.Font.GothamBold
_3_4.Text = "Energize"
_3_4.TextColor3 = Color3.fromRGB(255, 255, 255)
_3_4.TextSize = 20.000
_3_4.TextWrapped = true

_4_4.Name = "4"
_4_4.Parent = Execute4Frame
_4_4.BackgroundColor3 = Color3.fromRGB(64, 64, 64)
_4_4.BorderSizePixel = 0
_4_4.Size = UDim2.new(0, 200, 0, 50)
_4_4.Font = Enum.Font.GothamBold
_4_4.Text = "Chat Bypass (/e)"
_4_4.TextColor3 = Color3.fromRGB(255, 255, 255)
_4_4.TextSize = 20.000
_4_4.TextWrapped = true

_5_3.Name = "5"
_5_3.Parent = Execute4Frame
_5_3.BackgroundColor3 = Color3.fromRGB(64, 64, 64)
_5_3.BorderSizePixel = 0
_5_3.Size = UDim2.new(0, 200, 0, 50)
_5_3.Font = Enum.Font.GothamBold
_5_3.Text = "OP-Finality"
_5_3.TextColor3 = Color3.fromRGB(255, 255, 255)
_5_3.TextSize = 20.000
_5_3.TextWrapped = true

HubWorkGameFrame.Name = "HubWorkGameFrame"
HubWorkGameFrame.Parent = CocoHub
HubWorkGameFrame.AnchorPoint = Vector2.new(0.5, 0.5)
HubWorkGameFrame.BackgroundColor3 = Color3.fromRGB(43, 43, 43)
HubWorkGameFrame.BorderSizePixel = 0
HubWorkGameFrame.ClipsDescendants = true
HubWorkGameFrame.Position = UDim2.new(0.5, 0, 2, 0)
HubWorkGameFrame.Size = UDim2.new(0, 240, 0, 322)

GameFrame.Name = "GameFrame"
GameFrame.Parent = HubWorkGameFrame
GameFrame.Active = true
GameFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
GameFrame.BackgroundTransparency = 1.000
GameFrame.BorderSizePixel = 0
GameFrame.Position = UDim2.new(0, 0, 0.0655674934, 0)
GameFrame.Size = UDim2.new(1, 0, 0.934432507, 0)
GameFrame.CanvasSize = UDim2.new(0, 0, 1, 0)
GameFrame.ScrollBarThickness = 5

UIGridLayout_5.Parent = GameFrame
UIGridLayout_5.SortOrder = Enum.SortOrder.LayoutOrder
UIGridLayout_5.CellPadding = UDim2.new(0, 0, 0, 0)
UIGridLayout_5.CellSize = UDim2.new(1, 0, 0.119999997, 0)

_1_5.Name = "1"
_1_5.Parent = GameFrame
_1_5.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
_1_5.BackgroundTransparency = 1.000
_1_5.BorderSizePixel = 0
_1_5.Size = UDim2.new(0, 200, 0, 50)
_1_5.Font = Enum.Font.GothamBold
_1_5.Text = "Blox Hunt"
_1_5.TextColor3 = Color3.fromRGB(255, 255, 255)
_1_5.TextSize = 20.000
_1_5.TextWrapped = true

_2_5.Name = "2"
_2_5.Parent = GameFrame
_2_5.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
_2_5.BackgroundTransparency = 1.000
_2_5.BorderSizePixel = 0
_2_5.Size = UDim2.new(0, 200, 0, 50)
_2_5.Font = Enum.Font.GothamBold
_2_5.Text = "Break In"
_2_5.TextColor3 = Color3.fromRGB(255, 255, 255)
_2_5.TextSize = 20.000
_2_5.TextWrapped = true

_3_5.Name = "3"
_3_5.Parent = GameFrame
_3_5.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
_3_5.BackgroundTransparency = 1.000
_3_5.BorderSizePixel = 0
_3_5.Size = UDim2.new(0, 200, 0, 50)
_3_5.Font = Enum.Font.GothamBold
_3_5.Text = "Ninja Legends"
_3_5.TextColor3 = Color3.fromRGB(255, 255, 255)
_3_5.TextSize = 20.000
_3_5.TextWrapped = true

_4_5.Name = "4"
_4_5.Parent = GameFrame
_4_5.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
_4_5.BackgroundTransparency = 1.000
_4_5.BorderSizePixel = 0
_4_5.Size = UDim2.new(0, 200, 0, 50)
_4_5.Font = Enum.Font.GothamBold
_4_5.Text = "Natural Disaster Survival"
_4_5.TextColor3 = Color3.fromRGB(255, 255, 255)
_4_5.TextSize = 20.000
_4_5.TextWrapped = true

_5_4.Name = "5"
_5_4.Parent = GameFrame
_5_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
_5_4.BackgroundTransparency = 1.000
_5_4.BorderSizePixel = 0
_5_4.Size = UDim2.new(0, 200, 0, 50)
_5_4.Font = Enum.Font.GothamBold
_5_4.Text = "Build a Boat for Treasure"
_5_4.TextColor3 = Color3.fromRGB(255, 255, 255)
_5_4.TextSize = 20.000
_5_4.TextWrapped = true

_6_3.Name = "6"
_6_3.Parent = GameFrame
_6_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
_6_3.BackgroundTransparency = 1.000
_6_3.BorderSizePixel = 0
_6_3.Size = UDim2.new(0, 200, 0, 50)
_6_3.Font = Enum.Font.GothamBold
_6_3.Text = "Zombie Attack"
_6_3.TextColor3 = Color3.fromRGB(255, 255, 255)
_6_3.TextSize = 20.000
_6_3.TextWrapped = true

_7_2.Name = "7"
_7_2.Parent = GameFrame
_7_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
_7_2.BackgroundTransparency = 1.000
_7_2.BorderSizePixel = 0
_7_2.Size = UDim2.new(0, 200, 0, 50)
_7_2.Font = Enum.Font.GothamBold
_7_2.Text = "Prison Life"
_7_2.TextColor3 = Color3.fromRGB(255, 255, 255)
_7_2.TextSize = 20.000
_7_2.TextWrapped = true

_8_2.Name = "8"
_8_2.Parent = GameFrame
_8_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
_8_2.BackgroundTransparency = 1.000
_8_2.BorderSizePixel = 0
_8_2.Size = UDim2.new(0, 200, 0, 50)
_8_2.Font = Enum.Font.GothamBold
_8_2.Text = "Arsenal"
_8_2.TextColor3 = Color3.fromRGB(255, 255, 255)
_8_2.TextSize = 20.000
_8_2.TextWrapped = true

TopbarFrame_2.Name = "TopbarFrame"
TopbarFrame_2.Parent = HubWorkGameFrame
TopbarFrame_2.Active = true
TopbarFrame_2.AnchorPoint = Vector2.new(0.5, 0.5)
TopbarFrame_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TopbarFrame_2.BackgroundTransparency = 1.000
TopbarFrame_2.BorderSizePixel = 0
TopbarFrame_2.ClipsDescendants = true
TopbarFrame_2.Position = UDim2.new(0.5, 0, 0.0280000009, 0)
TopbarFrame_2.Selectable = true
TopbarFrame_2.Size = UDim2.new(1, 0, 0, 22)
TopbarFrame_2.Image = "http://www.roblox.com/asset/?id=4499763366"

Exit_2.Name = "Exit"
Exit_2.Parent = TopbarFrame_2
Exit_2.BackgroundColor3 = Color3.fromRGB(255, 84, 84)
Exit_2.BackgroundTransparency = 1.000
Exit_2.BorderSizePixel = 0
Exit_2.Position = UDim2.new(0.938000023, 0, 0.150000006, 0)
Exit_2.Size = UDim2.new(0, 15, 0, 15)
Exit_2.Font = Enum.Font.Gotham
Exit_2.Text = "X"
Exit_2.TextColor3 = Color3.fromRGB(255, 255, 255)
Exit_2.TextSize = 20.000

Credits.Name = "Credits"
Credits.Parent = TopbarFrame_2
Credits.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Credits.BackgroundTransparency = 1.000
Credits.BorderSizePixel = 0
Credits.Position = UDim2.new(0.0111576011, 0, 0, 0)
Credits.Size = UDim2.new(0.258716851, 0, 1, 0)
Credits.Font = Enum.Font.GothamBold
Credits.Text = "Coco Hub"
Credits.TextColor3 = Color3.fromRGB(255, 255, 255)
Credits.TextSize = 13.000
Credits.TextWrapped = true
Credits.TextXAlignment = Enum.TextXAlignment.Left

IntroHubFrame.Name = "IntroHubFrame"
IntroHubFrame.Parent = CocoHub
IntroHubFrame.AnchorPoint = Vector2.new(0.5, 0.5)
IntroHubFrame.BackgroundColor3 = Color3.fromRGB(43, 43, 43)
IntroHubFrame.BackgroundTransparency = 1.000
IntroHubFrame.BorderSizePixel = 0
IntroHubFrame.ClipsDescendants = true
IntroHubFrame.Position = UDim2.new(0.5, 0, 0.5, 0)
IntroHubFrame.Size = UDim2.new(0, 717, 0, 393)

IntroFrame.Name = "IntroFrame"
IntroFrame.Parent = IntroHubFrame
IntroFrame.AnchorPoint = Vector2.new(0.5, 0.5)
IntroFrame.BackgroundColor3 = Color3.fromRGB(43, 43, 43)
IntroFrame.BackgroundTransparency = 1.000
IntroFrame.BorderColor3 = Color3.fromRGB(43, 43, 43)
IntroFrame.ClipsDescendants = true
IntroFrame.Position = UDim2.new(0.5, 0, 0.5, 0)
IntroFrame.Image = "rbxassetid://3570695787"
IntroFrame.ImageColor3 = Color3.fromRGB(43, 43, 43)
IntroFrame.ScaleType = Enum.ScaleType.Slice
IntroFrame.SliceCenter = Rect.new(100, 100, 100, 100)

CocoLogo.Name = "CocoLogo"
CocoLogo.Parent = IntroFrame
CocoLogo.BackgroundColor3 = Color3.fromRGB(43, 43, 43)
CocoLogo.BackgroundTransparency = 1.000
CocoLogo.BorderColor3 = Color3.fromRGB(43, 43, 43)
CocoLogo.BorderSizePixel = 0
CocoLogo.ClipsDescendants = true
CocoLogo.Selectable = true
CocoLogo.Size = UDim2.new(1, 0, 1, 0)
CocoLogo.Image = "rbxassetid://5114892367"
CocoLogo.ImageTransparency = 1.000

local function JLRYMON_fake_script() -- CocoHub.NavigationFunction 
	local script = Instance.new('Script', CocoHub)

	script.Parent.IntroHubFrame.IntroFrame:TweenSize(UDim2.new(0,100,0,100), "Out", "Quad", 0.5, true)
	script.Parent.IntroHubFrame.IntroFrame.CocoLogo.ImageTransparency = 1
	wait (0.02)
	script.Parent.IntroHubFrame.IntroFrame.CocoLogo.ImageTransparency = 0.9
	wait (0.02)
	script.Parent.IntroHubFrame.IntroFrame.CocoLogo.ImageTransparency = 0.8
	wait (0.02)
	script.Parent.IntroHubFrame.IntroFrame.CocoLogo.ImageTransparency = 0.7
	wait (0.02)
	script.Parent.IntroHubFrame.IntroFrame.CocoLogo.ImageTransparency = 0.6
	wait (0.02)
	script.Parent.IntroHubFrame.IntroFrame.CocoLogo.ImageTransparency = 0.5
	wait (0.02)
	script.Parent.IntroHubFrame.IntroFrame.CocoLogo.ImageTransparency = 0.4
	wait (0.02)
	script.Parent.IntroHubFrame.IntroFrame.CocoLogo.ImageTransparency = 0.3
	wait (0.02)
	script.Parent.IntroHubFrame.IntroFrame.CocoLogo.ImageTransparency = 0.2
	wait (0.02)
	script.Parent.IntroHubFrame.IntroFrame.CocoLogo.ImageTransparency = 0.1
	wait (0.02)
	script.Parent.IntroHubFrame.IntroFrame.CocoLogo.ImageTransparency = 0
	wait(1)
	script.Parent.IntroHubFrame.IntroFrame:TweenSize(UDim2.new(0,3000,0,3000), "Out", "Quad", 0.5, true)
	script.Parent.IntroHubFrame.IntroFrame.CocoLogo.ImageTransparency = 0
	wait (0.02)
	script.Parent.IntroHubFrame.IntroFrame.CocoLogo.ImageTransparency = 0.1
	wait (0.02)
	script.Parent.IntroHubFrame.IntroFrame.CocoLogo.ImageTransparency = 0.2
	wait (0.02)
	script.Parent.IntroHubFrame.IntroFrame.CocoLogo.ImageTransparency = 0.3
	wait (0.02)
	script.Parent.IntroHubFrame.IntroFrame.CocoLogo.ImageTransparency = 0.4
	wait (0.02)
	script.Parent.IntroHubFrame.IntroFrame.CocoLogo.ImageTransparency = 0.5
	wait (0.02)
	script.Parent.IntroHubFrame.IntroFrame.CocoLogo.ImageTransparency = 0.6
	wait (0.02)
	script.Parent.IntroHubFrame.IntroFrame.CocoLogo.ImageTransparency = 0.7
	wait (0.02)
	script.Parent.IntroHubFrame.IntroFrame.CocoLogo.ImageTransparency = 0.8
	wait (0.02)
	script.Parent.IntroHubFrame.IntroFrame.CocoLogo.ImageTransparency = 0.9
	wait (0.02)
	script.Parent.IntroHubFrame.IntroFrame.CocoLogo.ImageTransparency = 1
	wait(0.5)
	script.Parent.IntroHubFrame:TweenPosition(UDim2.new(0.5,0,-1.5,0), "Out", "Quad", 0.5, true)
	wait(0.5)
	script.Parent.HubFrame:TweenPosition(UDim2.new(0.5,0,0.5,0), "Out", "Quad", 0.5, true)
	
	
	script.Parent.HubFrame.SidebarFrame.Exit.MouseButton1Click:connect(function()
		script.Parent.HubFrame:TweenSize(UDim2.new(0,0,0,0), "Out", "Quad", 0.5, true)
		wait(0.5)
		script.Parent.Parent.CocoHub:remove()
	end)
	
	script.Parent.HubFrame.SidebarFrame.Minimize.MouseButton1Click:connect(function()
		script.Parent.HubFrame:TweenPosition(UDim2.new(0.5,0,2,0), "Out", "Quad", 0.5, true)
		wait(0.5)
		script.Parent.ButtonFrame:TweenPosition(UDim2.new(1,-50,1,-50), "Out", "Quad", 0.5, true)
	end)
	
	script.Parent.HubFrame.SidebarFrame.B1.MouseButton1Click:connect(function()
		script.Parent.HubFrame.TopbarFrame.Title.Text = "Games"
		script.Parent.HubFrame.Execute1Frame:TweenPosition(UDim2.new(0.091, 0,0.127,0), "Out", "Quad", 0.5, true)
		script.Parent.HubFrame.Execute2Frame:TweenPosition(UDim2.new(0.091, 0,1,0), "Out", "Quad", 0.5, true)
		script.Parent.HubFrame.Execute3Frame:TweenPosition(UDim2.new(0.091, 0,1,0), "Out", "Quad", 0.5, true)
		script.Parent.HubFrame.Execute4Frame:TweenPosition(UDim2.new(0.091, 0,1,0), "Out", "Quad", 0.5, true)
	end)
	script.Parent.HubFrame.SidebarFrame.B2.MouseButton1Click:connect(function()
		script.Parent.HubFrame.TopbarFrame.Title.Text = "Hubs"
		script.Parent.HubFrame.Execute2Frame:TweenPosition(UDim2.new(0.091, 0,0.127,0), "Out", "Quad", 0.5, true)
		script.Parent.HubFrame.Execute1Frame:TweenPosition(UDim2.new(0.091, 0,1,0), "Out", "Quad", 0.5, true)
		script.Parent.HubFrame.Execute3Frame:TweenPosition(UDim2.new(0.091, 0,1,0), "Out", "Quad", 0.5, true)
		script.Parent.HubFrame.Execute4Frame:TweenPosition(UDim2.new(0.091, 0,1,0), "Out", "Quad", 0.5, true)
	end)
	script.Parent.HubFrame.SidebarFrame.B3.MouseButton1Click:connect(function()
		script.Parent.HubFrame.TopbarFrame.Title.Text = "Admin"
		script.Parent.HubFrame.Execute3Frame:TweenPosition(UDim2.new(0.091, 0,0.127,0), "Out", "Quad", 0.5, true)
		script.Parent.HubFrame.Execute1Frame:TweenPosition(UDim2.new(0.091, 0,1,0), "Out", "Quad", 0.5, true)
		script.Parent.HubFrame.Execute2Frame:TweenPosition(UDim2.new(0.091, 0,1,0), "Out", "Quad", 0.5, true)
		script.Parent.HubFrame.Execute4Frame:TweenPosition(UDim2.new(0.091, 0,1,0), "Out", "Quad", 0.5, true)
	end)
	script.Parent.HubFrame.SidebarFrame.B4.MouseButton1Click:connect(function()
		script.Parent.HubFrame.TopbarFrame.Title.Text = "Trolling"
		script.Parent.HubFrame.Execute4Frame:TweenPosition(UDim2.new(0.091, 0,0.127,0), "Out", "Quad", 0.5, true)
		script.Parent.HubFrame.Execute2Frame:TweenPosition(UDim2.new(0.091, 0,1,0), "Out", "Quad", 0.5, true)
		script.Parent.HubFrame.Execute3Frame:TweenPosition(UDim2.new(0.091, 0,1,0), "Out", "Quad", 0.5, true)
		script.Parent.HubFrame.Execute1Frame:TweenPosition(UDim2.new(0.091, 0,1,0), "Out", "Quad", 0.5, true)
	end)
	
	script.Parent.ButtonFrame.OpenButton.MouseButton1Click:connect(function()
		script.Parent.ButtonFrame:TweenPosition(UDim2.new(1,-50,2,-50), "Out", "Quad", 0.5, true)
		wait(0.5)
		script.Parent.HubFrame:TweenPosition(UDim2.new(0.5,0,0.5,0), "Out", "Quad", 0.5, true)
	end)
	
	script.Parent.HubWorkGameFrame.TopbarFrame.Exit.MouseButton1Click:connect(function()
		script.Parent.HubWorkGameFrame:TweenPosition(UDim2.new(0.5,0,2,0), "Out", "Quad", 0.5, true)
	end)
end
coroutine.wrap(JLRYMON_fake_script)()
local function XFSD_fake_script() -- HubFrame.DraggingScript 
	local script = Instance.new('LocalScript', HubFrame)

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
coroutine.wrap(XFSD_fake_script)()
local function WWREI_fake_script() -- _43.Script 
	local script = Instance.new('Script', _43)

	script.Parent.MouseButton1Down:Connect(function()
		loadstring(game:HttpGet("https://pastebin.com/raw/uD6w0Wgb"))();
	end)
end
coroutine.wrap(WWREI_fake_script)()
local function AXWJCU_fake_script() -- _44.Script 
	local script = Instance.new('Script', _44)

	script.Parent.MouseButton1Down:Connect(function()
		loadstring(game:HttpGet("https://pastebin.com/raw/q817HYb9"))();
	end)
end
coroutine.wrap(AXWJCU_fake_script)()
local function KIGPM_fake_script() -- _45.Script 
	local script = Instance.new('Script', _45)

	script.Parent.MouseButton1Down:Connect(function()
		loadstring(game:HttpGet("https://pastebin.com/raw/LEqzpDW0"))();
	end)
end
coroutine.wrap(KIGPM_fake_script)()
local function OLMIULT_fake_script() -- _46.Script 
	local script = Instance.new('Script', _46)

	script.Parent.MouseButton1Down:Connect(function()
		loadstring(game:HttpGet("https://pastebin.com/raw/ju2teccL"))();
	end)
end
coroutine.wrap(OLMIULT_fake_script)()
local function QRDLZL_fake_script() -- _1.Script 
	local script = Instance.new('Script', _1)

	script.Parent.MouseButton1Down:Connect(function()
		loadstring(game:HttpGet("https://raw.githubusercontent.com/CreativeHell/public-scripts/master/abd-public.lua"))();
	end)
end
coroutine.wrap(QRDLZL_fake_script)()
local function MSBY_fake_script() -- _2.Script 
	local script = Instance.new('Script', _2)

	script.Parent.MouseButton1Down:Connect(function()
		loadstring(game:HttpGet(('https://raw.githubusercontent.com/NGHDDDX/ScriptHubScripts/master/CCAimbot'),true))()
	end)
end
coroutine.wrap(MSBY_fake_script)()
local function FBZNMSG_fake_script() -- _3.Script 
	local script = Instance.new('Script', _3)

	script.Parent.MouseButton1Down:Connect(function()
		loadstring(game:HttpGet("https://ghostbin.co/paste/qua6e/raw"))();
	end)
end
coroutine.wrap(FBZNMSG_fake_script)()
local function UGEECJ_fake_script() -- _4.Script 
	local script = Instance.new('Script', _4)

	script.Parent.MouseButton1Down:Connect(function()
		loadstring(game:HttpGet("https://raw.githubusercontent.com/Hillsides/Game-Frickers/master/Balloon%20Simulator%202%20%5BPreview%20Of%20Dogey%20Hub%5D.lua",true))()
	end)
end
coroutine.wrap(UGEECJ_fake_script)()
local function DRQCEB_fake_script() -- _5.Script 
	local script = Instance.new('Script', _5)

	script.Parent.MouseButton1Down:Connect(function()
		loadstring(game:HttpGet("https://pastebin.com/raw/3qs77TTk"))();
	end)
end
coroutine.wrap(DRQCEB_fake_script)()
local function OPCULQU_fake_script() -- _6.Script 
	local script = Instance.new('Script', _6)

	script.Parent.MouseButton1Down:Connect(function()
		loadstring(game:HttpGet("https://pastebin.com/raw/cv4yFfQU"))();
	end)
end
coroutine.wrap(OPCULQU_fake_script)()
local function NABVAJ_fake_script() -- _7.Script 
	local script = Instance.new('Script', _7)

	script.Parent.MouseButton1Down:Connect(function()
		loadstring(game:HttpGet("https://pastebin.com/raw/AYjCdjgk"))();
	end)
end
coroutine.wrap(NABVAJ_fake_script)()
local function VYYAXA_fake_script() -- _8.Script 
	local script = Instance.new('Script', _8)

	script.Parent.MouseButton1Down:Connect(function()
		loadstring(game:HttpGet("https://pastebin.com/raw/yigKxDrK"))();
	end)
end
coroutine.wrap(VYYAXA_fake_script)()
local function RTZM_fake_script() -- _49.Script 
	local script = Instance.new('Script', _49)

	script.Parent.MouseButton1Down:Connect(function()
		loadstring(game:HttpGet("https://raw.githubusercontent.com/MarsQQ/Unpatchabomb/master/Unpatchabomb"))();
	end)
end
coroutine.wrap(RTZM_fake_script)()
local function GSZCN_fake_script() -- _10.Script 
	local script = Instance.new('Script', _10)

	script.Parent.MouseButton1Down:Connect(function()
		loadstring(game:HttpGet("https://pastebin.com/raw/MLPypHYv"))();
	end)
end
coroutine.wrap(GSZCN_fake_script)()
local function TDDXDLT_fake_script() -- _11.Script 
	local script = Instance.new('Script', _11)

	script.Parent.MouseButton1Down:Connect(function()
		loadstring(game:HttpGet("https://pastebin.com/raw/4XSEyeag"))();
	end)
end
coroutine.wrap(TDDXDLT_fake_script)()
local function SGFU_fake_script() -- _12.Script 
	local script = Instance.new('Script', _12)

	script.Parent.MouseButton1Down:Connect(function()
		loadstring(game:HttpGet("https://pastebin.com/raw/7Rc6nrdZ"))();
	end)
end
coroutine.wrap(SGFU_fake_script)()
local function JRUYAN_fake_script() -- _13.Script 
	local script = Instance.new('Script', _13)

	script.Parent.MouseButton1Down:Connect(function()
		loadstring(game:HttpGet("https://pastebin.com/raw/AcHFc885"))();
	end)
end
coroutine.wrap(JRUYAN_fake_script)()
local function XIFJFNO_fake_script() -- _14.Script 
	local script = Instance.new('Script', _14)

	script.Parent.MouseButton1Down:Connect(function()
		loadstring(game:HttpGet("https://pastebin.com/raw/GZWNs9uv"))();
	end)
end
coroutine.wrap(XIFJFNO_fake_script)()
local function DXIY_fake_script() -- _15.Script 
	local script = Instance.new('Script', _15)

	script.Parent.MouseButton1Down:Connect(function()
		loadstring(game:HttpGet("https://pastebin.com/raw/URDBqiUw"))();
	end)
end
coroutine.wrap(DXIY_fake_script)()
local function UHFOKT_fake_script() -- _16.Script 
	local script = Instance.new('Script', _16)

	script.Parent.MouseButton1Down:Connect(function()
		loadstring(game:HttpGet(("https://raw.githubusercontent.com/Denverrz/scripts/master/BrickedUrMom.lua"),true))()
	end)
end
coroutine.wrap(UHFOKT_fake_script)()
local function TGLXHJZ_fake_script() -- _17.Script 
	local script = Instance.new('Script', _17)

	script.Parent.MouseButton1Down:Connect(function()
		loadstring(game:HttpGet("https://pastebin.com/raw/cPNc5xV7"))();
	end)
end
coroutine.wrap(TGLXHJZ_fake_script)()
local function VSXVVJ_fake_script() -- _18.Script 
	local script = Instance.new('Script', _18)

	script.Parent.MouseButton1Down:Connect(function()
		loadstring(game:HttpGet("https://pastebin.com/raw/TXra9Typ"))();
	end)
end
coroutine.wrap(VSXVVJ_fake_script)()
local function OONNTZ_fake_script() -- _19.Script 
	local script = Instance.new('Script', _19)

	script.Parent.MouseButton1Down:Connect(function()
		loadstring(game:HttpGet("https://raw.githubusercontent.com/MarsQQ/ScriptHubScripts/master/Jailbricked"))();
	end)
end
coroutine.wrap(OONNTZ_fake_script)()
local function EIIM_fake_script() -- _20.Script 
	local script = Instance.new('Script', _20)

	script.Parent.MouseButton1Down:Connect(function()
		loadstring(game:HttpGet("https://pastebin.com/raw/1ZiryX69"))();
	end)
end
coroutine.wrap(EIIM_fake_script)()
local function MQCMD_fake_script() -- _21.Script 
	local script = Instance.new('Script', _21)

	script.Parent.MouseButton1Down:Connect(function()
		loadstring(game:HttpGet("https://pastebin.com/raw/qc7y8Xrz"))();
	end)
end
coroutine.wrap(MQCMD_fake_script)()
local function RYFQONY_fake_script() -- _22.Script 
	local script = Instance.new('Script', _22)

	script.Parent.MouseButton1Down:Connect(function()
		loadstring(game:HttpGet("https://pastebin.com/raw/dGmwtKFZ"))();
	end)
end
coroutine.wrap(RYFQONY_fake_script)()
local function YCFTGB_fake_script() -- _23.Script 
	local script = Instance.new('Script', _23)

	script.Parent.MouseButton1Down:Connect(function()
		loadstring(game:HttpGet("https://pastebin.com/raw/mz3TQhjt"))();
	end)
end
coroutine.wrap(YCFTGB_fake_script)()
local function IEXPD_fake_script() -- _24.Script 
	local script = Instance.new('Script', _24)

	script.Parent.MouseButton1Down:Connect(function()
		loadstring(game:HttpGet("https://pastebin.com/raw/As5D6NAN"))();
	end)
end
coroutine.wrap(IEXPD_fake_script)()
local function OWLRT_fake_script() -- _25.Script 
	local script = Instance.new('Script', _25)

	script.Parent.MouseButton1Down:Connect(function()
		loadstring(game:HttpGet("https://pastebin.com/raw/9ucUHW77"))();
	end)
end
coroutine.wrap(OWLRT_fake_script)()
local function NJRYTHX_fake_script() -- _26.Script 
	local script = Instance.new('Script', _26)

	script.Parent.MouseButton1Down:Connect(function()
		loadstring(game:HttpGet("https://raw.githubusercontent.com/MarsQQ/ScriptHubScripts/master/MM2%20Admin%20Panel"))();
	end)
end
coroutine.wrap(NJRYTHX_fake_script)()
local function NVNDLHK_fake_script() -- _27.Script 
	local script = Instance.new('Script', _27)

	script.Parent.MouseButton1Down:Connect(function()
		loadstring(game:HttpGet(('https://pastebin.com/raw/nGA6gAKM'),true))()
	end)
end
coroutine.wrap(NVNDLHK_fake_script)()
local function GBPOI_fake_script() -- _28.Script 
	local script = Instance.new('Script', _28)

	script.Parent.MouseButton1Down:Connect(function()
		loadstring(game:HttpGet("https://raw.githubusercontent.com/NGHDDDX/ScriptHubScripts/master/NinjaLegends",true))()
	end)
end
coroutine.wrap(GBPOI_fake_script)()
local function DOLOSH_fake_script() -- _29.Script 
	local script = Instance.new('Script', _29)

	script.Parent.MouseButton1Down:Connect(function()
		loadstring(game:HttpGet("https://pastebin.com/raw/RPCYGzpu"))();
	end)
end
coroutine.wrap(DOLOSH_fake_script)()
local function XEBUFK_fake_script() -- _30.Script 
	local script = Instance.new('Script', _30)

	script.Parent.MouseButton1Down:Connect(function()
		loadstring(game:HttpGet("https://ghostbin.co/paste/fs2qt/raw"))();
	end)
end
coroutine.wrap(XEBUFK_fake_script)()
local function FGXMJ_fake_script() -- _31.Script 
	local script = Instance.new('Script', _31)

	script.Parent.MouseButton1Down:Connect(function()
		loadstring(game:HttpGet("https://pastebin.com/raw/kh2JAXsL"))();
	end)
end
coroutine.wrap(FGXMJ_fake_script)()
local function NTSYFG_fake_script() -- _32.Script 
	local script = Instance.new('Script', _32)

	script.Parent.MouseButton1Down:Connect(function()
		loadstring(game:HttpGet("https://raw.githubusercontent.com/MarsQQ/ScriptHubScripts/master/Prisonware"))();
	end)
end
coroutine.wrap(NTSYFG_fake_script)()
local function YBJATS_fake_script() -- _33.Script 
	local script = Instance.new('Script', _33)

	script.Parent.MouseButton1Down:Connect(function()
		loadstring(game:HttpGet("https://pastebin.com/raw/FKane3Xg"))();
	end)
end
coroutine.wrap(YBJATS_fake_script)()
local function ZEMCYLR_fake_script() -- _34.Script 
	local script = Instance.new('Script', _34)

	script.Parent.MouseButton1Down:Connect(function()
		loadstring(game:HttpGet("https://pastebin.com/raw/qMcbuEuJ"))();
	end)
end
coroutine.wrap(ZEMCYLR_fake_script)()
local function KMQTI_fake_script() -- _35.Script 
	local script = Instance.new('Script', _35)

	script.Parent.MouseButton1Down:Connect(function()
		loadstring(game:HttpGet("https://pastebin.com/raw/jm3uaYpb"))();
	end)
end
coroutine.wrap(KMQTI_fake_script)()
local function FSQS_fake_script() -- _36.Script 
	local script = Instance.new('Script', _36)

	script.Parent.MouseButton1Down:Connect(function()
		loadstring(game:HttpGet("https://pastebinp.com/raw/Qv86dKq8"))();
	end)
end
coroutine.wrap(FSQS_fake_script)()
local function LVCRT_fake_script() -- _37.Script 
	local script = Instance.new('Script', _37)

	script.Parent.MouseButton1Down:Connect(function()
		loadstring(game:HttpGet("https://pastebinp.com/raw/f1whedKk"))();
	end)
end
coroutine.wrap(LVCRT_fake_script)()
local function LDIUEBE_fake_script() -- _38.Script 
	local script = Instance.new('Script', _38)

	script.Parent.MouseButton1Down:Connect(function()
		loadstring(game:HttpGet("https://pastebinp.com/raw/4jHBeTtf"))();
	end)
end
coroutine.wrap(LDIUEBE_fake_script)()
local function VXJI_fake_script() -- _39.Script 
	local script = Instance.new('Script', _39)

	script.Parent.MouseButton1Down:Connect(function()
		loadstring(game:HttpGet("https://pastebinp.com/raw/YYVLbzVg"))();
	end)
end
coroutine.wrap(VXJI_fake_script)()
local function NCYN_fake_script() -- _40.Script 
	local script = Instance.new('Script', _40)

	script.Parent.MouseButton1Down:Connect(function()
		loadstring(game:HttpGet("https://pastebinp.com/raw/61vdJN2e"))();
	end)
end
coroutine.wrap(NCYN_fake_script)()
local function DFZH_fake_script() -- _41.Script 
	local script = Instance.new('Script', _41)

	script.Parent.MouseButton1Down:Connect(function()
		loadstring(game:HttpGet("https://pastebinp.com/raw/mxVSVCLE"))();
	end)
end
coroutine.wrap(DFZH_fake_script)()
local function BRDDYTN_fake_script() -- _42.Script 
	local script = Instance.new('Script', _42)

	script.Parent.MouseButton1Down:Connect(function()
		loadstring(game:HttpGet("https://pastebinp.com/raw/Ptrnnf3D"))();
	end)
end
coroutine.wrap(BRDDYTN_fake_script)()
local function EPDXO_fake_script() -- _47.Script 
	local script = Instance.new('Script', _47)

	script.Parent.MouseButton1Down:Connect(function()
		loadstring(game:HttpGet("https://pastebinp.com/raw/Ptrnnf3D"))();
	end)
end
coroutine.wrap(EPDXO_fake_script)()
local function KUPPBI_fake_script() -- _48.Script 
	local script = Instance.new('Script', _48)

	script.Parent.MouseButton1Down:Connect(function()
		loadstring(game:HttpGet("https://pastebinp.com/raw/FKane3Xg"))();
	end)
end
coroutine.wrap(KUPPBI_fake_script)()
local function TRITHM_fake_script() -- _1_2.Script 
	local script = Instance.new('Script', _1_2)

	script.Parent.MouseButton1Down:Connect(function()
		script.Parent.Parent.Parent.Parent.HubWorkGameFrame:TweenPosition(UDim2.new(0.5,0,0.5,0), "Out", "Quad", 0.5, true)
		_G.Toggle_GUI = Enum.KeyCode.RightControl
	loadstring(game:HttpGet(("https://raw.githubusercontent.com/NotZyrex/Zyrex-Hub/master/Main.lua"),true))()
	end)
end
coroutine.wrap(TRITHM_fake_script)()
local function AOZIR_fake_script() -- _2_2.Script 
	local script = Instance.new('Script', _2_2)

	script.Parent.MouseButton1Down:Connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/RealMrQuacks/AuratusX/master/Load"))()
	end)
end
coroutine.wrap(AOZIR_fake_script)()
local function KHLPDBG_fake_script() -- _3_2.Script 
	local script = Instance.new('Script', _3_2)

	script.Parent.MouseButton1Down:Connect(function()
		loadstring(game:HttpGet(('https://www.potato-hub.com/PotatoHub.lua'),true))()
	end)
end
coroutine.wrap(KHLPDBG_fake_script)()
local function UBADDU_fake_script() -- _4_2.Script 
	local script = Instance.new('Script', _4_2)

	script.Parent.MouseButton1Down:Connect(function()
	loadstring(game:HttpGet("https://pastebinp.com/raw/UmhaEvTT",true))()
	end)
end
coroutine.wrap(UBADDU_fake_script)()
local function IOQZ_fake_script() -- _5_2.Script 
	local script = Instance.new('Script', _5_2)

	script.Parent.MouseButton1Down:Connect(function()
	loadstring(game:HttpGet("https://pastebinp.com/raw/D49LF55e",true))()
	end)
end
coroutine.wrap(IOQZ_fake_script)()
local function MADASIQ_fake_script() -- _6_2.Script 
	local script = Instance.new('Script', _6_2)

	script.Parent.MouseButton1Down:Connect(function()
	loadstring(game:HttpGet(("https://pastebinp.com/raw/yCrBkPaY"), true))()
	end)
end
coroutine.wrap(MADASIQ_fake_script)()
local function EWRQ_fake_script() -- _4_3.Script 
	local script = Instance.new('Script', _4_3)

	script.Parent.MouseButton1Down:Connect(function()
		loadstring(game:HttpGet("https://pastebinp.com/raw/HFkyyd1H", true))()
	end)
end
coroutine.wrap(EWRQ_fake_script)()
local function PNKLWEE_fake_script() -- _3_3.Script 
	local script = Instance.new('Script', _3_3)

	script.Parent.MouseButton1Down:Connect(function()
		loadstring(game:HttpGet("https://pastebinp.com/raw/bVjM0xCS", true))()
	end)
end
coroutine.wrap(PNKLWEE_fake_script)()
local function ABIE_fake_script() -- _2_3.Script 
	local script = Instance.new('Script', _2_3)

	script.Parent.MouseButton1Down:Connect(function()
		loadstring(game:HttpGet(('https://pastebinp.com/raw/Hv2BEncA'),true))()
	end)
end
coroutine.wrap(ABIE_fake_script)()
local function IQBC_fake_script() -- _1_3.Script 
	local script = Instance.new('Script', _1_3)

	script.Parent.MouseButton1Down:Connect(function()
		loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
	end)
end
coroutine.wrap(IQBC_fake_script)()
local function XYDA_fake_script() -- Logo_4.LocalScript 
	local script = Instance.new('LocalScript', Logo_4)

	while wait() do
		script.Parent.Rotation = script.Parent.Rotation + 15
		if script.Parent.Rotation == 360 then
			script.Parent.Rotation = 0
		end
	end
end
coroutine.wrap(XYDA_fake_script)()
local function ZVPLZ_fake_script() -- _1_4.Script 
	local script = Instance.new('Script', _1_4)

	script.Parent.MouseButton1Down:Connect(function()
		loadstring(game:HttpGet(("https://raw.githubusercontent.com/Denverrz/scripts/master/Invisible_Fling_Revamp.lua"),true))()
	end)
end
coroutine.wrap(ZVPLZ_fake_script)()
local function KNOU_fake_script() -- _2_4.Script 
	local script = Instance.new('Script', _2_4)

	script.Parent.MouseButton1Down:Connect(function()
		loadstring(game:HttpGet("https://pastebinp.com/raw/yBDULxqU", true))()
	end)
end
coroutine.wrap(KNOU_fake_script)()
local function AMCVWH_fake_script() -- _3_4.Script 
	local script = Instance.new('Script', _3_4)

	script.Parent.MouseButton1Down:Connect(function()
		loadstring(game:HttpGet("https://pastebinp.com/raw/Rx4Qqicd", true))()
	end)
end
coroutine.wrap(AMCVWH_fake_script)()
local function URAAMMO_fake_script() -- _4_4.Script 
	local script = Instance.new('Script', _4_4)

	script.Parent.MouseButton1Down:Connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/NotZyrex/Scripts/master/Zyrex-Chat-Bypass.lua"))();
	end)
end
coroutine.wrap(URAAMMO_fake_script)()
local function ABIWWH_fake_script() -- _5_3.Script 
	local script = Instance.new('Script', _5_3)

	script.Parent.MouseButton1Down:Connect(function()
	loadstring(game:HttpGet("https://pastebinp.com/raw/bk5J4cyc"))();
	end)
end
coroutine.wrap(ABIWWH_fake_script)()
