[//]: # (title: Set up an environment)

Before you begin [creating your first application](multiplatform-mobile-create-first-app.md) to work on both iOS and Android, start by setting up an environment for Kotlin Multiplatform Mobile development:

1. If you are going to work with shared code or Android-specific code, you can work on any computer with an operating 
   system supported by [Android Studio](https://developer.android.com/studio).  
   If you also want to write iOS-specific code and run an iOS application on a simulated or real device, use a Mac with a 
   macOS. These steps cannot be performed on other operating systems, such as Microsoft Windows. This is due to an Apple requirement.
2. Install [Android Studio](https://developer.android.com/studio) 4.2 or 2020.3.1 Canary 8 or higher.   
    You will use Android Studio for creating your multiplatform applications and running them on simulated or hardware devices.
3. If you need to write iOS-specific code and run an iOS application, install [Xcode](https://apps.apple.com/us/app/xcode/id497799835)
    –  version 11.3 or higher.                                                                                                                                                                                                                                                                                                                          
    Most of the time, Xcode will work in the background. You will use it to add Swift or Objective-C code to your iOS application.
4. Make sure that you have a [compatible Kotlin plugin](multiplatform-mobile-plugin-releases.md#release-details) installed.  
    In Android Studio, select **Tools** | **Kotlin** | **Configure Kotlin Plugin Updates** and check the current Kotlin 
    plugin version. If needed, update to the latest version in the **Stable** update channel.
5. Install the *Kotlin Multiplatform Mobile* plugin.  
    In Android Studio, select  **Preferences** | **Plugins**, search for the plugin *Kotlin Multiplatform Mobile* in 
    **Marketplace** and install it.
    
    ![Kotlin Multiplatform Mobile plugin](mobile-multiplatform-plugin.png){width=500}
    
    Check out [Kotlin Multiplatform Mobile plugin release notes](multiplatform-mobile-plugin-releases.md).
    
6. Install the [JDK](https://www.oracle.com/java/technologies/javase-downloads.html) if you haven't already done so.  
    To check if it's installed, run the command `java -version` in the Terminal.       
     
Now it's time to [create your first cross-platform mobile application](multiplatform-mobile-create-first-app.md).
