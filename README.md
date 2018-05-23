# Front-End Developer Cheat Sheet

This is a quick-and-dirty guide to getting hired as a front-end developer in 2018.

It covers:

- Skill set
  - The minimum skill set you need and how to get it
  - Skill set nice-to-haves
  - Things on the horizon you should be preparing for

- Stuff you need
  - Resume
  - Portfolio site, GitHub, or both

- Interviews
  - Topics that come up frequently
  - Things that will net you bonus points
  - Dos and don'ts (I just wanted a third thing here)

This guide covers topics that I’ve found come up in interviews fairly frequently. In-depth knowledge of every item on the following lists is not absolutely necessary, but you should be able to at least talk about them intelligently, should they come up.

Note: Items marked with * are not usually necessary, but will score you bonus points

## Skill set

### Must haves

#### React or Angular

You need functional knowledge of at least one current framework or you're basically unemployable. Working knowledge of a second is a good bonus. TODO: Add some advice on how to pick which one to learn. If you're in a hurry though, learn React.

- [React tutorial](https://reactjs.org/tutorial/tutorial.html)
  - 1 to 1.5 hours
- [Angular tutorial](https://angular.io/tutorial)
  - About 4 hours (3 hours + 1 hour of initialization)

## General
HTTP lifecycle

The names of the rendering engines of major browsers

Webservices:
- what they are
- RESTful
- SOAP

HTTP methods:
- GET
- POST
- DELETE
- PUT

HTML5 vs. HTML 4.x, XHTML, DHTML:
- What’s new in HTML5?
- What’s been deprecated?
- Browser support

CSS3 vs. CSS 2.x:
- What’s new in CSS3?
- What’s been deprecated?
- Browser support

Common IE bugs and how to work around them:
- Doctype and quirks mode/strict mode
- Box model/double margin
- Issues with floating elements
- hasLayout/zoom: 1

Be able to define the following:
- AJAX
- graceful degradation and progressive enhancement
- responsive design
- client-side scripting and server-side scripting
- prototypal inheritance
- MVC/MVVM architecture*
- service-oriented architecture*
- JSONP*

Be able to discuss common web technologies:
- AJAX
- HTML
- CSS
- JavaScript
- JSON
- XML
- PHP, Ruby, or other server-side language*
- SQL*
- XSL/XSLT*

Have a working knowledge of common development tools:
- version control tools (Git or SVN are most common, bonus points for CLI usage)
- FTP (duh)
- editor of your choice (Visual Studio and Eclipse are common, but not required)
- debugging, inspection, and performance analysis tools:
  - IE Debug Bar
  - Firebug
  - Chrome/Safari built-in development tools
  - YSlow*
  - proxies/network analysis tools (Charles)*
- build tools (Grunt, Yeoman, Brunch, etc)*
- package managers (Bower, NPM)*
- templating engines (handlebars, mustache, etc)*

## JavaScript
DOM access methods (without a library)

Basic types (strings, integers, booleans, etc)

Looping structures

Variable scope and hoisting

Event handling

Object syntax

hasOwnProperty

Closures, callbacks, and anonymous methods

Same origin policy/CORS:
- how it applies to AJAX
- how JSONP gets around this

jQuery:
- what it is (framework vs. library)
- noConflict
- using it with “fallbacks”
- plugins:
  - what they are
  - how to use them
  - how to write them

Common problems/misconceptions with JavaScript:
- lack of namespaces
- unexpected comparison behaviors (“truthy” vs. “falsey”, == vs. ===)
- NaN vs. null vs. undefined

The “this” keyword:
- what it is
- how to use it
- how it changes with execution scope, particularly anonymous methods

Arrays:
- creation (different methods of)
- access/referencing
- adding to and push()
- removing from and pop()
- associative vs. indexed
- multi-dimensional arrays*

Be able to explain the differences between:
- popular frameworks (jQuery, ExtJS, Prototype, MooTools)
- comparison operators (ie, === vs. ==)
- object properties and object methods
- “unobtrusive” vs. “obtrusive” JavaScript implementations
- event bubbling and event capturing
- static and dynamically typed languages*
- compiled and interpreted languages*
- classical and prototypal inheritance*
- design patterns*

JavaScript vs Java:
- dynamic, weakly typed vs. static, strongly typed
- interpreted at run time vs. compiled
- prototypical vs. classical inheritance

## HTML
Appropriate and inappropriate usage of table elements

IDs vs. classes, and how this applies to the interaction between JavaScript and CSS

What the doctype is, and how it works (particularly for IE)?

What is the DOM?

Page optimization

Why should you combine and compress external resources?

Why should you load scripts at the end of the page?

Appropriate usage of different image formats

Semantic markup

Write W3C valid markup* (do this anyway, but none of my employers have ever validated my markup)
SEO*

Templating languages (HAML, Jade, etc)*

## CSS
~### IE hacks~
- ~Wacky IE CSS selector hacks (underscore, tick, asterisk, etc)~
- ~IE-only conditional inclusion of stylesheets~
- ~IE-specific classes on the body or HTML element (see HTML5 boilerplate)~

### Box model

*I was asked this on a call as recently as May 2018*

Margin vs. padding
- How margin, padding, and border affect the width of an element

*TODO: box-sizing*

### Selectors

Selector specificity, and how it may affect performance

What !important does, and why you shouldn’t use it

*TODO: But when might you want to use it?*

External vs. inline styles, and why external styles are preferable

### Resets

What CSS “reset” and "normalize" utilities are, and what they do

### Units

Defining sizes: pxs vs. ems vs. pts vs. percentages

*TODO: Viewport units*

### Layout
CSS frameworks and grid systems (Bootstrap, 960 GS, Blueprint)*

*TODO: CSS grid, flexbox*

### Floats

What floats are, and how to use them

What “clearfix” is, and how it is used

### "Responsive"

- Media types
- Media queries (particularly in regards to mobile devices and pixel density)

### Preprocessors

(LESS, SASS/Compass, Stylus), and why they are useful*

*TODO: Pros/cons vs CSS custom properties and related native functions*

Be able to explain the differences between:
- values of the display attribute (block, inline, none, etc)
- values of the position attribute (absolute, relative, fixed, etc)
- display: none and visibility: hidden

How to use:
- pseudo-elements
- attribute selectors

### Major Bonus Points*
A GitHub account (seriously, people are super-impressed with this for some reason)

Front end development best practices

Having written original plugins (double posted if hosted on your GitHub account)

Working knowledge of:
- jQuery UI and jQuery Mobile
- HTML5 Boilerplate
- CSS3 PIE, Moderinzr
- JSLint, JSHint
- CSS Lint
- popular CMSes (Wordpress, Django, etc)
- optimization techniques
- images & CSS spriting
- scripts (combination, compression, minification/packing)
- CSS (combination, compression, minification)

General knowledge of:
- graphic design, UI/UX design, and usability
- JavaScript MVC/MVVM frameworks (backbone, ember)
- Accessibility and Section 508 compliance
- Unit testing/test-driven development
- Agile development practices
- NodeJS
- Coffeescript
- mobile-oriented JavaScript frameworks (Sencha Touch, Zepto, etc)

## Interview Advice
When someone comes into an interview and seems to know how to do *everything* I assume it means they don’t know how to do any of it as good as I want them to.  Answer any questions you’re asked, but when summarizing your general knowledge, stick to topics specific to the position you are applying for.

When asked about a particular topic you’re not an expert on, don’t be afraid to say you know about something, even if you’ve never used it - but be honest.

I like it when people can talk about what books, blogs, etc they’ve read to keep current with their craft.

Being able to speak of personal projects usually scores you points because it shows that you are genuinely interested in web technologies, outside of what you do for work.

### Resources and Sites of Interest

### General Help
- [https://developer.mozilla.org/en-US/](https://developer.mozilla.org/en-US/)
- [http://stackoverflow.com](http://stackoverflow.com)

#### Blogs
- [http://www.smashingmagazine.com](http://www.smashingmagazine.com)
- [http://www.alistapart.com](http://www.alistapart.com)
- [http://css-tricks.com](http://css-tricks.com)
- [http://www.quirksmode.org](http://www.quirksmode.org)
- [http://www.sitepoint.com](http://www.sitepoint.com)

#### Specs
- [http://www.w3.org](http://www.w3.org)
- [https://whatwg.org/](https://whatwg.org/)

#### Other
- [http://tympanus.net/codrops](http://tympanus.net/codrops)
- [Front-End Developer Interview Questions](https://github.com/darcyclarke/Front-end-Developer-Interview-Questions)

### It's 2018 and you've been asleep for the past 3 years

TODO: Identify:

- what you absolutely need to know to get a job in 2018
  - ES6
  - React OR Angular
- what are you probably going to need to know next year
- what doesn't really matter anymore

Here's what you've missed (details to follow soon):

- ES6 (ES2015)
  - Modules
  - Webpack
  - Babel
- Second (third?) generation of MVC(-ish) frameworks
  - Angular
  - React
  - Vue.js
- CSS
  - CSS custom properties
  - Grid
  - Masking
  - No one really cares if you're good at CSS anymore
    - *Seriously, no one cares*
