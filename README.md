# Anti-roblox-package-script-for-games

This script bans all packages, I recommend using R6 for the game in game avatar settings. (this is also a basic script!)


 ------------------------------------------------------
 
 while true do
wait()
c=game.Workspace:getChildren()
for i = 1, #c do
cc=c[i]:getChildren()
for ii=1, #cc do
if cc[ii].className=="CharacterMesh" then
cc[ii]:Remove()
end
end
end
end

 ------------------------------------------------------
