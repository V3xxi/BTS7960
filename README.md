# Wokwi-Chip-BTS7960
## Description

BTS7960 motor driver

-  

To use this chip in your project, include it as a dependency in your `diagram.json` file:

```json
"dependencies": { "chip-bts7960": "github:V3xxi/BTS7960/Wokwi-Chip-BTS7960@latest" }
```

Then, add the chip to your circuit by adding a `chip-l298n` item to the `parts` section of `diagram.json`:

```json
  "parts": {
    ...,
    {
      "type": "chip-bts7960",
      "id": "driver1",
      "attrs": { }
    },
```

## License

This project is licensed under the MIT license. See the [LICENSE](https://github.com/drf5na/Wokwi-Chip-L298N/blob/main/LICENSE) file for more details.
