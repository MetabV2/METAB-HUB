
local METABHUB = Instance.new("ScreenGui")
local METABIMAGE = Instance.new("ImageLabel")
local CloseButton = Instance.new("ImageButton")
local UIGradient = Instance.new("UIGradient")
local UIAspectRatioConstraint = Instance.new("UIAspectRatioConstraint")
local METAB6 = Instance.new("ImageButton")
local LineBottom = Instance.new("Frame")
local LineTop = Instance.new("Frame")
local Button8 = Instance.new("ImageButton")
local BtnText = Instance.new("TextLabel")
local UICorner = Instance.new("UICorner")
local METAB5 = Instance.new("ImageButton")
local LineBottom_2 = Instance.new("Frame")
local LineTop_2 = Instance.new("Frame")
local Button8_2 = Instance.new("ImageButton")
local BtnText_2 = Instance.new("TextLabel")
local UICorner_2 = Instance.new("UICorner")
local UICorner_3 = Instance.new("UICorner")
local METAB4 = Instance.new("ImageButton")
local LineBottom_3 = Instance.new("Frame")
local LineTop_3 = Instance.new("Frame")
local Button8_3 = Instance.new("ImageButton")
local BtnText_3 = Instance.new("TextLabel")
local UICorner_4 = Instance.new("UICorner")
local METAB3 = Instance.new("ImageButton")
local LineBottom_4 = Instance.new("Frame")
local LineTop_4 = Instance.new("Frame")
local Button8_4 = Instance.new("ImageButton")
local BtnText_4 = Instance.new("TextLabel")
local UICorner_5 = Instance.new("UICorner")
local METAB2 = Instance.new("ImageButton")
local LineBottom_5 = Instance.new("Frame")
local LineTop_5 = Instance.new("Frame")
local Button8_5 = Instance.new("ImageButton")
local BtnText_5 = Instance.new("TextLabel")
local UICorner_6 = Instance.new("UICorner")
local METAB1 = Instance.new("ImageButton")
local LineBottom_6 = Instance.new("Frame")
local LineTop_6 = Instance.new("Frame")
local Button8_6 = Instance.new("ImageButton")
local BtnText_6 = Instance.new("TextLabel")
local UICorner_7 = Instance.new("UICorner")
local METABHUB_2 = Instance.new("ImageButton")
local UIAspectRatioConstraint_2 = Instance.new("UIAspectRatioConstraint")
local UIGradient_2 = Instance.new("UIGradient")
local BtnText_7 = Instance.new("TextLabel")

--Properties:

METABHUB.Name = "METAB HUB"
METABHUB.Parent = game.CoreGui
METABHUB.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

METABIMAGE.Name = "METABIMAGE"
METABIMAGE.Parent = METABHUB
METABIMAGE.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
METABIMAGE.BackgroundTransparency = 1.000
METABIMAGE.Position = UDim2.new(0.26924789, 0, 0.205787718, 0)
METABIMAGE.Size = UDim2.new(0, 630, 0, 365)
METABIMAGE.Image = "http://www.roblox.com/asset/?id=7788975168"

CloseButton.Name = "CloseButton"
CloseButton.Parent = METABIMAGE
CloseButton.AnchorPoint = Vector2.new(0.5, 0.5)
CloseButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
CloseButton.BackgroundTransparency = 1.000
CloseButton.BorderSizePixel = 0
CloseButton.Position = UDim2.new(0.499550551, 0, 0.208712518, 0)
CloseButton.Size = UDim2.new(0.134232357, 0, 0.118330203, 0)
CloseButton.Image = "http://www.roblox.com/asset/?id=7400386959"

UIGradient.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(255, 255, 255)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(255, 255, 255)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(0, 136, 255))}
UIGradient.Offset = Vector2.new(-0.349999994, 0)
UIGradient.Rotation = -135
UIGradient.Parent = CloseButton

UIAspectRatioConstraint.Parent = CloseButton
UIAspectRatioConstraint.AspectRatio = 2.000

METAB6.Name = "METAB 6"
METAB6.Parent = METABIMAGE
METAB6.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
METAB6.BackgroundTransparency = 1.000
METAB6.Position = UDim2.new(0.64920634, 0, 0.572096884, 0)
METAB6.Size = UDim2.new(0, 123, 0, 82)
METAB6.Image = "http://www.roblox.com/asset/?id=7795937099"
METAB6.ImageTransparency = 1.000

LineBottom.Name = "LineBottom"
LineBottom.Parent = METAB6
LineBottom.AnchorPoint = Vector2.new(0.5, 0.5)
LineBottom.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
LineBottom.BackgroundTransparency = 1.000
LineBottom.BorderSizePixel = 0
LineBottom.Position = UDim2.new(0.499500483, 0, 0.999000013, 0)
LineBottom.Size = UDim2.new(0, 0, 0, 1)

LineTop.Name = "LineTop"
LineTop.Parent = METAB6
LineTop.AnchorPoint = Vector2.new(0.5, 0.5)
LineTop.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
LineTop.BackgroundTransparency = 1.000
LineTop.BorderSizePixel = 0
LineTop.Position = UDim2.new(0.499500483, 0, 0.00100000005, 0)
LineTop.Size = UDim2.new(0, 0, 0, 1)

Button8.Name = "Button8"
Button8.Parent = METAB6
Button8.AnchorPoint = Vector2.new(0.5, 0.5)
Button8.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Button8.BackgroundTransparency = 1.000
Button8.Position = UDim2.new(0.483739853, 0, 0.501469254, 0)
Button8.Size = UDim2.new(0, 122, 0, 83)
Button8.Image = "http://www.roblox.com/asset/?id=7796648161"
Button8.SliceCenter = Rect.new(4, 4, 252, 252)

BtnText.Name = "BtnText"
BtnText.Parent = Button8
BtnText.AnchorPoint = Vector2.new(0.5, 0.5)
BtnText.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
BtnText.BackgroundTransparency = 1.000
BtnText.BorderSizePixel = 0
BtnText.Position = UDim2.new(0.501231551, 0, 0.5, 0)
BtnText.Size = UDim2.new(0.989716768, -5, 0.917372882, -5)
BtnText.Font = Enum.Font.GothamBlack
BtnText.Text = ""
BtnText.TextColor3 = Color3.fromRGB(255, 255, 255)
BtnText.TextScaled = true
BtnText.TextSize = 14.000
BtnText.TextTransparency = 1.000
BtnText.TextWrapped = true

