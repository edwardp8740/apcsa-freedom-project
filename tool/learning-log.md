# Tool Learning Log

## Tool: **Godot**

## Project: **Mystery Thriller Game**

---

### 10/19/26:

* I'm starting off by looking at the documentations of Godot.
    * I've read the introductions and I found it provides videos to help beginners out, I will these videos to start off my learning
* In the video we learned about all the importants parts of Godot to know
    * Scenes are reusable templates that represent anything in your game.
    * Nodes are the building blocks of scenes. They are the elements you see in the viewport.
    * Scripts are text files that give instructions to the computer. You can attach them to nodes to control their behavior.
    * Signals are events that nodes emit to report what's happening in the game. You can connect signals to scripts to run code when an event occurs.
* It showed me a website like free code camp (fcc) where we learn about GDScript which is important to creating games with Godot since GDScript tells the stuff in the game what to do
    * [link](https://gdquest.github.io/learn-gdscript/#drawing-a-rectangle)
    * Completed a few lessons from this about GDScript
        * Learned about some basics of GDScript, notes about the code are in a google doc
* I plan on following the documentation about Godot to learn more about how Godot works and then follow the the `Your first 2D game` section

### 11/3/26:
* I looked into a video where it shows how to create a 2D game and it said that I should know some GDScript before getting started
    * It referred back to the fcc like lessons
* I did more lessons, learned how to call and create functions, variables/sub-variables, etc.
    * To create a function you must use the key word `func` and use `:` instead of `{}` to show what's inside the function.
        * ```Java
            func name(parameter1, ...):
                instruction_1
                intruction_2
                ...
            ```

        * names can NOT have spaces, it has to start with a letter or an underscore. You can't begin with a number, but you can use numbers after the first character.
    * Variables are just about the same as they would be in js/java but don't need an ending statement, `;`
        * ```java
            var rotation = 0
            ```
            * **NOTE**: Variables can change to anything, so it can change from numbers to text, becareful for this.
        * Sub-variables are basically variables within variables, like specifying from living room to the table in the living room
            * ```Java
                func run():
                    position.x = 200
                    position.y = 250
                ```
            *  it has x and y sub-variables. They respectively control the horizontal and vertical size of the game entity.
                * To access those X and Y sub-components, you add a dot (".") after the variable name.



<!-- 
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->
