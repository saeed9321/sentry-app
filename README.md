SentryApp
=========

Security for your iDevice.  Combines jailbreak detection, debugger detection, minimum device password requirements, app level password, and single sign on capabilities.

SentryApp combines several security projects to create a unique measure of security that cannot be found elsewhere.

[Passcode-check](https://github.com/project-imas/passcode-check) ensures that users have satisfactory device-level password.

[Security-check](https://github.com/project-imas/security-check) adds jailbreak detection and debugger detection.  If your device is in the wrong hands, your app will still be secure if someone jailbreaks or attempts to use a debugger.

Geofencing and location services allow device tracking and can take action if a device leaves a designated fence area.

[App-password](https://github.com/project-imas/app-password) protects the SentryApp with an additional password layer to protect the SentryApp settings.  This can be used for a second layer of security, or can allow an admin to setup a device that the user cannot change.

[Single-sign-on](https://github.com/project-imas/single-sign-on) allows the SentryApp to protect your custom apps by requiring the SentryApp to run.  If a device is vulnerable and fails one of the previous tests (device-level password, jailbreak detection, debugger detection, geofencing), then access to the custom app is prevented.


## Setup

In progress...

## Future capabilities

The [Mobile Device Management Server](https://github.com/project-imas/mdm-server) will have interactions with the SentryApp.  Failed tests can result in the device attempting to "phone home" and report vulnerabilities to the MDM Server.

The MDM Server may also have the capability to send information to the SentryApp, such as defining a new geofence.

## License

Copyright 2014 The MITRE Corporation, All Rights Reserved.

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this work except in compliance with the License. You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.