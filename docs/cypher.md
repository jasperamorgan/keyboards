
Rev7 PCB


Getting the Rev7 firmware

https://discord.com/channels/528955415719837696/528958603898519555/1151781301809070110

```
mkdir cypher7
cd cypher7
qmk setup westfoxtrot/qmk_firmware
cd qmk_firmware
git checkout cypher_r7
qmk compile -kb cablecardesigns/cypher/rev7 -km via
```
