# Table of contents

* [Table of Contents](README.md)
* [Import Expressions ](import-expressions.md)
* [01. Common Naming Patterns](01.-common-naming-patterns.md)
* [02. Names](02.-names.md)
* [03. Formatting](03.-formatting.md)
* [04. Functions](04.-functions.md)
* [05. Failure Checks](05.-failure-checks.md)
* [06. Encapsulation](06.-encapsulation.md)
* [07. Events](07.-events.md)
* [08. Concurrency](08.-concurrency.md)
* [09. Attributes](09.-attributes.md)
* [10. Constructors](10.-constructors.md)
* [11. Class & Specifiers](11.-class-and-specifiers.md)
* [12. Math](12.-math.md)
* [13. Containers](13.-containers.md)
* [📘 Fortnite Digest](fortnite-digest.md)
* [📗 Unreal Engine Digest](unreal-engine-digest.md)
* [📕 Verse Digest](verse-digest.md)
* [EG: Onboarding Guide](https://dev.epicgames.com/documentation/en-us/uefn/onboarding-guide-to-programming-with-verse-in-unreal-editor-for-fortnite)
* [EG: Verse Programming](https://dev.epicgames.com/documentation/en-us/uefn/learn-programming-with-verse-in-unreal-editor-for-fortnite)
* [EG: Language Reference](https://dev.epicgames.com/documentation/en-us/uefn/verse-language-reference)
* [EG: Official API](https://dev.epicgames.com/documentation/en-us/uefn/verse-api)
* [EG: Verse Scripting](https://forums.unrealengine.com/tags/c/development-discussion/programming-scripting/148/fortnite/l/latest)
* [EG: Dev Community](https://forums.unrealengine.com/tags/c/development-discussion/programming-scripting/148/fortnite/l/latest)
* [EG: Community Snippets](https://dev.epicgames.com/community/fortnite/snippets)
* [View on Github Wiki](https://github.com/LilWikipedia/UEFNVersePocketWiki)

## Scripts Directory

### `Game`
Contains various Verse scripts related to game mechanics and logic.

#### `asymmetric_multiplayer_balance.verse`
Handles team balancing for asymmetric multiplayer games, ensuring fair team distribution and managing player spawns and invisibility.

#### `balance_teams.verse`
Balances teams in a multiplayer game by assigning players to the smallest team when they join.

#### `boss_device.verse`
Manages a boss character that follows a player and interacts with a mutator zone device.

#### `boss_fight.verse`
Handles a boss fight scenario, including boss animations, health management, and player interactions.

#### `button_puzzle.verse`
Implements a button-based puzzle where players interact with buttons to toggle lights and solve the puzzle.

#### `countdown_timer.verse`
Creates a countdown timer that updates a UI element and signals when the timer ends.

#### `DuoReloadSystem.verse`
Implements a reload system for a duo-based game, where players can respawn if their partner is alive.

#### `elimination_game_device.verse`
Manages an elimination-based game mode, granting players new weapons as they eliminate others and checking for victory conditions.

#### `enemy_wave_spawner.verse`
Spawns waves of enemies and tracks player eliminations to progress through waves.

#### `ffa_shuffle_teams_device.verse`
Shuffles teams in a free-for-all game mode, ensuring each player is assigned to a different team.

#### `opt_in_opt_out_device.verse`
Allows players to opt in or out of a selection pool and randomly selects players from the pool when triggered.

### `Helper Scripts`
Contains utility scripts that assist with common tasks and functionalities.

#### `Arrays.verse`
Provides utility functions for working with arrays, including sorting and removing elements.

### `Object`
Contains scripts related to objects and their behaviors in the game.

#### `color_switch_synchronisedtiles.verse`
Manages a series of color-changing tiles that appear and disappear in a synchronized manner.

### `Player`
Contains scripts related to player actions, attributes, and interactions.

#### `AttachScriptToPlayer.verse`
Attaches a script to a player when they interact with a button device.

### `UI`
Contains scripts related to user interface elements and interactions.

#### `custom_progress_bar.verse`
Creates a custom progress bar UI element that updates smoothly based on a given percentage.
