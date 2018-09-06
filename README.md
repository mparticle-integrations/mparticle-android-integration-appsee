## Appsee Kit Integration


This repository contains the [Appsee](https://www.appsee.com/) integration for the [mParticle Android SDK](https://github.com/mParticle/mparticle-android-sdk).

### Adding the integration

1. Add the kit dependency to your app's build.gradle:

    ```groovy
    dependencies {
        implementation 'com.mparticle:android-appsee-kit:5+'
    }
    ```
2. Follow the mParticle Android SDK [quick-start](https://github.com/mParticle/mparticle-android-sdk), then rebuild and launch your app, and verify that you see `"Appsee detected"` in the output of `adb logcat`.
3. Reference mParticle's integration docs below to enable the integration.

### License

[Apache License 2.0](http://www.apache.org/licenses/LICENSE-2.0)
