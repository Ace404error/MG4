# MG4
## Devlog

The FloatAnimation script works to animate the fish food GameObjects by translating them on the y-axis (either up or down). When Start() is ran, the member variable _timer is set equal to the variable _switchSpeed, which has a set value. This sets the duration for which the fish food GameObject will move up and down. From there, the amount the fish food GameObject moves up or down is calculated by multiplying the _moveSpeed variable by Time.deltaTime. For moving down specifically, the direction is determined through an if-statement that switches the next value of _up to the opposite of its current value when _switchSpeed reaches zero. These are both calculated every frame using the Update() method. 

## Open-Source Assets
- [Quirky animal 3D models](https://assetstore.unity.com/packages/3d/characters/animals/quirky-series-free-animals-pack-178235)
- [City 3D models](https://assetstore.unity.com/packages/3d/environments/simplepoly-city-low-poly-assets-58899)
- [Bite sound effect](https://freesound.org/people/Jofae/sounds/353067/)