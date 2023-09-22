# android-apple-shazamkit

Publish Apple ShazamKit for Android to jitpack.io

https://developer.apple.com/download/all/?q=Android%20ShazamKit
https://developer.apple.com/shazamkit/android/

Add it to your build.gradle with:
```gradle
allprojects {
    repositories {
        maven { url "https://jitpack.io" }
    }
}
```

and:

```gradle
dependencies {
    implementation "com.github.kusstar:apple-shazamkit:0.1.0"
}
```