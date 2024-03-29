# create-groovestack
create-groovestack is a utility that allows you to quickly bootstrap a new [Groovestack](https://talysto.com/tech/groovestack/) application. It is powered by [Groovestack CORE](https://github.com/talysto/groovestack-core) modules
* Base
* Config
* Auth 
* Jobs 

Please reference the Groovestack CORE [Documentation](https://github.com/talysto/groovestack-core) for module descriptions and configuration options.

### Getting Started

To get started, simply run the Groovestack Utility with the command

`yarn create groovestack $AppName` or

`pnpm create groovestack $AppName` or

`npm create groovestack@latest $AppName` or

`npx create-groovestack@latest $AppName`

<!-- ## Install Groovestack into an Existing App

`cd` into the existing application and run

`yarn upgrade groovestack`

`pnpm upgrade groovestack`

`npx upgrade-groovestack@latest` -->

After the utility has completed, cd into the new Groovestack app's root directory

`cd $AppName`

and launch the Vite / Rails app

`bin/dev`

