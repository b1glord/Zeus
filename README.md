# Zeus
 Zeus - Ragnarok Packet Logger
 
## Requeriments
  - Visual Studio 2019 (C++ support)
 
## Configuration
You can configure the dll in `config.h` 

`Connection_use_WS2 <true|false>` Use Winsock lib instead of Ragnarok CRagConnection Functions
`DEBUG <true|false>` Enable / Disable Packet Dumper

`CRagConnection_instanceR_address 0XFFFFFFFF` CRagConnection_instanceR Hexadecimal Adresss
`CRagConnection_SendPacket_address 0XFFFFFFFF` CRagConnection_SendPacket Hexadecimal Adresss
`CRagConnection_RecvPacket_address 0XFFFFFFFF` CRagConnection_RecvPacket Hexadecimal  Adresss
 
## Finding CRagConnection Adresses
 1. Use BPE (`info.py`):
https://gitlab.com/4144/bpe/
2. Get it from output folder

## Updating PacketDB
PacketDB is based in recvpackets.txt
Coming soon... 

## Injecting into Ragnarok Client
1. Copy the Zeus.dll to Ragnarok Folder
2. Rename Zeus.dll to Zeus.asi
3. Start Ragnarok

Or use some DLL Injector (recommended):
https://guidedhacking.com/resources/guided-hacking-dll-injector.4/

## Prints
- Packet Logger (DEBUG OFF):
![debugOFF](https://i.imgur.com/SWhk1IW.png)
- Packet Logger (DEBUG ON):
![debugON](https://i.imgur.com/FV6rJbC.png)
