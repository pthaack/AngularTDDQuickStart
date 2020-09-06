# AngularTDDQuickStart
How to create an Angular app using the command line interface

## Angular TDD Quickstart from scratch
- [x] install Angular
- [x] install Visual Studio Code
1. open command (cmd)
4. create new app (ng new appNew)
3. change directory to new app (cd appNew)
5. add home component (ng g c home)
6. add database (ng g s data)
9. add theme (ng g s theme)
7. add pwa service (ng add @angular/pwa)
8. start demo web service (ng serve -o)
9. start test service (ng test)
10. remove everything so that only the router-outlet directive remains (app.component.html)
10. add test code to home component (home.component.spec.ts)
11. follow TDD steps
    1. write a test
    2. make it pass
    3. refactor
