--[[
	
	This is a VERY early tech demo of component.lua.
	Please take notice of that.
	
--]]

local module = {}

module.New = function (component)
	if script:FindFirstChild(component) then
		local componentModule = require(script[component])
		local comp = componentModule.Add("XMLSQRTCHK")
		
		return comp
	else
		error(component.." dosen't exist or hasn't been installed.")
	end
end


return module
