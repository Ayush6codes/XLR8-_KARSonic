# XLR8_KARSonic
Our team KARSonic's XLR8 Journey
# What makes our bot different
Our bot has a special feature we coded in the Raspberry Pi Pico W. First, it should be noted that we have used the differential drive. The bot can take two types of turns: <br/>1) Having some turn radius and moving while turning (basically like an Axle Drive) and 
<br/>2) Having 0 turn radius. 
<br/> We named the 1st as - "Small Turn" and the 2nd as - "Large Turn". The trigger for both is effortless. For example, if the controller is tilted right up to an angle of 70 degrees, then it will take a small right turn, while if it is tilted further than 70 degrees (up to 90) then it will take a large right turn. Same for the left. We also adjusted speeds and trigger angle (so that a small accidental tilt won't result in taking turns).
<br/><br/>
So what's the use of both types of turns ?
<br/><br/>
While taking turns on a slope, we noticed that the 2nd method of turning resulted in slipping of the bot. This was because 2 wheels moved in the reverse direction in this turning, and this caused them to slip and fall. Thus we developed the 1st method of turning, in which all the wheels move forward, but 2 of them slower (almost zero speed) than the others. Because of this method, the bot didn't slip while turning on slopes. Also, it resulted in faster turns at a few places which provided a time advantage in the competition.

PS : The code was tested just 20-30 mins before our final run :)
