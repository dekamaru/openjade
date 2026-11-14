# Dedicated Server

## What is it

A standalone relay for The Two Thrones multiplayer maps in OpenJade (Windows and Linux x86-64).

## How to use

Windows (PowerShell):

```powershell
.\openjade-relay.exe --port 27032
```

Linux:

```sh
chmod +x openjade-relay
./openjade-relay --port 27032
```

Allow inbound TCP port `27032`. Stop with **Ctrl+C**.

## OpenJade configuration

Add to `settings.ini` beside `openjade.exe` on each player's PC:

```ini
[multiplayer]
global_server_address=YOUR_SERVER_IP
global_server_port=27032
```

Replace `YOUR_SERVER_IP` with your server's address, then choose **Internet** in multiplayer.