UICorner.CornerRadius = UDim.new(0, 5)
UICorner.Parent = Button8

METAB5.Name = "METAB 5"
METAB5.Parent = METABIMAGE
METAB5.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
METAB5.BackgroundTransparency = 1.000
METAB5.Position = UDim2.new(0.403174639, 0, 0.571987212, 0)
METAB5.Size = UDim2.new(0, 122, 0, 83)
METAB5.Image = "http://www.roblox.com/asset/?id=7795896413"
METAB5.ImageTransparency = 1.000

LineBottom_2.Name = "LineBottom"
LineBottom_2.Parent = METAB5
LineBottom_2.AnchorPoint = Vector2.new(0.5, 0.5)
LineBottom_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
LineBottom_2.BackgroundTransparency = 1.000
LineBottom_2.BorderSizePixel = 0
LineBottom_2.Position = UDim2.new(0.499500483, 0, 0.999000013, 0)
LineBottom_2.Size = UDim2.new(0, 0, 0, 1)

LineTop_2.Name = "LineTop"
LineTop_2.Parent = METAB5
LineTop_2.AnchorPoint = Vector2.new(0.5, 0.5)
LineTop_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
LineTop_2.BackgroundTransparency = 1.000
LineTop_2.BorderSizePixel = 0
LineTop_2.Position = UDim2.new(0.499500483, 0, 0.00100000005, 0)
LineTop_2.Size = UDim2.new(0, 0, 0, 1)

Button8_2.Name = "Button8"
Button8_2.Parent = METAB5
Button8_2.AnchorPoint = Vector2.new(0.5, 0.5)
Button8_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Button8_2.BackgroundTransparency = 1.000
Button8_2.Position = UDim2.new(0.491803229, 0, 0.48866266, 0)
Button8_2.Size = UDim2.new(0, 122, 0, 83)
Button8_2.Image = "http://www.roblox.com/asset/?id=7796593144"
Button8_2.SliceCenter = Rect.new(4, 4, 252, 252)

BtnText_2.Name = "BtnText"
BtnText_2.Parent = Button8_2
BtnText_2.AnchorPoint = Vector2.new(0.5, 0.5)
BtnText_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
BtnText_2.BackgroundTransparency = 1.000
BtnText_2.BorderSizePixel = 0
BtnText_2.Position = UDim2.new(0.501231551, 0, 0.5, 0)
BtnText_2.Size = UDim2.new(0.989716768, -5, 0.917372882, -5)
BtnText_2.Font = Enum.Font.GothamBlack
BtnText_2.Text = ""
BtnText_2.TextColor3 = Color3.fromRGB(255, 255, 255)
BtnText_2.TextScaled = true
BtnText_2.TextSize = 14.000
BtnText_2.TextTransparency = 1.000
BtnText_2.TextWrapped = true

UICorner_2.CornerRadius = UDim.new(0, 5)
UICorner_2.Parent = Button8_2

UICorner_3.CornerRadius = UDim.new(0, 5)
UICorner_3.Parent = UICorner_2

METAB4.Name = "METAB 4"
METAB4.Parent = METABIMAGE
METAB4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
METAB4.BackgroundTransparency = 1.000
METAB4.Position = UDim2.new(0.152380958, 0, 0.571987271, 0)
METAB4.Size = UDim2.new(0, 122, 0, 83)
METAB4.Image = "http://www.roblox.com/asset/?id=7795873320"
METAB4.ImageTransparency = 1.000

LineBottom_3.Name = "LineBottom"
LineBottom_3.Parent = METAB4
LineBottom_3.AnchorPoint = Vector2.new(0.5, 0.5)
LineBottom_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
LineBottom_3.BackgroundTransparency = 1.000
LineBottom_3.BorderSizePixel = 0
LineBottom_3.Position = UDim2.new(0.499500483, 0, 0.999000013, 0)
LineBottom_3.Size = UDim2.new(0, 0, 0, 1)

LineTop_3.Name = "LineTop"
LineTop_3.Parent = METAB4
LineTop_3.AnchorPoint = Vector2.new(0.5, 0.5)
LineTop_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
LineTop_3.BackgroundTransparency = 1.000
LineTop_3.BorderSizePixel = 0
LineTop_3.Position = UDim2.new(0.499500483, 0, 0.00100000005, 0)
LineTop_3.Size = UDim2.new(0, 0, 0, 1)

Button8_3.Name = "Button8"
Button8_3.Parent = METAB4
Button8_3.AnchorPoint = Vector2.new(0.5, 0.5)
Button8_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Button8_3.BackgroundTransparency = 1.000
Button8_3.Position = UDim2.new(0.5, 0, 0.500481904, 0)
Button8_3.Size = UDim2.new(0, 122, 0, 83)
Button8_3.Image = "http://www.roblox.com/asset/?id=7796814571"
Button8_3.SliceCenter = Rect.new(4, 4, 252, 252)

BtnText_3.Name = "BtnText"
BtnText_3.Parent = Button8_3
BtnText_3.AnchorPoint = Vector2.new(0.5, 0.5)
BtnText_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
BtnText_3.BackgroundTransparency = 1.000
BtnText_3.BorderSizePixel = 0
BtnText_3.Position = UDim2.new(0.501231551, 0, 0.5, 0)
BtnText_3.Size = UDim2.new(0.989716768, -5, 0.917372882, -5)
BtnText_3.Font = Enum.Font.GothamBlack
BtnText_3.Text = ""
BtnText_3.TextColor3 = Color3.fromRGB(255, 255, 255)
BtnText_3.TextScaled = true
BtnText_3.TextSize = 14.000
BtnText_3.TextTransparency = 1.000
BtnText_3.TextWrapped = true

UICorner_4.CornerRadius = UDim.new(0, 5)
UICorner_4.Parent = Button8_3

