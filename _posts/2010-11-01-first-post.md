---
layout: post
title: First post
tags: [tech]
last_updated: 2010-10-07
published: false
---

This is the first post.  It has been updated since the post so has a last_updated value in the frontmatter.



A JavaScript OpenSearch client that configures itself around an OpenSearch
Description Document, making queries against OpenSearch services a little
easier from JS clients.

## Getting Started
Download the [production version][min] or the [development version][max].

[min]: https://raw.github.com/nsidc/OpenSearchlight/gh-pages/OpenSearchlight-0.1.1.min.js
[max]: https://raw.github.com/nsidc/OpenSearchlight/gh-pages/OpenSearchlight-0.1.1.js

## Usage

Assuming you're trying to use an OpenSearch service whose OSDD
at http://www.example.com/opensearch?description contains the following:


In your web page, the following code will retrieve search results for "steely",
in ATOM format, starting at the second page with ten results per page:


## Documentation
See the [annotated source][annotated_source].

[annotated_source]: http://nsidc.github.com/OpenSearchlight/

## License
OpenSearchlight is licensed under the MIT license.  See [LICENSE.txt][license].

[license]: https://raw.github.com/nsidc/OpenSearchlight/master/LICENSE.txt

## Credit

This software was developed by the National Snow and Ice Data Center, sponsored
by National Science Foundation grant number OPP-10-16048.

## Release History

* 0.1.1
  * Documentation fixes
* 0.1.0
  * Initial release

## Developer Notes

Please don't edit files in the `dist` subdirectory as they are generated via
grunt. You'll find source code in the `src` subdirectory!

While grunt can run the included unit tests via PhantomJS, this shouldn't be
considered a substitute for the real thing. Please be sure to test the
`test/*.html` unit test file(s) in _actual_ browsers.

### Install and Build

_This assumes you have [node.js](http://nodejs.org/) and [npm](http://npmjs.org/) installed already._

1. Test that grunt is installed globally by running `grunt --version` at the command-line.
2. If grunt isn't installed globally, run `npm install -g grunt` to install the latest version. _You may need to run `sudo npm install -g grunt`._
3. From the root directory of this project, run `npm install` to install the project's dependencies.
4. Run `grunt` from the root directory to run the tests and build the packages and documentaion.

### Installing PhantomJS

In order for the qunit task to work properly,
[PhantomJS](http://www.phantomjs.org/) must be installed and in the system PATH
(if you can run "phantomjs" at the command line, this task should work).

Unfortunately, PhantomJS cannot be installed automatically via npm or grunt, so
you need to install it yourself. There are a number of ways to install
PhantomJS.

* [PhantomJS and Mac OS X](http://ariya.ofilabs.com/2012/02/phantomjs-and-mac-os-x.html)
* [PhantomJS Installation](http://code.google.com/p/phantomjs/wiki/Installation) (PhantomJS wiki)

Note that the `phantomjs` executable needs to be in the system `PATH` for grunt to see it.

* [How to set the path and environment variables in Windows](http://www.computerhope.com/issues/ch000549.htm)
* [Where does $PATH get set in OS X 10.6 Snow Leopard?](http://superuser.com/questions/69130/where-does-path-get-set-in-os-x-10-6-snow-leopard)
*
