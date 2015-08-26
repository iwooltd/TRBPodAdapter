source 'https://github.com/iwooltd/specs.git'
source 'https://github.com/CocoaPods/Specs.git'

xcodeproj 'PodAdapter.xcodeproj'

#ignore warnings from pods
inhibit_all_warnings!
use_frameworks!

target :DummyiOS do
  platform :ios, '8.0'
  link_with 'DummyiOS'
  # TRBAPIClient
  pod 'FBSDKLoginKit', '~> 4.3'
  pod 'FXKeychain', '~> 1.5'
  pod 'pop', '~> 1.0'
  
  #TRBSocialClient
  pod 'AFOAuth2Manager', '~> 2.2'
  
  #TRBAPIClient
  pod 'Overcoat', '~> 3.0'
  pod 'Overcoat/ReactiveCocoa', '~>3.0'
  
  #TRBCore
  pod 'AFNetworking', '~> 2.5.4'
  
  #testing
  pod 'TUDelorean'
  pod 'Expecta+Snapshots', '~> 1.3'
end

target :DummywOS do
  platform :watchos, "2.0"
  link_with 'DummywOS'
end