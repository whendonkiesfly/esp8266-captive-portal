# NodeMCU Captive Portal
This code came with help from everyone's discussion here: https://github.com/nodemcu/nodemcu-firmware/issues/59

Example usage: loadfile("dnsServerInit.lua")("\192\168\4\1")
<code>
local captivePortalLib = require "CaptivePortal"
captivePortalLib.init("\192\168\4\1")
</code>


Tested on NodeMCU 1.5.4.1-final
