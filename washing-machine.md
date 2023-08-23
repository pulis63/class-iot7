![Washing Machine](pictures/iot-machine.png)

## Get hardware level operations e.g. wash_count
```
Topic: v1cdti/hw/get/6310301033/washing-01/model-01/WSH-SN001
Payload: {
    "action"    : "get",
    "project"   : "6310301033",
    "model"     : "model-01",
    "serial"    : "WSH-SN001",
    "name"      : "wash_count",
    "value"     : "114"
}
```

## Get firmware version
```
Topic: v1cdti/hw/get/6310301033/washing-01/model-01/WSH-SN001
Payload: {
    "action"    : "get",
    "project"   : "610301033",
    "model"     : "model-01",
    "serial"    : "WSH-SN001",
    "name"      : "wash_count",
    "value"     : "121"
}
```

## Get manufacture id and geo-location or location placement
```
Topic: v1cdti/hw/get/6310301033/washing-01/model-01/WSH-SN001
Payload: {
    "action"    : "get",
    "project"   : "6310301033",
    "model"     : "เครื่องซักผ้าฝาบน",
    "serial"    : "WSH-SN001",
    "name"      : "wash_count",
    "value"     : "129"
}
```

## Set geo-location or location placement
```
Topic: v1cdti/hw/set/6310301033/washing-01/model-01/WSH-SN001
Payload: {
    "action"    : "set",
    "project"   : "6310301033",
    "model"     : "model-01",
    "serial"    : "WSH-SN001",
    "name"      : "location",
    "value"     : "phetchabun"
}
```

## Monitor machine sensor
```
Topic: v1cdti/hw/monitor/6310301033/washing-01/model-01/WSH-SN001
Payload: {
    "action"    : "Monitor",
    "project"   : "6310301033",
    "model"     : "model-01",
    "serial"    : "WSH-SN001",
    "name"      : "Water Level Sensor",
    "value"     : "125"
}
```

## Set machie status to "maint" to indicate this machine need to be maintenance.
```
Topic: v1cdti/hw/set/6310301033/washing-01/model-01/WSH-SN001
Payload: {
    "action"    : "set",
    "project"   : "6310301033",
    "model"     : "model-01",
    "serial"    : "WSH-SN00maint1",
    "name"      : "status",
    "value"     : "maint"
}
```
