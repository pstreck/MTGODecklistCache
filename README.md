# MTGODecklistCache
This repository contains a cache in JSON format of tournaments posted on the MTGO Website (https://www.mtgo.com/en/mtgo/decklists) as well as a few other sources.

* Tools -> Tool to update and validate the repository
* Tournaments -> Tournament repository, organized by website and date
* Tournaments-Archive -> Tournament repository archive (for sources no longer being updated/maintained), organized by website and date

Each JSON file contains a tournament object, an array of decks, plus standings and bracket information when appropriate. Check Tools/MTGODecklistCache.Updater.Model to see exactly what these entities contain.
