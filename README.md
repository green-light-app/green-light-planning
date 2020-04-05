# green-light-planning
planning documentation for green-light dating app 

# User Stories 
- A user can create a profile with relevant personal information 
  1. Email 
  2. Password 
  (Profile)
  3. Name 
  4. Age 
  5. Height 
  6. Job 
  7. Home Location
  8. Dating Location 
  9. Drink Preference (wine, beer, mixed, none)
  10. Frequency of Drinking 
  11. Smoking (yes, no, sometimes)
  12. Frequency (daily, few times a week, monthly, rarely, never)
  13. Smoking Preference (cig, weed, vape, juul, none)
  14. Do you like to (check with yeho)
  15. Workout (options tk) 
  16. Favorite sport to watch 
  17. Favorite type of show (genre?)
  18. Favorite music genre 
  19. Match gender (women, men, bi, queer, asexual, pansexual, trans) 
  20. Relationship (serious, casual, unsure) 
  21. Question categories (pets, hometown, sports, hobbies, trivia, food, travel, fashion, tv, history, tech, celebrity, social, random) 
  22. Photos 

- A user can login/logout of their account with email/password
- A user can see, update, and delete their account 
- A user should be able to swipe R (yes) / L (no) on potential Matches 
- A user should be able to match with other users 
- A user should be able to unmatch with Matches 
- A user should be able to report inappropriate Matches 
- A user should be able to communicate with Matches in a live chat function 


# MVP Features 
- User CRUD 
- User Auth 
- Swipe/Match Functionality 
- Unmatch Functionality 
- Live Chat Functionality with Matches 


# Stretch Goals 
- Live Notifications of Match/Chat
- Algorithm to float more likely Matches to the top of the queue 
- Link profiles to IG 
- Link profiles to Spotify
- Report a Ghost Feature (button)?
  - if they do not respond to your most recent msg in 5 days, they are confirmed as a ghost upon report 
  - ghosts are pushed down the queue of potential matches (less likely to see them) 
  - 10 ghosts per month - your account is temporarily suspended for 1 week? 
- Rating System for Review Feature (catfishing photos, conversation, polite, handsy)?

# Architecture 
Server-Side: responsible for persisting User actions, serving potential matches, sends live messages from User to User and persists so they exist beyond session 
- Node.JS/Express? 
- PostgreSQL? 
- GraphQL? 
- Sockets.io 

Client-Side: responsible for UX 
- ReactNative 
- Redux? 
- HTML5 
- CSS 

## To Do
- Confirm architecture decisions with Caryn? 
- Confirm final User/Profile data with Yeho 
- Build base applications 
- Expand Trello board features to build 
- Onboard new SWE/DS with Yeho 
- Confirm what DS needs to build the algorithm 
- How to integrate the algorithm with the server? 
- Fake User data 

# Developing 
- Always work on a branch! 
- Note your branch name on Trello 
- Commit often! 
- When a feature is completed, make a PR in GH. At least one person should review the code before accepting the PR 
- Pull new Master and merge it into your local branch regularly to avoid merge conflicts 
- Stretch: tests! 

# SWE 
Build baseline functionality for the MVP features. Don't worry about aesthetics or design until Yeho transfers HiFi designs over to the team. 

# DS 
Build algorithm to filter potential Matches based on preferences, then layer in recommender logic 
