# Unified-IoT-Gateway
Es soll ein Gateway entwickelt werden, dass zwischen empfangenen CoAP Nachrichten und einem Messagebroker (in diesem Fall der RabbitMQ) vermittelt. Anschließend werden die Nachrichten mit Zusatzinformationen wie z.B URL oder Source angereichert. Im letzten Schritt wird die CoAP Nachricht in eine AMQP Nachricht convertiert und an den Messagebroker übergeben (Unified).
