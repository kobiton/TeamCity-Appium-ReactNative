# TeamCity-TestFlight-Appium-ReactNative
Guidance on integrating Kobiton service into the mobile app build pipeline: TeamCity, TestFlight, Appium and ReactNative.

If you are using:
+ TeamCity to build app
+ TestFlight for keeping the daily app build
+ Appium to write the automation test
+ Reactnative to write app

Kobiton is a mobile cloud platform that enables users to perform manual or automated testing on iOS and Android devices. This guide will demonstrate how to configure Travis CI to get the latest build on Testflight and run Appium automation tests on Kobiton Test Cloud service.

## Table of contents

1. This guide will demonstrate [how to trigger a TeamCity build from a push to GitHub](1-trigger-TeamCity.md)
2. This guide will demonstrate [how to run automation tests on your app with the Kobiton service](2-run-automation-test.md)