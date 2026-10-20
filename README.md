# Wallpaper Carousel Android Updates

This repository publishes only the Android app's update feed and signed APK files. The application source is maintained in a separate private repository.

The feed and download URLs are public so installed app versions can check for releases without embedding credentials. APK installation is always handed to Android's package installer and requires user approval. Each feed entry must include the version, APK URL, and SHA-256 checksum; package-signature verification remains enforced by Android.

No release artifact is published yet. The CI publishing workflow will populate this site after it is implemented and verified in the private source repository.
