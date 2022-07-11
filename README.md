local tangerex = loadstring(game:HttpGet("https://5f4d3288-7026-4802-bb67-917a76b5e7d8.id.repl.co/Tangerex/Template/main.lua"))()

reanimate = tangerex:Reanimate("PD",false --[[Usage: true or false to toggle click fling]]) -- SP / Simple, LF / Leg Fling, TF / Torso Fling, PD / Perma Death [Fling]

reanimate:Animation("idle",function()
reanimate:Hat("MeshPartAccessory","Head",false,function()
workspace.Camera.CameraSubject.Parent["MeshPartAccessory"].Handle.AccessoryWeld.C0=workspace.Camera.CameraSubject.Parent["MeshPartAccessory"].Handle.AccessoryWeld.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),0.5+1.3*math.cos(sine/10),1.8+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),0.5)
end)
RH.Part0 = workspace.Camera.CameraSubject.Parent.Torso
LH.Part0 = workspace.Camera.CameraSubject.Parent.Torso
NECK.C0=NECK.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),0.5) 
RJ.C0=RJ.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),-1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),0.5) 
RS.C0=RS.C0:Lerp(CFrame.new(1.2+0*math.cos(sine/10),0.5+0*math.cos(sine/10),-0.8+0*math.cos(sine/10))*CFrame.Angles(math.rad(73.3+-36.3*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(-48.2+0*math.cos(sine/10))),0.5) 
LS.C0=LS.C0:Lerp(CFrame.new(-1.2+0*math.cos(sine/10),0.5+0*math.cos(sine/10),-0.8+0*math.cos(sine/10))*CFrame.Angles(math.rad(73.3+-36.3*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(48.2+0*math.cos(sine/10))),0.5) 
RH.C0=RH.C0:Lerp(CFrame.new(0.5+0*math.cos(sine/10),-1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),0.5) 
LH.C0=LH.C0:Lerp(CFrame.new(-0.5+0*math.cos(sine/10),-1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),0.5)
end)

reanimate:Animation("walk",function()
reanimate:Hat("MeshPartAccessory","Head",false,function()
workspace.Camera.CameraSubject.Parent["MeshPartAccessory"].Handle.AccessoryWeld.C0=workspace.Camera.CameraSubject.Parent["MeshPartAccessory"].Handle.AccessoryWeld.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),0+0*math.cos(sine/10),1.5+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),0.5)
end)
RH.Part0 = workspace.Camera.CameraSubject.Parent.Torso
LH.Part0 = workspace.Camera.CameraSubject.Parent.Torso
NECK.C0=NECK.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),0.5) 
RJ.C0=RJ.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),-1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),0.5) 
RS.C0=RS.C0:Lerp(CFrame.new(1.5+0*math.cos(sine/10),0.5+0*math.cos(sine/10),-0.5+0*math.cos(sine/10))*CFrame.Angles(math.rad(98.3+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(-42+0*math.cos(sine/10))),0.5) 
LS.C0=LS.C0:Lerp(CFrame.new(-1.5+0*math.cos(sine/10),0.5+0*math.cos(sine/10),-0.5+0*math.cos(sine/10))*CFrame.Angles(math.rad(98.3+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(42+0*math.cos(sine/10))),0.5) 
RH.C0=RH.C0:Lerp(CFrame.new(0.5+0*math.cos(sine/10),-1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+-16.9*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),0.5) 
LH.C0=LH.C0:Lerp(CFrame.new(-0.5+0*math.cos(sine/10),-1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+16.9*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),0.5)
end)

reanimate:Animation("run",function()
--runlerphere
end)

reanimate:Animation("jump",function()
--jumplerphere
end)

reanimate:Animation("fall",function()
--falllerphere
end)

-- Read the documentation for modes/attacks/keybinds/clickbinds
