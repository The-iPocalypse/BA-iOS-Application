source 'https://github.com/CocoaPods/Specs.git'
platform :ios, '9.0'
target "BA-iOS-Application" do
	pod 'Alamofire', '~> 3.0'
	pod 'SwiftyJSON', :git => 'https://github.com/SwiftyJSON/SwiftyJSON.git'
	pod 'FormatterKit', '~> 1.8.0'
	pod 'PagingMenuController'
	pod 'MBProgressHUD', '~> 0.9.1'
	pod 'Whisper'
end

use_frameworks!

prepare_command = <<-CMD
SUPPORTED_LOCALES="['base', 'en']"
find . -type d ! -name "*$SUPPORTED_LOCALES.lproj" | grep .lproj | xargs rm -rf
CMD