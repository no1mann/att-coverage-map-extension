# AT&T Coverage Map Chrome Extension
Enable's mmWave coverage on the official AT&amp;T Coverage Map on Chromium-Based Browsers. I'm currently in the process of getting the extension approved on the Chrome Web Store, but given the extension permissions, that could take weeks.

# Background
Verizon has been the only carrier to show mmWave coverage on their coverage map. After looking at the code for AT&T's Coverage Map, I found out that AT&T has mmWave data, but they are forcibly  hiding it. This extension enables that mmWave coverage and displays it on their coverage map.

# How To Install Locally
1. Click the green "Code" button at the top of page and click "Download ZIP"
2. Extract the contents of the ZIP file to a folder
3. In Chrome, type in this into the address bar
> chrome://extensions
4. Turn on "Developer mode" in the top, right hand side of the screen
5. Click the "Load unpacked" button at the top, left of the screen
6. Select the folder you just unzipped (it should contain a mainfest.json file)
7. You then should see "AT&T Coverage Map - mmWave" in your extensions list. Go to the official 5g AT&T coverage map and you should see mmWave coverage

# Disclaimer
All mmWave data comes directly from AT&T. I can not speak for the validity of the coverage and I'm unaware of the last time they updated it.