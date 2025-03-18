## UDP Custom - Installer and Manager
#### * Version ⇢ 2.5-Lite
---
UDP (Protocolo de Datagramas de Usuario) es un protocolo de comunicación de red que opera sobre IP (Protocolo de Internet). Es un protocolo más simple que TCP (Protocolo de Control de Transmisión), ya que prioriza la velocidad sobre la fiabilidad.


---
<center><img src="https://raw.githubusercontent.com/http-custom/udp-custom/main/bin/banner.jpg" alt="banner" width="400"/></center>

# Supported OS
- ubuntu 20.04 [x86_64] ✅ _(recommended)_
- [arm] ❌

## Install
```
sudo -s
``` 
```
git clone https://github.com/rogellevi/udp-custom && cd udp-custom && chmod +x install.sh && ./install.sh
```


## Manually

## Note: 
 * Utilice la exclusión de puerto opcional cuando el puerto UDP entre 1 y 65535 ya esté en uso por otro túnel UDP, como badvpn, ovpn UDP y otros.
 * Edite la ruta config /root/udp/config.json, luego cámbiela y reinicie.
 * Exclusión de puerto opcional separada por coma, ej. 53,5300

#
  > _made from pieces with ❤️_
#
