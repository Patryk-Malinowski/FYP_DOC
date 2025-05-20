## Issues Encountered

### Outdated Documentation.

#### Learning Exercise Videos outdated
[Learning Exercise Video link at time of writing](https://docs.duckietown.com/daffy/opmanual-duckiebot/lx/supported/general_running_lx.html)

Video at that link seems to have different file/dir structure than the exercises I got.


This is my file structure, clearly missing a `template_ros` directory.
![Learning Exercises File Structure](../images/exercises_file_structure.png)


#### Incorrect wiring configuration for Duckiebot display

Following the assembly instructions for Duckiebot DB21J the camera wiring is incorrect and my display would never display.
![Incorrect Display Wiring](../images/display_wiring_incorrect.png)
[Link to documentation at time of writing](https://docs.duckietown.com/daffy/opmanual-duckiebot/assembly/db21j/index.html#top-deck-assembly)

The correct wiring below:
![Correct Display Wiring](../images/correct_display_wiring.jpeg)

Black - Red - Yellow - Blue


#### Confusing camera wiring illustration (Bend needed)

![Confusing Camera Assembly 1](../images/camera_assembly_1.png)

The ribbon cable you get in the kit does not have the blue ends on one side as shown in the image.


![Confusing Camera Assembly 2](../images/camera_assembly_2.png)


In practice you **must** twist the ribbon cable to have the blue end in the correct orientation for both connections.

![Twisted Camera Cable](../images/twisted_camera_cable.jpeg)

### Duckiebot Connectivity Issues

The Duckiebot would become unresponsive to pings and commands randomly for a short period of time. But for example the camera image would still be updated continously in the dashboard.


### Confusing Learning Exercises

Never used jupyter notebooks and found it confusing on where to write code and how to execute it... More so a reason why it took much longer than expected to get through the first exercise.



### Missing Components Errors

Shows unhealthy components although the ToF sensor works and everything is conected as per instructions. There just seemingly is no solution to this at time of writing.


![missing Components in Dashboard](../images/components_not_detected.png)


### Display changed | to # after dts duckiebot update

The display used `|` to indicate cpu usage etc. but after the update it uses `#`. There seems to be no fix at time of writing. Other people mention it in stack overflow.


![Display Using |](../images/display_using_pipe.jpeg)
![Display Using #](../images/display_using_hash.jpeg)

### Flashing lights

Possibly related to the constant connectivity issues? Lights turn off briefly and switch back on when nothing else is going on with the duckiebot.

### Missed generated Token

The token gets generated at the bottom of the webpage. I fully expected a pop up with the generated token. Initially though the token was not being generated at all.


### Documentation contradiction/confusion

When running a dts command to add my token it tells me it should look something like "dt2-..." this tells me I need a dt2 token. But in the documentation it says the token should look like "dt1-...".

Also because of this, I ended up using a dt2 token but it turns out there are issues with using the dt2 token.

![Confusing Documentation Regarding Tokens](../images/documentation_says_dt1_token_command_says_dt2_token.png)


In general there are little things in Duckietown that have been missed. Like the hints when generating a token all say they refer to minutes.

![Incorrect Hints in Token Generation](../images/token_generation_has_incorrect_hints.png)

### Unable to create a duckietown account

I **HAD** to use my github account to create a Duckietown account.

If you don't already have a github account, it might be a good idea to set one up now.

### Connection Issues

![Connection Issues](../images/connection_issues1.png)

![Connection Issues 2](../images/ping_duckiebot_packet_loss.png)

![Connection Issues 3](../images/connection_randomly_dropping_1.png)


## General Things

**Small community**
Lack of youtube videos for tutorials covering assembly, learning exercises and more...


Limited support in stack overflow and slack. Support will come but might take a while...

