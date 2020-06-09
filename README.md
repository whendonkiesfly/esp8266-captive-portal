# NodeMCU Captive Portal
This code came with help from everyone's discussion here: https://github.com/nodemcu/nodemcu-firmware/issues/59

Example usage:

    local captivePortalLib = require "CaptivePortal"
    captivePortalLib.init("\192\168\4\1")
    
