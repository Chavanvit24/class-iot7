![Washing Machine](pictures/iot-machine.png)

## Get hardware level operations e.g. wash_count
```
Topic: v1cdti/hw/get/6310301024/model-01/WSH-SN001
Payload: {
    "action"    : "get",
    "project"   : "6310301024",
    "model"     : "model-01",
    "serial"    : "WSH-SN01",
    "name"      : "wash_count",
    "value"     : "114"
}
```

## Get firmware version
```
Topic: v1cdti/hw/get/6310301024/model-01/WSH-SN001
Payload: {
    "action"    : "get",
    "project"   : "6310301024",
    "model"     : "model-01",
    "serial"    : "WSH-SN01",
    "name"      : "firmware",
    "value"     : "val01"
}
```

## Get manufacture id and geo-location or location placement
```
Topic: v1cdti/hw/get/6310301024/model-01/WSH-SN001
Payload: {
    "action"    : "get",
    "project"   : "6310301024",
    "model"     : "model-01",
    "serial"    : "WSH-SN01",
    "name"      : "wash_count"
    "value"     : "114"
    "location"  : "Bangkok"
}
```

## Set geo-location or location placement
```
Topic: v1cdti/hw/get/6310301024/model-01/WSH-SN001
Payload: {
    "action"    : "get",
    "project"   : "6310301024",
    "model"     : "model-01",
    "serial"    : "WSH-SN01",
    "name"      : "location",
    "value"     : "Bangkok"
}
```

## Monitor machine sensor
```
Topic: v1cdti/hw/Set/6310301024/model-01/WSH-SN001
Payload: {
    "action"    : "Set",
    "project"   : "6310301024",
    "model"     : "model-01",
    "serial"    : "WSH-SN01",
    "name"      : "rounds",
    "value"     : "2000"
}
```

## Set machie status to "maint" to indicate this machine need to be maintenance.
```
Topic: v1cdti/hw/Set/6310301024/model-01/WSH-SN001
Payload: {
    "action"    : "Set",
    "project"   : "6310301024",
    "model"     : "model-01",
    "serial"    : "WSH-SN01",
    "name"      : "wash_count",
    "value"     : "maint"
}
```