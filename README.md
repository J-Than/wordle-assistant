# WORDLE Assistant

WORDLE Assistant is a single-page web app for finding possible English-language matches in the WORDLE game or other online apps with the same rules/structure.

## Compatibility

The app should run on standard web browsers.

## Usage

This app is for players of WORDLE or similar apps, and requires a basic knowledge of the rules and objectives of the game. This app is not a game itself, but rather a tool to help find words if a player is stuck.

The formatting of the app, such as color choices and rough layout, are designed to mirror the general styling of most WORDLE applications, so the "rules" should be familiar to players of the game.

Instead of working from a hidden but pre-determined "answer" word, this app asks the user to manually change the colors of the specific letters based on what the game app has shown. It will then display all possible remaining matches from within the WORDLE dictionary based on the inclusion or disinclusion of letters.

## Data

The word list used by this app is pulled from the code of the original WORDLE website, which is not an exhaustive list of all possible 5-letter words. It includes only the words that are possible answer words for WORDLE.

The app does not check user inputs against any word list; for the purposes of "exploration," it is easiest to leave options open.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.