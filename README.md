local Rayfield = loadstring(game:HttpGet('https://sirius.menu/rayfield'))()

local Window = Rayfield:CreateWindow({
   Name = "🔥EchoGPT_9000Hub | GameZ",
   LoadingTitle = "EchoGPT_9000-V1",
   LoadingSubtitle = "by 7wuwt5",
   ConfigurationSaving = {
      Enabled = false,
      FolderName = nil,
      FileName = "EchoGPT_9000-Hutz"
   },
   Discord = {
      Enabled = false,
      Invite = "noinvitelink",
      RememberJoins = true
   },
   KeySystem = false,
   KeySettings = {
      Title = "Key | Youtube Hub",
      Subtitle = "Key System",
      Note = "Key In Discord Server",
      FileName = "YoutubeHubKey1",
      SaveKey = false,
      GrabKeyFromSite = true,
      Key = {"https://pastebin.com/raw/AtgzSPWK"}
   }
})

local MainTab = Window:CreateTab("🏠 Home", nil)
local MainSection = MainTab:CreateSection("Main")

Rayfield:Notify({
   Title = "You executed the script",
   Content = "WOmpWOpm",
   Duration = 5,
   Image = 13047715178,
   Actions = {
      Ignore = {
         Name = "Okay!",
         Callback = function()
            print("The user tapped Okay!")
         end
      },
   },
})

local Button = MainTab:CreateButton({
   Name = "Infinite Jump Toggle",
   Callback = function()
       _G.infinjump = not _G.infinjump

       if _G.infinJumpStarted == nil then
           _G.infinJumpStarted = true
           
           game.StarterGui:SetCore("SendNotification", {Title="Youtube Hub"; Text="Infinite Jump Activated!"; Duration=5;})

           local plr = game:GetService('Players').LocalPlayer
           local m = plr:GetMouse()
           m.KeyDown:connect(function(k)
               if _G.infinjump then
                   if k:byte() == 32 then
                       humanoid = game:GetService'Players'.LocalPlayer.Character:FindFirstChildOfClass('Humanoid')
                       humanoid:ChangeState('Jumping')
                       wait()
                       humanoid:ChangeState('Seated')
                   end
               end
           end)
       end
   end,
})

local Slider = MainTab:CreateSlider({
   Name = "WalkSpeed Slider",
   Range = {1, 350},
   Increment = 1,
   Suffix = "Speed",
   CurrentValue = 16,
   Flag = "sliderws",
   Callback = function(Value)
        game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = Value
   end,
})

local Slider = MainTab:CreateSlider({
   Name = "JumpPower Slider",
   Range = {1, 350},
   Increment = 1,
   Suffix = "Speed",
   CurrentValue = 16,
   Flag = "sliderjp",
   Callback = function(Value)
        game.Players.LocalPlayer.Character.Humanoid.JumpPower = Value
   end,
})

local Input = MainTab:CreateInput({
   Name = "Walkspeed",
   PlaceholderText = "1-500",
   RemoveTextAfterFocusLost = true,
   Callback = function(Text)
        game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = tonumber(Text)
   end,
})

local Button = MainTab:CreateButton({
   Name = "Fake-Verify",
   Callback = function()
       loadstring(game:HttpGet("https://raw.githubusercontent.com/fizzyscripting/Universal/refs/heads/main/FakeVerifiedOBF"))()
   end,
})

local Toggle = MainTab:CreateToggle({
   Name = "AutoFarm-DBU-Only",
   CurrentValue = false,
   Flag = "Toggle1",
   Callback = function(Value)
        loadstring(game:HttpGet("https://raw.githubusercontent.com/AcruxVrs/wl/main/NoG2", true))()
   end,
})

local TPTab = Window:CreateTab("MM2", nil)

local Button1 = TPTab:CreateButton({
   Name = "Verzion-v1",
   Callback = function()
       loadstring(game:HttpGet("https://raw.githubusercontent.com/Dexz00/DzHub/refs/heads/main/Jujutsu%20Infinite"))()
   end,
})

local Button2 = TPTab:CreateButton({
   Name = "Verzion-v2",
   Callback = function()
        loadstring(game:HttpGet('https://raw.githubusercontent.com/vertex-peak/vertex/refs/heads/main/loadstring'))()
   end,
})

local Tab = Window:CreateTab("BloxFruits", nil)

