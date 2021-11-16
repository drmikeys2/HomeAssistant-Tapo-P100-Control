# Home Assistant Tapo P100 Control
A custom integration for home assistant to control the Tapo P100 plugs

## Installation

To install the Tapo P100 integration copy the `tapo_p100_control` folder into the `custom_components` folder on your home assistant instance then these lines should be added to your `configuration.yaml` file. 

```yaml

#P100 or P105 Plug
#Example shows how to add multiple plugs
switch:
  - platform: tapo_p100_control
    ip_address: 192.168.x.10
    email: email@gmail.com
    password: some_password
    
  - platform: tapo_p100_control
    ip_address: 192.168.x.11
    email: email@gmail.com
    password: some_password
    
#L510 Series Bulbs
light:
    platform: tapo_p100_control
    ip_address: 192.168.x.x
    email: email@gmail.com
    password: Password123
```

### Using in automations


## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change

## Upcoming Features:
* Support for L530 Colour Bulbs
* UI setup integration
* Uploading to HACS

## Contributors
* [K4CZP3R](https://github.com/K4CZP3R)
* [Extreeeme](https://github.com/Extreeeme)


## License
[MIT](https://choosealicense.com/licenses/mit/)
