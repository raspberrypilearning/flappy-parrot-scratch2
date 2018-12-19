## Add a score

The player should score a point every time Flappy makes it through a gap between pipes.

--- task ---

Make a new variable **for all sprites** and call it `score`{:class="blockdata"}.

[[[generic-scratch-add-variable]]]

--- /task ---

Each 'Pipes' sprite clone should `wait until`{:class="blockcontrol"} Flappy has flown past and then increase the `score`{:class="blockdata"}.

--- task ---

First, `set score to 0`{:class="blockdata"} when the game begins:

![pipes sprite](images/pipes-sprite.png)

![blocks_1545217754_4094372](images/blocks_1545217754_4094372.png)

--- /task ---

--- task ---

Then add the following code to the `Pipes` sprite:

![pipes sprite](images/pipes-sprite.png)

![blocks_1545217755_526561](images/blocks_1545217755_526561.png)

--- /task ---

--- task ---

Add more code so that, when Flappy's `x` position is greater than the pipe clone's `x` position, the `score`{:class="blockdata"} increases by `1` and a sound of your choice plays.

You could use the 'pop' sound if you want, or add a sound from the library, for example 'bird'.

--- hints ---

--- hint ---

You need to `wait until`{:class="blockcontrol"} `Flappy's x position`{:class="blocksensing"} is `greater than (>)`{:class="blockoperators"} the `x position`{:class="blockmotion"} of `Pipes`.  

![pipes sprite](images/pipes-sprite.png)

![blocks_1545217756_632011](images/blocks_1545217756_632011.png)

Then `change score by 1`{:class="blockdata"} and `play a sound`{:class="blocksound"}. 

--- /hint ---

--- hint ---

Use these blocks in the correct order:

![pipes sprite](images/pipes-sprite.png)

![blocks_1545217757_7045462](images/blocks_1545217757_7045462.png)

--- /hint ---

--- hint ---

Your code should look like this:

![pipes sprite](images/pipes-sprite.png)

![blocks_1545217758_8350632](images/blocks_1545217758_8350632.png)

--- /hint ---

--- /hints ---

--- /task ---

--- task ---

Test your code and make sure you score a point every time Flappy gets through a gap between pipes. Check whether the `score`{:class="blockdata"} is set to `0` when you start a new game.

--- /task ---
