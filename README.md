# COMP6234

A repository designed to help students at Unviersity of Southampton setup their Node D3 environment on their COMP6234 module.

## Features
- Lightweight ready to use environment
- Has live/hot reload (reloads everytime you change files in 'd3_files' folder)

## Set Up

1. Install node:
   - [Node webpage](https://nodejs.org/en/)
2. Open terminal
3. Go into node_server folder
   - `cd node_server`
4. Install packages
   - `npm install`
5. Run the server
   - `npm run dev`

## Making changes

- To edit the javascript (js) files you can change/add files in the d3_files folder
- If a new files is added in d3_files folder, you must change the sources in the `<script>` block accordingly.
- e.g: add a new file with the name 'd3_treemap.js'
  - `...<body>
      <script src="./d3_files/d3_treemap.js"></script>
      <!-- This is where your code will go! -->
    </body>...s`
