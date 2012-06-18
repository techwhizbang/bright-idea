# Bright Idea #

                  _.,----,._
                .:'        `:.
              .'              `.
             .'                `.
             :                  :
             `    .'`':'`'`/    '
              `.   \  |   /   ,'
                \   \ |  /   /
                 `\_..,,.._/'
                  {`'-,_`'-}
                  {`'-,_`'-}
                  {`'-,_`'-}
                   `YXXXXY'
                     ~^^~

## Summary ##

All too often the subtleties between unit, integration, and functional testing
are blurred.

"Bright Idea" is a coding kata focused on helping developers think about
the differences between unit, integration, and functional testing.

## Description ##

You've bought an old house that needs lots of restoration. One of the many
projects to tackle in the house is to update the tacky and mostly inoperable
lighting systems that date back to the 1960's.

Among the many decisions to make, you've decided to upgrade one room at a time, starting with
the guest room.

In order to make the guest room warm and inviting you've chosen a sleek set of
sconces. Beside the sconces you want to install a dimmer switch with a timer on it.

Here is the list of lighting componentry:

* A pair of bedroom sconces
* Dimmable CFL bulbs (eco-friendly and energy efficient)
* Bedroom wiring
* A dimmer switch with a timer
* Wiring for dimmer switch
* Breaker box

### Sconce Properties ###

* Mounting hardware
* Electrical wiring: 1 hot, 1 neutral, and 1 ground wire.
* Light bulb socket
* Individual on/off switch

### Dimmable Compact Fluorescent Light (CFL) Bulb Properties ###

* Dimmable
* Balast
* Gas filled bulb

### Wiring for bedroom ###

* 4 Electrical wiring access points.
* Each electrical wiring access point has: 1 hot, 1 neutral, and 1 ground wire.

### Dimmer Switch with a Timer ###

* On/off switch
* Touch sensitive based dimmer
* Timer button with intervals of 10 minutes, 30 minutes, 1 hour, 2 hours, and 5 hours.
* Electrical wiring: 1 hot, 1 neutral, and 1 ground wire.

### Breaker Box ###

* Power switch (on/off) going to the guest bedroom.

## Hints ##

In any lighting system there are many individual components that make a fully "functional" lighting solution.
Once a lighting solution is fully "functional" we rarely think about the details of _how_ it works. Instead we just that
it works. I like to ask this question: When you walk into a room and hit the lights, how often
do you concern yourself with any details? There is one question, namely, did the lights turn on?

Conversely, as you couple or "integrate" the lighting components, you are more interested
in the signals between their integration points. For example after you connect the bedroom wiring to the dimmer switch
you should be interested in the voltage reading on the various wires.

As you're unit testing you should be laser focused on each of the individual component.