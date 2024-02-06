Basic Node-Red Flow example showing how to query Disguise API and trigger an LED light in the dashboard to show its status.

Functions that query to Service API for Machine status
If the LED is Green = Disguise Machine is "ready" If the LED is Red = Disguise Status is "offline"

If Disguise software is running it then checks the session API and report back 
red (offline) 
green (running) 
amber (warning) - if session has failed over or machine is in a warning state
grey leds (inactive) - API is not running as d3 manager is not running


![node-red](https://github.com/infocusav/Node-Red-Disguise-API/assets/114356063/2c966d78-908c-4e11-a587-25515d183ad5)
