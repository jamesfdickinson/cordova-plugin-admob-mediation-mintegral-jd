[mintegral](https://firebase.google.com/docs/admob/android/mediation-networks) for [mintegral](https://developers.facebook.com/docs/audience-network/getting-started)

Use with cordova admob plugins such as [cordova-admob-jimmy](https://github.com/jamesfdickinson/admob-google-cordova-clean)

[CHANGELOG](https://github.com/jamesfdickinson/cordova-plugin-admob-mediation-mintegral-jd/blob/master/CHANGELOG.md)

## Setup ##

In your project-level settings.gradle.kts file, add the following repositories:

````
dependencyResolutionManagement {
  repositories {
    google()
    mavenCentral()
    maven {
      url = uri("https://dl-maven-android.mintegral.com/repository/mbridge_android_sdk_oversea")
    }
  }
}
````
## Installation ##

In your application project directory:

```bash
cordova plugin add cordova-plugin-admob-mediation-mintegral-jd
```

## Usage ##

[Set Up Admob Mediation](https://support.google.com/admob/answer/3124703?hl=en)

Keep using the API of your favorite Admob cordova plugin!

## Licence ##

The MIT License