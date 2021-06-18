# Spartan theme for jsonresume [![npm version](https://badge.fury.io/js/jsonresume-theme-spartan-projects.svg)](https://badge.fury.io/js/jsonresume-theme-spartan-projects

_Forked from [jsonresume-theme-spartan](https://github.com/phoinixi/jsonresume-theme-spartan.git) by Francesco Esposito_

This is an extended version of the json resume theme spartan. I wanted to add a new section calling out specific projects that I worked on:

```
npm install jsonresume-theme-spartan-projects
```

[DEMO](https://phoinixi.github.io/website/resume/spartan)

## Getting started

### Install the command line

The official [resume-cli](https://github.com/jsonresume/resume-cli) to run the development server.

Go ahead and install it:

```
sudo npm install -g resume-cli
```

### Serve theme

While inside the theme folder, simply run:

```
resume serve
```

You should now see this message:

```
Preview: http://localhost:4000
Press ctrl-c to stop
```

### Social Profiles Icons

**Profiles supported with brand colors:**

github, stack overflow, linkedin, dribbble, twitter, facebook, pinterest, instagram, soundcloud, wordpress, youtube, flickr, google plus, tumblr, foursquare.

To have a social icon close the social link profile (or username) it is enough to set a `network` the name of the Social Network (es: 'Stack Overflow').

## Contribute

To test the theme, this is what you'll need:

- [node.js](http://howtonode.org/how-to-install-nodejs)
- [npm](http://howtonode.org/introduction-to-npm)

If you're on Linux, you can simply run:

```
sudo apt-get install nodejs-legacy npm
```

Or if you're on OSX and got [Homebrew](http://brew.sh/) installed:

```
brew install node
```

## License

Available under the [MIT license](http://opensource.org/licenses/mit-license.php).

## Changes to original

- Projects

  - Added a projects section to highlight work done
  - See the resume.example.json for the updates the schema