METAB3.Name = "METAB 3"
METAB3.Parent = METABIMAGE
METAB3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
METAB3.BackgroundTransparency = 1.000
METAB3.Position = UDim2.new(0.64920634, 0, 0.267877638, 0)
METAB3.Size = UDim2.new(0, 122, 0, 83)
METAB3.Image = "http://www.roblox.com/asset/?id=7795870859"
METAB3.ImageTransparency = 1.000

LineBottom_4.Name = "LineBottom"
LineBottom_4.Parent = METAB3
LineBottom_4.AnchorPoint = Vector2.new(0.5, 0.5)
LineBottom_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
LineBottom_4.BackgroundTransparency = 1.000
LineBottom_4.BorderSizePixel = 0
LineBottom_4.Position = UDim2.new(0.499500483, 0, 0.999000013, 0)
LineBottom_4.Size = UDim2.new(0, 0, 0, 1)

LineTop_4.Name = "LineTop"
LineTop_4.Parent = METAB3
LineTop_4.AnchorPoint = Vector2.new(0.5, 0.5)
LineTop_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
LineTop_4.BackgroundTransparency = 1.000
LineTop_4.BorderSizePixel = 0
LineTop_4.Position = UDim2.new(0.499500483, 0, 0.00100000005, 0)
LineTop_4.Size = UDim2.new(0, 0, 0, 1)

Button8_4.Name = "Button8"
Button8_4.Parent = METAB3
Button8_4.AnchorPoint = Vector2.new(0.5, 0.5)
Button8_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Button8_4.BackgroundTransparency = 1.000
Button8_4.Position = UDim2.new(0.491803259, 0, 0.5, 0)
Button8_4.Size = UDim2.new(0, 122, 0, 83)
Button8_4.Image = "http://www.roblox.com/asset/?id=7796574950"
Button8_4.SliceCenter = Rect.new(4, 4, 252, 252)

BtnText_4.Name = "BtnText"
BtnText_4.Parent = Button8_4
BtnText_4.AnchorPoint = Vector2.new(0.5, 0.5)
BtnText_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
BtnText_4.BackgroundTransparency = 1.000
BtnText_4.BorderSizePixel = 0
BtnText_4.Position = UDim2.new(0.501231551, 0, 0.5, 0)
BtnText_4.Size = UDim2.new(0.989716768, -5, 0.917372882, -5)
BtnText_4.Font = Enum.Font.GothamBlack
BtnText_4.Text = ""
BtnText_4.TextColor3 = Color3.fromRGB(255, 255, 255)
BtnText_4.TextScaled = true
BtnText_4.TextSize = 14.000
BtnText_4.TextTransparency = 1.000
BtnText_4.TextWrapped = true

UICorner_5.CornerRadius = UDim.new(0, 5)
UICorner_5.Parent = Button8_4

METAB2.Name = "METAB 2"
METAB2.Parent = METABIMAGE
METAB2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
METAB2.BackgroundTransparency = 1.000
METAB2.Position = UDim2.new(0.403174639, 0, 0.267877638, 0)
METAB2.Size = UDim2.new(0, 122, 0, 83)
METAB2.Image = "http://www.roblox.com/asset/?id=7789016141"
METAB2.ImageTransparency = 1.000

LineBottom_5.Name = "LineBottom"
LineBottom_5.Parent = METAB2
LineBottom_5.AnchorPoint = Vector2.new(0.5, 0.5)
LineBottom_5.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
LineBottom_5.BackgroundTransparency = 1.000
LineBottom_5.BorderSizePixel = 0
LineBottom_5.Position = UDim2.new(0.499500483, 0, 0.999000013, 0)
LineBottom_5.Size = UDim2.new(0, 0, 0, 1)

LineTop_5.Name = "LineTop"
LineTop_5.Parent = METAB2
LineTop_5.AnchorPoint = Vector2.new(0.5, 0.5)
LineTop_5.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
LineTop_5.BackgroundTransparency = 1.000
LineTop_5.BorderSizePixel = 0
LineTop_5.Position = UDim2.new(0.499500483, 0, 0.00100000005, 0)
LineTop_5.Size = UDim2.new(0, 0, 0, 1)

Button8_5.Name = "Button8"
Button8_5.Parent = METAB2
Button8_5.AnchorPoint = Vector2.new(0.5, 0.5)
Button8_5.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Button8_5.BackgroundTransparency = 1.000
Button8_5.Position = UDim2.new(0.5, 0, 0.5, 0)
Button8_5.Size = UDim2.new(0, 122, 0, 83)
Button8_5.Image = "http://www.roblox.com/asset/?id=7796601656"
Button8_5.SliceCenter = Rect.new(4, 4, 252, 252)

BtnText_5.Name = "BtnText"
BtnText_5.Parent = Button8_5
BtnText_5.AnchorPoint = Vector2.new(0.5, 0.5)
BtnText_5.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
BtnText_5.BackgroundTransparency = 1.000
BtnText_5.BorderSizePixel = 0
BtnText_5.Position = UDim2.new(0.501231551, 0, 0.5, 0)
BtnText_5.Size = UDim2.new(0.989716768, -5, 0.917372882, -5)
BtnText_5.Font = Enum.Font.GothamBlack
BtnText_5.Text = ""
BtnText_5.TextColor3 = Color3.fromRGB(255, 255, 255)
BtnText_5.TextScaled = true
BtnText_5.TextSize = 14.000
BtnText_5.TextTransparency = 1.000
BtnText_5.TextWrapped = true

UICorner_6.CornerRadius = UDim.new(0, 5)
UICorner_6.Parent = Button8_5

METAB1.Name = "METAB 1"
METAB1.Parent = METABIMAGE
METAB1.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
METAB1.BackgroundTransparency = 1.000
METAB1.Position = UDim2.new(0.152380958, 0, 0.266634673, 0)
METAB1.Size = UDim2.new(0, 122, 0, 83)
METAB1.Image = "http://www.roblox.com/asset/?id=7796442266"
METAB1.ImageTransparency = 1.000

LineBottom_6.Name = "LineBottom"
LineBottom_6.Parent = METAB1
LineBottom_6.AnchorPoint = Vector2.new(0.5, 0.5)
LineBottom_6.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
LineBottom_6.BackgroundTransparency = 1.000
LineBottom_6.BorderSizePixel = 0
LineBottom_6.Position = UDim2.new(0.499500483, 0, 0.999000013, 0)
LineBottom_6.Size = UDim2.new(0, 0, 0, 1)

