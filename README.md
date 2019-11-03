# AR Store Shop


## [Demo](https://drive.google.com/open?id=1yO8KbxmN-wrvnoNnCXHpylhwH5JiO_7M)


### Pre-Requisites: Android API 28 or Android Pi or higher.
## Sample Demo Screenshots:


<img src="https://github.com/anvitha-jain/AR_Store/blob/master/im1.jpg" height="350" width="200">

![1](https://github.com/anvitha-jain/AR_Store/blob/master/im1.jpg =20x30)

![2](https://github.com/anvitha-jain/AR_Store/blob/master/im2.jpg)

![3](https://github.com/anvitha-jain/AR_Store/blob/master/im3.jpg)

![4](https://github.com/anvitha-jain/AR_Store/blob/master/im4.jpg)

![5](https://github.com/anvitha-jain/AR_Store/blob/master/im5.jpg)

![6](https://github.com/anvitha-jain/AR_Store/blob/master/im6.jpg)

![7](https://github.com/anvitha-jain/AR_Store/blob/master/im7.jpg)

![8](https://github.com/anvitha-jain/AR_Store/blob/master/im8.jpg)

![9](https://github.com/anvitha-jain/AR_Store/blob/master/im9.jpg)

![10](https://github.com/anvitha-jain/AR_Store/blob/master/im10.jpg)


## Setup and Run Instructions: 

1. Download AR-Core from Google Play Store.
2. Build the application on Android Studio.
3. Run the application. 


### Other Instructions: 

1. Following are the dependencies Required in the build.gradle (Module: app) file: 

dependencies {
    implementation fileTree(dir: 'libs', include: ['*.jar']) </br>
    implementation 'com.android.support:appcompat-v7:28.0.0' </br>
    implementation 'com.android.support.constraint:constraint-layout:1.1.3' </br>
    implementation 'com.google.firebase:firebase-auth:16.0.3' </br>
    implementation 'com.google.firebase:firebase-database:16.0.1' </br>
    testImplementation 'junit:junit:4.12' </br>
    androidTestImplementation 'com.android.support.test:runner:1.0.2' </br>
    androidTestImplementation 'com.android.support.test.espresso:espresso-core:3.0.2' </br>
    implementation 'com.google.firebase:firebase-core:16.0.1' </br>
    implementation "com.google.ar.sceneform.ux:sceneform-ux:1.5.0" </br>
   //for paypal </br>
    implementation 'com.paypal.sdk:paypal-android-sdk:2.15.3' </br>
   //for text recognition using google ocr </br>
    implementation 'com.google.android.gms:play-services-vision:15.0.1' </br>
    implementation "com.google.android.gms:play-services-base:15.0.1" </br>
   //for items views </br>
    implementation 'com.android.support:recyclerview-v7:28.0.0' </br>
    implementation 'com.android.support:cardview-v7:28.0.0' </br>
    // for gif animation </br>
    compile 'pl.droidsonroids.gif:android-gif-drawable:1.2.3' </br>
}

2. Ensure that the AR images are present in the "sampledata" folder. 

3. Ensure that firebase is connected in Android Studio.

4. Ensure that the following permissions are present in the AndroidManifest.xml

 * INTERNET
 * CAMERA
 * ACCESS_NETWORK_STATE
 * WRITE_EXTERNAL_STORAGE
 * READ_EXTERNAL_STORAGE
