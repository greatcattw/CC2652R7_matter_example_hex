# CC2652R7_matter_example_hex
For Google home / Google nest hub gen 2 test

There are 3 hex file for test, lighting, lock, pump.<br>
You need to add you google account to google "Developer Console" and it is able to pass Matter check.<br>
<br>
![pic](pic/developer_console.png)<br><br><br>


The VID and PID is at https://github.com/TexasInstruments/matter/blob/v1.0-ti-branch/examples/xxx-app/cc13x2x7_26x2x7/args.gni <br>
All of VID is 0xFFF1.<br>
PID of lighting is 0x8001<br>
PID of lock is 0x8006<br>
PID of pump is 0x800A<br>
All of PIN is  34970112332<br>
All of QR-Code can get from UART log.<br>

The example of lock, press BTN-2 1 sec more to enable BLE advertising.<br>

![pic](pic/lock.png)<br>

![pic](pic/lighting.png)<br>

![pic](pic/pump.png)<br>





