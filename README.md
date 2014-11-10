# CircleBack Coding exercise 

This is a quick 4-6 hour coding exercise to gauge your skillset and ability to work with the iOS SDK.  You’re free to produce the code in anyway you like (provided it’s your own code).  CocoaPods are ok to use, just please note which you used on the README file.  We also request you include your pods directory.  This is considered best practice anyway.  When you’re done put the code on github and supply a link for us to pull the code and have a look.  

## General:
We’re going to create a simple faux-contact management app.  It won’t interface with the address book framework directly, but will rather mimic some of the capabilities of the iOS contacts application.  The app will consist of three primary views

1. 	A list view showing each contacts first name, last name, company name (if they have it), and a profile picture.  If there’s no profile picture provide a placeholder view that either shows the contact’s initials as in the iOS contacts or drop in some kind of placeholder image.  Tapping on a cell in the table will push (via navigation controller) to the contact detail view.  There should also be a button or means for me to go a view to add a contact from this screen. 

2. 	A contact detail view that lists the following possible details for a contact: 
  * First Name
  * Last Name
  * Address (Street1, Street2, City, State, Zip)
  * A single phone number
  * A single email address
  * Company
  * Job title
  * Display the profile image or placeholder somewhere logical in the view
  * I should be able to go back to return to the list or edit the contact from here (an edit button is fine)
3. 	A contact edit view, where the above information can be changed by a user.  It’s not required to add ability to change the contact image.  I should be able to save the contact and have it reflected throughout the rest of the app or or go back canceling my changes.  When I go back I should be alerted that will lose my changes and I’m provided the opportunity to cancel.  Reuse this view for adding a contact as well.

Your code should use proper design patterns throughout.  The code should compile after pulling and run without crashing on iOS8+.  We’ll not be judging design per se, but your UI should be intuitive; use the iOS contacts app as a guide.  Lastly, please supply any additional thoughts you might have implemented with more time other concerns about the project (errata).

That’s the minimum.  Extra credit for any of the following:
* Provide persistence (CoreData or other) so my changes are maintained after the app is killed.
* Provide the ability to change the profile image for a contact
* Any UI details or polish to enhance the user experience.  
* Provide the ability to have multiple emails/address/phones/etc.
* Export a contact to the iOS address book (if you’re feeling really ambitious).  
* Any other unique or interesting ideas you might have.  
  
**Happy Coding!**