LineTop_6.Name = "LineTop"
LineTop_6.Parent = METAB1
LineTop_6.AnchorPoint = Vector2.new(0.5, 0.5)
LineTop_6.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
LineTop_6.BackgroundTransparency = 1.000
LineTop_6.BorderSizePixel = 0
LineTop_6.Position = UDim2.new(0.499500483, 0, 0.00100000005, 0)
LineTop_6.Size = UDim2.new(0, 0, 0, 1)

Button8_6.Name = "Button8"
Button8_6.Parent = METAB1
Button8_6.AnchorPoint = Vector2.new(0.5, 0.5)
Button8_6.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Button8_6.BackgroundTransparency = 1.000
Button8_6.Position = UDim2.new(0.5, 0, 0.5, 0)
Button8_6.Size = UDim2.new(0, 122, 0, 83)
Button8_6.Image = "http://www.roblox.com/asset/?id=7796442266"
Button8_6.SliceCenter = Rect.new(4, 4, 252, 252)

BtnText_6.Name = "BtnText"
BtnText_6.Parent = Button8_6
BtnText_6.AnchorPoint = Vector2.new(0.5, 0.5)
BtnText_6.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
BtnText_6.BackgroundTransparency = 1.000
BtnText_6.BorderSizePixel = 0
BtnText_6.Position = UDim2.new(0.501231551, 0, 0.5, 0)
BtnText_6.Size = UDim2.new(0.989716768, -5, 0.917372882, -5)
BtnText_6.Font = Enum.Font.GothamBlack
BtnText_6.Text = ""
BtnText_6.TextColor3 = Color3.fromRGB(255, 255, 255)
BtnText_6.TextScaled = true
BtnText_6.TextSize = 14.000
BtnText_6.TextTransparency = 1.000
BtnText_6.TextWrapped = true

UICorner_7.CornerRadius = UDim.new(0, 5)
UICorner_7.Parent = Button8_6

METABHUB_2.Name = "METAB HUB"
METABHUB_2.Parent = METABHUB
METABHUB_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
METABHUB_2.BackgroundTransparency = 1.000
METABHUB_2.Position = UDim2.new(0.461317271, 0, 0.0225080401, 0)
METABHUB_2.Size = UDim2.new(0, 125, 0, 34)
METABHUB_2.Image = "http://www.roblox.com/asset/?id=7803981258"
METABHUB_2.ScaleType = Enum.ScaleType.Fit

UIAspectRatioConstraint_2.Parent = METABHUB_2
UIAspectRatioConstraint_2.AspectRatio = 3.042

UIGradient_2.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(255, 255, 255)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(255, 255, 255)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(0, 136, 255))}
UIGradient_2.Offset = Vector2.new(-0.349999994, 0)
UIGradient_2.Rotation = -135
UIGradient_2.Parent = METABHUB_2

BtnText_7.Name = "BtnText"
BtnText_7.Parent = METABHUB_2
BtnText_7.AnchorPoint = Vector2.new(0.5, 0.5)
BtnText_7.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
BtnText_7.BackgroundTransparency = 1.000
BtnText_7.BorderSizePixel = 0
BtnText_7.Position = UDim2.new(0.501231551, 0, 0.5, 0)
BtnText_7.Size = UDim2.new(0.989716768, -5, 0.917372882, -5)
BtnText_7.Visible = false
BtnText_7.Font = Enum.Font.GothamBlack
BtnText_7.Text = "CLICK!"
BtnText_7.TextColor3 = Color3.fromRGB(255, 255, 255)
BtnText_7.TextScaled = true
BtnText_7.TextSize = 14.000
BtnText_7.TextWrapped = true

-- Scripts:

local function WLKTW_fake_script() -- METABIMAGE.LocalScript 
	local script = Instance.new('LocalScript', METABIMAGE)

	
	local UIS = game:GetService('UserInputService')
	
	local frame = script.Parent
	
	
	
	local dragToggle = nil
	
	local dragSpeed = 0.25
	
	local dragStart = nil
	
	local startPos = nil
	
	
	
	local function updateInput(input)
	
		local delta = input.Position - dragStart
	
		local position = UDim2.new(startPos.X.Scale, startPos.X.Offset + delta.X,
	
			startPos.Y.Scale, startPos.Y.Offset + delta.Y)
	
		game:GetService('TweenService'):Create(frame, TweenInfo.new(dragSpeed), {Position = position}):Play()
	
	end
	
	
	
	frame.InputBegan:Connect(function(input)
	
		if (input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch) then 
	
			dragToggle = true
	
			dragStart = input.Position
	
			startPos = frame.Position
	
			input.Changed:Connect(function()
	
				if input.UserInputState == Enum.UserInputState.End then
	
					dragToggle = false
	
				end
	
			end)
	
		end
	
	end)
	
	
	
	UIS.InputChanged:Connect(function(input)
	
		if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
	
			if dragToggle then
	
				updateInput(input)
	
			end
	
		end
	
	end)
	
	
	
	
end
coroutine.wrap(WLKTW_fake_script)()
local function PPZBD_fake_script() -- METABIMAGE.LocalScript 
	local script = Instance.new('LocalScript', METABIMAGE)

	while true do
		script.Parent.BackgroundColor3 = Color3.new (255, 176, 0)
		wait(.7)
		script.Parent.BackgroundColor3 = Color3.new (0, 255, 0)
		wait(.7)
		script.Parent.BackgroundColor3 = Color3.new (255, 0, 0)
		wait(.7)
		script.Parent.BackgroundColor3 = Color3.new (170, 85, 0)
		wait(.7)
		script.Parent.BackgroundColor3 = Color3.new (106, 57, 9)
		wait(.7)
		script.Parent.BackgroundColor3 = Color3.new (0, 16, 176)
		wait(.7)
	end
end
coroutine.wrap(PPZBD_fake_script)()
local function XKJUW_fake_script() -- CloseButton.LocalScript 
	local script = Instance.new('LocalScript', CloseButton)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.Visible = false
	end)
