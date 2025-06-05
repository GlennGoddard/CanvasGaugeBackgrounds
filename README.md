# CanvasGaugeBackgrounds
Canvas Gauge Backgrounds for use in Home Assistant

Home Assistant Lovelace front-end yaml is included as a starting point.
The yaml will need to be modified to match the sensors that your system has.
You will need to install the custom canvas gauge for this to work.
The backgound and logo pictures need to be placed in your 'local'/'www' directory for Home Assistant.

I will be removing the blank sensor and redoing all the front-end yaml to use the custom-text-element instead of the state-label
In sensor.yaml which is included in configuration.yaml
Fake Sensor to give a blank for state-label in picture-elements card
This is not a space this is a special ASCII character between the quotes.
```
- platform: template
  sensors:
    blank_blank:
      friendly_name: "Blank Blank"
      value_template: " "
```

I am in the process of removing wording from the backgrounds and using state-label for text, this will allow any language of your choice.

| List (WIP):   | Background   | Logo   | Example   |
| --- | --- | --- | --- |
| Air Quaility (AQI)   | AQI_index.png   | AQI_Logo.png   | X    |
| Allergy   | Allergy_Blank.png   | Allergy_Logo.png   | X   |
| Asthma   | Allergy_Blank.png   | Asthma_Logo.png   | X   |
| Beaufort Wind Scale   | Beaufort.png   | Wind_Logo.png   | X   |
| Cold&Flu   | Allergy_Blank.png   | Cold_Logo.png   | X   |
| DewPoint   | Dewpoint.png   | Dewpoint_logo.png   | X   |
| Temperature   | Temperature.png   | Temperature_Logo.png   | X   |
| UV   | UV_Blank.png   | sun-UV.png   | X   |
| Wet Bulb Golb Temperature   | WBGT.png   | wbgt_logo.png   | X   |
| Air Pressure   | air_pressure.png   | air_pressure_logo.png | -   |

These examples are taken from Home Assistant and display exactly how it will look.

![alt text](https://github.com/GlennGoddard/CanvasGaugeBackgrounds/blob/main/AQI/Example_AQI.jpg?raw=true)
![alt text](https://github.com/GlennGoddard/CanvasGaugeBackgrounds/blob/main/Allergy/Example_Allergy.jpg?raw=true)
![alt text](https://github.com/GlennGoddard/CanvasGaugeBackgrounds/blob/main/Asthma/Example_Asthma.jpg?raw=true)
![alt text](https://github.com/GlennGoddard/CanvasGaugeBackgrounds/blob/main/Beaufort/Example_Beaufort.jpg?raw=true)
![alt text](https://github.com/GlennGoddard/CanvasGaugeBackgrounds/blob/main/Cold_Flu/Example_Cold.jpg?raw=true)
![alt text](https://github.com/GlennGoddard/CanvasGaugeBackgrounds/blob/main/DewPoint/Example_DewPoint.jpg?raw=true)
![alt text](https://github.com/GlennGoddard/CanvasGaugeBackgrounds/blob/main/Temperature/Example_Temperature.jpg?raw=true)
![alt text](https://github.com/GlennGoddard/CanvasGaugeBackgrounds/blob/main/UV/Example_UV.jpg?raw=true)
![alt text](https://github.com/GlennGoddard/CanvasGaugeBackgrounds/blob/main/WBGT/Example_WBGT.jpg?raw=true)
