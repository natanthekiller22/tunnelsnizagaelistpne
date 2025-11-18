# Sami & Somo: Underground Survival

## Game Concept

A 2D pixel art survival game where players control Sami and Somo, two characters tasked with building an underground tunnel network to save humanity from an impending collapse. Starting from a single tunnel entrance, players must carefully construct an expansive underground habitat for their extended family while managing structural integrity and preventing cave-ins.

## Story

Humanity stands on the brink of collapse. Surface life has become unsustainable, and the only hope for survival lies beneath the earth. Sami and Somo, two brave pioneers, have discovered the entrance to what could become humanity's last refuge. With only a single pier marking the tunnel's beginning, they must dig deep, build smart, and create a thriving underground civilization for all their cousins before it's too late.

## Characters

### Sami
- **Role**: Primary digger and structural engineer
- **Abilities**: Strong excavation skills, can identify weak points in tunnel structure
- **Pixel Art Style**: Distinctive character sprite with mining tools

### Somo  
- **Role**: Support builder and resource manager
- **Abilities**: Reinforcement specialist, manages support beams and tunnel stability
- **Pixel Art Style**: Complementary character design with construction equipment

## Core Gameplay Mechanics

### 1. Tunnel Construction
- **Starting Point**: Begin with a single tunnel entrance (pier/entry point)
- **Digging System**: Click or select areas to excavate soil and rock
- **Dual Character Control**: Switch between or simultaneously control Sami and Somo
- **Resource Collection**: Gather materials while digging (wood, stone, metal)

### 2. Structural Integrity System
- **Collapse Mechanics**: Tunnels can cave in if not properly supported
- **Support Structures**: Place beams, pillars, and reinforcements
- **Stability Indicators**: Visual feedback showing tunnel strength (color-coded or crack patterns)
- **Weight Distribution**: Consider the load from above when planning tunnel layouts
- **Soil Types**: Different underground layers with varying stability characteristics

### 3. Underground Habitat Development
- **Living Spaces**: Create rooms for family members (cousins)
- **Population Management**: Each cousin has basic needs (space, air, safety)
- **Resource Networks**: Build ventilation shafts, water collection systems
- **Expansion Planning**: Balance growth with structural safety

### 4. Progression System
- **Family Arrival**: Cousins gradually arrive seeking shelter
- **Technology Upgrades**: Unlock better tools, support materials, and building techniques
- **Depth Challenges**: Deeper tunnels offer better resources but higher risks
- **Time Pressure**: Surface conditions worsen over time, creating urgency

## Tunnel Engineering Research Requirements

### AI Development Instructions: Research These Topics

To create realistic and educational gameplay, research and implement the following tunnel engineering concepts:

#### 1. **Soil and Rock Mechanics**
- Types of soil (clay, sand, gravel, bedrock) and their stability properties
- Load-bearing capacity of different geological layers
- Water table effects on tunnel stability
- Angle of repose and natural arch formation

#### 2. **Support Structure Types**
- **Timber Support**: Traditional wooden beams and props
- **Steel Arches**: Modern I-beams and arch supports
- **Rock Bolts**: Anchoring systems for hard rock
- **Shotcrete**: Sprayed concrete for tunnel lining
- **Mesh Reinforcement**: Wire mesh and fiber reinforcement

#### 3. **Tunnel Boring Methods**
- Cut-and-cover method
- Drill and blast techniques
- Sequential excavation method (SEM/NATM)
- Tunnel boring machine (TBM) concepts - simplified for game
- Hand excavation limitations and dangers

#### 4. **Structural Safety Principles**
- Minimum pillar width ratios
- Crown and invert support requirements
- Proper spacing of support structures
- Ventilation shaft requirements
- Emergency escape routes

#### 5. **Common Failure Modes**
- Roof collapse (crown failure)
- Wall buckling
- Floor heaving
- Water infiltration damage
- Progressive collapse scenarios

#### 6. **Historical Tunnel Examples**
Study these for inspiration:
- Cu Chi Tunnels (Vietnam) - extensive underground networks
- Coober Pedy (Australia) - underground living spaces
- Burlington (UK) - underground city
- Montreal Underground City - modern underground infrastructure

## Technical Specifications

