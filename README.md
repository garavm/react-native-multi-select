# react-native-multi-select

## Getting started

`$ npm install react-native-multi-select --save`

### Mostly automatic installation

`$ react-native link react-native-multi-select`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-multi-select` and add `MultiSelect.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libMultiSelect.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainApplication.java`
  - Add `import com.reactlibrary.MultiSelectPackage;` to the imports at the top of the file
  - Add `new MultiSelectPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-multi-select'
  	project(':react-native-multi-select').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-multi-select/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-multi-select')
  	```


## Usage
```javascript
import MultiSelect from 'react-native-multi-select';

// TODO: What to do with the module?
MultiSelect;
```
