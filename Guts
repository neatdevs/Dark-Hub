--[[ Hats needed below:
https://www.roblox.com/catalog/3033910400/International-Fedora-Germany
https://www.roblox.com/catalog/6470135113/Fan-Hand-Sign-Why-Dont-We-WDW
https://www.roblox.com/catalog/7548993875/Slasher
made by sandbox#8694
]]--
local HatChar = game.Players.LocalPlayer.Character
local Hat = HatChar:FindFirstChild("InternationalFedora")
local Hat2 = HatChar:FindFirstChild("WDW_FoamFinger")

Hat2.Handle.SpecialMesh:Destroy()
Hat.Handle.SpecialMesh:Destroy()




HumanDied = false
local reanim
function noplsmesh(hat)
_G.OldCF=workspace.Camera.CFrame
oldchar=game.Players.LocalPlayer.Character
game.Players.LocalPlayer.Character=workspace[game.Players.LocalPlayer.Name]
for i,v in next, workspace[game.Players.LocalPlayer.Name][hat]:GetDescendants() do
if v:IsA('Mesh') or v:IsA('SpecialMesh') then
v:Remove()
end
end
game.Players.LocalPlayer.Character=oldchar
wait()
workspace.Camera.CFrame=_G.OldCF
game.Players.LocalPlayer.Character=oldchar
end
_G.ClickFling=false -- Set this to true if u want.
loadstring(game:HttpGet(('https://raw.githubusercontent.com/XeneonPlays/Nexo/main/NexoPD'),true))()

IT = Instance.new
CF = CFrame.new
VT = Vector3.new
RAD = math.rad
C3 = Color3.new
UD2 = UDim2.new
BRICKC = BrickColor.new
ANGLES = CFrame.Angles
EULER = CFrame.fromEulerAnglesXYZ
COS = math.cos
ACOS = math.acos
SIN = math.sin
ASIN = math.asin
ABS = math.abs
MRANDOM = math.random
FLOOR = math.floor

speed = 1
sine = 1
srv = game:GetService('RunService')

function hatset(yes,part,c1,c0,nm)
reanim[yes].Handle.AccessoryWeld.Part1=reanim[part]
reanim[yes].Handle.AccessoryWeld.C1=c1 or CFrame.new()
reanim[yes].Handle.AccessoryWeld.C0=c0 or CFrame.new()--3bbb322dad5929d0d4f25adcebf30aa5
if nm==true then
noplsmesh(yes)
end
end

--put the hat script converted below

reanim = game.Players.LocalPlayer.Character.CWExtra.NexoPD
RJ = reanim.HumanoidRootPart.RootJoint
RS = reanim.Torso['Right Shoulder']
LS = reanim.Torso['Left Shoulder']
RH = reanim.Torso['Right Hip']
LH = reanim.Torso['Left Hip']
Root = reanim.HumanoidRootPart
NECK = reanim.Torso.Neck
NECK.C0 = CF(0,1,0)*ANGLES(RAD(0),RAD(0),RAD(0))
NECK.C1 = CF(0,-0.5,0)*ANGLES(RAD(0),RAD(0),RAD(0))
RJ.C1 = CF(0,0,0)*ANGLES(RAD(0),RAD(0),RAD(0))
RJ.C0 = CF(0,0,0)*ANGLES(RAD(0),RAD(0),RAD(0))
RS.C1 = CF(-0.5,0.5,0)*ANGLES(RAD(0),RAD(0),RAD(0))
LS.C1 = CF(0.5,0.5,0)*ANGLES(RAD(0),RAD(0),RAD(0))
RH.C1 = CF(0,1,0)*ANGLES(RAD(0),RAD(0),RAD(0))
LH.C1 = CF(0,1,0)*ANGLES(RAD(0),RAD(0),RAD(0))
RH.C0 = CF(0,0,0)*ANGLES(RAD(0),RAD(0),RAD(0))
LH.C0 = CF(0,0,0)*ANGLES(RAD(0),RAD(0),RAD(0))
RS.C0 = CF(0,0,0)*ANGLES(RAD(0),RAD(0),RAD(0))
LS.C0 = CF(0,0,0)*ANGLES(RAD(0),RAD(0),RAD(0))

