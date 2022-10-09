local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()
local Window = OrionLib:MakeWindow({Name = "Ballz script", HidePremium = false, SaveConfig = false, ConfigFolder = "Fart6969"})

local Tab = Window:MakeTab({
	Name = "The balls",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

local Section = Tab:AddSection({
	Name = "Funny stuff"
})


Tab:AddButton({
	Name = "Spawn balls",
	Callback = function()
      	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-629, 114, 722)
        for a,b in pairs(game.Players.LocalPlayer.Character:GetDescendants()) do
            if b:IsA("BasePart") then
                b.Anchored = true
            end
        end
        for i=1,500 do
            local v1 = "Transform"
            local v2 = "Ball"
            local event = game:GetService("ReplicatedStorage").Events.Ball.ControlRE
            event:FireServer(v1, v2)  
        end
        wait(5)
        for c,d in pairs(game.Players.LocalPlayer.Character:GetDescendants()) do
            if d.Name == "WeldConstraint" then
                d:Destroy()
            end
        end
        for a,b in pairs(game.Players.LocalPlayer.Character:GetDescendants()) do
            if b:IsA("BasePart") then
                b.Anchored = false
            end
        end
      	print("we like balls")
  	end    
})

Tab:AddButton({
	Name = "Break players balls 🗿🗿🗿",
	Callback = function()
	    for i=1,20000 do
            local v1 = "Transform"
            local v2 = "Ball"
            local event = game:GetService("ReplicatedStorage").Events.Ball.ControlRE
            event:FireServer(v1, v2)  
        end
        wait(7)
        for fart,horse in pairs(game.Players.LocalPlayer.Character:GetDescendants()) do
            if horse.Name == "WeldConstraint" then
                horse:Destroy()
            end
        end
        wait(4)
        game.Players.LocalPlayer.Character.Head:Destroy()
      	print("they have no nuts")
  	end    
})








