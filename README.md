{
  "Version": "3.0.0",
  "ReleaseNotes": "nueva actualización",
  "UrlUpdate": "https://github.com/mauropicoto1992/vpnnn",
  "Sms": "",
  "LogoLink": "https://i.imgur.com/4n7bZz1.jpeg",
  "BackgroundLink": "https://i.imgur.com/7YcOUJP.jpeg",
  "CheckUser": "true",
  "Udp": [
    {
      "Porta": "7300"
    }
  ],
  "Servers": [
    {
      "Name": "Servidor BR",
      "TYPE": "premium",
      "FLAG": "br.png",
      "ServerIP": "vps.vpsmaster.tk",
      "CheckUser": "linkcheckuser",
      "ServerPort": "22",
      "SSLPort": "443",
      "USER": "mauro",
      "PASS": "1234"
    }
  ],
  "Networks": [
    {
       "Name": "VIVO CLOUD",
        "FLAG": "vi.png",
       "Payload": "GET / HTTP/1.1[crlf]vps.vpsmaster.tk[crlf]Connection: Upgrade[crlf]User-Agent: [ua][crlf]Upgrade: websocket[crlf][crlf]",
       "SNI": "survey.medallia.com",
       "TlsIP": "68.183.113.90",
       "ProxyIP": "68.183.113.90",
       "ProxyPort": "443",
       "Info": "Tlsws"
    }
  ]
}
