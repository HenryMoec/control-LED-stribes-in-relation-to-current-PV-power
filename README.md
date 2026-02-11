# How to visualize PV Power with a LED strip

Needs:
- smart LED strip
- Home Assistant
- Intergration for integrate the LED strip in Home Assistant
- sensor for current PV production

Set Up:
- install integration for the light strip in Home Assistant
- look for your device, if it´s show in the integration
- search for light entity in the LED device (light.{name})
- copy entity name in Developertools States
- have a look to the attributes (should be more or less similar to "attributes of the LED device")
- attributes can be used in an automation as in example automation.yaml shown
