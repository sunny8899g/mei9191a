port: 7890
socks-port: 7891
redir-port: 7892
mixed-port: 7893
allow-lan: false
mode: rule
log-level: info
ipv6: false
external-controller: 0.0.0.0:9090
clash-for-android:
  append-system-dns: false
profile:
  tracing: true
experimental:
  sniff-tls-sni: true
proxies:
  - {name: 🇭🇰香港 - 80端口 - 1, server: 43.198.222.208, port: 10080, type: vmess, uuid: 73530cba-9d6e-4e27-890d-ed636e458418, alterId: 0, cipher: auto, tls: false, network: ws, ws-opts: {path: /}}
  - {name: 🇭🇰香港 - 443端口 - 2, server: 13.230.161.84, port: 10443, type: vmess, uuid: 73530cba-9d6e-4e27-890d-ed636e458418, alterId: 0, cipher: auto, tls: false, network: ws, ws-opts: {path: /}}
  - {name: 🇯🇵东京 - 80端口 - 1, server: 54.250.169.220, port: 10080, type: vmess, uuid: 73530cba-9d6e-4e27-890d-ed636e458418, alterId: 0, cipher: auto, tls: false, network: ws, ws-opts: {path: /}}
  - {name: 🇯🇵东京 - 443端口 - 2, server: 18.143.91.204, port: 10443, type: vmess, uuid: 73530cba-9d6e-4e27-890d-ed636e458418, alterId: 0, cipher: auto, tls: false, network: ws, ws-opts: {path: /}}
  - {name: 🇸🇬狮城 - 80端口 - 1, server: 13.212.193.212, port: 10080, type: vmess, uuid: 73530cba-9d6e-4e27-890d-ed636e458418, alterId: 0, cipher: auto, tls: false, network: ws, ws-opts: {path: /}}
  - {name: 🇸🇬狮城 - 443端口 - 2, server: 18.143.164.254, port: 10443, type: vmess, uuid: 73530cba-9d6e-4e27-890d-ed636e458418, alterId: 0, cipher: auto, tls: false, network: ws, ws-opts: {path: /}}
  - {name: 🇰🇷首尔 - 80端口 - 1, server: 3.38.151.85, port: 18443, type: vmess, uuid: 73530cba-9d6e-4e27-890d-ed636e458418, alterId: 0, cipher: auto, tls: false, network: ws, ws-opts: {path: /}}
  - {name: 🇰🇷首尔 - 443端口 - 1, server: 43.201.53.169, port: 18443, type: vmess, uuid: 73530cba-9d6e-4e27-890d-ed636e458418, alterId: 0, cipher: auto, tls: false, network: ws, ws-opts: {path: /}}
  - {name: 🇺🇸美国西区 - 80端口 - 1, server: 43.201.19.255, port: 18443, type: vmess, uuid: 73530cba-9d6e-4e27-890d-ed636e458418, alterId: 0, cipher: auto, tls: false, network: ws, ws-opts: {path: /}}
  - {name: 🇺🇸美国西区 - 443端口 - 1, server: 3.101.103.212, port: 10443, type: vmess, uuid: 73530cba-9d6e-4e27-890d-ed636e458418, alterId: 0, cipher: auto, tls: false, network: ws, ws-opts: {path: /}}
  - {name: 🇭🇰香港 - TLS - 1, server: tls.0000000011a.node-for-bigairport.win, port: 443, type: vmess, uuid: 73530cba-9d6e-4e27-890d-ed636e458418, alterId: 0, cipher: auto, tls: true, network: ws, ws-opts: {path: /, headers: {Host: tls.0000000011a.node-for-bigairport.win}}}
  - {name: 🇭🇰香港 - TLS - 2, server: tls.0000000012a.node-for-bigairport.win, port: 443, type: vmess, uuid: 73530cba-9d6e-4e27-890d-ed636e458418, alterId: 0, cipher: auto, tls: true, network: ws, ws-opts: {path: /, headers: {Host: tls.0000000012a.node-for-bigairport.win}}}
  - {name: 🇯🇵东京 - TLS - 1, server: tls.0000000013a.node-for-bigairport.win, port: 443, type: vmess, uuid: 73530cba-9d6e-4e27-890d-ed636e458418, alterId: 0, cipher: auto, tls: true, network: ws, ws-opts: {path: /, headers: {Host: tls.0000000013a.node-for-bigairport.win}}}
  - {name: 🇯🇵东京 - TLS - 2, server: tls.0000000014a.node-for-bigairport.win, port: 443, type: vmess, uuid: 73530cba-9d6e-4e27-890d-ed636e458418, alterId: 0, cipher: auto, tls: true, network: ws, ws-opts: {path: /, headers: {Host: tls.0000000014a.node-for-bigairport.win}}}
  - {name: 🇸🇬狮城 - TLS - 1, server: tls.0000000015a.node-for-bigairport.win, port: 443, type: vmess, uuid: 73530cba-9d6e-4e27-890d-ed636e458418, alterId: 0, cipher: auto, tls: true, network: ws, ws-opts: {path: /, headers: {Host: tls.0000000015a.node-for-bigairport.win}}}
  - {name: 🇸🇬狮城 - TLS - 2, server: tls.0000000016a.node-for-bigairport.win, port: 443, type: vmess, uuid: 73530cba-9d6e-4e27-890d-ed636e458418, alterId: 0, cipher: auto, tls: true, network: ws, ws-opts: {path: /, headers: {Host: tls.0000000016a.node-for-bigairport.win}}}
  - {name: 🇰🇷首尔 - TLS - 1, server: tls.0000000017a.node-for-bigairport.win, port: 443, type: vmess, uuid: 73530cba-9d6e-4e27-890d-ed636e458418, alterId: 0, cipher: auto, tls: true, network: ws, ws-opts: {path: /, headers: {Host: tls.0000000017a.node-for-bigairport.win}}}
  - {name: 🇰🇷首尔 - TLS - 2, server: tls.0000000018a.node-for-bigairport.win, port: 443, type: vmess, uuid: 73530cba-9d6e-4e27-890d-ed636e458418, alterId: 0, cipher: auto, tls: true, network: ws, ws-opts: {path: /, headers: {Host: tls.0000000018a.node-for-bigairport.win}}}
  - {name: 🇺🇸美国西区 - TLS - 1, server: tls.0000000019a.node-for-bigairport.win, port: 443, type: vmess, uuid: 73530cba-9d6e-4e27-890d-ed636e458418, alterId: 0, cipher: auto, tls: true, network: ws, ws-opts: {path: /, headers: {Host: tls.0000000019a.node-for-bigairport.win}}}
  - {name: 🇺🇸美国西区 - TLS - 2, server: tls.0000000020a.node-for-bigairport.win, port: 443, type: vmess, uuid: 73530cba-9d6e-4e27-890d-ed636e458418, alterId: 0, cipher: auto, tls: true, network: ws, ws-opts: {path: /, headers: {Host: tls.0000000020a.node-for-bigairport.win}}}
