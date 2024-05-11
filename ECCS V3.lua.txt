if game:GetService("CoreGui"):FindFirstChild("UIGui") then
game:GetService("CoreGui"):FindFirstChild("UIGui"):Destroy()
game.Workspace.CurrentCamera.FieldOfView  = 70
end
local UIGui = Instance.new("ScreenGui")
local CoreSystemFrame = Instance.new("Frame")
local CoreSystemFrameBackground = Instance.new("Frame")
local CoreSystemFrameUICorner = Instance.new("UICorner")
local CoreSystemFrameBackgroundUICorner = Instance.new("UICorner")
local MinButton = Instance.new("TextButton")
local UIClick = Instance.new("Sound")
local MessageFrame = Instance.new("TextButton")
local MessageFrameUICorner = Instance.new("UICorner")
local Clock = Instance.new("TextLabel")
local StartUpSound = Instance.new("Sound")
local OpenButtonUI = Instance.new("Sound")
local MessageBackgroundFrame = Instance.new("Frame")
local TextLabel1 = Instance.new("TextLabel")
local MessageBackgroundFrameUICorner = Instance.new("UICorner")
local MessageImage = Instance.new("ImageLabel")
local CloseNotif = Instance.new("Sound")
local MessageImageUICorner = Instance.new("UICorner")
local OpenUIButtons = Instance.new("Sound")
local HomeButton = Instance.new("ImageButton")
local HomeButtonUICorner = Instance.new("UICorner")
local CloseUISound = Instance.new("Sound")
local Blur = Instance.new("BlurEffect")
local TweenService = game:GetService("TweenService")
local SearcherOpenUIButton = Instance.new("ImageButton")
local SearcherOpenUIButtonUICorner = Instance.new("UICorner")
local ConsoleButton = Instance.new("ImageButton")
local HoverButtons = Instance.new("Sound")
local EditorButton = Instance.new("ImageButton")
local MusicButton = Instance.new("ImageButton")
local WelcomeLabel = Instance.new("TextLabel")
local PlayerIcon = Instance.new("ImageLabel")
local PlayerIconUI = Instance.new("UICorner")
local PlayerIconBackground = Instance.new("Frame")
local PlayerIconBackgroundUI = Instance.new("UICorner")
local GameFrameBackground = Instance.new("Frame")
local GameFrameBackgroundUICorner = Instance.new("UICorner")
local GameFrame = Instance.new("ImageLabel")
local GameFrameUICorner = Instance.new("UICorner")
local FPSLabel = Instance.new("TextLabel")
local FPSLabelUICorner = Instance.new("UICorner")
local RunService = game:GetService("RunService")
local RenderStepped = RunService.RenderStepped
local sec = nil
local FPS = {}
local PingLabel = Instance.new("TextLabel")
local PingLabelUICorner = Instance.new("UICorner")
local CPULabel = Instance.new("TextLabel")
local CPUUICorner = Instance.new("UICorner")
local GPULabel = Instance.new("TextLabel")
local GPUUICorner = Instance.new("UICorner")
local PlayersInServer = Instance.new("TextLabel")
local PlayersInServerUICorner = Instance.new("UICorner")
local ServerSize = Instance.new("TextLabel")
local ServerSizeUICorner = Instance.new("UICorner")
local ServerLive = Instance.new("TextLabel")
local ServerLiveUICorner = Instance.new("UICorner")
local Executor = Instance.new("TextLabel")
local ExecutorUICorner = Instance.new("UICorner")
local MainFrame = Instance.new("Frame")
local SearchBox = Instance.new("TextBox")
local UICorner_3 = Instance.new("UICorner")
local ScriptAuthor = Instance.new("TextLabel")
local ScriptListFrame = Instance.new("ScrollingFrame")
local UIPadding = Instance.new("UIPadding")
local Scripts = Instance.new("Folder")
local UIGridLayout = Instance.new("UIGridLayout")
local ScriptFrame = Instance.new("ImageLabel")
local UICorner_6 = Instance.new("UICorner")
local ScriptTitle = Instance.new("TextLabel")
local ExecuteButton = Instance.new("TextButton")
local UICorner_7 = Instance.new("UICorner")
local InfoButton = Instance.new("TextButton")
local UICorner_8 = Instance.new("UICorner")
local ScriptGame = Instance.new("TextLabel")
local VerifiedScriptFrame = Instance.new("ImageLabel")
local UICorner_9 = Instance.new("UICorner")
local ScriptTitle_2 = Instance.new("TextLabel")
local VerifiedIcon = Instance.new("ImageLabel")
local ExecuteButton_2 = Instance.new("TextButton")
local UICorner_10 = Instance.new("UICorner")
local UICorner_11 = Instance.new("UICorner")
local ScriptAuthor_2 = Instance.new("TextLabel")
local ScriptGame_2 = Instance.new("TextLabel")
local ExecuteButtonBackground = Instance.new("Frame")
local ExecuteButtonBackgroundUICorner = Instance.new("UICorner")
local CopyLinkButton = Instance.new("TextButton")
local CopyLinkButtonUICorner = Instance.new("UICorner")
local CopyLinkButton_2 = Instance.new("TextButton")
local CopyLinkButtonUICorner_2 = Instance.new("UICorner")
local CopyScriptButton = Instance.new("TextButton")
local CopyScriptButtonUICorner = Instance.new("UICorner")
local CopyScriptButton_2 = Instance.new("TextButton")
local CopyScriptButtonUICorner_2 = Instance.new("UICorner")
local OpenDescriptionButton = Instance.new("TextButton")
local OpenDescriptionButtonUICorner = Instance.new("UICorner")
local OpenDescriptionButton_2 = Instance.new("TextButton")
local OpenDescriptionButtonUICorner_2 = Instance.new("UICorner")
local CopyLinkButtonBackground = Instance.new("Frame")
local CopyLinkButtonBackgroundUICorner = Instance.new("UICorner")
local CopyScriptBackground = Instance.new("Frame")
local CopyScriptBackgroundUICorner = Instance.new("UICorner")
local OpenDescriptionBackground = Instance.new("Frame")
local OpenDescriptionBackgroundUICorner = Instance.new("UICorner")
local ExecuteButtonBackground_2 = Instance.new("Frame")
local ExecuteButtonBackgroundUICorner_2 = Instance.new("UICorner")
local CopyLinkButtonBackground_2 = Instance.new("Frame")
local CopyLinkButtonBackgroundUICorner_2 = Instance.new("UICorner")
local CopyScriptBackground_2 = Instance.new("Frame")
local CopyScriptBackgroundUICorner_2 = Instance.new("UICorner")
local OpenDescriptionBackground_2 = Instance.new("Frame")
local OpenDescriptionBackgroundUICorner_2 = Instance.new("UICorner")
local DescriptionScript = Instance.new("TextButton")
local DescriptionScriptUICorner = Instance.new("UICorner")
local BackgroundImage = Instance.new("ImageLabel")
local ConsoleOutput = Instance.new("TextLabel")
local BackgroundImageUICorner = Instance.new("UICorner")
local ConsoleOutputUICorner = Instance.new("UICorner")
local BackgroundConsoleUICorner = Instance.new("UICorner")
local BackgroundConsole = Instance.new("Frame")
local logTable = {}
local CloseDescriptionSound = Instance.new("Sound")
local EditorBackground = Instance.new("Frame")
local EditorMainFrame = Instance.new("ImageLabel")
local EditorTextBox = Instance.new("TextBox")
local ExecuteButtonBackground_3 = Instance.new("Frame")
local ExecuteButton_3 = Instance.new("TextButton")
local EditorBackgroundUICorner = Instance.new("UICorner")
local EditorMainFrameUICorner = Instance.new("UICorner")
local ExecuteButtonBackgroundUICorner_3 = Instance.new("UICorner")
local ExecuteButtonUICorner_3 = Instance.new("UICorner")
local SaveButtonBackground = Instance.new("Frame")
local SaveButtonBackgroundUICorner = Instance.new("UICorner")
local SaveButton = Instance.new("TextButton")
local SaveButtonUICorner = Instance.new("UICorner")
local ClearButtonBackground = Instance.new("Frame")
local ClearButtonBackgroundUICorner = Instance.new("UICorner")
local ClearButton = Instance.new("TextButton")
local ClearButtonUICorner = Instance.new("UICorner")
local EditorTextBoxUICorner = Instance.new("UICorner")
local EditorTextBoxBackgroundUICorner = Instance.new("UICorner")
local CopyButtonBackground = Instance.new("Frame")
local CopyButtonBackgroundUICorner = Instance.new("UICorner")
local CopyButton = Instance.new("TextButton")
local CopyButtonUICorner = Instance.new("UICorner")
local SondFrameBackground = Instance.new("Frame")
local SondFrame = Instance.new("ImageLabel")
local MainSondFrame = Instance.new("Frame")
local SoundTextBox = Instance.new("TextBox")
local SondFrameBackgroundUICorner = Instance.new("UICorner")
local SondFrameUICorner = Instance.new("UICorner")
local MainSondFrameUICorner = Instance.new("UICorner")
local SoundTextBoxUICorner = Instance.new("UICorner")
local CoreSound = Instance.new("Sound")
local Stop_PlayButton = Instance.new("ImageButton")
local AudioName = Instance.new("TextLabel")
local Stop_PlayButtonBackground = Instance.new("Frame")
local Stop_PlayButtonBackgroundUICorner = Instance.new("UICorner")
local Stop_PlayButtonBackground_2 = Instance.new("Frame")
local Stop_PlayButtonBackgroundUICorner_2 = Instance.new("UICorner")
local Volume = 1
local SaveButtonBackground_2 = Instance.new("Frame")
local SaveButtonBackgroundUICorner_2 = Instance.new("UICorner")
local SaveButton_2 = Instance.new("ImageButton")
local SaveButtonUICorner_2 = Instance.new("UICorner")
local PlaylistButtonBackground = Instance.new("Frame")
local PlaylistButtonBackgroundUICorner = Instance.new("UICorner")
local PlaylistButtonBackground_2 = Instance.new("Frame")
local PlaylistButtonBackgroundUICorner_2 = Instance.new("UICorner")
local PlaylistButton = Instance.new("ImageButton")
local VolumeFrame = Instance.new("Frame")
local VolumeFrameUICorner = Instance.new("UICorner")
local VolumeUpButtonBackground = Instance.new("Frame")
local VolumeUpButtonBackgroundUICorner = Instance.new("UICorner")
local VolumeUpButton = Instance.new("ImageButton")
local VolumeUpButtonUICorner = Instance.new("UICorner")
local VolumeDownButtonBackground = Instance.new("Frame")
local VolumeDownButtonBackgroundUICorner = Instance.new("UICorner")
local VolumeDownButton = Instance.new("ImageButton")
local VolumeDownButtonUICorner = Instance.new("UICorner")
local VolumeUpButton_2 = Instance.new("ImageButton")
local VolumeUpButtonUICorner_2 = Instance.new("UICorner")
local VolumeDownButton_2 = Instance.new("ImageButton")
local VolumeDownButtonUICorner_2 = Instance.new("UICorner")
ReloadBackgroundButton = Instance.new("Frame")
ReloadBackgroundButtonUICorner = Instance.new("UICorner")
ReloadButton = Instance.new("ImageButton")
ReloadButtonUICorner = Instance.new("UICorner")
HistoryBackgroundButton = Instance.new("Frame")
HistoryBackgroundButtonUICorner = Instance.new("UICorner")
HistoryButton = Instance.new("ImageButton")
HistoryButtonUICorner = Instance.new("UICorner")
ClearAndSearchBackground = Instance.new("Frame")
ClearAndSearchBackgroundUICorner = Instance.new("UICorner")
ClearAndSearch = Instance.new("ImageButton")
ClearAndSearchUICorner = Instance.new("UICorner")
ClearButton_2Background = Instance.new("Frame")
ClearButton_2BackgroundUICorner = Instance.new("UICorner")
ClearButton_2 = Instance.new("ImageButton")
ClearButton_2UICorner = Instance.new("UICorner")

local function format(Int)
return string.format("%02i", Int)
end
 
local function convertToHMS(Seconds)
local Minutes = (Seconds - Seconds%60)/60
Seconds = Seconds - Minutes*60
local Hours = (Minutes - Minutes%60)/60
Minutes = Minutes - Hours*60
return format(Hours)..":"..format(Minutes)..":"..format(Seconds)
end
 
UIGui.Name = "UIGui"
UIGui.Parent = game.CoreGui
UIGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling
game.CoreGui.UIGui.Enabled = true
 
Blur.Size = 0
Blur.Parent = workspace.CurrentCamera
 
UIClick.Parent = game:GetService("SoundService")
UIClick.SoundId = "rbxassetid://626181985"
UIClick.Playing = true
UIClick.Looped = false
UIClick.Volume = 1
UIClick:Stop()
 
CoreSound.Parent = game:GetService("SoundService")
CoreSound.Playing = true
CoreSound.Looped = true
CoreSound.Volume = Volume
CoreSound:Stop()
 
CloseDescriptionSound.Parent = game:GetService("SoundService")
CloseDescriptionSound.SoundId = "rbxassetid://6698737249"
CloseDescriptionSound.Playing = true
CloseDescriptionSound.Looped = false
CloseDescriptionSound.Volume = 1
CloseDescriptionSound:Stop()
 
StartUpSound.Parent = game:GetService("SoundService")
StartUpSound.SoundId = "rbxassetid://6228337171"
StartUpSound.Playing = true
StartUpSound.Looped = false
StartUpSound.Volume = 1
StartUpSound:Stop()
 
OpenButtonUI.Parent = game:GetService("SoundService")
OpenButtonUI.SoundId = "rbxassetid://3779036535"
OpenButtonUI.Playing = true
OpenButtonUI.Looped = false
OpenButtonUI.Volume = 1
OpenButtonUI:Stop()
 
HoverButtons.Parent = game:GetService("SoundService")
HoverButtons.SoundId = "rbxassetid://6698737249"
HoverButtons.Playing = true
HoverButtons.Looped = false
HoverButtons.Volume = 1
HoverButtons:Stop()
 
CloseNotif.Parent = game:GetService("SoundService")
CloseNotif.SoundId = "rbxassetid://2566705750"
CloseNotif.Playing = true
CloseNotif.Looped = false
CloseNotif.Volume = 1
CloseNotif:Stop()
 
CloseUISound.Parent = game:GetService("SoundService")
CloseUISound.SoundId = "rbxassetid://2570875942"
CloseUISound.Playing = true
CloseUISound.Looped = false
CloseUISound.Volume = 1
CloseUISound:Stop()
 
