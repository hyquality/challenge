### Framework Used: Astro ###
https://astro.build/

https://docs.astro.build/en/getting-started/

### A Little About the Project ###
This project is to display all nearby food trucks on an interactive Google map. Currently I have utilized the static dummy data included in the challenge doc. This can be further improved by using an API endpoint that can then send dynamic data to the map.

1. Show all food trucks in a google map:
    - Display all food trucks in google map with pin markers
    - Each pin is clickable, and you can see truck name and what kind of food they sell

2. Show all food trucks in list format at the bottom of the Google map:
    - When you zoom the Google map in/out, or when you manually move the map area, only visible trucks are displayed in the list dynamically.


### Commands ###
1. Install dependencies
`npm install`

2. Start local dev server at `localhost:4321`
`npm run dev`

3. Build your production site to `./dist/`  
`npm run build`

4. Preview your build locally, before deploying
`npm run preview`

### Other Notes ###
- Dependencies included: Astro check, Tailwind, Typescript
- Need to add a proper Google map key
