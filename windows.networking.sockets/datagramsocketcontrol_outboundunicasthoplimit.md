---
-api-id: P:Windows.Networking.Sockets.DatagramSocketControl.OutboundUnicastHopLimit
-api-type: winrt property
---

<!-- Property syntax
public byte OutboundUnicastHopLimit { get;  set; }
-->

# Windows.Networking.Sockets.DatagramSocketControl.OutboundUnicastHopLimit

## -description
Gets or sets the hop limit on an outbound packet sent to a unicast IP address by the [DatagramSocket](datagramsocket.md) object.

## -property-value
The hop limit on an outbound packet sent by the [DatagramSocket](datagramsocket.md) object. The default is 128.

## -remarks
This [OutboundUnicastHopLimit](datagramsocketcontrol_outboundunicasthoplimit.md) property is the hop limit set on an outbound datagram packet sent to a unicast IP address using the [DatagramSocket](datagramsocket.md) object. This property is used to set the Time to Live (TTL) field in an IPv4 packet header. This property is used to set the Hop Limit field in an IPv6 header. The default value for this property is 128.

This property can be set before or after the [DatagramSocket](datagramsocket.md) is bound or connected. Before changing this value on a bound or connected [DatagramSocket](datagramsocket.md), any outgoing packets should first be flushed to ensure that all previously-written data is sent out with the previous hop limit.

Setting the [OutboundUnicastHopLimit](streamsocketcontrol_outboundunicasthoplimit.md) may not have an effect if the system doesn't support setting the TTL.

## -examples

## -see-also
[How to use advanced socket controls  ](http://msdn.microsoft.com/library/2e1071d8-a1c7-44c0-b93a-31a701d431c4), [How to use advanced socket controls  ](http://msdn.microsoft.com/library/f2c5be73-3461-452e-a38f-d2ddef9b5682), [DatagramSocket](datagramsocket.md)

## -capabilities
ID_CAP_NETWORKING [Windows Phone]