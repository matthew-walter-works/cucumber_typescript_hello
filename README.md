# cucumber_typescript_hello
This is a POC to let developers explore BDD testing.
https://github.com/cucumber/cucumber-js/blob/master/docs/nodejs_example.md

## to run use:
- Note: need to use local install otherwise error occurs
### Windows
- Via CMD
    - `.\\node_modules\.bin\cucumber-js -f .\\node_modules\cucumber-pretty`

- Via NPM
    - `npm test`
    - Note: defaults using the pretty formatter
## Troubleshooting
### Windows
1) Does not seem to work with Intelij, needs to be run via commandline
2) Needs to use Windows style relative paths for example not `./myDir` but `.\\myDir`