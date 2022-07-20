# 2ServosTutorial
## Step 1
### Drag two "on button A button pressed" blocks 
### Change the second block to a "on button B pressed" block
```blocks
input.onButtonPressed(Button.A, function () {
	
})
input.onButtonPressed(Button.B, function () {
	
})
```

## Step 1
### Add a servo control function to it
```blocks
input.onButtonPressed(Button.A, function () {
    pins.servoWritePin(AnalogPin.P0, 180)
})
input.onButtonPressed(Button.B, function () {
    pins.servoWritePin(AnalogPin.P0, 0)
})
```