<a name="readme-top"></a>

# IoT-CarController
Repositório para a matéria de Projetos em IoT 2024.1

Esse é um Projeto de IoT voltado para o controle remoto de um Veículo Elétrico. As funcionalidades dessa aplicação consiste em realizar o controle de direção do veículo, bem como receber imagem de vídeo atraves de uma câmera implementada no protótipo. Todo esse controle será feito atraves de uma página WEB, que mostrará uma interface com o vídeo que o veículo estará gravando. 
   
## :wrench: Explicação do programa
### Interface Web

Para realizar a implementação do servidor web na nossa aplicação, foi utilizada a ferramenta do JavaScript `Express` para o Back-End, juntamente com `HTML` e `CSS` para o Front-End. 

O protocolo de comunicação escolhido  para o projeto é o `Websocket` e o `SSH`.

O hardware escolhido para realizar o controle e alimentação do veículo é a placa `Torizon Toradex`.

Para realizar o streaming e o processamento de imagens do vídeo, foi utilizado a biblioteca `OpenCV` do Python.

### Funcionalidades 
A página web conta com uma interface gráfica que disponibilizará o vídeo e a direção que o veículo está percorrendo.

O programa verifica se o veículo está devidamente conectado ou se ocorreu um erro de conexão.

O vídeo contará com uma aplicação de Visão Computacional, a qual realizará a detecção de cones e distância entre eles.


## :rocket: Rodando o projeto

1. Clone o repositório
   ```sh
   git clone git@github.com:VitorFMaiaB/IoT-CarController.git
   ```
2. Inicialize o programa
   ```cmd
   python proj_main.py
   ```
3. Acesse a página web da aplicação
   ```cmd
   python proj_main.py
   ```
## :memo: License

Distributed under the GNU General Public License v3.0. See `LICENSE.txt` for more information.

## :handshake: Colaboradores
<table>
  <tr>
    <td align="center">
      <a href="https://github.com/ryan-costa01">
        <img src="https://avatars.githubusercontent.com/u/63657064?s=400&u=cae3d15c188ed977d1713fb373a5a42a145ae3ba&v=4" width="100px;" alt="Foto de Ryan Costa no GitHub"/><br>
        <sub>
          <b>Ryan Costa</b>
        </sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/VitorFMaiaB">
        <img src="https://avatars.githubusercontent.com/u/115305435?v=4" width="100px;" alt="Foto de Vitor Maia no Github"/><br>
        <sub>
          <b>Vitor Maia</b>
        </sub>
      </a>
    </td>