end
coroutine.wrap(XKJUW_fake_script)()
local function PEMPBNH_fake_script() -- CloseButton.ANIME 
	local script = Instance.new('LocalScript', CloseButton)

	local btn = script.Parent
	local uiGradient = btn:WaitForChild("UIGradient")
	
	local isHovering = false
	
	local tweenService = game:GetService("TweenService")
	local tweenInfo = TweenInfo.new(0.4, Enum.EasingStyle.Quint, Enum.EasingDirection.InOut)
	
	local gradientRestoreTween = tweenService:Create(uiGradient, tweenInfo, {Offset = Vector2.new(-0.35, 0)})
	local gradientAddTween = tweenService:Create(uiGradient, tweenInfo, {Offset = Vector2.new(1, 0)})
	
	
	btn.MouseEnter:Connect(function()
		
		isHovering = true
		
		gradientAddTween:Play()
	end)
	
	btn.MouseLeave:Connect(function()
		
		isHovering = false
		
		gradientRestoreTween:Play()
	end)
	
	btn.MouseButton1Down:Connect(function()
		
		gradientRestoreTween:Play()
	end)
	
	btn.MouseButton1Up:Connect(function()
		
		if not isHovering then
			gradientRestoreTween:Play()
		else
			gradientAddTween:Play()
		end
	end)
end
coroutine.wrap(PEMPBNH_fake_script)()
local function GIKDV_fake_script() -- Button8.Button8Script 
	local script = Instance.new('LocalScript', Button8)

	local btn = script.Parent
	local btnText = btn:WaitForChild("BtnText")
	
	local btnHoverArea = btn.Parent
	
	local lineTop = btnHoverArea:WaitForChild("LineTop")
	local lineBottom = btnHoverArea:WaitForChild("LineBottom")
	
	local isHovering = false
	
	local tweenService = game:GetService("TweenService")
	local tweenInfo = TweenInfo.new(0.3, Enum.EasingStyle.Quint, Enum.EasingDirection.InOut)
	
	local btnSizeInTween = tweenService:Create(btn, tweenInfo, {Size = UDim2.new(0.001, 0, 1, 0), ImageTransparency = 1})
	local btnSizeOutTween = tweenService:Create(btn, tweenInfo, {Size = UDim2.new(1, 0, 1, 0), ImageTransparency = 0})
	
	local textTransparentTween = tweenService:Create(btnText, tweenInfo, {TextTransparency = 1}) 
	local textOpaqueTween = tweenService:Create(btnText, tweenInfo, {TextTransparency = 0})
	
	local bottomLineTweenOut = tweenService:Create(lineBottom, tweenInfo, {Size = UDim2.new(1, 0, 0, 1), BackgroundTransparency = 0})
	local bottomLineTweenIn = tweenService:Create(lineBottom, tweenInfo, {Size = UDim2.new(0, 0, 0, 1), BackgroundTransparency = 1})
	local topLineTweenOut = tweenService:Create(lineTop, tweenInfo, {Size = UDim2.new(1, 0, 0, 1), BackgroundTransparency = 0})
	local topLineTweenIn = tweenService:Create(lineTop, tweenInfo, {Size = UDim2.new(0, 0, 0, 1), BackgroundTransparency = 1})
	
	
	local function hoverTween()
		
		btnSizeOutTween:Cancel()
		textOpaqueTween:Cancel()
		bottomLineTweenIn:Cancel()
		topLineTweenIn:Cancel()
		
		btnSizeInTween:Play()
		textTransparentTween:Play()
		bottomLineTweenOut:Play()
		topLineTweenOut:Play()
	end
	
	local function hoverTweenReverse()
	
		btnSizeInTween:Cancel()
		textTransparentTween:Cancel()
		bottomLineTweenOut:Cancel()
		topLineTweenOut:Cancel()
		
		btnSizeOutTween:Play()
		textOpaqueTween:Play()
		bottomLineTweenIn:Play()
		topLineTweenIn:Play()
	end
	
	
	btnHoverArea.MouseEnter:Connect(function()
		
		isHovering = true
		
		hoverTween()
	end)
	
	btnHoverArea.MouseLeave:Connect(function()
		
		isHovering = false
		
		hoverTweenReverse()
	end)
	
	btnHoverArea.MouseButton1Down:Connect(function()
		
		hoverTweenReverse()
	end)
	
	btnHoverArea.MouseButton1Up:Connect(function()
		
		if not isHovering then
			hoverTweenReverse()
		else
			hoverTween()
		end
	end)
end
coroutine.wrap(GIKDV_fake_script)()
local function WNHFPII_fake_script() -- Button8.LocalScript 
	local script = Instance.new('LocalScript', Button8)

	
	script.Parent.MouseButton1Down:connect(function()
		if game.PlaceId == 7601506770 then
			loadstring(game:HttpGet("https://raw.githubusercontent.com/NocturneMoDz/Get-Big-Simulator/main/SCRIPT",true))();
		end
	end)
