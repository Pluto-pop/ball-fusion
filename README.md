<h1 style="color:red;">Ball Fusion Game (Unity)</h1>

<h2 style="color:red;">Introduction</h2>
Ball Fusion Game is a Unity-based puzzle project inspired by the Suika game. It features dynamic object interactions where balls collide, bounce, and merge based on real-world physics principles such as gravity and motion. <br>

The game challenges players to strategically combine objects while managing space within the play area.

<h2 style="color:red;">Objectives</h2>

<h3 style="color:red;">Primary Goal</h3>
- Develop a fun and engaging physics-based puzzle game using Unity.

<h3 style="color:red;">Learning Objectives</h3>
- Implement multiple object collisions and interactions  <br>
- Apply physics concepts such as gravity, motion, and static interactions  <br>
- Design visually appealing and balanced gameplay mechanics  <br>

<h2 style="color:red;">Game Description</h2>

<h3 style="color:red;">Gameplay</h3>
- Players drop balls from the top of the screen  <br>
- Balls collide and interact dynamically  <br>
- When two balls of the same type collide, they merge into a larger ball  <br>
- The goal is to create higher-value balls and maximize score  <br>
- The game ends if the play area fills up  <br>

<h3 style="color:red;">Features</h3>
- Multiple Object Collisions – Real-time interactions between moving balls  <br>
- Bouncing Mechanics – Realistic rebound using physics materials  <br>
- Gravity System – Natural falling motion  <br>
- Motion and Static Physics – Interaction between moving balls and static boundaries  <br>

<h2 style="color:red;">Development Process</h2>

<h3 style="color:red;">Tools Used</h3>
- Engine: Unity (2022.3.39f1)  <br>
- Language: C#  <br>
- Assets:  <br>
  - Custom ball sprites  <br>
  - Particle effects  <br>
  - Physics materials  <br>
  - Audio effects  <br>

<h3 style="color:red;">Key Components</h3>

<b>Game Objects</b>  
- Dynamic Balls – Rigidbody-based objects for physics simulation  <br>
- Static Boundaries – Walls and platforms with colliders  <br>

<b>Physics Elements</b>  
- Physics Materials – Control friction and bounciness  

<b>Scripts</b>  
- Spawner.cs – Handles ball spawning  <br>
- CollisionManager.cs – Manages collision and merging logic  <br>
- GravityController.cs – Controls gravity behavior  <br>
- GameManager.cs – Handles scoring and game state  <br>

<h3 style="color:red;">Workflow</h3>
1. Designed the play area with boundaries and a drop zone  <br>
2. Applied physics materials for realistic behavior  <br>
3. Implemented merging logic for ball upgrades  <br>
4. Added visual and sound effects for feedback  <br>

<h2 style="color:red;">Physics Concepts in Action</h2>

<b>Multiple Object Collisions</b>  
- Managed using Unity’s Rigidbody and Collider components  <br>
- Custom scripts detect and merge similar balls  <br>

<b>Moving Object Collisions</b>  
- Balls change trajectory based on velocity and mass  

<b>Bouncing</b>  
- Controlled using restitution (bounciness)  <br>
- Simulates energy conservation for smooth interaction  <br>

<b>Gravity</b>  
- Constant downward force using Unity’s physics system  <br>
- Custom adjustments for special gameplay effects  <br>

<b>Motion and Static Physics</b>  
- Interaction between moving balls and static walls  <br>
- Friction and drag fine-tune movement  <br>

<h2 style="color:red;">Challenges Faced</h2>
- Balancing physics for realism and gameplay  <br>
- Optimizing collision detection with multiple objects  <br>
- Preventing overlapping and merging glitches  <br>

<h2 style="color:red;">Results</h2>
- Functional prototype with realistic physics interactions  <br>
- Successfully implemented merging mechanics  <br>
- Developed an engaging puzzle gameplay experience <br> 

<h2 style="color:red;">Screenshots</h2>

<h2 style="color:red;">Installation</h2>

```bash
git clone (https://github.com/Arohi-Shah/ball-fusion)
