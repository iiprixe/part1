-- Gui to Lua
-- Version: 3.2

-- Instances:

local executer = Instance.new("ScreenGui")
local executer_2 = Instance.new("Frame")
local UICorner = Instance.new("UICorner")
local Frame = Instance.new("Frame")
local ImageButton = Instance.new("ImageButton")
local TextLabel = Instance.new("TextLabel")
local BackGround = Instance.new("Frame")
local Holder = Instance.new("Frame")
local execute = Instance.new("TextButton")
local UICorner_2 = Instance.new("UICorner")
local Clear = Instance.new("TextButton")
local UICorner_3 = Instance.new("UICorner")
local BackGroundBottom = Instance.new("Frame")
local UICorner_4 = Instance.new("UICorner")
local ImageLabel = Instance.new("ImageLabel")
local security = Instance.new("TextLabel")
local UICorner_5 = Instance.new("UICorner")
local EditorFrame = Instance.new("ScrollingFrame")
local UICorner_6 = Instance.new("UICorner")
local Lines = Instance.new("TextLabel")
local Source = Instance.new("TextBox")
local Comments_ = Instance.new("TextLabel")
local Globals_ = Instance.new("TextLabel")
local Tokens_ = Instance.new("TextLabel")
local RemoteHighlight_ = Instance.new("TextLabel")
local Strings_ = Instance.new("TextLabel")
local Numbers_ = Instance.new("TextLabel")
local Keywords_ = Instance.new("TextLabel")
local Frame_2 = Instance.new("Frame")
local OpenDev = Instance.new("TextButton")
local UICorner_7 = Instance.new("UICorner")

--Properties:

executer.Name = "executer"
executer.Parent = game.CoreGui
executer.ResetOnSpawn = false

executer_2.Name = "executer"
executer_2.Parent = executer
executer_2.Active = true
executer_2.BackgroundColor3 = Color3.fromRGB(36, 77, 113)
executer_2.Position = UDim2.new(0.038002979, 0, 0.13966158, 0)
executer_2.Size = UDim2.new(0, 562, 0, 28)
executer_2.Active = true
executer_2.Draggable = true 

UICorner.CornerRadius = UDim.new(0, 9)
UICorner.Parent = executer_2

Frame.Parent = executer_2
Frame.BackgroundColor3 = Color3.fromRGB(36, 77, 113)
Frame.BorderColor3 = Color3.fromRGB(27, 42, 53)
Frame.BorderSizePixel = 0
Frame.Position = UDim2.new(0, 0, 0.563450515, 0)
Frame.Size = UDim2.new(0, 562, 0, 15)

ImageButton.Parent = executer_2
ImageButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageButton.BackgroundTransparency = 1.000
ImageButton.Position = UDim2.new(0, 0, 0.0357142873, 0)
ImageButton.Size = UDim2.new(0, 26, 0, 28)
ImageButton.Image = "rbxassetid://4430382116"

TextLabel.Parent = executer_2
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.Position = UDim2.new(0.0719518661, 0, 0.0896355733, 0)
TextLabel.Size = UDim2.new(0, 309, 0, 24)
TextLabel.Font = Enum.Font.GothamBold
TextLabel.Text = "Sekkays Gui - Right Control To Open/Close - Sekkay God#4968"
TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.TextSize = 11.000

BackGround.Name = "BackGround"
BackGround.Parent = executer_2
BackGround.BackgroundColor3 = Color3.fromRGB(33, 33, 33)
BackGround.BackgroundTransparency = 1.000
BackGround.BorderColor3 = Color3.fromRGB(27, 42, 53)
BackGround.BorderSizePixel = 0
BackGround.ClipsDescendants = true
BackGround.Position = UDim2.new(0, 0, 1, 0)
BackGround.Size = UDim2.new(0, 758, 0, 463)

Holder.Name = "Holder"
Holder.Parent = BackGround
Holder.BackgroundColor3 = Color3.fromRGB(33, 33, 33)
Holder.BorderColor3 = Color3.fromRGB(27, 42, 53)
Holder.BorderSizePixel = 0
Holder.Position = UDim2.new(-0.00263852254, 0, 0.000341691426, 0)
Holder.Size = UDim2.new(0, 564, 0, 415)

