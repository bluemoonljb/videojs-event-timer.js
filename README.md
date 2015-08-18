# videojs-event-timer.js
a plugin for video.js HTML5 player that trigger events at specified play time.
To learn more about vodeo.js HTML player, please visit http://www.videojs.com/

# Documentation

Plugin Options:

This plugin was created to work with jQuery, but you can remove this dependency by modifying the source code to fit your needs.
You can pass in an options object to the plugin upon initialization. 
Options may contain following properties:

event_name: the name of event to be triggered.

play_time: seconds, at what time the event will be triggered.

example options:

{events: [{"play_time":"6","event_name":"sample-event-1"},{"play_time":"12","event_name":"sample-event-2"}]}


To initialize event timer, try

videojs('video').event_timer({"events" : [{"play_time":"6","event_name":"sample-event-1"},{"play_time":"12","event_name":"sample-event-2"}]});


