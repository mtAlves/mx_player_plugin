# mx_player_plugin

![alt text](https://img.shields.io/pub/v/mx_player_plugin.svg?color=green&style=plastic)


A new Flutter plugin to open video files using mx player with subtitle and VLC player

## Usage

```dart
await PlayerPlugin.openWithMxPlayer(String url, String referer, String agent);
```

```dart
await PlayerPlugin.openWithWebVideoCast(String url, String referer, String agent);
```

```dart
await PlayerPlugin.openWithVlcPlayer(String url);
```
