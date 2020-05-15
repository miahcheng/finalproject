Project Description
This application is intended to be used by people who need to easily figure out when other people in a group are free. This could be used for scheduling meetings, but also for any sort of group activity. Whether it be grabbing coffee, having a party or planning a company meeting, this app will provide the capability for people to easily find out when every person is free. Realistically, this will be used most by students and young adults, and potentially working professionals for planning activities. This application is useful because it allows for users to log in and save their schedule information and allows for the planning of multiple events. This has more functionality than current alternatives such as When2Meet which only has temporary meetings. It should make planning events and get-togethers even easier and much more efficient. We as developers would like to build this application as it will give us more practice in authenticating users and allowing for them to interact with other users. It should present a valuable experience in furthering our knowledge of Golang and its capabilities alongside Docker and associated Databases.

Technical Description


P0
As a user, I want to be able to input my free times and see where overlap exists
P1
As a user, I want to be able to get the free times for a specific meeting
P2
As a user, I want to be able to change my schedule for any meeting
P3
As a user, I want to be able to save a general schedule which can be used quickly
P4
As a user, I want to vote on which free times work best for me
P5
As a user, I want to be able to alter my schedule once a meeting is decided
P6
As a user, I want to send messages to other users (Stretch Goal)


GET
/user/id
Get the free times and schedule for a user
POST
/user/id
Add free times to a user’s schedule
GET
/meeting/id
Get the free times associated with a meeting
POST
/meeting/id
Vote on a free time associated with a meeting
POST
/user
Create a new user or login
POST
/meeting
Create a new meeting
PATCH
/user/id
Update the times or information for a user

