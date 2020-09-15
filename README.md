# AirConnect for BitBar
Use your Google chromecast-enabled devices as speakers for your Apple AirPlay audio. This project simply brings together the powers of [AirConnect](https://github.com/philippe44/AirConnect) and [BitBar](https://github.com/matryer/bitbar).

## Installation
1. Make sure you're using macOS.
2. Download the appropriate file from [AirConnect](https://github.com/philippe44/AirConnect). Recommended: Download `aircast-osx-multi` and place it in your `/Applications` folder.
3. Install [BitBar](https://github.com/matryer/bitbar).
4. Download the [plugin](https://github.com/CartoonChess/bitbar-airconnect/blob/master/airconnect.1d.sh) and install it using the [BitBar instructions](https://github.com/matryer/bitbar#installing-plugins).
  - Make sure the path to your plugins doesn't contain any single or quotation marks. Ideally, avoid spaces as well.
5. If you are using a file or location for AirConnect other than `/Applications/aircast-osx-multi`, update the `path` and `processName` variables in the plugin file.
6. Refresh BitBar via its built-in menu. If everything is set up correctly, click **Start AirConnect** to start the bridge.
7. Stream audio to your chromecast devices by changing your Mac's audio output device, choosing AirPlay in an iOS app, etc.

![AirConnect plugin sample](https://user-images.githubusercontent.com/43363630/93159526-5214f580-f749-11ea-9b1e-0f5a143643d6.png)
