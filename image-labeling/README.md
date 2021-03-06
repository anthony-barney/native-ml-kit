# @react-native-ml-kit/image-labeling

React Native On-Device Image Labeling w/ Google ML Kit

> **⚠ WARNING: Don't use this in production.**  
> This package is still in alpha release, so it's not recommended to use it in production until it's fully stable, however using it for testing purposes is helpful.

## Getting started

`npm install @react-native-ml-kit/image-labeling --save`

### Linking

#### React Native > 0.59

[CLI autolink feature](https://github.com/react-native-community/cli/blob/master/docs/autolinking.md) links the module while building the app.

#### React Native <= 0.59

`react-native link @react-native-ml-kit/image-labeling`

### Installing Pods

On iOS, use CocoaPods to add the native RNMLKitImageLabeling to your project:

`npx pod-install`

## Usage

```javascript
import ImageLabeling from '@react-native-ml-kit/image-labeling';

const labels = await ImageLabeling.label(imageURL);
```
