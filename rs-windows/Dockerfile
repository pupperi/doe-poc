FROM mcr.microsoft.com/windows/servercore:1809
RUN reg add hklm\system\currentcontrolset\services\tcpip\parameters /v TcpMaxDataRetransmissions /t REG_DWORD /d 15 /f