execute.Name = "execute"
execute.Parent = Holder
execute.BackgroundColor3 = Color3.fromRGB(36, 77, 113)
execute.Position = UDim2.new(0.0201750416, 0, 0.976539612, 0)
execute.Size = UDim2.new(0, 100, 0, 30)
execute.ZIndex = 3
execute.Font = Enum.Font.GothamBold
execute.Text = "Execute"
execute.TextColor3 = Color3.fromRGB(255, 255, 255)
execute.TextSize = 14.000

UICorner_2.CornerRadius = UDim.new(0, 6)
UICorner_2.Parent = execute

Clear.Name = "Clear"
Clear.Parent = Holder
Clear.BackgroundColor3 = Color3.fromRGB(36, 77, 113)
Clear.Position = UDim2.new(0.208190382, 0, 0.976539612, 0)
Clear.Size = UDim2.new(0, 76, 0, 30)
Clear.ZIndex = 3
Clear.Font = Enum.Font.GothamBold
Clear.Text = "Clear"
Clear.TextColor3 = Color3.fromRGB(255, 255, 255)
Clear.TextSize = 14.000

UICorner_3.CornerRadius = UDim.new(0, 6)
UICorner_3.Parent = Clear

BackGroundBottom.Name = "BackGroundBottom"
BackGroundBottom.Parent = Holder
BackGroundBottom.BackgroundColor3 = Color3.fromRGB(33, 33, 33)
BackGroundBottom.BorderColor3 = Color3.fromRGB(27, 42, 53)
BackGroundBottom.Position = UDim2.new(0.003539823, 0, 0.978310227, 0)
BackGroundBottom.Size = UDim2.new(0, 562, 0, 36)

UICorner_4.CornerRadius = UDim.new(0, 9)
UICorner_4.Parent = BackGroundBottom

ImageLabel.Parent = Holder
ImageLabel.BackgroundColor3 = Color3.fromRGB(50, 50, 50)
ImageLabel.BorderSizePixel = 0
ImageLabel.Position = UDim2.new(0.0176295284, 0, 0.0406044833, 27)
ImageLabel.Size = UDim2.new(0, 547, 0, 355)

security.Name = "security"
security.Parent = ImageLabel
security.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
security.Size = UDim2.new(0, 535, 0, 379)
security.Visible = false
security.Font = Enum.Font.SourceSans
security.TextColor3 = Color3.fromRGB(0, 0, 0)
security.TextSize = 14.000

UICorner_5.Parent = ImageLabel

EditorFrame.Name = "EditorFrame"
EditorFrame.Parent = ImageLabel
EditorFrame.Active = true
EditorFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
EditorFrame.BackgroundTransparency = 1.000
EditorFrame.BorderSizePixel = 0
EditorFrame.Position = UDim2.new(0.00262462581, 0, 0.0233220328, 0)
EditorFrame.Size = UDim2.new(0, 545, 0, 359)
EditorFrame.ScrollBarThickness = 0

UICorner_6.Parent = EditorFrame

Lines.Name = "Lines"
Lines.Parent = EditorFrame
Lines.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Lines.BackgroundTransparency = 1.000
Lines.Size = UDim2.new(0, 30, 1, 0)
Lines.ZIndex = 4
Lines.Font = Enum.Font.Code
Lines.Text = "1"
Lines.TextColor3 = Color3.fromRGB(255, 255, 255)
Lines.TextSize = 15.000
Lines.TextYAlignment = Enum.TextYAlignment.Top

Source.Name = "Source"
Source.Parent = EditorFrame
Source.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Source.BackgroundTransparency = 1.000
Source.Position = UDim2.new(0, 23, 0, 0)
Source.Size = UDim2.new(0.918072343, 0, 87.6142654, 0)
Source.ZIndex = 3
Source.ClearTextOnFocus = false
Source.Font = Enum.Font.Code
Source.MultiLine = true
Source.PlaceholderColor3 = Color3.fromRGB(204, 204, 204)
Source.Text = "print(\"Sekkay Is Cool\")"
Source.TextColor3 = Color3.fromRGB(191, 191, 191)
Source.TextSize = 15.000
Source.TextWrapped = true
Source.TextXAlignment = Enum.TextXAlignment.Left
Source.TextYAlignment = Enum.TextYAlignment.Top

