---
-api-id: T:Windows.Devices.Bluetooth.GenericAttributeProfile.GattReadResult
-api-type: winrt class
---

<!-- Class syntax.
public class GattReadResult : Windows.Devices.Bluetooth.GenericAttributeProfile.IGattReadResult, Windows.Devices.Bluetooth.GenericAttributeProfile.IGattReadResult2
-->

# Windows.Devices.Bluetooth.GenericAttributeProfile.GattReadResult

## -description
Represents the result of an asynchronous read operation of a GATT Characteristic or Descriptor value.

## -remarks
One of the [ReadValueAsync](gattcharacteristic_readvalueasync.md) methods is used to retrieve a [GattReadResult](gattreadresult.md) object.

The [Status](gattreadresult_status.md) property on the [GattReadResult](gattreadresult.md) returned indicates if the result of the operation was successful.

## -examples

## -see-also
[ReadValueAsync](gattcharacteristic_readvalueasync.md), [Status](gattreadresult_status.md)