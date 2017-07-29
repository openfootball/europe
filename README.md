# France (incl. Monaco) - Ligue 1, Ligue 2


## What's `football.db`?

A free open public domain football database & schema
for use in any (programming) language (e.g. uses plain text datasets).
More [`football.db` Project Site »](http://openfootball.github.io)

## Intro

Free open public domain football data for France (incl. Monaco) / Europe. Events include:

| Level |                                |            |
| ----- | ------------------------------ | ---------- |
| I     |  Ligue 1                       |  20 Clubs  |
| II    |  Ligue 2                       |  20 Clubs  |


Example:

~~~
### Ligue 1 Clubs

paris,        Paris St. Germain|Paris Saint-Germain, PSG
montpellier,  HSC Montpellier|Montpellier Hérault SC,  MHS
lille,        OSC Lille|Lille OSC|LOSC Lille,    LIL
marseille,    Marseille|Olympique Marseille,  OM
...
~~~

~~~
## Ligue 1 - 2014/15

Journée 1

[Ven 8 Août]
  20h30  Stade de Reims      2-2  Paris SG
[Sam 9 Août]
  21h00  SC Bastia           3-3  Olympique de Marseille
  21h00  Évian TG            0-3  SM Caen
  21h00  EA Guingamp         0-2  AS Saint-Étienne
  21h00  LOSC Lille          0-0  FC Metz
  21h00  HSC Montpellier     0-1  Girondins de Bordeaux
  21h00  FC Nantes           1-0  RC Lens
  21h00  OGC Nice            3-2  Toulouse FC
[Dim 10 Août]
  17h00  Olympique Lyonnais  2-0  Stade Rennais FC
  21h00  AS Monaco FC        1-2  FC Lorient
~~~



## Build Your Own `france.db` Copy

Use the `sportdb` command line tool to build your own `france.db` copy
from the plain text datasets. [More »](https://github.com/openfootball/datafile)


### Examples

Build the database for all French clubs, leagues and seasons:

    $ sportdb new fr

Build the database for the 2014/15 season:

    $ sportdb new fr2014-15



## Questions? Comments?

Send them along to the
[Open Sports & Friends Forum/Mailing List](http://groups.google.com/group/opensport).
Thanks!
