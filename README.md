# Durable Function Example 

Ejeplo para usar Durable function en Azure Function, basado en [Creaci贸n de la primera funci贸n durable en Python](https://docs.microsoft.com/es-es/azure/azure-functions/durable/quickstart-python-vscode?tabs=windows)

## Comenzando 馃殌

_Estas instrucciones te permitir谩n obtener una copia del proyecto en funcionamiento en tu m谩quina local para prop贸sitos de desarrollo y pruebas._

Mira **Deployment** para conocer como desplegar el proyecto.


### Pre-requisitos 馃搵

Instalar
- [Azure Function Core Tools](https://docs.microsoft.com/en-us/azure/azure-functions/functions-run-local?tabs=v4%2Cwindows%2Ccsharp%2Cportal%2Cbash)
- [Extensi贸n Azure Function para Visual Studio](https://github.com/microsoft/vscode-azurefunctions)

### Instalaci贸n 馃敡

Para ejecutar en local

```
pip install -r requirements.txt
```

En Azure las librer铆as se instalan automaticamente

## Ejecutando las pruebas 鈿欙笍

_Explica como ejecutar las pruebas automatizadas para este sistema_

```
func host start
```

### Consultar la API 馃敥

_Explica que verifican estas pruebas y por qu茅_

```
http://localhost:7071/api/orchestrators/DurableFunctionsOrchestrator
```

ver en la carpeta Insomnia Instance, para ver un ejemplo de RestFull con Insomnia


## Despliegue 馃摝

Para desplegar usando [Visual Studio Code](https://fecork.notion.site/Desplegar-c-digo-en-Azure-Function-con-Visual-Studio-Code-df55f8a586af43709ef499ab4dc298c4)

Para desplegar a trav茅s de DevOps
[Pipeline](https://fecork.notion.site/Pipeline-para-Azure-Function-4a46b6b2529a4311841d6a51516ecf2a)
[Release](https://fecork.notion.site/Release-para-Azure-Function-3203b3a312aa40a79c2074533fc252d5)

## Construido con 馃洜锔?

_Menciona las herramientas que utilizaste para crear tu proyecto_

* [Azure Functions SDK](https://pypi.org/project/azure-functions/) - Microsoft

## Contribuyendo 馃枃锔?

Por favor lee el [CONTRIBUTING.md](https://gist.github.com/villanuevand/xxxxxx) para detalles de nuestro c贸digo de conducta, y el proceso para enviarnos pull requests.

## Wiki 馃摉

Puedes encontrar mucho m谩s de c贸mo utilizar este proyecto en nuestra [Wiki](https://github.com/tu/proyecto/wiki)

## Versionado 馃搶

Usamos [SemVer](http://semver.org/) para el versionado. Para todas las versiones disponibles, mira los [tags en este repositorio](https://github.com/tu/proyecto/tags).

## Autores 鉁掞笍

_Menciona a todos aquellos que ayudaron a levantar el proyecto desde sus inicios_

* **Wilberth Ferney C贸rdoba Canchala** - *Trabajo Inicial* - [LinkenId](https://github.com/villanuevand)
## Licencia 馃搫

Este proyecto est谩 bajo la Licencia (Tu Licencia) - mira el archivo [LICENSE.md](LICENSE.md) para detalles

## Expresiones de Gratitud 馃巵

* Comenta a otros sobre este proyecto 馃摙
* Invita una cerveza 馃嵑 o un caf茅 鈽? a alguien del equipo. 
* Da las gracias p煤blicamente 馃.
* etc.