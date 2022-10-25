# POS-Game (Part Of Speech)

## POS-Game which :-

- 10 Words are presented to the player one by one and he chooses wether this word is a noun,adverb,adjective or verb
- Consists of a Client folder and Server folder

## Installation :-

1. Clone the Github repository **(you have to add "--recurse-submodules" flag)**

   ```git
   git clone https://github.com/Kokosalah45/POS-AIO-client-server --recurse-submodules
   ```

2. In case you forgot to add the flag you can write this command **after cloning**

   ```git
   git submodule update --init
   ```

3. For Server and Client setup dependicies and run the apps By :-
   - using yarn :
     - install deps : `yarn install`
     - run app : `yarn run dev`
   - using npm :
     - install deps : `npm install`
     - run app: `npm run dev`

## Technologies Used :-

### Client-Side

1. Styling :
   - tailwindCss
   - postCss
2. State Management :
   - Prop drilling as state management solutions as context api , zustand or redux were not needed
3. Server-side request handling :
   - fetch
4. Miscellaneous
   - SwiperJs
   - Framer Motion
5. Tooling
   - TypeScript
   - Prettier

### Server-side

- ExpressJs
- TypeScript
- ts-node

### Hosting

- Client-App : [Netlify](https://635784cad40e11000825d38f--monumental-yeot-e027c5.netlify.app/)

- Server-App : [Railway](https://pos-trivia-production.up.railway.app/)

---