OpenUIButtons.Parent = game:GetService("SoundService")
OpenUIButtons.SoundId = "rbxassetid://3779036535"
OpenUIButtons.Playing = true
OpenUIButtons.Looped = false
OpenUIButtons.Volume = 1
OpenUIButtons:Stop()
 
MessageBackgroundFrame.Name = "MessageBackgroundFrame"
MessageBackgroundFrame.Parent = UIGui
MessageBackgroundFrame.AnchorPoint = Vector2.new(0.5, 0.5)
MessageBackgroundFrame.BackgroundColor3 = Color3.fromRGB(55, 55, 55)
MessageBackgroundFrame.Position = UDim2.new(0.5, 0, 2.5, 0)
MessageBackgroundFrame.Size = UDim2.new(0, 300, 0, 60)
MessageBackgroundFrame.ZIndex = 2
 
MessageBackgroundFrameUICorner.CornerRadius = UDim.new(0, 12)
MessageBackgroundFrameUICorner.Parent = MessageBackgroundFrame
 
MessageFrame.Name = "MessageFrame"
MessageFrame.Parent = MessageBackgroundFrame
MessageFrame.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
MessageFrame.Position = UDim2.new(0.5, 0, 0.5, 0)
MessageFrame.Size = UDim2.new(0, 297.3, 0, 57.5)
MessageFrame.AutoButtonColor = false
MessageFrame.Font = Enum.Font.SourceSansBold
MessageFrame.Text = "Successfully Loaded"
MessageFrame.TextColor3 = Color3.fromRGB(255, 255, 255)
MessageFrame.TextYAlignment = Enum.TextYAlignment.Top
MessageFrame.TextXAlignment = Enum.TextXAlignment.Right
MessageFrame.TextSize = 30
MessageFrame.AnchorPoint = Vector2.new(0.5, 0.5)
 
MessageFrameUICorner.CornerRadius = UDim.new(0, 12)
MessageFrameUICorner.Parent = MessageFrame
 
local emoji = ({
        ["01 01"] = "🎆",
        [(function(Year)
            local A = math.floor(Year/100)
            local B = math.floor((13+8*A)/25)
            local C = (15-B+A-math.floor(A/4))%30
            local D = (4+A-math.floor(A/4))%7
            local E = (19*(Year%19)+C)%30
            local F = (2*(Year%4)+4*(Year%7)+6*E+D)%7
            local G = (22+E+F)
            if E == 29 and F == 6 then
                return "04 19"
            elseif E == 28 and F == 6 then
                return "04 18"
            elseif 31 < G then
                return ("04 %02d"):format(G-31)
            end
            return ("03 %02d"):format(G)
        end)(tonumber(os.date"%Y"))] = "🥚",
        ["10 31"] = "🎃",
        ["12 25"] = "🎄"
    })[os.date("%m %d")]
    if emoji then
        MessageFrame.Text = ("%s %s"):format(MessageFrame.Text, emoji)
    end
MessageFrame.MouseButton1Click:Connect(function()
CloseNotif:Play()
MessageBackgroundFrame:TweenPosition(UDim2.new(0.5, 0, 2.5, 0),"InOut","Sine",0.3)
wait(0.5)
MessageBackgroundFrame:Destroy()
end)
 
MessageImage.Name = "MessageImage"
MessageImage.Parent = MessageFrame
MessageImage.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
MessageImage.BackgroundTransparency = 0.5
MessageImage.Position = UDim2.new(0.03, 0, 0.15, 0)
MessageImage.Size = UDim2.new(0, 40, 0, 40)
MessageImage.BorderSizePixel = 0
MessageImage.Image = "rbxassetid://15980315949"
 
MessageImageUICorner.Parent = MessageImage
MessageImageUICorner.CornerRadius = UDim.new(0.5, 0)
 
TextLabel1.Name = "TextLabel1"
TextLabel1.Parent = MessageFrame
TextLabel1.BackgroundTransparency = 1
TextLabel1.Position = UDim2.new(0.55, 0, 0.7, 0)
TextLabel1.Size = UDim2.new(0, 1, 0, 1)
TextLabel1.Font = Enum.Font.SourceSansBold
TextLabel1.Text = "Welcome to ECCS V3, "..game.Players.LocalPlayer.DisplayName
TextLabel1.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel1.TextTransparency = 0.3
TextLabel1.TextSize = 15
 
spawn(function()
repeat
wait()
if  MessageBackgroundFrame.Position == UDim2.new(0.5, 0, 0.9, 0) then
wait(4)
MessageBackgroundFrame:TweenPosition(UDim2.new(0.5, 0, 2.5, 0),"InOut","Sine",0.8)
CloseNotif:Play()
wait(0.5)
MessageBackgroundFrame:Destroy()
end
until 
MessageBackgroundFrame == nil
end)
 
CoreSystemFrameBackground.Name = "CoreSystemFrameBackground"
CoreSystemFrameBackground.Parent = UIGui
CoreSystemFrameBackground.AnchorPoint = Vector2.new(0.5, 0.5)
CoreSystemFrameBackground.BackgroundColor3 = Color3.fromRGB(55, 55, 55)
CoreSystemFrameBackground.Position = UDim2.new(-0.03, 0, 0.45, 0)
CoreSystemFrameBackground.Size = UDim2.new(0, 53.7, 0, 223)
CoreSystemFrameBackground.ZIndex = 2
 
CoreSystemFrameBackgroundUICorner.CornerRadius = UDim.new(0, 12)
CoreSystemFrameBackgroundUICorner.Parent = CoreSystemFrameBackground
 
CoreSystemFrame.Name = "CoreSystemFrame"
CoreSystemFrame.Parent = CoreSystemFrameBackground
CoreSystemFrame.AnchorPoint = Vector2.new(0.5, 0.5)
CoreSystemFrame.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
CoreSystemFrame.Position = UDim2.new(0.5, 0, 0.5, 0)
CoreSystemFrame.Size = UDim2.new(0, 50, 0, 220)
CoreSystemFrame.ZIndex = 2
 
CoreSystemFrameUICorner.CornerRadius = UDim.new(0, 12)
CoreSystemFrameUICorner.Parent = CoreSystemFrame
 
HomeButton.Parent = CoreSystemFrame
HomeButton.Size = UDim2.new(0, 33, 0, 33)
HomeButton.Position = UDim2.new(0.5, 0, 0.1, 0)
HomeButton.AnchorPoint = Vector2.new(0.5, 0.5)
HomeButton.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
HomeButton.ZIndex = 2
HomeButton.Image = "rbxassetid://15997029966"
HomeButton.AutoButtonColor = false
 
HomeButtonUICorner.CornerRadius = UDim.new(0, 12)
HomeButtonUICorner.Parent = HomeButton
HomeButton.MouseButton1Click:Connect(function()
game.Workspace.CurrentCamera.FieldOfView  = 70
SondFrameBackground:TweenPosition(UDim2.new(0.5, 0, -1, 0),"InOut","Sine",0.1)
EditorBackground:TweenPosition(UDim2.new(0.525, 0, -1, 0),"InOut","Sine",0.1)
BackgroundConsole:TweenPosition(UDim2.new(0.525, 0, -1, 0),"InOut","Sine",0.1)
MainFrame:TweenPosition(UDim2.new(0.5, 0, -1, 0),"InOut","Sine",0.1)
SearcherOpenUIButton.Image = "rbxassetid://15996914627"
MusicButton.Image = "rbxassetid://15996975276"
ConsoleButton.Image = "rbxassetid://16006754625"
EditorButton.Image = "rbxassetid://16006689419"
if HomeButton.Image == "rbxassetid://15997029966" then
Blur.Size = 100
HomeButton.Image = "rbxassetid://15997127208"
OpenButtonUI:Play()
GameFrameBackground:TweenPosition(UDim2.new(0.25, 0, 0.3, 0),"InOut","Sine",0.1)
game.Workspace.CurrentCamera.FieldOfView  = 30
else
if HomeButton.Image == "rbxassetid://15997127208" then
HomeButton.Image = "rbxassetid://15997029966"
CloseUISound:Play()
GameFrameBackground:TweenPosition(UDim2.new(0.25, 0, -1, 0),"InOut","Sine",0.1)
Blur.Size = 0
game.Workspace.CurrentCamera.FieldOfView  = 70
end
end
end)
 
MainFrame.Name = "MainFrame"
MainFrame.Parent = UIGui
MainFrame.AnchorPoint = Vector2.new(0.5, 0.5)
MainFrame.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
MainFrame.BackgroundTransparency = 1
MainFrame.Position = UDim2.new(0.5, 0, -1, 0)
MainFrame.Size = UDim2.new(0, 100, 0, 100)
 
SearcherOpenUIButton.Parent = CoreSystemFrame
SearcherOpenUIButton.Size = UDim2.new(0, 33, 0, 33)
SearcherOpenUIButton.Position = UDim2.new(0.5, 0, 0.28, 0)
SearcherOpenUIButton.AnchorPoint = Vector2.new(0.5, 0.5)
SearcherOpenUIButton.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
SearcherOpenUIButton.ZIndex = 2
SearcherOpenUIButton.Image = "rbxassetid://15996914627"
SearcherOpenUIButton.AutoButtonColor = false
 
SearcherOpenUIButtonUICorner.CornerRadius = UDim.new(0, 12)
SearcherOpenUIButtonUICorner.Parent = SearcherOpenUIButton
 
SearcherOpenUIButton.MouseButton1Click:Connect(function()
SondFrameBackground:TweenPosition(UDim2.new(0.5, 0, -1, 0),"InOut","Sine",0.1)
EditorBackground:TweenPosition(UDim2.new(0.525, 0, -1, 0),"InOut","Sine",0.1)
BackgroundConsole:TweenPosition(UDim2.new(0.525, 0, -1, 0),"InOut","Sine",0.1)
GameFrameBackground:TweenPosition(UDim2.new(0.25, 0, -1, 0),"InOut","Sine",0.1)
game.Workspace.CurrentCamera.FieldOfView  = 70
HomeButton.Image = "rbxassetid://15997029966"
MusicButton.Image = "rbxassetid://15996975276"
ConsoleButton.Image = "rbxassetid://16006754625"
EditorButton.Image = "rbxassetid://16006689419"
if SearcherOpenUIButton.Image == "rbxassetid://15996914627" then
SearcherOpenUIButton.Image = "rbxassetid://15997131910"
OpenButtonUI:Play()
Blur.Size = 100
MainFrame:TweenPosition(UDim2.new(0.5, 0, 0.5, 0),"InOut","Sine",0.1)
game.Workspace.CurrentCamera.FieldOfView  = 30
else
if SearcherOpenUIButton.Image == "rbxassetid://15997131910" then
SearcherOpenUIButton.Image = "rbxassetid://15996914627"
CloseUISound:Play()
Blur.Size = 0
MainFrame:TweenPosition(UDim2.new(0.5, 0, -1, 0),"InOut","Sine",0.1)
game.Workspace.CurrentCamera.FieldOfView  = 70
end
end
end)
 
EditorButton.Parent = CoreSystemFrame
EditorButton.Size = UDim2.new(0, 33, 0, 33)
EditorButton.Position = UDim2.new(0.5, 0, 0.64, 0)
EditorButton.AnchorPoint = Vector2.new(0.5, 0.5)
EditorButton.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
EditorButton.ZIndex = 2
EditorButton.Image = "rbxassetid://16006689419"
EditorButton.AutoButtonColor = false
EditorButton.BorderSizePixel = 0
 
EditorButton.MouseButton1Click:Connect(function()
SondFrameBackground:TweenPosition(UDim2.new(0.5, 0, -1, 0),"InOut","Sine",0.1)
BackgroundConsole:TweenPosition(UDim2.new(0.525, 0, -1, 0),"InOut","Sine",0.1)
GameFrameBackground:TweenPosition(UDim2.new(0.25, 0, -1, 0),"InOut","Sine",0.1)
MainFrame:TweenPosition(UDim2.new(0.5, 0, -1, 0),"InOut","Sine",0.1)
game.Workspace.CurrentCamera.FieldOfView  = 70
HomeButton.Image = "rbxassetid://15997029966"
ConsoleButton.Image = "rbxassetid://16006754625"
MusicButton.Image = "rbxassetid://15996975276"
SearcherOpenUIButton.Image = "rbxassetid://15996914627"
if EditorButton.Image == "rbxassetid://16006689419" then
EditorButton.Image = "rbxassetid://16006691599"
OpenButtonUI:Play()
EditorBackground:TweenPosition(UDim2.new(0.525, 0, 0.5, 0),"InOut","Sine",0.1)
Blur.Size = 100
game.Workspace.CurrentCamera.FieldOfView  = 30
else
if EditorButton.Image == "rbxassetid://16006691599" then
EditorButton.Image = "rbxassetid://16006689419"
CloseUISound:Play()
EditorBackground:TweenPosition(UDim2.new(0.525, 0, -1, 0),"InOut","Sine",0.1)
Blur.Size = 0
game.Workspace.CurrentCamera.FieldOfView  = 70
end
end
end)
 
ConsoleButton.Parent = CoreSystemFrame
ConsoleButton.Size = UDim2.new(0, 33, 0, 33)
ConsoleButton.Position = UDim2.new(0.5, 0, 0.46, 0)
ConsoleButton.AnchorPoint = Vector2.new(0.5, 0.5)
ConsoleButton.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
ConsoleButton.ZIndex = 2
ConsoleButton.Image = "rbxassetid://16006754625"
ConsoleButton.AutoButtonColor = false
ConsoleButton.BorderSizePixel = 0
 
ConsoleButton.MouseButton1Click:Connect(function()
SondFrameBackground:TweenPosition(UDim2.new(0.5, 0, -1, 0),"InOut","Sine",0.1)
EditorBackground:TweenPosition(UDim2.new(0.525, 0, -1, 0),"InOut","Sine",0.1)
GameFrameBackground:TweenPosition(UDim2.new(0.25, 0, -1, 0),"InOut","Sine",0.1)
MainFrame:TweenPosition(UDim2.new(0.5, 0, -1, 0),"InOut","Sine",0.1)
game.Workspace.CurrentCamera.FieldOfView  = 70
HomeButton.Image = "rbxassetid://15997029966"
MusicButton.Image = "rbxassetid://15996975276"
SearcherOpenUIButton.Image = "rbxassetid://15996914627"
EditorButton.Image = "rbxassetid://16006689419"
if ConsoleButton.Image == "rbxassetid://16006754625" then
ConsoleButton.Image = "rbxassetid://16006757026"
OpenButtonUI:Play()
BackgroundConsole:TweenPosition(UDim2.new(0.525, 0, 0.5, 0),"InOut","Sine",0.1)
Blur.Size = 100
game.Workspace.CurrentCamera.FieldOfView  = 30
else
if ConsoleButton.Image == "rbxassetid://16006757026" then
ConsoleButton.Image = "rbxassetid://16006754625"
CloseUISound:Play()
BackgroundConsole:TweenPosition(UDim2.new(0.525, 0, -1, 0),"InOut","Sine",0.1)
Blur.Size = 0
game.Workspace.CurrentCamera.FieldOfView  = 70
end
end
end)
 
