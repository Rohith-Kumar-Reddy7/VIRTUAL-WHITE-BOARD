# VIRTUAL-WHITE-BOARD

Virtual White Board application is a conferencing tool that can be used to conduct meeting/classes effectively.This application can be used to conduct white board meetings where one freely express.
their thoughts and ideas by drawing them on the white board.The Virtual White Board can be used along with video/audio conferencing tools to proivde overall meeting experience.

## Software needed to run this application
1. Install java(>=8 version).
2. Either clone this repository or download both "host.java","guest.java" files.


## Workflow of this application
1. Host of the meeting starts his host window.
2. all the guests who know the private IP address of host can join the meeting.
3. The guest will have the freedom to join and leave the meeting whenever he/she wants.
4. The host after starting a meeting continues to write on the board using a  stylus pen and delivers his thoughts to participants.
5. The host can end the meeting for everyone.

## How to host a meeting
1. Open a terminal and navigate to the folder where "host.java" file is saved.
2. compile that file using "javac host.java" command.
3. After that enter the command "java host".
4. A white board with a few controls will be displayed,this white board is the place where the host of the meeting can express his/her thoughts.

## How to attend a meeting
1. Open a terminal and navigate to folder where "guest.java" is located.
2. compile "guest.java" file using "java guest.java" command.
3. run the generated class file using "java guest".
4. Now the terminal will prompt for the IP address of the host who is conducting the meeting.(This application is designed to be work under same LAN,so it is expected all guests to know the private IP address of host who is conducting the meeting).
5. After that terminal will prompt for the port using which the guest would like to join the meeting.
6. Now the a window with white background would be visible,the background would immediately start showing the content that the host has written.


## Usecases of this application
1. A manager in a company wants to conduct a market research analysis session with his/her employees,but assembling all of them in a meeting room will take time.In this case the manager can just inform their employees to join a skype or any audio/video conferencing platform and start this application and immediately deliver his ideas to his employees.
2. A professor conducting a lab session to your students,he/she needs to deliver some key concepts before the students start implementing in the lab,using a physical board to deliver those concepts is not a good idea because not everyone will have a nice view of board.In this case the professor will start this application and declare his private IP address to students and all students can join the meeting ,now all of them can clearly see the virtual board on their screen clearly.

## features of this Virtual White Board
1. Host can write in different colors.
2. Host can erase the contents previously written.
3. Host can clear al the contents at once.
4. Host can end the meeting for all the participants at once.
5. Guest can leave/enter the meeting at anytime.


