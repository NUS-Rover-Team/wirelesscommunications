# Setting up Communications
## Admin Matters:
- This repository will be used to assign tasks for the week.
- All weekly tasks will be listed here in the ReadME.md. We will assign tasks during/after the weekly team meetings.
- All codes will be documented here. Reading materials will be linked here and downloads will be uploaded to the teams channel.
- Bring up code-related issues in the issues tab of this repo. Tag it with the apt tag.
- Other issues can be posted on the discussions forum of the team on github or the group telegram chat.
- If you are not too familiar with the usage of github, do not worry we will briefly go through it in the first Comms meeting!
- First off, click on **Watch** located at the top of the repo screen to get updates related to the repository.
- Secondly, the general rule of thumb when adding/removing/editing code in any of the Comms repos and subrepos is this:
1. For the first time you are contributing to the repository: remember to fork it to your account. This creates a new repository under your account, where you can edit and branch code. You can commit and push changes to your fork BUT DO NOT COMMIT CHANGES DIRECTLY TO THIS REPOSITORY.
2. Once you have made changes to your forked repo, you can make a **pull request** to the main repo. From there on, the comms leads will review the code and merge/not merge it with the main code accordingly.

### **Are you new to git source code control?**
Here are some links that will help:
1. [Git Tutorial](https://git-scm.com/docs/gittutorial)
2. [Git Branching Workflow](https://www.atlassian.com/git/tutorials/comparing-workflows/feature-branch-workflow)

We'll do an example of general workflow in the 1st team meeting. Before that, do the 1st part of the workflow procedure as specified [HERE.](https://raw.githubusercontent.com/NUS-Rover-Team/wirelesscommunications/master/docs/instructions/workflowpractice.md)

# Week 1: Literature Review

### 1. NASA's Rover Projects

- Read about the communication system used in Mars Rovers like [Curiosity](https://mars.nasa.gov/msl/mission/communications/) and [Perseverance](https://mars.nasa.gov/mars2020/spacecraft/rover/communications/).

### 2. Why Comms? 

- Why is communication needed for the rover?
- Why is wireless communication important?
- Do we focus on wired communication? (Like USB UART?)
- What are the subsystems that require communication?
- What is the direction of transfer?

### Compulsory readings

- [This website](https://commotionwireless.net/docs/cck/networking/learn-wireless-basics/) is a walkthorugh of wireless comms basics.

# Week 2: Literature Review and Hardware Selection

### 3. How do we Communicate?

- We require wireless communication to transfer data between the base station and the rover.
- What are the possible ways to make this communication possible?
- How can we organise the data packets?
- What are the possible issues/shortcomings?
- How do we use ROS to communicate?

### 4. Antenna Selection

- Watch [this video](https://www.youtube.com/watch?v=46SbGxS73dY) explaining antenna fundamentals.
- An article on increasing range in wireless communication: [click here](http://robotsforroboticists.com/long-distance-wireless-communications-antennas/)

### Additional Readings

- Pages 62 (from 4.3.6.3 Noise and Interference) to 71 (before 4.3.7 OPTICAL PROPAGATION BASICS) of [this document](https://public.ccsds.org/Pubs/880x0g3.pdf) explain the fundamentals of wireless communication using Antennae.
