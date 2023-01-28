### **Movidea**

Movidea is a webApp using react hooks which will be able to search for movies via the OMDB API and render the results to the user. The reason for building the app is just so that I can get a better understanding of using hooks in an application. While working on this project, I got to use hooks like :
- useState() 
- useEffect()
- useReducer() 

I am declaring the base components framed at intiallly followed workflow in order to implemennt this. Later on I also plan to work a little more styling and a few more features into this project.

1. App.js 
   - Parent component for others.
   - Contain a function that handles API request and calls API during initial render.
   - Here only use of OMDB API is implemented to get movie data and manage movie search.
      -> Generated key request for individual project.
      -> Formatted API key with search and response calls.
      
2. header.js
   - Render App header and accept title prop from movies.
   
3. movie.js
   - Reads data for each movie and lists them in organised manner.
   - Movie object is passed as a prop.
   
4. search.js
   - Contain a form with input elements and search buttons.
   - Uses hooksAPI "useState" which allows to add react state to a function component.
