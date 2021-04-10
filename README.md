# reggrepo114

#ACTIVITY 0101 <br>
![Poor Interface Example](/GPStest.png) <br>
**GPS Poor Interface** <br>
This is a GPS app I found on the Android app store called GPS test,
I found the interface hard to look at with all the bright colors, there is too much popping and it's visually noisy. Also the buttons have no clear indication of what their intended purpose is, nor does most of the other data in the viewport. <br>

![Good Interface Example 1of2](/Security1.jpg)
![Good Interface Example 2of2](/Security2.jpg) <br>
**Lorex Security App Good Interface** <br>
This is my home security system app which I feel is a good example of a better interface design. It's easy on the eyes and it's fairly obvious what the buttons do that are not named and the main screen is kept with as few options available as to keep it clean looking and extra features are available from the navicon in the upper left. The color scheme is also consistent with good contrast with the text.
<br><br>


#ACTIVITY 0102 <br>
**Usable List**
- Interactive objects are easy to identify.
- Interactive objects are placed so the user doesn't need to search.
- Color contrast is appropriate with daytime viewing taken into consideration.
- No horizontal scrolling is necessary.
- Font is easy to read.

**Intuitive List**
- Responds to hardware navigation buttons in a similar way they are commonly used.
- Purpose built objects and interactions are easily identified within the context they are being used.
- Content layout is in a logical order or information hierarchy.
- Restrain mobile content to only what the user needs, all the bells and whistles go to the actual website.
<br><br>






#**ACTIVITY 0201** <br>
**App selected:** Bitcoin checker <br>
![BTC Checker 1of2](/btcChecker1.jpg)<br>
![BTC Checker 2of2](/btcChecker2.jpg)<br>

**Description:** The app periodically updates prices of various crypto currencies from a number of exchanges.<br>

#**Permissions**<br>
- storage - Read contents of SD card.
- storage - Modify contents of SD card.
- have full network access.
- view network connections.
- control vibration.
- run at start up.
- prevent phone from sleeping.
- change audio settings.

#**Features**<br>
- android.hardware.audio.output.
- android.hardware.screen.portrait.
- android.hardware.touchscreen.
- android.hardware.wifi.direct.
- android.software.app_widgets.
<br><br>


