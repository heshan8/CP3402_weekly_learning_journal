# CP3402 Weekly Journal

## Week 10

### Learning activities and Resources
- Watched LinkedIn learning videos about Sass - [Link](https://www.linkedin.com/learning/sass-essential-training/welcome?u=2223545)
- Looked at a Sass basics guide - [Link](https://sass-lang.com/guide/)
- Used ChatGPT to generate some simple Sass exercises
- Looked at gulp documentation - [Link](https://gulpjs.com/docs/en/getting-started/quick-start)

### Estimated hours

Around 4 hours

### Content insights
#### Sass

- Sass, short for "Syntactically Awesome Style Sheets," is a CSS preprocessor. CSS on its own is adequate but when stylesheets get larger and more complex it can  be hard maintain.
- Sass has features that don’t exist in CSS yet such as nesting, mixins, inheritance, variables and functions that make it easier to maintain your code.  For example, instead of copying and pasting the same button styles everywhere, you can define a reusable mixin or extend a base style.

#### Gulp
- Sass cannot run natively in a browser and it must be compiled into standard CSS. This is where Gulp comes in handy. Gulp is a JavaScript-based task runner that helps you compile and execute tasks like:
    - compiling SASS/SCSS files
    - minifying and concatenating CSS and JS files
    - Adding vendor prefixes
    - Watching files for changes and auto-refreshing
    - Optimizing images
    - Bundling files for production
- By using Gulp, you can automate the process of compiling Sass files into CSS every time you make changes.
- Gulp can also apply vendor prefixes automatically (adding different browse compatability), minify the final CSS to reduce file size, and reload your browser during development using BrowserSync.
- Sass improves the writing and the structure of your stylesheets, while Gulp ensures that your Sass code is compiled, optimized, and ready for deployment without manual intervention



### Career/Employability/Learning Insights
Learning Sass and Gulp has helped me understand how web developers write cleaner and more efficient CSS and automate their workflows. Using BrowserSync made working with CSS and Sass way easier because whenever I made a change I could see the change directly in the browser. I tried to integrate Sass and Gulp for the theme development in the group project, but I had trouble getting it configured properly and ended up abandoning the idea. After this week im feeling more confident in handling front-end workflows. Understanding these tools gives me a better foundation for using more complex tools such as WebPack. Webpack takes multiple files (modules) that make up your application and combines them into a smaller number of optimized files (bundles). 