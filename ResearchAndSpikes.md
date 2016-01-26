#Research Initiatives/Spikes

###React Native
Redux, Immutable.js

Considerations:
		-API client must implement HPKP
		-need encrypted data store for at least PGP Keys, possibly for all data
		

###Block Chaining

###Server vs No Server

###Google Map alternative

###Fused Location Provider API
- Our issue with using Fused Location Provider API is that it's not open source and we aren't sure what Google will log. It also requires significantly more setup than the older and less performant Location Manager. We will be replacing our current implementation of the Fused Location Provider API with [Mapzen's LOST project](https://github.com/mapzen/LOST).
- When we move our native mobile implementations to React Native, we will be plugging the above module into a fork of the [React Native Android Geolocation](https://github.com/lxsameer/react-native-geolocation-android) package.

###HMAC
