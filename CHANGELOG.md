# Changelog

All notable changes to Karma Kargo will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.1.2] - 2026-03-14

### Fixed

- Fixed text clipping and layout overflow on displays with DPI scaling above 100%
- Fixed commodity and ship icons not appearing in the game
- Fixed application process remaining in the background after closing the window

## [0.1.1] - 2026-03-10

### Fixed

- Fixed crash when starting a new game on a fresh installation
- Fixed theme colors not loading correctly on first launch

## [0.1.0] - 2026-03-08

### Added

- Main menu with New Game, Continue, High Scores, Settings, and Quit
- New Game screen where players enter their name and optional seed to start a game
- Navigation map — interactive island map with destination selection, travel cost
  preview, double-click to sail, and one-click sailing
- Trade screen — unified flat-list view with all commodities in a single row,
  inline sliders and text input, color-coded prices showing deals relative to
  cross-island averages, and commodity categories (Food, Luxury, Raw Materials,
  Weapons, Trade Goods)
- Queue multiple trades and execute them all at once — supports multi-round
  trading (sell cargo, buy new goods, execute again) within a single port visit
- Keyboard shortcuts for the trade screen: arrow keys to navigate and adjust
  amounts, S to sell all, D to decline, F to fill cargo, Enter/Tab to edit,
  Ctrl+Enter to execute
- Sail confirmation dialog warns when you have unexecuted pending trades
- Cargo tracks cost basis per slot — ACOG (Average Cost of Goods) shows the
  weighted average price paid for held commodities
- Turn summary screen — end-of-turn recap showing actions taken and wealth
  changes with deltas versus the previous turn
- End game and score screen — final net worth, wealth breakdown, game stats,
  wealth curve chart, and game seed for sharing
- 50-turn competitive phase with net worth scoring, followed by unlimited
  sandbox play via Continue Playing on the score screen
- Market simulation — prices respond to supply and demand; markets replenish
  each turn
- Travel system — sail between islands with distance-based provision costs
- Automatic provision resupply when docking at an island — gold is deducted at a
  flat rate; a warning appears if funds are insufficient for a full resupply
- Provision sell-back slider on the trade screen — sell provisions for gold or
  buy them back at the same price
- Emergency provisions indicator shows extra provisions available from edible
  cargo, with a red warning when provisions are too low to reach any island
- Stranding mechanic — running out of provisions strands the ship; cargo is
  consumed to survive, with a drift penalty toward the nearest port
- Save and resume — game progress is automatically saved each turn and can be
  resumed via Continue on the main menu; each game is stored as a separate file
  in the Saves folder
- High scores — persistent leaderboard tracking best competitive scores
- Settings screen for managing player preferences (default player name, default
  turns, auto-save, show turn summary, confirm before sail)
- Version number, copyright info, and website link on the main menu
- Multiple islands, trade commodities, and ship classes
- Seeded random number generation for reproducible gameplay — share your seed
  from the score screen

### Changed

- Trade screen cargo sliders are taller with larger bay counter boxes for
  improved readability
- Text input fields have a recessed/inset appearance with gradient fill, bevel
  edges, and rounded corners
- Buttons render with a vertical gradient fill and highlight/shadow edge lines,
  giving them a 3D appearance

[Unreleased]: https://github.com/gb-inc/karma-kargo-game/compare/v0.1.2...HEAD
[0.1.2]: https://github.com/gb-inc/karma-kargo-game/compare/v0.1.1...v0.1.2
[0.1.1]: https://github.com/gb-inc/karma-kargo-game/compare/v0.1.0...v0.1.1
[0.1.0]: https://github.com/gb-inc/karma-kargo-game/commits/v0.1.0