local Button = Tab:CreateButton({
   Name = "BlueX Hub Blox Fruits",
   Callback = function()
       loadstring(game:HttpGet("https://raw.githubusercontent.com/Dev-BlueX/BlueX-Hub/refs/heads/main/EN.lua"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Lumin Hub Blox Fruits Script",
   Callback = function()
       loadstring(game:HttpGet("http://lumin-hub.lol/BloxFruits.lua"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Astral Hub Auto Blox Fruits",
   Callback = function()
       loadstring(game:HttpGet("https://raw.githubusercontent.com/Overgustx2/Main/refs/heads/main/BloxFruits_25.html"))()
   end,
})

local Tab = Window:CreateTab("Fisch", nil)

local Button = Tab:CreateButton({
   Name = "Speed Hub X Fisch",
   Callback = function()
       loadstring(game:HttpGet("https://raw.githubusercontent.com/AhmadV99/Speed-Hub-X/main/Speed%20Hub%20X.lua", true))()
   end,
})

local Button = Tab:CreateButton({
   Name = "YHUB Fisch Mobile",
   Callback = function()
       loadstring(game:HttpGet("https://raw.githubusercontent.com/Luarmor123/community-Y-HUB/refs/heads/main/Fisch-YHUB"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Kiciahook Super OP",
   Callback = function()
       loadstring(game:HttpGet("https://raw.githubusercontent.com/kiciahook/kiciahook/refs/heads/main/loader.lua"))()
   end,
})

local Tab = Window:CreateTab("Natural Disaster", nil)

local Button = Tab:CreateButton({
   Name = "NDS Script",
   Callback = function()
       loadstring(game:HttpGet("https://raw.githubusercontent.com/Thebestofhack123/2.0/refs/heads/main/NDS"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Natural Disaster Survival",
   Callback = function()
       loadstring(game:HttpGet('https://raw.githubusercontent.com/hussain1323232234/My-Scripts/main/Natural%20Disaster'))()
   end,
})

local Button = Tab:CreateButton({
   Name = "SpiderXHub",
   Callback = function()
       loadstring(game:HttpGet("https://raw.githubusercontent.com/SpiderScriptRB/Natural-Disaster-Survival/refs/heads/main/1.0.2%20Version%20Script.txt"))()
   end,
})

local Tab = Window:CreateTab("BlueLock", nil)

local Button = Tab:CreateButton({
   Name = "Custom style Kaiser",
   Callback = function()
       loadstring(game:HttpGet("https://raw.githubusercontent.com/Bhusant/Bathroom-attack/refs/heads/main/Bathroom"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Arbix Hub Blue Lock Rivals",
   Callback = function()
       loadstring(game:HttpGet(('https://pastefy.app/lbLVUm8Z/raw'), true))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Rivals Script Rinns Hub",
   Callback = function()
       loadstring(game:HttpGet("https://raw.githubusercontent.com/SkibidiCen/MainMenu/main/Code"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Rivals Script GUI",
   Callback = function()
       loadstring(game:HttpGet("https://raw.githubusercontent.com/gumanba/Scripts/refs/heads/main/BlueLock"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Over Hub Blue Lock Rivals",
   Callback = function()
       loadstring(game:HttpGet('https://api.overhub.xyz/keys/script/overhub'))()
   end,
})

local Tab = Window:CreateTab("Pet Sim 99", nil)

local Button = Tab:CreateButton({
   Name = "Reaper Hub Pet Simulator 99 Script PC",
   Callback = function()
       loadstring(game:HttpGet("https://raw.githubusercontent.com/AyoReaper/Reaper-Hub/refs/heads/main/loader.lua"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Script Pet Simulator 99",
   Callback = function()
       loadstring(game:HttpGet('https://raw.githubusercontent.com/SenhorLDS/ProjectLDSHUB/main/OfficialScript'))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Project WD",
   Callback = function()
       loadstring(game:HttpGet("https://raw.githubusercontent.com/Stefanuk12/ROBLOX/master/Games/Kohls%20Admin%20House/DarkKohls/GUI.lua"))()
   end,
})

local Tab = Window:CreateTab("Admin-Panels", nil)

local Button = Tab:CreateButton({
   Name = "Reviz Admin",
   Callback = function()
       loadstring(game:HttpGet('https://pastebin.com/ibFPdiF7'))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Admin House NBC",
   Callback = function()
       loadstring(game:HttpGet("https://raw.githubusercontent.com/Stefanuk12/ROBLOX/master/Games/Kohls%20Admin%20House/DarkKohls/GUI.lua"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Nameless-Admin",
   Callback = function()
       loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-Nameless-Admin-Official-15022"))()
   end,
})
