# Puntuación

Proyecto | Adquisición y utilización de datos | Relevancia y conclusiones específicas de Decred | Funcionalidad, facilidad de uso y accesibilidad | Ejecución | Documentación | Total
---|--:|--:|--:|--:|--:|--:
[Bitmoney](#bitmoney)              | 5  | 3  | 10 | 12 | 16 | 46 |
[Dcrtime&nbsp;explorer](#dcrtime)  | 15 | 15 | 16 | 18 | 13 | 77 |
[Decred&nbsp;Memories](#memory)    | 10 | 12 | 15 | 10 | 7  | 54 |
[Digital&nbsp;Identity](#identity) | 10 | 8  | 8  | 11 | 12 | 49 |
[iPati](#ipati)                    | 2  | 3  | 5  | 2  | 4  | 16 |
[People&nbsp;of&nbsp;Pi](#pop)     | 15 | 15 | 16 | 18 | 15 | 79 |

<a name="bitmoney"></a>

# Bitmoney

- Video 1: https://youtu.be/IhAkr-J2vwk
- Video 2: https://youtu.be/vvUANCgsFP8
- Código: https://github.com/Carlos-Carballo/Bitmoney

### Evaluación

- Utiliza principalmente la información sobre los precios y volumen de blockchain, aunque hay muchas métricas únicas del blockchain de Decred que podría incorporar que no considera esta entrega
- No veo nada que aplique específicamente a Decred en esta propuesta
- Las aplicaciones que minan, recopilan y transforman métricas relacionadas con el precio son bastante comunes
- El modelo de predicción parece ser original y puede o no ser un buen modelo, pero no tiene ninguna relevancia particular con Decred
- Es un sitio web con un diseño fácil de navegar
- La presentación de los datos, especialmente los títulos de las columnas no me quedan muy claros
- La documentación (PDF) explica bien tanto el diseño como las herramientas y técnicas para calcular las métricas que se usan en el modelo
- La primera documentación que vemos (README.md) no explica casi nada y no tiene enlaces para guiarnos, así que tenemos que buscar en el repositorio para encontrar la documentación

<a name="dcrtime"></a>

# Dcrtime Explorer

- Video: https://youtu.be/CdRPrywc-WU
- Código: https://github.com/yoandresaav/dcrtime-explorer
- Sitio en vivo: https://dcrtime-explorer.herokuapp.com/

### Evaluación

- Usa datos de varias fuentes de Decred, incluyendo blockchain y el servicio dcrtime
- Es un servicio que aplica directamente a Decred
- Tener verificación de firmas integrada directamente con el servico de timestamping es útil
- Las características básicas son fáciles de usar y como es una aplicación en linea no requiere que el usuario la instale
- Hay dos cosas que me llamaron la atención en cuanto al uso que no están bien definidas:
  - Gestión de claves
    - Este es un tema bastante complicado para muchos y la app más o menos lo ignora por completo
  - No ofrece (que yo sepa) una manera de utilizar claves públicas ya existentes
- La aplicación funciona según la descripción y el video
- La información presentada en la app y en README.md explica bien el proceso y propósito
- El código no tiene casi nada en cuanto a comentarios y los que hay solo dicen cosas como "util function" los cuales no ayudan al lector

<a name="memory"></a>

# Decred Memories

- Video: https://youtu.be/w-6C0tExLFI
- Código 1: https://github.com/aeh-bonilla/decred-memories-api
- Código 2: https://github.com/aeh-bonilla/decred-challenge-frontend

### Evaluación

- Incluye datos que aplican específicamente a Decred como:
  - Precio de tickets
  - Agendas Decred
- La información y las noticias se adaptan específicamente a Decred
- La interfaz es fácil de entender y tiene buena pinta
- La parte que tal vez sería la más interesante no funciona y tampoco hay información sobre cómo pretende lograr la meta de recopilar y mostrar los datos más relevantes
- La documentación explica el proceso de compilacion pero no hay un descripción técnica de cómo funciona
- El código no tiene ninguna documentación como por ejemplo comentarios

<a name="identity"></a>

# Digital Identity powered by Decred

- Video: https://youtu.be/HwjgUemRL-g
- Código: https://github.com/eliseoabelcarh/NodeJs-MongoDb-ChallengeAPI-DecredBlockchain

### Evaluación

- En cuanto a la utilización de datos de Decred, usa las APIs de timestamp para guardar y verificar la información
- Por lo que veo, no hay ninguna parte del sistema que require Decred
- La gestión de datos personales involucra las leyes de varios países y no veo nada al respecto
- De acuerdo con los mockups el uso no parece demasiado difícil pero faltan muchos detalles así que es muy probable que sea más complicado de lo que está presentado cuando haya todos los pasos obligatorios para cumplir las leyes respectivas
- Ofrece una API de tipo REST que es importante para el uso del servicio
- La descripción del propósito del proyecto es buena
- Hay documentación para las APIs y configuración del software
- El código no tiene ninguna documentación ni comentarios

<a name="ipati"></a>
# iPati

- Video: https://youtu.be/vIMALr1xh0E
- Código: https://github.com/manueldevmx/ipati-blc

### Evaluación

La verdad es que no hay casi nada disponible como para hacer una evaluación.
Sólo hay  una plantilla que parece una autocreación de la herramienta
[Create React App](https://github.com/facebook/create-react-app).

No está claro cómo pretende usar datos de la blockchain.  Dice que tiene que ver
con un sitio de crowdfunding, pero no menciona nada mas que "soportado" con
blockchain.  Pero, ¿cómo es entonces que está apoyada?

Tampoco hay una app con la que evaluar la facilidad de uso y accesibilidad, pero
como esto sería un sitio de web a base de React, es probable que sea normal en
este ámbito.

<a name="pop"></a>

# People of Pi

- Video: https://youtu.be/EYh4YJjEkTI
- Código: https://github.com/Pandogrammer/people-of-pi
- Sitio en vivo: http://34.86.240.81:8080/

### Evaluación

- Extrae varios datos de Politeia y los transforma de manera útil e intuitiva
- Proporciona un servicio que aplica directamente a Decred
- Puede ayudar a los stakeholders a tomar mejores decisiones
- Es fácil de usar y no require conocimientos especiales por parte del usuario
- El prototipo ya funciona y hace exactamente lo que pretende
- La documentación e información presentadas en la app, están claras
- La información en pitch.txt explica con claridad el proceso y propósito
- El código tiene algunos comentarios útiles pero aún puede mejorar
