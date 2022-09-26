# AndroidBle
Android Ble Connectivity Manager

Android Manifest :

Recommended settings for the Android Manifest

```
<uses-permission
    android:name="android.permission.BLUETOOTH"
    android:maxSdkVersion="30"/>
<uses-permission
    android:name="android.permission.BLUETOOTH_ADMIN"
    android:maxSdkVersion="30"/>
<uses-permission
    android:name="android.permission.BLUETOOTH_SCAN"
    android:minSdkVersion="30"/>
<uses-permission
    android:name="android.permission.BLUETOOTH_CONNECT"
    android:minSdkVersion="30"/>
<uses-permission
    android:name="android.permission.ACCESS_FINE_LOCATION"/>
<uses-permission
    android:name="android.permission.ACCESS_COARSE_LOCATION"/>
<uses-permission
    android:name="com.google.android.things.permission.MANAGE_BLUETOOTH"/>
<uses-feature
    android:name="android.hardware.bluetooth_le"
    android:required="true"
    tools:ignore="UnusedAttribute"/>
```
        
Work very fine with Silabs BGX13P BGX22P
