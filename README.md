# VCare
## Inspiration
Data-powered tools change the way that clinicians and health care facilities respond to patient need and provide care – for the better. It is observed that significant number of patients are impacted due to lack of proper monitoring. We intended to provide a life saving application that can be accessed from the fingertips of physicians.

## What it does
VCare solution aids to constantly monitor a patients health condition and performs the following actions during an emergency:
1) alerts the hospital staff using a voice assistant
2) sends an SMS alert to the physician

The solution also provide a real-time data monitoring using smart charts and graphs.

## How we built it
We used IBM Bluemix, NodeRed and Watson IoT to simulate a virtual hospital environment. As we don't have expensive medical sensors, we simulated the sensor data using CSV files. Once we have a periodic data, it can be monitored and we used NodeRed's flow to simulate the necessary IoT. 

## Challenges we ran into
1) Authorization error while creating an end-point api to feed the CSV data with the help of Datazar's api.
2) It's quite hard to find any public datasets that has data for continuous monitoring of a patient.

## Accomplishments that we're proud of

## What we learned
We are really amazed by the level at which IBM Bluemix and Watson IoT simplifies hustles in integrating different technologies like text-to-speech, IoT, storage service, Twilio etc. It's a great platform to create and integrate IoT at a fast pace.

## What's next for VCare
currently, the threshold level of a monitored parameter at which an emergency is created has to be set by the Physician. In future, even this can be completely automated by training our solution with patients medical history. This will help to be more precise in the kind of medication patient receives.
