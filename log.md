# 100 Days of Code - Log - Zdravko Tyankov

The log of my #100DaysOfCode challenge. Started on *[January 1, Friday, 2021]*.

#### ⚡ I will code for at least an hour every day for the next 100 days

## Day 23: Tuesday, 02/02/2021

**Time Spent:** 45m

**Today's Plan**

- I started looking at some new technologies and frameworks: Next.js, AWS Amplify, GraphQL.
- Started working on a Workshop about a multi-user blog.

**Link(s) to work & Resources**

- [Building a Server-less Multi-user Blogging Platform](https://youtu.be/13nYLmjZ0Ys?t=892)
## Day 22: Monday, 02/01/2021

**Time Spent:** 1h30m

**Today's Plan**

- Improve the weather app functionality and temperature conversions
- Add temp units to the store and make them available to all components that need them
- Add some transitions

**Link(s) to work & Resources**

- [Work Commit](https://github.com/ztyankov/svelte-random-meal-selector/commit/380572927e11663eab0cf0f77c91869b36dbda7d)
- [Svelte Workshop - Weather App](https://www.youtube.com/watch?v=35-ZGjqECks&t=6447)

## Day 21: Friday, 01/29/2021

**Time Spent:** 2h30m

**Today's Plan**

- Completed first half of Svelte Weather app workshop

**Link(s) to work & Resources**

- [Work Commit](https://github.com/ztyankov/svelte-random-meal-selector/commit/3f20aae2cb4483987d8b76b05a579d9fcf218541)
- [Svelte Workshop - Weather App](https://www.youtube.com/watch?v=35-ZGjqECks)

## Tuesday - Thursday: Skipped. Busy work week.
## Day 20: Monday, 01/25/2021

**Time Spent:** 3h30m

**Today's Plan**

- Finished implementing multiple components with TailwindCSS to build up an updated Card
- Fixed issues with search and filtering after the Snowpack integration
- Started styling buttons and input fields

**Thoughts:** Debugging in a Snowpack environment is not great. Going through the transpiled JS code is not very intuitive. I'm learning more about Tailwind and components styling. Things are getting a bit repetitive, so I started pulling some styles into the common styles.css file.

**Link(s) to work & Resources**

- [Work Commit](https://github.com/ztyankov/svelte-random-meal-selector/commit/2eb0cc9020fad8188a6da98d31ada85af2c1970b)

## Day 20: Sunday, 01/24/2021 - Skipped :(
## Day 19: Saturday, 01/23/2021

**Time Spent:** 3h

**Today's Plan**

- Converted my meal planner project form Rollup with Material UI to Snowpack with TailwindCSS
- Integrated with the svelte-spa-router and add basic routes from another project
- Added a prettier configuration for svelte
- Implemented some basic authentication with guarded routes
- Created a separate package.json file for the server

**Link(s) to work & Resources**

- [Work Commit](https://github.com/ztyankov/svelte-random-meal-selector/commit/5b70070cf315e585439cfddcf781d84d325b6f64)

## Day 19: Friday, 01/22/2021 - Skipped. Make up on Saturday


## Day 18: Thursday, 01/21/2021

**Time Spent:** 45m

**Today's Progress**

- I learned about Actions and how to pass multiple parameters `use:myAction={{duration, name}}`
- Got familiar with Component compositions via slots
    - `<slot><p>Default Content here<p/></slot>`
    - named slots with `<span slot="address">content here</span>` and `<slot name="address">Unknown Address</slot>`
    - slots with props
- Started learning about the Context API for communication between a parent components and its descendants
- Special elements like `<svelte:self>`, `<svelte:window>`, `<svelte:head>`

**Link(s) to work & Resources**

- [Current Exercise from Svelte Tutorial](https://svelte.dev/tutorial/svelte-options)

## Day 18: Wednesday, 01/20/2021 - Skipped. Too much work.
## Day 18: Tuesday, 01/19/2021 - Skipped. I was beat.

## Day 17: Monday, 01/18/2021

**Time Spent:** 2h

**Today's Progress**

- Fixed the compatibility issue between Snowpack and svelte-spa-router, by removing `extends: "@snowpack/app-scripts-svelte"` from the snowpack.config.js
- I upgraded the snowpack.config file to match the config changes for 3.0
- Setup some basic routes for Home and Dashboard and moved some content from App to those new routes
- *Note:* I also had to rename the routes file for the new router to `routes.config.ts`. Otherwise snowpack kept looking for an index file inside of /routes/

**Thoughts:** It required some tinkering with other snowpack-svelte templates to figure out what the problem was with that svelte-spa-router pkg and the snowpack config. I'm happy that I was able to resolve the problem!

- [Work Commit](https://github.com/ztyankov/svelte-random-meal-selector/commit/31180f2b68d0388f6e50c78433f6a2cf8561eebe)

## Day 16: Sunday, 01/17/2021

**Time Spent:** 45m

**Today's Progress**

- I upgraded snowpack to version 3.0.* and tried to fix the run error with the svelte spa router, but it didn't work.

**Thoughts:** I really want to use Snowpack for development, but there is always some issue that comes up...
## Day 15: Saturday, 01/16/2021

**Time Spent:** 1h30m

**Today's Progress**

- Today I looked into the different Router options for Svelte and I decided to use the [Svelte-Spa-Router](https://github.com/ItalyPaleAle/svelte-spa-router)
- I encountered some incompatibility issues between the new router and snowpack. Posted a troubleshooting comment on Github.
- I found some good videos from the last [Svelte Summit](https://sveltesummit.com/)
- Watched a very good video by Rich Harris about Futuristic Web Development. Thumbs up!!

**Link(s) to work & Resources**

- [Alessandro Segala: So you want to pick a router?](https://www.youtube.com/watch?v=EL1qM0cv0eA)
- [Rich Harris: Futuristic Web Development](https://www.youtube.com/watch?v=qSfdtmcZ4d0)

## Day 14: Friday, 01/15/2021

**Time Spent:** 1h30m

**Today's Progress**

- I learned about Svelte stores (readable/writable) and how easy they are to use.
- I learned about Svelte animations and how to make a custom one.
- Created a custom spinning animation by using Svelte's animation API that manipulates the content until the animation has settled.

**Link(s) to work & Resources**

- [Work Commit](https://github.com/ztyankov/snowpack-svelte-ts-tailwind/commit/fe23d554fdaa725334248b16068d656554caf5ae)
- [Current Exercise from Svelte Tutorial](https://svelte.dev/tutorial/custom-css-transitions)
## Day 13: Thursday, 01/14/2021

**Time Spent:** 1h

**Today's Progress**

- I started going through the official Svelte tutorial in order to fill in some gaps in my knowledge.

**Link(s) to work & Resources**

- [Current Exercise from Svelte Tutorial](https://svelte.dev/tutorial/update)

## Day 12: Wednesday, 01/13/2021

**Time Spent:** 1h

**Today's Progress**

- I found some good resources with Svelte tutorials and videos
- I learned about Actions and how they can be re-used across components

## Day 11: Tuesday, 01/12/2021

**Time Spent:** 1h30m

**Today's Progress**

- I spent more time playing with TailwindCSS, reading the documentation and understanding what customizations are available
- Finished styling a card component that resembles Material UI
- Updated the TailwindCSS config file with custom colors and fonts

**Thoughts:** TailwindCSS provides a lot of options and functionality. With some practice, I should be able to get creative. The whole framework is very customizable. I was able to extend and add new colors options.

**Link(s) to work & Resources**

- [Work Commit](https://github.com/ztyankov/snowpack-svelte-ts-tailwind/commit/956fb34b3f5947aa3f13bd75e3f1311bafb1957b)
- [TailwindCSS Docs](https://tailwindcss.com/docs/functions-and-directives#apply)

## Day 10: Monday, 01/11/2021

**Time Spent:** 1h

**Today's Progress**

- I watched some videos about Svelte actions and how you can replace regular event listeners with actions for re-usability

**Thoughts:** Actions are pretty cool. I just need to find the right situation to use them.

**Link(s) to work & Resources**

- [Svelte Components Lab](https://sveltelab.app/)
- [Reusing Event Listeners with Svelte](https://www.youtube.com/watch?v=_IGEl4t1TSM)
- [Order of Svelte Actions](https://www.youtube.com/watch?v=3R3PMEesQnM&t=4s)

## Day 9: Sunday, 01/10/2021

**Time Spent:** 3h

**Today's Progress**

- I got the Snowpack + Svelte + TS + TailwindCSS template up and running after updating my Node.js version
- Started creating a clone of a Material UI card with TailwindCSS styles

**Thoughts:** Since I was able to get this Snowpack setup running, I decided to spend more time learning TailwindCSS. Initially things were a bit confusing, because you need to apply a lot of different classes to create some layouts. The approach seems interesting, so I'll try to replace my Material UI components with TailwindCSS ones.

**Link(s) to work & Resources**

- [Work Commit](https://github.com/ztyankov/snowpack-svelte-ts-tailwind/commit/49b5f5472d69ac758f9fdab172e6079bb844e57b)
- [TailwindCSS Grid Documentation](https://tailwindcss.com/docs/grid-template-columns)
- [TailwindCSS Playground](https://play.tailwindcss.com/)
## Day 8: Saturday, 01/09/2021

**Time Spent:** 4h

**Today's Progress**

- I tested out the cool new FE build tool called 'Snowpack'.
- I was able to get the basic setup running with Snowpack, Svelte and Typescript.
- I couldn't find a way to add PostCSS and the Svelte Material UI library to the mix. It looks like there are some outstanding issues with Snowpack that have to be resolved before I can fully migrate to it.

**Thoughts:** Running Svelte + TS with Snowpack was wicked fast. But I hit many roadblocks on the way to adding PostCSS and Svelte Material to the mix. I found multiple bug reports about some of the issues. I tried configurations from other templates as well like Svelte-Tailwind or Snowpack-PostCSS-Webpack.

**Link(s) to work & Resources**

- [@snowpack/plugin-postcss does not work with imports (postcss-import)](https://github.com/snowpackjs/snowpack/discussions/1693)
- [Getting svelte-material-ui working with snowpack and sass](https://stackoverflow.com/questions/61970250/getting-svelte-material-ui-working-with-snowpack-and-sass/64175081#64175081)
- [SMUI How to integrate with snowpack](https://github.com/hperrin/svelte-material-ui/issues/196)
- [Svelte Tailwind Snowpack](https://github.com/agneym/svelte-tailwind-snowpack)
## Day 7: Friday, 01/08/2021

**Time Spent:** 2h10m

**Today's Progress**

- Created a generic and encapsulated filter component that can take an arbitrary set of values and notify the parent component of a selection
- Added more filters to my meal planner app
- Added media to the meal cards and made them look more refined
- Figured out how to apply a class to custom components with the `:global()` modifier

**Thoughts:** It was nice to create re-usable, standalone component for the filters. I used some CSS variables to dynamically update the styles and content in the new component. I'm getting better at styling the Material UI components inside Svelte. Today I also learned about image placeholder services like Placeholder.com. And I played around with some grid layouts and configurations.

**Link(s) to work & Resources**

- [Svelte Meal Planner Commit](https://github.com/ztyankov/svelte-random-meal-selector/commit/8527e003873eed85abe2ee2b18970487878c5c75)
- [Dynamic CSS Variables](https://svelte.dev/repl/8123d474edb04f198c3b83363716a709?version=3.23.2)
- [Placeholder.com](https://placeholder.com)
## Day 6: Thursday, 01/07/2021

**Time Spent:** 1h15m

**Today's Progress**

- Explore Material UI component customization through built-in mdc variables and inline styles
- Change design and colors for the filter container

**Thoughts:** Material UI components are not easy to customize. Even though some of them accept CSS classes, those classes don't appear to take effect. I might need to look into other UI systems to use that are more customizable. I wonder if Tailwind CSS would be fun to use for this project. Found Smelte, a UI framework built on top of Svelte and Tailwind CSS using Material specs.

**Link(s) to work & Resources**

- [Svelte Meal Planner Commit](https://github.com/ztyankov/svelte-random-meal-selector/commit/6a32d53cbfc2b824836acae8253bc237a13ce0cd)
- [Chip Material UI Variables](https://github.com/material-components/material-components-web/blob/v3.1.1/packages/mdc-chips/_variables.scss)
- [Smelte](https://github.com/matyunya/smelte)
## Day 6: Wednesday, 01/06/2021 - Skipped :(

**Thoughts:** I just couldn't muster any energy at the end of a long work day to do more coding. I'll be back tomorrow.
## Day 5: Tuesday, 01/05/2021

**Time Spent:** 1h45m

**Today's Progress**

- I explored reactive statements/variables and implemented a solution to my dynamic filtering
- More import/export issues came up with different prop types, so I had to extract each one into its own file
- I also updated my sample data points to provide more diversity

**Thoughts:** It's getting harder to do an extra hour of coding after the work day. Reactivity statements can be quite powerful! I like them.

**Link(s) to work & Resources**

- [Svelte Meal Planner Commit](https://github.com/ztyankov/svelte-random-meal-selector/commit/742a69ffa9effc45ee6c89588b5f741508825bed)
- [Svelte Reactivity](https://reactgo.com/svelte-reactivity/)
- [MDN Svelte Variables & Props](https://developer.mozilla.org/en-US/docs/Learn/Tools_and_testing/Client-side_JavaScript_frameworks/Svelte_variables_props)

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