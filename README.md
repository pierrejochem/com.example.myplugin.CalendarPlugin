com.example.myplugin.CalendarPlugin
==============================

Introduction
------------
cordova calendar plugin

Basic Usage
-------

        var startDate = new Date("August 24, 2016 8:00:00");
        var endDate = new Date("August 24, 2016 18:00:00");
        var notes = "Arrive on time, don't want to miss out (from Android)";
        var title = "PhoneGap Day";
        var location = "Portland, OR";
        var notes = "Arrive on time, don't want to miss out!";
        var success = function() { alert("Success"); };
        var error = function(message) { alert("Oopsie! " + message); };
        window.plugins.calendarplugin.createEvent(title, location, notes, startDate, endDate, success, error);
