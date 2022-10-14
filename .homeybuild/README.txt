With this app you can manage your Evohome and other systems that connect via Total Connect Comfort from within Homey. It is using the unofficial API of Evohome.

Supported devices

The following devices are known to work with the app:

Control systems:

- Evohome ( + gateway RFG100 )
- Evohome Wifi
- Round Wireless ( + gateway RFG100 )

Thermostats (always in combination with Control system)

- HR92

Not in the list? It still could be supported; as long as your thermostat can be controlled via the Total Connect Comfort app, it should be controllable by the Homey app. Feedback is appreciated, so I can adjust the list.

Settings
After installing the application, first visit the Homey Settings and navigate to the 'Honeywell Evohome' application.

Fill in your username (email address) and password and press save. Then, go to Devices and add a Honeywell Evohome device. Press thermostat and select which devices you'd like to add into Homey.

Donate

If you like the app, consider a donation to support development

Limitations

Although multiple locations are supported, the quickaction works only on the first location. This is work in progress.

ToDo in order of my priority (donate to change priority ;-) )

- Cancel all adjustments in an intelligent way to limit calls to Honeywell
- Add target temperature triggers
- Add hot water device support
- Check when heating mode is changing ( e.g. following  schedule , permanent, etc)
- Clean-up code / upgrade to SDK3
- Time limits on quick Actions
- Time limits on temperature heatSetpoint
- Add timeout to code if Evohome service doesn't respond
- Add error checking in code
- Translation to NL

Known bugs

In order of priority:

- When access token of Honeywell expires, the first login might give an error when reading status. Unsure if this also affects when updating; statistically changes are higher with the 5 minute interval. That's probably why I only see it during the regular_update.

Unknown bugs

Yes ;-)
