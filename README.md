# Energy House for Home Assistant

Inspired by the Anker app 💡, I tried to recreate it a little. The sensors are mainly from the Anker Solarbank 2 1600 AC and Shelly Pro 3EM.
I spent a lot of time to this 'Integration' 😉

<p>
<img src="anker_app.png" height="300">
<img src="dashboard.png" height="300">
</p>

Source: https://beta.ankersolix.com/de

It was not possible to install the Shelly Pro 3EM in the central distribution cabinet. This was installed in the apartment. In the basement, Tasmota sockets are connected via an LTE router so that the energy values can be read out. For this reason, there are also two pictures, with and without the basement.

## Funtions

- If sensors are unavailable or unknown, a warning icon will be shown
- If Basement is offline a warning icon will be shown and different sensors will be used

## Additional Resources

- [Anker Solix – Home Assistant Energiedashboard & Steuerung](https://www.simon42.com/anker-solix-home-assistant/)
- [Anker Solix Integration for Home Assistant](https://github.com/thomluther/ha-anker-solix/)

## Samples

