platform :ios, '12.0'

def testing_pods
  pod 'Quick'
  pod 'Nimble', '~> 7.1.3'
end

target 'PhotoWall' do
  # Comment the next line if you're not using Swift and don't want to use dynamic frameworks
  use_frameworks!

  # Pods for PhotoWall
  # pod 'GoogleSignIn'
  pod 'AWSS3', '~> 2.6.26'

  target 'PhotoWallTests' do
    inherit! :search_paths
    # Pods for testing
    testing_pods
  end
end
