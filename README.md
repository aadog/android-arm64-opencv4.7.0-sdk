# android-arm64-opencv4.7.0-sdk

env:

```
CGO_ENABLED=1
GOARCH=arm64
GOOS=android
CC=${ANDROID-NDK-BUNDLE}\toolchains\llvm\prebuilt\windows-x86_64\bin\aarch64-linux-android21-clang.cmd
CXX=${ANDROID-NDK-BUNDLE}\toolchains\llvm\prebuilt\windows-x86_64\bin\aarch64-linux-android21-clang++.cmd
CGO_CXXFLAGS:--std=c++11 -Wgnu-designator
CGO_CPPFLAGS=-I${SDK}\include
CGO_LDFLAGS=-L${SDK}\libs\opencv -lstdc++ -landroid -lopencv_calib3d -lopencv_core -lopencv_dnn -lopencv_features2d -lopencv_flann -lopencv_gapi -lopencv_highgui -lopencv_imgcodecs -lopencv_imgproc -lopencv_ml -lopencv_objdetect -lopencv_photo -lopencv_stitching -lopencv_video -lopencv_videoio -lOpenMAXAL -lOpenSLES -ltegra_hal -ltbb -lquirc -llibwebp -llibtiff -llibprotobuf -llibpng -llibopenjp2 -llibjpeg-turbo -littnotify -lIlmImf -lcpufeatures -lade -lz -lmediandk

```
