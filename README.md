Title
Zero Notification Fullscreen Application Spoofing Via Facebook for android and Facebook messanger
Vuln Type
Other
Product Area
Facebook - Android
Facebook Messanger -Android
Description/Impact
The listed Meta applications and possibly others DO NOT render any form of notification to the user when they enter full-screen mode.

This vulnerability allows a remote attacker to spoof any application/browser via the apps in-app browser. From which an attacker can render/spoof anything such as the facebook apps URL bar, lock-screens or even full applications.
Repro Steps
Mobile app version: Messanger 421.0.0.12.61, Facebook 427.0.0.31.63

(Simple test with attached w3schools fullscreen css example html. Will send the html/js/css from the example video if it is needed)

1. Host test html file (or https://www.w3schools.com/cssref/tryit.php?filename=trycss_sel_fullscreen)
2. Send to self or test account
3. Open link
4. Click "Open Fullscreen Button"
5. No fullscreen notification
