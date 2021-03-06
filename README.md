# Android Version made in Java
[Android Version](https://github.com/justvinny/pass-vault-java-android)

# Pass Volt v1.1 (Desktop)
Password management GUI made with Python's tkinter module.

It's main purpose is to make remembering unique complex passwords for your multiple accounts easier. 

Pass Volt stores all acount information into a local dbm file on your device using Python's shelve module.

This should be a secure solution as long as you do not share the dbm file to other people or get your device stolen. :)

# Screenshots: 

![Screenshot](https://github.com/justvinny/tk_PassVolt/blob/master/screenshots/SS_Login.png)

![Screenshot](https://github.com/justvinny/tk_PassVolt/blob/master/screenshots/SS_Home.png)

![Screenshot](https://github.com/justvinny/tk_PassVolt/blob/master/screenshots/SS_NewPlatform.png)

![Screenshot](https://github.com/justvinny/tk_PassVolt/blob/master/screenshots/SS_Remove1.png)

![Screenshot](https://github.com/justvinny/tk_PassVolt/blob/master/screenshots/SS_Remove2.png)
                                                                                                                                                                                                                        
# What's new:
* Finished fixing buttons not highlighting properly on Windows OS.
* Hidden password field when registering a new platform.
* Minor UI design tweaks—added title header for main menu and added borders for menu.

# Dependencies:

* pyperclip
* shelve, tkinter (both in standard lib)

# Current Features:

* Login page so only you can access the data. Input fields characters are also hidden to protect your account from prying eyes. :)
* Binded enter to Login button when highlighted with tab key.
* Input validation for entry fields. Also, if new user, automatically creates account based on first input.  
* Main menu/navigation that is located on the left part of the screen.
* Create new platform accounts that will be stored in the dbm file.
* Delete existing accounts that will be removed from the dbm file.
* Remove allows multiple selection for easy deletion.
* Status bar that shows results based on button presses is located on the lower right side of the screen.
* Using the pyperclip module, automatically copies the password to the clipboard.
  
  
# Work in progress:

* ~~Package into exe file for windows.~~ COMPLETED 27/1/2020
* ~~GUI design revamped~~ COMPLETED 27/1/2020
* ~~Create Pass Volt password page if new user.~~ COMPLETED 26/1/2020

# Future plans:

* Might make GUI even nicer—add icons, logo, fancier backgounds, etc. 
* Make a mobile version using kivy. 
  
