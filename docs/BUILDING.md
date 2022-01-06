# Building the app

## Table of contents
1. [Building iOS](#building-ios)
1. [Building Android](#building-android)

## Building iOS
> **NOTE:** This step can only build an iOS-`.app` file that can only be used on a simulator!

Making an iOS build can be done by running the following command `yarn ios.release.sim.build`.
The output can be found in [`../ios/Build/Products`](../ios/Build/Products)

## Building Android
> The [keystore](../android/app/sLSwagLab.keystore) is saved in this project. This is normally not a good advice, but this project isn't publishing to the Play Store so all data is filled with dummy data.
> This allows us to make a signed build.

Making an Android build can be done by running the following command `yarn android.release`. It will take a few minutes to build a release.

The output can be found in `android/app/build/outputs/apk/release/app-release.apk`
