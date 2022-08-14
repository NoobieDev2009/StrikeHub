local Player = game:GetService("Players").LocalPlayer
local PlayerThumbnail = "http://www.roblox.com/Thumbs/Avatar.ashx?x=150&y=150&Format=Png&username="..Player.Name
local plr = game.Players.LocalPlayer
local plrName = plr.Name
local plrId = plr.UserId
local cash = game.Players.LocalPlayer.DataFolder.Currency.Value .. "$"

--[=[
 d888b  db    db d888888b      .d888b.      db      db    db  .d8b.  
88' Y8b 88    88   `88'        VP  `8D      88      88    88 d8' `8b 
88      88    88    88            odD'      88      88    88 88ooo88 
88  ooo 88    88    88          .88'        88      88    88 88~~~88 
88. ~8~ 88b  d88   .88.        j88.         88booo. 88b  d88 88   88 
 Y888P  ~Y8888P' Y888888P      888888D      Y88888P ~Y8888P' YP   YP  CONVERTER
]=]

-- Instances: 15 | Scripts: 0 | Modules: 0
local G2L = {};

-- StarterGui.Alt control
G2L["1"] = Instance.new("ScreenGui", game.CoreGui);
G2L["1"]["Name"] = [[Alt control]];
G2L["1"]["ZIndexBehavior"] = Enum.ZIndexBehavior.Sibling;

-- StarterGui.Alt control.MainUI
G2L["2"] = Instance.new("Frame", G2L["1"]);
G2L["2"]["BorderSizePixel"] = 100;
G2L["2"]["BackgroundColor3"] = Color3.fromRGB(36, 36, 36);
G2L["2"]["Size"] = UDim2.new(1, 0, 1, 0);
G2L["2"]["BorderColor3"] = Color3.fromRGB(36, 36, 36);
G2L["2"]["Name"] = [[MainUI]];

