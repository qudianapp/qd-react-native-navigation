# qd-react-native-navigation

## Getting started

`$ npm install qd-react-native-navigation --save`

### Mostly automatic installation

`$ react-native link qd-react-native-navigation`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `qd-react-native-navigation` and add `RNNavigation.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNNavigation.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainApplication.java`
  - Add `import com.qudian.react_navigation.RNNavigationPackage;` to the imports at the top of the file
  - Add `new RNNavigationPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':qd-react-native-navigation'
  	project(':qd-react-native-navigation').projectDir = new File(rootProject.projectDir, 	'../node_modules/qd-react-native-navigation/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':qd-react-native-navigation')
  	```


## Usage
```javascript
import RNNavigation from 'qd-react-native-navigation';

// TODO: What to do with the module?
RNNavigation;
```
  