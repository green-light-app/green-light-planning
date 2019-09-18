# green-light-planning
planning documentation for green-light dating app 

# User Stories 
- A user can create a profile with relevant personal information 
  1. Name 
  2. Age 
  3. Location 
  4. Gender
  5. Job 
  6. Education
  7. Photos (6?) 
  8. Answers to Prompts 
    - Favorite snack
    - FMK: Hiking, Netflix, Bar Hopping
    - Favorite vacay spot 
    - If you could become any animal, what would it be and why 
    - What 3 items would you bring on a deserted island for survival 
    - Plane, Train, or Boat 
    - If you could only eat 1 thing for the rest of your life what would it be 
    - Favorite ~basic activity 
    - Can you keep a plant alive 
  9. Smoker/Nonsmoker 
  10. Drinker/Nondrinker 
  11. Drugs/Nondrugs 
  12. Weed/Nonweed 
  13. Dogs/Cats/Other/No
  14. Kids/No
  15. Casual/Unsure/Relationship

- A user can login to the app 
  1. Email 
  2. Password 
  
- A user can select dating preferences (dealbreakers) 
  1. Location (Radius) 
  2. Education 
  3. Smoker/Nonsmoker 
  4. Drinker/Nondrinker 
  5. Drugs/Nondrugs 
  6. Weed/Nonweed 
  7. Dogs/Cats/Other/No
  8. Kids/No
  9. Casual/Unsure/Relationship

- A user should be able to swipe R (yes) / L (no) on potential matches 
- A user should be able to match with other users 
- A matched user should be able to communicate with the other user 
- A user should be able to logout/delete their account  


# MVP Features 
- Auth 
- User CRUD (inclusive of job) 
- Set User Preferences 
- Swipe/Match Functionality 
- Unmatch functionality 
- Chat Functionality among Matches 


# Stretch Goals 
- WebSocket Chat 
- Live Notifications of Match/Chat
- Algorithm to float more likely Matches to the top of the queue 
- Report a Ghost Feature (button)
  - if they do not respond to your most recent msg in 5 days, they are confirmed as a ghost upon report 
  - ghosts are pushed down the queue of potential matches (less likely to see them) 
  - 10 ghosts per month - your account is temporarily suspended for 1 week? 
- Report Stuck with Bill Feature (button)
- Rating System for Review Feature (catfishing photos, conversation, polite, handsy)
- Link profiles to IG 
- Link profiles to Spotify
