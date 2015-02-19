Basis
===

Basis is a starter theme for building custom WordPress projects. It is simple and effective.

Getting Started
===

### Installation

If you have not done so yet, install [grunt-init][] by typing `npm install -g grunt-init`.

Once grunt-init is installed, clone this build template in your `~/.grunt-init/` directory. It's recommended that you use git to clone this template into that directory, as follows:

```
git clone git@github.com:velograph/basis.git ~/.grunt-init/basis
```

### Usage

At the command-line, cd into an empty directory, for your theme. e.g. wp-content/themes/yourtheme run this command and follow the prompts. The defaults in the prompts have an uppercase letter. so (n/Y) will mean 'Yes' is the default and (N/y) will mean 'No' is the default.

```
grunt-init basis
```

_Note that this template will generate files in the current directory, so be sure to change to a new directory first if you don't want to overwrite existing files._

Install the NPM modules required to actually process your newly-created project by running:

```
npm install
```

Run Grunt so it can generate your style.css

```
grunt
```

During development run

```
grunt watch
```
