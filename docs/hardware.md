# DIY Hardware

if you want to build your own AWTRIX Light, here are the pinout of the Ulanzi clock  

### Default

| GPIO  | Usage or part                                 |
|-------|-----------------------------------------------|
| 35    | LDR (light) sensor (GL5516)                   |
| 34    | Battery sensor                                |
| 32    | Matrix                                        |
| 26    | Left button                                   |
| 27    | Middle button                                 |
| 14    | Right button                                  |
| 15    | Buzzer                                        |
| 21/22 | Temperature and Humidity Sensors (SHT3x)      |


### ESP32 S2 PINOUT_keith

| GPIO  | Usage or part                                 |
|-------|-----------------------------------------------|
| 36    | SDA Temperature and Humidity Sensors (SHT3x)  |
| 37    | SCL Temperature and Humidity Sensors (SHT3x)  |
| 35    | LDR (light) sensor (GL5516)                   |
| 33    | Matrix                                        |
| 20    | DF player RX                                  |
| 19    | DF player TX                                  |
| 8     | Battery sensor                                |
| 7     | Buzzer                                        |
| 6     | Right button                                  |
| 5     | Middle button                                 |
| 4     | Left button                                   |

If the matrix displays meaningless characters, the matrix type must be changed.

Create a dev.json in your filemanager with the following content:

```json
{
  "matrix": 2
}
```

Change the matrix layout to 0,1 or 2
