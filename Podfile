source 'https://github.com/iwooltd/specs.git'
source 'https://github.com/CocoaPods/Specs.git'

xcodeproj 'PodAdapter.xcodeproj'

#ignore warnings from pods
inhibit_all_warnings!
use_frameworks!

target :PhoneUmbrellaFramework do
  platform :ios, '8.0'
  link_with 'PhoneUmbrellaFramework'
  
  # User app
  pod 'DZImageEditing', '~> 1.0'
  pod 'CardIO', '~> 5.0.1'
  pod 'JazzHands', '~> 0.2'
  pod 'TPKeyboardAvoiding'
  pod 'mopub-ios-sdk'
  
  # TRBAPIClient
  pod 'FBSDKLoginKit', '~> 4.3'
  pod 'FXKeychain', '~> 1.5'
  pod 'Overcoat', '~> 3.0'
  pod 'Overcoat/ReactiveCocoa', '~>3.0'
  pod 'AFNetworking', '~> 2.5.4'
  
  # TRBUIKit
  pod 'pop', '~> 1.0'
  
  #TRBSocialClient
  pod 'AFOAuth2Manager', '~> 2.2'
end

target :PhoneUmbrellaTestFramework do
    platform :ios, '8.0'
    link_with 'PhoneUmbrellaTestFramework'
    
    pod 'TUDelorean'
    pod 'Expecta+Snapshots', '~> 1.3'
end

target :WatchUmbrellaFramework do
  platform :watchos, "2.0"
  link_with 'WatchUmbrellaFramework'
end

target :WatchUmbrellaTestFramework do
    platform :watchos, "2.0"
    link_with 'WatchUmbrellaTestFramework'
end