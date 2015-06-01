# iTunes Graphics #
> 3D tool to visualize [iTunes API](https://www.apple.com/itunes/affiliates/resources/documentation/itunes-store-web-service-search-api.html) requests using [Three.JS](https://github.com/mrdoob/three.js/).

### Features ###
* Query iTunes for Movies, TV Shows, Music, Music Videos, Audiobooks, Ebooks, Short Films, Apps, Podcasts.
* Set search count limit (1 to 150).
* Render view in anagplyph 3D (red & cyan glasses needed).
* Click selection to visit iTunes Store page.

### Issues ###
* Click to open iTunes page currently not working.
* Only works locally because of this: `XMLHttpRequest cannot load. Origin [...] is not allowed by Access-Control-Allow-Origin.`
* Very CPU intensive: Slow on a high resolution, lags quickly.

### Possible Enhancements ###
* Handle duplicate posters (or filter out single TV episodes into separate search option).
* Smoother animations.
* Better compute grid layout.