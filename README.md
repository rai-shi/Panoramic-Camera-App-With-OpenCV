# updates from rai_shi for forked project
The project is forked from [@YarikSOffice OpenCV-Playground](https://github.com/YarikSOffice/OpenCV-Playground) project for the Windows Programming lecture assignment. The project is contributed with UI development and its functionalities.

## Project Information
This project is the development of image stitching as a panoramic view with Kotlin and OpenCV. There was a page for image scanning and stitching in the previous version. In addition to project,
- a camera screen is added,
- panoramic shooting is added to camera screen
- an area has been added where various filters can be applied to photos.

#### Here is the part that also exists in the project before ( "Go App" button is added)

<img src="https://github.com/rai-shi/Panoramic-Camera-App-With-OpenCV/blob/master/preview-ayse/panaromic-example.gif?raw=true" height="500px">

#### Here is the camera screen page. 
- There is a camera switch button which doesn't work.
- On the bottom left there is a button for panoramic image stitching. The panoramic image is directly saved to the gallery after picking the images.
- On the bottom middle there is a button for camera shooting. Shooted image is directly saved to the gallery.
- On the bottom right is a editing button, which doesn't work properly.

<img src="https://github.com/rai-shi/Panoramic-Camera-App-With-OpenCV/blob/master/preview-ayse/camera-example.gif?raw=true" height="500px">

## Dependencies
- Kotlin version = ```ext.kotlinVersion = '1.9.25'```
- Android Gradle version = ```'com.android.tools.build:gradle:8.0.1'```
- Java version = ```JavaVersion.VERSION_17``` 
- Other libraries,
```
dependencies {
    implementation 'androidx.appcompat:appcompat:1.0.2'
    implementation 'com.squareup.picasso:picasso:2.5.2'
    implementation "com.github.chrisbanes:PhotoView:2.3.0"

    implementation 'io.reactivex.rxjava2:rxandroid:2.1.1'
    implementation 'io.reactivex.rxjava2:rxjava:2.2.11'

    implementation "org.jetbrains.kotlin:kotlin-stdlib-jdk7:$kotlinVersion"

    implementation 'org.bytedeco:javacv:1.4.4'
    implementation 'org.bytedeco.javacpp-presets:opencv:4.0.1-1.4.4:android-arm64'
    implementation 'org.bytedeco.javacpp-presets:opencv:4.0.1-1.4.4:android-arm'
    implementation 'org.bytedeco.javacpp-presets:opencv:4.0.1-1.4.4:android-x86'


    implementation 'androidx.camera:camera-core:1.0.0'
    implementation 'androidx.camera:camera-camera2:1.0.0'
    implementation 'androidx.camera:camera-lifecycle:1.0.0'
    implementation "androidx.camera:camera-view:1.0.0-alpha23"

    implementation 'pub.devrel:easypermissions:3.0.0' 

    implementation 'com.github.mukeshsolanki:photofilter:1.0.2'
}
```
- Min SDK Version = ```minSdkVersion 21```
- Target SDK Version = ```targetSdkVersion 30```
- Build system is Gradle.

## Known Issues or Limitations

- Camera switching button wasn't developed, it is just an icon.
- When pressing filtering button the editing page can open but
  - Swapping area doesn't work.
  - App fails after pressing the directory icon to pick an image.
 

I am not a mobile app developer and I never used Kotlin or Java so that's all I could do for the assignment. So please be aware that the project is not what you are searching for. But if you decide to contribute for developed more this project, I tried to write clean code but it may look trash to you :upside_down_face:. So good luck!

## Contribute
Feel free to contribute!
Contact if you want aysenurtak1@gmail.com 

:star2::star2:

