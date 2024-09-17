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

<!--
```
## Ligue 1 Clubs

paris,        Paris St. Germain|Paris Saint-Germain, PSG
montpellier,  HSC Montpellier|Montpellier Hérault SC,  MHS
lille,        OSC Lille|Lille OSC|LOSC Lille,    LIL
marseille,    Marseille|Olympique Marseille,  OM
...
```
-->

```
= Ligue 1

Journée 1

[Ven 8 Août]
  20h30  Stade de Reims      2-2  Paris SG
[Sam 9 Août]
  21h00  SC Bastia           3-3  Olympique de Marseille
         Évian TG            0-3  SM Caen
         EA Guingamp         0-2  AS Saint-Étienne
         LOSC Lille          0-0  FC Metz
         HSC Montpellier     0-1  Girondins de Bordeaux
         FC Nantes           1-0  RC Lens
         OGC Nice            3-2  Toulouse FC
[Dim 10 Août]
  17h00  Olympique Lyonnais  2-0  Stade Rennais FC
  21h00  AS Monaco FC        1-2  FC Lorient
```



## Build Your Own `france.db` Copy

Use the `sportdb` command line tool to build your own `france.db` copy
from the plain text datasets. [More »](https://github.com/openfootball/datafile)


### Alternative I - Use the Quick Starter Templates

Use the quick starter datafile templates to start from scratch. Examples:

Build the database for all French clubs, leagues and seasons:

    $ sportdb new fr

Build the database for the 2020/21 season:

    $ sportdb new fr2020-21

[More »](https://github.com/openfootball/quick-starter)



### Alternative II - Do-It-Yourself (DIY) - Downlad and Unpack Zip Archive or Git Clone

Download and unpack the zip archive with the datasets or if you have git installed use the `git clone` command to
get a local copy.

Try in your working folder (that is, `/france`):

```
$ sportdb build
$ sportdb --verbose build     # or for more (verbose) details incl. debug info
```

This will

- setup a new single-file SQLite database e.g. `./sport.db` and
- read in all datasets in plain text (`.txt`)

That's it.



## Questions? Comments?

Yes, you can. More than welcome.
See [Help & Support »](https://github.com/openfootball/help)

