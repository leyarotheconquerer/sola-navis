# Ludum Dare 43

Theme: Sacrifices must be made

## Sola Navis

Welcome pilot. You have bene tasked with resource collection for our newest
colony. We need you to harvest resources from the asteroid belt surrounding the
planet so we can build facilities for the colonists.

Unfortunately, our fleet was damaged on the journey to this system, so we only
have one fully functional mining ship, and it doesn't have the capacity to
mine all that we need.

You'll need to mind enough resources for us to fix up the broken ships so you
can get us all we need. There's just one catch - you can't keep your old ship.
We'll need to scavenge those parts to make the new ship run properly.

### Core Mechanics

* Fly around the planet
* Harvest resources from asteroids
* Interact with space stations to fix your ship
* Interact with space stations to select a new ship
* Deliver resources to a space station to work towards a new ship

### Ships

* Ships will range from level 1 to level 3 (level 5 if time permits)
* Each level will have multiple options, except for level 1
* Each ship consists of 3 components
	- Harvester - determines what type of resources may be mined
	- Thruster - determines speed of the ship
	- Cargo Bay - determines how many resources may be held
* Each level has a max capacity for each of the components
* To get larger upgrade capacities, you must get a ship of a larger level
* All upgrades to the current ship will be lost when you switch ships

### Stations

* There are 4 stations to visit
	- Shipyard station - provides thruster upgrades
	- Mining station - provides harvester upgrades
	- Harbor station - provides cargo bay upgrades
	- Storage stations - holds resources and ships
		+ Only provides ships of the next level up
* To visit a station, fly in range and interact with it

### Asteroids

* There are different types of asteroids
	- Metal asteroid - cargo bay upgrades
	- Carbon asteroid - harvester upgrades
	- Ice asteroid - thruster upgrades
* Asteroids have different sizes
	- Larger asteroids take longer to harvest but result in more resources
* A certain amount of each resource type must be gathered to win the game (be ready for the colony)

## Development Plan

### Code

* Ship
	* Flight
	* Upgrade components
* Asteroid
	* Harvest
	* Stats
* Stations
	* Interacting
	* Providing upgrades
	* Storing resources
* Level
	* Spawning asteroids
	* Menu
	* Tutorial
	* Victory?

### Assets

* Planet
	* Model
* Asteroids (Variants?)
	* Metal
		* Large
		* Medium
		* Small
	* Carbon
		* Large
		* Medium
		* Small
	* Ice
		* Large
		* Medium
		* Small
* Ship
	* Level 1
		* Base components
	* Level 2
		* Broken components
		* Fixed components
		* Upgraded components
	* Level 3
		* Broken components
		* Fixed components
		* Upgraded components
		* Really upgraded components?
* Station
	* Shipyard
	* Mining
	* Harbor
	* Storage
* UI
	* Ship status indicators
		* Thruster
		* Storage capacity
		* Harvester types
	* Menu of some type
* Sounds
	* Music
	* Ship
		* Harvest sound
		* Flight sound
		* Upgrade sound
* Colony model?
