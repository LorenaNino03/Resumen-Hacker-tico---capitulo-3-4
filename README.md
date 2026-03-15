# Resumen-Hacker-tico---capitulo-3-4

# Capitulo 3
En este capitulo nos explica los fundamentos de la recopilación de inteligencia de código abierto , también nos explica metodologias para identificar brechas de seguridad, se habla de algunas herramientas clave como Recon-ng y Shodan, en el capitulo 3 también se logra observar técnicas de reconocimiento activo empleando Nmap, y el funcionamiento de los escáneres de vulnerabilidades.

Aqui explicamos algunos conceptos claves del texto.

# Recon-ng como Marco de Trabajo:
Su potencia radica en el uso de interfaces de programación de aplicaciones (API) con el fin de extraer información de plataformas como redes sociales. 

# Capacidades de Shodan: 
Shodan escanea dispositivos conectados a internet, bases de datos, y es capaz de identificar sistemos obsoletos o vulnerables.

# Técnicas de Escaneo con Nmap:

# Escaneo SYN (-sS): 
Conocido como escaneo "semiabierto", no completa la conexión TCP, lo que lo hace más difícil de detectar por algunos sistemas
# Escaneo de Conexión TCP (-sT):
Este si establece una conexión completa pero es mas ruidoso y propenso a activar alarmas.
# Escaneo UDP (-sU):
Identifica servicios como DNS, SNMP y DHCP

# Análisis de Vulnerabilidades:  
El proceso incluye numeración de puertos , registro de sofware y sus versiones. Estos escaneos pueden ser autenticados (con credenciales de nivel raíz) para obtener detalles internos del sistema, o pasivos, que monitorean el tráfico de la red sin interactuar directamente con los objetivos.

# Metodología y Conceptos Generales
- OSINT (Inteligencia de Código Abierto)
- Enumeración (proceso de recopilación activa)
- Superficie de ataque
- Vulnerabilidades conocidas

# Herramientas Específicas
- Recon-ng (marco modular)
- Shodan (buscador de dispositivos conectados)
- Nmap (escáner de puertos y descubrimiento)

# Capitulo 4
En este capitulo nos hablan sobre la ingenieria social la cual trata sobre la manipulación a las personas para que revelen información personal, instalen malware pensando que no es algo malo. para ello utilizan ataques digitales avanzados como el phishing, el vishing y el smishing.

Se explican algunos terminos clave que se encuentran en este capitulo.

# 1. Tácticas Fundamentales de Interacción

# Elicitación: 
Manera de obtener datos sensibles sin que la victima de se cuenta.
# Interrogatorio:
Se utilizan preguntas abiertas para conocer valores y objetivos, o preguntas cerradas para tomar el control de la conversación
# Lenguaje corporal:
Los atacantes analizan posturas, cambios de tonos en la voz, la dirección de la mirada, para asi evaluar la efectividad del engaño.

# 2. Variantes de Suplantación de Identidad:

# Phishing:
Envío de correos electrónicos con enlaces o archivos adjuntos maliciosos que imitan recursos confiables para robar credenciales
# Whaling (Caza de ballenas):
Ataque de alta sofisticación dirigido exclusivamente a ejecutivos de alto perfil (como CEOs) con un tono más formal y urgente.
# Vishing: 
Ingeniería social realizada a través de llamadas telefónicas o voz para obtener datos financieros
# Smishing: 
Uso de mensajes de texto (SMS) para engañar a las víctimas, a menudo con enlaces sobre paquetes perdidos o problemas de seguridad

# 3. Ataques Digitales y de Red

# Pharming (Suplantación de DNS): 
Redirección de un usuario de un sitio web legítimo a uno malicioso 
# Publicidad maliciosa (Malvertising):
 Inserción de anuncios maliciosos en sitios web de confianza que redirigen a los usuarios a sitios con malware

 # 4. Técnicas de Acceso Físico y Proximidad:

 # Abandono de USB (USB Drop):
 Dejar memorias USB infectadas en lugares estratégicos esperando que alguien las conecte por curiosidad o para "ayudar" a devolverlas
 # Búsqueda en la basura (Dumpster diving):
 Recuperar información privada (papeles, discos duros) de contenedores de desechos o reciclaje
 # Clonación de credenciales: 
 Uso de software y hardware para duplicar tarjetas de identificación por radiofrecuencia (RF)

 # 5. Herramientas Especializadas
# SET (Social-Engineer Toolkit): 
Herramientas para lanzar ataques de phishing y otros vectores de ingeniería social, integradas comúnmente en Kali Linux
# BeEF: 
Marco de trabajo para manipular navegadores web comprometidos y enviar notificaciones falsas
# Herramientas de falsificación de llamadas:
Aplicaciones como SpoofApp, SpoofCard o el sistema Asterisk permiten cambiar el identificador de llamadas y alterar la voz



