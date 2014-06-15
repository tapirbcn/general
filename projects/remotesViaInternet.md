Removes via internet
=========

We have many removes in our houses that we would like to control from the
Internet, for example the one on charge of the AC. This project
will make that possible.

Requirements
----

  - Extensible to any remove using IR
  - Low consumption

How are we going to wire things up
-----------

The idea is to have an arduino nano wired with an IR transmitor that will emit
the needed codes whenever a raspberry pi (connected via radio) tells it to.

Also, we will need some handy way of intercepting the codes emitted by the
actual remove so we can later on use our hack.
