## Next Projects, Miscellaneous stuff

### LottoScan 🍀

Since there is no such app in the App Store I don't want to reveal the code just yet. The application was supposed to detect contents of Lotto and Mini Lotto lottery tickets, download draw results from Lotto server and calculate winnings. It utilizes ML Kit's Vision. As you can guess, extracting interesting fragments from detected text in this case is tricky. The worst part is detecting game type. I tried to train model with Create ML using prepared game logos (10 of each type) but I failed miserably.<br>

![Demo](Images/lottoscan_01.gif) <br>
![Demo2](Images/lottoscan_02.gif) <br>

ResultsView composed using SwiftUI can look like this: <br>
<img src="Images/lottoscan_swiftUI.png" height="400"/>

#### Status

Suspended. I am noodling around with Apple's Vision and SwiftUI now. It works, but ML Kit's Vision is better and much more stable so extracting ticket contents will be even more tricky.

### Overlays 🗺

Slightly modified (for educational purposes) raywenderlich.com's "MapKit Tutorial: Overlay Views" (first part) <br>
You can load custom overlay image and corresponding JSON file produced by Maptiler app. <br>
I added user's position tracking and slider to change opacity of the overlay. <br>
<div align="center">
<img src="Images/overlays_01.png" height="400" hspace="20" />
<img src="Images/overlays_02.png" height="400" hspace="20"/>
<img src="Images/overlays_03.png" height="400" hspace="20"/>
</div> 

### Eyes To Words - Improve communication with people suffering from ALS 👀 <br>

I wanted to develop an application that would convert the sequences of the eye movements into letters and then into words according to the system shown in this [video](https://www.youtube.com/watch?v=DL_ZMWru1lU) <br>
It turns out that the better solution would be to use Tobii Eye Tracker or Arduino / Raspberry Pi with respective sensors 

### Game of Dice - an Iphone version of the dice game from Kingdom Come Deliverance 🎲 <br>

Currently I am getting familiar with [this](https://developer.apple.com/documentation/coreml/understanding_a_dice_roll_with_vision_and_object_detection) sample code and somehow trying to fit in one round game code  <br>

### ...
