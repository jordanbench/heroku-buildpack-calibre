# Calibre Heroku Buildpack

Simple buildpack to install [Calibre](http://calibre-ebook.com/) on Heroku.

Expects the calibre library in the _library_ directory and the users database in the users.sqlite file.

Writes the metadata file (library/metadata.db) to the postgresql database when going to sleep and reads the file on start.
