# harmonizerFXPlugin
harmonizerFX AU Plugin

# Pre-requisites
* Download [JUCE](https://juce.com/get-juce/download)

# Setup on Mac
* Launch `Projucer`
* Open (harmonizerFX/harmonizerFX.jucer)[harmonizerFX/harmonizerFX.jucer] in Projucer
* Select `Xcode (macOS)` under Selected exporter and click the Xcode icon to launch Xcode

![launch-xcode](screenshots/launch-xcode.png?raw=true "launch-xcode")

# Build on Xcode
* Select Target as `harmonizerFX - All` or `harmonizerFX - AU` and Build.

![xcode](screenshots/xcode.png?raw=true "xcode")

* If the build is successful you shall see `harmonizerFX.component` available under Products section of your Xcode project. Right-click and click "Show in Finder"
* Copy `$HOME/Library/Audio/Plug-Ins/Components/harmonizerFX.component` to `/Library/Audio/Plug-Ins/Components/` (This is where all system wide plugins are installed)

# Run
* Launch your preferred DAW and you shall find `harmonizerFX` plugin available under `SoundObjects` (temporary plugin manufacturer company title)
* Add the plugin to an audio-track and you shall be see the default plugin UI.

![default-plugin](screenshots/default-plugin.png?raw=true "default-plugin")
