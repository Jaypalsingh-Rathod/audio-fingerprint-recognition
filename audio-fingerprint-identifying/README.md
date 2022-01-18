## How to set up 

1. Run `$ make clean reset` or run python file reset-database to clean & init database struct
1. Copy some `.mp3` audio files into `mp3/` directory
1. Run `$ make fingerprint-songs`  or run python file 'collection-fingerprints-of-songs' to analyze audio files & fill your db with hashes
1. Start play any of audio file (from any source) from `mp3/` directory, and run (parallely) `$ make recognize-listen seconds=5`
