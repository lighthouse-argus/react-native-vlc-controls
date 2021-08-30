# react-native-vlc-control

[![ci][1]][2]

Controls for the React Native `<VLCPLayer>` component at [react-native-vlc-media-player](https://github.com/razorRun/react-native-vlc-media-player). For support with RN 0.45 or lower use version 1.3.1 or lower.

## Features

This package contains a simple set of GUI controls that work with the [react-native-vlc-media-player](https://github.com/razorRun/react-native-vlc-media-player) `<VLCPLayer>` component. This includes a back button, volume bar, fullscreen toggle, play/pause toggle, seekbar, title, error handling and timer toggle that can switch between time remaining and current time when tapped.

![How it looks](https://s3-us-west-2.amazonaws.com/nubix.ca/github/example.gif)

By default the `<VideoPlayer>` accepts a navigator property from React's built-in `<Navigator>` which pops the current scene off the stack when tapped. Alternatively you can provide your own onBack prop to the component to override this functionality. You should also provide your own onEnd prop to the component so it knows what to do when a video ends playback.

