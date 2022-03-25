# Cross-Platform Properties

| Property | Required | Default | Description |
| :--- | :--- | :--- | :--- |
| `arch` | No | String | This is made available for cross-compiling. It specifies the target architecture, by default it detects the machine on which the cli is executing. |
| `build` | | | Shell command to build an application |
| `bundle_identifier` | | |  A unique ID that identifies the bundle (used by all app stores). |
| `bundle_identifier_short` | | | A unique ID that identifies the bundle (used by all app stores). |
| `copyRight` |  |  |  | 
| `debug_flags` | No | None | Advanced Compiler Settings for debug purposes (ie C++ compiler -g, etc). |
| `description` | No | None | A short description of the app |
| `env` | No | None | An array of environment variables, separated by commas |
| `executable` | Yes | | The name of the file to be output. |
| `flags` | No | None | Advanced Compiler Settings (ie C++ compiler -02, -03, etc). |
| `forwardConsole` | | | |
| `height` | | | The initial height of the first window |
| `input` | | | A directory is where your application's code is located |
| `lang` | | | Localization |
| `maintainer` | No | | |
| `name` | Yes | None | The name of the program |
| `output` | Yes | | The binary output path |
| `title` | | | The initial title of the window (can have spaces and symbols etc). |
| `version` | Yes | None | A string that indicates the version of the cli tool and resources. |
| `versionShort` | No | None | A string that indicates the version for MacOS. |
| `width` | | | The initial width of the first window |


# Windows

| Property | Required | Default | Description |
| :--- | :--- | :--- | :--- |
| `revision` | No | | TODO: maybe the user doesn’t need to know about this? |
| `win_cmd` | Yes | None | The command to execute to spawn the “back-end” process. |
| `win_icon` | | | The icon to use for identifying your app on Windows. |
| `win_logo` | | | The icon to use for identifying your app on Windows. |
| `win_pfx` | No | | A relative path to the pfx file used for signing. |
| `win_publisher` | | | |
| `win_sign` | | | |


# Linux

| Property | Required | Default | Description |
| :--- | :--- | :--- | :--- |
| `linux_categories` | No | None | Helps to make your app searchable in Linux desktop environments |
| `linux_cmd` | Yes | | The command to execute to spawn the “back-end” process. |
| `linux_icon` | Yes | None | The icon to use for identifying your app in Linux desktop environments. |


# MacOS

| Property | Required | Default | Description |
| :--- | :--- | :--- | :--- |
| `mac_appstore_icon` | | | Mac App Store icon |
| `mac_category` | No | None | A category in the App Store |
| `mac_cmd` | Yes | None | The command to execute to spawn the “back-end” process. |
| `mac_distribution_method` | | | |
| `mac_entitlements` | No | None | plist file path |
| `mac_icon` | Yes | None | The icon to use for identifying your app on MacOS. |
| `mac_provisioning_profile` | | | |
| `mac_sign` | | | |
| `mac_signing_certificate` | | | |
| `mac_sign_paths` | | | |
| `mac_team_id` | | | |


# iOS

| Property | Required | Default | Description |
| :--- | :--- | :--- | :--- |
| `ios_device_simulator` | No | None | which device to target when building for the simulator |
| `ios_entitlements` | Yes | None | plist file path |
| `ios_distribution_method` | Yes | | |
| `ios_provisioning_profile` | Yes | None | The provisioning profile that is used for signing (should be mac?) |
| `ios_signing_certificate` | Yes | | |
| `ios_team_id` | Yes | | |


# Android

| Property | Optional | Default | Description |
| :--- | :--- | :--- | :--- |
|||||
