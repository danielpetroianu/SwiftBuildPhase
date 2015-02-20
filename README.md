# SwiftBuildPhase
https://github.com/facebook/xctool/issues/471

# copy & paste

    xctool \
        -project SwiftBuildPhase.xcodeproj \
        -scheme SwiftBuildPhase \
        build

-

    xcodebuild \
        -project SwiftBuildPhase.xcodeproj \
        -scheme SwiftBuildPhase \
        -configuration Debug \
        build
