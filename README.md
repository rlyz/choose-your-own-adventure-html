# Choose Your Own Adventure!

![https://media.giphy.com/media/3oEjHFzI1y4erDQ4kE/giphy.gif](https://media.giphy.com/media/3oEjHFzI1y4erDQ4kE/giphy.gif)


Create a text and image/gif based game that allows the user to arrive at different "destinations" based on links that they click.

The game can be as simple or as complicated as you would like to make it.

Below are some basic rules to get you started. 

### Rules
* Any path the user goes down must ask them at least **three** questions.
* There must be a minimum of **seven** total destinations the user could arrive at based on their responses.
* For **at least one** of the questions asked, there must be **more than two possible user responses**.


### Need Some Inspiration?

How about...
* A Lord of the Rings style adventure where the player is Frodo, and he must choose how to get to Mordor. Possible obstacles involve Orcs, Goblins and getting drunk on mead.
* A "Top Chef" style cooking adventure where the player is the chef, trying to make dinner for an elite group of judges. Possible obstacles include overcooking the meal, running out of time or mean judges.
* A Harry Potter themed adventure where the user is Harry and he must find all the horcruxes. Possible obstacles include He-who-must-not-be-named, Professor Snape or Ron being completely useless.

### Pseudo-coded Example

What is your name?
* `Sean`

Nice to meet you, `Sean`. What year would you like to go to? **(YYYY)**
* `2015 or later`
    * I see you're a fan of Back to the Future 2. Would you rather deal with Biff, or Griff?
        * Biff
            * Hmm, interesting. Biff is angry and has a cane. Do you stand and fight, or run away like a coward?
                * Stand and fight
                    * Good choice. Biff is old and feeble at this point. You push him over and he falls in a pile of manure.
                * Run like a coward
                    * You get away, but your future son Marty Jr. is heckled for the rest of his days for his dad's cowardice.
        * Griff
            * Griff is asking you if you are in, or out. What do you say?
                * In
                    * Bad call. Griff and his cronies rob the Hill Valley bank and frame you for it. No more time travel for you.
                * Out
                    * Good call. You deck Griff in the jaw and run away. He gives chase on his hoverboard and ends up in a pile of manure.
* `1985-2014`
    * Doc has already destroyed the Time Machine at this point. I guess you'll have to wait around until 2015. What name would you like to go by until then?
        * `Calvin Klein`
            * Welcome to the future, `Calvin Klein`.
* `1955-1984`
    * I see you're a fan of Back to the Future 1. Your future Mom has just asked you to the Enchantment Under the Sea dance. What do you do?
        * Yes
            * Creepy. I hope you have some backup plan in place to get out of this. Until then, you're stuck in 1955.
        * No
            * Honorable. But this also means that your future Dad will never meet your Mom, and therefore you cannot exist.
        * Set her up with George
            * Interesting. You set up an elaborate plan for your future Dad to surprise your Mom by beating you up. Despite going horribly awry, the plan ultimately works. You may go back to your own time.
* `before 1955`
    * I see you're a fan of Back to the Future 3. You've run out of gas and can't get back to your own time! How do you power the Time Machine?
        * Horses
            * Good idea, but no. The time machine needs to get to 88mph. 12 horsepower ain't gonna cut it.
        * Moonshine
            * You'd be better off drinking the moonshine. Do not pass Go, do not collect $200. Stuck in 1855.
        * Train
            * Good call! This plan seems to be working. But wait! Clara wants to go Back to the Future with you at the last moment. What do you do?
                * Take her
                    * Interesting choice. Unfortunately the Doc can't grab Clara and get back to the car in time. He ends up staying in 1855 with her.
                * Leave her
                    * Smart choice. Unfortunately the Doc was deeply in love with Clara, and when he gets back to 1985 he becomes very depressed.


### Further: Make Your Game Repeat as many times as the player wants 
* Have your player repeat a set of challenges or questions over again- if a player enters a situation or room, allow them to leave and come back if they want.

#### Pseudo-coded Example
* You are in a dark room. Would you like to enter the left door or the right door?
   * (user chooses left door)
   * You enter a drawing room with heavy curtains. A mage is sitting on the sofa. Would You like to talk to him? Yes, talk to him/Leave through the right door/Leave through the left door -----> **Left door leads to the dark room**
