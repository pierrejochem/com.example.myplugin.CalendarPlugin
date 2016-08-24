com.example.myplugin.CalendarPlugin
==============================

Introduction
------------
cordova calendar plugin

Example taken from: http://devgirl.org/2013/07/17/tutorial-how-to-write-a-phonegap-plugin-for-android/ but with corrected imports and a plugin.xml definition file.

Basic Usage
-------

```javascript
var startDate = new Date("August 24, 2016 8:00:00");
var endDate = new Date("August 24, 2016 18:00:00");
var notes = "Arrive on time, don't want to miss out (from Android)";
var title = "Example event";
var location = "Norderstedt, Germany";
var notes = "Arrive on time, don't want to miss out!";
var success = function() { alert("Success"); };
var error = function(message) { alert("Oopsie! " + message); };
window.plugins.calendarplugin.createEvent(title, location, notes, startDate, endDate, success, error);
```
