# Trabalho de CG 2018/1

## Descrição:
Este repositório é o projeto da disciplina de **Computação Gráfica** (atualmente referente à fase 2) do ano de 2018 do curso **CC-So - Ciência da Computação** da **UFSCar** - campus Sorocaba.


## Integrantes:
- João Paulo Bologna - 609684
- João Paulo Franscisco de Paula - 587370
- Matteus Takeshi Dias (OmTsTM) - 587400


## Objetivo:
### Fase 1: Nesta fase, um objeto 3D (optamos por um gato obeso), de tamanho ideal para o volume de visão, é exibido na tela, conforme ilustrado:

![](fase1.png)

### Fase 2: Nesta fase foi inserido um novo objeto 3D (optamos por um rato), realizado transformação de escala e rotação dos objetos, além da implementação de deslocamento da câmera ao redor dos objetos, conforme ilustrado:

![](fase2.png)

### Fase 3: Nesta fase inserimos dois novos objetos: um queijo e uma faca, somando um total de 4 objetos diferentes na cena. 
É possivel chavear entre câmeras (visão lateral e superior dos objetos) com: 
* Pressionando 1 - Câmera lateral;
* Pressionando 2 - Câmera superior.

Aplicação da iluminação Phong sobre os objetos: rato e gato.
Fonte utilizada: https://github.com/sneha-belkhale/threejs-shader-demo (também é referenciada dentro do código).

Criação de curvas (CatmullRomCurve) para que os objetos descrevam um movimento sobre elas.

![](fase3.png)
![](fase3_2.png)
![](fase3_3.png)


## Implementação:
O código foi feito em JavaScript, com auxílio da API [Three.js] (a qual facilita o trabalho com objetos 3D).

Inicialmente nosso objeto foi baixado do site [Free3D] e posteriormente convertido para json (também fazemos o uso de .obj's para outras funções dentro do projeto).

Para permitir uma melhor visualização do objeto, foi aplicado redimensionamento e implementada uma rotação com velocidade constante a alguns casos.

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


Algumas referências importantes:
[Three.js]: <https://threejs.org/>
[Free3D]: <https://free3d.com/>