Comments_.Name = "Comments_"
Comments_.Parent = Source
Comments_.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Comments_.BackgroundTransparency = 1.000
Comments_.Size = UDim2.new(1, 0, 1, 0)
Comments_.ZIndex = 5
Comments_.Font = Enum.Font.Code
Comments_.Text = ""
Comments_.TextColor3 = Color3.fromRGB(59, 200, 59)
Comments_.TextSize = 15.000
Comments_.TextXAlignment = Enum.TextXAlignment.Left
Comments_.TextYAlignment = Enum.TextYAlignment.Top

Globals_.Name = "Globals_"
Globals_.Parent = Source
Globals_.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Globals_.BackgroundTransparency = 1.000
Globals_.Size = UDim2.new(0.959459484, 0, 1, 0)
Globals_.ZIndex = 5
Globals_.Font = Enum.Font.Code
Globals_.Text = ""
Globals_.TextColor3 = Color3.fromRGB(85, 170, 255)
Globals_.TextSize = 15.000
Globals_.TextXAlignment = Enum.TextXAlignment.Left
Globals_.TextYAlignment = Enum.TextYAlignment.Top

Tokens_.Name = "Tokens_"
Tokens_.Parent = Source
Tokens_.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Tokens_.BackgroundTransparency = 1.000
Tokens_.Size = UDim2.new(1, 0, 1, 0)
Tokens_.ZIndex = 5
Tokens_.Font = Enum.Font.Code
Tokens_.Text = ""
Tokens_.TextColor3 = Color3.fromRGB(255, 255, 255)
Tokens_.TextSize = 15.000
Tokens_.TextXAlignment = Enum.TextXAlignment.Left
Tokens_.TextYAlignment = Enum.TextYAlignment.Top

RemoteHighlight_.Name = "RemoteHighlight_"
RemoteHighlight_.Parent = Source
RemoteHighlight_.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
RemoteHighlight_.BackgroundTransparency = 1.000
RemoteHighlight_.Size = UDim2.new(1, 0, 1, 0)
RemoteHighlight_.ZIndex = 5
RemoteHighlight_.Font = Enum.Font.Code
RemoteHighlight_.Text = ""
RemoteHighlight_.TextColor3 = Color3.fromRGB(0, 170, 255)
RemoteHighlight_.TextSize = 15.000
RemoteHighlight_.TextXAlignment = Enum.TextXAlignment.Left
RemoteHighlight_.TextYAlignment = Enum.TextYAlignment.Top

Strings_.Name = "Strings_"
Strings_.Parent = Source
Strings_.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Strings_.BackgroundTransparency = 1.000
Strings_.Size = UDim2.new(1, 0, 1, 0)
Strings_.ZIndex = 5
Strings_.Font = Enum.Font.Code
Strings_.Text = ""
Strings_.TextColor3 = Color3.fromRGB(173, 241, 149)
Strings_.TextSize = 15.000
Strings_.TextXAlignment = Enum.TextXAlignment.Left
Strings_.TextYAlignment = Enum.TextYAlignment.Top

Numbers_.Name = "Numbers_"
Numbers_.Parent = Source
Numbers_.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Numbers_.BackgroundTransparency = 1.000
Numbers_.Size = UDim2.new(1, 0, 1, 0)
Numbers_.ZIndex = 4
Numbers_.Font = Enum.Font.Code
Numbers_.Text = ""
Numbers_.TextColor3 = Color3.fromRGB(170, 170, 255)
Numbers_.TextSize = 15.000
Numbers_.TextXAlignment = Enum.TextXAlignment.Left
Numbers_.TextYAlignment = Enum.TextYAlignment.Top

