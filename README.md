# Instructions for porting for MS App Center

- Clone the Repo:
  > `npx create-react-native-app -t https://github.com/amandeepmittal/react-native-examples/tree/master/shared-element-transitions`
- Remove Expo:
  > `expo eject`
- Install MS App Center SDK
  > `yarn add appcenter appcenter-analytics appcenter-crashes --save-exact`
  > `cd ios`
  > `pod install`
  - Create a "AppCenter-Config.plist" file within the ios folder
  - open the xcode project file, add the "AppCenter-Config.plist" file, and do the following:
<img width="672" alt="Screen Shot 2564-12-24 at 13 31 41" src="https://user-images.githubusercontent.com/62129193/147325045-b9d75da5-6b20-4ed7-804c-fdfb845252cf.png">
