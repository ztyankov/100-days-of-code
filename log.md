# 100 Days of Code - Log - Zdravko Tyankov

The log of my #100DaysOfCode challenge. Started on *[January 1, Friday, 2021]*.

#### ⚡ I will code for at least an hour every day for the next 100 days

## Day 4: Monday, 01/04/2021

**Time Spent:** 1h

**Today's Progress**

- Refactor the search functionality into a separate component.
- Cleanup some of the old code.
- Add Chips (Tags) for meal types.
- Pick a new name: Z's Next Meal Planner

**Thoughts:** Doing 1 hour of coding after a long work day is not as easy as it seemed. I dabbled with some forms today, but decided against using them for now. I'll need to come up with a good way of filtering data at multiple levels.

**Link(s) to work**

- [Svelte Meal Planner Commit](https://github.com/ztyankov/svelte-random-meal-selector/commit/5670b5a4a4dc9ed420fa9cba5fe417e5e87f6d18)

**Resources**

- [Introduction to Svelte Tutorial IBM](https://developer.ibm.com/technologies/front-end-development/tutorials/svelte-introduction/)
## Day 3: Sunday, 01/03/2021

**Time Spent:** 1h25m

**Today's Progress**

- I learned about Svelte Material UI and integrated it with my random selector project
- Started using Card, TextField and some other Material components to make the app look better

**Thoughts:** Setting up Material UI for Svelte with my setup was a bit of a challenge. I had to install `rollup-plugin-postcss` and `node-sass` and make updates to the rollup.config.js. Also, I need to create a basic theme `src/theme/smui-theme.scss`. I found out that I can't use CSS classes on Components in Svelte so I had to resort to other tricks to get a meal card appear selected on click.

**Link(s) to work**

- [Svelte Random Selector Commit](https://github.com/ztyankov/svelte-random-meal-selector/commit/57839bd51fecca4d7133eddd3245ecf7817ac5f7)

**Resources**

- [Svelte Material UI](https://github.com/hperrin/svelte-material-ui)
- [Svelte Material UI Doc](https://sveltematerialui.com/)
- [Svelte Material UI - Card Example](https://github.com/hperrin/svelte-material-ui/blob/master/site/src/routes/demo/card.svelte)

## Day 2: January 2, 2021

**Time Spent:** 1h30m

**Today's Progress**

- I spent some time in the Svelte documentation to learn more about:
    - Scaffolding a new project
    - Reactivity rules
    - Svelte REPL ([read–eval–print loop](https://en.wikipedia.org/wiki/Read%E2%80%93eval%E2%80%93print_loop))
    - The Rollup module bundler
- Followed a tutorial for setting up a full stack app with Svelte and Express.
- Started working on a random meal selector app.
- Created the basic data structure for the meals, types, a display card.

**Thoughts:** Running Svelte and Express together was pretty easy. I was able to setup the whole thing and get a basic route running in under 30 minutes. I had some trouble exporting/importing types with Typescript in Svelte. In the end I was able to figure it out and it made sense the way it works. I used what I learned yesterday in setting up the new app.

**Link(s) to work**

- [Svelte Random Selector Commit](https://github.com/ztyankov/svelte-random-meal-selector/commit/c84efb0585982131d2c348b20c520064d52eb1db)

**Resources**
- [Full Stack Svelte App](https://medium.com/swlh/full-stack-development-starter-svelte-and-express-831aefee41c0)
- [Svelte Getting Started](https://developer.mozilla.org/en-US/docs/Learn/Tools_and_testing/Client-side_JavaScript_frameworks/Svelte_getting_started)

## Day 1: January 1, 2021

**Time Spent:** 1h30m

**Today's Progress**

- Created a simple Todo App with Svelte based on a tutorial from coding CodingTheSmartWay.
- Made the following enhancements:
    - Moved the todo data in a JSON file that loads when the component is mounted
    - Updated some of the styling for the cursor pointer and the way the input and the todo labels were handled
    - Switched out some uses of forEach() with map()
    - Cleaned up the code
    - Enable Typescript and add basic types

**Thoughts:** The code for the Todo App was fairly simple and easy to understand.

**Link(s) to work**

- [Svelte Todo App Commit](https://github.com/ztyankov/svelte-todo-app/commit/72d65ff20a3d7b559238b8e3b0b25d564998084b)

**Resources**

- [9 Projects to Build](https://dev.to/simonholdorf/9-projects-you-can-do-to-become-a-frontend-master-in-2020-n2h)
- [Building a Svelte Todo App](https://medium.com/codingthesmartway-com-blog/building-a-svelte-3-todo-app-from-start-to-deployment-1737f72c23a6)
- [Svelte Docs](https://svelte.dev/docs)
- [Svelte and Typescript](https://svelte.dev/blog/svelte-and-typescript)

## Day 0: January 1, 2021

**Time Spent:** 30m

**Today's Progress**

- Went over the rules and guidelines for the 100 days of code challenge.
- Forked the Log repo and started my own log.
- Came up with a list of goals:
    - Learn Svelte by building sample projects.
    - Improve React.js skills by building sample projects.
    - Learn and experiment with server side rendering frameworks and technologies.
    - Work on a personal project idea about building habits.

**Thoughts:** I'm trying to get into the habit of learning and experimenting with technologies, tools and frameworks that I don't get to use in my day-to-day work. This sounds like a good way of achieving that goal. This is sprint 0. Let's see how things go. I don't know how I feel about tweeting about this challenge every day though.

**Link(s) to work**

- [100-days-of-code repo](https://github.com/kallaway/100-days-of-code)