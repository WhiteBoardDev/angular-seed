## OVERVIEW

A kickstarter for [AngularJS](http://angularjs.org) projects. Includes testing, automation, project structure, and package management

***

## QUICK START

Install Node.js and then:

```
$ git clone <this repo>
$ cd angular-seed
$ sudo npm -g install grunt-cli karma bower
$ npm install
$ bower install
$ grunt watch
```
then:

```
$ grunt connect
```

## DIRECTORY STRUCTURE

At a high level, the structure looks roughly like this:

```
angular-seed/
  |- config/
  |- |- build.config.js
  |- |- module.prefix
  |- |- module.suffix
  |- src/
  |  |- app/
  |  |  |- <app logic>
  |  |- assets/
  |  |  |- <static files>
  |  |- common/
  |  |  |- <reusable code>
  |  |- less/
  |  |  |- main.less
  |- vendor/
  |- .bowerrc
  |- bower.json
  |- Gruntfile.js
  |- package.json
```


## GRUNT

To make the build even faster, tasks are placed into two categories: build and
compile. The build tasks (like those we've been discussing) are the minimal
tasks required to run your app during development.

Compile tasks, however, get your app ready for production. The compile tasks
include concatenation, minification, compression, etc. These tasks take a little
bit longer to run and are not at all necessary for development so are not called
automatically during build or watch.

To initiate a full compile, you simply run the default task:

```
$ grunt
```

This will perform a build and then a compile. The compiled site - ready for
uploading to the server! - is located in `bin/`, taking a cue from
traditional software development. To test that your full site works as
expected, open the `bin/index.html` file in your browser. Voila!


***

## LICENSE

The MIT License (MIT)

Copyright (c) 2014

Craig Nishina <craig.nishina@gmail.com>

Evan Harris <evan.tyler.harris@gmail.com>


Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.


