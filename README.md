# MG4
## Devlog

FloatAnimation:
It makes the fish food goes up and down. First there are the _switchspeed and _movespeed variable which are serialized so that you can change in engine. Second, In the void start method it sets the time to the _switchspeed; the timer decreases with Time.deltatime in the Update method, which means after 3 second the _switchspeed is going to equal to 0. Third, in the Update method, it constantly checks if the timer is less than or equals 0. If it reaches 0, its going to change _up variable to false or true accordingly. Last the if statement checks the _up variable. If it is true it moves the fish food up, down if it is false.

## Open-Source Assets
- [Quirky animal 3D models](https://assetstore.unity.com/packages/3d/characters/animals/quirky-series-free-animals-pack-178235)
- [City 3D models](https://assetstore.unity.com/packages/3d/environments/simplepoly-city-low-poly-assets-58899)
- [Bite sound effect](https://freesound.org/people/Jofae/sounds/353067/)
