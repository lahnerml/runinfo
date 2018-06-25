Simple script that linearly interpolates how long it will take to run a given
distance with a certain average pace.
Additionally, it gives the average pace that is needed to finish in a given
time.

To determine the average pace needed to finish within a specified time call the
script as
```
runinfo dist $distance dur $duration
```
Note, that `$duration` has to be either formatted as `HH:MM` or `MM`.

To determine the time it will take to race a distance with a given average pace
call the script as
```
runinfo dist $distance avg $average
```
Note, that `$average` has to be either formatted as `MM:SS`.

In general, dist has to be specified as number.  Additionally, marathon and
halfmarathon can be specified as `m` or `marathon` and `hm` or `halfmarathon`,
respectively.
