# project-ramsay
project-ramsay created by GitHub Classroom


# Report
Iteration 1:
For user story #8, sharing a shopping list, which was tested for in MainActivityTest5, 2 out of the 4 scenarios could not be 
tested for as it dealt with an email app that we had no control over. This is because it was not automated due to the user 
having to log into their email account in order to send the list to a recipent. However, the espresso test can work below if 
the individual who is grading it does not mind logging into their email account and sending to themselves to see that it was
properly delivered. We showed the user story properly working with all scenarios accomplished to Professor Damevski during his 
office hours on October 15th.

We tried several different approaches to implementing user story #1 (Ingredients list), but we ran out of time before we could get any of them to work in a way that was satisfactory. Luckily, the functionalities we needed were identical to those of user story #7 (Shopping list), so we borrowed heavily from that code, which had already been implemented.

We planned to implement an extra user story, namely #10 (Navigation menu), but failed to deliver on that one. Like with user story #1, a lot of time was spent flip-flopping between different possible implementations, rather than picking one and working on it. Once we finally chose a direction, we made some progress, but the "one repo now" commit and related confusion on October 13th made the project in the repo incompatible enough with the navigation prototype that merging was no longer possible. In an effort to save time and still meet the requirements for the iteration, we directed labour towards finishing user story #1, which we did successfully.

Iteration 2:

Video: https://www.screencast.com/t/l2Vyxk2jk9

Initially, we wanted to implement user story number two along with number six, but we ran out of time as this relied on another members code. So instead, we decided to focus on user story four which was Recipe History. We amended Recipe History to be updated manually by the user instead of having a favorite button because we found it easier to share. Similar to last time, we were not able to test the share button as it opens another app. If the tester does not mind logging into their email account and sending it to themselves, they will be able to see that the share function work properly. 

For user story #9, we wanted the user to be able to check out a list of recipes given by the app, each with its own unique data. We also wanted the user to be able to add their own recipes to the list os existing recipes. So if a user adds a recipe, its title will show on the recipe menu list. Unfortunately, we were unable to get the newly added recipe to display its info. 

We were able to deliver on user story #10, but since doing so affected the heirarchies of many of the xml files, all of the tests written in the previous iteration now fail. Fixing those tests is only a matter of pointing them back at the right views (the funcitonalities that were being tested haven't changed), but we didn't have time to complete that.
