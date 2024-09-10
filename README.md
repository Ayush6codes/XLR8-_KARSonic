# XLR8_KARSonic
Our team KARSonic's XLR8 Journey was very wonderful. We started working on our designs and strategies from the first day of the registrations itself. Then our mentor told us about a team that had included suspensions in their bot for last year's XLR8. We also thought of making a suspension system and worked on it for almost a week, trying different mechanisms, trying to stabilize the whole system, and effectively controlling the bot. Unfortunately, we couldn't make an effective suspension system before the final run, so we have kept that idea for later ;). Also, at first, we thought of using 300 rpm motors, but at 5:30 am on the day of the first run (and after pulling an all-nighter) we found that our bot couldn't go up an incline. So, we woke up at 8:30 am and ran to the stationery shop to buy 200 rpm motors. Our final model was completed at 9:30 am. Sadly, our bot couldn't run on the slopes of the main obstacle course and we had to skip many obstacles. We completed the first run in around 12 mins. We were utterly disappointed but not discouraged, we decided to give our best in the 2nd try. Then, we changed our wheels to 7X4 (we had used 10X4 in the first run), massively cut the weight of the bot, and lowered its height. We tested various codes on the day of the 2nd run and the final one was tested around 20 mins before the run, which helped turn in the slopes and gave us a massive time advantage. We completed the 2nd run in 4 mins 33s skipping only 1 obstacle. We learned more in that one day than in the one week we had been working on the bot.<br/>
Overall, it was a very nice experience, learning Mechanical, Electrical, and Coding aspects to a great depth and making a very innovative thing on our own.


# What makes our bot different
Our bot has a special feature we coded in the Raspberry Pi Pico W. First, it should be noted that we have used the differential drive. <br/>The bot can take two types of turns: <br/>1) Having some turn radius and moving while turning (basically like an Axle Drive) and 
<br/>2) Having 0 turn radius. 
<br/> We named the 1st as - "Small Turn" and the 2nd as - "Large Turn". The trigger for both is effortless. For example, if the controller is tilted right up to an angle of 70 degrees, then it will take a small right turn, while if it is tilted further than 70 degrees (up to 90) then it will take a large right turn. Same for the left. We also adjusted speeds and trigger angle (so that a small accidental tilt won't result in taking turns).
<br/><br/>
So what's the use of both types of turns ?
<br/><br/>
While taking turns on a slope, we noticed that the 2nd method of turning resulted in slipping of the bot. This was because 2 wheels moved in the reverse direction in this turning, and this caused them to slip and fall. Thus we developed the 1st method of turning, in which all the wheels move forward, but 2 of them slower (almost zero speed) than the others. Because of this method, the bot didn't slip while turning on slopes. Also, it resulted in faster turns at a few places which provided a time advantage in the competition.

PS: The code was tested just 20-30 mins before our final run :)

# Help from our Mentor

Our mentor (Aditya Anmol) helped us a lot. He cleared all our doubts regarding the controller, circuits, etc. He also suggested and encouraged us in trying a suspension mechanism for our bot. He helped us troubleshoot issues regarding our bot.
