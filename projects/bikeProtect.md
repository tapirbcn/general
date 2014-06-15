Bike protect
=========

Barcelona is a city where there are high chances that somebody is going to mess with
your bike so we need some hack to protect ourselves!

Requirements
----

  - Detects when wheels are moved from their place
  - Detects when wheels are spinning and they should not
  - Detects when your bike is shaked/moved heavily
  - Starts some noise to discourage people from touching your bike.
  - Sends an alarm via Radio to a base station (if available).
  - Base station connects to the internet, sends alarm to some kind of cloud.
  - Android application shows alarm.
  - Some way of turn it off when actually using the bike.
  - The battery should last for weeks
  - Everything should be lowcost

How are we going to wire things up
-----------

The idea is to have an arduino nano running all the time in a low power mode, this
will change the moment any of our alarms is triggered.

When any alarm is triggered a speaker will start buzzing and a FM radio signal will
emitted. This signal will be picked up by a base station that will forward the alarm
to the internet.
