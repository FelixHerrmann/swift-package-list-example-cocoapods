# Uncomment the next line to define a global platform for your project
# platform :ios, '9.0'

target 'SwiftPackageListCocoapodsExample' do
  # Comment the next line if you don't want to use dynamic frameworks
  use_frameworks!

  # Pods for SwiftPackageListCocoapodsExample
  pod 'Firebase', '~> 11.0'

  post_install do | installer |
      require 'fileutils'
      FileUtils.cp_r('Pods/Target Support Files/Pods-SwiftPackageListCocoapodsExample/Pods-SwiftPackageListCocoapodsExample-acknowledgements.plist', 'SwiftPackageListCocoapodsExample/Settings.bundle/Acknowledgements-cp.plist', :remove_destination => true)
  end
end
