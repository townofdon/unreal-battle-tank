# battle tank concept

## rules

- player spawns into the world as a controllable tank
- player has 1 life
- N AI tanks also spawn in
- N AI mortars also spawn in
- objective: elliminate all enemy fortifications
- failed objective: player dies
- bonus: steal enemy intelligence files
- player tank can take N damage
- enemy tanks/mortars can take N damage

## assets needed

- tank meshes
- mortar meshes
- meshes
  - tank
  - mortar
- materials
  - gunmetal, other metals
  - tread (if diff material)
- particles
  - barrel flash
  - smoke for projectile trajectory
  - explosion
- sound effects
  - firing a round
  - shell impacting the ground
  - shell impacting rock
  - shell impacting an object (tank or mortar)
  - barrel moving
  - turret moving
  - engine sound
- music
  - background music to create tension

## gameplay

- player and AI get spawned into a random location on map
  - could be previously defined spawn points

## controls

- [w] - forward
- [s] - backward
- [a] - rotate left
- [d] - rotate right
- mouse look - move the barrel

## development iterative cycle

- `world` => `tank` => `controls` => `player 2 / AI` => `UI` => `repeat`
