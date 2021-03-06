Music player
============

Annoyed by all existing players because some subset of:

* not open source
* missing sound format ([FLAC](http://flac.sourceforge.net/itunes.html), Ogg, ...)
* bugs ([1](http://bugzilla.songbirdnest.com/show_bug.cgi?id=23640), [2](http://bugzilla.songbirdnest.com/show_bug.cgi?id=25023), [3](http://bugzilla.songbirdnest.com/show_bug.cgi?id=25042), [4](http://bugzilla.songbirdnest.com/show_bug.cgi?id=18503), [5](http://bugzilla.songbirdnest.com/show_bug.cgi?id=18505), [6](http://bugzilla.songbirdnest.com/show_bug.cgi?id=18480), [7](http://bugzilla.songbirdnest.com/show_bug.cgi?id=18478), [8](http://bugzilla.songbirdnest.com/show_bug.cgi?id=25073), [9](http://bugzilla.songbirdnest.com/show_bug.cgi?id=25024), ...)
* missing output possibility (RAOP, PulseAudio, ...)
* no or too limited DJ mode
* no library / database

Features of this player:

* open source
* simple
* support of most important sound formats
* advanced intelligent DJ mode
* simple music database

About the DJ mode, what I want (maybe some of these somewhat configurable):

* continously always add songs
* liked songs more often
* context-based choices, e.g. related songs more likely
* possibility to easily manually add songs to the list
* easy way to restrict to a subset of songs (like a genre, a playlist, a filesystem directory, etc.)

About the database:

* main function: search
* should be fast and optional for playback, i.e. music can be played even when the database is currently not ready for some reason
* file-entries located on the local filesystem which don't exist anymore should automatically be deleted
* file-entries located on a network filesystem which is not mounted should be marked as currently-not-available
* file-entries located on a network filesystem which is mounted which don't exist anymore should automatically be deleted
* should automatically be filled by a filesystem directory
* import like-state from local players like iTunes and also online services like Last.fm

TODO / possible additional missing features:

* volume normalization
* beat frequence determination and clever DJ-like fading
* echoprint.me or similiar song determination (mostly for metadata, esp. if missing)
* use tags given by Last.fm (mostly more tags)
* integrate iTunes database (rating, volume normalization, metatags)
* Last.fm streaming support
* watch msic directory for changes (e.g. new files added)

-- Albert Zeyer, <http://www.az2000.de>

