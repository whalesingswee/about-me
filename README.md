# Frontend Guidelines Questionnaire
This is an answer based on Brad Frost’s [Frontend Guidelines Questionnarie](https://github.com/bradfrost/frontend-guidelines-questionnaire)

## HTML
### HTML Principles
I write Semantic markups, by that I mean using the correct and meaningful tag on the document disregarding its css style. Also, I use tab for the indention, personally I’d prefer 4 spaces, but kinda lazy to fix that on Sublime text because using tabs on javascript and css would definitely more handy.

### HTML Tools
I use Jade for the HTML preprocessor and uses Mustache for the template engine, it is very convenient specially when it comes to render the datas back from server.

### HTML Style
 - double quotes on HTML
- strictly no uppercases
- use data the right way
- comment like this `<!-- .end-of-class -->` 

---------------

## CSS 

### CSS Principles
- I do not oppose to long string selectors, but structure must be clear. every element should be able to be plugged and play. Naming should be general, I clearly divided component should be functional naming while layout should be presentational naming. 

### CSS Methodology
- I use BEM methodology with some mix up of ITCSS.

### CSS Tools
- I am using SASS and recently moved POSTCSS with use of `precss`, clearly because I am not used to `cssnext` yet.
- I personally use CSS reset and normalise mix because our project requires a lot of heavy redesign, resetting everything would definitely help.
- In our Gulp, aside from using autoprefixer, we use several mixins and SVG sprites, SVG icon-fonts to make our css flow even better.

### CSS Frameworks
- I do use Bootstrap and Foundation, but that’s before, I find it dirty and unable to modify easily if our site is fully redesigned, I think framework are fast and easy for those regular site, but if the design is way different from the typical ones, I think you should move on and create your own with style guide.

### CSS Style
- I use Tabs, clearly I think readability is important, and I’m used to it. 

---------------

## JavaScript

### JavaScript Principles


### JavaScript tools
- I use Angular and recently learning React.
- Vue.js is my next.
- I am following John Papa’s guide for Angular.
- Modernizr is a must.
- I like to use Greensock and Velocity for animating.
- I like to use SnapSVG for the SVG animation.

### JavaScript Style 
- I always use tab
- Commeting always starts with `// this is comment` 
- Use `camelCase` for functions while all `lowercase_underscore` for variables.

---------------

## Tooling
- I used both Grunt and Gulp, but I use Gulp heavily these days.
- I use Bower for managing the plugins
- Nope, I don’t use Yeoman

---------------

## Version control
- I use Git as it was my version control system in my entire web life.
- I usually host my open source code project on Github while we are using Bitbucket server on work.
- So far no one is managing pull request issues since we do not require that yet, most of our project could be done by communicating in person, but I do aware we will be needing that in future.
- Issues are tracked base on Jira or Github.

-----------

## Support and Optimization
- I optimise the site mainly for webkit and mozilla only, though I am aware of IE users, but I expect to support to the latest IE browsers only. 
- I mainly focus on iPhone, barely on Android because I do not have the device.

-----------

## Documentation
- I encourage my team to create a style guide every time we created a component.
- I always create a readme.md for the user so that they would have a summary of the project and how it is going to be used/installed.

-----------