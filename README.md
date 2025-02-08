--loadstring--
local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()

--windows--
local Window = Library.CreateLib("kavane hub", "Ocean")
local Tab = Window:NewTab("kavane hub tab")
local Section = Tab:NewSection("Testando")

--secao--
Section:NewLabel("Scripts")

--botao--
Section:NewButton("fly mobile script", "Voar pelo mapa", function()
    loadstring(game:HttpGet('https://pastebin.com/raw/YSL3xKYU'))()
end)
