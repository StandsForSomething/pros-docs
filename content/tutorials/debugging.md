---
title: Debugging in PROS
---

The [PROS API](/api/) provides various functions, like [`print()`](/api/#print) or [`printf()`](/api/#printf), that allow your robot to output information to a connected serial console during operation.


To view a robot's output, there are two officially supported methods:

1. Through the PROS CLI: <br/>

    Running `pros terminal` on the command line will open an output stream from a robot connected over direct USB connection, VEXnet, or [JINX](/tutorials/jinx/).

2. From within Atom: <br/>

    Click the button labeled "Open cortex serial output"
    {{< figure src="/images/atom/open-cortex.png" >}}<br/>

    A terminal panel will open at the bottom of the screen containing the output of a connected robot.<br/>
    {{< figure src="/images/atom/terminal-platformio.png" >}}
