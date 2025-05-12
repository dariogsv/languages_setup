# Setup Kotlin

## 1. Install Kotlin Command Line Compiler
1. Download https://github.com/JetBrains/kotlin/releases/download/v2.1.20/kotlin-compiler-2.1.20.zip 
2. Unpack the zip file to C:\Program Files\ 
3. Add bin folder path (c:\Program Files\kotlin-compiler-<version>\bin) to path environment variable

## 2. Install JVM, Android Studio and Android SDK
1. Install JDK, Android Studio and Android SDK using winget
```shell
winget install Oracle.JDK.24 # pode ser openjdk tbm, mas o oracle é mais completo e mais atualizado
winget install android-studio
winget install Google.PlatformTools
```

2. Add to path environment variable `C:\Users\<username>\AppData\Local\Android\Sdk\platform-tools`

## 3. Install Android SDK Command-line
1. Open Android Studio
2. Click in Settings > Appearance & Behavior > Android SDK > SDK Tools
3. Mark Android SDK Command-line Tools and click in Apply
4. Add bin folder path `C:\Users\<username>\AppData\Local\Android\Sdk\cmdline-tools\latest\bin` to path environment variable

## 4. Install Gradle
1. Download https://services.gradle.org/distributions/gradle-8.10.2-all.zip 
2. Unpack the zip file to C:\Program Files\ 
3. Add bin folder path (c:\Program Files\gradle-<version>\bin) to path environment variable

## 4. Install API level 35
1. sdkmanager "platform-tools" "platforms;android-35" "build-tools;35.0.0"

## 5. Create a new project
1. Access android studio and create a new project
2. Select Empty Activity and click in Next
3. Select  name, package name and save location and click in Finish

##