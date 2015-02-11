# SwiftBuildPhase
http://stackoverflow.com/questions/28363935/runing-xctool-on-project-that-has-a-build-phase-with-swift-script

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
