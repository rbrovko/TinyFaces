# TinyFaces 👦🏼👨🏾👩🏻

<img src="/Public/images/github-header.png?raw=true" width="888">

Avatars & Random data for your designs

Also check out [TinyFaces Sketch Plugin](https://github.com/maximedegreve/TinyFaces-Sketch-Plugin)

## 🤖 Before building (dependencies)

* Install [Vapor Toolbox](https://github.com/vapor/toolbox)
* Create a MySQL database called ```marvel_faces```, e.g. using the mysql CLI: ```CREATE DATABASE marvel_faces;```


### macOS:
* Run ```brew install gd```
* Run ```brew install mysql``` followed by ```mysql_secure_installation``` to setup a database
* Install [Xcode](https://developer.apple.com/xcode/)
* Run ```vapor xcode```, this will create the Xcode project
* Run the ```App``` target in Xcode
* TinyFaces should now be running on [http://localhost:8080](http://localhost:8080)

### Ubuntu (server):
* Run ```sudo apt-get install libgd-dev```
* Run ```apt-get install libmysqlclient-dev```




## 📖 Documentation

Visit the Vapor web framework's [documentation](http://docs.vapor.codes) for instructions on how to use this package.

## 💧 Community

Join the welcoming community of fellow Vapor developers in [Slack](http://vapor.team).

## 🔧 Compatibility

This package has been tested on macOS and Ubuntu.
