# SLICE/FFC GUI_PC_Simulators
Simulators for use on a PC that can be used for demonstration purposes
## Keypress Event Simulations
Various ways to introduce hardware actions by way of the keyboard
### All Models
#### Up Arrow Key = Clockwise Right Rotary Knob Rotation
#### Down Arrow Key = Counterclockwise Right Rotary Knob Rotation
#### Right Arrow Key = Clockwise Left Rotary Knob Rotation
#### Left Arrow Key = Counterclockwise Left Rotary Knob Rotation
#### End Key = Right Rotary Knob Switch (press and release knob)
#### Home Key = Left Rotary Knob Switch (press and release knob)
Rotary Knob Switches are used to advance the underline position one place to the left when rotary knob tuning is active.
### SLICE-QTC
#### P Key = Simulates a Device Power Exceeded condition
#### C Key = Simulates an Incompatable Thermistor Coefficients condition
#### T Key = Simulates a Temperature Hard Limit Exceeded condition
#### A Key = Increments the percentage complete during a simulated Auto Tune
#### F Key = Auto Tune Finished
#### L Key = Triggers an Auto Tune No Limit Cycles Error
#### I Key = Triggers an Auto Tune Current Lower Bound Exceeded Error
#### O Key = Triggers an Auto Tune Timeout Error
### SLICE-DCC
#### I Key = Simulates an Interlock Circuit Open condition
#### H Key = Simulates a Hardware Temperature Exceeded condition
#### A Key = Simulates an Ambient Temperature Exceeded condition
#### O Key = Simulates an Open Circuit on the current output condition
#### F Key = Simulates a possible fault detected
#### P Key = Simulates a Power Limit Exceeded condition
### SLICE-FFC100
#### F Key = Toggles availability of Load Limits and Plant settings on the Settings menu
#### (Ctrl + P) Key = Decrements the PZT voltage by 0.5
#### P Key = Increments the PZT voltage by 0.3
#### (Ctrl + O) Key = Decrements the OSC Modulation current by 0.5
#### O Key = Increments the OSC Modulation current by 0.5
#### T Key = Triggers a Temperature Out of Range error
#### I Key = Simulates an Interlock Circuit Open condition
