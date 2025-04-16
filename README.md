---
description: verse.FNCwiki.com
---

# Table of Contents

![](https://ue-cdn.artstation.com/imgproxy/kbNaxGnLbxRxJBFLqlZ12Ix89EhFVjCVN0wq14zhVag/filename:verse-programming-hero-image.png/resizing\_type:fill/width:1920/height:335/ext:jpg/aHR0cHM6Ly9kMWl2N2RiNDR5aGd4bi5jbG91ZGZyb250Lm5ldC9kb2N1bWVudGF0aW9uL2ltYWdlcy80NDkwN2Y5Yi0wYjM3LTQ0MWQtYjlkNy0zMjk0OTU3OWY4YWMvdmVyc2UtcHJvZ3JhbW1pbmctaGVyby1pbWFnZS5wbmc)

## VerseWiki

This project is just the **Epic Games** UEFN and Verse documentation rewritten in markdown- adding more direct navigation, and making the API easier to reference.

There is ALOT of unorganized documentation on Epic's website so this will be an ongoing project!



***

![](https://github.com/LilWikipedia/UEFNVersePocketWiki/assets/78571191/a894c872-b4e0-492e-b7dd-2c79dc971abe) ![](https://github.com/LilWikipedia/UEFNVersePocketWiki/assets/78571191/fe7cbe1e-1b77-49b4-b4aa-a6c6866882ce) ![](https://github.com/LilWikipedia/UEFNVersePocketWiki/assets/78571191/16c1ae8d-0299-4f94-81dd-8c8997188c76)

***

**Programming with Verse**

* Create your own rules and behaviors for your game by programming with Verse in UEFN!
* This guide provides a set of recommended standards for writing consistent code that's easy to maintain.
* By adhering to these guidelines, developers can improve code readability, reduce errors, and facilitate collaboration.
* Standardized code style is necessary to ensure code is easy to understand and maintain by both current and future developers working on a project.

***

## <mark style="color:green;">Verse Basics</mark>

### [Importing Expressions or Modules](import-expressions.md)

### [1. Common Naming Patterns](01.-common-naming-patterns.md)

### [2. Names](02.-names.md)

### [3. Formatting](03.-formatting.md)

### [4. Functions](04.-functions.md)

### [5. Failure Checks](05.-failure-checks.md)

### [6. Encapsulation](06.-encapsulation.md)

### [7. Events](07.-events.md)

### [8. Concurrency](08.-concurrency.md)

### [9. Attributes](09.-attributes.md)

### [10. Constructors](10.-constructors.md)

### [11. Class](11.-class-and-specifiers.md)

### [12. Math](12.-math.md)

***

## <mark style="color:green;">API</mark>

### [<mark style="background-color:blue;">Fortnite Digest</mark>](fortnite-digest.md)

#### [ui](fortnite-digest.md#ui)

#### [creative\_devices](fortnite-digest.md#creative\_devices)

#### [vehicles](fortnite-digest.md#vehicles)

#### [teams](fortnite-digest.md#teams)

#### [playspaces](fortnite-digest.md#playspaces)

#### [game](fortnite-digest.md#game)

#### [fortplayerutilities](fortnite-digest.md#fortplayerutilities)

#### [characters](fortnite-digest.md#characters)

#### [building](fortnite-digest.md#building)

#### [assets](fortnite-digest.md#assets)

#### [animation](fortnite-digest.md#animation)

#### [ai](fortnite-digest.md#ai)

### [<mark style="background-color:green;">Unreal Engine Digest</mark>](unreal-engine-digest.md)

#### [ui](unreal-engine-digest.md#ui)

#### [diagnostics](unreal-engine-digest.md#diagnostics)

#### [SpatialMath](unreal-engine-digest.md#spatialmath)

### [<mark style="background-color:red;">Verse Digest</mark>](verse-digest.md)

#### [Simulation](verse-digest.md#simulation)

#### [Tags](verse-digest.md#tags)

#### [Functions, Methods, and Getters](verse-digest.md#functions-methods-and-getters)

#### [Colors](verse-digest.md#colors)

#### [NamedColors](verse-digest.md#namedcolors)

#### [Native](verse-digest.md#native)

#### [Concurrency](verse-digest.md#concurrency)

***

## <mark style="color:green;">Source/Resources</mark>

### EG: [Verse Onboarding Guide](https://dev.epicgames.com/documentation/en-us/uefn/onboarding-guide-to-programming-with-verse-in-unreal-editor-for-fortnite)

### EG: [Programming with Verse](https://dev.epicgames.com/documentation/en-us/uefn/learn-programming-with-verse-in-unreal-editor-for-fortnite)

### EG: [Language Reference](https://dev.epicgames.com/documentation/en-us/uefn/verse-language-reference)

### EG: [Official API](https://dev.epicgames.com/documentation/en-us/uefn/verse-api)

### EG: [Verse Scripting](https://forums.unrealengine.com/tags/c/development-discussion/programming-scripting/148/fortnite/l/latest)

### EG: [Dev Community](https://forums.unrealengine.com/tags/c/development-discussion/programming-scripting/148/fortnite/l/latest)

### EG: [Community Snippets](https://dev.epicgames.com/community/fortnite/snippets)

***

## <mark style="color:green;">Scripts Directory</mark>

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

***

### [View on Github](https://github.com/LilWikipedia/UEFNVersePocketWiki)

***

####

_Use of the Unreal Engine, Unreal Editor for Fortnite and Verse is governed by_ _the terms of the Unreal® Engine_ [End User License Agreement](https://www.unrealengine.com/eula). _A majority of this content was taken from_ [_VERSE DOCUMENTATION_](https://dev.epicgames.com/documentation/en-us/uefn/verse-code-style-guide-in-unreal-editor-for-fortnite) _Such content belongs to EPIC GAMES. Verse icon, UEFN, UEFN icon, Unreal Engine, Unreal Engine logo, Fortnite, & Fortnite icon are property of EPIC GAMES_ **This gitbook is not maintained or endorsed by EPIC GAMES.** It is made for educational purposes only.
