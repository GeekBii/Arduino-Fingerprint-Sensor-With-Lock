# Arduino Fingerprint Sensor With Lock
### Using one of these two fingerprint readers is easy with an Arduino

## See YouTube video https:///www.YouTube.com/ralphbacon video #146
(Direct link to video: )

### LCSC - More Asian Brands, Lower Prices, 4 Hours Ready for Shipping  
#### China's leading Electronics Components source - 113 Authorized Brands, 174 International Brands, 555 Made in Asia Brands  
#### LCSC has been confirmed by ISO 9001: 2015.  
#### Shop: https://lcsc.com/

I'm using two different (but very similar) fingerprint readers here, an R307 and a slightly different, Adafruit-compatible version. I show here how to enrol fingerprints using the Windows (only) demo program and then read them back on the Arduino to power a small door lock.

You can do _everything_ on the Arduino, of course, but it makes sense to use the Windows' utility IDE first to ensure it all hangs together. I show you how to do this, all very easy once you have chosen a _suitable Arduino UNO to use._

#### Suitable Arduino Uno?
My original attempts at getting my R307 fingerprint reader working (over two years ago) came to nothing. Now, thanks to some comments in the Adafruit article I figured I needed an Arduino UNO with a "proper" USB to Serial converter, such as the µController found on the original Arduino Uno (an ATMega16U2). Luckily, I had an old, possibly cloned version of that board and it all sprang into life, so very easily!

#### Door locks
I didn't amend the Adafruit demo sketch for the Arduino to read the fingerprints, other than to power up the door lock if it found a matching fingerprint. There are dozens of different, 12v door locks out there - check what you need and how to fix it before buying one! Also, bear in mind that these locks take quite some current (the small one I used needs just under 400mA).

The Adafruit library that I used is also in my GitHub so we know that version will work, but it's always worth checking to see whether an updated version is available that might add features, correct bugs or make it compatible with other hardware.

Adafruit invests time and resources providing this open source code, please support Adafruit and open-source hardware by purchasing products from Adafruit!

### LINKS (some may be affiliate links that help my channel)

R307 fingerprint reader as used in the demo:  
https://www.banggood.com/R307-Optical-Fingerprint-Reader-Module-Sensor-Finger-Detection-Function-p-1258914.html?p=FQ040729393382015118&utm_campaign=25129675&utm_content=3897

R307 fingerprint sensor also available from Amazon, not bad prices:  
UK: https://amzn.to/2Eq0J8F
USA: https://amzn.to/2VDrhJu

Adafruit-like (possibly the same) fingerprint reader, as used in the demo:  
https://www.banggood.com/Fingerprint-Reader-Identification-Module-Fingerprint-Lock-Optical-Strip-Sensing-for-Arduino-Fingerpr-p-1343470.html?p=FQ040729393382015118&utm_campaign=25129675&utm_content=3897

The official Adafruit fingerprint reader (currently out of stock (May 2019) but will doubtless return):  
https://www.adafruit.com/product/751  

Small drawer lock, as used in the demo, 12v 400mA (approx):  
https://www.banggood.com/12V-DC-Cabinet-Door-Drawer-Electric-Lock-Assembly-Solenoid-Lock-27x29x18mm-p-1048590.html?p=FQ040729393382015118&utm_campaign=25129675&utm_content=3897

Electric door lock example (not used in the demo):  
https://www.banggood.com/Door-Electric-Strike-Lock-NO-Narrow-type-Electronic-Control-12V-DC-p-1040055.html

