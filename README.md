# serviceworker-example

A working example of using [Service Workers](http://www.w3.org/TR/2015/WD-service-workers-20150205/).


## Usage

A server is required for Service Workers, even if it's just a simple server running on `http://localhost` for local developement. Use a server of your choosing. Python's is good:

	python -m SimpleHTTPServer


### Advanced

To tempoarily disable Service Worker caching (for ease of testing), run this from your browser console:

    localStorage.disable_sw = '1'

To resume Service Worker caching, run this from your browser console:

    delete localStorage.disable_sw
