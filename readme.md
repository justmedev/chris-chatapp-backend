# chris-chatapp-backend

> Backend for [chris-chatapp-frontend](http://github.com/justmedev/chris-chatapp-frontend)

## About

This project uses [Feathers](http://feathersjs.com). An open source framework for building APIs and real-time applications.

## Getting Started

1. Make sure you have [NodeJS](https://nodejs.org/) and [yarn](https://www.yarnpkg.com/) installed.
2. Install your dependencies

    ```shell
    cd path/to/chris-chatapp-backend
    yarn
    ```
   
3. Navigate to the config folder and create a file called `local.json` -> Copy contents of `example.local.json` and change uppercase strings.
   ```shell
   cd path/to/chris-chatapp-backend
   cp config/example.local.json config/local.json
   gedit local.json # or 'notepad local.json' if on windows
   ``` 

4. Start your app

    ```shell
    yarn run compile # Compile TypeScript source
    yarn run migrate # Run migrations to set up the database
    yarn start
    ```

## Development
When developing, use `yarn run dev` to start a dev-server with hot-reload.

## Testing

Run `yarn test` and all your tests in the `test/` directory will be run.

## Scaffolding

This app comes with a powerful command line interface for Feathers. Here are a few things it can do:

```
$ npx feathers help                           # Show all commands
$ npx feathers generate service               # Generate a new Service
```

## Help

For more information on all the things you can do with Feathers visit [docs.feathersjs.com](http://docs.feathersjs.com).
