You can plot a bar graph to record data in the real world using the micro:bit. 

On the V2, you can use inputs and sensors or on the V1, the input can measure data.

### Plot bar graph for V2 users

In this example, the accelerometer has been used as the sensor for plotting your bar graph.

From inside the `Led`{:class='microbitled'} menu, you can find the `plot bar graph`{:class='microbitled'} block.

<img src="images/led-menu.png" alt="The led menu with the 'plot bar graph' block highlighted." width="350"/>

Place the `plot bar graph`{:class='microbitled'} block inside an event block or a loop block. The `every`{:class='microbitloops'} block has been used in this example.

<div style="position:relative;height:calc(100px + 5em);width:100%;overflow:hidden;"><iframe style="position:relative;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/---codeembed#pub:_00HP3DDHwCK8" allowfullscreen="allowfullscreen" frameborder="0" sandbox="allow-scripts allow-same-origin"></iframe></div>

From the `Input`{:class='microbitinput'} menu, you can find a sensor or input to measure with your graph. 

The `acceleration`{:class='microbitinput'} block has been used in this example.

Place the `acceleration`{:class='microbitinput'} block or any other sensor/input block inside the `0` to the left on the `plot bar graph`{:class='microbitled'} block.

<div style="position:relative;height:calc(100px + 5em);width:100%;overflow:hidden;"><iframe style="position:relative;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/---codeembed#pub:_agmFUzP71f2Y" allowfullscreen="allowfullscreen" frameborder="0" sandbox="allow-scripts allow-same-origin"></iframe></div>

Inside the 0 to the right of the `plot bar graph`{:class='microbitled'} block, you will need to write the maximum value to be recorded to the graph.

In this example, 1023 mg has been used. This value will be different for other sensors.

<div style="position:relative;height:calc(100px + 5em);width:100%;overflow:hidden;"><iframe style="position:relative;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/---codeembed#pub:_EgAL7zTWfDjT" allowfullscreen="allowfullscreen" frameborder="0" sandbox="allow-scripts allow-same-origin"></iframe></div>

The leds on the micro:bit will light up to show the value of the sensor being recorded against the maximum value field.

![The led display lighting up to show the values from the sensore being recorded'.](images/led-diasplay.gif)

To view the graph being plotted, click on the Advanced tab on your menu toolbox.

This will expand to showmore menu options.

Click on the Serial menu to find the `serial write line` block.

Place it below the `plot bar graph`{:class='microbitled'} block.

<div style="position:relative;height:calc(100px + 5em);width:100%;overflow:hidden;"><iframe style="position:relative;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/---codeembed#pub:_EMsKa86jp5y3" allowfullscreen="allowfullscreen" frameborder="0" sandbox="allow-scripts allow-same-origin"></iframe></div>

From the `Input`{:class='microbitinput'} menu, find the acceleration`{:class='microbitinput'} block.

Place it inside the empty field on the `serial write line` block.

<div style="position:relative;height:calc(100px + 5em);width:100%;overflow:hidden;"><iframe style="position:relative;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/---codeembed#pub:_cpbb16TXdWij" allowfullscreen="allowfullscreen" frameborder="0" sandbox="allow-scripts allow-same-origin"></iframe></div>

You can connect your micro:bit to your computer to view your graph.

You can also view the graph by clicking `show data` on the simulator.

### Plot bar graph for V1 users
