--carregar Dflay
local Fluent = loadstring(game:HttpGet("https://github.com/dawid-scripts/Fluent/releases/latest/download/main.lua"))()

local Window = Fluent:CreateWindow({
    Title = "Dflay.By.Dfuriaz " .. Fluent.Version,
    TabWidth = 160, Size = UDim2.fromOffset(580, 460), Theme = "Dark"
})

local Tabs = {
    Main = Window:AddTab({ Title = "Main" }),
    Settings = Window:AddTab({ Title = "Settings", Icon = "settings" })

    Tabs.Main:AddParagraph({ Title = "Bem-vindo,dflay", Content = "This is a paragraph.\nSecond line!" })

Tabs.Main:AddButton({ Title = "Button", Callback = function() print(*teste*) end })
Tabs.Main:AddButton({ Title = "Button", Callback = function() ... end })
Tabs.Main:AddButton({ Title = "Button", Callback = function() ... end })
Tabs.Main:AddButton({ Title = "Button", Callback = function() ... end })
Tabs.Main:AddButton({ Title = "Button", Callback = function() ... end })
