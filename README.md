# Using the robot

**Driverstation is the short and long window with enable and disable**
**Dashboard takes up more of the screen**

## Before you start
1. Turn the robot on.
2. Make sure the drivers for the wireless card are installed. (if there are any)
3. Check the robot for a battery.
4. Try skipping the deployment process first, the robot still has the code on it.
5. If there is no robot code, go to the deployment process.
6. If there is an issue, go to the debugging process.

## Deployment
Start command prompt with admin privileges:
```
win + r
"cmd"
return
```

Run in command prompt:

```
python "/path/to/robot.py" deploy --skip-tests
```

## Driverstation

1. Open Driverstation:
```
win
"driverstation"
return
```
2. OPTIONAL: Find "CAMERA BUILD" folder on Desktop and run the Dashboard EXE in it.
3. Connect to the robot's hotspot.
4. Enable teleop.
5. The robot will take about 5 seconds to respond after starting teleop, so give it some time.

## Debugging 

- Make sure the team number is 6517 in the Driverstation
- If the controls do not work, switch through the tabs on the Driverstation until you find a list of joysticks.
  Swap the joysticks in the list, enable teleop again, and try to use the controls.
- Make sure the robot is connected to the driverstation.
- It takes a while for the hotspot to show up, if that is the issue, wait a minute or two.
- If the hotspot still will not appear, change robot radios. (Message me on slack if this happens.)
- If the robot keeps turning on, not moving, and then the robot code crashes, redeploy and message me on slack.

## Notes

- Python master-race.
