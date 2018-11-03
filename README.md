# iNav-UW

Notes: to load the map and have everything works, you need to be physically in the building Engineering 1410 since the location data needs to be in that area. If you want to test it, you can go to the second floor of Engineering 1410 where we do most of our testing.

Then you can do the following to make sure everything works:
1. `pod isntall`: this will get all the cocapod files install into your directory
2. `open inav-uw.xcworkspace`
3. Run this in your device. Note: a simulator will not work since this require location data so you would have to run it on a physical device
4. Move around and wait for the app to locate you. If you are not in the building, the app will not load the map.
