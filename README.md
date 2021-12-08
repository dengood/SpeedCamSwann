# SpeedCamSwann

For what I lack in forsight in terms of purchasing a family home in a nice peaceful neighborhood I make for in pettiness.  Well pettiness, maybe not.  I like to think there is good reason for speed limits and that reason must in some way be related to safety of the general public.  Thankfully we live in Texas and there are no speedlimits in Texas.  According to dallasattorney.com you are speeding if your rate of speed is “unreasonable and imprudent under the circumstances then existing.”  Now I cannot attest to how many speeding tickets have been successfully dismissed based on the statutes as they exist under Texas law but for all those that confidently exchange reasonable courtesy for the letter of the law may you be emboldened.  

I chose poorly.  Anytime you place your satisfaction, mood, happiness, state of existence in the hands of the general public even down to those people that you share an immediate community with you must without any agonizing accept disappointment.  You must accept that people are going to only consider themselves in their actions.  When it comes to living in a neighborhood where people operate their vehicles at a responsible speed your mileage may vary.  If you are on a street that is in a neighborhood where there are few points of access the closer you are to the entrance and main artery of the neighborhood the higher speeds you will be subjected to.  With drivers as they are today there will be a number of those drivers driving at high speeds that are not so subtly staring at their laps.  Seems hazardous. 

So what of this project.  What is the point?  In an attempt to make peace with my poor decisions while similataneously not trying to increase my cynacism of human behavior I wanted to better understand the scope of those making the neighborhood a less pleasant place by their driving behavior.  Sure we can look around our neighborhood and be agitated by those that don't take care of their homes or by those that let their pets take a dump anywhere they please but this is a source of agitation that all can participate in with documented proof of the behavior.  

I borrow heavily and almost completely from Greg Tinkers project which can found here:  https://gregtinkers.wordpress.com/2016/03/25/car-speed-detector/

Greg's project was based on a RaspPi but setting up the RaspPi and weather proofing it and all this was too much effort.  I already had a Swann security system with hi-res PTZ camera but somehow didn't connect that it was RTSP capable.  I adapted the code to leverage the RTSP of the Swann NVR.  Next I don't like to have computers on all the time but leveraged my Synology NAS and its docker capability to run the Speed Camera python script continuously.  I set the script to only store pictures of those individuals that are doing in excess of 30 mph.  The posted speedlimit in our neighborhood is 25mph.  


No speed limits in Texas:
https://dallasattorney.com/blog/no-speed-limits-in-texas/
