# canvas-grid-master

Canvas-grid-master is an endless grid in canvas to browse a bunch of images stored in a folder.
Work in progress.

I am exploring two options :
* One that starts from that GitHub project : https://github.com/spoeken/infinite-canvas-grid
* And another from scratch (more succesfull for the moment)


## To Do :

### Features
* Improve image support
* Add fade in when image appears
* Optimize draw function
* Redo and complete the triggers (add mouse wheel support)
* Regenerate a bunch of tiles when the viewport is close to the limit of the array
* Different mode to spread the tile without repetition


### Nice to have
* Add easing when the viewport moves


### Fix
* Render bug on the first column when scale < 1


## Documentation

### Initializing
```javascript
<script type="text/javascript">
  var wall = new Wall('canvas','viewport',array});
</script>
```


### Options