MusicButton.Parent = CoreSystemFrame
MusicButton.Size = UDim2.new(0, 30, 0, 30)
MusicButton.Position = UDim2.new(0.5, 0, 0.82, 0)
MusicButton.AnchorPoint = Vector2.new(0.5, 0.5)
MusicButton.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
MusicButton.ZIndex = 2
MusicButton.Image = "rbxassetid://15996975276"
MusicButton.AutoButtonColor = false
MusicButton.BorderSizePixel = 0
 
MusicButton.MouseButton1Click:Connect(function()
EditorBackground:TweenPosition(UDim2.new(0.525, 0, -1, 0),"InOut","Sine",0.1)
BackgroundConsole:TweenPosition(UDim2.new(0.525, 0, -1, 0),"InOut","Sine",0.1)
GameFrameBackground:TweenPosition(UDim2.new(0.25, 0, -1, 0),"InOut","Sine",0.1)
MainFrame:TweenPosition(UDim2.new(0.5, 0, -1, 0),"InOut","Sine",0.1)
game.Workspace.CurrentCamera.FieldOfView  = 70
HomeButton.Image = "rbxassetid://15997029966"
SearcherOpenUIButton.Image = "rbxassetid://15996914627"
EditorButton.Image = "rbxassetid://16006689419"
ConsoleButton.Image = "rbxassetid://16006754625"
if MusicButton.Image == "rbxassetid://15996975276" then
MusicButton.Image = "rbxassetid://15997129790"
SondFrameBackground:TweenPosition(UDim2.new(0.5, 0, 0.5, 0),"InOut","Sine",0.1)
OpenButtonUI:Play()
Blur.Size = 100
game.Workspace.CurrentCamera.FieldOfView  = 30
else
if MusicButton.Image == "rbxassetid://15997129790" then
MusicButton.Image = "rbxassetid://15996975276"
SondFrameBackground:TweenPosition(UDim2.new(0.5, 0, -1, 0),"InOut","Sine",0.1)
CloseUISound:Play()
Blur.Size = 0
game.Workspace.CurrentCamera.FieldOfView  = 70
end
end
end)
 
 
 
MinButton.Name = "MinButton"
MinButton.Parent = UIGui
MinButton.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
MinButton.Position = UDim2.new(0, 0, 0.43, 0)
MinButton.Size = UDim2.new(0, 30, 0, 30)
MinButton.AutoButtonColor = false
MinButton.Font = Enum.Font.SourceSansBold
MinButton.Text = "<"
MinButton.TextColor3 = Color3.fromRGB(255, 255, 255)
MinButton.TextSize = 30
MinButton.BackgroundTransparency = 1
 
Clock.Parent = CoreSystemFrame
Clock.Size = UDim2.new(0, 55, 0, 32)
Clock.Position = UDim2.new(0, -2.5, 0, 195)
Clock.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Clock.BackgroundTransparency = 1
Clock.Text = os.date("%H:%M")
Clock.TextColor3 = Color3.fromRGB(200, 200, 200)
Clock.Font = Enum.Font.SourceSansBold
Clock.TextSize = 20
 
MinButton:TweenPosition(UDim2.new(0.05, 0, 0.43, 0),"InOut","Sine",1)
CoreSystemFrameBackground:TweenPosition(UDim2.new(0.03, 0, 0.45, 0),"InOut","Sine",1)
 
MinButton.MouseButton1Click:Connect(function()
UIClick:Play()
Blur.Size = 0
SondFrameBackground:TweenPosition(UDim2.new(0.5, 0, -1, 0),"InOut","Sine",0.1)
EditorBackground:TweenPosition(UDim2.new(0.525, 0, -1, 0),"InOut","Sine",0.1)
BackgroundConsole:TweenPosition(UDim2.new(0.525, 0, -1, 0),"InOut","Sine",0.1)
GameFrameBackground:TweenPosition(UDim2.new(0.25, 0, -1, 0),"InOut","Sine",0.1)
MainFrame:TweenPosition(UDim2.new(0.5, 0, -1, 0),"InOut","Sine",0.1)
game.Workspace.CurrentCamera.FieldOfView  = 70
HomeButton.Image = "rbxassetid://15997029966"
SearcherOpenUIButton.Image = "rbxassetid://15996914627"
MusicButton.Image = "rbxassetid://15996975276"
ConsoleButton.Image = "rbxassetid://16006754625"
EditorButton.Image = "rbxassetid://16006689419"
if MinButton.Text == "<" then
MinButton.Text = ">"
CoreSystemFrameBackground:TweenPosition(UDim2.new(-0.03, 0, 0.45, 0),"InOut","Sine",0.15)
MinButton:TweenPosition(UDim2.new(0, 0, 0.43, 0),"InOut","Sine",0.15)
else
if MinButton.Text == ">" then
MinButton.Text = "<"
MinButton:TweenPosition(UDim2.new(0.05, 0, 0.43, 0),"InOut","Sine",0.15)
CoreSystemFrameBackground.Visible = true
CoreSystemFrameBackground:TweenPosition(UDim2.new(0.03, 0, 0.45, 0),"InOut","Sine",0.15)
end
end
end)
 
PlayerIcon.Name = "PlayerIcon"
PlayerIcon.Parent = PlayerIconBackground
PlayerIcon.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
PlayerIcon.Position = UDim2.new(0.026, 0, 0.025, 0)
PlayerIcon.Size = UDim2.new(0, 66, 0, 66)
PlayerIcon.Image = "rbxassetid://15980315949"
 
PlayerIconUI.Parent = PlayerIcon
PlayerIconUI.CornerRadius = UDim.new(0.5, 0)
 
PlayerIconBackground.Name = "PlayerIconBackground"
PlayerIconBackground.Parent = GameFrame
PlayerIconBackground.BackgroundColor3 = Color3.fromRGB(55, 55, 55)
PlayerIconBackground.Position = UDim2.new(0.05, 0, -0.6, 0)
PlayerIconBackground.Size = UDim2.new(0, 70, 0, 70)
 
PlayerIconBackgroundUI.Parent = PlayerIconBackground
PlayerIconBackgroundUI.CornerRadius = UDim.new(0.5, 0)
 
WelcomeLabel.Name = "WelcomeLabel"
WelcomeLabel.Parent = GameFrame
WelcomeLabel.BackgroundTransparency = 1
WelcomeLabel.Position = UDim2.new(0.23, 0, -0.6, 0)
WelcomeLabel.Size = UDim2.new(0.5, 0, 0.4, 0)
WelcomeLabel.Font = Enum.Font.SourceSansBold
WelcomeLabel.Text = "Welcome Home, User"
WelcomeLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
WelcomeLabel.TextXAlignment = Enum.TextXAlignment.Left
WelcomeLabel.TextYAlignment = Enum.TextYAlignment.Top
WelcomeLabel.TextWrapped = true
WelcomeLabel.TextSize = 25
 
GameFrameBackground.Name = "GameFrameBackground"
GameFrameBackground.Parent = UIGui
GameFrameBackground.Position = UDim2.new(0.25, 0, -1, 0)
GameFrameBackground.Size = UDim2.new(0.5, 0, 0.5, 0)
GameFrameBackground.BackgroundColor3 = Color3.fromRGB(55, 55, 55)
 
GameFrameBackgroundUICorner.Parent = GameFrameBackground
GameFrameBackgroundUICorner.CornerRadius = UDim.new(0, 12)
 
GameFrame.Name = "GameFrame"
GameFrame.Parent = GameFrameBackground
GameFrame.Position = UDim2.new(0.005, 0, 0.01, 0)
GameFrame.Size = UDim2.new(0.99, 0, 0.985, 0)
GameFrame.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
GameFrame.Image = "rbxassetid://16027463995"
 
GameFrameUICorner.Parent = GameFrame
GameFrameUICorner.CornerRadius = UDim.new(0, 12)
 
FPSLabel.Name = "FPSLabel"
FPSLabel.Parent = GameFrame
FPSLabel.Position = UDim2.new(0.01, 0, 0.015, 0)
FPSLabel.Size = UDim2.new(0.35, 0, 0.2, 0)
FPSLabel.Font = Enum.Font.SourceSansBold
FPSLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
FPSLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
FPSLabel.TextSize = 25
FPSLabel.BackgroundTransparency = 0.8
 
FPSLabelUICorner.Parent = FPSLabel
FPSLabelUICorner.CornerRadius = UDim.new(0, 12)
 
