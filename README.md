### Dependencies

 * adb (from the [Android SDK](http://developer.android.com/sdk)), and in your PATH.
 * JDK 6

### Installation (and upgrade)
 
```
curl https://raw.githubusercontent.com/manymo/manymo/master/manymo-installer | bash
```

This will install the client into your workspace and add it to your PATH. 

### Documentation

```
manymo [options] COMMAND [ARGUMENTS]

Commands:
        launch EMULATORNAME          Launch a headless emulator and make it appear like a local device
        list                         List emulators; use the name attribute with the launch command
        token                        Display a prompt to enter authorization token
        tunnel TUNNELKEY             Make an in-browser emulator appear like a local device

Options:
        --adb-path PATH_TO_ADB       Specify path to adb executable; otherwise uses the one in your path
```

More documentation is at https://www.manymo.com/pages/documentation/manymo-command-line-tool
