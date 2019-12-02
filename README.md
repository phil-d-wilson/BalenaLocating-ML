![BalenaLocating](https://i.ibb.co/svRSnf7/logo.png)
A proof of concept project used to explore the [balenaCloud](https://www.balena.io/cloud/) stack for provisioning Raspberry Pi's as Bluetooth sensors, and a (simple!) KNN classifier to predict indoor positioning of iBeacons.

### The Plan:
One of the most difficult problems when developing Internet of Things solutions is provisioning the connected devices/sensors. Typically these devices need some network connectivity credentials (e.g. WIFI SSID & passphrase) and some credentials to authenticate against the backend cloud solution. Manually configuring a single device is OK, but when multiple devices are needed for a solution, this provisioning can be a blocker to progress. In addition, rapid development of concepts relies on a tight development-feedback loop. The [balenaCloud](https://www.balena.io/cloud/) is a solution to both of these issues, and so I was keen to try it for myself!

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE4OTI0NzE2NDksMTk3NzU2MDU3MCwxOT
Q5OTA4MDIyLDEzMTc0NzA4MTMsNDg2MjM5MDc1LC0xNTM2NTMw
NTg0XX0=
-->