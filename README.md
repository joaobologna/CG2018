# CG 2018/1

## Descrição:
Este repositório é o projeto da disciplina de **Computação Gráfica** do ano de 2018 do curso **CC-So - Ciência da Computação** da **UFSCar** - campus Sorocaba.


## Integrantes:
- João Paulo Bologna - 609684
- João Paulo Franscisco de Paula - 587370
- Matteus Takeshi Dias - 587400


## Gato e Rato

A cena demonstra a incansável busca do rato pelo seu alimento tipicamente preferido mas sendo observado pelo seu nativo predador. Dia e noite a cena se repete, refletindo mudanças temporáis representadas pela luz emitida do sol. 

## Implementação:
O código foi feito em JavaScript, com auxílio da API [Three.js](https://threejs.org/). Os modulos adicionais importados são: 

* KeyboardState: controlar inputs do teclado.
* OBJLoader: carregar arquivos .obj.
* MTLLoader: carregar texturas.
* Particles: adição de particulas na cena.

Todos os objetos podem ser encontrados em [Free3D](https://free3d.com/), assim como suas texturas. No projecto, encontram-se sob a pasta /assets. 

## Requisitos:

* Dois objetos carregados de arquivos: OK
* Cinco objetos no total: OK
* Dois movimentos distintos: NOK
* Uma curva de bezier: OK
* Textura em algum objeto: OK
* Shader próprio de ilminação phong: OK-NOK
* Duas posições distintas de câmeras: OK
* Alguma iteração com o usuário: OK
* Um objeto articulado: NOK

Extra: Particula!

## Como executar:
Para rodar o projeto é necessário que o navegador permita a execução de arquivo externo à pagina HTML (necessário para carregar o objeto).

Siga os passos listados abaixo, em seu navegador de preferência:

### No Mozilla Firefox:
- Digite na barra de endereço: about:config
- Configure o parâmetro "security.fileuri.strict_origin_policy" para "false"
- Abra o arquivo index.html que está na raiz do projeto

### No Google Chrome:
- Feche todas as instâncias abertas.
- no Windows execute o comando: chrome --allow-file-access-from-files
- no Linux execute o comando: google-chrome --allow-file-access-from-files
- Abra o arquivo index.html que está na raiz do projeto