Keywords_.Name = "Keywords_"
Keywords_.Parent = Source
Keywords_.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Keywords_.BackgroundTransparency = 1.000
Keywords_.Size = UDim2.new(1, 0, 1, 0)
Keywords_.ZIndex = 5
Keywords_.Font = Enum.Font.Code
Keywords_.Text = ""
Keywords_.TextColor3 = Color3.fromRGB(85, 85, 255)
Keywords_.TextSize = 15.000
Keywords_.TextXAlignment = Enum.TextXAlignment.Left
Keywords_.TextYAlignment = Enum.TextYAlignment.Top

Frame_2.Parent = Holder
Frame_2.BackgroundColor3 = Color3.fromRGB(36, 77, 113)
Frame_2.BorderColor3 = Color3.fromRGB(27, 42, 53)
Frame_2.BorderSizePixel = 0
Frame_2.Position = UDim2.new(0.0195035469, 0, 0.0771084353, 0)
Frame_2.Size = UDim2.new(0, 545, 0, 3)

OpenDev.Name = "OpenDev"
OpenDev.Parent = Holder
OpenDev.BackgroundColor3 = Color3.fromRGB(36, 77, 113)
OpenDev.Position = UDim2.new(0.0184740648, 0, 0.0247323643, 0)
OpenDev.Size = UDim2.new(0, 94, 0, 19)
OpenDev.ZIndex = 3
OpenDev.Font = Enum.Font.GothamBold
OpenDev.Text = "Dev Console"
OpenDev.TextColor3 = Color3.fromRGB(255, 255, 255)
OpenDev.TextSize = 14.000

UICorner_7.CornerRadius = UDim.new(0, 6)
UICorner_7.Parent = OpenDev

-- Scripts:

local function TDSD_fake_script() -- ImageButton.LocalScript 
	local script = Instance.new('LocalScript', ImageButton)

	local D = true
	
	script.Parent.MouseButton1Click:Connect(function()
		if D == true then
			script.Parent.Parent.BackGround.Holder:TweenPosition(UDim2.new(-0.003, 0,-0.995, 0),nil, nil, 0.5)
			D = false
		else
			D = true
			script.Parent.Parent.BackGround.Holder:TweenPosition(UDim2.new(-0.003, 0,0, 0),nil, nil, 0.5)
		end
	end)
end
coroutine.wrap(TDSD_fake_script)()
local function VAGGVR_fake_script() -- execute.LocalScript 
	local script = Instance.new('LocalScript', execute)

	script.Parent.MouseButton1Click:Connect(function()
		assert(loadstring(script.Parent.Parent.ImageLabel.EditorFrame.Source.Text))()
	end)
end
coroutine.wrap(VAGGVR_fake_script)()
local function JZQRRZ_fake_script() -- Clear.LocalScript 
	local script = Instance.new('LocalScript', Clear)

	
	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.ImageLabel.EditorFrame.Source.Text = "";
	end);
	
