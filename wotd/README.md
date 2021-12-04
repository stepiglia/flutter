# How I learnt to make apps in Flutter

https://medium.com/r/?url=https%3A%2F%2Flevelup.gitconnected.com%2Fcreate-a-cross-platform-mobile-app-with-flutter-in-under-5-minutes-ff3f4655670 

https://www.youtube.com/watch?v=TCwXGB6Olt4

When you have xcode installs you can open the simulator for iOS via terminal with:

```
open a- Simulator 
```

You cd in the directory that you want to create the app in

```
create wotd_app
```

Now you cd in the app and open the app (it will open in the simulator) 

```
flutter run
```

To stop it use 
```
ctrl + c
```

## To use an actual iOS device for testing 

sudo gem install cocoapods
pod setup

Then to the folder of your app > iOs, select the file 

`runner.xcworkspace`

Drag it on top of the xcode icon in dock to open it

Once opened, you'll see a "runner file" . Change the Team > Add an Account...

![image](https://user-images.githubusercontent.com/16845540/144719332-dbb43608-feb7-466e-bdfb-aaf142b6b459.png)

You can now run the project on your device after trusting the device. 


## To use an actual Android device 

Download it from the website and install it. 

You need to set up Developer options + USB debugging on your Android. Plug it in and 
`flutter run`

# To use an actual Android emulator 

Open android studio. Open AVD manager where you can create a virtual device. 

![image](https://user-images.githubusercontent.com/16845540/144719683-a961ba9e-f840-4843-9ace-58e63b2869f3.png)

The you can 
