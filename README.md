# Blocks and Inputs

![](https://github.com/hoc-labs/images/blob/main/branchesCycle.gif?raw=true)


On this page, you will create many different pictures (like the ones above) by creating a single block with an input parameter: Input parameters allow one block to do many related jobs.


### Command Block with Single Input
Follow the directions in this [video](https://drive.google.com/file/d/0ByQqv1wHXg3rM0RsNVdmN21Nek0/view?usp=sharing) to create a command block to draw a pinwheel shape with an input parameter to specify the number of branches. 

Create the block in the **Motion** palette.

These were made with the pinwheel block.

![](https://github.com/hoc-labs/images/blob/main/Wreath1.png?raw=true)

![](https://github.com/hoc-labs/images/blob/main/Wreath3.png?raw=true)

### Adding Multiple Inputs

Now you will modify your existing pinwheel block so that you can use it to draw a variety of shapes. Recall how you first generalized your original pinwheel script: you added an input variable called branches that controlled the turning angle of the sprite. By adding more input variables, you can generalize other aspects of your program...

![](https://github.com/hoc-labs/images/blob/main/assorted-pinwheels.png?raw=true)

Experiment with the input for the second move block inside your pinwheel block as shown below. First predict. What do you think will happen? Then try several inputs between -100 and 0.

![](https://github.com/hoc-labs/images/blob/main/pinwheel-change-second-move-input.png?raw=true)


What happened? How does it compare to what you predicted? How does this input value impact the sprite's behavior? How does it impact the resulting image on the stage?

![](https://github.com/hoc-labs/images/blob/main/asteriskpolygonCycleBW.gif?raw=true)

* Add a second input variable to control the amount of "backing up" that the sprite does before each turn through the full 360°.
* Drag off the new backup variable, place it where it belongs in the pinwheel code, and press "OK" or "Apply."
* Check that the new input slot in the pinwheel block behaves like the changes in your experimentation above.
* Use an Operator block and change the pinwheel script so that it will accept a positive value (between 0 and 100) for backup.
* Add a third input called size to control the input to the first move block.

![](https://github.com/hoc-labs/images/blob/main/U1L3-PinwheelwithInputs.png?raw=true)

Try out a variety of inputs to your pinwheel program...

![](https://github.com/hoc-labs/images/blob/main/U1L3-PinwheelwithInputs1.png?raw=true)

![](https://github.com/hoc-labs/images/blob/main/pinwheel-80-6-20-result.png?raw=true)

![](https://github.com/hoc-labs/images/blob/main/U1L3-PinwheelwithInputs2.png?raw=true)
![](https://github.com/hoc-labs/images/blob/main/pinwheel-80-5-60-result.png?raw=true)

Discuss what input values will give you a polygon or an asterisk.

![](https://github.com/hoc-labs/images/blob/main/polygon-result.png?raw=true)

![](https://github.com/hoc-labs/images/blob/main/asterisk-result.png?raw=true)

You may want to reduce the input value for the wait blocks inside the pinwheel script so you don't have to wait so long between trials.
