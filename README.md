# LWJGL - Lightweight Java Game Library

The Lightweight Java Game Library (LWJGL) is a solution aimed directly at professional and amateur Java programmers alike to enable commercial quality games to be written in Java.
LWJGL provides developers access to high performance crossplatform libraries such as OpenGL (Open Graphics Library), OpenCL (Open Computing Language) and OpenAL (Open Audio Library) allowing for state of the art 3D games and 3D sound.
Additionally LWJGL provides access to controllers such as Gamepads, Steering wheel and Joysticks.
All in a simple and straight forward API.

Website: [http://lwjgl.org](http://lwjgl.org)
Forum: [http://lwjgl.org/forum](http://lwjgl.org/forum)
Bugs/Suggestions: [https://github.com/LWJGL/lwjgl/issues](https://github.com/LWJGL/lwjgl/issues)

## Compilation

### Requirements

- JDK 8 arm64
- Ant
- XCode/MacOS SDK

### Instructions

```sh
ant generate-all
ant compile
ant compile_native
ant jars
```

### Build time paths

- `$JAVA_HOME`
- `$(xcode-select -print-path)/Platforms/MacOSX.platform/Developer/SDKs/MacOSX.sdk`
