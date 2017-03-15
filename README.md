# Demo

This is intended to be a demo and hands-on for the Software Engineering II course

## Install

Clone normally, then go to the folder where this project has been cloned and run the following commands:
Update node and tell the system to use the latest version (replace a.b.c to the installed version, e.g: 7.7.3)
```
nvm install node
nvm use x.y.z
nvm alias default vx.y.z
```
Install npm on the recently installed node
`npm install -g npm`
Make sure that you are on the folder where package.json is located and install the dependencies.
```
npm install -g
npm install
```
Run the application to make sure it works
`ng serve --host 0.0.0.0 --port 8080 `