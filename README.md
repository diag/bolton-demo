Bolton is an edge analytics system that gives you all the data, like full HTTPS payloads, metrics and logs, availabile to query in real time running right along with your application.  Bolton helps you find the right information, and allows you to search, alert, report, analyze and forward off your application's data in flight.

Developers spend more time running other people's code than their own. However, it's really hard to give your developer peer an easy-to-diagnose way of showing her what you were doing with her code. Bolton endeavors to be kind of a 'Tcpdump for Applications', allowing you to capture output from an application, work with the data, diagnose an issue and share the capture output with peers.

# Getting Started

Bolton is available via two methods, direct download for Linux x86-64 systems, or a Docker container.  The Docker container comes with a few pre-installed items that make it easier to demo, but both options should work equally well.

## Direct Download

Grab bolton from http://dl.taktak.io/linux/bolton (`curl -o bolton http://dl.taktak.io/linux/bolton`) and `chmod 755 ./bolton`.  

## Docker container

`docker run -p 9999:9999 -it taktak/bolton-demo bash`

## Start Bolton

Once you have bolton downloaded, start bolton using `bolton start`. Open your web browser to http://localhost:9999/ and follow the instructions from there.
