TTDman
======

Web based scheduler/manager for an OpenTTD dedicated server

TODO:

* Deal with savegames properly for fresh installations

INSTALLATION:

* Install perl modules:
  * Time::Duration
  * Mojolicious
  * AnyEvent
  * AnyEvent::Subprocess

* Change the schedule to suit (top of the file)

* Run the server:

  $ ./ttdman daemon --listen http://\*:3000

* Hit the web interface

  http://localhost:3000
