Simple NodeJS Server
====================

A NodeJS server very simple to serve statics. Customized port, path and HTML5 Push State.

## How to start
The default arguments are set for a fast start but you can customize them to make the script powerfull. You don't need clone the project within each project.
1. Clone the project in your workspace's root path.
2. Go to your project, p.e '[workspace-root]/myProject/'
3. Start the Node server: node ../simple-node-server/server
4. Enjoy your new server at http://localhost:8888

### Arguments
1. Port: by default is the port 8888, you can customize the port to set up several server.
2. Path: is the path of your project, by dafault is '.', you can specify any directory of your computer.
3. disablePushState: by default it's enabled, then you won't get a 404 when a file doesn't exist. It will return the index.html of your root.
