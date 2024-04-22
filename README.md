# Arlec Grid Gld315ha Esphome
ESPHome on the Arlec Grid GLD315HA Smart Light (Bunnings Australia)

This is a screw-type bulb available from Bunnings.

Crack it open with heat and a spudger around where the white plastic meets the diffuse plastic, then pry up the LED board

It contains a Tuya WB2L module with a BK7231T chip:
https://developer.tuya.com/en/docs/iot/wb2l-datasheet?id=K9duegc9bualu


Here are the current measurements with the stock firmware:
| Colour | Current |
| ------ | ------- |
| Whites | 64mA    |
| Red    | 34mA    |
| Green  | 26mA    |
| Blue   | 27mA    |

Looks like I can solder wires onto the test points on the back of the module, after taking a bit of the edge of the green PCB with a Dremel.

Stay tuned
