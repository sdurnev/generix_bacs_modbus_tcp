# generix_bacs_modbus_tcp


Read modbus arguments from 1000 to 2709 address, and returns a json object.

Programm flags:

-ip - generix_bacs ip address (defaut value "localhost");

-port - generix_bacs modbus tcp port (defaut value 502);

-id - generix_bacs modbus slave ID (defaut value 1);

-m - generix_bacs read areas values 

    -m=1 Alarm values (from 1000 to 109)

    -m=2 Strings values (from 1010 to 1059)

    -m=3 Battary modules (from 1060 to 2709)

-q - quantity of generix_bacs battary modules range, value range 1 - 17 (defaut value 1).
   
    -q=1  module from 1 - 20
   
    -q=1  module from 21 - 30
      

Example:

`jan_modbus_ip_mac_0.01.2 -ip=192.168.10.10 -port=1502 -id=2 -m=3 -q=2`