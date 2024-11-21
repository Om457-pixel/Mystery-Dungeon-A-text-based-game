# Mystery-Dungeon-A-text-based-game


### Path Details:
- **Dungeon Entrance:** The start of your adventure. Will you enter or turn back?
- **Fork in the Path:** A critical decision—choose between a path with flickering torches or one shrouded in darkness.
- **Monster:** An encounter with a fierce monster. Will you fight, flee, or bribe the creature?
- **Secret Door:** A hidden passage that may lead to treasure or a cursed fate.
- **Trap Room:** A deadly room filled with spikes and timed traps. Can you disarm it in time?
- **Treasure:** The final goal—open the chest to find either hidden treasure or your demise.

## How to Play

1. Run the game by executing the Python script.
2. You will be prompted with choices during the game. Type your responses to make decisions that guide your adventure.
3. The game will progress based on your choices, leading to different outcomes such as winning the treasure, escaping traps, or facing a game-over scenario.

## Installation

To play *Mystery Dungeon*, ensure you have Python installed. Then, run the script directly from your terminal or preferred Python environment.

```bash
python mystery_dungeon.py
```


```memraid
%% A simple flowchart explaining "How to Play" Mystery Dungeon

graph TD
    A[Start Game] --> B[Enter Dungeon]
    B --> C{Choose to Enter?}
    C -->|Yes| D[Meet Mysterious Guide]
    C -->|No| E[Game Over]
    D --> F{Trust the Guide?}
    F -->|Yes| G[Glowing Map Given]
    F -->|No| H[Continue Without Guide]
    G --> I[First Path Decision]
    H --> I[First Path Decision]
    I --> J{Choose Path: Left or Right?}
    J -->|Left| K[Encounter Monster]
    J -->|Right| L[Find Secret Door]
    K --> M{Fight, Flee, or Bribe?}
    L --> N{Open or Ignore Door?}
    M -->|Fight| O[Win or Lose Monster Battle]
    M -->|Flee| P[Stumble into Trap Room]
    M -->|Bribe| Q[Monster Lets You Pass]
    O --> R[Find Treasure]
    P --> S[Disarm Trap or Search Exit?]
    Q --> R[Find Treasure]
    N -->|Open| T[Find Cursed Treasure or Gems]
    N -->|Ignore| R[Find Treasure]
    S -->|Disarm| R[Find Treasure]
    S -->|Search| R[Find Treasure]
    T --> U[Game Over (Cursed Treasure)]
    T --> V[Win (Rare Gems)]
    R --> W{Open Treasure Chest?}
    W -->|Open| X[Win (Hidden Treasure) or Game Over (Mimic)]
    W -->|Leave| Y[Exit Dungeon Safely]
    X --> Z[Game Over or Win!]
    Y --> Z[Game Over (End of Adventure)]

