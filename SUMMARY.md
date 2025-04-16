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
* [Fortnite Digest](fortnite-digest.md)
* [Unreal Engine Digest](unreal-engine-digest.md)
* [Verse Digest](verse-digest.md)

## Scripts Directory

### `Game`
Contains various Verse scripts related to game mechanics and logic.

#### `asymmetric_multiplayer_balance.verse.txt`
Handles team balancing for asymmetric multiplayer games, ensuring fair team distribution and managing player spawns and invisibility.

#### `balance_teams.verse.txt`
Balances teams in a multiplayer game by assigning players to the smallest team upon joining.

#### `boss_device.verse.txt`
Manages a boss character, enabling it to follow a designated player and interact with a mutator zone.

#### `boss_fight.verse.txt`
Orchestrates a boss fight scenario, managing boss animations, health, states (idle, chasing, attacking), and player interactions within a defined arena.

#### `button_puzzle.verse.txt`
Implements a puzzle involving multiple buttons that toggle associated lights, requiring players to match a specific light sequence to succeed.

#### `capture_the_flag.verse.txt`
Manages a capture-the-flag game mode, including flag interactions, scoring, and team management.

#### `countdown_timer.verse.txt`
Creates a visual countdown timer using a UI text element, starting from a specified duration and triggering an event upon completion.

#### `cyber_tag.verse.txt`
Implements a cyber-themed tag game mode where players can tag others and earn points.

#### `custom_rank_system_device.verse.txt`
Implements a custom player ranking system featuring persistent storage, rank updates based on game events, and UI display via HUD and map indicators.

#### `day_night_loop.verse.txt`
Creates a dynamic day-night cycle, adjusting lighting and environmental effects over time.

#### `DuoReloadSystem.verse.txt`
Implements a respawn and elimination tracking system for duo teams, allowing players to respawn if their partner is alive.

#### `elimination_game_device.verse.txt`
Manages an elimination-driven game mode where players receive weapon upgrades upon eliminations, tracking scores and checking for win conditions.

#### `enemy_wave_spawner.verse.txt`
Spawns and manages waves of AI enemies (creatures or guards), tracking player eliminations per wave and signaling wave completion or game end.

#### `ffa_shuffle_teams_device.verse.txt`
Assigns each player joining a free-for-all game to a unique team at the start of the match.

#### `game_round_device.verse.txt`
Manages game rounds, including start, end, and transitions between rounds, with customizable settings.

#### `killing_spree.verse.txt`
Rewards players with score and HUD messages for consecutive eliminations within a defined time frame.

#### `marker_displace.verse.txt`
Handles the displacement of markers in the game world based on specific triggers or conditions.

#### `opt_in_opt_out_device.verse.txt`
Allows players to opt-in or opt-out using buttons and randomly selects one opted-in player when triggered by another device.

#### `puzzle_game_device.verse.txt`
Implements a logic-based puzzle game where players solve challenges to progress.

#### `spawning_manager_device.verse.txt`
Controls the spawning of players, AI, or objects in the game, ensuring proper placement and timing.

#### `team_elimination_device.verse.txt`
Tracks team eliminations and determines the winning team based on predefined conditions.

#### `team_management.verse.txt`
Handles team management, including assigning players to teams and tracking team-related events.

#### `team_selection_device.verse.txt`
Allows players to select their teams using a UI or device interaction, ensuring balanced team assignments.

#### `vote_manager.verse.txt`
Implements a voting system where players can vote on game options, with results determining the next game state or event.

---

### `Game/Sets`
Contains organized sets of scripts for specific game systems and utilities.

#### `Epic-PlayerStatTrackerSystem`
A system for tracking and managing player statistics.

- **`player_stat_example.verse.txt`**  
  Provides an example implementation of the player stat tracking system.

- **`player_stat_manager.verse.txt`**  
  Manages and updates player statistics, including wins, losses, and scores.

- **`player_stat.verse.txt`**  
  Defines the structure and logic for individual player statistics.

- **`player_stats_table.verse.txt`**  
  Implements a table for storing and retrieving player statistics.

#### `LilWikipedia - ReloadDuos`
A system for managing duo-based reload mechanics.

- **`DuoReloadSystem.verse.txt`**  
  Implements a respawn and elimination tracking system for duo teams.

- **`reloadsystemdiagram.png`**  
  A visual diagram explaining the reload system.

#### `liyability-custom-playspace`
Scripts for managing custom playspaces and team interactions.

- **`custom_playspace.verse.txt`**  
  Manages custom playspaces, including boundaries and interactions.

- **`sample_device.verse.txt`**  
  Provides a sample device for interacting with the custom playspace.

- **`team_manager_pair.verse.txt`**  
  Handles team pairing and management within the custom playspace.

#### `PiEqualsThree - CustomRankSystem`
A system for managing custom player ranks.

