# DotPlan

DotPlan is a Middleman site setup designed to be used locally to collate and collect notes, thoughts and plans.

## Pre-requisites

`bundle install`

## Usage

It can be used in two ways - the most ideal way is to clone this repository, and write your plans in the `source/plans` folder as markdown plans (`.markdown` files). These will be excluded automatically from source control, so good to back these up using Dropbox, iCloud or another file syncing service of some kind. This will allow you to easily pull down updates to DotPlan, and separates your plan data from the source control for the site itself.

Alternatively, you can fork this particular repo, remove the `source/plans/*.markdown` line from `.gitignore` and check in any plans to source control. This will make keeping up to date with upstream updates for DotPlan harder, but will allow version control on your plans, which may or may not be a good thing depending upon the data and plans you wish to keep there.

Setup as you would any other Middleman site - it'll work locally using:

`middleman server`

Or better yet, use something like [Pow](http://pow.cx/) for a better local server. You could even build and sync the site to S3 or somewhere else externally accessible if sharing with a team.

## License

Copyright 2018 Elliott Draper <el@ejdraper.com>

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.