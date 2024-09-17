
# Journal Entries

## Entry 1

Here is the first entry of my journal.

![Dinosaurs Squandered What They Had](images/end-of-the-world-meteor.jpg)

<br>

## Second Entry

Today we spoke about my project idea and spoke about some of its possible benefits and disadvantages that may arise. Some disadvantages were that it may be difficult to find a sensor that could track the animal's heartbeat or temperature from the neck area. A point made by one of my classmates was that the ear can be quite a good option for this that is readily used in the medical industry and used to measure oxygen levels. Instead of detecting the animal's temperature it could instead detect the environment temperature the animal is within using the microbits thermostat. <br>
The benefits of this could be to know how active the pet my be with the addition of a pedometer or gyro sensor. Having an lcd on the microbit it can also show a status of the pet on its collar as well as on the website in the form of a dynamic face. <br>

I purchased a pulse sensor from Ebay that will arrive within the week for use in my project. I also began testing features using the microbit controller. I used the built in temperature sensor to set the temperature variable and then checked if the temperature was within 3 different ranges, setting the pets overall temperature condition depending on which range it was within such as cold, fine, or hot. I also setup a calibratable step counter that checks for changes in the microbits accelerometer that will count steps and calculate walk distance based on the set average step distance.

<br>

This week we spoke about how my device can benefit the user, have its own unice aspects, and have a strong foundation. We also speculated how our projects could evolve or adapt, and conceptualised other potential options.

How can my project have a strong conceptual foundation? <br>
My device will be shaped around meeting the needs of pet home owners who want more information about their pet, in a fun new way. The pet health industry already has alot of research, and it will be tested on animals. <br>

How will my project benefit the user, why would they want to use it? <br>
It will benefit the user by giving them a simple effective means to check their pets overall health and activity. <br>

What is it similar to? <br>
This device shares similarities to other pet health trackers shown below, especially the PetPace dog collar. Similarly it will share similarities to a fitbit. <br>

How is it unique <br>
My device is unique because it gives the user fun images of cats alongside the information about their pet health.


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

### Idea Feedback
We spoke about my project idea and spoke about some of its possible benefits and disadvantages that may arise. Some disadvantages were that it may be difficult to find a sensor that could track the animal's heartbeat or temperature from the neck area. A point made by one of my classmates was that the ear can be quite a good option for this that is readily used in the medical industry and used to measure oxygen levels. Instead of detecting the animal's temperature it could instead detect the environment temperature the animal is within using the microbits thermostat. <br>
The benefits of this could be to know how active the pet my be with the addition of a pedometer or gyro sensor. Having an lcd on the microbit it can also show a status of the pet on its collar as well as on the website in the form of a dynamic face. 

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
A device for the user to keep track of their pet's health and wellbeing. Using different biometric sensors, it may collect input data such as heart rate, temperature, and number of steps or speed of movement and walk distance, and return output data of the overall health and happiness of the pet along with all information used to determine the results. <br>
The data will be readable from a web page that will show details about each aspect of the pet and rate its overall happiness. It will also show little quirky images of each aspect that sums up the pets active levels, temperature, and happyness. May get images from API's or in built images.

<br>

### Technology Required
Microbit V2 - microcontroller used to collect data and power devices. <br>
Pulse Sensor - reads the animals heartbeat. <br>
Accelerometer - reads number of steps taken or speed of movement. <br>
Thermometer - reads the external temperature surrounding the pet. <br>

<br>

## Development Process
### Microbit Tests
To get started on the device, I began by testing the microbits built in sensors that could benefit the project. <br>
I started with the temperature sensor, trying to detect the external temperature of the environment that the pet would be in. To do this I created a temperature variable that I then set to the current temperature the microbit sensor was receiving. Then I checked if the temperature was below a 15 degrees that is a temporary number I've defined as cold, and if not I checked if it was in a range between 15 and 30 that I defined as fine, and if not I checked if it was over 30 degrees that I defined as hot. Depending on therange that the temperature was in I set a variable for temperature state as either 0, 1, or 3, that I will use lter to calculate the pets overall condition. Finally using temp state I can then check at any time whether I want to show a happy or unhappy face on the microbit and play a melody when the tepmperature has entered a new range by only calling it if the temp state is not set to the current range. for the option of showing Fahrenheit on the eventual web page I also calculated it from the set temperature by applying the equasion F = C x (9/5) + 32. For convenience and reusability I separated these into separate functions. <br>

![Make Code Temperature](images/MC1.PNG) 

