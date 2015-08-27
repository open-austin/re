# recycling-bin :recycle:

This is a fork of https://github.com/open-city/recycling.

Our goals for this fork are to build:

- REST API that can be hosted easily on more than just Heroku. This means:
  - No Mongo dependency. Use a relational database like Postgres (or maybe GitHub pages). 
  - No memcached dependency. We can figure out scaling later.
  - https://github.com/open-austin/recycling-bin/issues/1
- Frontend that consumes the API. It should be just static files that can be hosted on GitHub pages.

#### License

Released to the public domain under [the Unlicense](http://unlicense.org/) by Open Austin, 2015.

#### Contributing

Please see [CONTRIBUTING.md](CONTRIBUTING.md).


