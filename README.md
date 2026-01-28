# BandPicker - MUSIC SKYNET

A band selection tool for [Instant Band Night](https://www.eventbrite.com/e/instant-band-night-35-the-35th-one-tickets-1980400506225) that helps you create fair and balanced bands from your roster of musicians.

## About Instant Band Night

Instant Band Night is a musical party in Oakland, CA where musicians who have just met spontaneously form bands and perform together. The format is simple but exhilarating:

1. Musicians are randomly assigned to bands by drawing names for each instrument (drums, guitar, bass, vocals, misc)
2. Each newly-formed band gets 5 minutes to plan their performance
3. They perform a single 5-minute set on stage
4. A randomly chosen artist sketches the band's concert poster during their performance

BandPicker automates the random selection process, ensuring fair distribution of musicians across multiple bands throughout the night while preventing the same people from being picked back-to-back (via the "Band Delay Factor" setting).

## Features

- **Name Input**: Add people to instrument categories (Vocals, Guitar, Bass, Drums, Misc, Art)
- **Smart Band Creation**: Automatically create balanced bands with configurable delay factors
- **Custom Band Builder**: Manually select roles for custom band configurations
- **Data Persistence**: All data saved to browser localStorage
- **Band Management**: Edit band members, replace with random picks, or manually select specific people

## Live Demo

Visit the app at: **https://akostibas.github.io/BandPicker/**

## Version History

- v2.1 - Added link to Instant Band Night event in README
- v2.0 - Renamed to index.html for cleaner URLs, added redirect for legacy URL
- v1.9 - Fixed Safari background rendering with webkit prefixes and html fallback
- v1.8 - Added Safari compatibility for backdrop-filter
- v1.7 - Improved error messaging for manual member selection
- v1.6 - Rock-and-roll visual styling with dark gradient background
- v1.5 - Improved tab contrast and readability
- v1.4 - Added Claude.md for persistent instructions
- v1.3 - Version numbering
- v1.2 - Data persistence via localStorage
- v1.1 - Instrument specification for Misc bucket
- v1.0 - Initial prototype

## Technical Details

- Single HTML file with inline CSS and JavaScript
- No external dependencies
- Deployed via GitHub Pages
- Compatible with modern browsers including Safari

## License

MIT
