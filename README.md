<!-- 
  <<< Author notes: Header of the course >>> 
  Include a 1280×640 image, course title in sentence case, and a concise description in emphasis.
  In your repository settings: enable template repository, add your 1280×640 social image, auto delete head branches.
  Add your open source license, GitHub uses Creative Commons Attribution 4.0 International.
-->

# Secure Voting Application

- Author: David Jones
- Saint Leo University COM-437

The Android Voting Application provides a modern approach to democracy. Votes may be cast from a mobile device at any location in the world with access to an Internet connection. This application can be used for organizations that need to collect opinions of a base of people. This application can be further developed with security features such as a login, biometric identification, location services, and encrypted data to secure the reliability of the information.

# Problem Addressing <br/>
A problem that the Android Voting Application is addressing is the accessibility and availability of elections from any location. Presidential elections in the United States are traditionally performed at a specific location on pieces of paper. Technology has evolved far enough to facilitate a safe voting environment from any potential attackers with a proper implementation. Security features will protect the elector from any potential attacks on the election. User accounts can be used for allowing one vote per person. Biometric identifiers such as fingerprint, retina scans, and voice recognition can prohibit others from casting a vote from another account that does not belong to them. Location services can ensure votes are being collection from the correct geographical areas. 

# Platform<br/>
The platform that the Voting Application will be made for is the mobile OS Android. Further development can expand this to iOS and other mobile platforms. 

# Functionality<br/>
Users may cast vote(s) on elections created by an Admin using a configuration of the following features:
- One vote per device using SharedPreferences
- Votes track using MySQLDatabase
Users may anonymously vote on their favorite brand or activity presented by the vote topics. Each user may only vote once per device, participation is tracked through the shared preferences file on the Android device. Votes are then tracked by an online database and updated accordingly. 

# Front/Back end support<br/>
Users may cast votes from any of the elections currently available in the UI. Database can be connected using an Azure database or MySQLServer database. Users may only cast one vote for each election, tracked by the SharedPrefereces file on the Android phone. Once a user has voted, the vote will be sent to an online database and the option to vote will be taken away from the UI using UI.GONE.


# Design

![1](https://github.com/Not-KennyS/Android-Voting-App/blob/main/images/1.png?raw=true)
![2](https://user-images.githubusercontent.com/53955832/200150229-bd1ccbe8-b6f8-442c-940e-52ace0b9b002.png)
![3](https://user-images.githubusercontent.com/53955832/200150230-6ded08ae-e5eb-48f1-a2ea-49636e19ba49.png)
