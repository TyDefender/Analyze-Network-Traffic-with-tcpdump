<h1>Analyze Network Traffic with TCPDump</h1>

<h2>Description</h2>
In this project, I engineered a custom script designed to execute a targeted tcpdump for a specific host. The script was carefully crafted with the incorporation of distinct variables, enhancing the interpretability of the captured data. I made the script executable through the integrated terminal, leveraging the power of the chmod command. The culmination of this process involved capturing a concise set of 10 packets, followed by the seamless upload of the resulting file to Wireshark for in depth analysis and insights. This endeavor showcased a systematic approach to network data capture and analysis, underlining the synergy between custom scripting and powerful tools like Wireshark.
<br/>

<h2>Shell Script</h2>

<b>sudo tcpdump -#XXtttt host skyroute66.com -w captured.pcap -C 1 -G 600</b>
- <b>(XX) hexadecimal</b> 
- <b>(tttt) timestamp</b>
- <b>(-w) write</b>
- <b>(-C) Limits the size in megabytes</b>
- <b>(-G) Limits the time in seconds</b>

<h2>Tools Used</h2>

- <b>tcpdump</b> 
- <b>Shell Scripting</b>
- <b>Visual Code Studio</b>
- <b>Wireshark</b>

<h2>Environments Used </h2>

- <b>Ubuntu</b>

<h2>Project walk-through:</h2>

<p align="center">
Create a script (watchdog.sh) designed to execute a targeted tcpdump for skyroute66.com<br/>
<img src="https://i.imgur.com/rus4X38.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Use integrated terminal to make watchdog.sh executable<br/>
<img src="https://i.imgur.com/JIFOR2I.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Visit site to genrate traffic and dump to capture.pcap<br/>
<img src="https://i.imgur.com/H8Kqin1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Upload dump file to Wireshark for further analysis<br/>
<img src="https://i.imgur.com/WdWTF2S.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
