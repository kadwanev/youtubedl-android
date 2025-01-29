
## Build and Install

./gradlew clean build

adb install ./app/build/outputs/apk/debug/app-universal-debug.apk

## Update master

git fetch

git co master

git merge parent/master master
