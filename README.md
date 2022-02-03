# mid-level-web-dev

```
A mid-level can just crack on with stuff

-- me
```

## Intro

This resource is primarily a learning and self assessment tool for
junior web developers to have a list of skills/tasks to have under
their belt, in order to push for a mid level developer role.

This project has a list of tasks that one can tick off, though some
are a little abstract, so I have also tried to include a list of small
projects that reference the tasks they cover. As per the point above,
the focus at this entry level, is to simply complete the task. Writing
maintainable, testable and ultimately 'clean' code is an ongoing
pursuit as one progresses to senior and beyond.

## Philosophy

This is a highly opinionated collection of tasks a mid level developer
should be able to do. It's not an exhaustive list, and of course many
will feel some elements probe too deep in the wrong direction, or some
areas are left completely unchallenged. Feel free to raise an issue with
suggestions and opinions!

Developers are the bulk of the workforce; juniors are still learning
the ropes, and seniors are spread between mentoring, planning and
resolving complex issues within their field. To this end, a developer
should just be able to get work done, no matter the task - this isn't
to say they 'know' everything, but rather, they have encountered
enough issues across a range of problem areas. They need to know where
to start looking, what to start googling, and potentially, who to
start asking for subject matter expertise within their company.

Some tasks put an emphasis on completing a task from memory - this is
simply a means to an end; I see this resource primarily as a learning
tool, so one should repeat certain tasks enough until the appropriate
skill is internalised, creating a firm foundation for further skills
to build upon.

To my mind a developer who is someone that can make something work,
and their journey towards senior is understanding how to build
something that will *also* scale.

You won't know clean code until you have stumbled and fallen face
first into your own filth laden code - ideally with a good mix of
other people's too to really push the point home. You need to write a
lot of code, which means repetition, practice, and enthusiasm to just
build things. Once you've come to hate your own creations,
congratulations, welcome to the club, you're now ready to learn about
[clean code](https://www.youtube.com/watch?v=7EmboKQH8lM&list=PLmmYSbUCWJ4x1GO839azG_BBw8rkh-zOj&t=221s).


# Tasks
## Fundamentals
### HTML

- [ ] set up a html file that greets the user
- [ ] create a link to a new page
- [ ] create a form that submits a payload to the server
- [ ] embed an iframe
- [ ] change part of the page with inline styles
- [ ] change an element with classes and a style block
- [ ] change an element with classes and a style-sheet
- [ ] include some inline JavaScript to log to the console
- [ ] link a JavaScript file that logs to the console
- [ ] read this introduction to [accessiblity](https://developer.mozilla.org/en-US/docs/Learn/Accessibility), and bookmark it - you'll likely want to expand your knowledge over time.
- [ ] get comfortable navigating the Mozilla docs, e.g [for iframes](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/iframe), and then also read:
  - [ ] [aria-labels](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Attributes/aria-label)
  - [ ] skim: [elements](https://developer.mozilla.org/en-US/docs/Web/HTML/Element) and try to familiarise yourself with each

### CSS
only worry about doing this in an evergreen browser, but don't use
anything marked as experimental

- [ ] change colours of elements
- [ ] change colours of elements
- [ ] change fonts with CSS (no changing html tags)
- [ ] layout a component using Flexbox
- [ ] layout a component using Grid
- [ ] layout a page using Flexbox
- [ ] layout a page using Grid
- [ ] mix Grid and Flexbox to create a page with components

useful links:
- [mozilla: css layout](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout)
- [css tricks: flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)

### JavaScript

Find somewhere that is quick and easy to experiment, personally I like
using the chrome devtools' `console`, as it's always around on any
person's machine. There are other tools, like REPLs for the terminal
and text editors. See what works for you.

#### Built-in
- [ ] use builtin data structures
  - [ ] Array (get really comfortable with this)
    - [ ] familiarise yourself with ALL methods
    - [ ] memorise how to use `map`, `find`, `filter`, `forEach`
    - [ ] memorise how to use `reduce` by:
	  - [ ] sum a list of numbers
	  - [ ] use `Object.entries` to iterate through an object and the reduce it back into a new object
  - [ ] Object (get really comfortable with this)
    - [ ] create objects with nested objects and nested arrays, with nested objects etc
    - [ ] memorise how to use `map`, `find`, `filter`, `forEach`
  - [ ] familiarise yourself with Set
  - [ ] familiarise yourself with  Map

#### DOM
- [ ] manipulate the DOM using JavaScript 
	- [ ] add new elements
	- [ ] change the values of an existing element on the page
	- [ ] change the styles of an element on the page
	- [ ] get all elements with a class and change them in one go
- [ ] add a callback function to a button
- [ ] add a callback function to a form and perform validation on the data before sending it to the server

#### Callbacks / Async
The projects lay out a little more on this, but some good places to
practice this are [GitHub's api](https://docs.github.com/en/rest).

- [ ] watch [this talk on the event loop](https://www.youtube.com/watch?v=8aGhZQkoFbQ), then watch it again and talk about it at dinner parties to make sure you understand the concepts
- [ ] memorise how to use `fetch` to make `GET` and `POST` requests


useful links:
- [mozilla: JavaScript built-ins](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects)
### Node.js

There's a lot of great stuff on Mozilla, in particular, this [intro](https://developer.mozilla.org/en-US/docs/Learn/Server-side/First_steps)
followed by [this](https://developer.mozilla.org/en-US/docs/Learn/Server-side/First_steps/Introduction) should help give some context to server side code.

- [ ] set up a small express server that returns:
  - [ ] a html page
  - [ ] some JSON
  - [ ] some JSON change changes depending on the path
  - [ ] some JSON change changes depending on the query parameters
  - [ ] a html page, which then asks the server for a number of assets such as images, css and JavaScript
 - [ ] repeat the above with Koa.js and  compare the differences

### HTTP
#### HTTPS
#### REST
#### GraphQL
#### Cookies
#### Headers
#### Iframe
### Processed to JavaScript / CSS
#### TypeScript
#### SCSS / SASS
#### Awareness of others

Google the following, see if you can get the gist of what they are
trying to do and why someone might want to use it over JavaScript

- Elm
- ClojureScript

### Web Assembly

- [ ] At a high level what is Web Assembly?
- [ ] What is a potential use case for Web Assembly?

## Component 'Frameworks'
### React
#### React Hooks
#### React Redux
### Next.js
### Svelte
## Testing
### JavaScript Testing
### Component Testing
### Browser Testing
## Project Setup / Tooling

## Projects
