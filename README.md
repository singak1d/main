# ACES TWO by ACES Go Places
A group of 3 ex-Home Team NSFs who are passionate about improving ACES with geolocation functions so that ACES can Go Places.

### Problem Statement
Problem Statement 4: Preventing the spread

In the event of a confirmed incident, there are usually multiple callers with information on the incident. However, this may make pinpointing the exact location difficult, as not all callers have information on the exact address of the affected premise, as they may be far away or passing by in moving vehicles. In certain locations, such as along highways, in parks/forested areas, and even out at sea, there are few or no reference addresses in order to accurately communicate the location of the incident. For events such as collapsed buildings, chemical leaks, large fires, or other large scale events, it is also dangerous for callers to approach the incident site to gather information, and thus they can only observe at a distance. Without accurate location information, ground officers attending to the cases would lose precious time, where those few minutes in finding out the exact location of the fire or a subject threatening to jump might mean the difference between life and death. 

ACES TWO aims to overcome these challenges by providing a way for callers to communicate to SCDF the location, extent and severity of an incident through their location data, photos, and videos. Through the compass and gyroscope in the phone, the azimuth to the incident can be plotted from their location (longitude, latitude, bearing), allowing SCDF Operations Centre to triangulate the location of the incident from two or more callers even in the absence of landmarks and reference points. The address and relevant details of the affected premises can then be extracted based on the triangulated position. By using an SMS link, it eliminates the need for users to download an additional application during an emergency, and enables anyone with a camera-equipped smartphone to provide accurate and timely information to SCDF. This also allows the Operations Centre to distinguish between multiple callers describing the same incident, or if there are two separate incidents or fire points occuring at the same time, enabling better sense-making and use of limited resources. 

As a result, ACES TWO allows SCDF to quickly identify, pinpoint, and gather information on events from the onset and prevent them from escalating further and causing greater damage to life and property. By allowing anyone in the vicinity and not just those who have downloaded myResponder or SGSecure apps to act as the "eyes on the ground" for emergency responders, community resilience is also improved, as foreigners and migrant workers can also participate in the emergency response process. In a world that is increasingly volatile, uncertain, complex and ambiguous, with multiple challenges ahead, ACES TWO is a solution that leverages technology to tap on the community for improved sense-making and faster response, not if, but when events occur. 

## Contents
1. [ACES TWO](#ACES-TWO)
1. [How it works?](#How-it-works?)
1. [scdf.tech webpage](#scdf.tech)
1. [Video Demo](#video-demo)
1. [Future Improvements/ Extensions](#future-improvements)
1. [Resources](#resources)

## ACES TWO
### How it works? (Architecture)
ACES TWO uses a separate webpage to pull important data from the caller's phone.
Such important data include Date and Time, current GPS location and direction of where the phone is facing, which helps SCDF to create a proper documentation of the case file onto ACES, rather than having our 995 Dispatchers manually typing out as is the current situation. This frees up our 995 Dispatchers to do more important tasks like assessing the nature of the incident. 

### scdf.tech webpage (Live demo/Getting Started)
*insert pic


The SMS link that will be sent to callers will bring them to the scdf.tech webpage. The webpage will first ask the caller to send their current GPS location data and direction of where their phone is facing for to the case file on ACES. In the event, where further information from the caller is needed in assisting our 995 Dispatchers to ascertain the nature of the incident, there are submission links at the bottom to allow callers to take photos and videos to upload onto ACES. In the submission links, the caller will be prompted to aim the incident location at the centre of their camera. This will help ACES TWO to narrow down the possible incident locations from the field-of-view of the caller.

[scdf.tech](https://scdf.tech)

### Video Demo
[Demo on YouTube](https://youtube.com)

### Future Improvements/ Extensions
#### Speech-to-Text capabilities
By tying ACES TWO with speech-to-text capability, additional information provided by the caller (i.e. description of what's on fire) can be cached and displayed to the 995 Dispatcher. This would ensure that our 995 Dispatchers will be able to understand the caller and have enough capacity to handle multiple tasks all at once.

#### Automated Information Gathering and Plotting


#### Management of False Alarms
Most industrial and commercial buildings in Singapore are equipped with Decentralised Alarm Monitoring Systems, which transmits the signal from an activated fire alarm to SCDF, who then activates the relevant appliances to the incident. This improves the speed of response and serves as an early-warning system to prevent incidents from escalating to a more serious level. However, false alarms due to  malfunctions, accidents, and even environmental factors (rainy days) result in precious emergency resources being wasted, as  crews are still required to remain on scene to track down the level and zone where the alarm originated. Through ACES TWO, SCDF Operations Centre can directly contact the building Fire Safety Manager or other on-duty personnel through the sms link to verify through photographic or video evidence of the False Alarm, and allow crews to return to base earlier.

[Source: https://www.scdf.gov.sg/docs/default-source/scdf-library/fssd-downloads/fsm-briefing-2017---fsm-perspective-on-false-alarms-and-practical-approach-to-fire-alarm-activation.pdf]

This function can be extended to residential premises as well. False Alarms at residential premises are mainly from Members-Of-Public (MOP) who are very concerned because of loud sounds, foul smells, or white smoke in their residential area. However, these may be a result of rotting food (perhaps due to improperly closed fridge doors) or incense smoke. When a call is received from a MOP who is not the premise owner, an SMS link can be sent to the premise owner to verify if there is indeed a genuine case of emergency.
Any non-response after a short time or negative response would then trigger the Standard Operating Procedure of activating SCDF officers to respond. A positive response from the premise owner, accompanied with photographic or video evidence would confirm the false alarm and avoid the need to activate precious emergency resources.

In cases where it is not a clear false alarm, such as a burning smell without any smoke, responding SCDF officers would have to make a judgement call of breaking into the house in the event that it escalates into an actual fire. However, this may also result in unnecessary damage to property in the case of a false alarm. ACES TWO can be used to quickly contact the premise owner and obtain more information, such as whether there is any food on the stove, greatly improving sense-making in a highly ambiguous situation. 

### Resources Used
