# Example of using Typescript with external directory

* Using paths and baseUrl in tsconfig.json to import modules under an alias
* When importing these files into app, compilation breaks
* Importing scripts locally works
* Based on clean install with Svelte version 3.26.0, executing `npx degit sveltejs/template my-svelte-project` and executing `node scripts/setupTypeScript.js`