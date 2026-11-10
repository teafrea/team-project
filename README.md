# Escape Room Adventure

## Team Information

### Team Members

- Zhiyu Li
- Wenqi Luo
- Yue Pan
- Jan Fung
- Bard Pan

---

## Project Description

### Domain

A text-based escape room game for the CSC207 Team Project. Players explore connected rooms, collect items, and solve puzzles to escape.

**Status:** Project planning. Pending course staff approval.

**Planned features:**

- Five connected rooms.
- Collectible items and an inventory.
- Item interactions for unlocking doors.
- Trivia puzzles.
- JSON story loading.
- Saving and loading game progress.

---

## User Stories

### User Story 1: Pick Up Items

**As a player, I want to pick up items from my current room so I have tools for solving puzzles and escaping.**

**Responsible member:** TBD

**Acceptance criteria:**

1. The game displays collectible items in the current room.
2. Selecting an available item adds it to the player's inventory.
3. The collected item disappears from the room.
4. The inventory displays the collected item's name.
5. Collecting an item twice does not create a duplicate.

### User Story 2: Get Hints

**As a player, I want to request hints when I am stuck so that I can continue solving puzzles and make progress in the game.**

**Responsible member:** TBD

**Acceptance criteria:**

1. The game allows the player to request hints.
2. Requesting a hint displays information relevant to the player's current stage or puzzle.
3. If no hint is available, the game displays a message indicating that no hint is available.

### User Story 3: Use Items

**As a player, I want to use items from my inventory so I can solve puzzles, unlock areas, and find new tools.**

**Responsible member:** TBD

**Acceptance criteria:**

1. The player can view and select an inventory item to use on an object in the current room.
2. Using the correct item solves a puzzle, unlocks an area, or reveals a new tool.
3. Using an incorrect item displays a message explaining that it cannot be used there.
4. Locked areas and restricted tools remain unavailable until the required interaction is completed.
5. Successful interactions update the room and remain completed during the current game session.

### User Story 4: Move Between Rooms

**As a player, I want to move through unlocked exits so that I can explore other rooms and continue my escape.**

**Responsible member:** TBD

**Acceptance criteria:**

1. The game lists the exits in the current room.
2. Choosing an unlocked exit moves the player to the connected room.
3. After moving, the game displays the new room’s name and description.
4. Choosing a locked exit displays a message and keeps the player in the current room.
5. Items in the player’s inventory remain available after moving.

### User Story 5: Save and Load Game Progress

**As a player, I want to save my game and load it later so that I can continue my escape without starting over.**

**Responsible member:** TBD

**Acceptance criteria:**

1. The player can save their current game progress.
2. The saved progress includes the current room, inventory, remaining room items, solved puzzles, and unlocked exits.
3. Loading a saved game restores these states so the player can continue from where they left off.
4. The saved game remains available after closing and restarting the application.
5. If saving or loading fails, the game displays an error message without changing the current game state.
6. If no saved game exists, the game informs the player when they attempt to load one.

---

## Use Cases

### Use Case 1: Pick Up Items

**Related user story:** User Story 1.

**Actor:** Player.

**Precondition:** The player is in a room containing a collectible item.

**Main flow:**

1. The game displays the collectible items in the current room.
2. The player selects an item to pick up.
3. The game adds the item to the player's inventory and removes it from the room.
4. The inventory displays the collected item's name.

**Alternative flow:** An item that has already been collected cannot be collected again.

**Postcondition:** The item is in the player's inventory and is no longer available in the room.

### Use Case 2: Get Hints

**Related user story:** User Story 2.

**Actor:** Player.

**Precondition:** The player has an active game.

**Main flow:**

1. The player requests a hint.
2. The game checks for a hint relevant to the current stage or puzzle.
3. The game displays the hint.

**Alternative flow:** If no hint is available, the game displays a message indicating that no hint is available.

**Postcondition:** The player receives a relevant hint or a message explaining that none is available.

### Use Case 3

TBD after team discussion.

### Use Case 4

TBD after team discussion.

### Use Case 5

TBD after team discussion. Add additional use cases as needed.

---

## Minimal Viable Product (MVP)

MVP scope and individual assignments are TBD after team discussion.

| Team Member | MVP Use Case |
|-------------|--------------|
| Zhiyu Li | TBD |
| Wenqi Luo | TBD |
| Yue Pan | TBD |
| Jan Fung | TBD |
| Bard Pan | TBD |

---

## Entities

Entity design is TBD after team discussion.

### Entity 1

TBD.

### Entity 2

TBD. Add additional entities as needed.

---

## API Usage

**API Name:** TBD.

**Documentation:** TBD; add the documentation link after selecting an API.

**How it is used in the program:** TBD after team discussion.

---

## Design Diagrams

### UML Class Diagram

TBD after the team agrees on the entities and architecture.

### Sequence Diagrams

TBD after the team agrees on the use cases.

---

## How to Run

---

## Notes

- This README is a planning draft for team discussion.
- Confirm the team roster, remaining user stories, use cases, MVP assignments, entities, and API choice with the team.
- The planned interface and screenshots will be added when available.
- See [TeamContract.md](TeamContract.md) for the team's collaboration expectations.
