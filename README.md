# Breaker #

[![Build Status](https://travis-ci.org/awochna/breaker.svg?branch=master)](https://travis-ci.org/awochna/breaker)
[![Coverage Status](https://coveralls.io/repos/github/awochna/breaker/badge.svg?branch=master)](https://coveralls.io/github/awochna/breaker?branch=master)

A Circuit Breaker in Elixir for making HTTP(S) requests to external resources.
Uses [HTTPotion](https://github.com/myfreeweb/httpotion) to make requests.

Currently, this is still very basic and a work in progress, but the final product will:

* Fail requests to an unhealthy service.
* Have a half-open state, for testing service health.
* Allow you to force a request through.


## Contributing ##

Bug reports are welcome and contributions are encouraged.
If something isn't working the way it should or a convention isn't being followed, that's a bug.
If there isn't documentation for something, I consider that a bug, too.

Please note that this project is released with a Contributor Code of Conduct. By participating in this project, you agree to abide by its terms.

## License ##

This project is released under the MIT license, as detailed in the included `license.txt` file.
