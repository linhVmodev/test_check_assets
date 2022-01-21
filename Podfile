# Uncomment the next line to define a global platform for your project
platform :ios, '11.0'

post_install do |installer|
  installer.pods_project.targets.each do |target|
    target.build_configurations.each do |config|
      config.build_settings.delete 'IPHONEOS_DEPLOYMENT_TARGET'
    end
  end
end

target 'test' do
  # Comment the next line if you don't want to use dynamic frameworks
  use_frameworks!

  pod 'Alamofire'
  pod 'RxSwift'
  pod 'RxCocoa'
  pod 'Toast-Swift'
  pod 'NVActivityIndicatorView/Extended', :git => 'https://github.com/linhVmodev/NVActivityIndicatorView.git', :branch => 'master'
  pod 'AFDateHelper'
  pod 'PromiseKit'
  pod 'SwiftyJSON'
  pod 'SwiftLint'
  pod 'Moya'
  pod 'SwiftGen'
  pod 'netfox'
  pod 'SVPullToRefresh'
  pod 'PanModal'
  pod 'PopupDialog', :git => 'https://github.com/linhVmodev/PopupDialog.git', :branch => 'master'
  pod 'DropDown', :git => 'https://github.com/linhVmodev/DropDown.git', :branch => 'master'
  pod 'SteviaLayout'
  pod 'AssetChecker', :git => 'https://github.com/freshOS/AssetChecker.git'

end
