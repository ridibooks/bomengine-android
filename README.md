# bomengine-android
BOM parser engine for Android platform

## Getting started
This library is distributed by [jitpack](https://jitpack.io).

You should add jitpack maven repository to build.gradle file of your root project.

```
allprojects {
    repositories {
        jcenter()
        maven { url "https://jitpack.io" }
    }
}
```

Then you can include this library by adding dependency script to build.gradle file of your project.

```
dependencies {
    ...
    compile 'com.github.ridibooks:bomengine-android:1.0' 
    ...
}
```