#**ACTIVITY 0203** <br>
For this activity I read the article about the principles of sound here [Principles of Sound](https://material.io/design/sound/about-sound.html#principles)
where the topic goes over how sound can provide positive feedback for a product.<br>

With provided examples the article discusses how different sounds can influence the emotional state of the user which makes sense, if colors can do it, then surely sound can as well. It's not something I've really put a lot of time into before reading the article as my own projects have not required any sound up to this point.

#**There are 3 types of sounds mentioned in the article**<br>
- Sound Design
- Music
- Voice

While the article continues to describe the sound types in more detail, it basically approaches sound much in the same that other visual design principles are, and that is to use sound to tell a story,  provide hierarchy, and increase the efficiency of communication and information in an intuitive way. 





<br><br>
#**ACTIVITY 0301** <br>
**Description:** Try to identify all the activities or screens in a frequently used app and attempt to categorize them in a meaningful way.

**App Chosen:** Bitcoin Checker<br>
![Bitcoin Checker App](/btcChecker_3screens.png)<br>

There are 3 screen/activities for this app.<br>
- The first screen is where you view your list of coins and their current prices. This is intended to be the main activity where you'll spend most of your time. 
- Plus button at the top of the 1st screen will bring you to the second activity/screen where you can choose from a list of exchanges.
- Once you've chosen an exchange on the 2nd screen, your brought to a 3rd screen where you can decide which coin from that exchange will be in the tracking list and what currency it will be paired with. Alarms and notifications can also be configured on this screen.<br>

<br><br>
#**ACTIVITY 0302** <br>
**Description:** Identify common android event types from chapter 3.2 that may be present in my app of choice.

**App chosen:** Bitcoin Checker<br>

**The following events are those I am fairly confident are part of the app.**

Event | Description
------------ | -------------
onClick() | Found on the majority buttons throughout all different activities.
onLongClick() | Fires when touching the screen.
onKey() | Fires during data entry from an on screen keyboard.
onDrag() |Fires when rearranging the stacked elements on the first screen.
Extra | There must be an event for watching price changes of external information, but I'm not finding anything on developer.android.com that seems to fit this criteria.



<br><br>
#**ACTIVITY 0401** <br>
**Description:** Characterize the navigation model and examine how to traverse through different activities / screens.

**App Chosen:** Bitcoin Checker<br>
![Bitcoin Checker App](/btcChecker_3screens.png)<br>

In the screenshots (above), the first page/Activity is brought up by opening up the app, from here we can get to the next Activity/Screen where we choose the exchange to use by hitting the "+" button in the top menu. 

From the Choose Exchange screen, the Activity will automatically change to the coin selection details screen once an exchange has been selected. 

Finally on the coin selection details screen, you can hit the checkmark to finish and return to the primary or main screen. 

No swiping is possible from any screens, however there is a hierarchy to the activities as the main activity is dependent on the information chosen on the other 2 screen. Screens must be accessed linearly and in order regardless of direction.
<br><br>


#**ACTIVITY 0403** <br>
**Description:** Characteristics and uses of the bottom app bar.
- Displays navigation and key actions.
- Provides access to a bottom nav drawer and up to 4 actions, including the floating action btn.
- Highlights important screen actions and draw focus to the floating action button.
- Available actions can changed based on the needs of the screen.
- Is easily reached from a handheld position.
- Is mobile oriented as it would feel clunky on a desktop app.
- Can be used in conjunction with the top app bar
<br>

**Description:** Characteristics and uses of the top app bar.
- The top app bar provides content and actions related to the current screen. It’s used for branding, screen titles, navigation, and actions.
- Can disappear with scrolling
- Provide a reliable way to guide users through an app.
- Have a consistent position and content to increase familiarity.
- Can form into a contextual action bar which provides actions for selected items until an action is taken or dismissed by the user.
<br><br>



#**ACTIVITY 0501** <br>
**Description:** Characterize the app's navigational model (similar to activity 0401), but in this case you will draw a diagrammatic representation of the navigation. You may use the same app chosen for activity 0401. Include an image of your drawing in your Process Portfolio and briefly describe what you have learned from this activity.<br>

**App Chosen:** Bitcoin Checker<br>
![Navigation Diagram](/navDia.jpg)<br>

I had a hard time with this one as I didn't feel that I learned anything by this activity, however my perception of the activity may have been wrong. I meant to revisit this before markup and upload but didn't unfortunately. 

My only real thought coming out of this activity would be that it helps when designing your MVP. However I have a feeling that's not the case here as we just went over this topic in DGL 111. So apologies if this one is a bit from left field like I think it is.
<br><br>



#**ACTIVITY 0503** <br>
**Description:** Carefully consider when the use of dialogs is appropriate and summarize any findings.

I found this article very enlightening actually, the information seems like it would be intuitive since it makes sense as I read it, but much of it was new to me.

The article more or less describes using modal dialogs as a problem solving tool that requires decision by the user, giving modal dialogs an important and critical role. The article basically lays out that the use of dialog modals for aesthetic purposes or visually centered purposes is a bad idea, and rightly so given how disruptive a dialog is to whatever app your running. This intentional interruption was designed with the idea that the information or decision requiring the user's interaction is critical, therefor use of dialogs outside of this premise would be interfering with user control on a level that isn't warranted.


#**ACTIVITY 0801** <br>
**Description:** Choose a relatively complex mobile app (Android or iOS) that you use frequently. For this activity you will characterize the app's data storage capabilities. 

**App: Lorex Cloud** <br>
Shared Preferences - I do not think the app uses shared preferences.<br> 
App-specific files - Preferences or configuration files that hold local information like favorite camera layouts would meet this.<br>
Shared storage: None.<br>
Database: 
There is a PVR which records the cameras but rewrites every month or so, but snapshots taken can be viewed across devices and saved to my phone if I like and later be searched via date, time, camera, and can do this while my mobile is offline if I saved the images previously. Sounds like querying a database to me.<br>
Cloud Storage:
Images taken from the security system and saved are available across my computer and mobile devices l, but as for the mobile app itself I do not think the app saves data over cloud storage directly as nothing the app produces would be useful to the rest of the system.<br><br>



#**Activity 0803**<br>
**Description:** Does the list in the to-do list app meet the expectations of Material Design? Summarize findings.<br>
 In some ways the to-do list resembles a single list configuration from Material Design, however,
I want to say no it does not meet the expectations of Material Design. If my understanding is correct the Material Design list is more of a multi-layered collection of components working together as a single larger more complex component (the list), compared to the to-do list app where the list was mainly a view component. This makes them very different even if they are similar visually and in function, the Modular nature of the Material Design list makes it more versatile and adaptable to use.<br><br>


#**Activity 0901: **<br>
**Description:** Write a paragraph or two on your process portfolio summarizing your understanding of Room, its main components and how they relate to one another.<br>
Room runs on top of SQLite and provides a level of abstraction that facilitates easier and more effective access to the database, and benefit from new capabilities such as compile time verification of SQL queries. Commonly Room is used to cache data to allow access to it when offline.<br>
It has 3 major parts, the data to be stored, the database itself and the DAOs which provides the means for modifying the database and handling the data to be transferred back and forth between an app and the database.<br><br>


#**Activity 0902**<br>
**Description:** Briefly summarize what you've learned about fragments in your portfolio.<br>
Fragments are a type of container basically and have their own scope and life cycle but are essentially still a process of the parent activity but they can be swapped out like spare parts to meet current requirements.

#**Activity 1002**<br>
**Description:** Use your process portfolio to summarize some of the main concerns you should consider when implementing notifications in your app.<br> 
- Being aware of the rate limit applied by android to notification so the system doesn't drop any information after too many notifications pass the rate limit.
- The importance level of the notifications.
- Reusing notifications
- Not annoying the user, keeping notifications appropriate.
- Lock screen notifications showing sensitive or private information.

#**Activity 1003**<br>
**Description:** Summarize the most important practices and considerations relating to notifications on your process portfolio.<br> Ensuring appropriate notifications appear in the right context. Such as a heads up display notification for things the require the users immediate attention.

#**Activity 1101**<br>
**Description:**Chapter 9 presents a variety of animation types for various purposes. Use a table on your process portfolio to enumerate all animation types presented and to briefly describe each.<br>
Type | Description
---- | -----------
Property Animation | Property animations use an Animator to modify properties of the target object like the color or transparency over a set amount of time and are defined in XML.
View Animation | View animations can be subset into Tween Animations that fill in the numbers between key points on a timeline, or they can be Frame animations which are a sequence of images shown to give the illusion of a singular moving entity.

#**Activity 1103**<br>
**Description:**What have you learned about the principles of designing for motion in smartphone apps? Summarize your thoughts on your process portfolio.<br>
Motion can do a lot, grab attention, direct attention, communicate information, highlight actions and can be used in many different ways to reinforce a scope of hierarchy in an app while not being limited to that use. Feedback and state communication are other useful ways motion can be used outside of supporting hierarchy.
