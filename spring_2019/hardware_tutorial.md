//This document contains a tutorial about what we did as the hardware team for FLOM(Folsom Library Occupation Monitor)

This being my second semester of college, with a very basic knowledge of circuits and sensors, I have already learned a lot. When we were deciding the technologies to use, we decided to use raspberry pi because we would be able to send information to a remote server that the software team could then use to make changes to the site and convey information to the users. A big discussion was also the pros and cons of different
sensors. I was in charge of gathering information about different sensors and how
they would be integrated with the raspberry pi. After doing research, we determined
that infrared sensors would be the best to use since it would provide us with the most
possible information. We found this infrared sensor array that had enough range to cover the entire room.
It was expensive but it would get the job done. Now that we had a sensor, we needed to implement it
with the raspberry pi. Liam told me to research and learn about I2C ports and code for that.
I learned alot about that and the gist of it is that you need a read and write function
that will essentially just read and write information to and from a raspberry pi.
Matthew and I also wrote some pseudocode about how we would determine if someone was in the room or not.
We made it so that it would continuosuly read the temperature and change the bse line. That way, when there is a massive change (when someone enters the room) , it would determine that someone was in the room. There are a lot of test cases and we want to get more analytics such as hwo many people are in the room at a time and different time stamps when people leave. That is more work for next semster that I will definitely work on.
