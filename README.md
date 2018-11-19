[![CircleCI](https://circleci.com/gh/ElpisSolar/digital-hub.svg?style=svg)](https://circleci.com/gh/ElpisSolar/digital-hub)
# DigitalHub

DigitalHub is an open-source [Jekyll](http://jekyllrb.com) e-book reader optimised for mobile phones. It serves a large collection of [Project Gutenberg](https://www.gutenberg.org/) books straight to your mobile browser. 

This website is served through a Raspberry Pi 3, powered by a solar mobile phone charging station (find out more [here](https://elpissolar.com/digital-platform/)), and will be made available in various refugee camps around the world.

This repository is a work in progress and we are always looking for contributions!

### Development

- `master` for development and pull requests.
- `development` for testing/working on new features.
- `gh-pages` for the demo page.

Check out the demo at [https://elpissolar.github.io/digital-hub/](https://elpissolar.github.io/digital-hub/)

#### Running locally

1. Clone this repo
2. Install required dependencies with [Bundler](http://bundler.io/)

        bundle install
3. Run the site with Jekyll

        bundle exec jekyll serve --watch
4. Visit the site at [http://localhost:4000](http://localhost:4000)

### License

**Jekyll theme based on 'hikari' by Mathieu Mayer-Mazzoli**
- <https://themes.gohugo.io/hikari/>

The MIT License (MIT)

Copyright (c) 2015 Mathieu Mayer-Mazzoli

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
