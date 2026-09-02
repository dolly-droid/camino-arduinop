# Umbral Seco

## Dispositivos lowtech e interfaces interactivas

**Equipo:** Umbral Seco
**Problemática:** Desecación ambiental y riesgo de incendios forestales

![Foto del equipo](imagenes/S01/equipo.png)

## Descripción

**Umbral Seco** aborda la dificultad de percibir los cambios progresivos de humedad y temperatura que producen la desecación del ambiente y de la vegetación. El proyecto se enfoca principalmente en habitantes de zonas de interfaz urbano-forestal, donde viviendas y vegetación se encuentran próximas y existe una mayor exposición a incendios forestales. A través de un dispositivo low-tech basado en Arduino, se busca registrar variables ambientales y traducirlas en una señal física y comprensible que permita visualizar cómo aumenta la sequedad del entorno a lo largo del tiempo.

## Equipo

| Integrantes   |
| ------------- |
| Martina Casas |
| Mirrayn Tapia |

## Desafío o problemática inicial

La desecación del ambiente es un proceso progresivo que puede resultar difícil de percibir de manera cotidiana. Factores como las altas temperaturas, la disminución de la humedad ambiental y la pérdida de humedad de la vegetación generan condiciones que pueden favorecer la propagación de incendios forestales.

El desafío consiste en **hacer visible este proceso antes de que sus efectos sean evidentes**, permitiendo observar cómo un entorno acumula condiciones de sequedad a lo largo del tiempo. En lugar de intentar predecir directamente la aparición de un incendio, buscamos detectar y comunicar cambios ambientales locales que puedan indicar una mayor susceptibilidad de la vegetación al fuego.

## Objetivo

Diseñar un dispositivo físico de baja complejidad tecnológica que permita **medir, registrar y representar la desecación progresiva de un entorno**, considerando variables como temperatura, humedad relativa del aire y humedad del suelo.

Mediante Arduino y sensores ambientales, el dispositivo buscará transformar estos datos en una representación visual sencilla que permita comprender no solo el estado actual del entorno, sino también **la acumulación de condiciones secas durante un determinado período de tiempo**.

Como primera hipótesis, planteamos que un dispositivo capaz de visualizar la disminución y permanencia de la humedad en el tiempo podría facilitar el reconocimiento de períodos de mayor desecación ambiental que normalmente son difíciles de percibir directamente.

## Usuarios y contexto

El proyecto está dirigido principalmente a **personas que habitan en zonas de interfaz urbano-forestal**, es decir, sectores donde viviendas y espacios habitados se encuentran próximos a vegetación susceptible de actuar como combustible en caso de incendio.

Como contexto inicial se consideran territorios identificados en el **Visor Chile Preparado de SENAPRED** con exposición a incendios forestales. Este contexto permite relacionar el dispositivo con situaciones territoriales reales y con medidas de prevención frente a este tipo de amenaza.

A partir de la información recopilada de **SENAPRED y CONAF**, se identificaron como variables relevantes:

* **Temperatura ambiental:** permite observar períodos de altas temperaturas.
* **Humedad relativa del aire:** permite reconocer condiciones ambientales más secas.
* **Humedad del suelo:** permite observar la pérdida progresiva de agua en el terreno.
* **Tiempo de exposición:** permite conocer cuánto tiempo permanecen determinadas condiciones ambientales.
* **Variación de la humedad:** permite observar la velocidad con que el entorno se está secando.

La primera hipótesis de dispositivo contempla el uso de un **Arduino**, un sensor de temperatura y humedad ambiental y un sensor de humedad del suelo. La información podría representarse mediante una serie de luces u otros elementos físicos que se acumulen progresivamente, haciendo visible el nivel de desecación experimentado por el entorno.

De esta manera, el dispositivo no pretende reemplazar los sistemas oficiales de prevención o alerta de incendios, sino funcionar como una **interfaz local de percepción ambiental**, capaz de hacer visible un fenómeno lento y difícil de reconocer a simple vista.

## Índice de la bitácora

* [S01 - Entrega 01](bitacora/S01.md)
* [S02 - Entrega 02](bitacora/S02.md)
* [S03 - Entrega 03](bitacora/S03.md)
