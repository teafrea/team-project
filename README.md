# Escape Room Adventure

A text-based escape room game for the CSC207 Team Project.

**Status:** Project planning. Pending course staff approval.

## Planned Features

- Five connected rooms.
- Collectible items and an inventory.
- Item interactions for unlocking doors.
- Trivia puzzles.
- JSON story loading.
- Saving and loading game progress.

## User Stories

### US1: Pick Up Items

**As a player, I want to pick up items from my current room so I have tools for solving puzzles and escaping.**

**Responsible member:** TBD

**Acceptance criteria:**

1. The game displays collectible items in the current room.
2. Selecting an available item adds it to the player's inventory.
3. The collected item disappears from the room.
4. The inventory displays the collected item's name.
5. Collecting an item twice does not create a duplicate.

### US2: Get Hints

**As a player, I want to request hints when I am stuck so that I can continue solving puzzles and make progress in the game.**

**Responsible member:** TBD

**Acceptance criteria:**

1. The game allows the player to request hints.
2. Requesting a hint displays information relevant to the player's current stage or puzzle.
3. If no hint is available, the game displays a message indicating that no hint is available.

### US3: Use Items

**As a player, I want to use items from my inventory so I can solve puzzles, unlock areas, and find new tools.**

**Responsible member:** TBD

**Acceptance criteria:**

1. The player can view and select an inventory item to use on an object in the current room.
2. Using the correct item solves a puzzle, unlocks an area, or reveals a new tool.
3. Using an incorrect item displays a message explaining that it cannot be used there.
4. Locked areas and restricted tools remain unavailable until the required interaction is completed.
5. Successful interactions update the room and remain completed during the current game session.

### US4: Move Between Rooms

**As a player, I want to move through unlocked exits so that I can explore other rooms and continue my escape.**

**Responsible member:** TBD

**Acceptance criteria:**

1. The game lists the exits in the current room.
2. Choosing an unlocked exit moves the player to the connected room.
3. After moving, the game displays the new room’s name and description.
4. Choosing a locked exit displays a message and keeps the player in the current room.
5. Items in the player’s inventory remain available after moving.

## External API

## Design

## Planned Interface

## Screenshots
