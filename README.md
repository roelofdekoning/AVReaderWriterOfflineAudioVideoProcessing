# AVReaderWriterOfflineAudioVideoProcessing
Make a copy of an AV file using Apple's AVReaderWriter

AVReaderWriter demonstrates how to use AVAssetReader to read (and decode) sample data from a movie file, then use AVAssetWriter to (encode and) write the sample data to a new movie file. A toggle can be set for decompression (and subsequent compression) of audio and video tracks in a movie file. If both toggles are off, an exact copy should be made of the original movie file.

The execution of these concepts is concentrated in AAPLDocument.m.

## Build Requirements

Xcode 7.0, OS X 10.11 SDK

## Runtime Requirements

OS X 10.11

# Structure

Source files: AAPLDocument.h/m, AAPLProgressPanelController.h/m, main.m
Project bundle: AVReaderWriter.xcodeproj, AVReaderWriterOSX-Info.plist, InfoPlist.strings
User interface files: AAPLProgressPanel.xib, MainMenu.xib, AAPLDocument.xib
User interface resources: AudioOnly2x.png, ErrorLoading2x.png

## Changes

Version 1.0
- First version.

Copyright (C) 2015 Apple Inc. All rights reserved.