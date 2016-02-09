#Homework 1: Part II


##Assignment
1. Scene 1: Login Screen with inputs for username/password and login button. Obscure text in password input field
2. Scene 2: Profile screen with image and two buttons: info and goals. Screen is pushed after user logs in
3. Scene 3: Bio is displayed using modal segue in new navigation controller when info button is selected. View includes bar button to return to profile
4. Scene 4: Goals screen with goals in bold red text and image of a favorite thing. View is navigation controller and includes bar buttons to return to profile and to navigate to info (bio)


##Steps by Scene
**Scene 1**:

- Created login screen using navigation controller
- added text fields for username and password
- added button for login

**Scene 2**

- Added view controller with label, image, and two buttons
- Embedded navigation controller
- Added scene title to Navigation bar
- Used stack view to align objects
- Added show/push segue from login button in scene 1

**Scene 3**

- Added view controller with text view
- Embedded navigation controller
- Added bar button item for return button to profile screen
- Configured button to show profile screen
- Added modal segue to display bio when user selected info button in scene 2
- Added scene title to Navigation bar

**Scene 4**

- Added view controller with image and text view
- Used text view to align objects
- Embedded navigation controller
- Added Bar button items for profile and info 
- Configured buttons using show/push actions
- Added scene title to navigation


##References

- **Stack View**
<https://developer.apple.com/library/ios/referencelibrary/GettingStarted/DevelopiOSAppsSwift/Lesson2.html#//apple_ref/doc/uid/TP40015214-CH5-SW1>
<http://useyourloaf.com/blog/easier-autolayout-with-stackviews/>

- **Text Views**
<https://developer.apple.com/library/ios/documentation/UserExperience/Conceptual/UIKitUICatalog/UITextField.html>

- **Adding Images**
<http://codewithchris.com/11-adding-and-displaying-images-in-your-app/>

- **Navigation Controllers**
<https://developer.apple.com/library/ios/referencelibrary/GettingStarted/DevelopiOSAppsSwift/Lesson8.html>

