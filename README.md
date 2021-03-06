# HackTogether Miami - Total Covid Prevention - Mask, Temperature, Distance, Crowd
## Inspiration
We are still facing the waves of Covid at certain interval of time. Lockdown has been lifted in most states but the struggles against Covid-19 aren’t over yet. It is of utmost importance that proper preventative measures are taken in public places if we want to avoid further Covid-19 waves.
## Project Description
I have found a “hack” that ensures that public places don’t become ‘Super-Spreaders’. The project provides two systems that can be implemented on CCTV cameras in any public place (after integration with IoT Technologies). The first system is built for a front view camera that detects a person’s temperature and whether they are wearing a mask. The second system is for a top view camera used to detect social distancing and monitor the number of people in a shop, restaurant, complex, etc.
## How we built it
The main tech stack we used is Computer Vision. We can solve so many real-time problem with the help of Computer Vision. We developed 2 modules , first for who are violating the basic rules of covid and, second for the crowd management at vaccination centers. because they can also be the potential contributor towards the spread.
## Challenges we ran into
Everyone is building covid prevention system individually but we decided to integrate those separate activities into one system so that can be useful for production also. We can integrate this system on any IOT camera to get this project in market. Integration was the hardest part during this project.
## The Problem It Solves
Both systems assist in the meticulous task of a security guard of catching the people who knowingly or unknowingly flout the rules. Whenever a person is not wearing a mask, not maintaining appropriate distance from other people, might have a high temperature, the guard/people can be cautioned by an alarm and are prompted to wear their masks and maintain social distance. Moreover, when the limit of people allowed at a place is exceeded, the alarm is triggered thus alerting the guard.
## Enhancement
This entire system can be enhanced if we can overcome some configuration limitations by using GPU over CPU and IR/thermal cameras instead of the normal ones.
## Instructions To Run
```
python Mask_and_Temperature_Detection.py
```
```
python PeopleCount_and_SocialDistance.py
```
## Demo
You can find the demo of the entire system <a href="https://www.youtube.com/watch?v=ou6FbRgJx7U">here</a>.
## Technologies Used 
OpenCV, Deep Learning, Computer Vision, Mobilenet, CNN
