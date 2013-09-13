# Welcome to `nhl.db`

A free open public domain National Hockey League (NHL) database 'n' schema
(`nhl.db`) for use in any (programming) language
(e.g. uses plain text fixtures/data sets).


## Usage

Use the `sportdb` command line tool to build your own `nhl.db` copy
from the plain text fixtures.  Example:

Step 1:  Get a copy of the `world.db` fixtures

    $ git clone git://github.com/geraldb/world.db.git

Step 2:  Get a copy the `nhl.db` fixtures

    $ git clone git://github.com/geraldb/nhl.db.git

Step 3:  Let's build the `nhl.db`

    $ sportdb setup --include ./nhl.db --worldinclude ./world.db

That's it.
See the [`sportdb` command line tool project](https://github.com/geraldb/sport.db.ruby) for more.



## Links

- Official site -> [`nhl.com`](http://nhl.com)

<!-------- some facts ------------>

- 30 teams

### Wikipedia

- [National_Hockey_League](http://en.wikipedia.org/wiki/National_Hockey_League)
- [2013–14_NHL_season](http://en.wikipedia.org/wiki/2013–14_NHL_season)
- [2012–13_NHL_season](http://en.wikipedia.org/wiki/2012–13_NHL_season)


## License

The `nhl.db` schema, data and scripts are dedicated to the public domain.
Use it as you please with no restrictions whatsoever.

## Questions? Comments?

Send them along to the [Open Sports Database & Friends Forum/Mailing List](http://groups.google.com/group/opensport).
Thanks!