### Game Engine Recommendations
- **Godot Engine**: Excellent 2D support, open-source, good pixel art tools
- **Unity 2D**: Robust toolset with extensive asset support
- **GameMaker Studio**: Specialized for 2D games, beginner-friendly
- **Pygame**: Python-based, good for prototyping

### Pixel Art Requirements

#### Resolution and Style
- **Base Resolution**: 320x180 or 640x360 (scalable)
- **Pixel Size**: 16x16 or 32x32 tiles for environment
- **Character Sprites**: 16x16 or 32x32 pixels
- **Color Palette**: 32-64 colors for cohesive aesthetic
- **Art Style**: Retro-inspired with clear readability

#### Asset Requirements
- **Characters**: Sami and Somo with 4-8 directional animations
- **Terrain Tiles**: 
  - Soil (light, medium, heavy)
  - Rock layers (sedimentary, hard rock)
  - Underground features (caves, water, ore deposits)
- **Support Structures**:
  - Wooden beams (vertical, horizontal, diagonal)
  - Metal supports
  - Reinforcement indicators
- **UI Elements**:
  - Structural integrity meter
  - Resource counters
  - Mini-map of tunnel network
  - Cousin population tracker

#### Animation Requirements
- Digging animations (pickaxe swings, shovel work)
- Tunnel collapse sequences
- Character idle and walking cycles
- Beam placement animations
- Environmental effects (dust, falling debris, water drips)

### Game Systems to Implement

#### 1. Physics System
```
- Grid-based or tile-based physics
- Gravity simulation for unsupported blocks
- Cascading collapse mechanics
- Structural stress propagation
```

#### 2. AI for NPCs (Cousins)
```
- Pathfinding through tunnel network
- Basic needs system (rest, safety)
- Reaction to danger (cave-ins, flooding)
- Task assignment (helping with construction)
```

#### 3. Procedural Generation
```
- Randomized underground layer composition
- Resource node placement
- Underground hazard distribution (water pockets, unstable zones)
```

#### 4. Save System
```
- Tunnel layout persistence
- Character progress and upgrades
- Population status
- Resource inventory
```

## Development Phases

### Phase 1: Core Mechanics (MVP)
- [ ] Basic 2D movement for Sami and Somo
- [ ] Simple digging mechanics (remove tiles)
- [ ] Basic collapse system (unsupported tiles fall)
- [ ] Support beam placement
- [ ] Simple pixel art for characters and tiles

### Phase 2: Structure and Stability
- [ ] Implement advanced collapse mechanics
- [ ] Different soil types with unique properties
- [ ] Structural integrity visualization
- [ ] Support structure variety
- [ ] Weight distribution calculation

### Phase 3: Population and Progression
- [ ] Cousin arrival system
- [ ] Living space creation
- [ ] Resource management
- [ ] Technology upgrade tree
- [ ] Time-based pressure mechanics

### Phase 4: Polish and Content
- [ ] Enhanced pixel art and animations
- [ ] Sound effects and music
- [ ] Tutorial system
- [ ] Additional tunnel types and challenges
- [ ] End-game scenarios

## Game Features Checklist

### Essential Features
- [ ] Dual character control system
- [ ] Grid-based digging and building
- [ ] Realistic collapse mechanics
- [ ] Support structure placement
- [ ] Resource gathering and management
- [ ] Population counter (cousins saved)
- [ ] Structural stability indicators
- [ ] Save/Load functionality

### Advanced Features
- [ ] Water infiltration mechanics
- [ ] Ventilation system requirements
- [ ] Temperature management
- [ ] Underground farming/food production
- [ ] Power generation (underground)
- [ ] Multiple tunnel levels/floors
- [ ] Random events (earthquakes, cave-ins)
- [ ] Multiplayer cooperative mode

### Quality of Life Features
- [ ] Undo last action
- [ ] Blueprint/planning mode
- [ ] Auto-save functionality
- [ ] Adjustable game speed
- [ ] Zoom in/out functionality
- [ ] Tunnel naming system
- [ ] Statistics tracking

## Controls (Suggested)

### Keyboard
- **WASD / Arrow Keys**: Move Sami
- **IJKL**: Move Somo (when dual control enabled)
- **Tab**: Switch between Sami and Somo
- **E**: Dig/Interact
- **Q**: Place support structure
- **R**: Rotate structure
- **1-9**: Quick select tools/structures
- **Space**: Pause/Menu
- **M**: Map view
- **Esc**: Pause menu

