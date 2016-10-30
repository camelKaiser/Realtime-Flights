##Capital One Summit Application for Software Engineers Submission##



A data visualization of realtime plane flights and airports on a physical globe. The plane flights refresh every minute (please allow up to a minute to initially load). It is currently hosted on github pages and uses a CORS proxy to access the data.

[Live Demo with AWS](http://flight-globe.com.s3-website-us-east-1.amazonaws.com/)

[Also hosted on gh pages](https://camelkaiser.github.io/Realtime-Flights/) (Used to test active changes)

The original challenge can be found here: https://www.mindsumo.com/contests/global-data-visualization

Made with:
* [Crossorigin.me](https://www.chromeexperiments.com/globe) for providing a working CORS proxy and saving me a ton of grief
* [Flightradar24](https://www.flightradar24.com/0,0/5) for providing a JSON streaming endpoint 
* [Mike van Rossum](https://github.com/askmike/realtime-webgl-globe) for his modifed version of Chrome Experimnt's original globe
* [Chrome Experiments WebGL Globe](https://www.chromeexperiments.com/globe)

![alt text](https://github.com/camelKaiser/Realtime-Flights/blob/master/example.png "Green Airports, Red Planes")

##Installation##
To run on a local server, simply

1. Download the repository
2. Navigate to the directory through the terminal
3. Enter 'python -m SimpleHTTPServer 8000' (You may need to change the port if you've already got something there)
