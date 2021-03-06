## Changelog

#### Upcoming

#### v0.3.2.0

*Minor*

* Added a "Whom would you like to lynch?" message during the Villagers' turn. ([#25](https://github.com/hjwylde/werewolf/issues/25))
* Allowed lowercase roles for `--extra-roles` in the `start` command. ([#33](https://github.com/hjwylde/werewolf/issues/33))

*Revisions*

* Shrunk some of the help text to make it more readable. ([#25](https://github.com/hjwylde/werewolf/issues/25))

#### v0.3.1.3

*Revisions*

* Fixed a bug where Werewolves could devour other Werewolves. ([#34](https://github.com/hjwylde/werewolf/issues/34))
* Changed Werewolf text from "kill" to "devour". ([#34](https://github.com/hjwylde/werewolf/issues/34))

#### v0.3.1.2

*Revisions*

* Fixed dead werewolves being informed of votes. ([#24](https://github.com/hjwylde/werewolf/issues/24))

#### v0.3.1.1

*Revisions*

* Tidied up the help text to be smaller. ([#26](https://github.com/hjwylde/werewolf/issues/26))
* Fixed a bug where the turn was advanced to Werewolves when no Werewolves were alive. ([#26](https://github.com/hjwylde/werewolf/issues/26))

#### v0.3.1.0

*Minor*

* Added a message to say the names of all the players at the start of a game. ([#23](https://github.com/hjwylde/werewolf/issues/23))
* Added a message to say the roles in play at the start of a game. ([#16](https://github.com/hjwylde/werewolf/issues/16))

#### v0.3.0.5

*Revisions*

* Fixed a bug where Werewolves could devour other Werewolves. ([#34](https://github.com/hjwylde/werewolf/issues/34))
* Changed Werewolf text from "kill" to "devour". ([#34](https://github.com/hjwylde/werewolf/issues/34))

#### v0.3.0.4

*Revisions*

* Fixed dead werewolves being informed of votes. ([#24](https://github.com/hjwylde/werewolf/issues/24))

#### v0.3.0.3

*Revisions*

* Tidied up the help text to be smaller. ([#26](https://github.com/hjwylde/werewolf/issues/26))
* Fixed a bug where the turn was advanced to Werewolves when no Werewolves were alive. ([#26](https://github.com/hjwylde/werewolf/issues/26))

#### v0.3.0.2

*Revisions*

* Tidied up the help text to be smaller. ([#26](https://github.com/hjwylde/werewolf/issues/26))
* Fixed a bug where the turn was advanced to Werewolves when no Werewolves were alive. ([#26](https://github.com/hjwylde/werewolf/issues/26))

#### v0.3.0.1

*Revisions*

* Fixed `interpret` to display the commands help messages when given invalid arguments. ([#22](https://github.com/hjwylde/werewolf/issues/22))

#### v0.3.0.0

*Major*

* Added `--extra-roles` option to `start`. ([#12](https://github.com/hjwylde/werewolf/issues/12))
* Removed Seer from being included by default. ([#12](https://github.com/hjwylde/werewolf/issues/12))

*Minor*

* Allowed `start` to work when the game has ended but `end` hasn't been called. ([#15](https://github.com/hjwylde/werewolf/issues/15))
* Added `quit` command. ([#13](https://github.com/hjwylde/werewolf/issues/13))

#### v0.2.0.2

*Revisions*

* Fixed dead werewolves being informed of votes. ([#24](https://github.com/hjwylde/werewolf/issues/24))

#### v0.2.0.1

*Revisions*

* Tidied up the help text to be smaller. ([#26](https://github.com/hjwylde/werewolf/issues/26))
* Fixed a bug where the turn was advanced to Werewolves when no Werewolves were alive. ([#26](https://github.com/hjwylde/werewolf/issues/26))

#### v0.2.0.0

*Major*

* Added the Seer role. ([#4](https://github.com/hjwylde/werewolf/issues/4))
* Removed the need to encode / decode to JSON for the state file. ([#9](https://github.com/hjwylde/werewolf/issues/9))

#### v0.1.0.0

*Major*

* Initial implementation with Villagers and Werewolves. ([#1](https://github.com/hjwylde/werewolf/issues/1))
