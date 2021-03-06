*v0.0.1: Abasic ducktaped functionality
*v0.0.2: Added test to insert data
*v0.1.0: Now can GET json data /:user/weights with the user weights
  *v0.1.1: Ordered the weight data by date, most recent first
*v0.2.0: Now can PUT a new weight under /:user/weights/:year/:month/:day/:weight
  *v0.2.1: added README
  *v0.2.2: fix month on PUT
  *v0.2.3: fix README list
  *v0.2.4: fix GET weights returning an error
*v0.3.0: added a React stub to render at the bare URL
  *v0.3.1: improve bare URL stub
  *v0.3.2: add (stubbed) button to load weight data
  *v0.3.3: load ajax data with the button
*v0.4.0: Setup workflow with gulp: 'gulp build' now launches browserify plus babelify to build our JS bundle. For some reason babelify was throwing an error on ES6 imports with an npm task. Also added a React component that renders a stub text when requesting data with the button, and added a bit of info in the Readme.
  *v0.4.1: Async load weights on button press and output the first of them with the react component
  *v0.4.2: Render a table with all the weights using the react component
  *v0.4.3: Refactored code that renders rows
  *v0.4.4: Add TODOs to Readme
  *v0.4.5: Refactor main.jsx
  *v0.4.6: Change title after loading weights
  *v0.4.7: Add glyph to button. Remove redundant div.
*v0.5.0: Added D3.js to plot graphs with the user weights (user story 7).
  *v0.5.1: Move weights to the first column.
  *v0.5.2: Mark highest and lowest weight (user story 6).
  *v0.5.3: Plot mean weight.
*v0.6.0: Add button to delete weight entries.
*v0.7.0: Add form to add new entries.
  *v0.7.1: Remove some console logs.
  *v0.7.2: Remove reference to localhost.
  *v0.7.3: Prettier form using Bootstrap classes.
  *v0.7.4: Add Array.includes pollyfill.
  *v0.7.5: Add fetch and Promise pollyfills.
  *v0.7.6: Transform date and kg inputs to React modules.
*v0.8.0: Multi-user
  *v0.8.1: Update references after username change.
