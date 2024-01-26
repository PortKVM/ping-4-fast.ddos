### P4FD (Ping 4 Fast DDOS)
## Another DDOS Tool (Built in to Linux/Windows using the ping tool)

### Importent:
- Microsoft might patch this tool
- Kali or Debian 12 is good, because most of the -commands are working fine

Command: 

For Windows Users:
```nodejs
// Domain
ping example.com -f -t -l 1

// IP
ping 93.184.216.34 -f -t -l 1
```

For Linux (Very Good at ddos pinging)
```node
// Domain
ping example.com -bits 1024 -s 1024

// IP
ping 93.184.216.34 -bits 1024 -s 1024
```

How this works:
```js
ping (URL/IP)
 -f // flood (supported on any OS that has an ping command, Doesnt work on linux)
 -t // run in a loop (THIS DOESNT WORK ON LINUX)
 -l 1 // Send 1 byte (THIS DOESNT WORK ON LINUX)
 -bits 1024 // Run fast (Only on Linux)
 -s // Bit size (Only works on linux)
```
