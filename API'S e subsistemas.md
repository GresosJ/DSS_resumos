# API's e subsistemas

Estes proximos diagrams precisam que os diagrams de dominio e de use cases estejam completos. Ao rever os modelos anteriores, devemos definir as responsabilidades:

| OculistaLN |
|:---:|
|- procura clientes;|
|- procura cliente;|
|- procura detalhes doa produtos;|
|- regista reserva dos produtos;|

      ^
      |
    Responsabilidade que a logica de negocios tem que cumprir para satisfazer o use caase! - cf.guiado pelos Use Cases

    API da logica de negocios para suportar os Use Cases.
      |
      v

![API](img/API.png)

## Diagrama de componentes