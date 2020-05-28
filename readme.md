# Summery
-- 
> This is a personal practic projects based on a roguelike game tutorial by libtcod.   
> The tutorial url is <http://rogueliketutorials.com/>
### part-1
```
init and load source
game_loop:
    render
    action = input_handlers(key)
```
### part-2
```
abstract Entity
    x, y, char, color
    move()
    
abstract render_functions
    render_all()
    clear_all()
    
abstract Tile
    block, block_sight
    
abstract GameMap
    width, height, tiles
    initialize_tiles()
    is_blocked()

handle the relationship between move and block tile
```