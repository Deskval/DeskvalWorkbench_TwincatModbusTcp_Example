All product names, logos, and brands are property of their respective owners.

# DeskvalWorkbench_TwincatModbusTcp_Example
PLC Project Sample - Modbus Tcp Communication with Deskval Workbench

# Overview of Modbus TCP
Modbus is a serial, Client/Server protocol. Modbus TCP is the implementation of Modbus on Ethernet. For detailed information, visit https://www.modbus.org/
Clients request data using Function Codes FC, and Server will reply accordingly. 
A Modbus TCP Server is identified by IP Address and Port Number. Conventionally, Port Number 502 is popular, but other Port Numbers may be used as well.

# Deskval Workbench is a Modbus TCP Server
Deskval Workbench exposes its Modbus tables data, called as Modbus TCP Server Tags.
In 16 bit register table, a NUM value is occupies 2 registers. Deskval Modbus Tcp Server stores as Big Endian, that means High Word first then Low Word.
