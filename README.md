<img src="https://raw.githubusercontent.com/silvergravel/mobile_angels/master/logoAngels.jpg" width="25%">
# Mobile Angels
**The Sbb Travel Assistant**
###### Team: 
Graham Tritt, Ahmed Alhammadi, Almerey Karwan, Abrar Burk
<br>
<br>
## Project Challenge:
Build on the existing services and data provided by SBB, to simplify the travel experience of the elderly.

SBB open data portal: http://data.sbb.ch/explore/?sort=modified
It provides access to SBB train timings, refreshments and other ammenities on train stations, and a lot more.
<br>
<br>
![alt tag](https://raw.githubusercontent.com/silvergravel/mobile_angels/master/SBBdata.jpg)
<br>
<br>

## The Problem:
**Train Travel can be overwhelming for the elderly.** <br>Keeping track of connecting train numbers, correct boarding platforms, transfer times, etc can lead to confusion, sometimes resulting in unfortunate situations.
<br>
<br>
![alt tag](https://raw.githubusercontent.com/silvergravel/mobile_angels/master/schedule.jpg)
<br>
<br>

**Technological Fears.** <br>General resistance towards using phone applications, sometimes even smartphones, reduces the possibilities of using new technological solutions to address this problem. 
<br>
<br>

![alt tag](https://raw.githubusercontent.com/silvergravel/mobile_angels/master/techFear.jpg)
<br>
<br>

**Current SBB SMS service** <br>SBB already has an SMS service called 'Procom' meant to provide assistance to hearing impaired passengers. You can read more about it here: http://www.sbb.ch/en/station-services/passengers-with-reduced-mobility/hearing-impaired.html<br>
<br>
Curiosity led us to send an SMS to the provided number and see what sort of response we get. However, the response was bizzare to say the least. An outright 'Who are you?' made us feel like we had just prank texted someone who didn't take very kindly to it. Not exactly the kind of feeling one would want from an assistance service!
<br>
<br>

## Framework Definition
**Our focus:**<br>
How do you simplify SBB train schedule information such that, the elderly have a clear understanding and therefore, a frictionless journey from home to destination?
<br>
<br>


## Inspirations:
**Tourist Angels**<br>
http://www.touristangelapp.com/<br>
<img src="https://raw.githubusercontent.com/silvergravel/mobile_angels/master/touristAngels.jpg" width="50%">

**Senior Service 24**<br>
https://seniorservice24.ch/<br>
<img src="https://raw.githubusercontent.com/silvergravel/mobile_angels/master/seniorSerive.jpg" width="50%">


**Digit**<br>
https://digit.co/<br>
<img src="https://raw.githubusercontent.com/silvergravel/mobile_angels/master/digit.jpg" width="50%">
<br>
<br>


## Values 
- Independence
- Convenience
- Personalized
<br>
<br>


## Mission?
Travel Angels is an SMS based, intelligent travel assistant, that provides personalized guidance to the elderly through every stage of their SBB journey, from home till destination.
<br>
<br>


## Strategy
###### Initial Vision
- SBB could provide a yearly chat-bot subscription for people who would like constant assistance during their train journeys. 
- Subscribed members would receive SMS guidance with regards to their train timings, platform numbers, connecting train details, refreshment and other station amenities, and also assistance in stressful situations like boarding wrong trains and reaching unintended locations.
- The idea was to develop a friendly and approachable AI driven assistant, that responds to natural language of the user, thereby making the user experience extremely intuitive and comfortable considering the target user group<br>
<br>
![alt tag](https://raw.githubusercontent.com/silvergravel/mobile_angels/master/explorations.jpg)
<br>
<br>

###### The Prototype
![alt tag](https://raw.githubusercontent.com/silvergravel/mobile_angels/master/proto.jpg)
<br>
<br>

###### Tech Specs
**Hubot**<br>
https://hubot.github.com/<br>
<br>
**Slack**<br>
https://slack.com/<br>
<br>
**SBB Database**<br>
http://data.sbb.ch/explore/?sort=modified<br>
<br>
**Twilio**
https://www.twilio.com/<br>
<br>
We used the Hubot framework to develop the Bot that used the SBB train schedule API to provide relevant guidance. The initial prototype was implemented in Slack, however since SMS is the best mode of communication with our target user, the BOT can be very quickly swapped to an SMS based service using the Twilio SMS adapter: https://hubot.github.com/docs/adapters/<br>
<br>
A few tests with Twilio suggested that it is probably one of the best and cost efficent ways to deliver information on the web, through SMS.
<br>
<br>

###### Further Developments

**Automated GPS tracking to improve system intelligence**<br>
<img src="https://raw.githubusercontent.com/silvergravel/mobile_angels/master/further0.jpg" width="50%">

**Assistance for special needs**<br>
![alt tag](https://raw.githubusercontent.com/silvergravel/mobile_angels/master/further1.jpg)

**Refreshments and station services**<br>
![alt tag](https://raw.githubusercontent.com/silvergravel/mobile_angels/master/further2.jpg)

**Assistance for connecting buses and cable cars**<br>
![alt tag](https://raw.githubusercontent.com/silvergravel/mobile_angels/master/further3.jpg)
