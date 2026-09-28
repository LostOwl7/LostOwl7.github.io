# README.md


There are two stylesheets - `good.css`, and  `bad.css`. 

Your job is to make _two_ different menus using the same valid HTML5
`<nav>` element structure: 
- one that looks good and behaves well, and 
- one that should be as ugly and unusable as you would like it to be.

You must use at least _one_ CSS transition in each CSS file. 

Please detail your process, any people you may have worked with, specific
tutorials that may have found useful, tales of your interactions with
AI, or anything else you might want to document in the space below. 

Not including this part will instantly cost you 10 points:

---

## Process

I started from the starter files. Both pages use a `<nav>` with an unordered list of four links (`href="#"`), and the About link has `class="current"`. The bad page has no logo, just the links.

In both CSS files the links stack vertically by default (phone view). A media query (`min-width: 769px`) switches them to a row on bigger screens.

### Good version
- White bar, Inter font, blue logo text.
- The current link is dark blue with white text.
- Links get a light blue background on hover, with a transition.

### Bad version
- Yellow bar on a yellow page with yellow text, so it is very hard to read.
- Small Creepster font.
- Links jump away when you hover over them (transform transition), so they are hard to click.

## Collaboration / tutorials / AI

- Partner: <!-- name, or "worked alone" -->
- Tutorials/references: <!-- e.g. MDN docs on flexbox, transitions, media queries -->
- AI use: I used Claude (Anthropic's AI assistant) to help draft the HTML, CSS, and this README from the assignment instructions and starter files. <!-- Describe what you changed, tested, or learned yourself. -->
