# mqtt
mqtt_test
publish and subscribe;
1.need agent service , confirm ip address.confirm topic name. both publish and subscribe;
2.need read source code about client.class MQTTMessage:
    """ This is a class that describes an incoming message. It is passed to the
    on_message callback as the message parameter.

    Members:

    topic : String. topic that the message was published on.
    payload : String/bytes the message payload.
    qos : Integer. The message Quality of Service 0, 1 or 2.
    retain : Boolean. If true, the message is a retained message and not fresh.
    mid : Integer. The message id.
  """ 
  
