# au-revoir
A SayonaraJS client for presentations. Made with [Reveal.JS](https://github.com/hakimel/reveal.js/) and [AngularJS](https://angularjs.org/)

![Aurevoir example gif](https://files.aaronthedev.com/$/hgtzb)

# Install

Similar to [Reveal.JS](https://github.com/hakimel/reveal.js/), you can follow the basic to get started.

Simply git clone, or download, this project. And have your sayonara config point to the folder. It will automatically serve the index.html, and use your sayonara server! You can then edit this theme by following and configuring the [Reveal.JS](https://github.com/hakimel/reveal.js/) options at their repo.

# Usage

The way the slides are generated are:

Slide 1: Page and its contents

Vertical Slides: If a page has entry types, it will grab all the entries in each entry type, and add them to the page as page.allEntries. The entries in page.allEntries are then sorted by order, and then displayed vertically. **I'd suggest having only one entryType per page to keep things sorted easier.**

# Contributing

All contributions are welcome! Open a PR, and it shall be reviewed!
