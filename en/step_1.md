You can plot a bar graph on the LEDs to show values from the sensors.

### Plot bar graph

In this example, accelerometer values are plotted as a bar graph.

You can find the `plot bar graph`{:class='microbitled'} block in the `Led`{:class='microbitled'} menu.

<img src="images/led-menu.png" alt="The Led menu with the 'plot bar graph' block highlighted." width="350"/>

Place the `plot bar graph`{:class='microbitled'} block inside an event block or a loop block. The `every`{:class='microbitloops'} block has been used in this example.

```microbit
loops.everyInterval(500, function () {
    led.plotBarGraph(
    0,
    0
    )
})
```

From the `Input`{:class='microbitinput'} menu, get the `acceleration`{:class='microbitinput'} block.

Place the `acceleration`{:class='microbitinput'} block inside the `0` on the left of the `plot bar graph`{:class='microbitled'} block.

```microbit
loops.everyInterval(500, function () {
    led.plotBarGraph(
    input.acceleration(Dimension.X),
    0
    )
})
```

You will need to add the maximum value to be plotted on the graph. Replace the `0` to the right of the `plot bar graph`{:class='microbitled'} block with your maximum value.

In this example, 1023 has been used, which is the maximum value of acceleration in mg that can be sensed by the accelerometer. The maximum value will be different for other sensors.

```microbit
loops.everyInterval(500, function () {
    led.plotBarGraph(
    input.acceleration(Dimension.X),
    1023
    )
})
```

The LEDs on the micro:bit will light up to show the value of the sensor being recorded up to the maximum value field.

![The LED display lighting up to show the values from the sensor being recorded.](images/led-display.gif)
