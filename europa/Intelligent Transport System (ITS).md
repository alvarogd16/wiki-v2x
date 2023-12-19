# Estándar europeo ITS

En el estándar europeo [EN 302 665](https://www.etsi.org/deliver/etsi_en/302600_302699/302665/01.01.01_60/en_302665v010101p.pdf) se define la arquitectura de comunicaciones para aplicaciones ITS y V2X.

Normalmente al estándar europeo se le conoce como ITS-G5 pero como veremos más adelante esta solo es una de las capas que componen el protocolo.

En el informe técnico [TR 102 638](https://www.etsi.org/deliver/etsi_tr/102600_102699/102638/01.01.01_60/tr_102638v010101p.pdf) podemos encontrar una serie de aplicaciones básica de este tipo de tecnología.
## Pila de protocolos

| Protocolos | Niveles OSI |
| -----------| ------------|
| Servicios | 5, 6, 7 |
| Red y transporte | 3, 4 |
| Acceso | 1, 2 |

Se añade el bloque de "Aplicación" en el que se hace referencia a las aplicaciones que hagan uso de los servicios ITS.

Se añade el bloque "Gestión" que es el encargado de gestionar las comunicaciones de la estación ITS.

Se añade el bloque "Seguridad" que provee de servicio de seguridad a las diferentes capas.

El esquema general queda así:
![[ArquitectureITS.png]]

