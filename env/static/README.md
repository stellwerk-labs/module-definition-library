# Example

```shell
octl create module \
    --set=resource_type=env \
    --set=module_source=git::https://github.com/stellwerk-labs/module-definition-library//env/static \
    --set=module_inputs='{"values": {"KEY": "VALUE"}}'
```
