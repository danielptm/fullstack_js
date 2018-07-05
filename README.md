# fullstack_js
A CLI tool that can be used to consistently and quickly build react and node components. The idea is that you create a clone of a node and react seed project into 2 different folders. In the terminal you can be 1 level above both folders and be able to create node and react components or you can be in the root of the node or react project and create components just for that project. Much like the angular CLI you can then just type "fullstack generate <ComponentName>" to create the component that you want.
  
### General features
When running a command check to make sure in the level above the react project and node project, or in the react or node project. Otherwise an error message shows.
There is a symlink so this is able to be run from anywhere in the file structure.
Create CLI .fullstack_settings file that is config for the CLI for that project. There are node settings, and react settings, and project settings.

### Down the road features
Have it work for Angular and vue also.

### flags
-h, help list help for the CLI
-t create a test for whatever component is being generates, based on the component name, the test file is created with the appopriate structure

### Primary commands
Start dev react server
Start node server
Start both at the same time
Generate production build of react project and choose to leave in default place of react project or build/move it to the node project.

Alter project to go against a mongo db running in a docker
Alter project to go against a mysql running in a docker.
(These commands will download the docker image for the development machine and start them up if not already downloaded, and adjust the whole backend accordingly)

### Create commands for files
Create a clone of the node_seed project
Create a clone of the react_seed project
Create React stateful component
Create React stateless component
Create React scss file
Create React css file
Create React http module
Create React test file for a component
Create api module
Create service module
Create db module
Create utils module
Create test file for any one of those modules.
