# Web Spider Obstacle Course (WSOC)

* [Source](https://github.com/postmodern/wsoc/)
* [Issues](https://github.com/postmodern/wsoc/issues)
* [Email](mailto:postmodern.mod3 at gmail.com)

## Description

The Web Spider Obstacle Course (WSOC) is an example web server that tests
the thoroughness and resilience of Web Spiders.

## Features

* Written as a Sinatra application.
* Provides Specs for the expected behavior of a web spider for every link in
  the Obstacle Course.
* Provides an Obstacle Course containing:
  * Empty links.
  * Circular links.
  * Links with relative-paths.
  * Links with absolute-paths.
  * Remote links.
  * <tt>javascript:</tt> links.
  * Links within +frameset+ and +iframe+ tags.
  * Cookie protected pages.
  * HTTP 300, 301, 302, 303 and 307 Redirects.
  * Meta-Refresh Redirects.
  * HTTP Baisc Auth protected pages.

## Synopsis

    $ wsoc_server -p 8080

## Requirements

* [json](http://flori.github.com/json/) ~> 1.4
* [sinatra](http://sinatrarb.com) ~> 1.0

## Install

    $ gem install wsoc

## License

WSOC - The Web Spider Obstacle Course

Copyright (c) 2009-2011 Hal Brodigan (postmodern.mod3 at gmail.com)

This program is free software; you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation; either version 2 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program; if not, write to the Free Software
Foundation, Inc., 51 Franklin St, Fifth Floor, Boston, MA  02110-1301  USA
