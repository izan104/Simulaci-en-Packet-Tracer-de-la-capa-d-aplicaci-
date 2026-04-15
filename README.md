# Simulaci-en-Packet-Tracer-de-la-capa-d-aplicaci-
# 🖧 Práctica de redes: Servidores DHCP, DNS y Web

## 📌 Descripción
Esta práctica consiste en la configuración y verificación del funcionamiento de una red local con tres servicios principales: servidor DHCP, servidor DNS y servidor web. El objetivo es comprobar la comunicación entre dispositivos, la asignación dinámica de direcciones IP y la resolución de nombres de dominio.

---

## 🌐 Topología de red

Todos los dispositivos se encuentran en la red:

- Red: 192.168.1.0/24

---

## 🖥️ Configuración de servidores

### 🔹 Servidor DHCP
- IP: 192.168.1.1  
- Máscara: 255.255.255.0  
- Pool de direcciones: 192.168.1.10 – 192.168.1.200  
- DNS asignado a los clientes: 192.168.1.2  

Función: asigna automáticamente direcciones IP a los clientes de la red.

---

### 🔹 Servidor DNS
- IP: 192.168.1.2  
- Máscara: 255.255.255.0  

Configuración:
- Dominio: www.activitat41.cat  
- Resolución: 192.168.1.3 (servidor web)

Función: traduce nombres de dominio a direcciones IP.

---

### 🔹 Servidor Web
- IP: 192.168.1.3  
- Máscara: 255.255.255.0  

Contenido del archivo `index.html`:

```html
<html>
 <body>
 <h1>ESCOLA DEL TREBALL</h1>
 <h2>Benvinguts!</h2>
 </body>
</html>
