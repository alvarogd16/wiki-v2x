# Cooperative Awareness (CA) basic service

En el estándar [EN 302 637-2](https://www.etsi.org/deliver/etsi_en/302600_302699/30263702/01.03.01_30/en_30263702v010301v.pdf) se define el Cooperative Awareness Basic Service, además del Cooperative Awareness Message [[CAM]].

La conciencia (awareness) cooperativa respecto al tráfico se refiere a la información sobre la posición, la dinámica y sus atributos mutua entre usuarios de la via e infraestructura.

Esta información se envía a través de mensajes CAM y la construcción, gestión y procesamiento corresponde al CA service que forma parte de la capa de servicios.

## Servicios que ofrece CA basic service

### Enviar CAMs

Se compone de dos fases:
1. Generación
2. Transmisión

Se generan periódicamente con frecuencia controlada por el CA basic service. Se determina en función de diferentes factores (cambio en la posición o en la velocidad, congestión del canal, DCC...)

### Recibir CAMs

Presenta los mensajes CAM a las diferentes aplicaciones ITS y/o a otros servicios.

## Funcionalidad que debe tener

### Codificar CAM

Construye el CAM con el formato específico.

### Decodificar CAM

Decodifica el CAM recibido.

### Gestión de transmisión de CAM

- Activa y termina operaciones de transmisión CAM.
- Determina la frecuencia.
- Desencadena la generación de CAM.

### Gestión de recepción de CAM

- Desencadena la decodificación de CAM cuando llegan.
- Provee de datos del CAM a otras aplicaciones ITS y/o servicios.