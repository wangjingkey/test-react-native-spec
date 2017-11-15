# test-react-native-spec

examples for pod react from https://github.com/fishmwei/react-native-spec.git

## Steps

### add repo
`pod repo add fishmwei https://github.com/fishmwei/react-native-spec.git`

### eidt podfile
```ruby

source 'https://github.com/fishmwei/react-native-spec.git'

def podreact
  pod 'yoga', '0.49.3.React'
  pod 'React', '~>0.49.3'
  pod 'React/Core', '~>0.49.3'
  pod 'React/CxxBridge', '~>0.49.3'
  pod 'React/RCTText', '~>0.49.3'
  pod 'React/RCTNetwork', '~>0.49.3'
  pod 'React/RCTWebSocket', '~>0.49.3'
  pod 'React/RCTImage', '~>0.49.3'
  pod 'React/DevSupport', '~>0.49.3'
  pod 'React/jschelpers', '~>0.49.3'
  pod 'React/cxxreact', '~>0.49.3'
  pod 'React/ART', '~>0.49.3'
  pod 'React/RCTActionSheet', '~>0.49.3'
  pod 'React/RCTAnimation', '~>0.49.3'

  pod 'React/RCTBlob', '~>0.49.3'
  pod 'React/RCTCameraRoll', '~>0.49.3'
  pod 'React/RCTGeolocation', '~>0.49.3'

  pod 'React/RCTPushNotification', '~>0.49.3'
  pod 'React/RCTSettings', '~>0.49.3'
  pod 'React/RCTVibration', '~>0.49.3'
  pod 'React/fishhook', '~>0.49.3'
  pod 'React/RCTLinkingIOS', '~>0.49.3'
   
  pod 'DoubleConversion', '1.1.5'
  pod 'GLog', '0.3.4'
  pod 'Folly', '2016.09.26.00' 
  pod 'boost', '1.63.0'
end

target 'TestRN493' do
  # Uncomment the next line if you're using Swift or would like to use dynamic frameworks
  # use_frameworks!

  podreact
end

```
then execute command `pod install` in terminal  

### run 
run code ...