Mode='1'

mousechanger=game.Players.LocalPlayer:GetMouse().KeyDown:Connect(function(k)
if k == '1' then-- first mode
Mode='1'
elseif k == 'e' then-- second mode
Mode='2'
elseif k == 'urkeybind' then-- third mode
Mode='3'
end
end)



attacklol=game.Players.LocalPlayer:GetMouse().Button1Down:Connect(function()
Mode='Attack0'
wait(0.1) -- time of attack u can edit this
Mode='Attack1'
wait(0.1)
Mode='Attack3'
wait(0.4)
Mode ='2'
end)



coroutine.wrap(function()
while true do -- anim changer
if HumanDied then mousechanger:Disconnect() attacklol:Disconnect() break end
sine = sine + speed
local rlegray = Ray.new(reanim["Right Leg"].Position + Vector3.new(0, 0.5, 0), Vector3.new(0, -2, 0))
local rlegpart, rlegendPoint = workspace:FindPartOnRay(rlegray, char)
local llegray = Ray.new(reanim["Left Leg"].Position + Vector3.new(0, 0.5, 0), Vector3.new(0, -2, 0))
local llegpart, llegendPoint = workspace:FindPartOnRay(llegray, char)
local rightvector = (Root.Velocity * Root.CFrame.rightVector).X + (Root.Velocity * Root.CFrame.rightVector).Z
local lookvector = (Root.Velocity * Root.CFrame.lookVector).X + (Root.Velocity * Root.CFrame.lookVector).Z
if lookvector > reanim.Humanoid.WalkSpeed then
lookvector = reanim.Humanoid.WalkSpeed
end
if lookvector < -reanim.Humanoid.WalkSpeed then
lookvector = -reanim.Humanoid.WalkSpeed
end
if rightvector > reanim.Humanoid.WalkSpeed then
rightvector = reanim.Humanoid.WalkSpeed
end
if rightvector < -reanim.Humanoid.WalkSpeed then
rightvector = -reanim.Humanoid.WalkSpeed
end
local lookvel = lookvector / reanim.Humanoid.WalkSpeed
local rightvel = rightvector / reanim.Humanoid.WalkSpeed
if Mode == '1' then
if Root.Velocity.y > 1 then -- jump
--jump clerp here
elseif Root.Velocity.y < -1 then -- fall
--fall clerp here
elseif Root.Velocity.Magnitude < 2 then -- idle
hatset('WDW_FoamFinger','Torso',CFrame.new(),reanim['WDW_FoamFinger'].Handle.AccessoryWeld.C0:Lerp(CF(0+0*math.cos(sine/13),0.8+0*math.cos(sine/13),-0.8+0*math.cos(sine/13))*ANGLES(RAD(20+5*math.cos(sine/13)),RAD(0+10*math.cos(sine/13)),RAD(0+10*math.cos(sine/13))),1),false)
NECK.C0 = NECK.C0:Lerp(CF(0+0*math.cos(sine/13),1+0*math.cos(sine/13),0+0*math.cos(sine/13))*ANGLES(RAD(0+0*math.cos(sine/13)),RAD(0+0*math.cos(sine/13)),RAD(0+0*math.cos(sine/13))),.3)
RJ.C0 = RJ.C0:Lerp(CF(0+0*math.cos(sine/90),-0.1+0.1*math.cos(sine/90),0+0*math.cos(sine/90))*ANGLES(RAD(10+-3*math.cos(sine/90)),RAD(0+0*math.cos(sine/90)),RAD(0+0*math.cos(sine/90))),.3)
RS.C0 = RS.C0:Lerp(CF(1+0*math.cos(sine/30),0+-0.2*math.cos(sine/30),0+0*math.cos(sine/30))*ANGLES(RAD(200+0*math.cos(sine/30)),RAD(20+0*math.cos(sine/30)),RAD(0+0*math.cos(sine/30))),.3)
LS.C0 = LS.C0:Lerp(CF(-1+0*math.cos(sine/30),0.5+-0.2*math.cos(sine/30),0+0*math.cos(sine/30))*ANGLES(RAD(13+0*math.cos(sine/30)),RAD(49+0*math.cos(sine/30)),RAD(4+0*math.cos(sine/30))),.3)
RH.C0 = RH.C0:Lerp(CF(0.7+0*math.cos(sine/40),-1+0.006*math.cos(sine/40),-0.5+0*math.cos(sine/40))*ANGLES(RAD(-10+0*math.cos(sine/40)),RAD(-45+0*math.cos(sine/40)),RAD(0+0*math.cos(sine/40))),.3)
LH.C0 = LH.C0:Lerp(CF(-0.7+0*math.cos(sine/40),-1+0.06*math.cos(sine/40),-0.5+0*math.cos(sine/40))*ANGLES(RAD(-10+0*math.cos(sine/40)),RAD(45+0*math.cos(sine/40)),RAD(0+0*math.cos(sine/40))),.3)
hatset('InternationalFedora','Left Arm',CFrame.new(),reanim['InternationalFedora'].Handle.AccessoryWeld.C0:Lerp(CF(0+0*math.cos(sine/13),0.7+0*math.cos(sine/13),0+0*math.cos(sine/13))*ANGLES(RAD(0+0*math.cos(sine/13)),RAD(0+0*math.cos(sine/13)),RAD(0+0*math.cos(sine/13))),1),false)
hatset('Back_AccAccessory','Right Arm',CFrame.new(),reanim['Back_AccAccessory'].Handle.AccessoryWeld.C0:Lerp(CF(0+0*math.cos(sine/13),2+0*math.cos(sine/13),-0+0*math.cos(sine/13))*ANGLES(RAD(-27+0*math.cos(sine/13)),RAD(20+0*math.cos(sine/13)),RAD(57+0*math.cos(sine/13))),1),false)
elseif Root.Velocity.Magnitude < 20 then -- walk
hatset('WDW_FoamFinger','Torso',CFrame.new(),reanim['WDW_FoamFinger'].Handle.AccessoryWeld.C0:Lerp(CF(0+0*math.cos(sine/13),0.8+0*math.cos(sine/13),-0.8+0*math.cos(sine/13))*ANGLES(RAD(20+5*math.cos(sine/13)),RAD(0+10*math.cos(sine/13)),RAD(0+10*math.cos(sine/13))),1),false)
hatset('InternationalFedora','Left Arm',CFrame.new(),reanim['InternationalFedora'].Handle.AccessoryWeld.C0:Lerp(CF(0+0*math.cos(sine/13),0.7+0*math.cos(sine/13),0+0*math.cos(sine/13))*ANGLES(RAD(0+0*math.cos(sine/13)),RAD(0+0*math.cos(sine/13)),RAD(0+0*math.cos(sine/13))),1),false)
hatset('Back_AccAccessory','Right Arm',CFrame.new(),reanim['Back_AccAccessory'].Handle.AccessoryWeld.C0:Lerp(CF(0+0*math.cos(sine/13),2+0*math.cos(sine/13),-0+0*math.cos(sine/13))*ANGLES(RAD(-27+0*math.cos(sine/13)),RAD(20+0*math.cos(sine/13)),RAD(57+0*math.cos(sine/13))),1),false)
NECK.C0 = NECK.C0:Lerp(CF(0+0*math.cos(sine/13),1+0*math.cos(sine/13),0+0*math.cos(sine/13))*ANGLES(RAD(0+0*math.cos(sine/13)),RAD(0+0*math.cos(sine/13)),RAD(0+0*math.cos(sine/13))),.3)
RJ.C0 = RJ.C0:Lerp(CF(0+0*math.cos(sine/90),-0.1+0.1*math.cos(sine/90),0+0*math.cos(sine/90))*ANGLES(RAD(10+-3*math.cos(sine/90)),RAD(0+0*math.cos(sine/90)),RAD(0+0*math.cos(sine/90))),.3)
RS.C0 = RS.C0:Lerp(CF(1+0*math.cos(sine/30),0+-0.2*math.cos(sine/30),0+0*math.cos(sine/30))*ANGLES(RAD(200+0*math.cos(sine/30)),RAD(20+0*math.cos(sine/30)),RAD(0+0*math.cos(sine/30))),.3)
LS.C0 = LS.C0:Lerp(CF(-1+0*math.cos(sine/30),0.5+-0.2*math.cos(sine/30),0+0*math.cos(sine/30))*ANGLES(RAD(13+0*math.cos(sine/30)),RAD(49+0*math.cos(sine/30)),RAD(4+0*math.cos(sine/30))),.3)
RH.C0 = RH.C0:Lerp(CF(0.5+0*math.cos(sine/13),-1+0.006*math.cos(sine/13),0+-0.5*math.cos(sine/13))*ANGLES(RAD(-10+35*math.cos(sine/13)),RAD(0+0*math.cos(sine/13)),RAD(0+0*math.cos(sine/13))),.3)
LH.C0 = LH.C0:Lerp(CF(-0.5+0*math.cos(sine/13),-1+0.06*math.cos(sine/13),0+0.5*math.cos(sine/13))*ANGLES(RAD(-10+-35*math.cos(sine/13)),RAD(0+0*math.cos(sine/13)),RAD(0+0*math.cos(sine/13))),.3)
elseif Root.Velocity.Magnitude > 20 then -- run
--run clerp here
end
elseif Mode == '2' then
if Root.Velocity.y > 1 then -- jump
--jump clerp here
elseif Root.Velocity.y < -1 then -- fall
--fall clerp here
elseif Root.Velocity.Magnitude < 2 then -- idle
hatset('WDW_FoamFinger','Torso',CFrame.new(),reanim['WDW_FoamFinger'].Handle.AccessoryWeld.C0:Lerp(CF(0+0*math.cos(sine/13),0.8+0*math.cos(sine/13),-0.8+0*math.cos(sine/13))*ANGLES(RAD(20+5*math.cos(sine/13)),RAD(0+10*math.cos(sine/13)),RAD(0+10*math.cos(sine/13))),1),false)
NECK.C0 = NECK.C0:Lerp(CF(0+0*math.cos(sine/13),1+0*math.cos(sine/13),0+0*math.cos(sine/13))*ANGLES(RAD(0+0*math.cos(sine/13)),RAD(0+0*math.cos(sine/13)),RAD(0+0*math.cos(sine/13))),.3)
RJ.C0 = RJ.C0:Lerp(CF(0+0*math.cos(sine/15),-0.6+0.05*math.cos(sine/15),0+0*math.cos(sine/15))*ANGLES(RAD(-45+0*math.cos(sine/15)),RAD(0+0*math.cos(sine/15)),RAD(0+0*math.cos(sine/15))),.3)
RS.C0 = RS.C0:Lerp(CF(1+0*math.cos(sine/30),0+0.1*math.cos(sine/30),-0.5+0*math.cos(sine/30))*ANGLES(RAD(145+0*math.cos(sine/30)),RAD(0+0*math.cos(sine/30)),RAD(0+0*math.cos(sine/30))),.3)
LS.C0 = LS.C0:Lerp(CF(-1+0*math.cos(sine/13),0+0*math.cos(sine/13),-1+0*math.cos(sine/13))*ANGLES(RAD(45+0*math.cos(sine/13)),RAD(-5+0*math.cos(sine/13)),RAD(4+0*math.cos(sine/13))),.3)
RH.C0 = RH.C0:Lerp(CF(1+0*math.cos(sine/13),-1+0.05*math.cos(sine/13),0+0*math.cos(sine/13))*ANGLES(RAD(44+0*math.cos(sine/13)),RAD(69+0*math.cos(sine/13)),RAD(-36+0*math.cos(sine/13))),.3)
LH.C0 = LH.C0:Lerp(CF(-1+0*math.cos(sine/13),-1+0.05*math.cos(sine/13),0+0*math.cos(sine/13))*ANGLES(RAD(64+0*math.cos(sine/13)),RAD(131+0*math.cos(sine/13)),RAD(-25+0*math.cos(sine/13))),.3)
hatset('Back_AccAccessory','Right Arm',CFrame.new(),reanim['Back_AccAccessory'].Handle.AccessoryWeld.C0:Lerp(CF(0+0*math.cos(sine/13),1.6+0*math.cos(sine/13),0+0*math.cos(sine/13))*ANGLES(RAD(-90+0*math.cos(sine/13)),RAD(-3+0*math.cos(sine/13)),RAD(90+0*math.cos(sine/13))),1),false)
elseif Root.Velocity.Magnitude < 20 then -- walk
hatset('WDW_FoamFinger','Torso',CFrame.new(),reanim['WDW_FoamFinger'].Handle.AccessoryWeld.C0:Lerp(CF(0+0*math.cos(sine/13),0.8+0*math.cos(sine/13),-0.8+0*math.cos(sine/13))*ANGLES(RAD(20+5*math.cos(sine/13)),RAD(0+10*math.cos(sine/13)),RAD(0+10*math.cos(sine/13))),1),false)
NECK.C0 = NECK.C0:Lerp(CF(0+0*math.cos(sine/13),1+0*math.cos(sine/13),0+0*math.cos(sine/13))*ANGLES(RAD(0+0*math.cos(sine/13)),RAD(0+0*math.cos(sine/13)),RAD(0+0*math.cos(sine/13))),.3)
RJ.C0 = RJ.C0:Lerp(CF(0+0*math.cos(sine/13),0+0*math.cos(sine/13),0+0*math.cos(sine/13))*ANGLES(RAD(-10+0*math.cos(sine/13)),RAD(0+0*math.cos(sine/13)),RAD(0+0*math.cos(sine/13))),.3)
RS.C0 = RS.C0:Lerp(CF(1+0*math.cos(sine/13),0.3+0*math.cos(sine/13),0+0*math.cos(sine/13))*ANGLES(RAD(0+0*math.cos(sine/13)),RAD(-45+5*math.cos(sine/13)),RAD(45+0*math.cos(sine/13))),.3)
LS.C0 = LS.C0:Lerp(CF(-1+0*math.cos(sine/13),0.5+0*math.cos(sine/13),0+0*math.cos(sine/13))*ANGLES(RAD(0+-35*math.cos(sine/13)),RAD(0+0*math.cos(sine/13)),RAD(0+0*math.cos(sine/13))),.3)
RH.C0 = RH.C0:Lerp(CF(0.5+0*math.cos(sine/13),-1+0*math.cos(sine/13),0+0.3*math.cos(sine/13))*ANGLES(RAD(0+-35*math.cos(sine/13)),RAD(0+0*math.cos(sine/13)),RAD(0+0*math.cos(sine/13))),.3)
LH.C0 = LH.C0:Lerp(CF(-0.5+0*math.cos(sine/13),-1+0*math.cos(sine/13),0+-0.3*math.cos(sine/13))*ANGLES(RAD(0+35*math.cos(sine/13)),RAD(0+0*math.cos(sine/13)),RAD(0+0*math.cos(sine/13))),.3)
hatset('Back_AccAccessory','Right Arm',CFrame.new(),reanim['Back_AccAccessory'].Handle.AccessoryWeld.C0:Lerp(CF(0.3+0*math.cos(sine/13),1.9+0*math.cos(sine/13),0+0*math.cos(sine/13))*ANGLES(RAD(127+0*math.cos(sine/13)),RAD(134+0*math.cos(sine/13)),RAD(236+0*math.cos(sine/13))),1),false)
elseif Root.Velocity.Magnitude > 20 then -- run
--run clerp here
end
elseif Mode == '3' then
if Root.Velocity.y > 1 then -- jump
--jump clerp here
elseif Root.Velocity.y < -1 then -- fall
--fall clerp here
elseif Root.Velocity.Magnitude < 2 then -- idle
--idle clerp here
elseif Root.Velocity.Magnitude < 20 then -- walk
--walk clerp here
elseif Root.Velocity.Magnitude > 20 then -- run
--run clerp here
end
elseif Mode == 'Attack0' then
NECK.C0 = NECK.C0:Lerp(CF(0+0*math.cos(sine/13),1+0*math.cos(sine/13),0+0*math.cos(sine/13))*ANGLES(RAD(0+0*math.cos(sine/13)),RAD(35+0*math.cos(sine/13)),RAD(0+0*math.cos(sine/13))),.3)
RJ.C0 = RJ.C0:Lerp(CF(0+0*math.cos(sine/13),0+0*math.cos(sine/13),0+0*math.cos(sine/13))*ANGLES(RAD(-10+0*math.cos(sine/13)),RAD(-50+0*math.cos(sine/13)),RAD(0+0*math.cos(sine/13))),.3)
RS.C0 = RS.C0:Lerp(CF(1+0*math.cos(sine/13),0.5+0*math.cos(sine/13),-0.5+0*math.cos(sine/13))*ANGLES(RAD(-163+0*math.cos(sine/13)),RAD(0+0*math.cos(sine/13)),RAD(0+0*math.cos(sine/13))),.3)
LS.C0 = LS.C0:Lerp(CF(-1+0*math.cos(sine/13),0.5+0*math.cos(sine/13),0+0*math.cos(sine/13))*ANGLES(RAD(9+0*math.cos(sine/13)),RAD(42+0*math.cos(sine/13)),RAD(0+0*math.cos(sine/13))),.3)
RH.C0 = RH.C0:Lerp(CF(0.5+0*math.cos(sine/13),-1.2+0*math.cos(sine/13),0+0*math.cos(sine/13))*ANGLES(RAD(-2+0*math.cos(sine/13)),RAD(-143+0*math.cos(sine/13)),RAD(-13+0*math.cos(sine/13))),.3)
LH.C0 = LH.C0:Lerp(CF(-0.7+0*math.cos(sine/13),-1+0*math.cos(sine/13),-0.2+0*math.cos(sine/13))*ANGLES(RAD(0+0*math.cos(sine/13)),RAD(51+0*math.cos(sine/13)),RAD(0+0*math.cos(sine/13))),.3)
hatset('Back_AccAccessory','Right Arm',CFrame.new(),reanim['Back_AccAccessory'].Handle.AccessoryWeld.C0:Lerp(CF(0.5+0*math.cos(sine/13),2+0*math.cos(sine/13),-0.4+0*math.cos(sine/13))*ANGLES(RAD(45+0*math.cos(sine/13)),RAD(-214+0*math.cos(sine/13)),RAD(-74+0*math.cos(sine/13))),1),false)
elseif Mode == 'Attack1' then
NECK.C0 = NECK.C0:Lerp(CF(0+0*math.cos(sine/13),1+0*math.cos(sine/13),0+0*math.cos(sine/13))*ANGLES(RAD(0+0*math.cos(sine/13)),RAD(35+0*math.cos(sine/13)),RAD(0+0*math.cos(sine/13))),.3)
RJ.C0 = RJ.C0:Lerp(CF(0+0*math.cos(sine/13),0+0*math.cos(sine/13),0+0*math.cos(sine/13))*ANGLES(RAD(-10+0*math.cos(sine/13)),RAD(-50+0*math.cos(sine/13)),RAD(0+0*math.cos(sine/13))),.3)
RS.C0 = RS.C0:Lerp(CF(0.5+0*math.cos(sine/13),0.8+0*math.cos(sine/13),-0.8+0*math.cos(sine/13))*ANGLES(RAD(-272+0*math.cos(sine/13)),RAD(45+0*math.cos(sine/13)),RAD(-69+0*math.cos(sine/13))),.3)
LS.C0 = LS.C0:Lerp(CF(-1+0*math.cos(sine/13),0.5+0*math.cos(sine/13),0+0*math.cos(sine/13))*ANGLES(RAD(9+0*math.cos(sine/13)),RAD(74+0*math.cos(sine/13)),RAD(-9+0*math.cos(sine/13))),.3)
RH.C0 = RH.C0:Lerp(CF(0.5+0*math.cos(sine/13),-1.2+0*math.cos(sine/13),0+0*math.cos(sine/13))*ANGLES(RAD(-2+0*math.cos(sine/13)),RAD(-143+0*math.cos(sine/13)),RAD(-13+0*math.cos(sine/13))),.3)
LH.C0 = LH.C0:Lerp(CF(-0.7+0*math.cos(sine/13),-1+0*math.cos(sine/13),-0.2+0*math.cos(sine/13))*ANGLES(RAD(0+0*math.cos(sine/13)),RAD(51+0*math.cos(sine/13)),RAD(0+0*math.cos(sine/13))),.3)
hatset('Back_AccAccessory','Right Arm',CFrame.new(),reanim['Back_AccAccessory'].Handle.AccessoryWeld.C0:Lerp(CF(0.5+0*math.cos(sine/13),2+0*math.cos(sine/13),-0.4+0*math.cos(sine/13))*ANGLES(RAD(36+0*math.cos(sine/13)),RAD(-225+0*math.cos(sine/13)),RAD(-58+0*math.cos(sine/13))),1),false)
elseif Mode == 'Attack3' then
NECK.C0 = NECK.C0:Lerp(CF(0+0*math.cos(sine/13),1+0*math.cos(sine/13),0+0*math.cos(sine/13))*ANGLES(RAD(0+0*math.cos(sine/13)),RAD(-35+0*math.cos(sine/13)),RAD(0+0*math.cos(sine/13))),.3)
RJ.C0 = RJ.C0:Lerp(CF(0+0*math.cos(sine/13),0+0*math.cos(sine/13),0+0*math.cos(sine/13))*ANGLES(RAD(-10+0*math.cos(sine/13)),RAD(50+0*math.cos(sine/13)),RAD(0+0*math.cos(sine/13))),.3)
RS.C0 = RS.C0:Lerp(CF(1+0*math.cos(sine/13),0.+0*math.cos(sine/13),-1+0*math.cos(sine/13))*ANGLES(RAD(-7+0*math.cos(sine/13)),RAD(0+0*math.cos(sine/13)),RAD(0+0*math.cos(sine/13))),.3)
LS.C0 = LS.C0:Lerp(CF(-1.5+0*math.cos(sine/13),0.5+0*math.cos(sine/13),0+0*math.cos(sine/13))*ANGLES(RAD(25+0*math.cos(sine/13)),RAD(22+0*math.cos(sine/13)),RAD(0+0*math.cos(sine/13))),.3)
RH.C0 = RH.C0:Lerp(CF(0.5+0*math.cos(sine/13),-1.2+0*math.cos(sine/13),0+0*math.cos(sine/13))*ANGLES(RAD(-2+0*math.cos(sine/13)),RAD(-143+0*math.cos(sine/13)),RAD(-13+0*math.cos(sine/13))),.3)
LH.C0 = LH.C0:Lerp(CF(-0.7+0*math.cos(sine/13),-1+0*math.cos(sine/13),-0.2+0*math.cos(sine/13))*ANGLES(RAD(0+0*math.cos(sine/13)),RAD(51+0*math.cos(sine/13)),RAD(0+0*math.cos(sine/13))),.3)
hatset('Back_AccAccessory','Right Arm',CFrame.new(),reanim['Back_AccAccessory'].Handle.AccessoryWeld.C0:Lerp(CF(0.5+0*math.cos(sine/13),2+0*math.cos(sine/13),-0.4+0*math.cos(sine/13))*ANGLES(RAD(36+0*math.cos(sine/13)),RAD(-225+0*math.cos(sine/13)),RAD(-58+0*math.cos(sine/13))),1),false)
end
srv.RenderStepped:Wait()
end
end)()
--Created using Nexo Animator
