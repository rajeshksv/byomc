# songs-dl

Aim is to build a utility which helps you maintain offline songs library (audio/video). In short, it does two things

- Download songs from various sources - Youtube, Raaga, Saavn etc
- Add rich metadata to songs so that you can browse via album, album artist

Initially will build it for Indian songs (especially for telugu). In case it turns out to be good/feasible and I am still interested in it, will extend for other languages.

## Features built:

NA

## Features planning to build:

### Downloading Songs 
- Download songs via source URL from supported websites
- Download songs via keywords
- Download songs via playlist URL
- Download songs via collection URL (A collection generally would be one song in the source website which contains 10-20 songs embedded in it)
- [Ambitious] Download collections via keywords. Ex: Illayaraja, SP Balu, Chiranjeevi. Download songs from various sources, remove duplicates (Deep learning), organize them

### Adding Metadata
- Once you get the song, you need to fetch metadata and add to it
- If possible, Fetch metadata from same website
- If not, then you need to get metadata intelligently
  - Convert initial audio to text and make it as title, get artist, album metadata from user
  - [Ambitious] Add deep learning model to detect songs metadata like Shazam


