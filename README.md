

%% A simple flowchart explaining "How to Play" Mystery Dungeon

```memraid
graph TD;
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
