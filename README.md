# Detecting human body poses in 3D with Vision and counting the jumps action
You keep your camera position in the direction of the waist and start jumping it will give you counts
## Overview
## Requirements
An iPhone with iOS version 17 or above
- Note: This sample code project is associated with WWDC23 session 111241: [Explore 3D body pose and person segmentation in Vision](https://developer.apple.com/wwdc23/111241/).
## Configure the sample code project
Before you run the sample code project in Xcode, ensure you're using an iOS device with an A12 chip or later. The input image should have all limbs of the subject visible.
- Note: Due to a behavior change with `cameraOriginMatrix` API, if this sample project is run on a device on a build earlier than beta 3, camera position will be rotated 180 degrees.  
