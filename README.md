# OMDb Client Code

The client code for OMDb, a media search aggregator.

## Use

To run the server code for this project, you will need to have **node** and **npm** installed on your machine. Furthermore, you will need a `.env` document in the `/client` folder with a `REACT_APP_API_KEY` variable containing the OMDb API key. Finally, one can `cd` into the `/client` repo and run:

- `npm i`: Installs the necessary dependencies and packages
- `npm run start`: Runs the client on a development environment

## Stack

- **React**: Web-language for dynamically displaying data
- **Material UI**: Ready to use React components
- **Framer Motion**: Component animation library

## Organization

- **index.js**: The main file that is run which renders the front-end
- **/components**: The front-end components that were created
- **/contexts**: The React contexts that are used to maintain data
- **/css**: Web-styling in SASS
- **/js**: Functions that run API calls to the back-end
- **/routes**: Top-level routes to each page