local function fre()
local fr = tick()
for index = #FPS,1,-1 do
FPS[index + 1] = (FPS[index] >= fr - 1) and FPS[index] or nil
end
FPS[1] = fr
local fps = (tick() - sec >= 1 and #FPS) or (#FPS / (tick() - sec))
fps = math.floor(fps)
FPSLabel.Text = "Fps: "..fps
end
sec = tick()
RenderStepped:Connect(fre)
 
PingLabel.Name = "PingLabel"
PingLabel.Parent = GameFrame
PingLabel.Position = UDim2.new(0.37, 0, 0.015, 0)
PingLabel.Size = UDim2.new(0.62, 0, 0.2, 0)
PingLabel.Font = Enum.Font.SourceSansBold
PingLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
PingLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
PingLabel.TextSize = 25
PingLabel.BackgroundTransparency = 0.8
 
PingLabelUICorner.Parent = PingLabel
PingLabelUICorner.CornerRadius = UDim.new(0, 12)
 
 
CPULabel.Name = "CPULabel"
CPULabel.Parent = GameFrame
CPULabel.Position = UDim2.new(0.01, 0, 0.265, 0)
CPULabel.Size = UDim2.new(0.62, 0, 0.2, 0)
CPULabel.Font = Enum.Font.SourceSansBold
CPULabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
CPULabel.TextColor3 = Color3.fromRGB(255, 255, 255)
CPULabel.TextSize = 25
CPULabel.BackgroundTransparency = 0.8
 
CPUUICorner.Parent = CPULabel
CPUUICorner.CornerRadius = UDim.new(0, 12)
 
GPULabel.Name = "GPULabel"
GPULabel.Parent = GameFrame
GPULabel.Position = UDim2.new(0.64, 0, 0.265, 0)
GPULabel.Size = UDim2.new(0.35, 0, 0.2, 0)
GPULabel.Font = Enum.Font.SourceSansBold
GPULabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
GPULabel.TextColor3 = Color3.fromRGB(255, 255, 255)
GPULabel.TextSize = 25
GPULabel.BackgroundTransparency = 0.8
 
GPUUICorner.Parent = GPULabel
GPUUICorner.CornerRadius = UDim.new(0, 12)
 
PlayersInServer.Name = "PlayersInServer"
PlayersInServer.Parent = GameFrame
PlayersInServer.Position = UDim2.new(0.01, 0, 0.78, 0)
PlayersInServer.Size = UDim2.new(0.62, 0, 0.2, 0)
PlayersInServer.Font = Enum.Font.SourceSansBold
PlayersInServer.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
PlayersInServer.TextColor3 = Color3.fromRGB(255, 255, 255)
PlayersInServer.TextSize = 25
PlayersInServer.BackgroundTransparency = 0.8
 
PlayersInServerUICorner.Parent = PlayersInServer
PlayersInServerUICorner.CornerRadius = UDim.new(0, 12)
 
ServerSize.Name = "ServerSize"
ServerSize.Parent = GameFrame
ServerSize.Position = UDim2.new(0.64, 0, 0.78, 0)
ServerSize.Size = UDim2.new(0.35, 0, 0.2, 0)
ServerSize.Font = Enum.Font.SourceSansBold
ServerSize.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ServerSize.TextColor3 = Color3.fromRGB(255, 255, 255)
ServerSize.TextSize = 25
ServerSize.BackgroundTransparency = 0.8
 
ServerSizeUICorner.Parent = ServerSize
ServerSizeUICorner.CornerRadius = UDim.new(0, 12)
 
 
ServerLive.Name = "ServerLive"
ServerLive.Parent = GameFrame
ServerLive.Position = UDim2.new(0.01, 0, 0.52, 0)
ServerLive.Size = UDim2.new(0.35, 0, 0.2, 0)
ServerLive.Font = Enum.Font.SourceSansBold
ServerLive.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ServerLive.TextColor3 = Color3.fromRGB(255, 255, 255)
ServerLive.TextSize = 25
ServerLive.BackgroundTransparency = 0.8
ServerLive.TextScaled = true
ServerLive.TextWrapped = true
 
ServerLiveUICorner.Parent = ServerLive
ServerLiveUICorner.CornerRadius = UDim.new(0, 12)
 
Executor.Name = "Executor"
Executor.Parent = GameFrame
Executor.Position = UDim2.new(0.37, 0, 0.52, 0)
Executor.Size = UDim2.new(0.62, 0, 0.2, 0)
Executor.Font = Enum.Font.SourceSansBold
Executor.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Executor.TextColor3 = Color3.fromRGB(255, 255, 255)
Executor.TextSize = 25
Executor.BackgroundTransparency = 0.8
 
ExecutorUICorner.Parent = Executor
ExecutorUICorner.CornerRadius = UDim.new(0, 12)
 
spawn(function()
repeat
wait()
local ping = tonumber(game:GetService("Stats"):FindFirstChild("PerformanceStats").Ping:GetValue())
local gpu = tonumber(game:GetService("Stats"):FindFirstChild("PerformanceStats").GPU:GetValue())
local cpu = tonumber(game:GetService("Stats"):FindFirstChild("PerformanceStats").CPU:GetValue())
cpu = math.floor(cpu)
gpu = math.floor(gpu)
ping = math.floor(ping)
PingLabel.Text = "Ping: "..ping
CPULabel.Text = "CPU: "..cpu
GPULabel.Text = "GPU: "..gpu
PlayersInServer.Text = "Players: "..#game.Players:GetPlayers()
ServerSize.Text = "Server Size: "..game.Players.MaxPlayers
ServerLive.Text = "Server Live: "..convertToHMS(time())
Executor.Text = "Executor: "..identifyexecutor()
Clock.Text = os.date("%H:%M")
until 
PingLabel == nil
end)
 
 
SearchBox.Name = "SearchBox"
SearchBox.Parent = MainFrame
SearchBox.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
SearchBox.BackgroundTransparency = 0.5
SearchBox.Position = UDim2.new(-3.55, 0, -1.8, 0)
SearchBox.Size = UDim2.new(0, 855, 0, 26)
SearchBox.ClearTextOnFocus = false
SearchBox.Font = Enum.Font.SourceSansBold
SearchBox.PlaceholderText = "Tap to search"
SearchBox.Text = ""
SearchBox.TextColor3 = Color3.fromRGB(255, 255, 255)
SearchBox.TextTransparency = 0
SearchBox.TextScaled = true
SearchBox.TextSize = 14.000
SearchBox.TextWrapped = true
 
UICorner_3.CornerRadius = UDim.new(0, 12)
UICorner_3.Parent = SearchBox
 
ScriptListFrame.Name = "ScriptListFrame"
ScriptListFrame.Parent = MainFrame
ScriptListFrame.Active = true
ScriptListFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ScriptListFrame.BackgroundTransparency = 1
ScriptListFrame.BorderSizePixel = 0
ScriptListFrame.Position = UDim2.new(-3.8, 0, -1.5, 0)
ScriptListFrame.Size = UDim2.new(0, 1000, 0, 420)
ScriptListFrame.ZIndex = 2
ScriptListFrame.CanvasSize = UDim2.new(0, 0, 0, 0)
 
ScriptAuthor.Name = "ScriptAuthor"
ScriptAuthor.Parent = ScriptFrame
ScriptAuthor.BackgroundTransparency = 1
ScriptAuthor.Position = UDim2.new(0, 10, 0, 150)
ScriptAuthor.Size = UDim2.new(0, 280, 0, 30)
ScriptAuthor.Font = Enum.Font.SourceSansBold
ScriptAuthor.Text = "by ScriptAuthor"
ScriptAuthor.TextColor3 = Color3.fromRGB(192, 192, 192)
ScriptAuthor.TextSize = 14.000
ScriptAuthor.TextWrapped = true
ScriptAuthor.TextScaled = true
ScriptAuthor.TextXAlignment = Enum.TextXAlignment.Left
 
UIPadding.Parent = ScriptListFrame
UIPadding.PaddingBottom = UDim.new(0, 10)
UIPadding.PaddingLeft = UDim.new(0, 25)
UIPadding.PaddingRight = UDim.new(0, 25)
UIPadding.PaddingTop = UDim.new(0, 10)
 
Scripts.Name = "Scripts"
Scripts.Parent = ScriptListFrame
 
UIGridLayout.Parent = Scripts
UIGridLayout.SortOrder = Enum.SortOrder.LayoutOrder
UIGridLayout.CellPadding = UDim2.new(0, 20, 0, 20)
UIGridLayout.CellSize = UDim2.new(0, 855, 0, 400)
 
ScriptFrame.Name = "ScriptFrame"
ScriptFrame.Parent = Scripts
ScriptFrame.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
ScriptFrame.BackgroundTransparency = 0.5
ScriptFrame.Size = UDim2.new(0, 200, 0, 100)
ScriptFrame.Position = UDim2.new(1.5, 0, 0, 0)
ScriptFrame.Image = "rbxassetid://16050153732"
 
UICorner_6.CornerRadius = UDim.new(0, 12)
UICorner_6.Parent = ScriptFrame
 
ScriptTitle.Name = "ScriptTitle"
ScriptTitle.Parent = ScriptFrame
ScriptTitle.BackgroundTransparency = 1
ScriptTitle.Position = UDim2.new(0, 10, 0, 20)
ScriptTitle.Size = UDim2.new(0, 840, 0, 100)
ScriptTitle.Font = Enum.Font.SourceSansBold
ScriptTitle.Text = "Script Title"
ScriptTitle.TextColor3 = Color3.fromRGB(255, 255, 255)
ScriptTitle.TextScaled = true
ScriptTitle.TextSize = 14.000
ScriptTitle.TextWrapped = true
ScriptTitle.TextXAlignment = Enum.TextXAlignment.Left
 
ExecuteButtonBackground.Name = "ExecuteButtonBackground"
ExecuteButtonBackground.Parent = ScriptFrame
ExecuteButtonBackground.BackgroundColor3 = Color3.fromRGB(55, 55, 55)
ExecuteButtonBackground.Position = UDim2.new(0.0123, 0, 0.794, 0)
ExecuteButtonBackground.Size = UDim2.new(0, 205, 0, 55)
 
ExecuteButtonBackgroundUICorner.Parent = ExecuteButtonBackground
ExecuteButtonBackgroundUICorner.CornerRadius = UDim.new(0, 15)
 
ExecuteButton.Name = "ExecuteButton"
ExecuteButton.Parent = ScriptFrame
ExecuteButton.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
ExecuteButton.Position = UDim2.new(0.015, 0, 0.8, 0)
ExecuteButton.Size = UDim2.new(0, 200, 0, 50)
ExecuteButton.AutoButtonColor = false
ExecuteButton.Font = Enum.Font.SourceSansBold
ExecuteButton.Text = "Execute"
ExecuteButton.TextColor3 = Color3.fromRGB(255, 255, 255)
ExecuteButton.TextSize = 14.000
ExecuteButton.TextScaled = true
ExecuteButton.TextWrapped = true
 
UICorner_7.CornerRadius = UDim.new(0, 12)
UICorner_7.Parent = ExecuteButton
 
CopyLinkButtonBackground.Name = "CopyLinkButtonBackground"
CopyLinkButtonBackground.Parent = ScriptFrame
CopyLinkButtonBackground.BackgroundColor3 = Color3.fromRGB(55,55, 55)
CopyLinkButtonBackground.Position = UDim2.new(0.2569, 0, 0.794, 0)
CopyLinkButtonBackground.Size = UDim2.new(0, 205, 0, 55)
 
CopyLinkButtonBackgroundUICorner.Parent = CopyLinkButtonBackground
CopyLinkButtonBackgroundUICorner.CornerRadius = UDim.new(0, 15)
 
CopyLinkButton.Name = "CopyLinkButton"
CopyLinkButton.Parent = ScriptFrame
CopyLinkButton.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
CopyLinkButton.Position = UDim2.new(0.26, 0, 0.8, 0)
CopyLinkButton.Size = UDim2.new(0, 200, 0, 50)
CopyLinkButton.AutoButtonColor = false
CopyLinkButton.Font = Enum.Font.SourceSansBold
CopyLinkButton.Text = "Copy Link"
CopyLinkButton.TextColor3 = Color3.fromRGB(255, 255, 255)
CopyLinkButton.TextSize = 14.000
CopyLinkButton.TextScaled = true
CopyLinkButton.TextWrapped = true
 
CopyLinkButtonUICorner.CornerRadius = UDim.new(0, 12)
CopyLinkButtonUICorner.Parent = CopyLinkButton
 
 
CopyScriptBackground.Name = "CopyScriptBackground"
CopyScriptBackground.Parent = ScriptFrame
CopyScriptBackground.BackgroundColor3 = Color3.fromRGB(55 ,55, 55)
CopyScriptBackground.Position = UDim2.new(0.5022, 0, 0.794, 0)
CopyScriptBackground.Size = UDim2.new(0, 205, 0, 55)
 
CopyScriptBackgroundUICorner.Parent = CopyScriptBackground
CopyScriptBackgroundUICorner.CornerRadius = UDim.new(0, 15)
 
 
CopyScriptButton.Name = "CopyScriptButton"
CopyScriptButton.Parent = ScriptFrame
CopyScriptButton.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
CopyScriptButton.Position = UDim2.new(0.505, 0, 0.8, 0)
CopyScriptButton.Size = UDim2.new(0, 200, 0, 50)
CopyScriptButton.AutoButtonColor = false
CopyScriptButton.Font = Enum.Font.SourceSansBold
CopyScriptButton.Text = "Copy Script"
CopyScriptButton.TextColor3 = Color3.fromRGB(255, 255, 255)
CopyScriptButton.TextSize = 14.000
CopyScriptButton.TextScaled = true
CopyScriptButton.TextWrapped = true
 
CopyScriptButtonUICorner.CornerRadius = UDim.new(0, 12)
CopyScriptButtonUICorner.Parent = CopyScriptButton
 
 
OpenDescriptionBackground.Name = "OpenDescriptionBackground"
OpenDescriptionBackground.Parent = ScriptFrame
OpenDescriptionBackground.BackgroundColor3 = Color3.fromRGB(55,55, 55)
OpenDescriptionBackground.Position = UDim2.new(0.747, 0, 0.794, 0)
OpenDescriptionBackground.Size = UDim2.new(0, 205, 0, 55)
 
OpenDescriptionBackgroundUICorner.Parent = OpenDescriptionBackground
OpenDescriptionBackgroundUICorner.CornerRadius = UDim.new(0, 15)
 
 
OpenDescriptionButton.Name = "OpenDescriptionButton"
OpenDescriptionButton.Parent = ScriptFrame
OpenDescriptionButton.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
OpenDescriptionButton.Position = UDim2.new(0.75, 0, 0.8, 0)
OpenDescriptionButton.Size = UDim2.new(0, 200, 0, 50)
OpenDescriptionButton.AutoButtonColor = false
OpenDescriptionButton.Font = Enum.Font.SourceSansBold
OpenDescriptionButton.Text = "Description"
OpenDescriptionButton.TextColor3 = Color3.fromRGB(255, 255, 255)
OpenDescriptionButton.TextSize = 14.000
OpenDescriptionButton.TextScaled = true
OpenDescriptionButton.TextWrapped = true
 
OpenDescriptionButtonUICorner.CornerRadius = UDim.new(0, 12)
OpenDescriptionButtonUICorner.Parent = OpenDescriptionButton
 
ScriptGame.Name = "ScriptGame"
ScriptGame.Parent = ScriptFrame
ScriptGame.BackgroundTransparency = 1
ScriptGame.Position = UDim2.new(0, 10, 0, 220)
ScriptGame.Size = UDim2.new(0, 280, 0, 30)
ScriptGame.Font = Enum.Font.SourceSansBold
ScriptGame.Text = "Game"
ScriptGame.TextColor3 = Color3.fromRGB(192, 192, 192)
ScriptGame.TextSize = 14
ScriptGame.TextWrapped = true
ScriptGame.TextScaled = true
ScriptGame.TextXAlignment = Enum.TextXAlignment.Left
 
VerifiedScriptFrame.Name = "VerifiedScriptFrame"
VerifiedScriptFrame.Parent = Scripts
VerifiedScriptFrame.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
VerifiedScriptFrame.Size = UDim2.new(0, 300, 0, 150)
VerifiedScriptFrame.Image = "rbxassetid://16050153732"
 
UICorner_9.CornerRadius = UDim.new(0, 12)
UICorner_9.Parent = VerifiedScriptFrame
 
ScriptTitle_2.Name = "ScriptTitle"
ScriptTitle_2.Parent = VerifiedScriptFrame
ScriptTitle_2.BackgroundTransparency = 1
ScriptTitle_2.Position = UDim2.new(0, 10, 0, 20)
ScriptTitle_2.Size = UDim2.new(0, 840, 0, 100)
ScriptTitle_2.Font = Enum.Font.SourceSansBold
ScriptTitle_2.Text = "Script Title"
ScriptTitle_2.TextColor3 = Color3.fromRGB(255, 255, 255)
ScriptTitle_2.TextScaled = true
ScriptTitle_2.TextSize = 14.000
ScriptTitle_2.TextWrapped = true
ScriptTitle_2.TextXAlignment = Enum.TextXAlignment.Left
 
VerifiedIcon.Name = "VerifiedIcon"
VerifiedIcon.Parent = VerifiedScriptFrame
VerifiedIcon.BackgroundTransparency = 0
VerifiedIcon.Position = UDim2.new(0.75, 0, 0.35, 0)
VerifiedIcon.Size = UDim2.new(0, 215, 0, 150)
VerifiedIcon.Image = "rbxassetid://15621211889"
VerifiedIcon.BackgroundTransparency = 1
 
ExecuteButtonBackground_2.Name = "ExecuteButtonBackground"
ExecuteButtonBackground_2.Parent = VerifiedScriptFrame
ExecuteButtonBackground_2.BackgroundColor3 = Color3.fromRGB(55,55, 55)
ExecuteButtonBackground_2.Position = UDim2.new(0.0123, 0, 0.794, 0)
ExecuteButtonBackground_2.Size = UDim2.new(0, 205, 0, 55)
 
ExecuteButtonBackgroundUICorner_2.Parent = ExecuteButtonBackground_2
ExecuteButtonBackgroundUICorner_2.CornerRadius = UDim.new(0, 15)
 
ExecuteButton_2.Name = "ExecuteButton"
ExecuteButton_2.Parent = VerifiedScriptFrame
ExecuteButton_2.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
ExecuteButton_2.Position = UDim2.new(0.015, 0, 0.8, 0)
ExecuteButton_2.Size = UDim2.new(0, 200, 0, 50)
ExecuteButton_2.AutoButtonColor = false
ExecuteButton_2.Font = Enum.Font.SourceSansBold
ExecuteButton_2.Text = "Execute"
ExecuteButton_2.TextColor3 = Color3.fromRGB(255, 255, 255)
ExecuteButton_2.TextSize = 14.000
ExecuteButton_2.TextScaled = true
ExecuteButton_2.TextWrapped = true
 
UICorner_10.CornerRadius = UDim.new(0, 12)
UICorner_10.Parent = ExecuteButton_2
 
CopyLinkButtonBackground_2.Name = "CopyLinkButtonBackground"
CopyLinkButtonBackground_2.Parent = VerifiedScriptFrame
CopyLinkButtonBackground_2.BackgroundColor3 = Color3.fromRGB(55,55, 55)
CopyLinkButtonBackground_2.Position = UDim2.new(0.2569, 0, 0.794, 0)
CopyLinkButtonBackground_2.Size = UDim2.new(0, 205, 0, 55)
 
CopyLinkButtonBackgroundUICorner_2.Parent = CopyLinkButtonBackground_2
CopyLinkButtonBackgroundUICorner_2.CornerRadius = UDim.new(0, 15)
 
CopyLinkButton_2.Name = "CopyLinkButton"
CopyLinkButton_2.Parent = VerifiedScriptFrame
CopyLinkButton_2.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
CopyLinkButton_2.Position = UDim2.new(0.26, 0, 0.8, 0)
CopyLinkButton_2.Size = UDim2.new(0, 200, 0, 50)
CopyLinkButton_2.AutoButtonColor = false
CopyLinkButton_2.Font = Enum.Font.SourceSansBold
CopyLinkButton_2.Text = "Copy Link"
CopyLinkButton_2.TextColor3 = Color3.fromRGB(255, 255, 255)
CopyLinkButton_2.TextSize = 14.000
CopyLinkButton_2.TextScaled = true
CopyLinkButton_2.TextWrapped = true
 
CopyLinkButtonUICorner_2.CornerRadius = UDim.new(0, 12)
CopyLinkButtonUICorner_2.Parent = CopyLinkButton_2
 
 
CopyScriptBackground_2.Name = "CopyScriptBackground"
CopyScriptBackground_2.Parent = VerifiedScriptFrame
CopyScriptBackground_2.BackgroundColor3 = Color3.fromRGB(55,55, 55)
CopyScriptBackground_2.Position = UDim2.new(0.5022, 0, 0.794, 0)
CopyScriptBackground_2.Size = UDim2.new(0, 205, 0, 55)
 
CopyScriptBackgroundUICorner_2.Parent = CopyScriptBackground_2
CopyScriptBackgroundUICorner_2.CornerRadius = UDim.new(0, 15)
 
 
CopyScriptButton_2.Name = "CopyScriptButton"
CopyScriptButton_2.Parent = VerifiedScriptFrame
CopyScriptButton_2.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
CopyScriptButton_2.Position = UDim2.new(0.505, 0, 0.8, 0)
CopyScriptButton_2.Size = UDim2.new(0, 200, 0, 50)
CopyScriptButton_2.AutoButtonColor = false
CopyScriptButton_2.Font = Enum.Font.SourceSansBold
CopyScriptButton_2.Text = "Copy Script"
CopyScriptButton_2.TextColor3 = Color3.fromRGB(255, 255, 255)
CopyScriptButton_2.TextSize = 14.000
CopyScriptButton_2.TextScaled = true
CopyScriptButton_2.TextWrapped = true
 
CopyScriptButtonUICorner_2.CornerRadius = UDim.new(0, 12)
CopyScriptButtonUICorner_2.Parent = CopyScriptButton_2

OpenDescriptionBackground_2.Name = "OpenDescriptionBackground"
OpenDescriptionBackground_2.Parent = VerifiedScriptFrame
OpenDescriptionBackground_2.BackgroundColor3 = Color3.fromRGB(55,55, 55)
OpenDescriptionBackground_2.Position = UDim2.new(0.747, 0, 0.794, 0)
OpenDescriptionBackground_2.Size = UDim2.new(0, 205, 0, 55)
 
OpenDescriptionBackgroundUICorner_2.Parent = OpenDescriptionBackground_2
OpenDescriptionBackgroundUICorner_2.CornerRadius = UDim.new(0, 15)

OpenDescriptionButton_2.Name = "OpenDescriptionButton"
OpenDescriptionButton_2.Parent = VerifiedScriptFrame
OpenDescriptionButton_2.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
OpenDescriptionButton_2.Position = UDim2.new(0.75, 0, 0.8, 0)
OpenDescriptionButton_2.Size = UDim2.new(0, 200, 0, 50)
OpenDescriptionButton_2.AutoButtonColor = false
OpenDescriptionButton_2.Font = Enum.Font.SourceSansBold
OpenDescriptionButton_2.Text = "Description"
OpenDescriptionButton_2.TextColor3 = Color3.fromRGB(255, 255, 255)
OpenDescriptionButton_2.TextSize = 14.000
OpenDescriptionButton_2.TextScaled = true
OpenDescriptionButton_2.TextWrapped = true
 
OpenDescriptionButtonUICorner_2.CornerRadius = UDim.new(0, 12)
OpenDescriptionButtonUICorner_2.Parent = OpenDescriptionButton_2
 
ScriptAuthor_2.Name = "ScriptAuthor"
ScriptAuthor_2.Parent = VerifiedScriptFrame
ScriptAuthor_2.BackgroundTransparency = 1
ScriptAuthor_2.Position = UDim2.new(0, 10, 0, 150)
ScriptAuthor_2.Size = UDim2.new(0, 280, 0, 30)
ScriptAuthor_2.Font = Enum.Font.SourceSansBold
ScriptAuthor_2.Text = "by ScriptAuthor"
ScriptAuthor_2.TextColor3 = Color3.fromRGB(192, 192, 192)
ScriptAuthor_2.TextSize = 14.000
ScriptAuthor_2.TextWrapped = true
ScriptAuthor_2.TextScaled = true
ScriptAuthor_2.TextXAlignment = Enum.TextXAlignment.Left
 
ScriptGame_2.Name = "ScriptGame"
ScriptGame_2.Parent = VerifiedScriptFrame
ScriptGame_2.BackgroundTransparency = 1
ScriptGame_2.Position = UDim2.new(0, 10, 0, 220)
ScriptGame_2.Size = UDim2.new(0, 280, 0, 30)
ScriptGame_2.Font = Enum.Font.Code
ScriptGame_2.Text = "Game"
ScriptGame_2.TextColor3 = Color3.fromRGB(192, 192, 192)
ScriptGame_2.TextSize = 14.000
ScriptGame_2.TextWrapped = true
ScriptGame_2.TextScaled = true
ScriptGame_2.TextXAlignment = Enum.TextXAlignment.Left
 
DescriptionScript.Name = "DescriptionScript"
DescriptionScript.Parent = MainFrame
DescriptionScript.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
DescriptionScript.Position = UDim2.new(-3.55, 0, -1.4, 0)
DescriptionScript.Size = UDim2.new(0, 855, 0, 400)
DescriptionScript.AutoButtonColor = false
DescriptionScript.BackgroundTransparency = 0.2
DescriptionScript.Font = Enum.Font.SourceSansBold
DescriptionScript.Text = "Description"
DescriptionScript.TextColor3 = Color3.fromRGB(255, 255, 255)
DescriptionScript.TextSize = 14.000
DescriptionScript.TextScaled = true
DescriptionScript.TextWrapped = true
 
DescriptionScriptUICorner.CornerRadius = UDim.new(0, 12)
DescriptionScriptUICorner.Parent = DescriptionScript
 
DescriptionScript.Visible = false

ReloadBackgroundButton.Name = "ReloadBackgroundButton"
ReloadBackgroundButton.Parent = MainFrame
ReloadBackgroundButton.AnchorPoint = Vector2.new(0.5, 0.5)
ReloadBackgroundButton.BackgroundColor3 = Color3.fromRGB(55, 55, 55)
ReloadBackgroundButton.Position = UDim2.new(-3.9, 0, 2.3, 0)
ReloadBackgroundButton.Size = UDim2.new(0, 46, 0, 46)
 
ReloadBackgroundButtonUICorner.CornerRadius = UDim.new(0, 15)
ReloadBackgroundButtonUICorner.Parent = ReloadBackgroundButton
 
ReloadButton.Name = "ReloadButton"
ReloadButton.Parent = ReloadBackgroundButton
ReloadButton.AnchorPoint = Vector2.new(0.5, 0.5)
ReloadButton.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
ReloadButton.Position = UDim2.new(0.5, 0, 0.5, 0)
ReloadButton.Size = UDim2.new(0, 41, 0, 41)
ReloadButton.Image = "rbxassetid://16422858330"
ReloadButton.AutoButtonColor = false
 
ReloadButtonUICorner.CornerRadius = UDim.new(0, 12)
ReloadButtonUICorner.Parent = ReloadButton

HistoryBackgroundButton.Name = "HistoryBackgroundButton"
HistoryBackgroundButton.Parent = MainFrame
HistoryBackgroundButton.AnchorPoint = Vector2.new(0.5, 0.5)
HistoryBackgroundButton.BackgroundColor3 = Color3.fromRGB(55, 55, 55)
HistoryBackgroundButton.Position = UDim2.new(-3.9, 0, 1.8, 0)
HistoryBackgroundButton.Size = UDim2.new(0, 46, 0, 46)
 
HistoryBackgroundButtonUICorner.CornerRadius = UDim.new(0, 15)
HistoryBackgroundButtonUICorner.Parent = HistoryBackgroundButton
 
HistoryButton.Name = "HistoryButton"
HistoryButton.Parent = HistoryBackgroundButton
HistoryButton.AnchorPoint = Vector2.new(0.5, 0.5)
HistoryButton.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
HistoryButton.Position = UDim2.new(0.5, 0, 0.5, 0)
HistoryButton.Size = UDim2.new(0, 41, 0, 41)
HistoryButton.Image = "rbxassetid://16428511381"
HistoryButton.AutoButtonColor = false
 
HistoryButtonUICorner.CornerRadius = UDim.new(0, 12)
HistoryButtonUICorner.Parent = HistoryButton

ClearAndSearchBackground.Name = "ClearAndSearchBackground"
ClearAndSearchBackground.Parent = MainFrame
ClearAndSearchBackground.AnchorPoint = Vector2.new(0.5, 0.5)
ClearAndSearchBackground.BackgroundColor3 = Color3.fromRGB(55, 55, 55)
ClearAndSearchBackground.Position = UDim2.new(-3.9, 0, -1.2, 0)
ClearAndSearchBackground.Size = UDim2.new(0, 46, 0, 46)
 
ClearAndSearchBackgroundUICorner.CornerRadius = UDim.new(0, 15)
ClearAndSearchBackgroundUICorner.Parent = ClearAndSearchBackground
 
ClearAndSearch.Name = "ClearAndSearch"
ClearAndSearch.Parent = ClearAndSearchBackground
ClearAndSearch.AnchorPoint = Vector2.new(0.5, 0.5)
ClearAndSearch.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
ClearAndSearch.Position = UDim2.new(0.5, 0, 0.5, 0)
ClearAndSearch.Size = UDim2.new(0, 41, 0, 41)
ClearAndSearch.Image = "rbxassetid://16449084806"
ClearAndSearch.AutoButtonColor = false
 
ClearAndSearchUICorner.CornerRadius = UDim.new(0, 12)
ClearAndSearchUICorner.Parent = ClearAndSearch

BackgroundConsole.Name = "BackgroundConsole"
BackgroundConsole.Parent = UIGui
BackgroundConsole.AnchorPoint = Vector2.new(0.5, 0.5)
BackgroundConsole.BackgroundColor3 = Color3.fromRGB(55, 55, 55)
BackgroundConsole.Position = UDim2.new(0.525, 0, -1, 0)
BackgroundConsole.Size = UDim2.new(0, 860, 0, 405)
 
BackgroundConsoleUICorner.CornerRadius = UDim.new(0, 15)
BackgroundConsoleUICorner.Parent = BackgroundConsole
 
BackgroundImage.Name = "BackgroundImage"
BackgroundImage.Parent = BackgroundConsole
BackgroundImage.AnchorPoint = Vector2.new(0.5, 0.5)
BackgroundImage.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
BackgroundImage.Position = UDim2.new(0.5, 0, 0.5, 0)
BackgroundImage.Size = UDim2.new(0, 855, 0, 400)
BackgroundImage.Image = "rbxassetid://16068028120"
 
BackgroundImageUICorner.CornerRadius = UDim.new(0, 12)
BackgroundImageUICorner.Parent = BackgroundImage
 
ConsoleOutput.Name = "ConsoleOutput"
ConsoleOutput.Parent = BackgroundImage
ConsoleOutput.AnchorPoint = Vector2.new(0.5, 0.5)
ConsoleOutput.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
ConsoleOutput.BackgroundTransparency = 0.2
ConsoleOutput.Position = UDim2.new(0.5, 0, 0.5, 0)
ConsoleOutput.Size = UDim2.new(0, 855, 0, 400)
ConsoleOutput.Text = "Notifications, warnings and script errors will be displayed here to simplify working with them."
ConsoleOutput.TextColor3 = Color3.fromRGB(255, 255, 255)
ConsoleOutput.TextScaled = false
ConsoleOutput.Font = Enum.Font.Code
ConsoleOutput.TextSize = 14
ConsoleOutput.TextWrapped = true
ConsoleOutput.TextXAlignment = Enum.TextXAlignment.Left
ConsoleOutput.TextYAlignment = Enum.TextYAlignment.Top
 
ConsoleOutputUICorner.CornerRadius = UDim.new(0, 12)
ConsoleOutputUICorner.Parent = ConsoleOutput
 
EditorBackground.Name = "EditorBackground"
EditorBackground.Parent = UIGui
EditorBackground.AnchorPoint = Vector2.new(0.5, 0.5)
EditorBackground.BackgroundColor3 = Color3.fromRGB(55, 55, 55)
EditorBackground.Position = UDim2.new(0.525, 0, -1, 0)
EditorBackground.Size = UDim2.new(0, 860, 0, 405)
 
EditorBackgroundUICorner.CornerRadius = UDim.new(0, 15)
EditorBackgroundUICorner.Parent = EditorBackground
 
EditorMainFrame.Name = "EditorMainFrame"
EditorMainFrame.Parent = EditorBackground
EditorMainFrame.AnchorPoint = Vector2.new(0.5, 0.5)
EditorMainFrame.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
EditorMainFrame.Position = UDim2.new(0.5, 0, 0.5, 0)
EditorMainFrame.Size = UDim2.new(0, 855, 0, 400)
EditorMainFrame.Image = "rbxassetid://16109043024"
 
EditorMainFrameUICorner.CornerRadius = UDim.new(0, 12)
EditorMainFrameUICorner.Parent = EditorMainFrame
 
EditorTextBox.Name = "EditorTextBox"
EditorTextBox.Parent = EditorMainFrame
EditorTextBox.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
EditorTextBox.BackgroundTransparency = 0.2
EditorTextBox.Position = UDim2.new(0.02, 0, 0.04, 0)
EditorTextBox.Size = UDim2.new(0, 820, 0, 310)
EditorTextBox.ClearTextOnFocus = false
EditorTextBox.Font = Enum.Font.SourceSansBold
EditorTextBox.PlaceholderText = "print(\"Hello World\")"
EditorTextBox.Text = ""
EditorTextBox.TextColor3 = Color3.fromRGB(255, 255, 255)
EditorTextBox.TextTransparency = 0
EditorTextBox.TextSize = 14.000
EditorTextBox.TextWrapped = true
EditorTextBox.TextXAlignment = Enum.TextXAlignment.Left
EditorTextBox.TextYAlignment = Enum.TextYAlignment.Top
 
EditorTextBoxUICorner.CornerRadius = UDim.new(0, 12)
EditorTextBoxUICorner.Parent = EditorTextBox
 
ExecuteButtonBackground_3.Name = "ExecuteButtonBackground_3"
ExecuteButtonBackground_3.Parent = EditorMainFrame
ExecuteButtonBackground_3.BackgroundColor3 = Color3.fromRGB(55, 55, 55)
ExecuteButtonBackground_3.Position = UDim2.new(0.02, 0, 0.85, 0)
ExecuteButtonBackground_3.Size = UDim2.new(0, 195, 0, 55)
 
ExecuteButtonBackgroundUICorner_3.Parent = ExecuteButtonBackground_3
ExecuteButtonBackgroundUICorner_3.CornerRadius = UDim.new(0, 15)
 
ClearButtonBackground.Name = "ClearButtonBackground"
ClearButtonBackground.Parent = EditorMainFrame
ClearButtonBackground.BackgroundColor3 = Color3.fromRGB(55, 55, 55)
ClearButtonBackground.Position = UDim2.new(0.75, 0, 0.85, 0)
ClearButtonBackground.Size = UDim2.new(0, 195, 0, 55)
 
ClearButtonBackgroundUICorner.Parent = ClearButtonBackground
ClearButtonBackgroundUICorner.CornerRadius = UDim.new(0, 15)
 
SaveButtonBackground.Name = "SaveButtonBackground"
SaveButtonBackground.Parent = EditorMainFrame
SaveButtonBackground.BackgroundColor3 = Color3.fromRGB(55, 55, 55)
SaveButtonBackground.Position = UDim2.new(0.506, 0, 0.85, 0)
SaveButtonBackground.Size = UDim2.new(0, 195, 0, 55)
 
SaveButtonBackgroundUICorner.Parent = SaveButtonBackground
SaveButtonBackgroundUICorner.CornerRadius = UDim.new(0, 15)
 
CopyButtonBackground.Name = "CopyButtonBackground"
CopyButtonBackground.Parent = EditorMainFrame
CopyButtonBackground.BackgroundColor3 = Color3.fromRGB(55, 55, 55)
CopyButtonBackground.Position = UDim2.new(0.264, 0, 0.85, 0)
CopyButtonBackground.Size = UDim2.new(0, 195, 0, 55)
 
CopyButtonBackgroundUICorner.Parent = CopyButtonBackground
CopyButtonBackgroundUICorner.CornerRadius = UDim.new(0, 15)
 
ExecuteButton_3.Name = "ExecuteButton_3"
ExecuteButton_3.Parent = ExecuteButtonBackground_3
ExecuteButton_3.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
ExecuteButton_3.Position = UDim2.new(0.013, 0, 0.05, 0)
ExecuteButton_3.Size = UDim2.new(0, 190, 0, 50)
ExecuteButton_3.AutoButtonColor = false
ExecuteButton_3.Font = Enum.Font.SourceSansBold
ExecuteButton_3.Text = "Execute"
ExecuteButton_3.TextColor3 = Color3.fromRGB(255, 255, 255)
ExecuteButton_3.TextSize = 14.000
ExecuteButton_3.TextScaled = true
ExecuteButton_3.TextWrapped = true
 
ExecuteButtonUICorner_3.CornerRadius = UDim.new(0, 12)
ExecuteButtonUICorner_3.Parent = ExecuteButton_3
 
SaveButton.Name = "SaveButton"
SaveButton.Parent = SaveButtonBackground
SaveButton.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
SaveButton.Position = UDim2.new(0.013, 0, 0.05, 0)
SaveButton.Size = UDim2.new(0, 190, 0, 50)
SaveButton.AutoButtonColor = false
SaveButton.Font = Enum.Font.SourceSansBold
SaveButton.Text = "Save"
SaveButton.TextColor3 = Color3.fromRGB(255, 255, 255)
SaveButton.TextSize = 14.000
SaveButton.TextScaled = true
SaveButton.TextWrapped = true
 
SaveButtonUICorner.CornerRadius = UDim.new(0, 12)
SaveButtonUICorner.Parent = SaveButton
 
CopyButton.Name = "CopyButton"
CopyButton.Parent = CopyButtonBackground
CopyButton.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
CopyButton.Position = UDim2.new(0.013, 0, 0.05, 0)
CopyButton.Size = UDim2.new(0, 190, 0, 50)
CopyButton.AutoButtonColor = false
CopyButton.Font = Enum.Font.SourceSansBold
CopyButton.Text = "Copy"
CopyButton.TextColor3 = Color3.fromRGB(255, 255, 255)
CopyButton.TextSize = 14.000
CopyButton.TextScaled = true
CopyButton.TextWrapped = true
 
CopyButtonUICorner.CornerRadius = UDim.new(0, 12)
CopyButtonUICorner.Parent = CopyButton
 
ClearButton.Name = "ClearButton"
ClearButton.Parent = ClearButtonBackground
ClearButton.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
ClearButton.Position = UDim2.new(0.013, 0, 0.05, 0)
ClearButton.Size = UDim2.new(0, 190, 0, 50)
ClearButton.AutoButtonColor = false
ClearButton.Font = Enum.Font.SourceSansBold
ClearButton.Text = "Clear"
ClearButton.TextColor3 = Color3.fromRGB(255, 255, 255)
ClearButton.TextSize = 14.000
ClearButton.TextScaled = true
ClearButton.TextWrapped = true
 
ClearButtonUICorner.CornerRadius = UDim.new(0, 12)
ClearButtonUICorner.Parent = ClearButton

ClearButton_2Background.Name = "ClearButton_2Background"
ClearButton_2Background.Parent = BackgroundConsole
ClearButton_2Background.AnchorPoint = Vector2.new(0.5, 0.5)
ClearButton_2Background.BackgroundColor3 = Color3.fromRGB(55, 55, 55)
ClearButton_2Background.Position = UDim2.new(-0.04, 0, 0.945, 0)
ClearButton_2Background.Size = UDim2.new(0, 46, 0, 46)
 
ClearButton_2BackgroundUICorner.CornerRadius = UDim.new(0, 15)
ClearButton_2BackgroundUICorner.Parent = ClearButton_2Background
 
ClearButton_2.Name = "ClearButton_2"
ClearButton_2.Parent = ClearButton_2Background
ClearButton_2.AnchorPoint = Vector2.new(0.5, 0.5)
ClearButton_2.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
ClearButton_2.Position = UDim2.new(0.5, 0, 0.5, 0)
ClearButton_2.Size = UDim2.new(0, 41, 0, 41)
ClearButton_2.Image = "rbxassetid://16477707611"
ClearButton_2.AutoButtonColor = false
 
ClearButton_2UICorner.CornerRadius = UDim.new(0, 12)
ClearButton_2UICorner.Parent = ClearButton_2

SondFrameBackground.Name = "SondFrameBackground"
SondFrameBackground.Parent = UIGui
SondFrameBackground.AnchorPoint = Vector2.new(0.5, 0.5)
SondFrameBackground.BackgroundColor3 = Color3.fromRGB(55, 55, 55)
SondFrameBackground.Position = UDim2.new(0.5, 0, -1, 0)
SondFrameBackground.Size = UDim2.new(0, 350, 0, 400)
 
SondFrameBackgroundUICorner.CornerRadius = UDim.new(0, 15)
SondFrameBackgroundUICorner.Parent = SondFrameBackground
 
SondFrame.Name = "SondFrame"
SondFrame.Parent = SondFrameBackground
SondFrame.AnchorPoint = Vector2.new(0.5, 0.5)
SondFrame.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
SondFrame.Position = UDim2.new(0.5, 0, 0.5, 0)
SondFrame.Size = UDim2.new(0, 345, 0, 395)
SondFrame.Image = "rbxassetid://16139850662"
 
SondFrameUICorner.CornerRadius = UDim.new(0, 15)
SondFrameUICorner.Parent = SondFrame
 
MainSondFrame.Name = "MainSondFrame"
MainSondFrame.Parent = SondFrame
MainSondFrame.BackgroundTransparency = 0.4
MainSondFrame.AnchorPoint = Vector2.new(0.5, 0.5)
MainSondFrame.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
MainSondFrame.Position = UDim2.new(0.5, 0, 0.5, 0)
MainSondFrame.Size = UDim2.new(0, 345, 0, 395)
 
MainSondFrameUICorner.CornerRadius = UDim.new(0, 15)
MainSondFrameUICorner.Parent = MainSondFrame
 
SoundTextBox.Name = "SoundTextBox"
SoundTextBox.Parent = MainSondFrame
SoundTextBox.BackgroundColor3 = Color3.fromRGB(55, 55, 55)
SoundTextBox.BackgroundTransparency = 0.4
SoundTextBox.Position = UDim2.new(0.0055, 0, 0.01, 0)
SoundTextBox.Size = UDim2.new(0, 340, 0, 25)
SoundTextBox.ClearTextOnFocus = false
SoundTextBox.Font = Enum.Font.SourceSansBold
SoundTextBox.PlaceholderText = "Sound Id here"
SoundTextBox.Text = ""
SoundTextBox.TextColor3 = Color3.fromRGB(255, 255, 255)
SoundTextBox.TextTransparency = 0
SoundTextBox.TextScaled = true
SoundTextBox.TextSize = 14.000
SoundTextBox.TextWrapped = true
 
SoundTextBoxUICorner.CornerRadius = UDim.new(0, 15)
SoundTextBoxUICorner.Parent = SoundTextBox
 
Stop_PlayButtonBackground.Name = "Stop_PlayButtonBackground"
Stop_PlayButtonBackground.Parent = MainSondFrame
Stop_PlayButtonBackground.AnchorPoint = Vector2.new(0.5, 0.5)
Stop_PlayButtonBackground.BackgroundColor3 = Color3.fromRGB(55, 55, 55)
Stop_PlayButtonBackground.Position = UDim2.new(0.5, 0, 0.5, 0)
Stop_PlayButtonBackground.Size = UDim2.new(0, 105, 0, 105)
 
Stop_PlayButtonBackgroundUICorner.CornerRadius = UDim.new(1, 0)
Stop_PlayButtonBackgroundUICorner.Parent = Stop_PlayButtonBackground
 
Stop_PlayButtonBackground_2.Name = "Stop_PlayButtonBackground_2"
Stop_PlayButtonBackground_2.Parent = Stop_PlayButtonBackground
Stop_PlayButtonBackground_2.AnchorPoint = Vector2.new(0.5, 0.5)
Stop_PlayButtonBackground_2.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Stop_PlayButtonBackground_2.Position = UDim2.new(0.5, 0, 0.5, 0)
Stop_PlayButtonBackground_2.Size = UDim2.new(0, 100, 0, 100)
 
Stop_PlayButtonBackgroundUICorner_2.CornerRadius = UDim.new(1, 0)
Stop_PlayButtonBackgroundUICorner_2.Parent = Stop_PlayButtonBackground_2
 
Stop_PlayButton.Name = "Stop_PlayButton"
Stop_PlayButton.Parent = Stop_PlayButtonBackground_2
Stop_PlayButton.AnchorPoint = Vector2.new(0.5, 0.5)
Stop_PlayButton.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Stop_PlayButton.Position = UDim2.new(0.6, 0, 0.5, 0)
Stop_PlayButton.Size = UDim2.new(0, 80, 0, 80)
Stop_PlayButton.BackgroundTransparency = 1
Stop_PlayButton.Image = "rbxassetid://16139639068"
 
AudioName.Name = "AudioName"
AudioName.Parent = MainSondFrame
AudioName.BackgroundTransparency = 1
AudioName.Position = UDim2.new(0.0055, 0, 0.1, 0)
AudioName.Size = UDim2.new(0, 340, 0, 25)
AudioName.Font = Enum.Font.SourceSansBold
AudioName.Text = ""
AudioName.TextColor3 = Color3.fromRGB(192, 192, 192)
AudioName.TextScaled = true
AudioName.TextSize = 14.000
AudioName.TextWrapped = true
AudioName.TextXAlignment = Enum.TextXAlignment.Left
 
SaveButtonBackground_2.Name = "SaveButtonBackground_2"
SaveButtonBackground_2.Parent = MainSondFrame
SaveButtonBackground_2.AnchorPoint = Vector2.new(0.5, 0.5)
SaveButtonBackground_2.BackgroundColor3 = Color3.fromRGB(55, 55, 55)
SaveButtonBackground_2.Position = UDim2.new(0.2, 0, 0.5, 0)
SaveButtonBackground_2.Size = UDim2.new(0, 55, 0, 55)
 
SaveButtonBackgroundUICorner_2.CornerRadius = UDim.new(1, 0)
SaveButtonBackgroundUICorner_2.Parent = SaveButtonBackground_2
 
SaveButton_2.Name = "SaveButton_2"
SaveButton_2.Parent = SaveButtonBackground_2
SaveButton_2.AnchorPoint = Vector2.new(0.5, 0.5)
SaveButton_2.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
SaveButton_2.Position = UDim2.new(0.5, 0, 0.5, 0)
SaveButton_2.Size = UDim2.new(0, 50, 0, 50)
SaveButton_2.Image = "rbxassetid://16139574980"
SaveButton_2.AutoButtonColor = false
 
SaveButtonUICorner_2.CornerRadius = UDim.new(1, 0)
SaveButtonUICorner_2.Parent = SaveButton_2
 
PlaylistButtonBackground.Name = "PlaylistButtonBackground"
PlaylistButtonBackground.Parent = MainSondFrame
PlaylistButtonBackground.AnchorPoint = Vector2.new(0.5, 0.5)
PlaylistButtonBackground.BackgroundColor3 = Color3.fromRGB(55, 55, 55)
PlaylistButtonBackground.Position = UDim2.new(0.8, 0, 0.5, 0)
PlaylistButtonBackground.Size = UDim2.new(0, 55, 0, 55)
 
PlaylistButtonBackgroundUICorner.CornerRadius = UDim.new(1, 0)
PlaylistButtonBackgroundUICorner.Parent = PlaylistButtonBackground
 
PlaylistButtonBackground_2.Name = "PlaylistButtonBackground_2"
PlaylistButtonBackground_2.Parent = PlaylistButtonBackground
PlaylistButtonBackground_2.AnchorPoint = Vector2.new(0.5, 0.5)
PlaylistButtonBackground_2.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
PlaylistButtonBackground_2.Position = UDim2.new(0.5, 0, 0.5, 0)
PlaylistButtonBackground_2.Size = UDim2.new(0, 50, 0, 50)
 
PlaylistButtonBackgroundUICorner_2.CornerRadius = UDim.new(1, 0)
PlaylistButtonBackgroundUICorner_2.Parent = PlaylistButtonBackground_2
 
PlaylistButton.Name = "PlaylistButton"
PlaylistButton.Parent = PlaylistButtonBackground_2
PlaylistButton.AnchorPoint = Vector2.new(0.5, 0.5)
PlaylistButton.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
PlaylistButton.Position = UDim2.new(0.55, 0, 0.55, 0)
PlaylistButton.Size = UDim2.new(0, 40, 0, 40)
PlaylistButton.Image = "rbxassetid://16139588106"
PlaylistButton.BackgroundTransparency = 1
 
VolumeDownButtonBackground.Name = "VolumeDownButtonBackground"
VolumeDownButtonBackground.Parent = MainSondFrame
VolumeDownButtonBackground.AnchorPoint = Vector2.new(0.5, 0.5)
VolumeDownButtonBackground.BackgroundColor3 = Color3.fromRGB(55, 55, 55)
VolumeDownButtonBackground.Position = UDim2.new(0.1, 0, 0.9, 0)
VolumeDownButtonBackground.Size = UDim2.new(0, 50, 0, 35)
 
VolumeDownButtonBackgroundUICorner.CornerRadius = UDim.new(0, 15)
VolumeDownButtonBackgroundUICorner.Parent = VolumeDownButtonBackground
 
VolumeUpButtonBackground.Name = "VolumeUpButtonBackground"
VolumeUpButtonBackground.Parent = MainSondFrame
VolumeUpButtonBackground.AnchorPoint = Vector2.new(0.5, 0.5)
VolumeUpButtonBackground.BackgroundColor3 = Color3.fromRGB(55, 55, 55)
VolumeUpButtonBackground.Position = UDim2.new(0.9, 0, 0.9, 0)
VolumeUpButtonBackground.Size = UDim2.new(0, 50, 0, 35)
 
VolumeUpButtonBackgroundUICorner.CornerRadius = UDim.new(0, 15)
VolumeUpButtonBackgroundUICorner.Parent = VolumeUpButtonBackground
 
VolumeUpButton.Name = "VolumeUpButton"
VolumeUpButton.Parent = VolumeUpButtonBackground
VolumeUpButton.AnchorPoint = Vector2.new(0.5, 0.5)
VolumeUpButton.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
VolumeUpButton.Position = UDim2.new(0.5, 0, 0.5, 0)
VolumeUpButton.Size = UDim2.new(0, 46, 0, 32)
VolumeUpButton.Image = "rbxassetid://16164520143"
VolumeUpButton.AutoButtonColor = false
 
VolumeUpButtonUICorner.CornerRadius = UDim.new(0, 12)
VolumeUpButtonUICorner.Parent = VolumeUpButton
 
VolumeDownButton.Name = "VolumeDownButton"
VolumeDownButton.Parent = VolumeDownButtonBackground
VolumeDownButton.AnchorPoint = Vector2.new(0.5, 0.5)
VolumeDownButton.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
VolumeDownButton.Position = UDim2.new(0.5, 0, 0.5, 0)
VolumeDownButton.Size = UDim2.new(0, 46, 0, 32)
VolumeDownButton.Image = "rbxassetid://16164522333"
VolumeDownButton.AutoButtonColor = false
 
VolumeDownButtonUICorner.CornerRadius = UDim.new(0, 12)
VolumeDownButtonUICorner.Parent = VolumeDownButton
 
VolumeDownButton_2.Name = "VolumeDownButton_2"
VolumeDownButton_2.Parent = VolumeDownButtonBackground
VolumeDownButton_2.AnchorPoint = Vector2.new(0.5, 0.5)
VolumeDownButton_2.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
VolumeDownButton_2.Position = UDim2.new(0.5, 0, 0.5, 0)
VolumeDownButton_2.Size = UDim2.new(0, 46, 0, 32)
VolumeDownButton_2.Image = "rbxassetid://16164522333"
VolumeDownButton_2.AutoButtonColor = false
 
VolumeDownButtonUICorner_2.CornerRadius = UDim.new(0, 12)
VolumeDownButtonUICorner_2.Parent = VolumeDownButton_2
 
VolumeUpButton_2.Name = "VolumeUpButton_2"
VolumeUpButton_2.Parent = VolumeUpButtonBackground
VolumeUpButton_2.AnchorPoint = Vector2.new(0.5, 0.5)
VolumeUpButton_2.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
VolumeUpButton_2.Position = UDim2.new(0.5, 0, 0.5, 0)
VolumeUpButton_2.Size = UDim2.new(0, 46, 0, 32)
VolumeUpButton_2.Image = "rbxassetid://16164520143"
VolumeUpButton_2.AutoButtonColor = false
 
VolumeUpButtonUICorner_2.CornerRadius = UDim.new(0, 12)
VolumeUpButtonUICorner_2.Parent = VolumeUpButton_2
 
VolumeDownButton_2.Visible = false
VolumeUpButton_2.Visible = false
 
VolumeFrame.Name = "VolumeFrame"
VolumeFrame.Parent = MainSondFrame
VolumeFrame.Position = UDim2.new(0.2, 0, 0.895, 0)
VolumeFrame.Size = UDim2.new(0, 10, 0, 5)
VolumeFrame.BackgroundColor3 = Color3.new(255, 255, 255)
 
VolumeFrameUICorner.CornerRadius = UDim.new(1, 0)
VolumeFrameUICorner.Parent = VolumeFrame
 
 
function setHoverDef(from, to, obj)
    from = from or obj.Size
    
    obj.MouseEnter:Connect(function()
 
        TweenService:Create(obj, TweenInfo.new(0.2, Enum.EasingStyle.Linear, Enum.EasingDirection.InOut), {
            Size = to
}):Play()
 
    end)
    
    obj.MouseLeave:Connect(function()
 
        TweenService:Create(obj, TweenInfo.new(0.2, Enum.EasingStyle.Linear, Enum.EasingDirection.InOut), {
            Size = from
 }):Play()
 
    end)
end
 
setHoverDef(nil, UDim2.new(0, 40, 0, 40), HomeButton)
setHoverDef(nil, UDim2.new(0, 40, 0, 40), SearcherOpenUIButton)
setHoverDef(nil, UDim2.new(0, 40, 0, 40), ConsoleButton)
setHoverDef(nil, UDim2.new(0, 40, 0, 40), EditorButton)
setHoverDef(nil, UDim2.new(0, 36, 0, 36), MusicButton) 
function createfolders(path)
 local pathtbl = string.split(path, "/")
 for i, v in pairs(pathtbl) do
  if i == 1 then
   if not isfolder(v) then
    makefolder(v)
   end
  else
   local newpath = pathtbl[1]
   for i2=2, i-1 do
    newpath = newpath.. "/" ..pathtbl[i2]
   end
   newpath = newpath.. "/" ..v
   if not isfolder(newpath) then
    makefolder(newpath)
   end
  end
 end
end
 
if not isfile("ECCS_V3/CoreSystem/Files/ECCSV3EDITOR.ECCS") and isfile("ECCS_V3/CoreSystem/Files/ECCSV3Player.ECCS") and isfile("ECCS_V3/CoreSystem/Files/ECCSV3SearchHistory.ECCS") and isfolder("ECCS_V3") then
delfolder("ECCS_V3")
end
 
createfolders("ECCS_V3/CoreSystem/Files")
 
if not isfile("ECCS_V3/CoreSystem/Files/ECCSV3EDITOR.ECCS") then
writefile("ECCS_V3/CoreSystem/Files/ECCSV3EDITOR.ECCS", ""..EditorTextBox.Text)
end
 
if not isfile("ECCS_V3/CoreSystem/Files/ECCSV3Player.ECCS") then
writefile("ECCS_V3/CoreSystem/Files/ECCSV3Player.ECCS", " ")
end

if not isfile("ECCS_V3/CoreSystem/Files/ECCSV3SearchHistory.ECCS") then
writefile("ECCS_V3/CoreSystem/Files/ECCSV3SearchHistory.ECCS", "")
end

ExecuteButton_3.MouseButton1Click:Connect(function()
loadstring(EditorTextBox.Text)()
end)
 
CopyButton.MouseButton1Click:Connect(function()
setclipboard(EditorTextBox.Text)
end)
 
EditorTextBox.FocusLost:Connect(function(enterPressed)
if enterPressed then
HoverButtons:Play()
loadstring(EditorTextBox.Text)()
end
end)
 
SaveButton.MouseButton1Click:Connect(function()
writefile("ECCS_V3/CoreSystem/Files/ECCSV3EDITOR.ECCS", ""..EditorTextBox.Text)
end)
 
ClearButton.MouseButton1Click:Connect(function()
EditorTextBox.Text = ""
end)
 
function setHoverColor(Out, to2, obj2)
    Out = Out or obj2.BackgroundColor3
    
    obj2.MouseEnter:Connect(function()
 
        TweenService:Create(obj2, TweenInfo.new(0.2, Enum.EasingStyle.Linear, Enum.EasingDirection.InOut), {
            BackgroundColor3 = to2
}):Play()
 end)
    
    obj2.MouseLeave:Connect(function()
 
        TweenService:Create(obj2, TweenInfo.new(0.2, Enum.EasingStyle.Linear, Enum.EasingDirection.InOut), {
            BackgroundColor3 = Out
 }):Play()
 end)
end
 
function setHoverColor_2(Out2, to3, obj3)
    Out2 = Out2 or obj3.BackgroundColor3
    
    obj3.MouseEnter:Connect(function()
 
        TweenService:Create(obj3, TweenInfo.new(0.2, Enum.EasingStyle.Linear, Enum.EasingDirection.InOut), {
            BackgroundColor3 = to3
}):Play()
 
    end)
    
    obj3.MouseLeave:Connect(function()
 
        TweenService:Create(obj3, TweenInfo.new(0.2, Enum.EasingStyle.Linear, Enum.EasingDirection.InOut), {
            BackgroundColor3 = Out2
 }):Play()
 
    end)
end

setHoverColor(nil, Color3.fromRGB(200, 200, 200), CoreSystemFrameBackground)
setHoverColor(nil, Color3.fromRGB(200, 200, 200), MessageBackgroundFrame)
setHoverColor(nil, Color3.fromRGB(200, 200, 200), GameFrameBackground)
setHoverColor(nil, Color3.fromRGB(200, 200, 200), PlayerIconBackground)
setHoverColor(nil, Color3.fromRGB(200, 200, 200), BackgroundConsole)
setHoverColor(nil, Color3.fromRGB(200, 200, 200), ExecuteButtonBackground_3)
setHoverColor(nil, Color3.fromRGB(200, 200, 200), ClearButtonBackground)
setHoverColor(nil, Color3.fromRGB(200, 200, 200), SaveButtonBackground)
setHoverColor(nil, Color3.fromRGB(200, 200, 200), CopyButtonBackground)
setHoverColor(nil, Color3.fromRGB(200, 200, 200), EditorBackground)
setHoverColor(nil, Color3.fromRGB(200, 200, 200), SondFrameBackground)
setHoverColor(nil, Color3.fromRGB(200, 200, 200), Stop_PlayButtonBackground)
setHoverColor(nil, Color3.fromRGB(200, 200, 200), SaveButtonBackground_2)
setHoverColor(nil, Color3.fromRGB(200, 200, 200), PlaylistButtonBackground)
setHoverColor(nil, Color3.fromRGB(200, 200, 200), VolumeDownButtonBackground)
setHoverColor(nil, Color3.fromRGB(200, 200, 200), VolumeUpButtonBackground)
setHoverColor_2(nil, Color3.fromRGB(200, 200, 200), ReloadBackgroundButton)
setHoverColor_2(nil, Color3.fromRGB(200, 200, 200), HistoryBackgroundButton)
setHoverColor_2(nil, Color3.fromRGB(200, 200, 200), ClearAndSearchBackground)
setHoverColor_2(nil, Color3.fromRGB(200, 200, 200), ClearButton_2Background)


Stop_PlayButtonBackground.MouseEnter:Connect(function()
HoverButtons:Play()
end)

ClearAndSearchBackground.MouseEnter:Connect(function()
HoverButtons:Play()
end)
 
SaveButtonBackground_2.MouseEnter:Connect(function()
HoverButtons:Play()
end)
 
PlaylistButtonBackground.MouseEnter:Connect(function()
HoverButtons:Play()
end)
 
VolumeDownButtonBackground.MouseEnter:Connect(function()
HoverButtons:Play()
end)
 
VolumeUpButtonBackground.MouseEnter:Connect(function()
HoverButtons:Play()
end)
 
GameFrameBackground.MouseEnter:Connect(function()
HoverButtons:Play()
end)
 
PlayerIconBackground.MouseEnter:Connect(function()
HoverButtons:Play()
end)
 
game:GetService("LogService").MessageOut:Connect(
function(Message)
    repeat
        wait()
    until Message
    logTable[#logTable + 1] = Message
    ConsoleOutput.Text = (table.concat(logTable, "\n"))
    for i, v in pairs(logTable) do
        if i == 30 then
            table.remove(logTable, 1)
        end
    end
end
)

function setHoverSysSize(Out2, to23, obj23)
    Out2 = Out2 or obj23.Size
    
    obj23.MouseEnter:Connect(function()
 
        TweenService:Create(obj23, TweenInfo.new(0.2, Enum.EasingStyle.Linear, Enum.EasingDirection.InOut), {
            Size = to23
}):Play()
 
    end)
    
    obj23.MouseLeave:Connect(function()
 
        TweenService:Create(obj23, TweenInfo.new(0.2, Enum.EasingStyle.Linear, Enum.EasingDirection.InOut), {
            Size = Out2
 }):Play()
 
    end)
end
 
setHoverSysSize(nil, UDim2.new(0, 303, 0, 63), MessageBackgroundFrame)
setHoverSysSize(nil, UDim2.new(0, 55.7, 0, 225), CoreSystemFrameBackground)
 
 
 
local getfakeasset = getcustomasset or getsynasset
 
local HttpService = game:GetService("HttpService")
local TweenService = game:GetService("TweenService")
local TextService = game:GetService("TextService")
 
 
 
local page = 1
local gquery = ""
 
function tableConcat(t1,t2)
    for i, v in pairs(t2) do
        table.insert(t1, v)
    end
    return t1
end
 
 
ScriptListFrame.AutomaticCanvasSize = Enum.AutomaticSize.Y
 
ScriptListFrame.ScrollBarImageColor3 = Color3.fromRGB(0, 0, 0)
 
 
local VerifiedScript = VerifiedScriptFrame:Clone()
local Script = ScriptFrame:Clone()
ScriptFrame:Destroy()
VerifiedScriptFrame:Destroy()
 
 
 
function _if(a, b, c)
    if a then return b else return c end
end
 
function fastmodeExec(func)
    if getgenv().fastmode == true then
        task.spawn(func)
    else
        func()
    end
end
 
function fetchScripts(query, page)
    page = page or 1
    query = HttpService:UrlEncode(query)
    
    local url = _if(query == "", "https://www.scriptblox.com/api/script/fetch?page="..tostring(page), "https://scriptblox.com/api/script/search?q="..query.."&max=100&mode=free&page=".. tostring(page))
    local req = HttpService:JSONDecode(game:HttpGetAsync(url)).result
    
    return req.scripts
end
 
function fixScript(scriptObj)
 
            local req = HttpService:JSONDecode(game:HttpGetAsync("https://www.scriptblox.com/api/script/".. scriptObj.slug)).script
            scriptObj["script"] = _if(scriptObj["script"], scriptObj["script"], req.script)
            scriptObj["features"] = _if(scriptObj["features"], scriptObj["features"], req.features)
            scriptObj["owner"] = _if(scriptObj["owner"], scriptObj["owner"], req.owner)
            
  
    return scriptObj
end
 
 
 
function refreshScripts(scriptTbl)
    if #scriptTbl <= 0 then
        SearchBox.Text = ""
      SearchBox.PlaceholderText = "No script founded"
wait(1)
SearchBox.PlaceholderText = "Tap to search"
        return
    else
        SearchBox.PlaceholderText = "Tap to search"
    end
    
    local UIGridLayoutCopy = UIGridLayout:Clone()
    Scripts:ClearAllChildren()
    UIGridLayoutCopy.Parent = Scripts
    
    addScripts(scriptTbl)
end
 
function addScripts(scriptTbl)
    for i, v in pairs(scriptTbl) do
        fastmodeExec(function()
            local newScript
 
            v = fixScript(v)
 
            if v.verified == true then
                newScript = VerifiedScript:Clone()
                newScript.ScriptTitle.Text = v.title
                newScript.ScriptAuthor.Text = "by ".. v.owner.username
                newScript.ScriptGame.Text = v.game.name
                newScript.Parent = Scripts
            else
                newScript = Script:Clone()
                newScript.ScriptTitle.Text = v.title
                newScript.ScriptAuthor.Text = "by ".. v.owner.username
                newScript.ScriptGame.Text = v.game.name
                newScript.Parent = Scripts
            end
 
            newScript.ExecuteButton.MouseButton1Click:Connect(function()
 
                loadstring(v.script)()
            end)
 
            newScript.CopyLinkButton.MouseButton1Click:Connect(function()
            setclipboard("https://scriptblox.com/script/".. v.slug)
end)
 
 
setHoverColor(nil, Color3.fromRGB(200, 200, 200), newScript.ExecuteButtonBackground)
setHoverColor(nil, Color3.fromRGB(200, 200, 200), newScript.CopyLinkButtonBackground)
setHoverColor(nil, Color3.fromRGB(200, 200, 200), newScript.CopyScriptBackground)
setHoverColor(nil, Color3.fromRGB(200, 200, 200), newScript.OpenDescriptionBackground)
 
newScript.ExecuteButtonBackground.MouseEnter:Connect(function()
HoverButtons:Play()
end)
 
newScript.CopyLinkButtonBackground.MouseEnter:Connect(function()
HoverButtons:Play()
end)
 
newScript.CopyScriptBackground.MouseEnter:Connect(function()
HoverButtons:Play()
end)
 
newScript.OpenDescriptionBackground.MouseEnter:Connect(function()
HoverButtons:Play()
end)
 
newScript.CopyScriptButton.MouseButton1Click:Connect(function()
setclipboard(v.script)
end)
 
newScript.OpenDescriptionButton.MouseButton1Click:Connect(function()
DescriptionScript.Visible = true
DescriptionScript.Text = v.features
ScriptListFrame.Visible = false
end)
 
 
end)
end
 
    
    pagefetchrunning = false
end
 
DescriptionScript.MouseButton1Click:Connect(function()
DescriptionScript.Visible = false
ScriptListFrame.Visible = true
CloseDescriptionSound:Play()
end)
 
BackgroundConsole.MouseEnter:Connect(function()
HoverButtons:Play()
end)
 
 
ExecuteButtonBackground_3.MouseEnter:Connect(function()
HoverButtons:Play()
end)
 
ExecuteButtonBackground.MouseEnter:Connect(function()
HoverButtons:Play()
end)
 
ClearButtonBackground.MouseEnter:Connect(function()
HoverButtons:Play()
end)
 
SaveButtonBackground.MouseEnter:Connect(function()
HoverButtons:Play()
end)
 
 
CopyButtonBackground.MouseEnter:Connect(function()
HoverButtons:Play()
end)
 
 
SearchBox.FocusLost:Connect(function(enterPressed)
    if enterPressed then
DescriptionScript.Visible = false
ScriptListFrame.Visible = true
        gquery = SearchBox.Text
        page = 1
        local scriptsTbl = fetchScripts(SearchBox.Text, 1)
        refreshScripts(scriptsTbl)
   writefile("ECCS_V3/CoreSystem/Files/ECCSV3SearchHistory.ECCS", ""..SearchBox.Text)
    end
end)

ReloadButton.MouseButton1Click:Connect(function()
DescriptionScript.Visible = false
ScriptListFrame.Visible = true
        gquery = SearchBox.Text
        page = 1
        local scriptsTbl = fetchScripts(SearchBox.Text, 1)
        refreshScripts(scriptsTbl)
end)

ReloadButton.MouseEnter:Connect(function()
  HoverButtons:Play()
 end)
HistoryButton.MouseEnter:Connect(function()
  HoverButtons:Play()
 end)

ClearButton_2.MouseButton1Click:Connect(function()
ConsoleOutput.Text = "Notifications, warnings and script errors will be displayed here to simplify working with them."
end)

ClearButton_2.MouseEnter:Connect(function()
  HoverButtons:Play()
 end)

HistoryButton.MouseButton1Click:Connect(function()
local ReadECCSV3History = readfile("ECCS_V3/CoreSystem/Files/ECCSV3SearchHistory.ECCS")
SearchBox.Text = ""..ReadECCSV3History
DescriptionScript.Visible = false
ScriptListFrame.Visible = true
        gquery = SearchBox.Text
        page = 1
        local scriptsTbl = fetchScripts(SearchBox.Text, 1)
        refreshScripts(scriptsTbl)
end)

SearchBox.FocusLost:Connect(function(enterPressed)
if enterPressed then
HoverButtons:Play()
end
end)
 
 
VolumeUpButton.MouseButton1Click:Connect(function()
Volume = Volume + 0.5
end)
 
VolumeDownButton.MouseButton1Click:Connect(function()
Volume = Volume - 0.5
end)
 
SaveButton_2.MouseButton1Click:Connect(function()
if Stop_PlayButton.Image == "rbxassetid://16139639068" and SoundTextBox.Text == "" then
SoundTextBox.PlaceholderText = "Enter Id here"
wait(1)
SoundTextBox.PlaceholderText = "Sound Id here"
else
SoundTextBox.PlaceholderText = "Sound Id here"
if SaveButton_2.Image == "rbxassetid://16139574980" then
SaveButton_2.Image = "rbxassetid://16139703752"
writefile("ECCS_V3/CoreSystem/Files/ECCSV3Player.ECCS", ""..SoundTextBox.Text)
else
if SaveButton_2.Image == "rbxassetid://16139703752" then
SaveButton_2.Image = "rbxassetid://16139574980"
writefile("ECCS_V3/CoreSystem/Files/ECCSV3Player.ECCS", " ")
end
end
end
end)
 
PlaylistButton.MouseButton1Click:Connect(function()
local ReadECCSV3_2 = readfile("ECCS_V3/CoreSystem/Files/ECCSV3Player.ECCS")
SoundTextBox.Text = ReadECCSV3_2
if SoundTextBox.Text == " " then
SoundTextBox.Text = ""
end
end)
 
ClearAndSearch.MouseButton1Click:Connect(function()
SearchBox.Text = ""
SearchBox:CaptureFocus()
end)

Stop_PlayButton.MouseButton1Click:Connect(function()
if Stop_PlayButton.Image == "rbxassetid://16139639068" and SoundTextBox.Text == "" then
SoundTextBox.PlaceholderText = "Enter Id here"
wait(1)
SoundTextBox.PlaceholderText = "Sound Id here"
else
SoundTextBox.PlaceholderText = "Sound Id here"
if Stop_PlayButton.Image == "rbxassetid://16139639068" then
Stop_PlayButton.Image = "rbxassetid://16139637058"
Stop_PlayButton.Position = UDim2.new(0.5, 0, 0.5, 0)
Audio = game:GetService("MarketplaceService"):GetProductInfo(SoundTextBox.Text)
AudioName.Text = Audio.Name
CoreSound.SoundId = "rbxassetid://"..SoundTextBox.Text
CoreSound:Play()
else
if Stop_PlayButton.Image == "rbxassetid://16139637058" then
Stop_PlayButton.Image = "rbxassetid://16139639068"
Stop_PlayButton.Position = UDim2.new(0.6, 0, 0.5, 0)
CoreSound:Stop()
end
end
end
end)
 
SoundTextBox.FocusLost:Connect(function(enterPressed)
if enterPressed then
if Stop_PlayButton.Image == "rbxassetid://16139639068" and SoundTextBox.Text == "" then
SoundTextBox.PlaceholderText = "Enter Id here"
wait(1)
SoundTextBox.PlaceholderText = "Sound Id here"
else
SoundTextBox.PlaceholderText = "Sound Id here"
if Stop_PlayButton.Image == "rbxassetid://16139639068" then
Stop_PlayButton.Image = "rbxassetid://16139637058"
Stop_PlayButton.Position = UDim2.new(0.5, 0, 0.5, 0)
Audio = game:GetService("MarketplaceService"):GetProductInfo(SoundTextBox.Text)
AudioName.Text = Audio.Name
CoreSound.SoundId = "rbxassetid://"..SoundTextBox.Text
CoreSound:Play()
else
if Stop_PlayButton.Image == "rbxassetid://16139637058" then
Stop_PlayButton.Image = "rbxassetid://16139639068"
Stop_PlayButton.Position = UDim2.new(0.6, 0, 0.5, 0)
CoreSound:Stop()
end
end
end
end
end)
 
spawn(function()
repeat
wait()
local ReadECCSV3_2 = readfile("ECCS_V3/CoreSystem/Files/ECCSV3Player.ECCS")
if SoundTextBox.Text == ReadECCSV3_2 then
SaveButton_2.Image = "rbxassetid://16139703752"
else
if SoundTextBox.Text ~= ReadECCSV3_2 then
SaveButton_2.Image = "rbxassetid://16139574980"
end
if SoundTextBox.Text == "" then
SaveButton_2.Image = "rbxassetid://16139574980"
Stop_PlayButton.Image = "rbxassetid://16139639068"
Stop_PlayButton.Position = UDim2.new(0.6, 0, 0.5, 0)
CoreSound:Stop()
AudioName.Text = ""
end
end
until 
SaveButton_2 == nil
end)
 
spawn(function()
repeat
wait()
CoreSound.Volume = Volume
if Volume == 0 then
VolumeFrame:TweenSize(UDim2.new(0, 0, 0, 5), "Out", "Linear", 0.5)
VolumeUpButton.Visible = true
VolumeDownButton.Visible = false
VolumeDownButton_2.Visible = true
VolumeUpButton_2.Visible = false
else
if Volume == 0.5 then
VolumeFrame:TweenSize(UDim2.new(0, 55, 0, 5), "Out", "Linear", 0.5)
VolumeUpButton.Visible = true
VolumeDownButton.Visible = true
VolumeDownButton_2.Visible = false
VolumeUpButton_2.Visible = false
else
if Volume == 1 then
VolumeFrame:TweenSize(UDim2.new(0, 105, 0, 5), "Out", "Linear", 0.5)
VolumeUpButton.Visible = true
VolumeDownButton.Visible = true
VolumeDownButton_2.Visible = false
VolumeUpButton_2.Visible = false
else
if Volume == 1.5 then
VolumeFrame:TweenSize(UDim2.new(0, 155, 0, 5), "Out", "Linear", 0.5)
VolumeUpButton.Visible = true
VolumeDownButton.Visible = true
VolumeDownButton_2.Visible = false
VolumeUpButton_2.Visible = false
else
if Volume == 2 then
VolumeFrame:TweenSize(UDim2.new(0, 205, 0, 5), "Out", "Linear", 0.5)
VolumeUpButton.Visible = false
VolumeDownButton.Visible = true
VolumeUpButton_2.Visible = true
VolumeDownButton_2.Visible = false
end
end
end
end
end
until 
SaveButton_2 == nil
end)
 
refreshScripts(fetchScripts(gquery, 1))
 
ScriptListFrame:GetPropertyChangedSignal("CanvasPosition"):Connect(function()
    if (ScriptListFrame.CanvasPosition.Y + ScriptListFrame.AbsoluteSize.Y) >= ScriptListFrame.AbsoluteCanvasSize.Y -200 and not pagefetchrunning then
        page = page + 1
        pagefetchrunning = true
        addScripts(fetchScripts(gquery, page))
    end
end)
 
local ReadECCSV3 = readfile("ECCS_V3/CoreSystem/Files/ECCSV3EDITOR.ECCS")
EditorTextBox.Text = ""..ReadECCSV3
PlayerIcon.Image = "https://www.roblox.com/headshot-thumbnail/image?userId=".. game.Players.LocalPlayer.UserId .."&width=999&height=999&format=png"
WelcomeLabel.Text = "Welcome Home, "..game.Players.LocalPlayer.DisplayName
MessageBackgroundFrame:TweenPosition(UDim2.new(0.5, 0, 0.9, 0),"InOut","Sine",0.8)
StartUpSound:Play()
