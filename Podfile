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
  pod 'DZImageEditing', :git => 'https://github.com/harryworld/DZImageEditing', :commit => 'e9eb958409b9c50ac37e1f2a307f1ddb03578bcb'
  pod 'TPKeyboardAvoiding'
  pod 'mopub-ios-sdk'
  
  # TRBAPIClient
  pod 'FBSDKLoginKit', '~> 4.5.1'
  pod 'FXKeychain', '~> 1.5'
  pod 'Overcoat', '~> 3.0'
  pod 'Overcoat/ReactiveCocoa', '~>3.0'
  pod 'AFNetworking', '~> 2.5.4'
  
  # TRBUIKit
  pod 'pop', '~> 1.0'
  pod 'MBProgressHUD', '~> 0.9.1'
  pod 'NUI', '~> 0.5'
  
  #TRBSocialClient
  pod 'AFOAuth2Manager', '~> 2.2'
end

target :PhoneUmbrellaTestFramework do
    platform :ios, '8.0'
    link_with 'PhoneUmbrellaTestFramework'
    
    pod 'TUDelorean'
end

target :WatchUmbrellaFramework do
  platform :watchos, "2.0"
  link_with 'WatchUmbrellaFramework'
end

target :WatchUmbrellaTestFramework do
    platform :watchos, "2.0"
    link_with 'WatchUmbrellaTestFramework'
end