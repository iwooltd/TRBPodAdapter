source 'https://github.com/iwooltd/specs.git'
source 'https://github.com/CocoaPods/Specs.git'

project 'PodAdapter.xcodeproj'

#ignore warnings from pods
inhibit_all_warnings!
use_frameworks!

target :PhoneUmbrellaFramework do
  platform :ios, '12.0'
  #PhoneUmbrellaFramework
  
  pod 'Firebase/Core'
  pod 'Firebase/Crash'
  
  # User app
  pod 'DZImageEditing', :git => 'https://github.com/harryworld/DZImageEditing', :commit => 'e9eb958409b9c50ac37e1f2a307f1ddb03578bcb'
  pod 'TOCropViewController'
  pod 'mopub-ios-sdk'
end

target :PhoneUmbrellaTestFramework do
    platform :ios, '12.0'
    #PhoneUmbrellaTestFramework
    
    pod 'TUDelorean'
end

