# Pre-work - **Tippo**

**Tippo** is a tip calculator application for iOS.

Submitted by: **Lu Liu 🙋🏻**

Time spent: **2.5** hours spent in total

## User Stories

The following **required** functionality is complete:
* [x] User can enter a bill amount, choose a tip percentage, and see the tip and total values.

The following **optional** features are implemented:
* [x] Custom font
* [x] UI animations (a simple and subtle fade-in for trying out the nested view feature a bit)
* [x] Making sure the keyboard is always visible and the bill amount is always the first responder. This way the user doesn't have to tap anywhere to use this app. Just launch the app and start typing.

## Video Walkthrough

Here's a walkthrough of implemented user stories:

<a href="http://imgur.com/a/FyMrf" target="_blank"><img src="http://i.imgur.com/IidTiLc.gif" title='Video Walkthrough' width='' alt='Video Walkthrough' /></a>

GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

When I added an action, Xcode automatically generated arg types as "Any" instead of "AnyObject" demo-ed in the video, so when I tried to link the Value Changed event of the Segmented Control back to my calculateTip() function, there was only "insert action" but no "connect action" triggered.

## License

    Copyright ©2016 Lu Liu

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
