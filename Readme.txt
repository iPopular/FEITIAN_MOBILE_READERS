Get Start:

Download demo application from Appstore:
https://itunes.apple.com/us/app/smartcard-reader/id525954151?mt=8

Download demo application APK file for Android:
https://github.com/FeitianSmartcardReader/FEITIAN_MOBILE_READERS/raw/master/Android%20SDK/BIN/FTReaderStandard.apk


History:
2018/01/19
	- Update demo app, demo update to 2.0.1
	    1. Using CoreBluetooth API to scan the BLE readers and through the UUID rules to do filter
	    2. Using a thread to check the Bluetooth broadcast information each 1s, to make the BLE reader list up to date
	    3. Output the log into demo App, the user can connect their iOS device into a computer, through iTunes to export the log, this improve help us to locate the issues
	    4. Fix issue for display the battery status of Bluetooth Smart reader (bR500BLE,bR301BLE)	
	- Update iOS SDK, new lib is 3.5.40, changed debugging flag, to void compilation conflicts with client Libraries
2018/12/18
	- Update iOS SDK, new lib is 3.5.39, the change log can find in iOS folder -> readme
2018/12/04
	- Update iOS SDK, a minor update of demo code
2018/10/15
	- Update iOS SDK, add iReader basic demo to github
2018/10/12
	- Update iOS SDK, release version is 3.5.29
	- Update iOS OC Demo code, support all feitian reader, and improve UI
	- 3.5.29 support Autopair or manual pair with bR301BLE and bR500
	- 3.5.29 support get battery status for bR500, bR301BLE not support yet, we are working to add this feature
2018/6/25
	- Update iOS SDK, release version is 3.5.16
	- After call SCardEstablishContext, the scan thread will start scan the BLE device
	- The 3.5.16 lib will automaticly do scan and connect the closest reader
	- Imrpove the thread safe
	- ScardDisconnect will only disconnect smart card
	- Merger iR301 and bR301 SDK(v1.32.5) into combo SDK
	- Fixed few bugs for BLE reader
2018/4/12
	- Update Android SDK, release combo Android SDK, support R301,R502,vR504,iR301,bR301,bR301BLE,bR500 
	- Will update iOS SDK recently, the lib is working on improve, should be upgrade in two weeks.
2018/1/22 
	- Update Lib to 3.5.9, modify features of bR301BLE and bR500, modify SCardListReader API, this is debug version, and not release yet, only for test, once release will update GIT, thanks for your support.
2018/1/15 
	- Update iOS lib to 3.5.8 and Update demo code(put two demos in one SDK)
