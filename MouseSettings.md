### Swapping Middle button to right button
```
# find out the device id
xinput --list

# swap the middle and right button for device 13
xinput --set-button-map 13 1 3 2
```
