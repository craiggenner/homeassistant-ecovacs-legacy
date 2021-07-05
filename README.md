# homeassistant-ecovacs-legacy
Fork of the Home Assistant Ecovacs integration with quick fixes

See https://github.com/home-assistant/core/tree/dev/homeassistant/components/ecovacs

In general follow the documentation at https://www.home-assistant.io/integrations/ecovacs

Changes are:

### Configuration:

```yaml
ecovacs:
  ...
  skip_devices:
    - OZMO_U2
    - Basement
```

Description:

```
skip_devices:
  description: A list of devices (by name, not id) to skip from being made available in Home Assistant, most usefull for new Ecovacs devices that this integration doesn't work with.
  required: false
  type: list
```
