# Uncomment this line to define a global platform for your project
# platform :ios, "6.0"

source 'https://github.com/CocoaPods/Specs.git'
source 'ssh://git@git.openmarket.com/tng/Specs.git'

target "matrixConsole" do


# Different flavours of pods to MatrixKit
# The tagged version on which this version of Console has been built
#pod 'MatrixKit', '~> 0.2.2'

# The lastest release available on the CocoaPods repository 
#pod 'MatrixKit'

# The develop branch version
pod 'MatrixSDK', :git => 'https://github.com/matrix-org/matrix-ios-sdk.git', :branch => 'develop'
pod 'MatrixKit', :git => 'https://github.com/matrix-org/matrix-ios-kit.git', :branch => 'develop'

# The one used for developping both MatrixSDK and MatrixKit
# Note that MatrixSDK must be cloned into a folder called matrix-ios-sdk next to the MatrixKit folder
#pod 'MatrixKit', :path => '../matrix-ios-kit/MatrixKit.podspec'
#pod 'MatrixSDK', :path => '../matrix-ios-sdk/MatrixSDK.podspec'

pod 'GBDeviceInfo', '~> 2.2.9'


### OpenWebRTC call stack ###
# The wrapper lib between MatrixSDK and OpenWebRTC-SDK
pod 'MatrixOpenWebRTCWrapper', :git => 'https://github.com/matrix-org/matrix-ios-openwebrtc-wrapper.git', :branch => 'master'
pod 'OpenWebRTC-SDK', :git => 'https://github.com/matrix-org/openwebrtc-ios-sdk.git', :branch => 'cvo_support'

pod 'MatrixEndpointWrapper'

end

target "matrixConsole" do

end

