## Plate builder configuration

These are the parameters to input in the plate builder: http://builder.swillkb.com/ for the BFO-9000 keyboard


### Layout Left

```
["","","","","","",""],
["","","","","","",""],
["","","","","","",""],
["","","","","","",""],
["","","","","","",""],
["","","","","","",""]
```

### Layout Right

```
["","","","","","","",""],
["","","","","","","",""],
["","","","","","","",""],
["","","","","","","",""],
["","","","","","","",""],
["","","","","","","",""]
```

### Switch Type

`MX {_t:1}`

### Edge Padding

Top (mm): 5

### Plate Corners

Radius (mm): 2

### Custom Polygons

- Layer: Switch Layer
- Cutout shape: Circle
- Diameter (mm): 2
- Relative to: `[-x,-y]`
- Circle centers: `[19.05, 19.05*2+5]; [19.05, 19.05*5+5]; [19.05*3, 19.05+5]; [19.05*3, 19.05*4+5]; [19.05*5, 19.05*3+5];  [19.05*6, 19.05+5]; [19.05*6, 19.05*5+5]`

