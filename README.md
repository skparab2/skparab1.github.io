# Skparab1's Github Website
**This website can now be viewed at [skparab1.github.io](https://skparab1.github.io)**

## Pages
- [Homepage](https://skparab1.github.io)
- Subpages
  - Redirect
    - my url shortener
  - r
    - a shorter link for my url shortener
  - [search](https://skparab1.github.io/search)
    - a search page for my software and website content
    - pretty good now actually, uses optimized rendering (like [oskeyboard](https://skparab1.github.io/r/key))'
    - however, is in p5js
  - [traffic simulator](https://skparab1.github.io/traffic_simulator)
    - a web host for my traffic simulator
  - [login](https://skparab1.github.io/login)
    - a webpage for logging in to skparab1 services
    - can be used across skparab1 web applications
  - [homepage](https://skparab1.github.io/homepage)
    - my new homepage
    - in HTML (with HTML canvas)
    - will be renames to /home subpage when i finish it
  - go
    - working on a url shortener in html
    - likely will be much faster than my old one (which used p5js)  
  - main
    - a test page which will become my new main page(homepage)
    - image carousel
      - images work
      - centering works
      - dots display
      - dots work when clicked
      - arrows display
      - arrows work when clicked, but speed up carousel
      - auto timed change works
      - slide/totalsides counter works
      - total of 6 slides for now
      - most images are the same dimensions 9e
    
 
-------------------------------------------- dont go below this line stuff is not organized --------------------------------------------

## Url packing string query framework for search
- search results are displayed, and are narrowed down by filters
- the data of the filters is packed into the url as a query
- and the page is refreshed with the conditions packed into the url
- for example, if the user filters no python, then the string '&py=false' will be packed into the url
- when the page loads, it will unpack the url and filter the results accordingly
- multiple parameters can also be packed for example '&js=false&md=false&pas=false'
  - the & is used to seperate packed parameters (which are the filters)
- try it [here](https://skparab1.github.io/search)

