# Europe


## What's `football.db`?

A free open public domain football (soccer) database & schema
for use in any (programming) language
(e.g. uses plain text datasets for match schedules, results and more).
More [`football.db` Project Site »](http://openfootball.github.io)


## Intro

Free open public domain match fixtures & results datasets in the Football.TXT format include:

<!--  moved to its own repo in 2025/26
- [**Belgium**](belgium) - First Division A
--> 

- [**Netherlands**](netherlands) - Eredivisie
- [**Switzerland (Schweiz • Suisse • Svizzera • Svizra) incl. Liechtenstein**](switzerland) - Super League, Challenge League
- [**Hungary**](hungary) - NB I
- [**Czech Republic**](czech-republic) - First League
- [**Finland**](finland) - Veikkausliiga
- [**France**](france) - Ligue 1, Ligue 2
- [**Iceland**](iceland) - Urvalsdeild
- [**Ireland**](ireland) - Premier Division
- [**Scotland**](scotland) - Premiership
- [**Portugal**](portugal) - Primeira Liga
- [**Greece**](greece) - Super League
- [**Turkey**](turkey) - Süper Lig, 1. Lig
- and others

<!--
todo: add
 europe/croatia/
        europe/denmark/
        europe/luxembourg/
        europe/norway/
        europe/poland/
        europe/slovakia/
        europe/sweden/
        europe/ukraine/
-->



## Build Your Own `europe.db` Copy

### Alternative I - Do-It-Yourself (DIY) - Download and Unpack Zip Archive or Git Clone

Download and unpack the zip archive with the datasets or if you have git installed use the `git clone` command to
get a local copy.

Try in your working folder (that is, `/europe`):

```
$ sportdb build
$ sportdb --verbose build     # or for more (verbose) details incl. debug info
```

This will

- setup a new single-file SQLite database e.g. `./sport.db`
- read in all datasets in plain text (`.txt`)

That's it.


### Alternative II  - Read / Load Match files with `football-to-sqlite` / `football-to-psql`

Run the `football-to-sqlite` tool against match files in the Football.TXT format like so:

```
$ football-to-sqlite belgium.db belgium/2024-25_be1.txt
```

or pass in more than one match file:

```
$ football-to-sqlite switzerland.db switzerland/2024-25_ch1.txt \
                                    switzerland/2024-25_ch2.txt \
                                    switzerland/2023-24_ch1.txt \
                                    switzerland/2023-24_ch2.txt
```


Note: If the single-file SQLite database (and its tables, views & indices) do not (yet) exist,
they get auto-created on the first run.

[More »](https://github.com/sportdb/football.db/tree/master/football-to-sqlite)




## License

The football.db schema, data and scripts are dedicated to the public domain. Use it as you please with no restrictions whatsoever.


## Questions? Comments?

Yes, you can. More than welcome.
See [Help & Support »](https://github.com/openfootball/help)