- **`game_manager.verse.txt`**  
  Oversees the rank system, including rank updates and interactions.

- **`player_stats_manager.verse.txt`**  
  Tracks and updates player statistics for rank calculations.

- **`rank_manager.verse.txt`**  
  Manages player ranks, including promotions and demotions.

#### `Steinn-1v1-Map`
Scripts for managing 1v1 gameplay mechanics.

- **`Game_Manager.verse.txt`**  
  Manages the overall flow of 1v1 matches, including player pairing, round transitions, and score tracking.

- **`GameUI.verse.txt`**  
  Handles the user interface for 1v1 matches, such as displaying scores, timers, and match status.

#### `Tsaryii-SuperKitX-1.0.1`
A comprehensive kit for advanced game mechanics.

- **`BefuDigest.verse.txt`**  
  Implements a digest system for managing and processing game-related data efficiently.

- **`Classes.verse.txt`**  
  Defines reusable classes and structures for advanced game logic.

- **`DND.verse.txt`**  
  Implements mechanics inspired by Dungeons & Dragons, such as dice rolls and character attributes.

- **`SuperKitX.verse.txt`**  
  The core script of the SuperKitX system, integrating advanced mechanics and utilities.

#### `tuurGevers - NPC-utils`
Utilities for managing NPCs in the game.

- **`Basic_Behavior.verse.txt`**  
  Implements basic NPC behaviors, such as idle, patrol, and follow.

- **`Basic_state_examples.verse.txt`**  
  Provides examples of state-based NPC behaviors for easy customization.

- **`Basic_Statefull_behavior.verse.txt`**  
  Manages stateful NPC behaviors, enabling transitions between different states like attack and defend.

- **`Guard_State_machine.verse.txt`**  
  Implements a state machine for guard NPCs, including patrol, alert, and combat states.

- **`Main.verse.txt`**  
  The main entry point for NPC utilities, integrating various NPC-related scripts.

- **`npc_player.verse.txt`**  
  Manages interactions between NPCs and players, such as combat and dialogue.

- **`Npc_Utils.verse.txt`**  
  Provides general utility functions for NPC management, such as spawning and pathfinding.

- **`Raycasting_utils.verse.txt`**  
  Implements raycasting utilities for detecting objects or players in the game world.

- **`RaycastingPool.verse.txt`**  
  Manages a pool of raycasting operations for efficient detection and interaction.

- **`Statefull_guard_behavior.verse.txt`**  
  Defines stateful behaviors for guard NPCs, including transitions between patrol, alert, and combat states.

- **`Statefull_Guard.verse.txt`**  
  Implements a comprehensive guard NPC system with stateful behavior and interactions.

- **`StateMachine.verse.txt`**  
  Provides a reusable state machine framework for managing NPC states and transitions.

- **`Subscribe.verse.txt`**  
  Implements a subscription system for NPC events, enabling dynamic reactions to game triggers.

- **`utils.verse.txt`**  
  Contains general utility functions for NPC-related operations, such as pathfinding and event handling.

---

### `Helper Scripts`
Contains utility scripts that assist with common tasks and functionalities.

#### `Arrays.verse.txt`
Provides utility functions for sorting integer arrays (`SortIntArray`) and removing specific players from player arrays (`RemoveElementFromArray`).

#### `BeFuDigest(by@Tsaryii).verse.txt`
Implements a digest system for managing and processing game-related data efficiently.

#### `BlankDeviceWithModules.verse.txt`
Provides a template for creating devices with modular components.

#### `ConcurrencyExt.verse.txt`
Extends concurrency utilities, enabling advanced task scheduling and management.

#### `ConvertingMaybeAgent.verse.txt`
Handles conversions of optional agent types to ensure safe and consistent operations.

#### `custom_listenable.verse.txt`
Implements a custom event listener system for handling game events dynamically.

#### `event_device.verse.txt`
Manages event-driven interactions between devices and game elements.

#### `Events.verse.txt`
Defines reusable event structures and handlers for game logic.

#### `float_int_casts.verse.txt`
Provides utility functions for safely casting between float and integer types.

#### `get_agent.verse.txt`
Implements logic for retrieving and managing agent references in the game.

#### `HandleOptionals.verse.txt`
Provides utility functions for handling optional values (`maybe` types) in Verse.

#### `HandleStrings.verse.txt`
Implements string manipulation utilities, such as concatenation and formatting.

#### `hello_world_device.verse.txt`
A simple example device that outputs "Hello, World!" to demonstrate basic Verse scripting.

#### `Maps.verse.txt`
Implements map-related utilities for managing key-value pairs in game logic.

#### `Positionals.verse.txt`
Provides utilities for managing positional data, such as coordinates and transformations.

#### `tick_rate_graph.verse.txt`
Implements a system for visualizing and managing tick rates in the game.

#### `tips.verse.txt`
Provides a collection of helpful tips and best practices for Verse scripting.

