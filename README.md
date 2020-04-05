# generix_bacs_modbus_tcp


Read modbus arguments from 1000 to 2709 address, and returns a json object.

Programm flags:

-ip - generix_bacs ip address (defaut value "localhost");

-port - generix_bacs modbus tcp port (defaut value 502);

-id - generix_bacs modbus slave ID (defaut value 1);

      

Example:

`generix_bacs_modbus_tcp -ip=127.0.0.1 -port=1113 -id=1`