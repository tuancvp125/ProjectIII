# Some techiniques
## Cấp 1:
**Remote shell / command execution** — run arbitrary commands or spawn a shell on the victim.

**File system access** — upload, download, delete, list directories, read sensitive files.

**Screen capture & webcam control** — take screenshots, record webcam/video.

**Keylogging & credential theft** — capture typed passwords, clipboard scraping, browser cookie/log extraction.

**Process & service control** — start/stop processes, inject into other processes, spawn new services.

**Persistence mechanisms** — autorun registry keys, scheduled tasks, services, startup folder, WMI, DLL side-loading.

## Cấp 2

Privilege escalation helpers — exploit wrappers or credential abuse to gain higher privileges.

Port/proxy/tunnel functionality — act as proxy, port-forward, create SOCKS tunnels, reverse/forward shells.

**Command & Control (C2) communication** — beaconing to C2 over HTTP(S), DNS, WebSocket, custom protocols, sometimes covert channels.

Modular/plugin architecture — download additional modules (ransomware, miners, scanners).

**Data exfiltration** — compress/encrypt and send files to remote servers (FTP, HTTP, SMB, cloud storage).

## Cấp 3

**Anti-analysis** / sandbox detection — sleep/jitter, VM checks, debugger checks, API call timing tricks.

**Anti-forensics** — wipe logs, delete artifacts, timestomping, process hollowing.

**Encryption / obfuscation** — encoded payloads, encrypted C2 traffic, packers, custom XOR/RC4/ChaCha obfuscation.

**Bypass AV**
