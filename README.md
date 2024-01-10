# Mini-IOT-System for home automtion system
The Internet of Things is not about things, but about meeting the needs and improving the lives of people through interconnected devices and intelligent data analysis.

![image](https://github.com/Ayatollah-blip/Mini-IOT-System/assets/55857049/de5508ad-c602-41f5-8291-8247714d2215)

## Intro
Welcome to the future of connected living with our Smart Home Automation System! In a world where technology seamlessly integrates into our daily lives, our IoT project aims to transform traditional homes into intelligent and responsive living spaces. The convergence of devices, data, and connectivity allows us to create an innovative ecosystem that enhances convenience, energy efficiency, and overall well-being.

## The Context
This project is our Portfolio Project, concluding our third sprint at ALX. We were able to choose who we wanted to work with and what we wanted to work on, as long as we present a working program at the end of the three weeks of development.

## The Team
* **Aymane El yamani** [aymaneelyamani3@gmail.com] - Software Engineer and indutrial automation engineer.
* **Hind Ouchani** [ouchani.hind@gmail.com] - Test engineer.

## Technologies
  * For the database:
            -  Either we will be working everything with embeded system so we will use light way database, so it will either MariaDb or LightSQL
            -  Or an normal one since our embeded system will only aquire the Data, then we will use an event driven technologie to sent it to our server to be logued
  * About the event driven Data aquisition, i think we will use RabbitMq with protocole MQTT to transfer the data aquired from our raspberry pi to the server.
  * For the server either be it in the raspberry pi or independent, we will use SQL alchemy to log the data to our database
  * For the Fron end we will do our first essaie to work with Angular.
## Challenge
  * Our bigest chalenge will be time, i hope that we will be able to finish it on time
  * The project will not be able to solve the physical and Hardware problems, you will be able to supervise, control and maybe be predict and prevent them.
  * This project will help the normale people to have :
           - Remote control:  Access and control your home devices from anywhere in the world through a user-friendly web application.
           - Energy Efficiency: Optimize energy consumption by intelligently managing lighting, heating, and cooling systems based on occupancy and usage patterns.
           - Personalization: Tailor your home environment to your liking with personalized settings for lighting, temperature, and entertainment.
           - Data Analytics: Gain insights into your usage patterns, energy consumption, and device performance through comprehensive data analytics.
 ## Risks
   * For the technical risks, as i mentionned above, we may slow doen our raspberry if we used it as data aquisition tool and server in the same time.
   * For non technical tool, user will have access to control remmotely, so we will have to implement a good security system into their housing.\
 
