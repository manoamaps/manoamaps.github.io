# Table of contents

[GitHub Organization](https://github.com/manoamaps/source)

[Deployed app](http://manoamaps.meteorapp.com/#/)

[M1 Project Page](https://github.com/manoamaps/source/projects/1)

[M2 Project Page](https://github.com/manoamaps/source/projects/2)

[M3 Project Page](https://github.com/manoamaps/source/projects/3)

# Project Description
Manoa parking app that will make parking on UH easier. First allows users to input their owned parking passes into a profile.  Then the user could use an interactive map that will allow them to see where they can park at which times of the day.  App will also have a system where users can input open parking spaces allowing for other users to know where there is open parking.

Team Members: Andrew Kurano, Jeremy Nagahama, Damien Lim

# Milestone 1:
 1. Get basic Meteor template running.
 2. Get basic Map component running 
  * Shows Map of Manoa
  * Shows current time in map, and what Pass you have.
  * Slider bar to adjust time.
 3. Update Map picture when new parking rules apply  
 4. Get basic MongoDB running.
  * Setup to accomodate parking passes, with pass having the time it's allotted.
  
 Add Passes Page
![Add Passes Page](/imgs/Add.png)

Landing Page
![Add Passes Page](/imgs/Landing.png)

Map Passes Page
![Add Passes Page](/imgs/Map.png)

# Milestone 2:
1. Integrate Map with DB so that map is not hard coded.
2. Setup Better Landing Page

# Milestone 3:
1. Finish editing maps so it looks professional.
2. Have parking passes tie in to which image loads.

# Guided Tour
 1. Create Account 
 ![Add Passes Page](/imgs/1.png)
 2. Add Pass to account 
 ![Add Passes Page](/imgs/2.png)
 3. Map will show your passes, along with where you can park.
 ![Add Passes Page](/imgs/3.png)
 4. Slider will let you change time, showing where you can park.

Integration with DB
![Add Passes Page](/imgs/mongo.png)

# Initial User Study
The application was popular amongst those we asked for feedback and they agreed it was something they might use. They said they particularly liked the slider feature so that it is more convenient for when they need to find parking at the current time of day. They said it could be improved by adding our planned feature of saying when a parking spot is open and/or having the slider start at the current time of day.The map itself was visually appealing and conveyed where parking was available to be clear.

# User Study Part 2.
After making finishing touches to app, and making it clear the steps, our users were much happier with the process. We had a night staff member who didn't even know that he was allowed to park at certain lots, and our app helped him show that. One user said she wished she had this freshmen year so she knew exactly where, but more importantly when, she could park. The only complaint was a user who wished he could fullscreen the map, as he was near-sighted.

# Developer Guide
 1. Clone Git Repo
 2. Run Command "npm install"
 3. Run Command "meteor npm run start"
 4. Navigate to browser, enter in URL "locahost:3000"
















