# summerbot-debug
A configuration interface for the summerbot
## Commands
### to bot
 - AYR command asked to the device to wait for the end of it's boot
 - WHOIS command asked to know the device name
 - +POS command asking for a continuous stream of POS commands
 - -POS
 - SPOS X Y A command setting the position of the bot
 - GOTO X Y A command moving the robot to specific location
 - GSIDE command asking for robot side
 - SSIDE S command setting robot side
 - GSTRAT command asking for the strat ID
 - CSTRAT command asking to switch to another strat
 - CHECK PART command asking to run a self test
 - TRANS D command translating the robot
 - ROT A command rotating the robot

### from bot
 - POS X Y Z current pos of the robot
 - READY response to AYR
 - IAM NAME response to WHOIS
 - SIDE S side of the robot can be sent unprompted or in response to GSIDE
 - STRAT S strat of the robot can be sent unprompted or in response to GSTRAT and CSTRAT
 - CHECK DATA DATA DATA ... results of the selftest routine 
