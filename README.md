if not LPH_OBFUSCATED then
    getfenv().LPH_NO_VIRTUALIZE = function(f) return f end;
end

local gui = 
{
	blazedLoader = Instance.new("ScreenGui"),
	Frame = Instance.new("Frame"),
	UICorner = Instance.new("UICorner"),
	TextLabel = Instance.new("TextLabel"),
	TextLabel_1 = Instance.new("TextLabel"),
	signin_load = Instance.new("TextButton"),
	UICorner_1 = Instance.new("UICorner"),
	UIStroke = Instance.new("UIStroke"),
	TextLabel_2 = Instance.new("TextLabel"),
	fps_checkbox = Instance.new("Frame"),
	UICorner_2 = Instance.new("UICorner"),
	UICorner_3 = Instance.new("UICorner"),
	UIStroke_1 = Instance.new("UIStroke"),
	ImageLabel = Instance.new("ImageLabel"),
	fpscheckbox_button = Instance.new("TextButton"),
	TextLabel_3 = Instance.new("TextLabel"),
	UICorner_4 = Instance.new("UICorner"),
	UIStroke_2 = Instance.new("UIStroke"),
	UIStroke_3 = Instance.new("UIStroke"),
}

gui.blazedLoader.ZIndexBehavior = Enum.ZIndexBehavior.Sibling
gui.blazedLoader.Name = "Foundation"
gui.blazedLoader.Parent = game:GetService("CoreGui")

gui.Frame.BorderSizePixel = 0
gui.Frame.Size = UDim2.new(0, 426, 0, 249)
gui.Frame.BorderColor3 = Color3.fromRGB(0, 0, 0)
gui.Frame.Name = "Frame"
gui.Frame.Position = UDim2.new(0.396226, 0, 0.362031, 0)
gui.Frame.BackgroundColor3 = Color3.fromRGB(20, 20, 20)
gui.Frame.Parent = gui.blazedLoader

gui.UICorner.Name = "UICorner"
gui.UICorner.CornerRadius = UDim.new(0, 12)
gui.UICorner.Parent = gui.Frame

gui.TextLabel.BorderSizePixel = 0
gui.TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
gui.TextLabel.FontFace = Font.new("rbxassetid://11702779517", Enum.FontWeight.Bold, Enum.FontStyle.Normal)
gui.TextLabel.TextSize = 40
gui.TextLabel.Position = UDim2.new(0.244949, 0, 0.11245, 0)
gui.TextLabel.Size = UDim2.new(0, 147, 0, 50)
gui.TextLabel.Name = "TextLabel"
gui.TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
gui.TextLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
gui.TextLabel.Text = "Gult"
gui.TextLabel.BackgroundTransparency = 1
gui.TextLabel.Parent = gui.Frame

gui.TextLabel_1.BorderSizePixel = 0
gui.TextLabel_1.BackgroundColor3 = Color3.fromRGB(160, 160, 160)
gui.TextLabel_1.FontFace = Font.new("rbxassetid://11702779517", Enum.FontWeight.Bold, Enum.FontStyle.Normal)
gui.TextLabel_1.TextSize = 20
gui.TextLabel_1.Position = UDim2.new(0.479798, 0, 0.11245, 0)
gui.TextLabel_1.Size = UDim2.new(0, 106, 0, 57)
gui.TextLabel_1.Name = "TextLabel"
gui.TextLabel_1.TextColor3 = Color3.fromRGB(227, 181, 200)
gui.TextLabel_1.BorderColor3 = Color3.fromRGB(0, 0, 0)
gui.TextLabel_1.Text = "2.2"
gui.TextLabel_1.BackgroundTransparency = 1
gui.TextLabel_1.Parent = gui.Frame

gui.signin_load.BorderSizePixel = 0
gui.signin_load.BackgroundColor3 = Color3.fromRGB(203, 195, 227)
gui.signin_load.FontFace = Font.new("rbxassetid://11702779517", Enum.FontWeight.Bold, Enum.FontStyle.Normal)
gui.signin_load.TextColor3 = Color3.fromRGB(255, 255, 255)
gui.signin_load.Position = UDim2.new(0.161616, 0, 0.598394, 0)
gui.signin_load.TextSize = 23
gui.signin_load.Size = UDim2.new(0, 274, 0, 31)
gui.signin_load.Name = "signin_load"
gui.signin_load.BorderColor3 = Color3.fromRGB(0, 0, 0)
gui.signin_load.Text = "Sign In"
gui.signin_load.Active = true
gui.signin_load.Selectable = true
gui.signin_load.Parent = gui.Frame

gui.UICorner_1.Name = "UICorner"
gui.UICorner_1.Parent = gui.signin_load

gui.UIStroke.ApplyStrokeMode = Enum.ApplyStrokeMode.Border
gui.UIStroke.Name = "UIStroke"
gui.UIStroke.Thickness = 1.4
gui.UIStroke.Color = Color3.fromRGB(25, 25, 25)
gui.UIStroke.Parent = gui.signin_load

gui.TextLabel_2.BorderSizePixel = 0
gui.TextLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
gui.TextLabel_2.FontFace = Font.new("rbxassetid://11702779517", Enum.FontWeight.Bold, Enum.FontStyle.Normal)
gui.TextLabel_2.TextSize = 13
gui.TextLabel_2.Position = UDim2.new(0.290404, 0, 0.690763, 0)
gui.TextLabel_2.Size = UDim2.new(0, 200, 0, 50)
gui.TextLabel_2.Name = "TextLabel"
gui.TextLabel_2.TextColor3 = Color3.fromRGB(255, 255, 255)
gui.TextLabel_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
gui.TextLabel_2.Text = "--Reduce ping?"
gui.TextLabel_2.BackgroundTransparency = 1
gui.TextLabel_2.Parent = gui.Frame

gui.fps_checkbox.BorderSizePixel = 0
gui.fps_checkbox.Size = UDim2.new(0, 20, 0, 20)
gui.fps_checkbox.BorderColor3 = Color3.fromRGB(0, 0, 0)
gui.fps_checkbox.Name = "fps_checkbox"
gui.fps_checkbox.Position = UDim2.new(0.383838, 0, 0.751004, 0)
gui.fps_checkbox.BackgroundColor3 = Color3.fromRGB(157, 125, 138)
gui.fps_checkbox.Parent = gui.Frame

gui.UICorner_2.Name = "UICorner"
gui.UICorner_2.CornerRadius = UDim.new(0, 5)
gui.UICorner_2.Parent = gui.fps_checkbox

gui.UICorner_3.Name = "UICorner"
gui.UICorner_3.Parent = gui.fps_checkbox

gui.UIStroke_1.ApplyStrokeMode = Enum.ApplyStrokeMode.Border
gui.UIStroke_1.Name = "UIStroke"
gui.UIStroke_1.Thickness = 1.4
gui.UIStroke_1.Color = Color3.fromRGB(25, 25, 25)
gui.UIStroke_1.Parent = gui.fps_checkbox

gui.ImageLabel.BorderSizePixel = 0
gui.ImageLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
gui.ImageLabel.Image = "http://www.roblox.com/asset/?id=9754130783"
gui.ImageLabel.Size = UDim2.new(0, 20, 0, 20)
gui.ImageLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
gui.ImageLabel.Name = "ImageLabel"
gui.ImageLabel.BackgroundTransparency = 1
gui.ImageLabel.Parent = gui.fps_checkbox

gui.fpscheckbox_button.BorderSizePixel = 0
gui.fpscheckbox_button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
gui.fpscheckbox_button.FontFace = Font.new("rbxasset://fonts/families/SourceSansPro.json", Enum.FontWeight.Regular, Enum.FontStyle.Normal)
gui.fpscheckbox_button.TextColor3 = Color3.fromRGB(0, 0, 0)
gui.fpscheckbox_button.Position = UDim2.new(-2.7, 0, 0, 0)
gui.fpscheckbox_button.TextSize = 14
gui.fpscheckbox_button.Size = UDim2.new(0, 200, 0, 20)
gui.fpscheckbox_button.Name = "fpscheckbox_button"
gui.fpscheckbox_button.BorderColor3 = Color3.fromRGB(0, 0, 0)
gui.fpscheckbox_button.Text = ""
gui.fpscheckbox_button.Active = true
gui.fpscheckbox_button.BackgroundTransparency = 1
gui.fpscheckbox_button.Selectable = true
gui.fpscheckbox_button.Parent = gui.fps_checkbox

gui.TextLabel_3.BorderSizePixel = 0
gui.TextLabel_3.BackgroundColor3 = Color3.fromRGB(20, 20, 20)
gui.TextLabel_3.FontFace = Font.new("rbxassetid://11702779517", Enum.FontWeight.Bold, Enum.FontStyle.Normal)
gui.TextLabel_3.TextSize = 14
gui.TextLabel_3.Position = UDim2.new(0.161616, 0, 0.425703, 0)
gui.TextLabel_3.Size = UDim2.new(0, 274, 0, 36)
gui.TextLabel_3.Name = "TextLabel"
gui.TextLabel_3.TextColor3 = Color3.fromRGB(50, 50, 50)
gui.TextLabel_3.BorderColor3 = Color3.fromRGB(0, 0, 0)
gui.TextLabel_3.Text = "   "..tostring(LRM_LinkedDiscordID)..""
gui.TextLabel_3.TextXAlignment = Enum.TextXAlignment.Left
gui.TextLabel_3.Parent = gui.Frame

gui.UICorner_4.Name = "UICorner"
gui.UICorner_4.Parent = gui.TextLabel_3

gui.UIStroke_2.ApplyStrokeMode = Enum.ApplyStrokeMode.Border
gui.UIStroke_2.Name = "UIStroke"
gui.UIStroke_2.Thickness = 1.4
gui.UIStroke_2.Color = Color3.fromRGB(25, 25, 25)
gui.UIStroke_2.Parent = gui.TextLabel_3

gui.UIStroke_3.ApplyStrokeMode = Enum.ApplyStrokeMode.Border
gui.UIStroke_3.Name = "UIStroke"
gui.UIStroke_3.Thickness = 1.4
gui.UIStroke_3.Color = Color3.fromRGB(25, 25, 25)
gui.UIStroke_3.Parent = gui.Frame



gui.fpscheckbox_button.MouseButton1Click:Connect(function()
	if gui.fps_checkbox.BackgroundColor3 == Color3.fromRGB(157, 125, 138) then
		gui.fps_checkbox.BackgroundColor3 = Color3.fromRGB(20,20,20) 
		gui.ImageLabel.Visible = false
		getgenv().boostframes = false
	elseif gui.fps_checkbox.BackgroundColor3 == Color3.fromRGB(20,20,20) then
		getgenv().boostframes = true
		gui.fps_checkbox.BackgroundColor3 = Color3.fromRGB(157, 125, 138)
		gui.ImageLabel.Visible = true
		end
end)