### Mouse
- **Left Click**: Dig/Select
- **Right Click**: Place support
- **Scroll Wheel**: Zoom
- **Middle Click**: Pan camera

## Win/Loss Conditions

### Victory Conditions
- Successfully house X number of cousins (e.g., 50, 100)
- Survive until surface conditions stabilize
- Create a self-sustaining underground civilization
- Reach a certain depth milestone

### Failure Conditions
- Major collapse that blocks all escape routes
- Unable to house arriving cousins (population overflow)
- Critical resource depletion
- Character death (if permadeath is enabled)

## Educational Value

This game teaches:
- **Engineering Principles**: Structural integrity, load distribution, safety factors
- **Resource Management**: Planning, budgeting materials, sustainability
- **Risk Assessment**: Balancing expansion with safety
- **Problem Solving**: Creative solutions to spatial and structural challenges
- **Historical Context**: Real-world tunnel engineering and underground living

## AI Development Guidelines

### Step-by-Step Implementation Guide

1. **Initial Setup**
   - Choose game engine and set up project
   - Create basic 2D scene with camera controller
   - Implement grid/tile system for underground world

2. **Research Phase**
   - Study tunnel engineering basics (see research section above)
   - Review existing mining/digging games for inspiration (Minecraft, Terraria, Dig Dug)
   - Compile reference material for pixel art style

3. **Prototype Development**
   - Create simple character movement
   - Implement basic tile removal (digging)
   - Add simple gravity for unsupported tiles
   - Test core loop: dig, place support, repeat

4. **Art Creation**
   - Design Sami and Somo character sprites
   - Create tile set for different soil/rock types
   - Design support structure sprites
   - Develop UI mockups

5. **Systems Integration**
   - Implement structural integrity calculation
   - Add resource collection and inventory
   - Create support placement mechanics
   - Develop collapse detection and animation

6. **Content and Balance**
   - Add cousin arrival system
   - Implement progression and upgrades
   - Balance difficulty curve
   - Create tutorial sequence

7. **Testing and Refinement**
   - Playtest core mechanics
   - Gather feedback on difficulty
   - Optimize performance
   - Polish animations and effects

### Code Architecture Suggestions

```
/src
  /characters
    - sami.gd/cs/py
    - somo.gd/cs/py
  /environment
    - tile.gd/cs/py
    - soil_types.gd/cs/py
    - collapse_system.gd/cs/py
  /structures
    - support_beam.gd/cs/py
    - structural_integrity.gd/cs/py
  /systems
    - resource_manager.gd/cs/py
    - population_manager.gd/cs/py
    - progression_system.gd/cs/py
  /ui
    - hud.gd/cs/py
    - menu.gd/cs/py
/assets
  /sprites
    /characters
    /tiles
    /structures
  /audio
  /fonts
```

## Resources for AI Development

### Tunnel Engineering Resources
- "Tunnel Engineering Handbook" - search for academic papers
- YouTube channels: Practical Engineering, Real Engineering
- Mining and tunnel construction documentation
- Civil engineering textbooks on underground structures

### Game Development Resources
- Pixel art tutorials: Lospec, Pixel Joint
- 2D game development courses on YouTube
- Game design documents from similar games
- Physics simulation tutorials

### Similar Games for Reference
- **Terraria**: 2D digging and building mechanics
- **Minecraft**: Resource management and structural building
- **Dig Dug**: Classic tunnel digging gameplay
- **Motherload**: Underground mining progression
- **SteamWorld Dig**: Modern take on digging mechanics
- **Oxygen Not Included**: Underground colony management

## License

This README serves as a comprehensive design document and technical specification for AI developers to create the Sami & Somo tunnel building game. Implementation details and code are to be developed based on these guidelines.

## Getting Started for AI Developers

1. Review this entire document thoroughly
2. Conduct additional research on the topics listed in "Tunnel Engineering Research Requirements"
3. Choose your preferred game engine and set up the development environment
4. Start with Phase 1 MVP implementation
5. Iterate based on playtesting and feedback
6. Refer back to this document for feature priorities and technical specifications

Remember: The goal is to create an engaging, educational, and fun game that teaches players about tunnel engineering while providing an exciting survival challenge. Focus on making the structural mechanics intuitive and the pixel art visually appealing. Good luck building Sami & Somo's underground world!