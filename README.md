# wakeps4_on_bt Wake Ps4 on BlueTooth

### HASS Integration
Copy the custom_components folder to get it install under '/config/custom_components/wakeps4_on_bt/'.  
Edit your configuration.yaml file.

```YAML
# Wake Ps4 On BT
wakeps4_on_bt:

switch:
  - platform: wakeps4_on_bt
    adapter: 'hci0'
    dsbt_address: xx:xx:xx:xx:xx:xx
    ps4bt_address: xx:xx:xx:xx:xx:xx
```
