# Design Patterns Warehouse Demo

## About

Video course companion code.

## Section 6, Video 3

Changes since _Section 6_, _Video 2_.

* Split `demo-app` into two projects: `demo-cli` and `demo-web` .
* Create new `Main` class for both new projects.
* Refactor `App` to be the superclass of the `Cli` and `Web` classes.
* Externalize configuration using environment variables where applicable - refactor `AbstractDbDao` and other classes.
* Turned the `demo-web` and `demo-rest` projects into WAR projects.
* **Note**: moved the `templates/` folder to the `demo-web` project.
This should have been done earlier but it doesn't have any adverse effect during runtime.
The only downside is that the artifact built for `demo-cli` also contains these files. 
