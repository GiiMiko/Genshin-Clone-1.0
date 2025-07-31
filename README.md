# Genshin Clone 1.0

This project is an educational clone of Genshin Impact built in Unity using C#.  
It is not intended for commercial use but as a learning exercise in game development.

## Structure

The Unity project uses the following folder organization:

```
GenshinClone/
├── Assets/
│   ├── Characters/Player/Scripts/PlayerMovement.cs
│   ├── Scripts/
│   ├── World/Terrains/
│   ├── UI/HUD/
│   └── Resources/
├── .gitignore
└── README.md
```

- **Assets/Characters/Player/Scripts/PlayerMovement.cs** – script controlling player movement.  
- **Assets/Scripts/** – other gameplay scripts.  
- **Assets/World/Terrains/** – terrain assets and scenes.  
- **Assets/UI/HUD/** – UI elements for the heads-up display.  
- **Assets/Resources/** – additional resources such as prefabs, materials or textures.

## Getting Started

To work with this project:

1. Clone the repository:
   ```bash
   git clone https://github.com/GiiMiko/Genshin-Clone-1.0.git
   ```
2. Open the project in Unity (2021 or newer).
3. Open the `Main` scene or create your own scenes within `Assets/World/Terrains/`.

## Contributing

Pull requests are welcome. When adding new functionality, please create a new commit per feature and update the README or documentation if necessary.
