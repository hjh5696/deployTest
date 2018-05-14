fastlane documentation
================
# Installation

Make sure you have the latest version of the Xcode command line tools installed:

```
xcode-select --install
```

Install _fastlane_ using
```
[sudo] gem install fastlane -NV
```
or alternatively using `brew cask install fastlane`

# Available Actions
## Android
### android test
```
fastlane android test
```
Runs all the tests
### android bump_version_code
```
fastlane android bump_version_code
```
bump version code
### android beta
```
fastlane android beta
```
Deploy a new internal version to the Google Play Store
### android deploy
```
fastlane android deploy
```
Deploy a new version to the Google Play
### android increase_build_number_and_push_to_beta
```
fastlane android increase_build_number_and_push_to_beta
```


----

This README.md is auto-generated and will be re-generated every time [fastlane](https://fastlane.tools) is run.
More information about fastlane can be found on [fastlane.tools](https://fastlane.tools).
The documentation of fastlane can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