end
coroutine.wrap(WNHFPII_fake_script)()
local function FLTE_fake_script() -- Button8_2.Button8Script 
	local script = Instance.new('LocalScript', Button8_2)

	local btn = script.Parent
	local btnText = btn:WaitForChild("BtnText")
	
	local btnHoverArea = btn.Parent
	
	local lineTop = btnHoverArea:WaitForChild("LineTop")
	local lineBottom = btnHoverArea:WaitForChild("LineBottom")
	
	local isHovering = false
	
	local tweenService = game:GetService("TweenService")
	local tweenInfo = TweenInfo.new(0.3, Enum.EasingStyle.Quint, Enum.EasingDirection.InOut)
	
	local btnSizeInTween = tweenService:Create(btn, tweenInfo, {Size = UDim2.new(0.001, 0, 1, 0), ImageTransparency = 1})
	local btnSizeOutTween = tweenService:Create(btn, tweenInfo, {Size = UDim2.new(1, 0, 1, 0), ImageTransparency = 0})
	
	local textTransparentTween = tweenService:Create(btnText, tweenInfo, {TextTransparency = 1}) 
	local textOpaqueTween = tweenService:Create(btnText, tweenInfo, {TextTransparency = 0})
	
	local bottomLineTweenOut = tweenService:Create(lineBottom, tweenInfo, {Size = UDim2.new(1, 0, 0, 1), BackgroundTransparency = 0})
	local bottomLineTweenIn = tweenService:Create(lineBottom, tweenInfo, {Size = UDim2.new(0, 0, 0, 1), BackgroundTransparency = 1})
	local topLineTweenOut = tweenService:Create(lineTop, tweenInfo, {Size = UDim2.new(1, 0, 0, 1), BackgroundTransparency = 0})
	local topLineTweenIn = tweenService:Create(lineTop, tweenInfo, {Size = UDim2.new(0, 0, 0, 1), BackgroundTransparency = 1})
	
	
	local function hoverTween()
		
		btnSizeOutTween:Cancel()
		textOpaqueTween:Cancel()
		bottomLineTweenIn:Cancel()
		topLineTweenIn:Cancel()
		
		btnSizeInTween:Play()
		textTransparentTween:Play()
		bottomLineTweenOut:Play()
		topLineTweenOut:Play()
	end
	
	local function hoverTweenReverse()
	
		btnSizeInTween:Cancel()
		textTransparentTween:Cancel()
		bottomLineTweenOut:Cancel()
		topLineTweenOut:Cancel()
		
		btnSizeOutTween:Play()
		textOpaqueTween:Play()
		bottomLineTweenIn:Play()
		topLineTweenIn:Play()
	end
	
	
	btnHoverArea.MouseEnter:Connect(function()
		
		isHovering = true
		
		hoverTween()
	end)
	
	btnHoverArea.MouseLeave:Connect(function()
		
		isHovering = false
		
		hoverTweenReverse()
	end)
	
	btnHoverArea.MouseButton1Down:Connect(function()
		
		hoverTweenReverse()
	end)
	
	btnHoverArea.MouseButton1Up:Connect(function()
		
		if not isHovering then
			hoverTweenReverse()
		else
			hoverTween()
		end
	end)
end
coroutine.wrap(FLTE_fake_script)()
local function HJCNB_fake_script() -- Button8_2.LocalScript 
	local script = Instance.new('LocalScript', Button8_2)

	
	script.Parent.MouseButton1Down:connect(function()
		if game.PlaceId == 6202744791 then
		loadstring(game:HttpGet("https://raw.githubusercontent.com/NocturneMoDz/BayView-RP/main/SCRIPT",true))();
		end
	end)
end
coroutine.wrap(HJCNB_fake_script)()
local function YOLAG_fake_script() -- Button8_3.Button8Script 
	local script = Instance.new('LocalScript', Button8_3)

	local btn = script.Parent
	local btnText = btn:WaitForChild("BtnText")
	
	local btnHoverArea = btn.Parent
	
	local lineTop = btnHoverArea:WaitForChild("LineTop")
	local lineBottom = btnHoverArea:WaitForChild("LineBottom")
	
	local isHovering = false
	
	local tweenService = game:GetService("TweenService")
	local tweenInfo = TweenInfo.new(0.3, Enum.EasingStyle.Quint, Enum.EasingDirection.InOut)
	
	local btnSizeInTween = tweenService:Create(btn, tweenInfo, {Size = UDim2.new(0.001, 0, 1, 0), ImageTransparency = 1})
	local btnSizeOutTween = tweenService:Create(btn, tweenInfo, {Size = UDim2.new(1, 0, 1, 0), ImageTransparency = 0})
	
	local textTransparentTween = tweenService:Create(btnText, tweenInfo, {TextTransparency = 1}) 
	local textOpaqueTween = tweenService:Create(btnText, tweenInfo, {TextTransparency = 0})
	
	local bottomLineTweenOut = tweenService:Create(lineBottom, tweenInfo, {Size = UDim2.new(1, 0, 0, 1), BackgroundTransparency = 0})
	local bottomLineTweenIn = tweenService:Create(lineBottom, tweenInfo, {Size = UDim2.new(0, 0, 0, 1), BackgroundTransparency = 1})
	local topLineTweenOut = tweenService:Create(lineTop, tweenInfo, {Size = UDim2.new(1, 0, 0, 1), BackgroundTransparency = 0})
	local topLineTweenIn = tweenService:Create(lineTop, tweenInfo, {Size = UDim2.new(0, 0, 0, 1), BackgroundTransparency = 1})
	
	
	local function hoverTween()
		
		btnSizeOutTween:Cancel()
		textOpaqueTween:Cancel()
		bottomLineTweenIn:Cancel()
		topLineTweenIn:Cancel()
		
		btnSizeInTween:Play()
		textTransparentTween:Play()
		bottomLineTweenOut:Play()
		topLineTweenOut:Play()
	end
	
	local function hoverTweenReverse()
	
		btnSizeInTween:Cancel()
		textTransparentTween:Cancel()
		bottomLineTweenOut:Cancel()
		topLineTweenOut:Cancel()
		
		btnSizeOutTween:Play()
		textOpaqueTween:Play()
		bottomLineTweenIn:Play()
		topLineTweenIn:Play()
	end
	
	
	btnHoverArea.MouseEnter:Connect(function()
		
		isHovering = true
		
		hoverTween()
	end)
	
	btnHoverArea.MouseLeave:Connect(function()
		
		isHovering = false
		
		hoverTweenReverse()
	end)
	
	btnHoverArea.MouseButton1Down:Connect(function()
		
		hoverTweenReverse()
	end)
	
	btnHoverArea.MouseButton1Up:Connect(function()
		
		if not isHovering then
			hoverTweenReverse()
		else
			hoverTween()
		end
	end)
end
coroutine.wrap(YOLAG_fake_script)()
local function ZAEM_fake_script() -- Button8_3.LocalScript 
	local script = Instance.new('LocalScript', Button8_3)

	script.Parent.MouseButton1Down:connect(function()
		
		if game.PlaceId == 5987989452 then
		loadstring(game:HttpGet("https://raw.githubusercontent.com/NocturneMoDz/monke-game-/main/Script",true))();
		end
	end)
