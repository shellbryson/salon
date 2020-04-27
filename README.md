# Edinburgh Literary Salon

This is a custom Ghost theme for the Salon

## Installation

### Prerequisites

Your local machine must be capable of running a node development environment

* `nodejs` (10 or later)
* `gulp` (installed globally)
* `yarn` (installed globally)

### Step 1 - install ghost

* Install Ghost locally (see https://ghost.org/docs/install/local/)
* Start Ghost and make sure it's working. Ghost should then be running on your local machine

### Step 2 - download theme

Checkout this project into `<your_gost_folder>/content/themes/`

### Step 3 - install theme

From a terminal, inside the theme we just dowloaded, run `yarn install`

### Step 4 - start development

Run `yarn dev` - this will compile the theme and remain running. While running, any changed files will trigger a recompile of the theme.

### Step 5 - using the theme

Launch ghost (locally, as installed in step 1). From the admin, go to the Design > Themes section and pick the `Salon` theme. So long as `yarn dev` is running, any changes to your theme will be reflected in the local version of your Ghost site.

### Step 6 - deploying the theme (to your live site)

* From another terminal, find your ghost theme folder (`<your_gost_folder>/content/themes/salon`)
* Run `yarn zip` - this will generate a compiled zip of all the files needed for the live theme.
* From your live site, go to admin > design > themes, and upload the new theme. It should activate immediately.

> Caution: do not accidentally 'upload' this theme to your local development copy as it will break.

## Tips

* To stop any of the `yarn` processes, simply press `ctrl` + `c`

## Development

Changes to the theme should source controlled via Git.
