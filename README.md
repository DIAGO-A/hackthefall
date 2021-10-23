## Inspiration
Since in this hackathon a lot of sponsor encouraging to use their cool API in our project so I thought of making something that can implement most of the sponsor's API in my project, and that is where I came Up with the Idea of making a SMART-DEVICE that can control our appliances and door using the voice command with courier and symbl.ai APIs under the authentication of SAWO API.

## What it does

It is basically a voice enabled smart device that can open a door using a voice command with OTP valid for 40 sec sent to the registered mobile using **Twilio API**, and closes automatically off after 15 sec.

Our voice command system is enabled only with the registered ID of **SAWO** implemented in node red, if any unverified id is used to log in, it sends the user the the alert notification with id used for login.

We can also control our home appliances using this device, such as turning on or off the room light.

Each and every action taken by the system, the admin will be notified using the **Courier API**, for extra safety and security!


## How we built it
The whole backend and handling is done in the NODE-RED and had used the BOLT- wifi module with relay for opening or closing any appliances.
other from that I had used Some of the great APIs from our sponsor, Courier, SAWO, SYMBL.AI and Twilio.

## Challenges we ran into
1. The main challenges we ran through is to handle the symbl.ai transcription inside the node red and to implement the symbl.ai inside the template node and to run only with the verified user, authenticated by SAWO
2. Using of courier in node red!

## Accomplishments that we're proud of
At last we are proud what we learned and had made , some what the result is just what we wanted!
## What we learned
1. How to use Courier API
2. How to use SYMBL.AI
3. How to use the APIs in node-red
4.how to change the tabs automatically in node red.
