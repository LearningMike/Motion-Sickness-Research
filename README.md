# Motion Sickness Research
* [Guide To Motion Sickness - Google Doc](https://docs.google.com/document/d/e/2PACX-1vQe9ovALwpzzemTj97FFigmz61Hqo8ERhvdECJCx2AmiaULwMf4icccNqwD9a8d6IsqRompdUX8QmtS/pub "Link")
* [Motion Sickness: Age and Experience - Google Doc](https://docs.google.com/document/d/19YFytgKm9uV4bf8o8m0E3g3nK-P-FLQHBfe74kACn7I/edit "Link")
* Motion Sickness: Matching Perceptions and Easing Habituation **(stuck)**

Motion sickness is a condition that occurs when exposed to an environment with unfamiliar motion and orientation cues. We sense our movements in real-life three-dimensional space by vision and deduction from acceleration and deceleration events. While vision is obvious, these deduction events are detected through feedback from multiple systems during acceleration and deceleration; vestibular, haptic and pressure etc. By keeping account of these events, we can predict our orientation, position and help maintain our postural balance. When our different perceptions of these events do not match it creates a subversion in experience, as what we believe should be happening is not. While the easiest solution to Motion Sickness is to avoid motion, this greatly affects immersion in Virtual Reality games with freedom of movement. The goal is to research and develop a locomotion system for VR games that maintains immersion while greatly reducing the effects of motion sickness without use of massive or room-scale space.

Here, I present my analysis of a human being walking in real life with the goal of bringing the experience of moving in VR closer to real life and significantly reducing the occurrence of motion sickness for most people. This experience is interpreted as the positional data of a Quest 2 HMD, Left and Right Controllers during a short stride forward.

![WalkingSimData](https://github.com/LearningMike/Motion-Sickness-Research/assets/31394535/51b32081-927a-4362-972f-2265c7a102b9)

SfsHead: Velocity of the player moving forward. \
SfbLeft: Velocity of the left controller relative to the body. \
SfbRight: Velocity of the right controller relative to the body. \
DfbLeft: Distance of the left controller relative to the body. \
DfbRight: Distance of the right controller relative to the body. \

Main points observed within one half walk cycle:
1. The velocity of the controllers are at maximum while they cross.
2. The velocity of the controllers are at minimum or zero when they are furthest apart. 
3. The velocity of the controller moving backwards is the velocity of the player moving forward.

  
### Walking Simulator (Project Paused)
[YouTube Video](https://www.youtube.com/watch?v=mYyiv_fWQX0&list=PLtCV-3rgo36gouvLAEJzEdEW9aH_c7YKW&index=7 "Link")  
[Invite URL](https://www.meta.com/s/3mKE1bO5M "Join")  
[AppLab Beta (Join via Invite URL First)](https://www.meta.com/en-gb/experiences/5836841769681227 "Join via Invite URL")  
*NOTE: The AppLab Beta Link will appear broken until you Join via Invite URL with your Meta Quest Account*
