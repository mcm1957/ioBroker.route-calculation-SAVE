![Logo](admin/route-calculation.png)
# ioBroker.route-calculation
<!--
[![NPM version](https://img.shields.io/npm/v/iobroker.route-calculation.svg)](https://www.npmjs.com/package/iobroker.route-calculation)
[![Downloads](https://img.shields.io/npm/dm/iobroker.route-calculation.svg)](https://www.npmjs.com/package/iobroker.route-calculation)

![Number of Installations](https://iobroker.live/badges/route-calculation-installed.svg)
![Current version in stable repository](https://iobroker.live/badges/route-calculation-stable.svg)

[![NPM](https://nodei.co/npm/iobroker.route-calculation.png?downloads=true)](https://nodei.co/npm/iobroker.route-calculation/)

**Tests:** ![Test and Release](https://github.com/icastillo15/ioBroker.route-calculation/workflows/Test%20and%20Release/badge.svg)
-->
## route-calculation adapter for ioBroker
This Adapter uses the HERE.com API version 8 to check the traffic on your routes. This adapter is a fork of https://github.com/iobroker-community-adapters/ioBroker.roadtraffic. 
You can configure multiple routes and the adapter will check the actual traffic situation and show you how long your journey will take.
The Adapter has an alarm clock - so you can tell the Adapter at which time you have to be at work - and the Adapter starts playing Radio and makes an announcement on Alexa (Alexa2 Adapter required) - or you can use your own script to react on the alarm of the adapter..


## Getting started
So lets go:
1. Go to https://platform.here.com/sign-up and create a HERE.com Free Account (Freemium). You don´t need to enable billing so you can skip the billing information.

2. Look for the REST Section and click on "Generate App". You can generate new keys as well in the Access Manager.

3. Open the Instancesettings of the roadtraffic Adapter in ioBroker and paste the API Key into the config field.

4. Click the Plus icon in the Instance-Settings and create your first Route..

After you entered all informations to the config dialog click "Save & Close".
The Adapter should now restart and you are ready to go!

Image by <a href="https://www.freepik.com/free-photo/3d-view-map_45145244.htm#query=route%20logo&position=7&from_view=search&track=ais&uuid=74e89d28-9cfe-4b5e-94c9-a965b83497b4">Freepik</a>
## Changelog
<!--
    Placeholder for the next version (at the beginning of the line):
    ### **WORK IN PROGRESS**
-->

### **0.0.1 (2023-11-27)**
* (icastillo) Added support for here.com API v8 version. Added translations.

## License
The MIT License (MIT)

Copyright (c) 2023 icastillo15 <starwarsmalu@gmail.com>
Copyright (c) 2023 iobroker-community-adapters <mcm57@gmx.at>
Copyright (c) 2019 BuZZy1337 <buzzy1337@outlook.de>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
