2048-android
============

This is the android port of the 2048 game
It's nothing fancy, just a webview that loads the locally stored html files of the original game.
I just wanted to make it instantly playable without Internet (the app doesn't require any permissions) and with
a quick access icon for my smartphone.

Feel free to contribute with pull requests to the original project if you have any android
specific improvements in mind.

Play store link: https://play.google.com/store/apps/details?id=com.game.beyondinfinity.a2048

##Building

If you want to build from source just do

    git clone --recursive https://github.com/rrohaill/2048.git
    cd 2048-android/
    git submodule update --init --recursive
    ./gradlew build

### With Eclipse

1. Copy `https://github.com/rrohaill/2048.git` to clipboard
2. File -> Import -> Git / Projects from Git -> Clone URI
3. Paste URI from clipboard (if it did not appeared automatically)
4. Next> Next> **Check "Clone submodules"**
5. Next> select "Import existing project"

### With Android Studio

1. Follow first three lines of Building directions.
2. In Android Studio selection "Open an Existing Android Studio Project"
3. When prompted, add the VCS root.
