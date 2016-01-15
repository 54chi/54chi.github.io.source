# Ghost

The project is maintained by a non-profit organisation called the **Ghost Foundation**, along with an amazing group of independent [contributors](https://github.com/TryGhost/Ghost/contributors). We're trying to make publishing software that changes the shape of online journalism.

- [Ghost.org](https://ghost.org)
- [Latest Release](https://ghost.org/download/)
- [Support](http://support.ghost.org/)
- [Theme Docs](http://themes.ghost.org)
- [Contributing Guide](https://github.com/TryGhost/Ghost/blob/master/CONTRIBUTING.md)
- [Feature Requests](http://ideas.ghost.org/)
- [Dev Blog](http://dev.ghost.org)

**NOTE: If you’re stuck, can’t get something working or need some help, please head on over and join our [Slack community](https://ghost.org/slack/) rather than opening an issue.**

# Buster
Super simple, Totally awesome, Brute force static site generator for Ghost.

Start with a clean, no commits Github repository.

Generate Static Pages. Preview. Deploy to Github Pages.

- [Buster](https://github.com/axitkhurana/buster)

# Quick Start Install

Make sure you've installed Node.js - We recommend the latest **Node v0.10.x** release. For other versions [click here](http://support.ghost.org/supported-node-versions/). May contain nuts.

## Ghost
1. Download the [latest release](https://ghost.org/download/) of Ghost
1. Unzip in the location you want to install
1. Fire up a terminal
1. `npm install --production`
1. Start Ghost!
    - Local environment: `npm start`
    - On a server: `npm start --production`
1. `http://localhost:2368/ghost` :tada:

More [install docs](http://support.ghost.org/installation/) here in case you got stuck.

<a name="getting-started"></a>

Congrats! You made it. BTW you can also just `npm install ghost` if you're into that sort of thing. NPM afficionados can also read up on using [Ghost as an NPM module](https://github.com/TryGhost/Ghost/wiki/Using-Ghost-as-an-npm-module).

More general [install docs](http://support.ghost.org/installation/) here in case you got stuck.

## Github Pages

1. Follow [this guide](https://pages.github.com/)

## Buster

1. Install Python. You can use [chocolatey](https://chocolatey.org/)
1. Run: `pip install Buster` or `py install Buster` (depends on your python version)
1. cd into your ghost directory
1. `buster setup`
1. Open a different terminal window, cd into your ghost directory and start ghost `npm start`
1. From the other terminal window, generate the static version of the ghost site: `buster generate`
1. Deploy your static site to github: `buster deploy`

If you get stuck, follow [this guide](http://leftofnull.com/2014/02/07/using-github-pages-with-ghost-and-buster-on-windows-part-1/) (which is what I did). Keep in mind that the guide is from 2014, and many things (including the fix for Buster in Windows) have been updated.

# Copyright & License

Copyright (c) 2013-2015 Ghost Foundation - Released under the [MIT license](LICENSE).
