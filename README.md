# AfterGit-Official

**simplest git client for android that uses Termux's API**. <br><br>
*[`an implementation of AfterRun.`](https://github.com/IMOitself/AfterRun)*

<br>

> [!NOTE]
>  this version is for Android Studio. See [AfterGit](https://github.com/IMOitself/AfterGit) for AIDE version.

> [!WARNING]
>  the development of this project has been paused and will resume after implementing a [solution](https://github.com/IMOitself/subfoldersync-vibe) to sync commits with [AfterGit](https://github.com/IMOitself/AfterGit).

<br>


## Download

[![Releases](https://img.shields.io/badge/Releases-look%20for%20apk-blue?style=for-the-badge)](https://github.com/IMOitself/AfterGit/releases/)

<br>

## Installation
> [!IMPORTANT]
> must have [Termux](https://f-droid.org/en/packages/com.termux/)   installed <br><br>
>  must have run this command on Termux first:
> ```bash
> pkg install termux-api
> sed -i 's/# allow-external-apps = true/allow-external-apps = true/g' ~/.termux/termux.properties
> termux-setup-storage
> ```
<br>

## Features

- [x] check repo status
- [x] list unsaved changes
- [x] commit changes
- [x] commit amend
- [x] show unsaved changes' diff
- [x] commit history
- [x] commit history graph
- [x] commit diff
- [ ] push
- [ ] fetch
- [ ] pull

<br>

## Screenshots

> [!TIP]
> idk i just like the green alert thingy here :D

<img src="assets/ss1_home.jpg" width="200"><img src="assets/ss2_commit.jpg" width="200">
<img src="assets/ss3_diff.jpg" width="200">
<img src="assets/ss4_logs.jpg" width="200">
<img src="assets/ss5_logs.jpg" width="200">
<img src="assets/ss6_commit_desc.jpg" width="200">
<img src="assets/ss7_status.jpg" width="200">
<img src="assets/ss8_coming_soon.jpg" width="200">
