--create by FRITE--
while true do wait()
local args = {
    [1] = {
        ["multiply"] = 6,
        ["action"] = "hit",
        ["enemyHum"] = workspace.dummies.TrainingDummy6.Humanoid
    }
}

game:GetService("ReplicatedStorage").DamageEvent:FireServer(unpack(args))
end
