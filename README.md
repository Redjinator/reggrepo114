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
<br>






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
- android.software.app_widgets.<br>


#**ACTIVITY 0202** <br>
For this activity I read the article about the principles of sound here [Principles of Sound](https://material.io/design/sound/about-sound.html#principles)
where the topic goes over how sound can provide positive feedback for a product.<br>

With provided examples the article discusses how different sounds can influence the emotional state of the user which makes sense, if colors can do it, then surely sound can as well. It's not something I've really put a lot of time into before reading the article as my own projects have not required any sound up to this point.

#**There are 3 types of sounds mentioned in the article**<br>
- Sound Design
- Music
- Voice

While the article continues to describe the sound types in more detail, it basically approaches sound much in the same that other visual design principles are, and that is to use sound to tell a story,  provide hierarchy, and increase the efficiency of communication and information in an intuitive way. 
<br>





#**ACTIVITY 0301** <br>
**Description:** Try to identify all the activities or screens in a frequently used app and attempt to catagorize them in a meaningful way.

**App Choosen:** Bitcoin Checker<br>
![Bitcoin Checker App](/btcChecker_3screens.png)<br>

There are 3 screen/activities for this app.<br>
- The first screen is where you view your list of coins and their current prices. This is intented to be the main activity where you'll spend most of your time. 
- Plus button at the top of the 1st screen will bring you to the second activity/screen where you can choose from a list of exchanges.
- Once you've choosen an exchange on the 2nd screen, your brought to a 3rd screen where you can decide which coin from that exchange will be in the tracking list and what currency it will be paired with. Alarms and notifications can also be configured on this screen.<br>


#ACTIVITY 0302** <br>
**Description:** Identify common android event types from chapter 3.2 that may be present in my app of choice.

**App Choosen:** Bitcoin Checker<br>

**The following events are those I am fairly confident are part of the app.**
- onLongClick()	

Event | Description
------------ | -------------
onClick() | Found on the majority buttons throughout all different activities.
onLongClick() | Fires when touching the screen.
onKey() | Fires during data entry from an on screen keyboard.
onDrag() |Fires when rearranging the stacked elements on the first screen.
Extra | There must be an event for watching price changes of external information, but I'm not finding anything on developer.android.com that seems to fit this criteria.






