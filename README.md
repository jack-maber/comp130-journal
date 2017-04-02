# comp130-journal
Base repository for COMP130 research journal

[] are used to denote the sourced paper with the number corresponding to the paper in the source list.

## Section 1 - Introduction
SDV(Self Driving Vehicles) technology has come a long way since it's early beginnings in the 90's, with teams such as ARGO and Navlab demonstrating "thousands of kilometres of highway driving at speeds up to 130 kph with normal traffic" [4], and although this may sound very much like what current SDV's are capable of, the technology used was all far too large and took up most of the room in the car that could be used to possibly seat passengers,  and the route the cars took were pre-planned with "highly accurate GPS way points" so this sort of test doesn't really have any sort of practicality in the real world, and was more used to show that the technology could work. However, thanks however to the continued miniaturisation of technology and the use of new technologies such as ultra high resolution cameras that can help spot pedestrians up to 97 meters away [6], (which can far outstrip that of some road users), SDV's are now something that is available to the general public, thanks in no small part to Tesla, who in 2015 allowed it's users to utilise the experimental "Autopilot" mode [3], and as such many other companies such as Google and the car giant Toyota started to invest and develop in SDV technology, but this sudden development didn't come without it's critiques, as the normal person and academics alike started to ask, can you program a SDV to have acceptable ethics?, and who is at fault when the vehicle makes a mistake?

## Section 2 - The Problems
As with any problem, there is a good outcome and a bad outcome, but what about the problems where there is no good outcome, this kind of problem is normally shown with the age old "Trolley" Problem where "in which a trolley is threatening to collide with unsuspecting children and the only way to stop it is to throw a fat man over the side of a bridge and onto the track's switch" [1] and as humans, we'll take many factors and our own morals into making this decision, where every individual's answer will be different, where as "because computer programs take things quite literally", as paper 1 puts it, SDV's don't have the luxury of a human brain at their disposal, paper one also discusses that there have been many experiments and "substantial" literature on the subject, with paper 7 being one of them, where they ran a simulation of the "Trolley" problem and made test subjects pick an option depending on scenario, these included hitting once child, several children and their best friend, and then changed other factors such as their chance of survival, and obviously as the chance increased, they would pick to risk their life and save the other party over their own. People also seemed to pick saving children over old people by quite a surprising margin, which is something that another paper brought up, paper 2 brings up this with the situation of 2 old people and child crossing the road and the car can't dodge either, this is another moral dilemma that would the driver of a normal car would make based on their own morals and ethics, but what about an SDV? As discussed before, they can't decide on their own, so a programmer must make this decision by picking which is the option SDV will pick, so in a fatal collision, who is at fault and who will take the brunt of the aftermath?

## Section 3 - The Programmer or Driver, who is at fault?
Nearly all of the papers that I read discussed the section title in some way, paper 5 has quite an interesting view on the subject as it proposes a soloution to the problem where by the SDV learns and changse it's actions based on the inputs of the driver when it isn't "Autopilot" mode 

Paper 5, the car should learn from the human
US law would put blame onto automaker anyway














# Sources
## Paper 1: Can you program ethics into a self-driving car? Noah J. Goodall - cited
http://ieeexplore.ieee.org.ezproxy.falmouth.ac.uk/document/7473149/

Hardcoding roads laws is bad as it limits the vehicle and drivers normally will break the law to gain speed, and things such as positioning itself in a lane to avoid debree, and actively moving awawy from larger threats such as trucks to minamise risk, but transferring that risk to to other road users as they are closer to them. 

Due to the sheer amount of scenarious and problems that occur on roads, it will be  along time before each problem can be computed and taken into account.

Unfair treatment of road user as the car will avoid danger from dangerous drivers and move towards law abiding vehicles.

Would the car crash on purpose to save another person's life? 

## Paper 2:Driving the self-driving vehicle: Expanding the technological design horizon Pascale-L. Blyth - cited
http://ieeexplore.ieee.org.ezproxy.falmouth.ac.uk/document/7439419/

Much as the same as the first paper, poses the Trolly Problem.

Should it kill an old person and spare a child, but the child may be taller than the young person? 

"SDVs are revolutionary and will infiltrate society in a more pervasive, broader, and potentially disruptive sense than other automated vehicle systems"

