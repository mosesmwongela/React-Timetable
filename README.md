# React-Timetable
A simple react-native timetable

HOW TO RUN IT

create a file local.properties in android/ with this line:=> sdk.dir = C:/Users/Moses/AppData/Local/Android/sdk

npm i

mkdir android/app/src/main/assets

react-native bundle --platform android --dev false --entry-file index.android.js --bundle-output android/app/src/main/assets/index.android.bundle --assets-dest android/app/src/main/res

react-native run-android
