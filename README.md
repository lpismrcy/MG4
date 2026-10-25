# MG4
## Devlog
Write your Devlog here.
How the FloatAnimation script works is it basically flips a single variable between true and false. When it is false it is coded for the y position to decrease, and when true the y value increases. The amount of time inbetween switching is set by the developer in the component menu, and is set by the Start() function. The variable that is changing between true and false is _up. Due to the Update() method the timer is always decreasing, and the food is always moving in the direction. When the timer reaches zero, it changes the value of _up and resets. 
## Open-Source Assets
- [Quirky animal 3D models](https://assetstore.unity.com/packages/3d/characters/animals/quirky-series-free-animals-pack-178235)
- [City 3D models](https://assetstore.unity.com/packages/3d/environments/simplepoly-city-low-poly-assets-58899)
- [Bite sound effect](https://freesound.org/people/Jofae/sounds/353067/)