#### `tostring_logic.verse.txt`
Implements logic for converting various data types to string representations.

---

### `Object`
Contains scripts related to objects and their behaviors in the game.

#### `color_switch_synchronisedtiles.verse.txt`
Controls a set of color-changing tiles, activating and deactivating them sequentially in a synchronized pattern initiated at game start.

#### `color_switch_tile.verse.txt`
Manages individual color-changing tiles, enabling them to change color based on specific triggers or conditions.

#### `disappear_appear_platform.verse.txt`
Implements platforms that disappear and reappear based on game events or timers, adding dynamic challenges for players.

#### `itemrotator.verse.txt`
Rotates an object continuously or based on specific triggers.

#### `object_follow_player.verse.txt`
Enables an object to follow a player, maintaining a specified distance and orientation.

#### `random_system.verse.txt`
Implements a randomization system for selecting objects or events.

#### `random_teleporter.verse.txt`
Teleports players or objects to random locations within a predefined area.

#### `SignalRemoteToTriggers.verse.txt`
Handles signaling between remote devices and triggers, enabling complex interactions between game elements.

#### `SpawnAndMoveProp.verse.txt`
Spawns props and moves them along predefined paths or based on player interactions.

---

### `CustomCurrency`
Contains scripts related to custom currency systems in the game.

#### `Custom_Player.verse.txt`
Manages player-specific custom currency, including earning, spending, and tracking balances.

#### `Game_Manager.verse.txt`
Oversees the custom currency system, including global settings, transactions, and interactions with other game systems.

---

### `Player`
Contains scripts related to player actions, attributes, and interactions.

#### `AttachScriptToPlayer.verse.txt`
Defines a simple component (`my_component`) and attaches an instance of it to a player when they interact with a designated button device.

#### `damage.verse.txt`
Implements a system for applying damage to players, including health and shield reduction.

#### `double_life.verse.txt`
Grants players a second life, allowing them to respawn once after being eliminated.

#### `DynamicPlayerTeleporter.verse.txt`
Teleports players dynamically to specific locations based on game events or triggers.

#### `freeze_player.verse.txt`
Freezes a player in place, preventing movement for a specified duration.

#### `get_all_fortcharacters.verse.txt`
Retrieves and manages a list of all Fortnite characters currently in the game.

#### `get_closest_player.verse.txt`
Finds the closest player to a specified location or object.

#### `health_and_shield_incrementer.verse.txt`
Gradually increments a player's health and shield over time.

#### `hp_and_shield_manager.verse.txt`
Manages player health and shield values, including regeneration and depletion.

#### `instant_spawn.verse.txt`
Spawns players instantly at predefined locations.

#### `invisibility.verse.txt`
Grants players temporary invisibility, making them undetectable by others.

#### `life_steal.verse.txt`
Implements a life-steal mechanic, allowing players to regain health by dealing damage to others.

#### `loadout_granter_device.verse.txt`
Grants players specific loadouts based on game events or interactions.

#### `move_explosive_to_player.verse.txt`
Moves an explosive object toward a player, triggering an explosion upon contact.

#### `PollingPlayerSpeed.verse.txt`
Monitors and tracks player speed, triggering events based on speed thresholds.

#### `spawn_player_device.verse.txt`
Spawns players at specific locations with customizable settings.

#### `standstill_player_tracker.verse.txt`
Tracks players who remain stationary for a certain duration, triggering events or penalties.

#### `SuperPowerHideOnJump.verse.txt`
Grants players a superpower that activates when they jump, such as temporary invisibility or increased speed.

#### `timed_abilities.verse.txt`
Implements abilities for players that activate for a limited time, such as speed boosts or damage resistance.

#### `underground_teleport.verse.txt`
Teleports players to an underground location, enabling hidden or secret gameplay areas.

---

### `UI`
Contains scripts related to user interface elements and interactions.

#### `custom_progress_bar.verse.txt`
Creates and manages a custom, smoothly updating progress bar UI element for individual players.

#### `loadout_selector_device.verse.txt`
Implements a UI for players to select their loadouts before starting the game.

#### `loadout_vote_selection_device.verse.txt`
Provides a voting interface for players to choose loadouts collectively.

#### `moveable_widget.verse.txt`
Implements a UI widget that players can move around the screen dynamically.

#### `page_manager.verse.txt`
Manages multiple pages of UI elements, allowing navigation between them.

#### `show_ui.verse.txt`
Displays a UI element to players, such as a message or prompt, based on game events.

#### `subtitle_device.verse.txt`
Implements a subtitle system for displaying text-based messages during gameplay.

#### `ui_creator.verse.txt`
Generates dynamic UI elements for players, such as buttons and labels.

#### `ui_dialog.verse.txt`
Implements a dialog system for displaying messages or prompts to players.

#### `ui_dynamics_text_widget.verse.txt`
Creates a dynamic text widget that updates in real-time based on game variables.