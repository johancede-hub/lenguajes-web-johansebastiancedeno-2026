# Bitácora de inspección HTTP - Semana 1

## Sitio 1: Estado Colombiano
* [cite_start]**URL completa:** https://www.gov.co/ [cite: 9]
* **Fecha y hora de la observación:** 10 de mayo de 2026, 10:05 AM
* [cite_start]**Código de estado del documento principal:** 304 
* [cite_start]**TTFB:** 130,01 ms 
* **Tamaño total transferido:** 1,2 MB
* [cite_start]**Número total de peticiones:** 202 
* [cite_start]**Lista de redirecciones 3xx:** Ninguna observada. 
* [cite_start]**Autoridad emisora del certificado TLS:** Amazon 
* [cite_start]**Fecha de expiración del certificado:** jueves, 19 de noviembre de 2026, 18:59:59 

### Evidencias
[cite_start]![Panel Network Sitio 1](capturas/sitio1-network.png) [cite: 14, 26]
[cite_start]![Certificado TLS Sitio 1](capturas/sitio1-tls.png) [cite: 14, 27]

## Sitio 2: Institución Universitaria (María Cano)
* **URL completa:** https://www.fumc.edu.co/
* **Fecha y hora de la observación:** 10 de mayo de 2026, 10:20 AM
* [cite_start]**Código de estado del documento principal:** 200 OK [cite: 10]
* [cite_start]**TTFB (Time To First Byte):** 1,02 s 
* [cite_start]**Tamaño total transferido:** 988 kB [cite: 10]
* [cite_start]**Número total de peticiones:** 217 [cite: 10]
* **Lista de redirecciones 3xx observadas:** Ninguna en el documento principal.
* [cite_start]**Autoridad emisora del certificado TLS:** GlobalSign RSA OV SSL CA 2018 
* [cite_start]**Fecha de expiración del certificado:** sábado, 7 de noviembre de 2026 

### Evidencias Sitio 2
![Panel Network Sitio 2](capturas/sitio2-network.png)
![Certificado TLS Sitio 2](capturas/sitio2-tls.png)

## Sitio 3: Comercio Colombiano (Éxito)
* **URL completa:** https://www.exito.com/
* **Fecha y hora de la observación:** 10 de mayo de 2026, 10:27 AM
* **Código de estado del documento principal:** 200 OK
* **TTFB (Time To First Byte):** 114,94 ms
* **Tamaño total transferido:** 1,7 MB
* **Número total de peticiones:** 371
* **Lista de redirecciones 3xx observadas:** Ninguna en la petición del documento.
* **Autoridad emisora del certificado TLS:** Google Trust Services (WE1)
* **Fecha de expiración del certificado:** sábado, 20 de junio de 2026

### Evidencias Sitio 3
![Panel Network Sitio 3](capturas/sito3-network.png)
![Certificado TLS Sitio 3](capturas/sitio3.tls.png)