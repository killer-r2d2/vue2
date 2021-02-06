# real world vue2
## a training to learn vue
### https://www.vuemastery.com/courses

Roger Killer
Date: 06.02.2021
Notice:

##### Vue Router Basics:
Server-Side vs. Client-Side Routing
When it comes to websites, typically we connect our page together with links, right?
A link gets clicked, it calls back to the server for the next page,
and that page gets loaded.
When it comes to Vue, many choose chlient-side routing, meaning that the
routing happens in the browser itself using JavaScript. Our webpage is loaded
from a single index.html page and we can use client-side-routing to 
dynamically present different views, depending on which link is clicked.
Often the view we need to show has already been loaded into the browser,
so we don't need to reach out to the server for it.

###### A Single-Page-Application (SPA)
is definded as a web app that loads
from a single page and dynamiclly updates that page as the user interacts
with the app. However, if we're using a single page application we need
a way to navigate between content (client-side-routing).

###### How can we implement client-side routing in a single page Vue application?
Vue has its own official routing solution, called Vue Router. We set up
our project with Vue Router already installed using the Vue CLI.







## Project setup
```
yarn install
```

### Compiles and hot-reloads for development
```
yarn serve
```

### Compiles and minifies for production
```
yarn build
```

### Lints and fixes files
```
yarn lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
