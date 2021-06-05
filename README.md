# Lua MTA Scripts

Lua MTA Scripts are few essentials scripts for your MTA project server. Most of them are written by myself, some of them with a bit of community help.

## Implementation

To import new scripts to your mta server put them in:
```html
mods\deathmatch\resources\(Put script in folder, or create new one)
```

## Auto-Launch scripts
If you would like to run scripts automatically (after launching server) go to:

```html
mtaserver.conf -> Open with text editor
Scroll way down to the bottom
You will see comment in config
" <!-- Specifies resources that are loaded when the server starts and/or which are protected from being stopped."
and then, if you wish to add "cars" (folder name) add line like this:
"<resource src="cars" startup="1" />"
```

## Features in each script folder
Admins:
```html
-Teleport to xyz postion
-Teleport to location
-Create jetpack
-Clear chat
```
Cars:
```html
-Insert and save vehicles in database
-Custom commands to resp cars
-Teleport into a car
-Create custom handling of a car
```
db:
simple database connection.

players:
```html
-Spawn players on specified XYZ position
-Fade camera in to the player animation
```
swap:
```html
Simple template to swap car graphics.
Here you may find a toyota supra instead of Cheetah
```


## License
[MIT](https://choosealicense.com/licenses/mit/)
