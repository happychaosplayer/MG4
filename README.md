# MG4
## Devlog
The FloatAnimation script animates the fish food GameObjects as components of the objects by first setting the _timer to the switch speed in Start(). Then in every frame, _up is passed into the parameters of the if statement (defaulted to false) then the y value of the transform is positive, if _up is true then the y value of the traansform is negative. Along with this, as the _timer float value is negative the bool value is flip-flopped and the _timer is reset to loop everything previously described.

## Open-Source Assets
- [Quirky animal 3D models](https://assetstore.unity.com/packages/3d/characters/animals/quirky-series-free-animals-pack-178235)
- [City 3D models](https://assetstore.unity.com/packages/3d/environments/simplepoly-city-low-poly-assets-58899)
- [Bite sound effect](https://freesound.org/people/Jofae/sounds/353067/)