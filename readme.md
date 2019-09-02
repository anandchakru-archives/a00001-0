# Niview template

## Setup

```sh

# NOTE: Both repo should be in the same directory
git clone https://github.com/nesign/niview.git
git clone https://github.com/nesign/a00001.git

# Start and watch for changes
cd niview
npm run start

```

### Open [localhost](http://localhost:4200/?iid=demo1) in browser to load empty invite

Open another terminal and start the designer

```sh
cd a00001
npm run start:dev

```

Start designing now using .src/teamplate/main.html, .src/styles/main.scss & .src/scripts/main.js

## Custom designs

The following files can be used to fit your design needs.
WARNING: These files should be used ONLY to design the invite. All resources must be included, no external assets, no external cdn, no external content, and definitely no XSS. To include a referral link, please write to us.

### main.scss

The css will apply to the whole invite, ensure the sites look and feel is not disturbed.

### main.js

The scripts for designing the invite.

### main.html

The mustache template to define the DOM structure of the invite.

## Before a Pull Request

* Ensure you update the .src/assets/thumbnail-*.jpg files to reflect the changes.
* Ensure the minified version is not too heavy.
* Test the design in all different screen sizes.
* You may use [puppeteer](https://github.com/GoogleChrome/puppeteer#usage) to automate thumbnail.
