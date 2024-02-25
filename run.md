
# Gost version 3

# Gost

```bash

gost -L udp://:43800 -L tcp://:43800 -F relay+quic://194:43800

gost -L relay+quic://:43800 -L ss://chacha20-ietf-poly1305:C4s8geMyjPqDkSd9KXEtJA@:43800 -L ssu://chacha20-ietf-poly1305:C4s8geMyjPqDkSd9KXEtJA@:43800

nohup gost -L relay+quic://:43800 -L ss://aes-256-gcm:C4s8geMyjPqDkSd9KXEtJA@:43801 -L ssu://aes-256-gcm:C4s8geMyjPqDkSd9KXEtJA@:43801

```
