# Release Notes for JavaFX 26.0.2

## Introduction

The following notes describe important changes and information about this release. In some cases, the descriptions provide links to additional detailed information about an issue or a change.

These notes document the JavaFX 26.0.2 update release. As such, they complement the [JavaFX 26](https://github.com/openjdk/jfx26u/blob/master/doc-files/release-notes-26.md) and [JavaFX 26.0.1](https://github.com/openjdk/jfx26u/blob/master/doc-files/release-notes-26.0.1.md) release notes.

## List of Fixed Bugs

Issue Key | Summary | Subcomponent
--------- | ------- | ------------
[JDK-8379209](https://bugs.openjdk.org/browse/JDK-8379209) | Uninitialised variable in pathApplierFunctionFast of coretext.c | graphics
[JDK-8379211](https://bugs.openjdk.org/browse/JDK-8379211) | Uninitialised memory in Java_com_sun_javafx_font_freetype_OSFreetype_FT_1Outline_1Decompose | graphics
[JDK-8379257](https://bugs.openjdk.org/browse/JDK-8379257) | Update JPEG Image Decoding Software to 10 | graphics
[JDK-8378510](https://bugs.openjdk.org/browse/JDK-8378510) | Provide media support for libavcodec version 62 | media
[JDK-8379206](https://bugs.openjdk.org/browse/JDK-8379206) | 4 Null pointer dereference defect groups in 4 glib files | media
[JDK-8381447](https://bugs.openjdk.org/browse/JDK-8381447) | Remove G_DISABLE_CHECKS compiler flag on Windows to align GLib/GStreamer compilation with macOS/Linux | media
[JDK-8375084](https://bugs.openjdk.org/browse/JDK-8375084) | Update libxslt to 1.1.45 | web
[JDK-8378226](https://bugs.openjdk.org/browse/JDK-8378226) | Animated GIFs do not animate after WebKit 620.1 update | web
[JDK-8379336](https://bugs.openjdk.org/browse/JDK-8379336) | Update libxml2 to 2.15.2 | web
[JDK-8381517](https://bugs.openjdk.org/browse/JDK-8381517) | GlassViewDelegate::convertNSStringToJString can return uninitialized value | window-toolkit

## List of Security fixes

Issue Key | Summary | Subcomponent
--------- | ------- | ------------
JDK-8373527 (not public) | Improve Graphics playback | graphics
JDK-8379207 (not public) | Improve audio conversion | media
JDK-8383129 (not public) | Better Handling of MP4 Files | media
JDK-8383143 (not public) | Enhance Playlist Loading | media
JDK-8378277 (not public) | Improve Editor selection | web
JDK-8383092 (not public) | Enhance WebView Resource Loading | web
