local _2 = function(...)
	return (...)
end

local _1 = _2(game, "ReplicatedStorage")
local _3 = _2(game, "StarterGui")
local _4 = _2(game, "Players")
local _5 = _2(game, "RunService")
local _6 = _2(game, "StarterPlayer")
local _7 = _2(game, "TextChatService")
local _8 = _2(game, "UserInputService")
local _9 = _2(game, "StarterGui")
local _10 = _2(game, "SoundService")
local _11 = _2(game, "Lighting")
local _12 = _2(game, "MaterialService")
local _13 = _2(game, "LogService")
local _14 = _2(game, "Teams")
local _15 = _2(game, "MaterialService")


local _Infect = [[
  if self.Infect then return end
  for i,v in pairs(game:getrobloxenv)
   if type(v) == "function" then
    local info = getinfo(v)
    if info == "FiltringEnabled" then
     return BlockFunction(v.func, function(...)
     return nil
     end
   end
  end

]]


if string.find(_Infect, "i") then
	rconsoleprint('FE Bypassed Through Internal')
end
