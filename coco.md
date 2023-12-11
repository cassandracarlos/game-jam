### Scene Creation

.scn is the extension for Godot scene

1. Background
2. Ground blocks (tileset)
3. Character (via Pixel Adventure on itch.io)

Resize textureRect on scene (Background Image)
TileMap node:
1. One-time configuration of tileset
2. Split tilemap into small pixels

Input map
Character (sprite) setup - character movement and collision
Sprite animation (import frames)
1. default
2. jumping
3. running

---

ParallaxScrollingScene
    ParallaxBackground
        ParallaxLayer
            Sprite
        ParallaxLayer2
            Sprite
        ParallaxLayer3
            Sprite
        ParallaxLayer4
            Sprite