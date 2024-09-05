
# Journal Entries

## Entry 1

Here is the first entry of my journal.

![Dinosaurs Squandered What They Had](images/end-of-the-world-meteor.jpg)

<br>

## Second Entry

Today we spoke about my project idea and spoke about some of its possible benefits and disadvantages that may arise. Some disadvantages were that it may be difficult to find a sensor that could track the animal's heartbeat or temperature from the neck area. A point made by one of my classmates was that the ear can be quite a good option for this that is readily used in the medical industry and used to measure oxygen levels. Instead of detecting the animal's temperature it could instead detect the environment temperature the animal is within using the microbits thermostat. <br>
The benefits of this could be to know how active the pet my be with the addition of a pedometer or gyro sensor. Having an lcd on the microbit it can also show a status of the pet on its collar as well as on the website in the form of a dynamic face. <br>

Apparently, you can get a free heartrate sensor from Queensland health.

I purchased a pulse sensor from Ebay that will arrive within the week for use in my project. I also began testing features using the microbit controller. I used the built in temperature sensor to set the temperature variable and then checked if the temperature was within 3 different ranges, setting the pets overall temperature condition depending on which range it was within such as cold, fine, or hot. I also setup a calibratable step counter that checks for changes in the microbits accelerometer that will count steps and calculate walk distance based on the set average step distance.

<br>

## Choosing A Project
In this section, using the provided generator I used the generated options both individually and, in a group, to come up with possible project ideas relating to responsive design.

<br>

### Quick Ideas - Group
1. <br>
Form - Custom hardware, physical hardware each person places finger on a device sensor <br>
Configuration - Multi person, game with multiple people causing stress <br>
Input - Biometrics - measuring heartrate of each person and anyone outside the measured output sends data <br>
Output - Haptic - Highest measurement gets zapped by device <br>

2. <br>
Form - Mobile app <br>
Configuration - Multiperson use app on their phone. <br>
Input - Environment Sensors collects each persons data (Geolocation) gives their weather <br>
Output - Informational Tells people if they will also get rain

<br>

### My Ideas - Individual
Form - Custom Hardware <br>
Configuration - Nonhuman <br>
Input - Manual Controls <br>
Output - Informational <br>
This could be an informative biometrics reader for cats and dogs, to inform the owner of the animal's health such as vitals, temperature, and fatigue. It could be made from a microbit with a heart rate monitor and reading the animals temperature, a Wi-Fi chip or bluetooth could be used to send the information to a web application. This device could be made in a small form factor to be used as a collar attachment, provided these biometrics can be read from the neck area and cause minimal discomfort.

<br>

## Similar Projects
### MeasureON!
MeasureON! is a dog heartrate monitor app that pairs with a device and provides consistent heart rate monitoring. It uses a harness that places the monitor on the lateral sides of the chest using sensory combs that manoeuvre through the dog's fur, alleviating the need to shave. This device is mainly used by veterinarians and requires hypoallergenic gel to be applied for conductivity. <br>
Device also measures temperature, respiratory rate, relative activity level, and ambient conditions. <br>

![Dog Heart Rate Monitor](images/HRM1.jpg)
![Dog Heart Rate Monitor](images/HRM2.jpg)

<br>

### PetPace AI Smart Collar
PetPace is an AI smart collar that continually monitors a pet's health and GPS location, sending data to a phone app for pet owners to view. The device examines all essential vitals and biometrics to collect data that then through machine learning observes your pet's health over time, collecting essential data for your vet. The app sends alerts of early warning signs for need of veterinary care and also correlates your pet's data against thousands of similar pets. Thanks to the device collecting data every 2 minutes you can keep a constant update of your pet's condition through the app to check your pet's temperature, heart and respiration rate, the condition of its activity and sleep, as well as its GPS location.

![PetPace Smart Collar](images/PPC2.PNG)
![PetPace Smart Collar App](images/PPC1.PNG)

<br>

### UID Temperature Monitoring System
The UID temperature monitoring system is an implanted RFID microchip that will measure an animal's temperature with high accuracy. Microchip readers are used to scan the chips measurements that are then sent to a computer using wireless or serial link communication. Microchips contain on-board memory for customised identifiers of each subject such as unique identifiers, gender, DOB, study number etc. System generally used for animals in a clinical or research setting and is beneficial for streamline temperature collection that is safer and more accurate than traditional methods.

![Temperature Monitoring System](images/UID1.PNG)
![Temperature Monitoring System](images/UID2.PNG)

<br>

### Infrared Thermometer
The infrared monitor is a less invasive method for home users to check their pets temperature. Using a long probe the device measures heat waves around the ear drums and only requires one second to measure. The device allows for the sound to be turned off to avoid scaring the animal and has the option to view the temperature in degrees Celsius and Fahrenheit.

![Infrared Thermometer](images/IT1.jpg)
![Infrared Thermometer](images/IT2.jpg)

<br>

# Animal Health Tracker
## Overview
Wearable Technology senses biometric data of pets.
A device for the user to keep track of their pet's health and wellbeing. Using different biometric sensors, it may collect input data such as heart rate, temperature, and number of steps or speed of movement and walk distance, and return output data of the overall health and happiness of the pet along with all information used to determine the results. 

<br>

### Technology Required
Microbit - microcontroller used to collect data and power devices
Pulse Sensor - reads the animals heartbeat
Accelerometer - reads number of steps taken or speed of movement
Thermometer - reads the external temperature surrounding the pet.

<br>

## Development Process
### Microbit Tests
To get started on the device, I began by testing the microbits built in sensors that could benefit the project. <br>
I started with the temperature sensor, trying to detect the external temperature of the environment that the pet would be in. To do this I created a temperature variable that I then set to the current temperature the microbit sensor was receiving. Then I checked if the temperature was below a 15 degrees that is a temporary number I've defined as cold, and if not I checked if it was in a range between 15 and 30 that I defined as fine, and if not I checked if it was over 30 degrees that I defined as hot. Depending on therange that the temperature was in I set a variable for temperature state as either 0, 1, or 3, that I will use lter to calculate the pets overall condition. Finally using temp state I can then check at any time whether I want to show a happy or unhappy face on the microbit and play a melody when the tepmperature has entered a new range by only calling it if the temp state is not set to the current range. for the option of showing Fahrenheit on the eventual web page I also calculated it from the set temperature by applying the equasion F = C x (9/5) + 32. For convenience and reusability I separated these into separate functions. <br>

![Make Code Temperature](images/MC1.PNG) 

<br>

To 

![Make Code Step Counter](images/MC2.PNG)

## References
MeasureON! Dog Heart Rate Monitor - https://vetmeasure.com/continuous-heart-rate-monitor/ <br>
PetPace - https://petpace.com/ <br>
UID Temperature Monitoring System - https://www.uidevices.com/laboratory-animal-temperature/ <br>
Infrared Thermometer - https://www.gosupps.com/dog-ear-temperature-monitor-pet-infrared-thermometer-only-for-pets-measure-in-1-second-mute-function-c-f-switchable-blue.html?srsltid=AfmBOorF7DzYrcJCc1eii48Vd4hFJCoi1JKDK0yf57EgcQsOX40jelz-mm4 <br>
