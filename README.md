##Capital One Summit Application for Software Engineers Submission##

[Live Demo with AWS](http://flight-globe.com.s3-website-us-east-1.amazonaws.com/)

[Also hosted on gh pages](https://camelkaiser.github.io/Realtime-Flights/)

The original challenge can be found here: https://www.mindsumo.com/contests/global-data-visualization

A data visualization of realtime plane flights on a physical globe. The plane flights refresh every minute (please allow up to a minute to initially load). It is currently hosted on github pages and uses a CORS proxy to access the data.

Thanks to:
* [Crossorigin.me](https://www.chromeexperiments.com/globe) for providing a working CORS proxy and saving me a ton of grief
* [Flightradar24](https://www.flightradar24.com/0,0/5) for providing a JSON streaming endpoint 
* [Mike van Rossum](https://github.com/askmike/realtime-webgl-globe) for his modifed version of Chrome Experimnt's original globe
* [Chrome Experiments WebGL Globe](https://www.chromeexperiments.com/globe)

##Installation##
To run on a local server, simply
1. Download the repository
2. Navigate to the directory through the terminal
3. Enter 'python -m SimpleHTTPServer 8000' (You may need to change the port if you've already got something there)