gui.signin_load.MouseButton1Click:Connect(function()
gui.blazedLoader:Destroy()
    local loadingtime = tick()
    local notificationLibrary = loadstring(game:HttpGet("https://raw.githubusercontent.com/laagginq/ui-libraries/main/xaxas-notification/src.lua"))();
    local notifications = notificationLibrary.new({            
        NotificationLifetime = 5, 
        NotificationPosition = "Middle",
        
        TextFont = Enum.Font.Code,
        TextColor = Color3.fromRGB(255, 255, 255),
        TextSize = 15,
        
        TextStrokeTransparency = 0, 
        TextStrokeColor = Color3.fromRGB(0, 0, 0)
    });
    
    local AkaliNotif = loadstring(game:HttpGet("https://raw.githubusercontent.com/Kinlei/Dynissimo/main/Scripts/AkaliNotif.lua"))();
    local ANotify = AkaliNotif.Notify;
    
    
    function Kick(Reason)
        game.Players.LocalPlayer:Kick(Reason)
    end
    
    getgenv().NotiMode = "Roblox"
    
    function Notifications(NotiINFO)
        if getgenv().NotiMode == "Roblox" then
            game:GetService("StarterGui"):SetCore("SendNotification",{
                Title = "Foundation", -- Required
                Text = NotiINFO, -- Required
                Icon = "https://imgur.com/a/SmsmznT" -- Optional
            })
        else
            if getgenv().NotiMode == "Xaxa" then
                notifications:BuildNotificationUI();
                notifications:Notify(NotiINFO);
        else
            if getgenv().NotiMode == "Akali" then
                ANotify({
                    Description = NotiINFO;
                    Title = "Foundation";
                    Duration = 1;
                    });
                else
                    Kick('[Foundation]: Notification Error, please contact lofi if this continues.')
        end
            end
                end
            end
    
    
    if game.PlaceId == 11883610532 or game.PlaceId == 12128125888 or game.PlaceId == 12543953865 then 
        print("[Foundation]: Five Duels Detected")
        getgenv().fdDetected = true
    
    getgenv().AimPart = "HumanoidRootPart" 
    getgenv().OldAimPart = "HumanoidRootPart"
    getgenv().AimlockKey = "q"
    getgenv().AimRadius = 5
    getgenv().ThirdPerson = true 
    getgenv().FirstPerson = true
    getgenv().TeamCheck = false 
    getgenv().PredictMovement = false
    getgenv().PredictionVelocity = 7.22
    
    getgenv().Smoothness = false
    getgenv().SmoothnessAmount = 1
    getgenv().EasingStyle = Enum.EasingStyle.Elastic
    
    getgenv().Notifications = false
    
    getgenv().AutoPrediction = false
    getgenv().UnlockOnDeath = false
    getgenv().Shake = false
    getgenv().ShakePower = 0
    
    local Players, Uis, RService, SGui = game:GetService"Players", game:GetService"UserInputService", game:GetService"RunService", game:GetService"StarterGui";
    local Client, Mouse, Camera, CF, RNew, Vec3, Vec2 = Players.LocalPlayer, Players.LocalPlayer:GetMouse(), workspace.CurrentCamera, CFrame.new, Ray.new, Vector3.new, Vector2.new;
    local Aimlock, MousePressed, CanNotify = true, false, false;
    local AimlockTarget
    local OldPre;
    
    
    
    getgenv().WorldToViewportPoint = function(P)
        return Camera:WorldToViewportPoint(P)
    end
    
    getgenv().WorldToScreenPoint = function(P) 
        return Camera.WorldToScreenPoint(Camera, P)
    end
    
    getgenv().GetObscuringObjects = function(T)
        if T and T:FindFirstChild(getgenv().AimPart) and Client and Client.Character:FindFirstChild("Head") then 
            local RayPos = workspace:FindPartOnRay(RNew(
                T[getgenv().AimPart].Position, Client.Character.Head.Position)
            )
            if RayPos then return RayPos:IsDescendantOf(T) end
        end
    end
    
    getgenv().GetNearestTarget = function()
        local players = {}
        local PLAYER_HOLD  = {}
        local DISTANCES = {}
        for i, v in pairs(Players:GetPlayers()) do
            if v ~= Client then
                table.insert(players, v)
            end
        end
        for i, v in pairs(players) do
            if v.Character ~= nil then
                local AIM = v.Character:FindFirstChild("Head")
                if getgenv().TeamCheck == true and v.Team ~= Client.Team then
                    local DISTANCE = (v.Character:FindFirstChild("Head").Position - game.Workspace.CurrentCamera.CFrame.p).magnitude
                    local RAY = Ray.new(game.Workspace.CurrentCamera.CFrame.p, (Mouse.Hit.p - game.Workspace.CurrentCamera.CFrame.p).unit * DISTANCE)
                    local HIT,POS = game.Workspace:FindPartOnRay(RAY, game.Workspace)
                    local DIFF = math.floor((POS - AIM.Position).magnitude)
                    PLAYER_HOLD[v.Name .. i] = {}
                    PLAYER_HOLD[v.Name .. i].dist= DISTANCE
                    PLAYER_HOLD[v.Name .. i].plr = v
                    PLAYER_HOLD[v.Name .. i].diff = DIFF
                    table.insert(DISTANCES, DIFF)
                elseif getgenv().TeamCheck == false and v.Team == Client.Team then 
                    local DISTANCE = (v.Character:FindFirstChild("Head").Position - game.Workspace.CurrentCamera.CFrame.p).magnitude
                    local RAY = Ray.new(game.Workspace.CurrentCamera.CFrame.p, (Mouse.Hit.p - game.Workspace.CurrentCamera.CFrame.p).unit * DISTANCE)
                    local HIT,POS = game.Workspace:FindPartOnRay(RAY, game.Workspace)
                    local DIFF = math.floor((POS - AIM.Position).magnitude)
                    PLAYER_HOLD[v.Name .. i] = {}
                    PLAYER_HOLD[v.Name .. i].dist= DISTANCE
                    PLAYER_HOLD[v.Name .. i].plr = v
                    PLAYER_HOLD[v.Name .. i].diff = DIFF
                    table.insert(DISTANCES, DIFF)
                end
            end
        end
        
        if unpack(DISTANCES) == nil then
            return nil
        end
        
        local L_DISTANCE = math.floor(math.min(unpack(DISTANCES)))
        if L_DISTANCE > getgenv().AimRadius then
            return nil
        end
        
        for i, v in pairs(PLAYER_HOLD) do
            if v.diff == L_DISTANCE then
                return v.plr
            end
        end
        return nil
    end
    
    
    
    RService.RenderStepped:Connect(function()
        if getgenv().ThirdPerson == true and getgenv().FirstPerson == true then 
            if (Camera.Focus.p - Camera.CoordinateFrame.p).Magnitude > 1 or (Camera.Focus.p - Camera.CoordinateFrame.p).Magnitude <= 1 then 
                CanNotify = true 
            else 
                CanNotify = false 
            end
        elseif getgenv().ThirdPerson == true and getgenv().FirstPerson == false then 
            if (Camera.Focus.p - Camera.CoordinateFrame.p).Magnitude > 1 then 
                CanNotify = true 
            else 
                CanNotify = false 
            end
        elseif getgenv().ThirdPerson == false and getgenv().FirstPerson == true then 
            if (Camera.Focus.p - Camera.CoordinateFrame.p).Magnitude <= 1 then 
                CanNotify = true 
            else 
                CanNotify = false 
            end
        end
        if Aimlock == true and MousePressed == true then 
            if AimlockTarget and AimlockTarget.Character and AimlockTarget.Character:FindFirstChild(getgenv().AimPart) then 
                if getgenv().FirstPerson == true then
                    if CanNotify == true then
                        if getgenv().PredictMovement == true then
                            if getgenv().Smoothness == true then
                                --// The part we're going to lerp/smoothen \\--
                                local Main = CF(Camera.CFrame.p, AimlockTarget.Character[getgenv().AimPart].Position + AimlockTarget.Character[getgenv().AimPart].Velocity/PredictionVelocity)
                                
                                --// Making it work \\--
                                Camera.CFrame = Camera.CFrame:Lerp(Main, getgenv().SmoothnessAmount, getgenv().EasingStyle , Enum.EasingDirection.InOut)
                            else
                                Camera.CFrame = CF(Camera.CFrame.p, AimlockTarget.Character[getgenv().AimPart].Position + AimlockTarget.Character[getgenv().AimPart].Velocity/PredictionVelocity)
                            end
                        elseif getgenv().PredictMovement == false then 
                            if getgenv().Smoothness == true then
                                --// The part we're going to lerp/smoothen \\--
                                local Main = CF(Camera.CFrame.p, AimlockTarget.Character[getgenv().AimPart].Position)
    
                                --// Making it work \\--
                                Camera.CFrame = Camera.CFrame:Lerp(Main, getgenv().SmoothnessAmount, getgenv().EasingStyle , Enum.EasingDirection.InOut)
                            else
                                Camera.CFrame = CF(Camera.CFrame.p, AimlockTarget.Character[getgenv().AimPart].Position)
                            end
                        end
                    end
                end
            end
        end
       if getgenv().UnlockOnDeath  == true and AimlockTarget and AimlockTarget.Character:FindFirstChild("Humanoid") then
        if AimlockTarget.StarterPlayer.StarterCharacterScripts.BodyEffects['K.O'] then
            AimlockTarget = nil
            
            if getgenv().Notifications == true then
                Notify({
                    Title = FoundationName,
                    Description = "Unlocked",
                    Duration = 1
                })
            end
            if getgenv().ChatNotis == true then
    game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("Unlocked","All")
            end
        end
    end
    
                if getgenv().Shake == true and AimlockTarget and AimlockTarget.Character then
                    local Main = CF(Camera.CFrame.p, AimlockTarget.Character[getgenv().AimPart].Position + AimlockTarget.Character[getgenv().AimPart].Velocity/PredictionVelocity +
                    Vector3.new(
                        math.random(-getgenv().ShakePower, getgenv().ShakePower),
                        math.random(-getgenv().ShakePower, getgenv().ShakePower),
                        math.random(-getgenv().ShakePower, getgenv().ShakePower)
                    ) * 0.1)
                    Camera.CFrame = Camera.CFrame:Lerp(Main, getgenv().SmoothnessAmount, getgenv().EasingStyle , Enum.EasingDirection.InOut)
                end
    
       if getgenv().AutoPrediction == true then
        pingvalue = game:GetService("Stats").Network.ServerStatsItem["Data Ping"]:GetValueString()
        split = string.split(pingvalue,'(')
        ping = tonumber(split[1])
    if ping < 30 then
        getgenv().PredictionVelocity = 7.758
    elseif ping < 40 then
        getgenv().PredictionVelocity = 7.364
    elseif ping < 50 then
        getgenv().PredictionVelocity = 7.456 
    elseif ping < 60 then
        getgenv().PredictionVelocity = 7.217
    elseif ping < 70 then
        getgenv().PredictionVelocity = 6.972 
    elseif ping < 80 then
        getgenv().PredictionVelocity = 6.782
    elseif ping < 90 then
        getgenv().PredictionVelocity = 6.597 
    elseif ping < 100 then
        getgenv().PredictionVelocity = 3.88
    elseif ping < 110 then
        getgenv().PredictionVelocity = 6.099
    end
    end
    
    end)
    
    
    
    local repo = 'https://raw.githubusercontent.com/wally-rblx/LinoriaLib/main/'
    local Library = loadstring(game:HttpGet('https://pastebin.com/raw/7Tk5QM6R'))()
    local ThemeManager = loadstring(game:HttpGet('https://pastebin.com/raw/WxMCy9be'))()
    local SaveManager = loadstring(game:HttpGet('https://pastebin.com/raw/rNY1ZdQT'))()
    
    local Window = Library:CreateWindow({
        Title = 'Foundation | buyer build | five duels',
        Center = true, 
        AutoShow = true,
        Size = UDim2.fromOffset(650, 500),
        TabPadding = 4,
    })
    
    
    
    local Tabs = {
        Main = Window:AddTab('Aiming'),
        ['Settings'] = Window:AddTab('Settings'),
    }
    
    local LeftGroupBox = Tabs.Main:AddLeftGroupbox('Aimlock')
    
    
    
    LeftGroupBox:AddToggle('Aimlock', {
        Text = 'Enable',
        Default = false, 
        Tooltip = 'Enables Aimlock', 
    })
    
    Toggles.Aimlock:OnChanged(function()
        getgenv().AimlockEnabled = Toggles.Aimlock.Value
    end)
    
    
    Toggles.Aimlock:AddKeyPicker('AimlockBind', {
        Default = 'None', 
        SyncToggleState = false, 
    
        Mode = 'Toggle',
    
        Text = 'Enable', 
        NoUI = false,
    })
    Options.AimlockBind:OnClick(function()
    if AimlockEnabled then 
        Target = not Target
        --
        if AimlockTarget then
            AimlockTarget = nil
            MousePressed = false
            if getgenv().Notifications then
                Notifications("Unlocked")
            end
        else
            if AimlockTarget == nil then
                local Target;Target = GetNearestTarget()
                if Target ~= nil then 
                    AimlockTarget = Target
                    if getgenv().Notifications then
                        notifications:BuildNotificationUI();
                        Notifications("Locked Onto"..tostring(Aimlock));
                    end
                    MousePressed = true
                end
            end
        end
            end
    end)
    
    LeftGroupBox:AddInput('CamPrediction', {
        Default = '7.22',
        Numeric = true, 
        Finished = false,
        Text = 'Prediction',
        Tooltip = 'Example: 7.22', 
        Placeholder = '...', 
        Callback = function(int)
            getgenv().PredictionVelocity = int
            notifications:BuildNotificationUI();
            Notifications("Prediction Changed To: "..tostring(int));
            end 
    })
    
    LeftGroupBox:AddToggle('CamPingBased', {
        Text = 'Auto prediction',
        Default = false, 
        Tooltip = 'Autos Configures Prediction', 
    })
    
    Toggles.CamPingBased:OnChanged(function()
        getgenv().AutoPrediction = Toggles.CamPingBased.Value
    end)
    
    LeftGroupBox:AddDropdown('CamHitpart', {
        Values = { 'HumanoidRootPart', 'UpperTorso', 'LowerTorso', 'Head' },
        Default = 1, -- number index of the value / string
        Multi = false, -- true / false, allows multiple choices to be selected
    
        Text = 'Hitpart',
        Tooltip = 'Where your bullets will hit', -- Information shown when you hover over the textbox
    })
    
    Options.CamHitpart:OnChanged(function()
        getgenv().AimPart = Options.CamHitpart.Value
    end)
    
    LeftGroupBox:AddToggle('CamAlerts', {
        Text = 'Notifications',
        Default = false, 
        Tooltip = 'Notifys Locking/Unlocking', 
    })
    
    Toggles.CamAlerts:OnChanged(function()
        getgenv().Notifications = Toggles.CamAlerts.Value
    end)
    
    
    
    LeftGroupBox:AddToggle('CamUnOnD', {
        Text = 'Unlock On Death',
        Default = false, 
        Tooltip = 'Automatically Unlocks Target On KO', 
    })
    
    Toggles.CamUnOnD:OnChanged(function()
        getgenv().UnlockOnDeath = Toggles.CamUnOnD.Value
    end)
    
    LeftGroupBox:AddToggle('CamShake', {
        Text = 'Vibrate',
        Default = false, 
        Tooltip = 'Shakes On The Target', 
    })
    
    Toggles.CamShake:OnChanged(function()
        getgenv().Shake = Toggles.CamShake.Value
    end)
    
    
    LeftGroupBox:AddInput('CamShakePower', {
        Default = '5',
        Numeric = true, 
        Finished = false,
        Text = 'Vibrate Power',
        Tooltip = 'Ex: 5', 
        Placeholder = '...', 
        Callback = function(int)
            getgenv().ShakePower = int
            notifications:BuildNotificationUI();
            Notifications("Shake Power Changed To: "..tostring(int));
            end 
    })
    
    LeftGroupBox:AddToggle('CamSmoothness', {
        Text = 'Smoothness',
        Default = false, 
        Tooltip = 'Smoothens Camlock', 
    })
    
    Toggles.CamSmoothness:OnChanged(function()
        getgenv().Smoothness = Toggles.CamSmoothness.Value
    end)
    
    LeftGroupBox:AddInput('CamSmoothnessPWR', {
        Default = '1',
        Numeric = true, 
        Finished = false,
        Text = 'Levelness',
        Tooltip = 'Ex: 0.52', 
        Placeholder = '...', 
        Callback = function(int)
            getgenv().SmoothnessAmount = int
            notifications:BuildNotificationUI();
            Notifications("Levelness Power Changed To: "..tostring(int));
            end, 0.01
    })
    
    LeftGroupBox:AddDropdown('CamSmoothingStyle', {
        Values = { 'Linear', 'Sine', 'Back', 'Quad', 'Quart', 'Quint', 'Bounce', 'Elastic', 'Exponential', 'Circular', 'Cubic' },
        Default = 1, -- number index of the value / string
        Multi = false, -- true / false, allows multiple choices to be selected
    
        Text = 'Smoothing Style',
        Tooltip = 'Aimlock Smoothing Style', -- Information shown when you hover over the textbox
    })
    
    Options.CamSmoothingStyle:OnChanged(function()
        if Options.CamSmoothingStyle.Value == "Linear" then
            getgenv().EasingStyle = Enum.EasingStyle.Linear
        end
    
        if Options.CamSmoothingStyle.Value == "Sine" then
            getgenv().EasingStyle = Enum.EasingStyle.Sine
        end
    
        if Options.CamSmoothingStyle.Value == "Back" then
            getgenv().EasingStyle = Enum.EasingStyle.Back
        end
    
        if Options.CamSmoothingStyle.Value == "Quad" then
            getgenv().EasingStyle = Enum.EasingStyle.Quad
        end
    
        if Options.CamSmoothingStyle.Value == "Quart" then
            getgenv().EasingStyle = Enum.EasingStyle.Quart
        end
    
        if Options.CamSmoothingStyle.Value == "Quint" then
            getgenv().EasingStyle = Enum.EasingStyle.Quint
        end
    
        if Options.CamSmoothingStyle.Value == "Bounce" then
            getgenv().EasingStyle = Enum.EasingStyle.Bounce
        end
    
        if Options.CamSmoothingStyle.Value == "Elastic" then
            getgenv().EasingStyle = Enum.EasingStyle.Elastic
        end
    
        if Options.CamSmoothingStyle.Value == "Exponential" then
            getgenv().EasingStyle = Enum.EasingStyle.Exponential
        end
    
        if Options.CamSmoothingStyle.Value == "Circular" then
            getgenv().EasingStyle = Enum.EasingStyle.Circular
        end
    
        if Options.CamSmoothingStyle.Value == "Cubic" then
            getgenv().EasingStyle = Enum.EasingStyle.Cubic
        end
    end)
    
    
        
    --[[local MyButton2 = MyButton:AddButton('Sub button', function()
        print('You clicked a sub button!')
    end)
    
    
    MyButton:AddTooltip('This is a button')
    MyButton2:AddTooltip('This is a sub button')
    
    LeftGroupBox:AddLabel('This is a label')
    LeftGroupBox:AddLabel('This is a label\n\nwhich wraps its text!', true)
    
    LeftGroupBox:AddDivider()
    
    LeftGroupBox:AddSlider('MySlider', {
        Text = 'This is my slider!',
        Default = 0,
        Min = 0,
        Max = 5,
        Rounding = 1,
        Compact = false, 
    })
    
    local Number = Options.MySlider.Value
    Options.MySlider:OnChanged(function()
        print('MySlider was changed! New value:', Options.MySlider.Value)
    end)
    
    Options.MySlider:SetValue(3)
    
    
    LeftGroupBox:AddInput('MyTextbox', {
        Default = 'My textbox!',
        Numeric = false, 
        Finished = false,
    
        Text = 'This is a textbox',
        Tooltip = 'This is a tooltip', 
    
        Placeholder = 'Placeholder text',
    })
    
    Options.MyTextbox:OnChanged(function()
        print('Text updated. New text:', Options.MyTextbox.Value)
    end)
    
    LeftGroupBox:AddDropdown('MyDropdown', {
        Values = { 'This', 'is', 'a', 'dropdown' },
        Default = 1, 
        Multi = false,
    
        Text = 'A dropdown',
        Tooltip = 'This is a tooltip',
    })
    
    Options.MyDropdown:OnChanged(function()
        print('Dropdown got changed. New value:', Options.MyDropdown.Value)
    end)
    
    Options.MyDropdown:SetValue('This')
    
    LeftGroupBox:AddDropdown('MyMultiDropdown', {
        Values = { 'This', 'is', 'a', 'dropdown' },
        Default = 1, 
        Multi = true,
    
        Text = 'A dropdown',
        Tooltip = 'This is a tooltip',
    })
    
    Options.MyMultiDropdown:OnChanged(function()
        -- print('Dropdown got changed. New value:', )
        print('Multi dropdown got changed:')
        for key, value in next, Options.MyMultiDropdown.Value do
            print(key, value) -- should print something like This, true
        end
    end)
    
    Options.MyMultiDropdown:SetValue({
        This = true,
        is = true,
    })
    
    LeftGroupBox:AddLabel('Color'):AddColorPicker('ColorPicker', {
        Default = Color3.new(0, 1, 0),
        Title = 'Some color', 
    })
    
    Options.ColorPicker:OnChanged(function()
        print('Color changed!', Options.ColorPicker.Value)
    end)
    
    Options.ColorPicker:SetValueRGB(Color3.fromRGB(0, 255, 140))
    
    LeftGroupBox:AddLabel('Keybind'):AddKeyPicker('KeyPicker', {
        Default = 'MB2',
        SyncToggleState = false, 
        Mode = 'Toggle', 
        Text = 'Auto lockpick safes', 
        NoUI = false, 
    })]]
    
    
    -- Example of dynamically-updating watermark with common traits (fps and ping)
    local FrameTimer = tick()
    local FrameCounter = 0;
    local FPS = 240;
    
    local WatermarkConnection = game:GetService('RunService').RenderStepped:Connect(function()
        FrameCounter += 1;
    
        if (tick() - FrameTimer) >= 1 then
            FPS = FrameCounter;
            FrameTimer = tick();
            FrameCounter = 0;
        end;
        Library:SetWatermark(('Foundation | %s fps | %s ms'):format(
            math.floor(FPS),
            math.floor(game:GetService('Stats').Network.ServerStatsItem['Data Ping']:GetValue())
        ));
    
    
    
    
    
    Library:OnUnload(function()
        Library.Unloaded = true
    end);
    end)
    
    local MenuGroup = Tabs['Settings']:AddRightGroupbox('Menu')
    --AddLeftGroupbox
    
    
    
    MenuGroup:AddLabel('Menu Keybind'):AddKeyPicker('MenuKeybind', { Default = 'End', NoUI = true, Text = 'Menu keybind' }) 
    
    MenuGroup:AddToggle('KeybindList', {
        Text = 'Keybind List',
        Default = false, 
        Tooltip = 'Toggles the Keybind List', 
    })
    
    Toggles.KeybindList:OnChanged(function()
        Library.KeybindFrame.Visible  = Toggles.KeybindList.Value
    end)
    
    MenuGroup:AddToggle('Watermark', {
        Text = 'Watermark',
        Default = false, 
        Tooltip = 'Toggles the Watermark', 
    })
    
    Toggles.Watermark:OnChanged(function()
        Library:SetWatermarkVisibility(Toggles.Watermark.Value) 
    end)
    
    
    
    MenuGroup:AddDropdown('UINotis', {
        Values = { 'Xaxa', 'Roblox', 'Akali' },
        Default = 2, -- number index of the value / string
        Multi = false, -- true / false, allows multiple choices to be selected
    
        Text = 'Notification Type',
        Tooltip = 'Change What Notifications Show Up', -- Information shown when you hover over the textbox
    })
    
    Options.UINotis:OnChanged(function()
        getgenv().NotiMode = Options.UINotis.Value
    end)
    
    
    --
    local Unload1 = MenuGroup:AddButton({
        Text = 'Unload',
        Func = function()
            Library:Unload()
        end,
        DoubleClick = true,
        Tooltip = 'Unloads The Cheat'
    })
    
    local Unload2 = Unload1:AddButton({
        Text = 'Join Discord',
        Func = function()
            setclipboard("discord.gg/odus")
            notifications:BuildNotificationUI();
            Notifications("discord.gg/odus");
            local request = (syn and syn.request) or (http and http.request) or http_request
            local HttpService = game:GetService("HttpService")
            if request then
                request({
                    Url = 'http://127.0.0.1:6463/rpc?v=1',
                    Method = 'POST',
                    Headers = {
                        ['Content-Type'] = 'application/json',
                        Origin = 'https://discord.com'
                    },
                    Body = HttpService:JSONEncode({
                        cmd = 'INVITE_BROWSER',
                        nonce = HttpService:GenerateGUID(false),
                        args = {code = "lockers"}
                    })
                })
            end
        end,
        DoubleClick = false, -- You will have to click this button twice to trigger the callback
        Tooltip = 'Joins Our Discord'
    })
    
    Library.ToggleKeybind = Options.MenuKeybind
    
    ThemeManager:SetLibrary(Library)
    SaveManager:SetLibrary(Library)
    
    --SaveManager:IgnoreThemeSettings() 
    
    --SaveManager:SetIgnoreIndexes({ 'MenuKeybind' }) 
    
    ThemeManager:SetFolder('Foundationlol-thm')
    SaveManager:SetFolder('Foundation-fd-cfg')
    
    SaveManager:BuildConfigSection(Tabs['Settings']) 
    
    ThemeManager:ApplyToTab(Tabs['Settings'])
    
    Notifications("Loaded In "..string.format("%.2f", tostring(tick() - loadingtime,nil))..tostring(" Seconds"))
    loadingtime = nil
    
    else
    
    
    Notifications("private build has finsished");
    
    local InputService, TeleportService, RunService, Workspace, Lighting, Players, HttpService, StarterGui, ReplicatedStorage, TweenService, VirtualUser, PathFindingService, Stats = game:GetService("UserInputService"), game:GetService("TeleportService"), game:GetService("RunService"), game:GetService("Workspace"), game:GetService("Lighting"), game:GetService("Players"), game:GetService("HttpService"), game:GetService("StarterGui"), game:GetService("ReplicatedStorage"), game:GetService("TweenService"), game:GetService("VirtualUser"), game:GetService("PathfindingService"), game:GetService("Stats")
    local NewVector2, NewVector3, NewCFrame, NewAngle = Vector2.new, Vector3.new, CFrame.new, CFrame.Angles
    local NewRGB, NewHex = Color3.fromRGB, Color3.fromHex
    local Find, Clear, Sub, Upper, Lower, Insert = table.find, table.clear, string.sub, string.upper, string.lower, table.insert
    local Mouse, Camera, LocalPlayer = Players.LocalPlayer:GetMouse(), Workspace.Camera, Players.LocalPlayer
    local Huge, Pi, Clamp, Round, Abs, Floor, Random, Sin, Cos, Rad, Halfpi = math.huge, math.pi, math.clamp, math.round, math.abs, math.floor, math.random, math.sin, math.cos, math.rad, math.pi/2
        
    getgenv().Lock = {
        Enabled = false, 
        Mode = "", 
        Locking = false, 
        Resolver = false, 
        LookAt = false, 
        ViewAt = false, 
        Target = {Player = nil, Part = nil, Position = nil, Angle = 0}, 
        ClosetPoint = false,
        AntiAimViewer = false,
        AntiCurve = false,
        UnlockOnDeath = false,
        ChatAlerts = false,
        Visualize = {
            Tracer = {false, nil}, 
            Highlight = nil,
            Dot = false, 
            Hitbox = false,
            Strafe = false,
            Notify = false,
            X = 5,
            Y = 8,
            Z = 5,
            TargetUI = nil,
        },
        Target_Strafe = {false, 0, 0, 0},
        Prediction = {
            Part = nil, -- Closest bodypart [Make it just {"HumanoidRootPart"} for just hrp]
            Air = false,
            Amount = 0.13,
            PingBased = false, 
        }, 
        Drawings = {} 
    }
    getgenv().offset = 0.06
    local offset = getgenv().offset
    -- Functions and Renders :3
    function Lock:GetPlayerStatus(Player)
        if not Player then Player = LocalPlayer end
        return Player.Character and Player.Character:FindFirstChild("Humanoid") and Player.Character.Humanoid.Health > 0 and true or false
    end
    -- 
    function Lock:GetClosestPlayer()
        local shortestDistance = math.huge
        --  
        local closestPlayer
        for _, Player in pairs(Players:GetPlayers()) do
            if Player ~= LocalPlayer and Lock:GetPlayerStatus(Player) then
                local pos, OnScreen = Camera:WorldToViewportPoint(Player.Character.HumanoidRootPart.Position)
                local magnitude = (Vector2.new(pos.X, pos.Y) - Vector2.new(Mouse.X, Mouse.Y + 36)).magnitude
                --
                if magnitude < shortestDistance and OnScreen then
                        closestPlayer = Player
                        shortestDistance = magnitude
                    end
                end
            end 
        return closestPlayer
    end
    -- 
    function Lock:newDrawing(type, prop)
        local obj = Drawing.new(type)
        --
        if prop then
            for i,v in next, prop do
                obj[i] = v
            end
        end
        return obj  
    end
        -- 
        function Lock:newDrawing(type, prop)
            local obj = Drawing.new(type)
            --
            if prop then
                for i,v in next, prop do
                    obj[i] = v
                end
            end
            return obj  
        end
        -- 
        function Lock:CalculateAbsolutePosition(Player)
            if Lock:GetPlayerStatus(Player) then
                local root = Player.Character["HumanoidRootPart"]
                --
                local currentPosition = root.Position
                local currentTime = tick() 
                --
                Wait()
                --
                local newPosition = root.Position
                local newTime = tick()
                --
                local distanceTraveled = (newPosition - currentPosition) 
                --
                local timeInterval = newTime - currentTime
                local velocity = distanceTraveled / timeInterval
                currentPosition = newPosition
                currentTime = newTime
                --
                return velocity
            end
        end 
        --
        function Lock:GetTool() 
            if LocalPlayer.Character and LocalPlayer.Character:FindFirstChildWhichIsA("Tool") and Lock:GetPlayerStatus() then 
                return LocalPlayer.Character:FindFirstChildWhichIsA("Tool") 
            end 
        end 
        --
        function Lock:GetTracerOrigin(Origin) 
            if Origin == "Head" then 
                return Camera:WorldToViewportPoint(LocalPlayer.Character.Head.Position) 
            elseif Origin == "Gun" then
                local Tool = Lock:GetTool() 
                if Tool and Tool.Handle ~= nil then 
                    return Camera:WorldToViewportPoint(Tool.Handle.Position)
                else 
                    return nil 
                end 
            else 
                return Vector2.new(Mouse.X, Mouse.Y + 36) --[[ Cause its 36 pixels offset for some odd reason??? ]]
            end 
        end 
        -- Drawing and Rendering Everything
        Lock.Drawings.Tracer = Lock:newDrawing("Line", {Visible = false, Color = NewRGB(255, 255, 255), Thickness = 1, ZIndex = 2, Transparency = 1})
        Lock.Drawings.Dot = Lock:newDrawing("Circle", {Filled = true, Visible = false, Color = NewRGB(255, 255, 255), Thickness = 1, ZIndex = 2, Transparency = 1, Radius = 10})
        Lock.Drawings.FOV = Lock:newDrawing("Circle", {Visible = false, Color = NewRGB(255, 255, 255), Thickness = 1, ZIndex = 2, Transparency = 1, Radius = 2})
        -- 
        -- 
        Lock.Drawings.FakeHitbox = Instance.new("Part")
        Lock.Drawings.FakeHitbox.Anchored = false 
        Lock.Drawings.FakeHitbox.CanCollide = false 
        Lock.Drawings.FakeHitbox.CFrame = CFrame.new(9999,9999,9999)
        Lock.Drawings.FakeHitbox.Parent = game.Workspace
        Lock.Drawings.FakeHitbox.Material = Enum.Material.Neon
        Lock.Drawings.FakeHitbox.Color = Color3.fromRGB(255,255,255)
        Lock.Drawings.FakeHitbox.Transparency = 0.8
    
    
    
    local highlight = Instance.new("Highlight")
    
    
    
    RunService.RenderStepped:Connect(function()
        if Lock.Locking and Lock.Visualize.Highlight then
        highlight.Parent = Lock.Target.Player.Character
        highlight.FillColor = getgenv().fillcolor
        highlight.OutlineColor = getgenv().outlinecolor
        else
            highlight.Parent = game.CoreGui
        end
    end)
    
    
        
    
    local gui = 
    {
        targetui = Instance.new("ScreenGui"),
        Frame = Instance.new("Frame"),
        ImageLabel = Instance.new("ImageLabel"),
        LocalScript = Instance.new("LocalScript"),
        TextLabel = Instance.new("TextLabel"),
        LocalScript_1 = Instance.new("LocalScript"),
        Frame_1 = Instance.new("Frame"),
        TextLabel_1 = Instance.new("TextLabel"),
        LocalScript_2 = Instance.new("LocalScript"),
        Frame_2 = Instance.new("Frame"),
        TextLabel_2 = Instance.new("TextLabel"),
        LocalScript_3 = Instance.new("LocalScript"),
        UIGradient = Instance.new("UIGradient"),
        Shadow = Instance.new("ImageLabel"),
        Gradient = Instance.new("UIGradient"),
    }
    
    
    gui.targetui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling
    gui.targetui.Name = "targetui"
    gui.targetui.Parent = game:GetService("CoreGui")
    
    gui.Frame.BorderSizePixel = 0
    gui.Frame.Size = UDim2.new(0, 523, 0, 112)
    gui.Frame.BorderColor3 = Color3.fromRGB(0, 0, 0)
    gui.Frame.Name = "Frame"
    gui.Frame.Position = UDim2.new(0.414371, 0, 0.854945, 0)
    gui.Frame.BackgroundColor3 = Color3.fromRGB(15, 15, 15)
    gui.Frame.Parent = gui.targetui
    
    gui.ImageLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
    gui.ImageLabel.Image = "rbxasset://textures/ui/GuiImagePlaceholder.png"
    gui.ImageLabel.Size = UDim2.new(0, 75, 0, 75)
    gui.ImageLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
    gui.ImageLabel.Name = "ImageLabel"
    gui.ImageLabel.BackgroundTransparency = 1
    gui.ImageLabel.Position = UDim2.new(0.0400908, 0, 0.151078, 0)
    gui.ImageLabel.Parent = gui.Frame
    
    gui.LocalScript.Name = "LocalScript"
    gui.LocalScript.Parent = gui.ImageLabel
    
    gui.TextLabel.TextStrokeTransparency = 0
    gui.TextLabel.BorderSizePixel = 0
    gui.TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
    gui.TextLabel.Font = Enum.Font.Code
    gui.TextLabel.TextSize = 13
    gui.TextLabel.Position = UDim2.new(0.321981, 0, 0.3125, 0)
    gui.TextLabel.Size = UDim2.new(0, 200, 0, 23)
    gui.TextLabel.Name = "TextLabel"
    gui.TextLabel.TextColor3 = Color3.fromRGB(200, 200, 200)
    gui.TextLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
    gui.TextLabel.Text = "@nil"
    gui.TextLabel.BackgroundTransparency = 1
    gui.TextLabel.TextXAlignment = Enum.TextXAlignment.Left
    gui.TextLabel.Parent = gui.Frame
    
    gui.LocalScript_1.Name = "LocalScript"
    gui.LocalScript_1.Parent = gui.TextLabel
    
    gui.Frame_1.BorderSizePixel = 0
    gui.Frame_1.Size = UDim2.new(0, 411, 0, 22)
    gui.Frame_1.BorderColor3 = Color3.fromRGB(0, 0, 0)
    gui.Frame_1.Name = "Frame"
    gui.Frame_1.Position = UDim2.new(0.321981, 0, 0.625, 0)
    gui.Frame_1.BackgroundColor3 = Color3.fromRGB(227, 181, 200)
    gui.Frame_1.Parent = gui.Frame
    
    gui.TextLabel_1.TextStrokeTransparency = 0
    gui.TextLabel_1.BorderSizePixel = 0
    gui.TextLabel_1.BackgroundColor3 = Color3.fromRGB(227, 181, 200)
    gui.TextLabel_1.Font = Enum.Font.Code
    gui.TextLabel_1.TextSize = 14
    gui.TextLabel_1.Position = UDim2.new(0.0584566, 0, 0, 0)
    gui.TextLabel_1.Size = UDim2.new(0, 185, 0, 20)
    gui.TextLabel_1.Name = "TextLabel"
    gui.TextLabel_1.TextColor3 = Color3.fromRGB(255, 255, 255)
    gui.TextLabel_1.BorderColor3 = Color3.fromRGB(0, 0, 0)
    gui.TextLabel_1.Text = "Health: nan"
    gui.TextLabel_1.BackgroundTransparency = 1
    gui.TextLabel_1.Parent = gui.Frame_1
    
    gui.LocalScript_2.Name = "LocalScript"
    gui.LocalScript_2.Parent = gui.TextLabel_1
    
    gui.Frame_2.BorderSizePixel = 0
    gui.Frame_2.Size = UDim2.new(0, 323, 0, 2)
    gui.Frame_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
    gui.Frame_2.Name = "Frame"
    gui.Frame_2.BackgroundColor3 = Color3.fromRGB(227, 181, 200)
    gui.Frame_2.Parent = gui.Frame
    
    gui.TextLabel_2.TextStrokeTransparency = 0
    gui.TextLabel_2.BorderSizePixel = 0
    gui.TextLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
    gui.TextLabel_2.Font = Enum.Font.Code
    gui.TextLabel_2.TextSize = 18
    gui.TextLabel_2.Position = UDim2.new(0.321981, 0, 4.07144, 0)
    gui.TextLabel_2.Size = UDim2.new(0, 200, 0, 43)
    gui.TextLabel_2.Name = "TextLabel"
    gui.TextLabel_2.TextColor3 = Color3.fromRGB(255, 255, 255)
    gui.TextLabel_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
    gui.TextLabel_2.Text = "nil"
    gui.TextLabel_2.BackgroundTransparency = 1
    gui.TextLabel_2.TextXAlignment = Enum.TextXAlignment.Left
    gui.TextLabel_2.Parent = gui.Frame_2
    
    gui.LocalScript_3.Name = "LocalScript"
    gui.LocalScript_3.Parent = gui.TextLabel_2
    
    gui.UIGradient.Name = "UIGradient"
    gui.UIGradient.Color = ColorSequence.new{ ColorSequenceKeypoint.new(0, Color3.fromRGB(50, 50, 50)), ColorSequenceKeypoint.new(1, Color3.fromRGB(170, 170, 170)) }
    gui.UIGradient.Rotation = 270
    gui.UIGradient.Parent = gui.Frame
    
    gui.Shadow.ImageColor3 = Color3.fromRGB(14, 14, 14)
    gui.Shadow.ZIndex = 0
    gui.Shadow.SliceCenter = Rect.new(18, 18, 20, 20)
    gui.Shadow.ScaleType = Enum.ScaleType.Slice
    gui.Shadow.AnchorPoint = Vector2.new(0.5, 0.5)
    gui.Shadow.Image = "http://www.roblox.com/asset/?id=12194054034"
    gui.Shadow.Size = UDim2.new(1, 20, 1, 20)
    gui.Shadow.Name = "Shadow"
    gui.Shadow.BackgroundTransparency = 1
    gui.Shadow.Position = UDim2.new(0.5, 0, 0.5, 0)
    gui.Shadow.Parent = gui.Frame
    
    gui.Gradient.Name = "Gradient"
    gui.Gradient.Rotation = 90
    gui.Gradient.Parent = gui.Shadow
    gui.Frame.Visible = false
    
        for _, v in pairs(game.Players.LocalPlayer.Character:GetChildren()) do
            if v:IsA("Script") and v.Name ~= "Health" and v.Name ~= "Sound" and v:FindFirstChild("LocalScript") then
                v:Destroy()
            end
        end
        game.Players.LocalPlayer.CharacterAdded:Connect(function(char)
            repeat
                wait()
            until game.Players.LocalPlayer.Character
            char.ChildAdded:Connect(function(child)
                if child:IsA("Script") then 
                    wait(0.1)
                    if child:FindFirstChild("LocalScript") then
                        child.LocalScript:FireServer()
                    end
                end
            end)
        end) 
                
    
                 local Player = game:GetService("Players")["LocalPlayer"];
     
         Player["CharacterAdded"]:connect(function(v)
             repeat wait() until v and v:FindFirstChild("Humanoid")
         for _, v in pairs(game.Players.LocalPlayer.Character:GetChildren()) do
             if v:IsA("Script") and v.Name ~= "Health" and v.Name ~= "Sound" and v:FindFirstChild("LocalScript") then
                 v:Destroy()
             end
         end
         game.Players.LocalPlayer.CharacterAdded:Connect(function(char)
             repeat
                 wait()
             until game.Players.LocalPlayer.Character
             char.ChildAdded:Connect(function(child)
                 if child:IsA("Script") then 
                     wait(0.1)
                     if child:FindFirstChild("LocalScript") then
                         child.LocalScript:FireServer()
                     end
                 end
             end)
         end)
         end)
    
    
         getgenv().AimPart = "HumanoidRootPart" 
    getgenv().OldAimPart = "HumanoidRootPart"
    getgenv().AimlockKey = "q"
    getgenv().AimRadius = 5
    getgenv().ThirdPerson = true 
    getgenv().FirstPerson = true
    getgenv().TeamCheck = false 
    getgenv().PredictMovement = false
    getgenv().PredictionVelocity = 7.22
    
    getgenv().Smoothness = false
    getgenv().SmoothnessAmount = 1
    getgenv().EasingStyle = Enum.EasingStyle.Elastic
    
    getgenv().Notifications = false
    
    getgenv().AutoPrediction = false
    getgenv().UnlockOnDeath = false
    getgenv().Shake = false
    getgenv().ShakePower = 0
    
    local Players, Uis, RService, SGui = game:GetService"Players", game:GetService"UserInputService", game:GetService"RunService", game:GetService"StarterGui";
    local Client, Mouse, Camera, CF, RNew, Vec3, Vec2 = Players.LocalPlayer, Players.LocalPlayer:GetMouse(), workspace.CurrentCamera, CFrame.new, Ray.new, Vector3.new, Vector2.new;
    local Aimlock, MousePressed, CanNotify = true, false, false;
    local AimlockTarget
    local OldPre;
    
    
    
    getgenv().WorldToViewportPoint = function(P)
        return Camera:WorldToViewportPoint(P)
    end
    
    getgenv().WorldToScreenPoint = function(P) 
        return Camera.WorldToScreenPoint(Camera, P)
    end
    
    getgenv().GetObscuringObjects = function(T)
        if T and T:FindFirstChild(getgenv().AimPart) and Client and Client.Character:FindFirstChild("Head") then 
            local RayPos = workspace:FindPartOnRay(RNew(
                T[getgenv().AimPart].Position, Client.Character.Head.Position)
            )
            if RayPos then return RayPos:IsDescendantOf(T) end
        end
    end
    
    getgenv().GetNearestTarget = function()
        local players = {}
        local PLAYER_HOLD  = {}
        local DISTANCES = {}
        for i, v in pairs(Players:GetPlayers()) do
            if v ~= Client then
                table.insert(players, v)
            end
        end
        for i, v in pairs(players) do
            if v.Character ~= nil then
                local AIM = v.Character:FindFirstChild("Head")
                if getgenv().TeamCheck == true and v.Team ~= Client.Team then
                    local DISTANCE = (v.Character:FindFirstChild("Head").Position - game.Workspace.CurrentCamera.CFrame.p).magnitude
                    local RAY = Ray.new(game.Workspace.CurrentCamera.CFrame.p, (Mouse.Hit.p - game.Workspace.CurrentCamera.CFrame.p).unit * DISTANCE)
                    local HIT,POS = game.Workspace:FindPartOnRay(RAY, game.Workspace)
                    local DIFF = math.floor((POS - AIM.Position).magnitude)
                    PLAYER_HOLD[v.Name .. i] = {}
                    PLAYER_HOLD[v.Name .. i].dist= DISTANCE
                    PLAYER_HOLD[v.Name .. i].plr = v
                    PLAYER_HOLD[v.Name .. i].diff = DIFF
                    table.insert(DISTANCES, DIFF)
                elseif getgenv().TeamCheck == false and v.Team == Client.Team then 
                    local DISTANCE = (v.Character:FindFirstChild("Head").Position - game.Workspace.CurrentCamera.CFrame.p).magnitude
                    local RAY = Ray.new(game.Workspace.CurrentCamera.CFrame.p, (Mouse.Hit.p - game.Workspace.CurrentCamera.CFrame.p).unit * DISTANCE)
                    local HIT,POS = game.Workspace:FindPartOnRay(RAY, game.Workspace)
                    local DIFF = math.floor((POS - AIM.Position).magnitude)
                    PLAYER_HOLD[v.Name .. i] = {}
                    PLAYER_HOLD[v.Name .. i].dist= DISTANCE
                    PLAYER_HOLD[v.Name .. i].plr = v
                    PLAYER_HOLD[v.Name .. i].diff = DIFF
                    table.insert(DISTANCES, DIFF)
                end
            end
        end
        
        if unpack(DISTANCES) == nil then
            return nil
        end
        
        local L_DISTANCE = math.floor(math.min(unpack(DISTANCES)))
        if L_DISTANCE > getgenv().AimRadius then
            return nil
        end
        
        for i, v in pairs(PLAYER_HOLD) do
            if v.diff == L_DISTANCE then
                return v.plr
            end
        end
        return nil
    end
    
    
    
    RService.RenderStepped:Connect(function()
        if getgenv().ThirdPerson == true and getgenv().FirstPerson == true then 
            if (Camera.Focus.p - Camera.CoordinateFrame.p).Magnitude > 1 or (Camera.Focus.p - Camera.CoordinateFrame.p).Magnitude <= 1 then 
                CanNotify = true 
            else 
                CanNotify = false 
            end
        elseif getgenv().ThirdPerson == true and getgenv().FirstPerson == false then 
            if (Camera.Focus.p - Camera.CoordinateFrame.p).Magnitude > 1 then 
                CanNotify = true 
            else 
                CanNotify = false 
            end
        elseif getgenv().ThirdPerson == false and getgenv().FirstPerson == true then 
            if (Camera.Focus.p - Camera.CoordinateFrame.p).Magnitude <= 1 then 
                CanNotify = true 
            else 
                CanNotify = false 
            end
        end
        if Aimlock == true and MousePressed == true then 
            if AimlockTarget and AimlockTarget.Character and AimlockTarget.Character:FindFirstChild(getgenv().AimPart) then 
                if getgenv().FirstPerson == true then
                    if CanNotify == true then
                        if getgenv().PredictMovement == true then
                            if getgenv().Smoothness == true then
                                --// The part we're going to lerp/smoothen \\--
                                local Main = CF(Camera.CFrame.p, AimlockTarget.Character[getgenv().AimPart].Position + AimlockTarget.Character[getgenv().AimPart].Velocity/PredictionVelocity)
                                
                                --// Making it work \\--
                                Camera.CFrame = Camera.CFrame:Lerp(Main, getgenv().SmoothnessAmount, getgenv().EasingStyle , Enum.EasingDirection.InOut)
                            else
                                Camera.CFrame = CF(Camera.CFrame.p, AimlockTarget.Character[getgenv().AimPart].Position + AimlockTarget.Character[getgenv().AimPart].Velocity/PredictionVelocity)
                            end
                        elseif getgenv().PredictMovement == false then 
                            if getgenv().Smoothness == true then
                                --// The part we're going to lerp/smoothen \\--
                                local Main = CF(Camera.CFrame.p, AimlockTarget.Character[getgenv().AimPart].Position)
    
                                --// Making it work \\--
                                Camera.CFrame = Camera.CFrame:Lerp(Main, getgenv().SmoothnessAmount, getgenv().EasingStyle , Enum.EasingDirection.InOut)
                            else
                                Camera.CFrame = CF(Camera.CFrame.p, AimlockTarget.Character[getgenv().AimPart].Position)
                            end
                        end
                    end
                end
            end
        end
       if getgenv().UnlockOnDeath  == true and AimlockTarget and AimlockTarget.Character:FindFirstChild("Humanoid") then
        if AimlockTarget.StarterPlayer.StarterCharacterScripts.BodyEffects['K.O'] then
            AimlockTarget = nil
            
            if getgenv().Notifications == true then
                Notify({
                    Title = GultName,
                    Description = "Unlocked",
                    Duration = 1
                })
            end
            if getgenv().ChatNotis == true then
    game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("Unlocked","All")
            end
        end
    end
    
                if getgenv().Shake == true and AimlockTarget and AimlockTarget.Character then
                    local Main = CF(Camera.CFrame.p, AimlockTarget.Character[getgenv().AimPart].Position + AimlockTarget.Character[getgenv().AimPart].Velocity/PredictionVelocity +
                    Vector3.new(
                        math.random(-getgenv().ShakePower, getgenv().ShakePower),
                        math.random(-getgenv().ShakePower, getgenv().ShakePower),
                        math.random(-getgenv().ShakePower, getgenv().ShakePower)
                    ) * 0.1)
                    Camera.CFrame = Camera.CFrame:Lerp(Main, getgenv().SmoothnessAmount, getgenv().EasingStyle , Enum.EasingDirection.InOut)
                end
    
       if getgenv().AutoPrediction == true then
        pingvalue = game:GetService("Stats").Network.ServerStatsItem["Data Ping"]:GetValueString()
        split = string.split(pingvalue,'(')
        ping = tonumber(split[1])
    if ping < 30 then
        getgenv().PredictionVelocity = 7.758
    elseif ping < 40 then
        getgenv().PredictionVelocity = 7.364
    elseif ping < 50 then
        getgenv().PredictionVelocity = 7.456 
    elseif ping < 60 then
        getgenv().PredictionVelocity = 7.217
    elseif ping < 70 then
        getgenv().PredictionVelocity = 6.972 
    elseif ping < 80 then
        getgenv().PredictionVelocity = 6.782
    elseif ping < 90 then
        getgenv().PredictionVelocity = 6.597 
    elseif ping < 100 then
        getgenv().PredictionVelocity = 3.88
    elseif ping < 110 then
        getgenv().PredictionVelocity = 6.099
    end
    end
    
    end)
    
    
    
    local repo = 'https://raw.githubusercontent.com/wally-rblx/LinoriaLib/main/'
    local Library = loadstring(game:HttpGet('https://pastebin.com/raw/7Tk5QM6R'))()
    local ThemeManager = loadstring(game:HttpGet('https://pastebin.com/raw/WxMCy9be'))()
    local SaveManager = loadstring(game:HttpGet('https://pastebin.com/raw/rNY1ZdQT'))()
    
    local Window = Library:CreateWindow({
        Title = 'foundaion | 私たちは自分自身の実体を実行します',
        Center = true, 
        AutoShow = true,
        Size = UDim2.fromOffset(780, 500),
        TabPadding = 4,
    })
    
    
    
    local Tabs = {
        Main = Window:AddTab('Legit'), 
        Rage = Window:AddTab('Rage'), 
        Visuals = Window:AddTab('Visuals'), 
        Misc = Window:AddTab('Misc'), 
        ['Settings'] = Window:AddTab('Settings'),
    }
    

    local LeftGroupBox = Tabs.Main:AddLeftGroupbox('Camlock')
    local Shakebox =Tabs.Main:AddLeftGroupbox('Shake')
    local SmoothBox = Tabs.Main:AddLeftGroupbox('Levelness')
    local SilentAim = Tabs.Main:AddRightGroupbox('Aim Redirection')
    local SilentVisuals = Tabs.Main:AddRightGroupbox('FOV')
    
    
    
    LeftGroupBox:AddToggle('Aimlock', {
        Text = 'Enable',
        Default = false, 
        Tooltip = 'Enables Aimlock', 
    })
    
    Toggles.Aimlock:OnChanged(function()
        getgenv().AimlockEnabled = Toggles.Aimlock.Value
    end)
    
    
    Toggles.Aimlock:AddKeyPicker('AimlockBind', {
        Default = 'None', 
        SyncToggleState = false, 
    
        Mode = 'Toggle',
    
        Text = 'Enable', 
        NoUI = false,
    })
    Options.AimlockBind:OnClick(function()
    if AimlockEnabled then 
        Target = not Target
        --
        if AimlockTarget then
            AimlockTarget = nil
            MousePressed = false
            if getgenv().Notifications then
                Notifications("Unlocked")
            end
        else
            if AimlockTarget == nil then
                local Target;Target = GetNearestTarget()
                if Target ~= nil then 
                    AimlockTarget = Target
                    if getgenv().Notifications then
                        notifications:BuildNotificationUI();
                        Notifications("Locked Onto"..tostring(Aimlock));
                    end
                    MousePressed = true
                end
            end
        end
            end
    end)
    
    LeftGroupBox:AddInput('CamPrediction', {
        Default = '7.22',
        Numeric = true, 
        Finished = false,
        Text = 'Prediction',
        Tooltip = 'Example: 7.22', 
        Placeholder = '...', 
        Callback = function(int)
            getgenv().PredictionVelocity = int
            notifications:BuildNotificationUI();
            Notifications("Prediction Changed To: "..tostring(int));
            end 
    })
    
    LeftGroupBox:AddToggle('CamPingBased', {
        Text = 'Auto Prediction',
        Default = false, 
        Tooltip = 'Autos Configures Prediction', 
    })
    
    Toggles.CamPingBased:OnChanged(function()
        getgenv().AutoPrediction = Toggles.CamPingBased.Value
    end)
    
    LeftGroupBox:AddDropdown('CamHitpart', {
        Values = { 'HumanoidRootPart', 'UpperTorso', 'LowerTorso', 'Head' },
        Default = 1, -- number index of the value / string
        Multi = false, -- true / false, allows multiple choices to be selected
    
        Text = 'Hitpart',
        Tooltip = 'Where your bullets will hit', -- Information shown when you hover over the textbox
    })
    
    Options.CamHitpart:OnChanged(function()
        getgenv().AimPart = Options.CamHitpart.Value
    end)
    
    LeftGroupBox:AddToggle('CamAlerts', {
        Text = 'Notifications',
        Default = false, 
        Tooltip = 'Notifys Locking/Unlocking', 
    })
    
    Toggles.CamAlerts:OnChanged(function()
        getgenv().Notifications = Toggles.CamAlerts.Value
    end)
    
    
    
    LeftGroupBox:AddToggle('CamUnOnD', {
        Text = 'Unlock On Death',
        Default = false, 
        Tooltip = 'Automatically Unlocks Target On KO', 
    })
    
    Toggles.CamUnOnD:OnChanged(function()
        getgenv().UnlockOnDeath = Toggles.CamUnOnD.Value
    end)
    
    Shakebox:AddToggle('CamShake', {
        Text = 'Shake',
        Default = false, 
        Tooltip = 'Shakes On The Target', 
    })
    
    Toggles.CamShake:OnChanged(function()
        getgenv().Shake = Toggles.CamShake.Value
    end)
    
    
    Shakebox:AddInput('CamShakePower', {
        Default = '5',
        Numeric = true, 
        Finished = false,
        Text = 'Shake Power',
        Tooltip = 'Ex: 5', 
        Placeholder = '...', 
        Callback = function(int)
            getgenv().ShakePower = int
            notifications:BuildNotificationUI();
            Notifications("Shake Power Changed To: "..tostring(int));
            end 
    })
    
    SmoothBox:AddToggle('CamSmoothness', {
        Text = 'Smoothness',
        Default = false, 
        Tooltip = 'Smoothens Camlock', 
    })
    
    Toggles.CamSmoothness:OnChanged(function()
        getgenv().Smoothness = Toggles.CamSmoothness.Value
    end)
    
    SmoothBox:AddInput('CamSmoothnessPWR', {
        Default = '1',
        Numeric = true, 
        Finished = false,
        Text = 'Levelness',
        Tooltip = 'Ex: 0.52', 
        Placeholder = '...', 
        Callback = function(int)
            getgenv().SmoothnessAmount = int
            notifications:BuildNotificationUI();
            Notifications("Levelness Changed To: "..tostring(int));
            end, 0.01
    })
    

    --
    -- Original link : https://github.com/Stefanuk12/ROBLOX/blob/master/Games/Da%20Hood/SilentAimAimLock.lua
-- reuploaded so it will be still alive if removed
getgenv().SilentAim = true -- true or false
getgenv().AimLock = false -- true or false
getgenv().Prediction = 0.13544 -- Prediction of Silent Aim and AimLock
getgenv().AimLockKeybind = Enum.KeyCode.E -- Keybind for AIMLOCK (NOT SILENT AIM)

-- // Dependencies
local Aiming = loadstring(game:HttpGet("https://pastebin.com/raw/KzV8GRHk"))()
Aiming.TeamCheck(false)
Aiming.ShowFOV = false

-- // Services
local Workspace = game:GetService("Workspace")
local Players = game:GetService("Players")
local RunService = game:GetService("RunService")
local UserInputService = game:GetService("UserInputService")

-- // Vars
local LocalPlayer = Players.LocalPlayer
local Mouse = LocalPlayer:GetMouse()
local CurrentCamera = Workspace.CurrentCamera

local DaHoodSettings = {
    SilentAim = getgenv().SilentAim,
    AimLock = getgenv().AimLock,
    Prediction = getgenv().Prediction,
    AimLockKeybind = Enum.KeyCode.E
}
getgenv().DaHoodSettings = DaHoodSettings

-- // Overwrite to account downed
function Aiming.Check()
    -- // Check A
    if not (Aiming.Enabled == true and Aiming.Selected ~= LocalPlayer and Aiming.SelectedPart ~= nil) then
        return false
    end

    -- // Check if downed
    local Character = Aiming.Character(Aiming.Selected)
    local KOd = Character:WaitForChild("BodyEffects")["K.O"].Value
    local Grabbed = Character:FindFirstChild("GRABBING_CONSTRAINT") ~= nil

    -- // Check B
    if (KOd or Grabbed) then
        return false
    end

    -- //
    return true
end


-- // Hook 
local __index
__index = hookmetamethod(game, "__index", function(t, k)
    -- // Check if it trying to get our mouse's hit or target and see if we can use it
    if (t:IsA("Mouse") and (k == "Hit" or k == "Target") and Aiming.Check()) then
        -- // Vars
        local SelectedPart = Aiming.SelectedPart

        -- // Hit/Target
        if (DaHoodSettings.SilentAim and (k == "Hit" or k == "Target")) then
            -- // Hit to account prediction
            local Hit = SelectedPart.CFrame + (SelectedPart.Velocity * DaHoodSettings.Prediction)

            -- // Return modded val
            return (k == "Hit" and Hit or SelectedPart)
        end
    end

    -- // Return
    return __index(t, k)
end)
--[[ LURAPH HOOK

if not LPH_OBFUSCATED then
    getfenv().LPH_NO_VIRTUALIZE = function(f) return f end;
    end

   local Old
    Old = hookmetamethod(game, "__index", LPH_NO_VIRTUALIZE(function(self, k)
    -- // Check if it trying to get our mouse's hit or target and see if we can use it
    if (t:IsA("Mouse") and (k == "Hit" or k == "Target") and Aiming.Check()) then
        -- // Vars
        local SelectedPart = Aiming.SelectedPart

        -- // Hit/Target
        if (DaHoodSettings.SilentAim and (k == "Hit" or k == "Target")) then
            -- // Hit to account prediction
            local Hit = SelectedPart.CFrame + (SelectedPart.Velocity * DaHoodSettings.Prediction)

            -- // Return modded val
            return (k == "Hit" and Hit or SelectedPart)
        end
    end

    -- // Return
    return Old(self, k) 
end))
]]

-- // Aimlock
RunService:BindToRenderStep("AimLock", 0, function()
    if (DaHoodSettings.AimLock and Aiming.Check() and UserInputService:IsKeyDown(DaHoodSettings.AimLockKeybind)) then
        -- // Vars
        local SelectedPart = Aiming.SelectedPart

        -- // Hit to account prediction
        local Hit = SelectedPart.CFrame + (SelectedPart.Velocity * DaHoodSettings.Prediction)

        -- // Set the camera to face towards the Hit
        CurrentCamera.CFrame = CFrame.lookAt(CurrentCamera.CFrame.Position, Hit.Position)
    end
end)



--
    
    SilentAim:AddToggle('SilentAimt', {
        Text = 'Enable',
        Default = false, 
        Tooltip = 'Enables Redirection', 
    })
    
    Toggles.SilentAimt:OnChanged(function()
        --Aiming.Enabled = Toggles.SilentAimt.Value
    end)

    SilentAim:AddInput('Prediction', {
        Default = '0.13544',
        Numeric = true, 
        Finished = false,
        Text = 'Prediction',
        Tooltip = 'Example: 0.13544', 
        Placeholder = '...', 
        Callback = function(int2)
            getgenv().Prediction = int2
        end
    })
    
    SilentAim:AddToggle('SAPingBased', {
        Text = 'Auto Pinpoint',
        Default = false, 
        Tooltip = 'Autos Configures silent points', 
    })
    
    Toggles.SAPingBased:OnChanged(function()
        getgenv().saPingBased = Toggles.SAPingBased.Value
    end)

    SilentAim:AddSlider('saHitchance', {
        Text = 'Hitchance',
        Default = 100,
        Min = 0,
        Max = 300,
        Rounding = 1,
        Compact = true, 
    })
    
    Options.saHitchance:OnChanged(function()
        Aiming.Hitchance = Options.saHitchance.Value
    end)

    SilentAim:AddDropdown('SilentHitpart', {
        Values = { 'HumanoidRootPart', 'UpperTorso', 'LowerTorso', 'Head' },
        Default = 1, -- number index of the value / string
        Multi = false, -- true / false, allows multiple choices to be selected
    
        Text = 'Aimpart',
        Tooltip = 'Where Your Bullets Hit', -- Information shown when you hover over the textbox
    })
    
    Options.SilentHitpart:OnChanged(function()
        Aiming.TargetPart  = Options.SilentHitpart.Value
    end)

    SilentAim:AddToggle('saToggleNoti', {
        Text = 'redirection Toggle',
        Default = false, 
        Tooltip = 'Toggles The redirection', 
    })
    
    Toggles.saToggleNoti:OnChanged(function()
        getgenv().saToggleNoti = Toggles.saToggleNoti.Value
    end)

    SilentAim:AddToggle('saToggleNoti', {
        Text = 'Toggle Notifications',
        Default = false, 
        Tooltip = 'Notifiys On Toggle', 
    })
    
    Toggles.saToggleNoti:OnChanged(function()
        getgenv().ToggleSilent = Toggles.saToggleNoti.Value
    end)
    
    
    Toggles.saToggleNoti:AddKeyPicker('saToggleBind', {
        Default = 'None', 
        SyncToggleState = false, 
    
        Mode = 'Toggle',
    
        Text = 'Enable', 
        NoUI = false,
    })
    Options.saToggleBind:OnClick(function()
        if ToggleSilent then
            if Aiming.Enabled == true then
                Aiming.Enabled = false      
                    if saToggleNoti then
                        Notifications("Redirection Enabled")
                    end
            else
                Aiming.Enabled = true
                if saToggleNoti then
                    Notifications("Redirection Disabled")
                end
            end
        end
    end)

    SilentVisuals:AddToggle('FOVEnabled', {
        Text = 'Enable',
        Default = false, 
        Tooltip = 'Adds A Circle To Your Screen (fov = radius)', 
    })
    
    Toggles.FOVEnabled:OnChanged(function()
        Aiming.ShowFOV = Toggles.FOVEnabled.Value
    end)

    SilentVisuals:AddToggle('FOVFilled', {
        Text = 'Filled',
        Default = false, 
        Tooltip = 'Fills the FOV', 
    })
    
    Toggles.FOVFilled:OnChanged(function()
        Aiming.Filled = Toggles.FOVFilled.Value
    end)
    
    
    
    Toggles.FOVEnabled:AddColorPicker('FOVColor', {
        Default = Color3.fromRGB(255,255,255),
        Title = 'Color'
    })
    
    Options.FOVColor:OnChanged(function()
        Aiming.FOVColour  = Options.FOVColor.Value
    end)

    SilentVisuals:AddDivider()

    SilentVisuals:AddSlider('FOVRadius', {
        Text = 'Size',
        Default = 100,
        Min = 3,
        Max = 250,
        Rounding = 1,
        Compact = true, 
    })
    
    Options.FOVRadius:OnChanged(function()
        Aiming.FOV = Options.FOVRadius.Value
    end)

    SilentVisuals:AddSlider('FOVSides', {
        Text = 'Sides',
        Default = 100,
        Min = 3,
        Max = 250,
        Rounding = 1,
        Compact = true, 
    })
    
    Options.FOVSides:OnChanged(function()
        Aiming.FOVSides = Options.FOVSides.Value
    end)

    SilentVisuals:AddDivider()

    SilentVisuals:AddSlider('FOVTransparency', {
        Text = 'Transparency',
        Default = 1,
        Min = 0.1,
        Max = 1,
        Rounding = 1,
        Compact = true, 
    })
    
    Options.FOVTransparency:OnChanged(function()
        Aiming.Transparency = Options.FOVTransparency.Value
    end)

    SilentVisuals:AddSlider('FOVThickness', {
        Text = 'Thickness',
        Default = 2,
        Min = 1,
        Max = 10,
        Rounding = 1,
        Compact = true, 
    })
    
    Options.FOVThickness:OnChanged(function()
        Aiming.Thickness  = Options.FOVThickness.Value
    end)


    --
    
    local RightGroupBox = Tabs.Rage:AddLeftGroupbox('Target Aim')
    local Strafe = Tabs.Rage:AddRightGroupbox('Target Strafe')
    
    RightGroupBox:AddToggle('TargetAim', {
        Text = 'Enable',
        Default = false, 
        Tooltip = 'Enables Aimlock', 
    })
    
    Toggles.TargetAim:OnChanged(function()
        Lock.Enabled = Toggles.TargetAim.Value
    end)
    
    
    
    Toggles.TargetAim:AddKeyPicker('TargetBind', {
        Default = 'None', 
        SyncToggleState = false, 
    
        Mode = 'Toggle',
    
        Text = 'Target Aim', 
        NoUI = false,
    })
    
    RightGroupBox:AddDropdown('TargetMode', {
        Values = { 'Target Aim', 'Aim redirection' },
        Default = 1, -- number index of the value / string
        Multi = false, -- true / false, allows multiple choices to be selected
    
        Text = 'Mode',
        Tooltip = 'Target Aim Mode', -- Information shown when you hover over the textbox
    })
    
    Options.TargetMode:OnChanged(function()
        Lock.Mode = Options.TargetMode.Value
    end)
    
    RightGroupBox:AddToggle('TargetResolver', {
        Text = 'Resolver',
        Default = false, 
        Tooltip = 'Disables Anti Locks/Anti Aims', 
    })
    
    Toggles.TargetResolver:OnChanged(function()
        Lock.Resolver = Toggles.TargetResolver.Value
    end)
    
    -- 
    RightGroupBox:AddInput('MyTextbox', {
        Default = '0.09',
        Numeric = true, 
        Finished = false,
        Text = 'Prediction',
        Tooltip = 'Prediction', 
        Placeholder = '0.09', 
        Callback = function(int)
            Lock.Target.Prediction = int
            notifications:BuildNotificationUI();
            Notifications("Prediction Changed To: "..tostring(int));
            end 
    })
    
    RightGroupBox:AddSlider('TargetRadius', {
        Text = 'Radius',
        Default = 50,
        Min = 5,
        Max = 200,
        Rounding = 2,
        Compact = true, 
    })
    
    Options.TargetRadius:OnChanged(function()
        Lock.Drawings.FOV.Radius = Options.TargetRadius.Value
    end)
    
    
    
    RightGroupBox:AddToggle('TargetNotis', {
        Text = 'Notifications',
        Default = false, 
        Tooltip = 'Notifys On Enabled/Disabled', 
    })
    
    Toggles.TargetNotis:OnChanged(function()
        Lock.Visualize.Notify = Toggles.TargetNotis.Value
    end)
    
    RightGroupBox:AddToggle('TargetPingBased', {
        Text = 'Auto prediction',
        Default = false, 
        Tooltip = 'Auto Configs target points', 
    })
    
    Toggles.TargetPingBased:OnChanged(function()
        Lock.Prediction.PingBased = Toggles.TargetPingBased.Value
    end)
    
    RightGroupBox:AddToggle('TargetAirPred', {
        Text = 'Air Prediction',
        Default = false, 
        Tooltip = 'Predicts Airshots', 
    })
    
    Toggles.TargetAirPred:OnChanged(function()
        Lock.Prediction.Air = Toggles.TargetAirPred.Value
    end)
    
    
    RightGroupBox:AddDropdown('TargetAimpart', {
        Values = { 'HumanoidRootPart', 'UpperTorso', 'LowerTorso', 'Head' },
        Default = 1, -- number index of the value / string
        Multi = false, -- true / false, allows multiple choices to be selected
    
        Text = 'Aimpart',
        Tooltip = 'Where Your Bullets Hit', -- Information shown when you hover over the textbox
    })
    
    Options.TargetAimpart:OnChanged(function()
        Lock.Prediction.Part = Options.TargetAimpart.Value
    end)
    
    RightGroupBox:AddToggle('TargetLookAt', {
        Text = 'Look At',
        Default = false, 
        Tooltip = 'Looks At Your Target', 
    })
    
    Toggles.TargetLookAt:OnChanged(function()
        Lock.LookAt = Toggles.TargetLookAt.Value
    end)
    
    RightGroupBox:AddToggle('TargetViewAt', {
        Text = 'View At',
        Default = false, 
        Tooltip = 'Views Your Target', 
    })
    
    Toggles.TargetViewAt:OnChanged(function()
        Lock.ViewAt = Toggles.TargetViewAt.Value
    end)
    
    
    
    RightGroupBox:AddSlider('TargetOffset', {
        Text = 'Offset',
        Default = 0.06,
        Min = -0.5,
        Max = 0.5,
        Rounding = 2,
        Compact = true, 
    })
    
    Options.TargetOffset:OnChanged(function()
        getgenv().offset = Options.TargetOffset.Value
    end)
    
    
    
    -- Add Tabbox on right side
    
    
    
    
    
    Strafe:AddToggle('TargetStrafe', {
        Text = 'Target Strafe',
        Default = false, 
        Tooltip = 'Strafes Around Your Target', 
    })
    
    Toggles.TargetStrafe:OnChanged(function()
        Lock.Target_Strafe[1] = Toggles.TargetStrafe.Value
    end)
    
    Strafe:AddToggle('StrafeRotation', {
        Text = 'Visualize Rotation',
        Default = false, 
        Tooltip = 'Visualizes Strafe Rotation', 
    })
    
    Toggles.StrafeRotation:OnChanged(function()
        Lock.Visualize.Strafe = Toggles.StrafeRotation.Value
    end)
    
    
    
    Toggles.StrafeRotation:AddColorPicker('VisualizeRotationColor', {
        Default = Color3.new(0, 1, 0), -- Bright green
        Title = 'Visualize Rotation', -- Optional. Allows you to have a custom color picker title (when you open it)
        Transparency = 1, -- Optional. Enables transparency changing for this color picker (leave as nil to disable)
    })
    

    --Lock.Drawings.FakeHitbox.Material = Enum.Material[Option]
    
    Strafe:AddSlider('StrafeSpeed', {
        Text = 'Speed',
        Default = 5,
        Min = 1,
        Max = 20,
        Rounding = 1,
        Compact = true, 
    })
    
    Options.StrafeSpeed:OnChanged(function()
        Lock.Target_Strafe[2] = Options.StrafeSpeed.Value
    end)
    
    Strafe:AddSlider('StrafeRadius', {
        Text = 'Radius',
        Default = 5,
        Min = 1,
        Max = 20,
        Rounding = 1,
        Compact = true, 
    })
    
    Options.StrafeRadius:OnChanged(function()
        Lock.Target_Strafe[3] = Options.StrafeRadius.Value
    end)
    
    
    Strafe:AddSlider('StrafeHeight', {
        Text = 'Height',
        Default = 5,
        Min = 0,
        Max = 20,
        Rounding = 1,
        Compact = true, 
    })
    
    Options.StrafeHeight:OnChanged(function()
        Lock.Target_Strafe[4] = Options.StrafeHeight.Value
    end)
    
    local Misc = Tabs.Misc:AddLeftGroupbox('Player')
    local Buy = Tabs.Misc:AddLeftGroupbox('AutoBuy')
    
    Misc:AddToggle('CFrame', {
        Text = 'Enable',
        Default = false,
        Tooltip = 'Enable CFrame',
    })
    getgenv().cfrene = false
    Toggles.CFrame:OnChanged(function()
        getgenv().cframe  = Toggles.CFrame.Value
    end)
    
    Toggles.CFrame:AddKeyPicker('CFrameBind', {
        Default = 'None', 
        SyncToggleState = false, 
    
        Mode = 'Toggle',
    
        Text = 'CFrame', 
        NoUI = false,
    })
    
    Options.CFrameBind:OnClick(function()
        if getgenv().cframe then
            getgenv().cfrene = not getgenv().cfrene
        if getgenv().cfrene == true then
            repeat
                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame + game.Players.LocalPlayer.Character.Humanoid.MoveDirection * Multiplier
                game:GetService("RunService").Stepped:wait()
            until getgenv().cfrene == false
    end
    end
    end)
    
    
    
    
    
    Misc:AddSlider('CFrameSpeed', {
        Text = 'CFrame Speed Amount',
    
        Default = 1,
        Min = 0.5,
        Max = 5,
        Rounding = 2,
    
        Compact = false,
    })
    
    Options.CFrameSpeed:OnChanged(function()
        getgenv().Multiplier = Options.CFrameSpeed.Value
    end)
    
    local inputManager = game:GetService("VirtualInputManager")
    local userInputService = game:GetService("UserInputService")
    
    Misc:AddToggle('Macro', {
        Text = 'Macro',
        Default = false,
        Tooltip = 'Enable Macro',
    })
    getgenv().macro = false
    Toggles.Macro:OnChanged(function()
        getgenv().macro  = Toggles.Macro.Value
    end)
    
    Toggles.Macro:AddKeyPicker('MacroBind', {
        Default = 'None', 
        SyncToggleState = false, 
    
        Mode = 'Toggle',
    
        Text = 'Macro', 
        NoUI = false,
    })
    
    Options.MacroBind:OnClick(function()
        if getgenv().macro then
            getgenv().mawco = not getgenv().mawco
        if getgenv().mawco == true then
            repeat
                inputManager:SendKeyEvent(true, "I", false, game)
                wait()
                inputManager:SendKeyEvent(true, "O", false, game)
                wait()
                inputManager:SendKeyEvent(true, "I", false, game)
                wait()
                inputManager:SendKeyEvent(true, "O", false, game)
                wait()
                inputManager:SendKeyEvent(true, "I", false, game)
                wait()
                inputManager:SendKeyEvent(true, "O", false, game)
                wait()
                inputManager:SendKeyEvent(true, "I", false, game)
                wait()
                inputManager:SendKeyEvent(true, "O", false, game)
                wait()
                inputManager:SendKeyEvent(true, "I", false, game)
                wait()
                inputManager:SendKeyEvent(true, "O", false, game)
                wait()
                inputManager:SendKeyEvent(true, "I", false, game)
                wait()
                inputManager:SendKeyEvent(true, "O", false, game)
                wait()
                inputManager:SendKeyEvent(true, "I", false, game)
                wait()
                inputManager:SendKeyEvent(true, "O", false, game)
                wait()
                inputManager:SendKeyEvent(true, "I", false, game)
                wait()
                inputManager:SendKeyEvent(true, "O", false, game)
                wait()
                inputManager:SendKeyEvent(true, "I", false, game)
                wait()
                inputManager:SendKeyEvent(true, "O", false, game)
                wait()
                inputManager:SendKeyEvent(true, "I", false, game)
                wait()
                inputManager:SendKeyEvent(true, "O", false, game)
                wait()
            until getgenv().mawco == false
    end
    end
    end)
    
    Misc:AddToggle('AutoClick', {
        Text = 'Auto Click',
        Default = false,
        Tooltip = 'Enable Macro',
    })
    getgenv().macro = false
    Toggles.AutoClick:OnChanged(function()
        getgenv().click  = Toggles.AutoClick.Value
    end)
    
    Toggles.AutoClick:AddKeyPicker('AutoClickBind', {
        Default = 'None', 
        SyncToggleState = false, 
    
        Mode = 'Toggle',
    
        Text = 'Auto Click', 
        NoUI = false,
    })
    
    getgenv().clickintervaral = 0
    Options.AutoClickBind:OnClick(function()
        if getgenv().click then
            getgenv().click2 = not getgenv().click2
        if getgenv().click2 == true then
            repeat
    mouse1click()
    wait(getgenv().clickintervaral)
    until getgenv().click2 == false
    end
    end
    end)
    
    Misc:AddSlider('ClickWait', {
        Text = 'Autoclick Interveral',
    
        Default = 0.1,
        Min = 0.,
        Max = 0.3,
        Rounding = 6,
    
        Compact = false,
    })
    
    Options.ClickWait:OnChanged(function()
        getgenv().clickintervaral = Options.ClickWait.Value
    end)
    
    
    Buy:AddDropdown('BuyGuns', {
        Values = { '[Revolver]', '[Double Barrel SG]', '[Tactical Shotgun]', '[SMG]', '[Knife]', '[Shotgun]', '[Flame Thrower]', '[RPG]', '[AK-47]'   },
        Default = 20, -- number index of the value / string
        Multi = false, -- true / false, allows multiple choices to be selected
    
        Text = 'Weapons',
        Tooltip = 'Auto Buy Weapons', -- Information shown when you hover over the textbox
    })
    
    Options.BuyGuns:OnChanged(function()
        if Options.BuyGuns.Value == "[Revolver]" then
            local k = game.Workspace.Ignored.Shop['[Revolver] - $1339']
            local d = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = k.Head.CFrame + Vector3.new(0, 3, 0)
            if (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - k.Head.Position).Magnitude <= 50 then
                wait(.2)
                fireclickdetector(k:FindFirstChild("ClickDetector"), 4)
                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(d)
            end
        end
    
        if Options.BuyGuns.Value == "[Double Barrel SG]" then
            local d = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
            local k = game.Workspace.Ignored.Shop['[Double-Barrel SG] - $1442']
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = k.Head.CFrame + Vector3.new(0, 3, 0)
            if (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - k.Head.Position).Magnitude <= 50 then
                wait(.2)
                fireclickdetector(k:FindFirstChild("ClickDetector"), 4)
                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(d)
            end
        end
    
        if Options.BuyGuns.Value == "[Shotgun]" then
            local k = game.Workspace.Ignored.Shop['[Shotgun] - $1288']
            local d = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = k.Head.CFrame + Vector3.new(0, 3, 0)
            if (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - k.Head.Position).Magnitude <= 50 then
                wait(.2)
                fireclickdetector(k:FindFirstChild("ClickDetector"), 4)
                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(d)
            end
        end
    
        if Options.BuyGuns.Value == "[Tactical Shotgun]" then
            local k = game.Workspace.Ignored.Shop['[TacticalShotgun] - $1751']
            local d = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = k.Head.CFrame + Vector3.new(0, 3, 0)
            if (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - k.Head.Position).Magnitude <= 50 then
                wait(.2)
                fireclickdetector(k:FindFirstChild("ClickDetector"), 4)
                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(d)
            end
        end
        if Options.BuyGuns.Value == "[SMG]" then
            local k = game.Workspace.Ignored.Shop['[SMG] - $773']
            local d = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = k.Head.CFrame + Vector3.new(0, 3, 0)
            if (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - k.Head.Position).Magnitude <= 50 then
                wait(.2)
                fireclickdetector(k:FindFirstChild("ClickDetector"), 4)
                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(d)
            end
        end
    
        if Options.BuyGuns.Value == "[Knife]" then
            local k = game.Workspace.Ignored.Shop['[Knife] - $155']
            local d = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = k.Head.CFrame + Vector3.new(0, 3, 0)
            if (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - k.Head.Position).Magnitude <= 50 then
                wait(.2)
                fireclickdetector(k:FindFirstChild("ClickDetector"), 4)
                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(d)
            end
        end
    
        if Options.BuyGuns.Value == "[RPG]" then
            local k = game.Workspace.Ignored.Shop['[RPG] - $6180']
            local d = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = k.Head.CFrame + Vector3.new(0, 3, 0)
            if (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - k.Head.Position).Magnitude <= 50 then
                wait(.2)
                fireclickdetector(k:FindFirstChild("ClickDetector"), 4)
                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(d)
            end
        end
    
        if Options.BuyGuns.Value == "[AK-47]" then
            local k = game.Workspace.Ignored.Shop['[AK47] - $2318']
            local d = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = k.Head.CFrame + Vector3.new(0, 3, 0)
            if (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - k.Head.Position).Magnitude <= 50 then
                wait(.2)
                fireclickdetector(k:FindFirstChild("ClickDetector"), 4)
                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(d)
            end
        end
    
        if Options.BuyGuns.Value == "[Flame Thrower]" then
            local k = game.Workspace.Ignored.Shop['[Flamethrower] - $25750']
            local d = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = k.Head.CFrame + Vector3.new(0, 3, 0)
            if (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - k.Head.Position).Magnitude <= 50 then
                wait(.2)
                fireclickdetector(k:FindFirstChild("ClickDetector"), 4)
                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(d)
            end
        end
    
    end)
    
    Buy:AddDropdown('BuyAmmo', {
        Values = { '[Taco]', '[Hamburger]', '[Pizza]', '[Popcorn]', '[Cranberry]', '[Chicken]', '[Donut]', ''   },
        Default = 20, -- number index of the value / string
        Multi = false, -- true / false, allows multiple choices to be selected
    
        Text = 'Weapons',
        Tooltip = 'Auto Buy Weapons', -- Information shown when you hover over the textbox
    })
    
    Options.BuyAmmo:OnChanged(function()
    
    end)
    
    local VisualsWorld = Tabs.Visuals:AddLeftGroupbox('World Visuals')
    local TargetVisuals = Tabs.Visuals:AddRightGroupbox('Target Aim Visuals')
    --local SilentVisuals = Tabs.Visuals:AddLeftGroupbox('Direction')
    local ChamBox = Tabs.Visuals:AddRightTabbox()

    
    
    -- 





    --
    VisualsWorld:AddLabel('Fog Color'):AddColorPicker('FogColorR', {
        Default = Color3.fromRGB(100, 87, 72), -- Bright green
        Title = 'Fog Color', -- Optional. Allows you to have a custom color picker title (when you open it)
        Transparency = nil, -- Optional. Enables transparency changing for this color picker (leave as nil to disable)
    
        Callback = function(Value)
        end
    })
    
    Options.FogColorR:OnChanged(function()
        game:GetService("Lighting").FogColor = Options.FogColorR.Value
    end)
    
    VisualsWorld:AddSlider('FogEnd', {
        Text = 'Fog Distance',
        Default = 800,
        Min = 25,
        Max = 5000,
        Rounding = 1,
        Compact = true, 
    })
    
    Options.FogEnd:OnChanged(function()
        game:GetService("Lighting").FogEnd = Options.FogEnd.Value
    end)
    
    
    local TabBox3 = ChamBox:AddTab('Player')
    
    --local ChamBox = Tabs.Visuals:AddRightTabbox()
    
    
    TabBox3:AddToggle('BodyCham', {
        Text = 'Body Cham',
        Default = false, 
        Tooltip = 'Chams Your Body', 
    })
    
    
    Toggles.BodyCham:OnChanged(function()
    
    
        TargetVisuals:AddToggle('TargetHitbox', {
            Text = 'Fake Hitbox',
            Default = false, 
            Tooltip = 'Adds A Fake Hitbox On Your Target', 
        })
        
        Toggles.TargetHitbox:OnChanged(function()
            Lock.Visualize.Hitbox = Toggles.TargetHitbox.Value
        end)
    end)
    
    
    
    Toggles.TargetHitbox:AddColorPicker('TargetHitboxColor', {
        Default = Color3.new(0, 1, 0), -- Bright green
        Title = 'Hitbox Color', -- Optional. Allows you to have a custom color picker title (when you open it)
        Transparency = 1, -- Optional. Enables transparency changing for this color picker (leave as nil to disable)
    })
    
    Options.TargetHitboxColor:OnChanged(function()
        Lock.Drawings.FakeHitbox.Color = Options.TargetHitboxColor.Value
        Lock.Drawings.FakeHitbox.Transparency = Options.TargetHitboxColor.Transparency
    end)
    
    TargetVisuals:AddDropdown('BodyChamMaterial', {
        Values = { 'ForceField', 'Neon', 'Glass' },
        Default = 1, -- number index of the value / string
        Multi = false, -- true / false, allows multiple choices to be selected
    
        Text = 'Cham Material',
        Tooltip = 'Customize The Cham Material', -- Information shown when you hover over the textbox
    })
    
    Options.BodyChamMaterial:OnChanged(function()
       
    end)
    
    
    
    
    Lock.Drawings.FakeHitbox.CFrame = CFrame.new(9999,9999,9999)
    
    
    
    
    TargetVisuals:AddSlider('HitboxSize', {
        Text = 'Hitbox Size',
        Default = 4,
        Min = 1,
        Max = 15,
        Rounding = 1,
        Compact = true, 
    })
    
    Options.HitboxSize:OnChanged(function()
        Lock.Visualize.X = Options.HitboxSize.Value
        Lock.Visualize.Y = Options.HitboxSize.Value
        Lock.Visualize.Z = Options.HitboxSize.Value
    end)
    
    TargetVisuals:AddDropdown('TargetMaterial', {
        Values = { 'Neon', 'Plastic', 'ForceField', 'Glass' },
        Default = 3, -- number index of the value / string
        Multi = false, -- true / false, allows multiple choices to be selected
    
        Text = 'Material',
        Tooltip = 'Hitbox Material', -- Information shown when you hover over the textbox
    })
    
    Options.TargetMaterial:OnChanged(function()
        Lock.Drawings.FakeHitbox.Material = Enum.Material[Options.TargetMaterial.Value]
    end)
    
    
    
    
    TargetVisuals:AddToggle('VisualHighlight', {
        Text = 'Highlight',
        Default = false, 
        Tooltip = 'Adds A Dot To The Targets Aimpart', 
    })
    
    Toggles.VisualHighlight:OnChanged(function()
        Lock.Visualize.Highlight = Toggles.VisualHighlight.Value
    end)
    
    
    
    Toggles.VisualHighlight:AddColorPicker('HighlightFill', {
        Default = Color3.fromRGB(255,0,255),
        Title = 'Highlight Fill Color'
    })
    
    Options.HighlightFill:OnChanged(function()
        getgenv().fillcolor = Options.HighlightFill.Value
    end)
    
    Toggles.VisualHighlight:AddColorPicker('HighlightOutline', {
        Default = Color3.fromRGB(255,255,255),
        Title = 'Highlight Outline Color'
    })
    
    Options.HighlightOutline:OnChanged(function()
        getgenv().outlinecolor = Options.HighlightOutline.Value
    end)
    
    
    
    
    TargetVisuals:AddToggle('VisualDot', {
        Text = 'Dot',
        Default = false, 
        Tooltip = 'Adds A Dot To The Targets Aimpart', 
    })
    
    Toggles.VisualDot:OnChanged(function()
        Lock.Visualize.Dot = Toggles.VisualDot.Value
    end)
    
    Toggles.VisualDot:AddColorPicker('DotColor', {
        Default = Color3.new(0, 1, 0), -- Bright green
        Title = 'Dot Color', -- Optional. Allows you to have a custom color picker title (when you open it)
        Transparency = 1, -- Optional. Enables transparency changing for this color picker (leave as nil to disable)
    })
    
    Options.DotColor:OnChanged(function()
        Lock.Drawings.Dot.Color = Options.DotColor.Value
        Lock.Drawings.Dot.Transparency = Options.DotColor.Transparency
    end)
    
    
    TargetVisuals:AddToggle('VisualTracer', {
        Text = 'Tracer',
        Default = false, 
        Tooltip = 'Adds A Tracer From You To Your Target', 
    })
    
    Toggles.VisualTracer:OnChanged(function()
        Lock.Visualize.Tracer[1] = Toggles.VisualTracer.Value
    end)
    
    Toggles.VisualTracer:AddColorPicker('TracerColor', {
        Default = Color3.new(0, 1, 0), -- Bright green
        Title = 'Tracer Color', -- Optional. Allows you to have a custom color picker title (when you open it)
        Transparency = 1, -- Optional. Enables transparency changing for this color picker (leave as nil to disable)
    })
    
    Options.TracerColor:OnChanged(function()
        Lock.Drawings.Tracer.Color = Options.TracerColor.Value
        Lock.Drawings.Tracer.Transparency = Options.TracerColor.Transparency
    end)
    
    TargetVisuals:AddDropdown('TracerOrigin', {
        Values = { 'Head', 'Mouse', 'Gun', 'Crosshair' },
        Default = 1, -- number index of the value / string
        Multi = false, -- true / false, allows multiple choices to be selected
    
        Text = 'Tracer Origin',
        Tooltip = 'Customize The Tracer Origin', -- Information shown when you hover over the textbox
    })
    
    Options.TracerOrigin:OnChanged(function()
        Lock.Visualize.Tracer[2] = Options.TracerOrigin.Value
    end)
    
    
    
    
    TargetVisuals:AddToggle('TargetUI', {
        Text = 'Target UI',
        Default = false, 
        Tooltip = 'Get info on your targets', 
    })
    
    Toggles.TargetUI:OnChanged(function()
        Lock.Visualize.TargetUI = Toggles.TargetUI.Value
    end)
    
    
    TargetVisuals:AddToggle('TargetFOV', {
        Text = 'FOV',
        Default = false, 
        Tooltip = 'Adds A Fake Hitbox On Your Target', 
    })
    
    Toggles.TargetFOV:OnChanged(function()
        Lock.Drawings.FOV.Visible = Toggles.TargetFOV.Value
    end)
    
    
    Toggles.TargetFOV:AddColorPicker('FOVColor', {
    Default = Color3.new(0, 1, 0), -- Bright green
    Title = 'FOV Color', -- Optional. Allows you to have a custom color picker title (when you open it)
    Transparency = 1, -- Optional. Enables transparency changing for this color picker (leave as nil to disable)
    })
    
    Options.FOVColor:OnChanged(function()
    Lock.Drawings.FOV.Color = Options.FOVColor.Value
     Lock.Drawings.FOV.Transparency = Options.FOVColor.Transparency
    end)
    
    
    
    
        
    --[[local MyButton2 = MyButton:AddButton('Sub button', function()
        print('You clicked a sub button!')
    end)
    
    
    MyButton:AddTooltip('This is a button')
    MyButton2:AddTooltip('This is a sub button')
    
    LeftGroupBox:AddLabel('This is a label')
    LeftGroupBox:AddLabel('This is a label\n\nwhich wraps its text!', true)
    
    LeftGroupBox:AddDivider()
    
    LeftGroupBox:AddSlider('MySlider', {
        Text = 'This is my slider!',
        Default = 0,
        Min = 0,
        Max = 5,
        Rounding = 1,
        Compact = false, 
    })
    
    local Number = Options.MySlider.Value
    Options.MySlider:OnChanged(function()
        print('MySlider was changed! New value:', Options.MySlider.Value)
    end)
    
    Options.MySlider:SetValue(3)
    
    
    LeftGroupBox:AddInput('MyTextbox', {
        Default = 'My textbox!',
        Numeric = false, 
        Finished = false,
    
        Text = 'This is a textbox',
        Tooltip = 'This is a tooltip', 
    
        Placeholder = 'Placeholder text',
    })
    
    Options.MyTextbox:OnChanged(function()
        print('Text updated. New text:', Options.MyTextbox.Value)
    end)
    
    LeftGroupBox:AddDropdown('MyDropdown', {
        Values = { 'This', 'is', 'a', 'dropdown' },
        Default = 1, 
        Multi = false,
    
        Text = 'A dropdown',
        Tooltip = 'This is a tooltip',
    })
    
    Options.MyDropdown:OnChanged(function()
        print('Dropdown got changed. New value:', Options.MyDropdown.Value)
    end)
    
    Options.MyDropdown:SetValue('This')
    
    LeftGroupBox:AddDropdown('MyMultiDropdown', {
        Values = { 'This', 'is', 'a', 'dropdown' },
        Default = 1, 
        Multi = true,
    
        Text = 'A dropdown',
        Tooltip = 'This is a tooltip',
    })
    
    Options.MyMultiDropdown:OnChanged(function()
        -- print('Dropdown got changed. New value:', )
        print('Multi dropdown got changed:')
        for key, value in next, Options.MyMultiDropdown.Value do
            print(key, value) -- should print something like This, true
        end
    end)
    
    Options.MyMultiDropdown:SetValue({
        This = true,
        is = true,
    })
    
    LeftGroupBox:AddLabel('Color'):AddColorPicker('ColorPicker', {
        Default = Color3.new(0, 1, 0),
        Title = 'Some color', 
    })
    
    Options.ColorPicker:OnChanged(function()
        print('Color changed!', Options.ColorPicker.Value)
    end)
    
    Options.ColorPicker:SetValueRGB(Color3.fromRGB(0, 255, 140))
    
    LeftGroupBox:AddLabel('Keybind'):AddKeyPicker('KeyPicker', {
        Default = 'MB2',
        SyncToggleState = false, 
        Mode = 'Toggle', 
        Text = 'Auto lockpick safes', 
        NoUI = false, 
    })]]
    
    
    -- Example of dynamically-updating watermark with common traits (fps and ping)
    local FrameTimer = tick()
    local FrameCounter = 0;
    local FPS = 240;
    
    local WatermarkConnection = game:GetService('RunService').RenderStepped:Connect(function()
        FrameCounter += 1;
    
        if (tick() - FrameTimer) >= 1 then
            FPS = FrameCounter;
            FrameTimer = tick();
            FrameCounter = 0;
        end;
        Library:SetWatermark(('i love kids-viko | %s fps | %s ms'):format(
            math.floor(FPS),
            math.floor(game:GetService('Stats').Network.ServerStatsItem['Data Ping']:GetValue())
        ));
    
    
    
    
    
    Library:OnUnload(function()
        Library.Unloaded = true
    end);
    end)
    
    local MenuGroup = Tabs['Settings']:AddRightGroupbox('Menu')
    --AddLeftGroupbox
    
    
    
    MenuGroup:AddLabel('Menu Keybind'):AddKeyPicker('MenuKeybind', { Default = 'End', NoUI = true, Text = 'Menu keybind' }) 
    
    MenuGroup:AddToggle('KeybindList', {
        Text = 'Keybind List',
        Default = false, 
        Tooltip = 'Toggles the Keybind List', 
    })
    
    Toggles.KeybindList:OnChanged(function()
        Library.KeybindFrame.Visible  = Toggles.KeybindList.Value
    end)
    
    MenuGroup:AddToggle('Watermark', {
        Text = 'Watermark',
        Default = false, 
        Tooltip = 'Toggles the Watermark', 
    })
    
    Toggles.Watermark:OnChanged(function()
        Library:SetWatermarkVisibility(Toggles.Watermark.Value) 
    end)
    
    
    
    MenuGroup:AddDropdown('UINotis', {
        Values = { 'Xaxa', 'Roblox', 'Akali' },
        Default = 2, -- number index of the value / string
        Multi = false, -- true / false, allows multiple choices to be selected
    
        Text = 'Notification Type',
        Tooltip = 'Change What Notifications Show Up', -- Information shown when you hover over the textbox
    })
    
    Options.UINotis:OnChanged(function()
        getgenv().NotiMode = Options.UINotis.Value
    end)
    
    
    --
    local Unload1 = MenuGroup:AddButton({
        Text = 'Unload',
        Func = function()
            Library:Unload()
        end,
        DoubleClick = true,
        Tooltip = 'Unloads The Cheat'
    })
    
    local Unload2 = Unload1:AddButton({
        Text = 'Join Discord',
        Func = function()
            setclipboard("NIGGGGGGGAAAA")
            notifications:BuildNotificationUI();
            Notifications("https://discord.gg/JPsMTKJzhD");
            local request = (syn and syn.request) or (http and http.request) or http_request
            local HttpService = game:GetService("HttpService")
            if request then
                request({
                    Url = 'http://127.0.0.1:6463/rpc?v=1',
                    Method = 'POST',
                    Headers = {
                        ['Content-Type'] = 'application/json',
                        Origin = 'https://discord.com'
                    },
                    Body = HttpService:JSONEncode({
                        cmd = 'INVITE_BROWSER',
                        nonce = HttpService:GenerateGUID(false),
                        args = {code = ""}
                    })
                })
            end
        end,
        DoubleClick = false, -- You will have to click this button twice to trigger the callback
        Tooltip = 'Joins Our Discord'
    })
    
    Library.ToggleKeybind = Options.MenuKeybind
    
    ThemeManager:SetLibrary(Library)
    SaveManager:SetLibrary(Library)
    
    --SaveManager:IgnoreThemeSettings() 
    
    --SaveManager:SetIgnoreIndexes({ 'MenuKeybind' }) 
    
    ThemeManager:SetFolder('Gultlol-thm')
    SaveManager:SetFolder('Gult-cfg')
    
    SaveManager:BuildConfigSection(Tabs['Settings']) 
    
    ThemeManager:ApplyToTab(Tabs['Settings'])
    
    -- Code Below 
    Options.TargetBind:OnClick(function()
        if Lock.Enabled then 
            Lock.Locking = not Lock.Locking 
            -- 
            if Lock.Locking == true then 
                Lock.Target.Player = Lock:GetClosestPlayer() 
    
                -- target ui
                if Lock.Visualize.TargetUI then
                gui.TextLabel.Text = "@"..tostring(Lock.Target.Player)
                gui.TextLabel_2.Text = Lock.Target.Player.DisplayName
                RunService.RenderStepped:Connect(function()
                gui.TextLabel_1.Text = "Health: "..tostring(Lock.Target.Player.Character.Humanoid.Health)
                end)
    
                local player = Lock.Target.Player
    
                local userId = Lock.Target.Player.UserId
                local thumbType = Enum.ThumbnailType.HeadShot
                local thumbSize = Enum.ThumbnailSize.Size420x420
                local content, isReady = Players:GetUserThumbnailAsync(userId, thumbType, thumbSize)
    
                local imageLabel = gui.ImageLabel
                imageLabel.Image = content
                imageLabel.Size = UDim2.new(0, 75,0, 75)
                gui.Frame.Visible = true
            end
                -- target ui
    
                if (Lock.Visualize.Notify == true) then 
                    if Lock.Mode == "Target Aim" then
                    notifications:BuildNotificationUI();
                    Notifications("Locked onto: ".. Lock.Target.Player.DisplayName);
                    wait(1) print(Lock.Target.Prediction)
                    else
                        notifications:BuildNotificationUI();
                        Notifications("Redirection Enabled");
                    end
                else
            end
                -- 
            if Lock.ViewAt then 
                Camera.CameraSubject = Lock.Target.Player.Character.Humanoid
            end     
        else 
            if Lock.Visualize.TargetUI then
            gui.Frame.Visible = false
        end
            Lock.Drawings.Dot.Visible = false 
            Lock.Drawings.Tracer.Visible = false 
            Camera.CameraSubject = LocalPlayer.Character.Humanoid
            LocalPlayer.Character.Humanoid.AutoRotate = true 
            -- 
            if (Lock.Visualize.Notify == true) then 
                if Lock.Mode == "Target Aim" then
                    notifications:BuildNotificationUI();
                    Notifications("Unlocked");
                    else
                        notifications:BuildNotificationUI();
                        Notifications("Redirection Disabled");
                    end
            end 
        end 
        end 
    end)
    RunService.Heartbeat:Connect(function(FPS)
        if Lock.Drawings.FOV.Visible and Lock.Drawings.FOV.Position ~= NewVector2(Mouse.X, Mouse.Y + offset) then 
            Lock.Drawings.FOV.Position = NewVector2(Mouse.X, Mouse.Y + offset)
        end
        --   
        if Lock.Locking and Lock.Target.Player and Lock:GetPlayerStatus(Lock.Target.Player) then
            if Lock.Mode == "redirection" then 
                Lock.Target.Player = Lock:GetClosestPlayer()
            end 
            -- 
            if Lock.Target.Player and Lock.Target.Player.Character then 
                Lock.Target.Status = Lock:GetPlayerStatus(Lock.Target.Player)
                Lock.Target.Velocity = Lock.Resolver and Lock:CalculateAbsolutePosition(Lock.Target.Player) or Lock.Target.Player.Character.HumanoidRootPart.Velocity
                
                
      --ELEGANT WORK ON THIS, DONT DO ANYTHING ELSE!
      if Lock.Prediction.PingBased then
        local pingvalue = game:GetService("Stats").Network.ServerStatsItem["Data Ping"]:GetValueString()
        local split = string.split(pingvalue,'(')
        local ping = tonumber(split[1])    
        --[[ elegants 
        if ping < 100 then
            Lock.Target.Prediction = 0.141987
        elseif ping < 80 then
            Lock.Target.Prediction = 0.139340
        elseif ping < 70 then
            Lock.Target.Prediction = 0.12533
              elseif ping < 65 then
                Lock.Target.Prediction = 0.1264236
        elseif ping < 50 then
            Lock.Target.Prediction = 0.13544
        elseif ping < 30 then
            Lock.Target.Prediction = 0.11252476
            
            --[[ louls 
            if ping < 30 then
                Lock.Target.Prediction = 0.1099
            elseif
                ping < 35 then
                    Lock.Target.Prediction = 0.2294
                elseif
                    ping < 40 then
                        Lock.Target.Prediction = 0.1195
                    elseif
                        ping < 45 then
                            Lock.Target.Prediction = 0.1207
                        elseif
                            ping < 50 then
                                Lock.Target.Prediction = 0.1219
                            elseif      
                                ping < 55 then
                                    Lock.Target.Prediction = 0.1228
                                elseif
                                    ping < 60 then
                                        Lock.Target.Prediction = 0.1237 
                                    elseif
                                        ping < 65 then 
                                            Lock.Target.Prediction = 0.1264 
                                        elseif
                                            ping < 70 then
                                                Lock.Target.Prediction = 0.1291
                                            elseif
                                                ping < 75 then
                                                    Lock.Target.Prediction = 0.1314
                                                elseif
                                                    ping < 80 then 
                                                        Lock.Target.Prediction = 0.1337 
                                                    elseif
                                                        ping < 85 then
                                                            Lock.Target.Prediction = 0.1343
                                                        elseif
                                                            ping < 90 then
                                                                Lock.Target.Prediction = 0.1349
                                                            elseif
                                                                ping < 95 then
                                                                    Lock.Target.Prediction = 0.1363
                                                                elseif
                                                                    ping < 100 then
                                                                        Lock.Target.Prediction = 0.1378
                                                                    elseif
                                                                        ping < 105 then
                                                                            Lock.Target.Prediction = 0.1418 
                                                                        elseif
                                                                            ping < 110 then
                                                                            Lock.Target.Prediction = 0.1459
                                                                            ]]
    
                                                                            -- sosa sets
    
                                                                            if ping < 10 then
                                                                                Lock.Target.Prediction = 0.1112873
                                                                            elseif ping < 20 then
                                                                                Lock.Target.Prediction = 0.1211928
                                                                            elseif ping < 30 then
                                                                                Lock.Target.Prediction = 0.1254263
                                                                            elseif ping < 40 then
                                                                                Lock.Target.Prediction = 0.1314356
                                                                            elseif ping < 50 then
                                                                                Lock.Target.Prediction = 0.1368384
                                                                            elseif ping < 60 then
                                                                                Lock.Target.Prediction = 0.12671983
                                                                            elseif ping < 70 then
                                                                                Lock.Target.Prediction = 0.12862974
                                                                            elseif ping < 80 then
                                                                                Lock.Target.Prediction = 0.13581963
                                                                            elseif ping < 90 then
                                                                                Lock.Target.Prediction = 0.13873952
                                                                            elseif ping < 100 then
                                                                                Lock.Target.Prediction = 0.14173456
                                                                            elseif ping < 110 then
                                                                                Lock.Target.Prediction = 0.14362652
                                                                            elseif ping < 120 then
                                                                                Lock.Target.Prediction = 0.14683943
                                                                            elseif ping < 130 then
                                                                                Lock.Target.Prediction = 0.15175864
                                                                            elseif ping < 140 then
                                                                                Lock.Target.Prediction = 0.15382643
                                                                            elseif ping < 150 then
                                                                                Lock.Target.Prediction = 0.15873582
                                                                            end
                                                                        end
    
                                                                        if Lock.Target_Strafe[1] then 
                                                                            Lock.Target.Angle += Lock.Target_Strafe[2]
                                                                            LocalPlayer.Character.HumanoidRootPart.CFrame = 
                                                                            Lock.Target.Player.Character.HumanoidRootPart.CFrame 
                                                                            * NewAngle(0, Rad(Lock.Target.Angle), 0) 
                                                                            * NewCFrame(0, Lock.Target_Strafe[4], Lock.Target_Strafe[3])
                                                                        end 
                                                                        --
                                                                        if Lock.LookAt then 
                                                                            LocalPlayer.Character.Humanoid.AutoRotate = false 
                                                                            local NearestPos = CFrame.new(LocalPlayer.Character.PrimaryPart.Position, Vector3.new(Lock.Target.Player.Character.HumanoidRootPart.Position.X, LocalPlayer.Character.PrimaryPart.Position.Y, Lock.Target.Player.Character.HumanoidRootPart.Position.Z))
                                                                            LocalPlayer.Character:SetPrimaryPartCFrame(NearestPos)
                                                                        end 
                                                                        -- 
                                                                        if Lock.Target.Position then 
                                                                            local Position1, OnScreen = Camera:WorldToViewportPoint(Lock.Target.Position)
                                                                            local MousePosition = NewVector2(Mouse.X, Mouse.Y + 36)
                                                                            local Magn = (MousePosition - NewVector2(Position1.X, Position1.Y)).Magnitude
                                                                            -- 
                                                                            if Lock.Drawings.FOV.Visible then 
                                                                                Lock.Drawings.FOV.Position = NewVector2(Mouse.X, Mouse.Y + 36)
                                                                                if (Magn >= Lock.Drawings.FOV.Radius) then Lock.Target.Status = false end 
                                                                            end
                                                                            -- 
                                                                            if Lock.Visualize.Hitbox == true then 
                                                                                Lock.Drawings.FakeHitbox.CFrame = NewCFrame(Lock.Target.Position)
                                                                                Lock.Drawings.FakeHitbox.Size = NewVector3(Lock.Visualize.X, Lock.Visualize.Y, Lock.Visualize.Z)
                                                                            else 
                                                                                Lock.Drawings.FakeHitbox.CFrame = NewCFrame(999,9999,999)
                                                                            end 
                                                                            -- 
                                                                            if OnScreen then 
                                                                                if Lock.Visualize.Tracer[1] then 
                                                                                    Lock.Drawings.Tracer.Visible = true 
                                                                                    --
                                                                                    if Lock:GetTracerOrigin(Lock.Visualize.Tracer[2]) ~= nil then 
                                                                                        local Position2, OnScreen = Lock:GetTracerOrigin(Lock.Visualize.Tracer[2])  
                                                                                        --
                                                                                        if Position2 then 
                                                                                            Lock.Drawings.Tracer.From = Vector2.new(Position2.X, Position2.Y)
                                                                                        end 
                                                                                    end 
                                                                                    Lock.Drawings.Tracer.To = Vector2.new(Position1.X, Position1.Y)
                                                                                end
                                                                                -- 
                                                                                if Lock.Visualize.Dot then 
                                                                                    Lock.Drawings.Dot.Visible = true 
                                                                                    Lock.Drawings.Dot.Position = NewVector2(Position1.X, Position1.Y)
                                                                                else 
                                                                                    Lock.Drawings.Dot.Visible = false 
                                                                                end 
                                                                                -- 
                                                                                if Lock.Visualize.Strafe and Lock.Target_Strafe[1] then 
                                                                                end 
                                                                            else 
                                                                                Lock.Drawings.Dot.Visible = false 
                                                                                Lock.Drawings.Tracer.Visible = false 
                                                                            end  
                                                                        end 
                                                                    end
                                                                end
                                                            end)
                                                            
    if not LPH_OBFUSCATED then
    getfenv().LPH_NO_VIRTUALIZE = function(f) return f end;
    end
    local Old
    Old = hookmetamethod(game, "__index", LPH_NO_VIRTUALIZE(function(self, k)
        if (self:IsA("Mouse") and (k == "Hit" or k == "Target")) and Lock.Locking and Lock.Target.Player then 
            local Part = Lock.Prediction.Part or "HumanoidRootPart"
            if Lock.Prediction.Air == true and Lock.Target.Player.Character.Humanoid.FloorMaterial == Enum.Material.Air then 
                SilentArg = Lock.Target.Player.Character["LeftFoot"].Position + (Lock.Target.Velocity * Lock.Target.Prediction)
            else 
                SilentArg = Lock.Target.Player.Character[Part].Position + (Lock.Target.Velocity * Lock.Target.Prediction)
            end 
            Lock.Target.Position = SilentArg
            -- 
            if Lock.Target.Status == true then  
                return (k == "Hit" and NewCFrame(SilentArg))
            end 
        end 
        return Old(self, k) 
    end))
    
    Notifications("Loaded In "..string.format("%.2f", tostring(tick() - loadingtime,nil))..tostring(" Seconds"))
    loadingtime = nil
    end
    
if boostframes then
    getgenv().boostFPS = true

    local vim = game:GetService("VirtualInputManager")
    setfpscap(999)
    
    game.DescendantAdded:Connect(function(d)
       if d.Name == "MainView" and d.Parent.Name == "DevConsoleUI" and boostFPS then
           task.wait()
           local screen = d.Parent.Parent.Parent
           screen.Enabled = false;
           d.Visible = false;
       end
    end)
    
    vim:SendKeyEvent(true, "F9", 0, game)    
    wait()
    vim:SendKeyEvent(false, "F9", 0, game)  
    
    while true do
       task.wait()
       if not boostFPS then
           continue;
       end
    
    end
end

end)
