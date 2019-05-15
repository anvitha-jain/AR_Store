# AR Shop Store


### Pre-Requisites: Android API 28 or Android Pi or higher.

## Setup and Run Instructions: 

1. Download AR-Core from Google Play Store.
2. Build the application on Android Studio.
3. Run the application. 


### Other Instructions: 

1. Following are the dependencies Required in the build.gradle (Module: app) file: 

dependencies {
    implementation fileTree(dir: 'libs', include: ['*.jar'])
    implementation 'com.android.support:appcompat-v7:28.0.0'
    implementation 'com.android.support.constraint:constraint-layout:1.1.3'
    implementation 'com.google.firebase:firebase-auth:16.0.3'
    implementation 'com.google.firebase:firebase-database:16.0.1'
    testImplementation 'junit:junit:4.12'
    androidTestImplementation 'com.android.support.test:runner:1.0.2'
    androidTestImplementation 'com.android.support.test.espresso:espresso-core:3.0.2'
    implementation 'com.google.firebase:firebase-core:16.0.1'
    implementation "com.google.ar.sceneform.ux:sceneform-ux:1.5.0"
   //for paypal
    implementation 'com.paypal.sdk:paypal-android-sdk:2.15.3'
   //for text recognition using google ocr
    implementation 'com.google.android.gms:play-services-vision:15.0.1'
    implementation "com.google.android.gms:play-services-base:15.0.1"
   //for items views
    implementation 'com.android.support:recyclerview-v7:28.0.0'
    implementation 'com.android.support:cardview-v7:28.0.0'
    // for gif animation
    compile 'pl.droidsonroids.gif:android-gif-drawable:1.2.3'
}

2. Ensure that the AR images are present in the "sampledata" folder. 

3. Ensure that firebase is connected in Android Studio.

4. Ensure that the following permissions are present in the AndroidManifest.xml

    <uses-permission android:name="android.permission.INTERNET" />
    <uses-permission android:name="android.permission.CAMERA" />
    <uses-permission android:name="android.permission.ACCESS_NETWORK_STATE" />
    <uses-permission android:name="android.permission.WRITE_EXTERNAL_STORAGE" />
    <uses-permission android:name="android.permission.READ_EXTERNAL_STORAGE" /> 