end
coroutine.wrap(ZAEM_fake_script)()
local function VKOMMY_fake_script() -- Button8_4.Button8Script 
	local script = Instance.new('LocalScript', Button8_4)

	local btn = script.Parent
	local btnText = btn:WaitForChild("BtnText")
	
	local btnHoverArea = btn.Parent
	
	local lineTop = btnHoverArea:WaitForChild("LineTop")
	local lineBottom = btnHoverArea:WaitForChild("LineBottom")
	
	local isHovering = false
	
	local tweenService = game:GetService("TweenService")
	local tweenInfo = TweenInfo.new(0.3, Enum.EasingStyle.Quint, Enum.EasingDirection.InOut)
	
	local btnSizeInTween = tweenService:Create(btn, tweenInfo, {Size = UDim2.new(0.001, 0, 1, 0), ImageTransparency = 1})
	local btnSizeOutTween = tweenService:Create(btn, tweenInfo, {Size = UDim2.new(1, 0, 1, 0), ImageTransparency = 0})
	
	local textTransparentTween = tweenService:Create(btnText, tweenInfo, {TextTransparency = 1}) 
	local textOpaqueTween = tweenService:Create(btnText, tweenInfo, {TextTransparency = 0})
	
	local bottomLineTweenOut = tweenService:Create(lineBottom, tweenInfo, {Size = UDim2.new(1, 0, 0, 1), BackgroundTransparency = 0})
	local bottomLineTweenIn = tweenService:Create(lineBottom, tweenInfo, {Size = UDim2.new(0, 0, 0, 1), BackgroundTransparency = 1})
	local topLineTweenOut = tweenService:Create(lineTop, tweenInfo, {Size = UDim2.new(1, 0, 0, 1), BackgroundTransparency = 0})
	local topLineTweenIn = tweenService:Create(lineTop, tweenInfo, {Size = UDim2.new(0, 0, 0, 1), BackgroundTransparency = 1})
	
	
	local function hoverTween()
		
		btnSizeOutTween:Cancel()
		textOpaqueTween:Cancel()
		bottomLineTweenIn:Cancel()
		topLineTweenIn:Cancel()
		
		btnSizeInTween:Play()
		textTransparentTween:Play()
		bottomLineTweenOut:Play()
		topLineTweenOut:Play()
	end
	
	local function hoverTweenReverse()
	
		btnSizeInTween:Cancel()
		textTransparentTween:Cancel()
		bottomLineTweenOut:Cancel()
		topLineTweenOut:Cancel()
		
		btnSizeOutTween:Play()
		textOpaqueTween:Play()
		bottomLineTweenIn:Play()
		topLineTweenIn:Play()
	end
	
	
	btnHoverArea.MouseEnter:Connect(function()
		
		isHovering = true
		
		hoverTween()
	end)
	
	btnHoverArea.MouseLeave:Connect(function()
		
		isHovering = false
		
		hoverTweenReverse()
	end)
	
	btnHoverArea.MouseButton1Down:Connect(function()
		
		hoverTweenReverse()
	end)
	
	btnHoverArea.MouseButton1Up:Connect(function()
		
		if not isHovering then
			hoverTweenReverse()
		else
			hoverTween()
		end
	end)
end
coroutine.wrap(VKOMMY_fake_script)()
local function RBLDENG_fake_script() -- Button8_4.LocalScript 
	local script = Instance.new('LocalScript', Button8_4)

	
	script.Parent.MouseButton1Down:connect(function()
		if game.PlaceId == 6484864709 then
		loadstring(game:HttpGet("https://raw.githubusercontent.com/NocturneMoDz/Gym-Tycoon-/main/README.md",true))();
		end
	end)
end
coroutine.wrap(RBLDENG_fake_script)()
local function ENXVA_fake_script() -- Button8_5.Button8Script 
	local script = Instance.new('LocalScript', Button8_5)

	local btn = script.Parent
	local btnText = btn:WaitForChild("BtnText")
	
	local btnHoverArea = btn.Parent
	
	local lineTop = btnHoverArea:WaitForChild("LineTop")
	local lineBottom = btnHoverArea:WaitForChild("LineBottom")
	
	local isHovering = false
	
	local tweenService = game:GetService("TweenService")
	local tweenInfo = TweenInfo.new(0.3, Enum.EasingStyle.Quint, Enum.EasingDirection.InOut)
	
	local btnSizeInTween = tweenService:Create(btn, tweenInfo, {Size = UDim2.new(0.001, 0, 1, 0), ImageTransparency = 1})
	local btnSizeOutTween = tweenService:Create(btn, tweenInfo, {Size = UDim2.new(1, 0, 1, 0), ImageTransparency = 0})
	
	local textTransparentTween = tweenService:Create(btnText, tweenInfo, {TextTransparency = 1}) 
	local textOpaqueTween = tweenService:Create(btnText, tweenInfo, {TextTransparency = 0})
	
	local bottomLineTweenOut = tweenService:Create(lineBottom, tweenInfo, {Size = UDim2.new(1, 0, 0, 1), BackgroundTransparency = 0})
	local bottomLineTweenIn = tweenService:Create(lineBottom, tweenInfo, {Size = UDim2.new(0, 0, 0, 1), BackgroundTransparency = 1})
	local topLineTweenOut = tweenService:Create(lineTop, tweenInfo, {Size = UDim2.new(1, 0, 0, 1), BackgroundTransparency = 0})
	local topLineTweenIn = tweenService:Create(lineTop, tweenInfo, {Size = UDim2.new(0, 0, 0, 1), BackgroundTransparency = 1})
	
	
	local function hoverTween()
		
		btnSizeOutTween:Cancel()
		textOpaqueTween:Cancel()
		bottomLineTweenIn:Cancel()
		topLineTweenIn:Cancel()
		
		btnSizeInTween:Play()
		textTransparentTween:Play()
		bottomLineTweenOut:Play()
		topLineTweenOut:Play()
	end
	
	local function hoverTweenReverse()
	
		btnSizeInTween:Cancel()
		textTransparentTween:Cancel()
		bottomLineTweenOut:Cancel()
		topLineTweenOut:Cancel()
		
		btnSizeOutTween:Play()
		textOpaqueTween:Play()
		bottomLineTweenIn:Play()
		topLineTweenIn:Play()
	end
	
	
	btnHoverArea.MouseEnter:Connect(function()
		
		isHovering = true
		
		hoverTween()
	end)
	
	btnHoverArea.MouseLeave:Connect(function()
		
		isHovering = false
		
		hoverTweenReverse()
	end)
	
	btnHoverArea.MouseButton1Down:Connect(function()
		
		hoverTweenReverse()
	end)
	
	btnHoverArea.MouseButton1Up:Connect(function()
		
		if not isHovering then
			hoverTweenReverse()
		else
			hoverTween()
		end
	end)
