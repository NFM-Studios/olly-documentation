## Wagers Breakdown
To begin Wagers are broken down into 3 specific segments. First WagerRequests.
When a user/team wants to play in a wager they will submit a WagerRequest 
to the given website including the amount of credits they want 
to wager and any additional information, as well as specifying the team they'd like to play with, 
and the game and platform they want to compete on.
Next after the request is submitted it will stay active only for 30 minutes after it is initially created. 
Another team may challenge this team and in doing so creating a WagerChallenge. (For developer terms it exists, 
but for user purposes it only serves as a confirmation to challenge the team that requested a wager)
The purpose of a challenge is simply for the system to ensure that the challenging team is elgibile to play.
After the team challenges a WagerMatch will be created, simply a standard match, just associated with a Wager.