end
coroutine.wrap(JZQRRZ_fake_script)()
local function FEOJJ_fake_script() -- ImageLabel.LocalScript 
	local script = Instance.new('LocalScript', ImageLabel)

	-- Decompiled with the Synapse X Luau decompiler.
	
	local l__Source__1 = script.Parent.EditorFrame.Source;
	local function u1(p1, p2)
		local v2 = {};
		for v3, v4 in pairs(p2) do
			v2[v4] = true;
		end;
		local u2 = {
			["="] = true, 
			["."] = true, 
			[","] = true, 
			["("] = true, 
			[")"] = true, 
			["["] = true, 
			["]"] = true, 
			["{"] = true, 
			["}"] = true, 
			[":"] = true, 
			["*"] = true, 
			["/"] = true, 
			["+"] = true, 
			["-"] = true, 
			["%"] = true, 
			[";"] = true, 
			["~"] = true
		};
		return p1:gsub(".", function(p3)
			if u2[p3] == nil then
				return p3;
			end;
			return " ";
		end):gsub("%S+", function(p4)
			if v2[p4] ~= nil then
				return p4;
			end;
			return (" "):rep(#p4);
		end);
	end;
	local u3 = { "and", "break", "do", "else", "elseif", "end", "false", "for", "function", "goto", "if", "in", "local", "nil", "not", "or", "repeat", "return", "then", "true", "until", "while" };
	local u4 = { "getrawmetatable", "game", "workspace", "script", "math", "string", "table", "print", "wait", "BrickColor", "Color3", "next", "pairs", "ipairs", "select", "unpack", "Instance", "Vector2", "Vector3", "CFrame", "Ray", "UDim2", "Enum", "assert", "error", "warn", "tick", "loadstring", "_G", "shared", "getfenv", "setfenv", "newproxy", "setmetatable", "getmetatable", "os", "debug", "pcall", "ypcall", "xpcall", "rawequal", "rawset", "rawget", "tonumber", "tostring", "type", "typeof", "_VERSION", "coroutine", "delay", "require", "spawn", "LoadLibrary", "settings", "stats", "time", "UserSettings", "version", "Axes", "ColorSequence", "Faces", "ColorSequenceKeypoint", "NumberRange", "NumberSequence", "NumberSequenceKeypoint", "gcinfo", "elapsedTime", "collectgarbage", "PhysicalProperties", "Rect", "Region3", "Region3int16", "UDim", "Vector2int16", "Vector3int16" };
	local function u5(p5)
		local u6 = {
			["="] = true, 
			["."] = true, 
			[","] = true, 
			["("] = true, 
			[")"] = true, 
			["["] = true, 
			["]"] = true, 
			["{"] = true, 
			["}"] = true, 
			[":"] = true, 
			["*"] = true, 
			["/"] = true, 
			["+"] = true, 
			["-"] = true, 
			["%"] = true, 
			[";"] = true, 
			["~"] = true
		};
		local u7 = "";
		p5:gsub(".", function(p6)
			if u6[p6] ~= nil then
				u7 = u7 .. p6;
				return;
			end;
			if p6 == "\n" then
				u7 = u7 .. "\n";
				return;
			end;
			if p6 == "\t" then
				u7 = u7 .. "\t";
				return;
			end;
			u7 = u7 .. " ";
		end);
		return "";
	end;
	local function u8(p7)
		local u9 = "";
		p7:gsub(".", function(p8)
			if tonumber(p8) ~= nil then
				u9 = u9 .. p8;
				return;
			end;
			if p8 == "\n" then
				u9 = u9 .. "\n";
				return;
			end;
			if p8 == "\t" then
				u9 = u9 .. "\t";
				return;
			end;
			u9 = u9 .. " ";
		end);
		return "";
	end;
	local function u10(p9)
		local u11 = false;
		local u12 = "";
		p9:gsub(".", function(p10)
			if u11 == false and p10 == "\"" then
				u11 = true;
			elseif u11 == true and p10 == "\"" then
				u11 = false;
			end;
			if u11 == false and p10 == "\"" then
				u12 = u12 .. "\"";
				return;
			end;
			if p10 == "\n" then
				u12 = u12 .. "\n";
				return;
			end;
			if p10 == "\t" then
				u12 = u12 .. "\t";
				return;
			end;
			if u11 == true then
				u12 = u12 .. p10;
				return;
			end;
			if u11 == false then
				u12 = u12 .. " ";
			end;
		end);
		return "";
	end;
	local l__Lines__13 = l__Source__1.Parent.Lines;
	local function v5(p11)
		if p11 == "Text" then
			l__Source__1.Text = l__Source__1.Text:gsub("\r", "");
			l__Source__1.Text = l__Source__1.Text:gsub("\t", "      ");
			local l__Text__6 = l__Source__1.Text;
			l__Source__1.Keywords_.Text = u1(l__Text__6, u3);
			l__Source__1.Globals_.Text = u1(l__Text__6, u4);
			l__Source__1.RemoteHighlight_.Text = u1(l__Text__6, { "FireServer", "fireServer", "InvokeServer", "invokeServer" });
			l__Source__1.Tokens_.Text = u5(l__Text__6);
			l__Source__1.Numbers_.Text = u8(l__Text__6);
			l__Source__1.Strings_.Text = u10(l__Text__6);
			local u14 = 1;
			l__Text__6:gsub("\n", function()
				u14 = u14 + 1;
			end);
			l__Lines__13.Text = "";
			for v7 = 1, u14 do
				l__Lines__13.Text = l__Lines__13.Text .. v7 .. "\n";
			end;
		end;
	end;
	v5("Text");
	l__Source__1.Changed:Connect(v5);
	
end
coroutine.wrap(FEOJJ_fake_script)()
local function ZYWIBH_fake_script() -- OpenDev.LocalScript 
	local script = Instance.new('LocalScript', OpenDev)

	script.Parent.MouseButton1Click:Connect(function()
	
		local console = Instance.new("ScreenGui")
		local console_2 = Instance.new("Frame")
		local UICorner = Instance.new("UICorner")
		local Frame = Instance.new("Frame")
		local ImageButton = Instance.new("ImageButton")
		local TextLabel = Instance.new("TextLabel")
		local BackGround = Instance.new("Frame")
		local Holder = Instance.new("Frame")
		local BackGroundBottom = Instance.new("Frame")
		local UICorner_2 = Instance.new("UICorner")
		local ImageLabel = Instance.new("ImageLabel")
		local UICorner_3 = Instance.new("UICorner")
		local OutputFrame = Instance.new("Frame")
		local console_3 = Instance.new("ScrollingFrame")
		local output = Instance.new("TextLabel")
	
		--Properties:
	
		console.Name = "console"
		console.Parent = game.CoreGui
		console.ResetOnSpawn = false
	
		console_2.Name = "console"
		console_2.Parent = console
		console_2.Active = true
		console_2.BackgroundColor3 = Color3.fromRGB(36, 77, 113)
		console_2.Position = UDim2.new(0.472429216, 0, 0.13966158, 0)
		console_2.Size = UDim2.new(0, 551, 0, 27)
		console_2.Active = true
		console_2.Draggable = true
	
		UICorner.CornerRadius = UDim.new(0, 9)
		UICorner.Parent = console_2
	
		Frame.Parent = console_2
		Frame.BackgroundColor3 = Color3.fromRGB(36, 77, 113)
		Frame.BorderColor3 = Color3.fromRGB(27, 42, 53)
		Frame.BorderSizePixel = 0
		Frame.Position = UDim2.new(0, 0, 0.581612468, 0)
		Frame.Size = UDim2.new(0, 551, 0, 13)
	
		ImageButton.Parent = console_2
		ImageButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
		ImageButton.BackgroundTransparency = 1.000
		ImageButton.Position = UDim2.new(0, 0, 0.0357142873, 0)
		ImageButton.Size = UDim2.new(0, 26, 0, 28)
		ImageButton.Image = "rbxassetid://4430382116"
	
		TextLabel.Parent = console_2
		TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
		TextLabel.BackgroundTransparency = 1.000
		TextLabel.Position = UDim2.new(0.0470871255, 0, 0.129992455, 0)
		TextLabel.Size = UDim2.new(0, 309, 0, 23)
		TextLabel.Font = Enum.Font.GothamBold
		TextLabel.Text = "Dev Console"
		TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
		TextLabel.TextSize = 12.000
		TextLabel.TextXAlignment = Enum.TextXAlignment.Left
	
		BackGround.Name = "BackGround"
		BackGround.Parent = console_2
		BackGround.BackgroundColor3 = Color3.fromRGB(33, 33, 33)
		BackGround.BackgroundTransparency = 1.000
		BackGround.BorderColor3 = Color3.fromRGB(27, 42, 53)
		BackGround.BorderSizePixel = 0
		BackGround.ClipsDescendants = true
		BackGround.Position = UDim2.new(0, 0, 1, 0)
		BackGround.Size = UDim2.new(0, 758, 0, 463)
	
		Holder.Name = "Holder"
		Holder.Parent = BackGround
		Holder.BackgroundColor3 = Color3.fromRGB(33, 33, 33)
		Holder.BorderColor3 = Color3.fromRGB(27, 42, 53)
		Holder.BorderSizePixel = 0
		Holder.Position = UDim2.new(0, 0, 0.00215982716, 0)
		Holder.Size = UDim2.new(0, 551, 0, 420)
	
		BackGroundBottom.Name = "BackGroundBottom"
		BackGroundBottom.Parent = Holder
		BackGroundBottom.BackgroundColor3 = Color3.fromRGB(33, 33, 33)
		BackGroundBottom.BorderColor3 = Color3.fromRGB(27, 42, 53)
		BackGroundBottom.Position = UDim2.new(0, 0, 0.980369031, 0)
		BackGroundBottom.Size = UDim2.new(0, 551, 0, 37)
	
		UICorner_2.CornerRadius = UDim.new(0, 9)
		UICorner_2.Parent = BackGroundBottom
	
		ImageLabel.Parent = Holder
		ImageLabel.BackgroundColor3 = Color3.fromRGB(50, 50, 50)
		ImageLabel.BorderSizePixel = 0
		ImageLabel.Position = UDim2.new(0.0132137239, 0, -0.0372529514, 27)
		ImageLabel.Size = UDim2.new(0, 537, 0, 425)
	
		UICorner_3.Parent = ImageLabel
	
		OutputFrame.Name = "OutputFrame"
		OutputFrame.Parent = ImageLabel
		OutputFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
		OutputFrame.BackgroundTransparency = 1.000
		OutputFrame.Position = UDim2.new(0, 0, 0.0448568203, 0)
		OutputFrame.Size = UDim2.new(0, 538, 0, 395)
	
		console_3.Name = "console"
		console_3.Parent = OutputFrame
		console_3.BackgroundColor3 = Color3.fromRGB(76, 76, 76)
		console_3.BackgroundTransparency = 1.000
		console_3.BorderColor3 = Color3.fromRGB(36, 77, 113)
		console_3.BorderSizePixel = 2
		console_3.Position = UDim2.new(1.02973974, -554, 0.684633434, -278)
		console_3.Size = UDim2.new(0, 537, 0, 404)
		console_3.CanvasSize = UDim2.new(4, 5, 9999999, 9999999)
	
		output.Name = "output"
		output.Parent = console_3
		output.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
		output.BackgroundTransparency = 1.000
		output.Size = UDim2.new(0, 517, 0, 11)
		output.Font = Enum.Font.Code
		output.Text = ""
		output.TextColor3 = Color3.fromRGB(59, 255, 0)
		output.TextSize = 14.000
		output.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
		output.TextXAlignment = Enum.TextXAlignment.Left
		output.TextYAlignment = Enum.TextYAlignment.Top
	
		-- Scripts:
	
		local function JWDDU_fake_script() -- ImageButton.LocalScript 
			local script = Instance.new('LocalScript', ImageButton)
	
			local D = true
	
			script.Parent.MouseButton1Click:Connect(function()
				if D == true then
					script.Parent.Parent.BackGround.Holder:TweenPosition(UDim2.new(0, 0,-1.06, 0),nil, nil, 0.5)
					D = false
				else
					D = true
					script.Parent.Parent.BackGround.Holder:TweenPosition(UDim2.new(0, 0,0, 0),nil, nil, 0.5)
				end
			end)
		end
		coroutine.wrap(JWDDU_fake_script)()
		local function DBSRQ_fake_script() -- console_3.console 
			local script = Instance.new('LocalScript', console_3)
	
			--in play mode the console only shows output from localscripts.
			--made by pyccknnxakep
			local player = game.Players.LocalPlayer
			local ls = game:GetService('LogService')
			local colors = {[0] = Color3.new(1, 1, 1), Color3.new(0/255,98/255,255/255), Color3.new(1, 1, 0), Color3.new(1, 0, 0)}
			local num = 0
			ls.MessageOut:Connect(function(msg,type)
				num = num + 1
				local t = tick()
				local l = script.Parent.output:Clone()
				l.Position = UDim2.new(0, 0, 0, num*24)
				l.Text = ('>[%02i:%02i:%02i] - %s'):format((t/3600)%24, (t/60)%60, t%60, msg)
				l.TextColor3 = colors[type.Value]
				l.Parent = script.Parent
			end)
			script.Parent.Parent.button.MouseButton1Click:Connect(function()
				script.Parent.Visible = not script.Parent.Visible
			end)
		end
		coroutine.wrap(DBSRQ_fake_script)()
		local function GQIFGKV_fake_script() -- console_2.LocalScript 
			local script = Instance.new('LocalScript', console_2)
	
			local UserInputService = game:GetService("UserInputService")
	
			function onKeyPress(inputObject, gameProcessedEvent)
				if not gameProcessedEvent then
					if inputObject.KeyCode == Enum.KeyCode.RightControl then 
						if script.Parent.Visible == false then
							script.Parent.Visible = true
						else
							script.Parent.Visible = false
						end
					end
				end
			end
	
			UserInputService.InputBegan:connect(onKeyPress)
		end
		coroutine.wrap(GQIFGKV_fake_script)()
		local function PLOAI_fake_script() -- console_2.Dragify 
			local script = Instance.new('LocalScript', console_2)
	
			script.Parent.Parent.console.Active = true
			script.Parent.Parent.console.Draggable = true
		end
		coroutine.wrap(PLOAI_fake_script)()
		local function SBBUE_fake_script() -- console_2.Dragify 
			local script = Instance.new('LocalScript', console_2)
	
			local UserInputService = game:GetService("UserInputService")
	
			local gui = script.Parent
	
			local dragging
			local dragInput
			local dragStart
			local startPos
	
			local function update(input)
				local delta = input.Position - dragStart
				gui.Position = UDim2.new(startPos.X.Scale, startPos.X.Offset + delta.X, startPos.Y.Scale, startPos.Y.Offset + delta.Y)
			end
	
			gui.InputBegan:Connect(function(input)
				if input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch then
					dragging = true
					dragStart = input.Position
					startPos = gui.Position
	
					input.Changed:Connect(function()
						if input.UserInputState == Enum.UserInputState.End then
							dragging = false
						end
					end)
				end
			end)
	
			gui.InputChanged:Connect(function(input)
				if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
					dragInput = input
				end
			end)
	
			UserInputService.InputChanged:Connect(function(input)
				if input == dragInput and dragging then
					update(input)
				end
			end)
		end
		coroutine.wrap(SBBUE_fake_script)()
	end)
end
coroutine.wrap(ZYWIBH_fake_script)()
local function FQURVH_fake_script() -- executer_2.LocalScript 
	local script = Instance.new('LocalScript', executer_2)

	local UserInputService = game:GetService("UserInputService")
	
	function onKeyPress(inputObject, gameProcessedEvent)
		if not gameProcessedEvent then
	    if inputObject.KeyCode == Enum.KeyCode.RightControl then 
				if script.Parent.Visible == false then
					script.Parent.Visible = true
				else
					script.Parent.Visible = false
				end
			end
		end
	end
	
	UserInputService.InputBegan:connect(onKeyPress)
end
coroutine.wrap(FQURVH_fake_script)()
local function NYPU_fake_script() -- executer_2.Dragify 
	local script = Instance.new('LocalScript', executer_2)

	script.Parent.Parent.executer.Active = true
	script.Parent.Parent.executer = true
end
coroutine.wrap(NYPU_fake_script)()
local function QULLM_fake_script() -- executer_2.Dragify 
	local script = Instance.new('LocalScript', executer_2)

	local UserInputService = game:GetService("UserInputService")
	
	local gui = script.Parent
	
	local dragging
	local dragInput
	local dragStart
	local startPos
	
	local function update(input)
		local delta = input.Position - dragStart
		gui.Position = UDim2.new(startPos.X.Scale, startPos.X.Offset + delta.X, startPos.Y.Scale, startPos.Y.Offset + delta.Y)
	end
	
	gui.InputBegan:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch then
			dragging = true
			dragStart = input.Position
			startPos = gui.Position
	
			input.Changed:Connect(function()
				if input.UserInputState == Enum.UserInputState.End then
					dragging = false
				end
			end)
		end
	end)
	
	gui.InputChanged:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
			dragInput = input
		end
	end)
	
	UserInputService.InputChanged:Connect(function(input)
		if input == dragInput and dragging then
			update(input)
		end
	end)
end
coroutine.wrap(QULLM_fake_script)()
