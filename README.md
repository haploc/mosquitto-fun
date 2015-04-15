# mosquitto-fun
Some basic stuff after starting with mosquitto (MQTT)

Very much inspired by the [tempmonitor](https://github.com/jpmens/tempmonitor) by [jpmens](https://github.com/jpmens).

As mosquitto does not have websocket support in the standard packages, it needs to be activated on compilation time.
In the SOURCES/ you can find the config.mk file that was adapted, as well as the necessary spec-files to build the RPMS.
The SPEC files were heavily inspired by the SRPMS I found, and were not changed that much.

Scripts/ contains some basic bash-scripts to generate data.
In www/ you can find a very basic webdemo, also heavily inspired by the person mentioned above.

Note: I'm not a rpmbuild spec-ialist, any improvements are welcome.