"if a city is not technologically-outfitted for SDVs, SDVs will not be able to drive properly." Meaning all of the major cities and towns will have to be reworked for SDV's but what about regular cars?

As with all technology, the higher prices model may be safer or better equipped than the lower priced model, causing classist roads, where the lower tier may be more dangerous. "“speed hierarchy”"

## Paper 3:Self-driving cars and the law Nathan A. Greenblatt - cited
http://ieeexplore.ieee.org.ezproxy.falmouth.ac.uk/document/7419800/

"2015 lawsuit against Ford, GM, and Toyota accused the companies of “hawking vehicles that are vulnerable to hackers who could hypothetically wrest control of essential functions such as brakes and steering.” Meaning that hackers could easily turn the car into a weapon

GM's ignition-switch recall cost the company US 7 billion. For at least some autonomous-car defects, however, the recall could take the form of a software patch delivered wirelessly and inexpensively. Lowering the chance of recalls not being carried out and defects going on to cause harm. 

"THERE's A REASON to speed the rollout of autonomous vehicles. By replacing error-prone human drivers, autonomous driving technology can potentially save 30,000 lives each year in the United States alone. It can annually prevent 5 million accidents and 2 million injuries, conserve 7 billion liters of fuel, and save so many hundreds of billions of dollars in lost productivity and accident-related costs that the figures are beyond comprehension. That's because computer drivers are in principle fundamentally safer drivers. They never text, do their makeup, or fall asleep at the wheel. (Human error, in contrast, causes roughly 93 percent of crashes.) Robo-drivers can have 360-degree vision, and thanks to lidar, radar, and ultrasonic sensors, they can see through fog and in the dark."

"Computer drivers can have “telepathy”: A computer driver could let another computer driver know that it is considering changing lanes before making the decision to do so. It could communicate with traffic lights to minimize wait times at intersections and optimize traffic flow."

## Paper 4:Self-Driving Cars and the Urban Challenge Chris Urmson - cited
http://ieeexplore.ieee.org.ezproxy.falmouth.ac.uk/document/4475861/

In the United States, over 42,000 people are killed and over 2.7 million people are injured each year

"Maps also provide important contextual information. Consider figure 2a; without any context, the two vehicles appear to be on a collision course. Given context (see figure 2b), we can safely assume that one of the vehicles is just making a lane change and that nothing untoward is about to happen. Boss uses a model of the nearby roads in much the same way to anticipate and reason about other vehicles' movements."

"For individuals who have lost their driving privilege owing to age or disability, autonomous vehicles will remove the spatial barriers limiting them from interacting with family, friends, and the community."

"Only vehicles would be on the course, and they had to be midsized cars or larger. This removed pedestrians and bicycles from the scope."


## Paper 5:Issues about autonomous cars Claudiu Pozna - cited            
http://ieeexplore.ieee.org.ezproxy.falmouth.ac.uk/document/7507360/

"Our proposed solution to this issue is to acquire new knowledges. We consider that the locomotion is a source of experience which can be transformed in knowledges using learning technics. Once again the human driver example is follow. Starting with a basic collection of driving behaviors the human driving will acquire new skills using its experience."

"the second level mission is to solve situations which are probable but there are not anticipated by the previous level (a pedestrian which cross the road, an illegally maneuver of another driver etc.)"

"The tactical level will trigger a particular behavior in order to solve a particular locomotion problem."

## Paper 6:An Autonomous Driving System for Unknown Environments Using a Unified Map View Document Inwook Shim - cited
http://ieeexplore.ieee.org.ezproxy.falmouth.ac.uk/document/7046370/

Table 1 states that it can see a person upto 97m away
Very maths heavy 
Makes it safer by having objects that might not cause an immediate threat be taken into account. 

## Paper 7:First Person Trolley Problem: Evaluation of Drivers' Ethical Decisions in a Driving Simulator - cited
http://delivery.acm.org.ezproxy.falmouth.ac.uk/10.1145/3010000/3004336/p117-frison.pdf?ip=193.61.64.8&id=3004336&acc=ACTIVE%20SERVICE&key=BF07A2EE685417C5%2EEAA225A8AB01C582%2E4D4702B0C3E38B35%2E4D4702B0C3E38B35&CFID=727941429&CFTOKEN=73815547&__acm__=1490977716_858b57fdc01d85585787b0565d9ada65

Used humans to test the trolley dilemma and used that data to propose 