<br>

To create a step counter for the pets I first tested the on shake function to increment steps when the microbit was shaken. However I quickly discovered that the built in shake function was not sensetive enough to register steps from a smaller animal, and could not be adjusted. Following online information I found that an alternative to this is to check for changes in the microbits accelerometer strength value. I first implemented this method by checking if the acceleration strengh was greater than a defined value, and then increasing the steps variable by 1. To take this further I also created a walk distance variable to calculate the distance walked by the pet, based off of the average step distance and then multipolying it by the number of steps taken. THis will only be an estimation but is still a useful feature to have on the product. <br>
Unfortuunately this method to gather the number of steps taken proved to be ineffective as this function was simply called in the forever method, resulting in many steps being registered as long as the accelleration value was exceeding the devined strength value. <br>
I also utilised button A and B on the device as a function to check the number of steps taken, as well as resetting the step counter and walk distance. The benefit of the pet state function allowed me to return to the oet state image after 2 seconds. <br>

![Make Code Step Counter](images/MC2.PNG)

<br>

To fix the step counter I performed some various tests and eventually found the best option was to refine the strength value and also create a variable to check if a step had been recently registered to limit the number of multiple steps being registered in a single step, that wouold be set to true once a step was taken. after .2 seconds the varible would be reverted to false to allow the next step to be registered. This efectively allows the apex of the accelerometer strength value to be limited to a timeframe and strength that may be adjusted through testing to find the perfect values. This is a rudimentary method to achieve this with certain inacuracies that may arrise but seems to be the best option for the use case. <br>
I also added a clear screen function when button A or B was pressed for a cleaner outcome when showing step values on the LED display. <br>

![Make Code Step Counter](images/MC3.PNG)

<br>

As the set temp function did not need to be checked every tick of the microbit, I moved it to its own timed loop that could check the temperature every 5 seconds for the time being. This will most likely be changed to every minute or 5 minutes as the temperature will generally not change that often resulting in unnecessary calls. <br>
Also as the microbit is a V2 it has a logo button that may be pressed, so I utilised its functionality to show the current temperature in degrees celcius when pressed, before returning to the current pet state. <br>

![Button Shows Temp](images/MC4.PNG)

<br>

### Adding A Pulse Sensor
On make code I setup a simple function to read the inputs from the pulse sensor. I began by creating 2 variable caller heartRate and heartRateSmoothed. I will be using the microbit pin 0 to read the values recieved from the pulse sensor so I set the heartRate variable to the pin 0 using analog read pin, which then was made visible using serial write value. To get a smoothed result I then used a calculation for smoothing the values of the heartRate variable that is shown below. This requireed a variable I called ratio that could be changed to increase or decrease the smoothing that I currently set to '.05'. heartRateSmoothed was also made visible using serial read value. <br>

![Button Shows Temp](images/MC5.PNG) <br>

After connecting the pule sensor device to the micro bit using its 3 volt, earth, and 0 pins, I was able to recieve data and check the sensors effectiveness. Below you can see the sensor reading my heart rate with the raw data on the bottom and the smoothed data on top. <br>

![My Heart Rate](images/MC6.PNG) <br>

Now that I have confirmed the code and sensor is working I began tests with the sensor on my cat. Right away I was having trouble reading the pets heartrate as pointed out by my tutor because the pulse sensor requires skin contact for effective results. Luckily my cat has very short hair and areas with visible skin so after testing different areas such as the neck, chest, and skin, I found an area on the neck that gave results. Unfortunately these results still are not great, and in most scenarios using this sensor on other pets with more fur the user would have trouble getting effective results. This createsa problem for my devices main use case and I will have to think about weather I should try other sensor types or even reevaluate what my device could be used for, or even change it entirely. <br>

![Cats Heart Rate](images/MC7.PNG)

<br>

## References
MeasureON! Dog Heart Rate Monitor - https://vetmeasure.com/continuous-heart-rate-monitor/ <br>
PetPace - https://petpace.com/ <br>
UID Temperature Monitoring System - https://www.uidevices.com/laboratory-animal-temperature/ <br>
Infrared Thermometer - https://www.gosupps.com/dog-ear-temperature-monitor-pet-infrared-thermometer-only-for-pets-measure-in-1-second-mute-function-c-f-switchable-blue.html?srsltid=AfmBOorF7DzYrcJCc1eii48Vd4hFJCoi1JKDK0yf57EgcQsOX40jelz-mm4 <br>