end
coroutine.wrap(ENXVA_fake_script)()
local function XRDFJK_fake_script() -- Button8_5.LocalScript 
	local script = Instance.new('LocalScript', Button8_5)

	
	script.Parent.MouseButton1Down:connect(function()
		if game.PlaceId == 7662717460 then
			loadstring(game:HttpGet("https://raw.githubusercontent.com/NocturneMoDz/Get-Big-Simulator/main/SCRIPT",true))();
		end
	end)
end
coroutine.wrap(XRDFJK_fake_script)()
local function JODEF_fake_script() -- Button8_6.Button8Script 
	local script = Instance.new('LocalScript', Button8_6)

	local btn = script.Parent
	local btnText = btn:WaitForChild("BtnText")
	
	local btnHoverArea = btn.Parent
	
	local lineTop = btnHoverArea:WaitForChild("LineTop")
	local lineBottom = btnHoverArea:WaitForChild("LineBottom")
	
	local isHovering = false
	
	local tweenService = game:GetService("TweenService")
	local tweenInfo = TweenInfo.new(0.3, Enum.EasingStyle.Quint, Enum.EasingDirection.InOut)
	
	local btnSizeInTween = tweenService:Create(btn, tweenInfo, {Size = UDim2.new(0.001, 0, 1, 0), ImageTransparency = 1})
	local btnSizeOutTween = tweenService:Create(btn, tweenInfo, {Size = UDim2.new(1, 0, 1, 0), ImageTransparency = 0})
	
	local textTransparentTween = tweenService:Create(btnText, tweenInfo, {TextTransparency = 1}) 
	local textOpaqueTween = tweenService:Create(btnText, tweenInfo, {TextTransparency = 0})
	
	local bottomLineTweenOut = tweenService:Create(lineBottom, tweenInfo, {Size = UDim2.new(1, 0, 0, 1), BackgroundTransparency = 0})
	local bottomLineTweenIn = tweenService:Create(lineBottom, tweenInfo, {Size = UDim2.new(0, 0, 0, 1), BackgroundTransparency = 1})
	local topLineTweenOut = tweenService:Create(lineTop, tweenInfo, {Size = UDim2.new(1, 0, 0, 1), BackgroundTransparency = 0})
	local topLineTweenIn = tweenService:Create(lineTop, tweenInfo, {Size = UDim2.new(0, 0, 0, 1), BackgroundTransparency = 1})
	
	
	local function hoverTween()
		
		btnSizeOutTween:Cancel()
		textOpaqueTween:Cancel()
		bottomLineTweenIn:Cancel()
		topLineTweenIn:Cancel()
		
		btnSizeInTween:Play()
		textTransparentTween:Play()
		bottomLineTweenOut:Play()
		topLineTweenOut:Play()
	end
	
	local function hoverTweenReverse()
	
		btnSizeInTween:Cancel()
		textTransparentTween:Cancel()
		bottomLineTweenOut:Cancel()
		topLineTweenOut:Cancel()
		
		btnSizeOutTween:Play()
		textOpaqueTween:Play()
		bottomLineTweenIn:Play()
		topLineTweenIn:Play()
	end
	
	
	btnHoverArea.MouseEnter:Connect(function()
		
		isHovering = true
		
		hoverTween()
	end)
	
	btnHoverArea.MouseLeave:Connect(function()
		
		isHovering = false
		
		hoverTweenReverse()
	end)
	
	btnHoverArea.MouseButton1Down:Connect(function()
		
		hoverTweenReverse()
	end)
	
	btnHoverArea.MouseButton1Up:Connect(function()
		
		if not isHovering then
			hoverTweenReverse()
		else
			hoverTween()
		end
	end)
end
coroutine.wrap(JODEF_fake_script)()
local function TURG_fake_script() -- Button8_6.LocalScript 
	local script = Instance.new('LocalScript', Button8_6)

	
	script.Parent.MouseButton1Down:connect(function()
		if game.PlaceId == 7172456337 then
		loadstring(game:HttpGet("https://raw.githubusercontent.com/NocturneMoDz/Lawn-Mower-Simulator/main/SCRIPT",true))();
		end
	end)
end
coroutine.wrap(TURG_fake_script)()
local function ETUFS_fake_script() -- METABHUB_2.LocalScript 
	local script = Instance.new('LocalScript', METABHUB_2)

	script.Parent.MouseButton1Click:connect(function()
		script.Parent.Parent.METABIMAGE.Visible = not script.Parent.Parent.METABIMAGE.Visible
	end)
	
end
coroutine.wrap(ETUFS_fake_script)()
local function EZIX_fake_script() -- METABHUB_2.Button7Script 
	local script = Instance.new('LocalScript', METABHUB_2)

	local btn = script.Parent
	local uiGradient = btn:WaitForChild("UIGradient")
	
	local isHovering = false
	
	local tweenService = game:GetService("TweenService")
	local tweenInfo = TweenInfo.new(0.4, Enum.EasingStyle.Quint, Enum.EasingDirection.InOut)
	
	local gradientRestoreTween = tweenService:Create(uiGradient, tweenInfo, {Offset = Vector2.new(-0.35, 0)})
	local gradientAddTween = tweenService:Create(uiGradient, tweenInfo, {Offset = Vector2.new(1, 0)})
	
	
	btn.MouseEnter:Connect(function()
		
		isHovering = true
		
		gradientAddTween:Play()
	end)
	
	btn.MouseLeave:Connect(function()
		
		isHovering = false
		
		gradientRestoreTween:Play()
	end)
	
	btn.MouseButton1Down:Connect(function()
		
		gradientRestoreTween:Play()
	end)
	
	btn.MouseButton1Up:Connect(function()
		
		if not isHovering then
			gradientRestoreTween:Play()
		else
			gradientAddTween:Play()
		end
	end)
end
coroutine.wrap(EZIX_fake_script)()
