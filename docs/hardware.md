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


### ESP32 S2

| GPIO  | Usage or part                                 |
|-------|-----------------------------------------------|
| 35    | LDR (light) sensor (GL5516)                   |
| 34    | Battery sensor                                |
| 33    | Matrix                                        |
| 26    | Left button                                   |
| 27    | Middle button                                 |
| 14    | Right button                                  |
| 15    | Buzzer                                        |
| 21/22 | Temperature and Humidity Sensors (SHT3x)      |

If the matrix displays meaningless characters, the matrix type must be changed.

Create a dev.json in your filemanager with the following content:

```json
{
  "matrix": 2
}
```

Change the matrix layout to 0,1 or 2
