# Angular Playground

## Quickstart

1. Create a new project

`ng new <project name>`

2. Would you like to add Angular routing?

3. Which stylesheet format would you like to use?

4. Enter directory

`cd <project name>`

5. Run Angular Server

`ng serve`

6. Run `localhost:4200` in browser

7. Empty out following file sections:

`src > app > app.component.html (entire content)`

Personally, do not recommend to delete the following due to testing error:
`src > app > app.component.ts > export class AppComponent {} (brackets)`

### Optional

8. Install Boostrap

`npm install --save bootstrap@3`

9. Modify `angular.json` file with the follow:

```
"styles": [
     "node_modules/bootstrap/dist/css/bootstrap.min.css",
     "src/styles.css"
]
``` 
