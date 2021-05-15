# SmartVideo-Android-SDK
A description of this package.

## Installation

### Gradle
Add ***videoengager-sdk-release.aar*** to `libs` folder in project .

**Note**: `minSdkVersion` for the Android SDK is 21 (Android 5.0 "Lollipop").

Add the necessary libraries into your `build.gradle` file:
```
dependencies {
    implementation fileTree(dir: 'libs', include: ['*.jar','*.aar'])
    implementation 'com.google.code.gson:gson:2.8.6'  
    implementation "androidx.lifecycle:lifecycle-viewmodel-ktx:2.3.0"  
    implementation 'com.squareup.picasso:picasso:2.8'  
    implementation 'org.webrtc:google-webrtc:1.0.22270'
}
```

## Permissions

These permissions should be added to the application's `AndroidManifext.xml` file:

```
<uses-permission android:name="android.permission.INTERNET" />  
<uses-permission android:name="android.permission.CAMERA" />  
<uses-permission android:name="android.permission.RECORD_AUDIO" />  
<uses-permission android:name="android.permission.ACCESS_NETWORK_STATE" />  
<uses-permission android:name="android.permission.BLUETOOTH" />  
<uses-permission android:name="android.permission.CHANGE_NETWORK_STATE" />  
<uses-permission android:name="android.permission.MODIFY_AUDIO_SETTINGS" />    
<uses-feature android:name="android.hardware.camera" />    
<uses-permission android:name="android.permission.FLASHLIGHT"/>    
<permission android:name="android.permission.FLASHLIGHT"  
  android:permissionGroup="android.permission-group.HARDWARE_CONTROLS"  
  android:protectionLevel="normal" />  
<uses-feature android:name="android.hardware.camera.flash" android:required="false" />
```

## Usage

Please refer to our [Demo App](https://github.com/VideoEngager/SmartVideo-Android-SDK-Demo-App) for an usage example. 
