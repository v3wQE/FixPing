--PING SPOOFER
-- MADE BY Memelouse#0001
local PerformanceStats = game:GetService("CoreGui"):WaitForChild("RobloxGui"):WaitForChild("PerformanceStats");
local colortype = Color3.fromRGB(126, 211, 33);
local PingLabel;
local color;
local color1;
local color2;
local color3;
local color4;
local color5;
local color6;
local color7;
local color8;
local color9;
local color10;
local color11;
local color12;
local color13;
local color14;
local color15;
local color16;
local color17;
local color18;
local color19;
for I, Child in next, PerformanceStats:GetChildren() do
    if Child.StatsMiniTextPanelClass.TitleLabel.Text == "Ping" then
        PingLabel = Child.StatsMiniTextPanelClass.ValueLabel;
        color = Child.PS_AnnotatedGraph.PS_BarFrame.Bar_0;
        color1 = Child.PS_AnnotatedGraph.PS_BarFrame.Bar_1;
        color2 = Child.PS_AnnotatedGraph.PS_BarFrame.Bar_2;
        color3 = Child.PS_AnnotatedGraph.PS_BarFrame.Bar_3;
        color4 = Child.PS_AnnotatedGraph.PS_BarFrame.Bar_4;
        color5 = Child.PS_AnnotatedGraph.PS_BarFrame.Bar_5;
        color6 = Child.PS_AnnotatedGraph.PS_BarFrame.Bar_6;
        color7 = Child.PS_AnnotatedGraph.PS_BarFrame.Bar_7;
        color8 = Child.PS_AnnotatedGraph.PS_BarFrame.Bar_8;
        color9 = Child.PS_AnnotatedGraph.PS_BarFrame.Bar_9;
        color10 = Child.PS_AnnotatedGraph.PS_BarFrame.Bar_10;
        color11 = Child.PS_AnnotatedGraph.PS_BarFrame.Bar_11;
        color12 = Child.PS_AnnotatedGraph.PS_BarFrame.Bar_12;
        color13 = Child.PS_AnnotatedGraph.PS_BarFrame.Bar_13;
        color14 = Child.PS_AnnotatedGraph.PS_BarFrame.Bar_14;
        color15 = Child.PS_AnnotatedGraph.PS_BarFrame.Bar_15;
        color16 = Child.PS_AnnotatedGraph.PS_BarFrame.Bar_16;
        color17 = Child.PS_AnnotatedGraph.PS_BarFrame.Bar_17;
        color18 = Child.PS_AnnotatedGraph.PS_BarFrame.Bar_18;
        color19 = Child.PS_AnnotatedGraph.PS_BarFrame.Bar_19;
        break;
    end;
end;
PingLabel:GetPropertyChangedSignal("Text"):Connect(function()
    local textrandom = math.random(1000,2000) / 100
    PingLabel.Text = textrandom.. " ms";
        color.BackgroundColor3 = colortype
        color1.BackgroundColor3 = colortype
        color2.BackgroundColor3 = colortype
        color3.BackgroundColor3 = colortype
        color4.BackgroundColor3 = colortype
        color5.BackgroundColor3 = colortype
        color6.BackgroundColor3 = colortype
        color7.BackgroundColor3 = colortype
        color8.BackgroundColor3 = colortype
        color9.BackgroundColor3 = colortype
        color10.BackgroundColor3 = colortype
        color11.BackgroundColor3 = colortype
        color12.BackgroundColor3 = colortype
        color13.BackgroundColor3 = colortype
        color14.BackgroundColor3 = colortype
        color15.BackgroundColor3 = colortype
        color16.BackgroundColor3 = colortype
        color17.BackgroundColor3 = colortype
        color18.BackgroundColor3 = colortype
        color19.BackgroundColor3 = colortype
        if game.PlaceId == 9825515356 then
            game:GetService("ReplicatedStorage").MainEvent:FireServer("GetPing",textrandom)
        end
end);
                    game.StarterGui:SetCore("SendNotification", {
                        Title = "Meff.sol V2";
                        Text = "Succes!",
                        Icon = "rbxassetid://9419289467",
                        Duration = 1
                    })