-- StarterGui.Alt control.MainUI.Holder
G2L["3"] = Instance.new("Frame", G2L["2"]);
G2L["3"]["BorderSizePixel"] = 0;
G2L["3"]["BackgroundColor3"] = Color3.fromRGB(25, 25, 25);
G2L["3"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["3"]["Size"] = UDim2.new(0, 1310, 0, 585);
G2L["3"]["Position"] = UDim2.new(0.5, 0, 0.5436005592346191, 0);
G2L["3"]["Name"] = [[Holder]];

-- StarterGui.Alt control.MainUI.Holder.UICorner
G2L["4"] = Instance.new("UICorner", G2L["3"]);



-- StarterGui.Alt control.MainUI.Holder.Pfp and stuff
G2L["5"] = Instance.new("ImageLabel", G2L["3"]);
G2L["5"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["5"]["Image"] = PlayerThumbnail;
G2L["5"]["Size"] = UDim2.new(0, 152, 0, 143);
G2L["5"]["Name"] = [[Pfp and stuff]];
G2L["5"]["Position"] = UDim2.new(0.44198474287986755, 0, 0.4923076629638672, 0);

-- StarterGui.Alt control.MainUI.Holder.Pfp and stuff.UICorner
G2L["6"] = Instance.new("UICorner", G2L["5"]);
G2L["6"]["CornerRadius"] = UDim.new(100, 100);

-- StarterGui.Alt control.MainUI.Holder.Pfp and stuff.Username
G2L["7"] = Instance.new("TextLabel", G2L["5"]);
G2L["7"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["7"]["TextSize"] = 25;
G2L["7"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["7"]["Size"] = UDim2.new(0, 297, 0, 50);
G2L["7"]["Text"] = [[Greetings, ]]..plrName;
G2L["7"]["Name"] = [[Username]];
G2L["7"]["Font"] = Enum.Font.Gotham;
G2L["7"]["BackgroundTransparency"] = 1;
G2L["7"]["Position"] = UDim2.new(-0.47790244221687317, 0, 1.093414545059204, 0);

-- StarterGui.Alt control.MainUI.Holder.Pfp and stuff.UserID
G2L["8"] = Instance.new("TextLabel", G2L["5"]);
G2L["8"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["8"]["TextSize"] = 20;
G2L["8"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["8"]["Size"] = UDim2.new(0, 193, 0, 50);
G2L["8"]["Text"] = [[UserID : ]]..plrId;
G2L["8"]["Name"] = [[UserID]];
G2L["8"]["Font"] = Enum.Font.Gotham;
G2L["8"]["BackgroundTransparency"] = 1;
G2L["8"]["Position"] = UDim2.new(-0.47790244221687317, 0, 1.3565725088119507, 0);

-- StarterGui.Alt control.MainUI.Holder.Pfp and stuff.Cash
G2L["9"] = Instance.new("TextLabel", G2L["5"]);
G2L["9"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["9"]["TextSize"] = 20;
G2L["9"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["9"]["Size"] = UDim2.new(0, 144, 0, 50);
G2L["9"]["Text"] = [[Cash : ]]..cash;
G2L["9"]["Name"] = [[Cash]];
G2L["9"]["Font"] = Enum.Font.Gotham;
G2L["9"]["BackgroundTransparency"] = 1;
G2L["9"]["Position"] = UDim2.new(-0.49230125546455383, 1, 1.587296724319458, 0);

-- StarterGui.Alt control.MainUI.Holder.Kick alts
G2L["a"] = Instance.new("TextButton", G2L["3"]);
G2L["a"]["BorderSizePixel"] = 0;
G2L["a"]["TextSize"] = 18;
G2L["a"]["BackgroundColor3"] = Color3.fromRGB(36, 36, 36);
G2L["a"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["a"]["Size"] = UDim2.new(0, 158, 0, 65);
G2L["a"]["Name"] = [[Kick alts]];
G2L["a"]["Text"] = [[Kick alts]];
G2L["a"]["Font"] = Enum.Font.Gotham;
G2L["a"]["Position"] = UDim2.new(0.43969467282295227, 0, 0.1606837660074234, 0);

-- StarterGui.Alt control.MainUI.Holder.Kick alts.UICorner
G2L["b"] = Instance.new("UICorner", G2L["a"]);

-- StarterGui.Alt control.MainUI.Holder.Kick alts.LocalScript
G2L["c"] = Instance.new("LocalScript", G2L["a"]);

-- StarterGui.Alt control.MainUI.Holder.Reset ats
G2L["c"] = Instance.new("TextButton", G2L["3"]);
G2L["c"]["BorderSizePixel"] = 0;
G2L["c"]["TextSize"] = 18;
G2L["c"]["BackgroundColor3"] = Color3.fromRGB(36, 36, 36);
G2L["c"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["c"]["Size"] = UDim2.new(0, 158, 0, 65);
G2L["c"]["Name"] = [[Reset ats]];
G2L["c"]["Text"] = [[Reset alts]];
G2L["c"]["Font"] = Enum.Font.Gotham;
G2L["c"]["Position"] = UDim2.new(0.43969467282295227, 0, 0.3042735159397125, 0);

-- StarterGui.Alt control.MainUI.Holder.Reset ats.UICorner
G2L["d"] = Instance.new("UICorner", G2L["c"]);

-- StarterGui.Alt control.MainUI.Holder.Reset ats.LocalScript
G2L["f"] = Instance.new("LocalScript", G2L["d"]);

-- StarterGui.Alt control.MainUI.Title
G2L["e"] = Instance.new("TextLabel", G2L["2"]);
G2L["e"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["e"]["TextSize"] = 30;
G2L["e"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["e"]["Size"] = UDim2.new(0, 200, 0, 50);
G2L["e"]["Text"] = [[Strike Hub]];
G2L["e"]["Name"] = [[Title]];
G2L["e"]["Font"] = Enum.Font.Gotham;
G2L["e"]["BackgroundTransparency"] = 1;
G2L["e"]["Position"] = UDim2.new(0.4263623058795929, 0, 0.026722926646471024, 0);

-- StarterGui.Alt control.MainUI.Subtitle
G2L["f"] = Instance.new("TextLabel", G2L["2"]);
G2L["f"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["f"]["TextSize"] = 25;
G2L["f"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["f"]["Size"] = UDim2.new(0, 200, 0, 50);
G2L["f"]["Text"] = [[Alt control V2]];
G2L["f"]["Name"] = [[Subtitle]];
G2L["f"]["Font"] = Enum.Font.Gotham;
G2L["f"]["BackgroundTransparency"] = 1;
G2L["f"]["Position"] = UDim2.new(0.4263623058795929, 0, 0.061884671449661255, 0);


-- StarterGui.Alt control.MainUI.Holder.Kick alts.LocalScript
local function C_c()
	local script = G2L["c"];
	script.Parent.MouseButton1Click:Connect(function()
		game.Players.LocalPlayer:Kick("Kicked!")
	end)
end;
task.spawn(C_c);
-- StarterGui.Alt control.MainUI.Holder.Reset ats.LocalScript
local function C_f()
	local script = G2L["f"];
	script.Parent.MouseButton1Click:Connect(function()
		game.Players.LocalPlayer.Character:FindFirstChild("Humanoid").Health = 0
	end)
end;
task.spawn(C_f);

return G2L["1"];
