# Pacote ROS para Controle e Detecção de Colisão

#### Disciplina de Robótica Móvel, ministrada pelo Prof. Dr. Jeferson Lima
#### Equipe: Ken Victor Okada Narita, Luiz Felipe Florintino, Maira Wehebrink

O objetivo do projeto é criar um pacote ROS de controle e detecção de colisão de um robô diferencial utilizando o simulador Gazebo (TurtleBot3_gazebo).

Este código está atualmente testado e funcionando com [ROS Noetic](http://wiki.ros.org/noetic/) e [Ubuntu 20.04 LTS](https://releases.ubuntu.com/20.04/).

## Sobre

Neste pacote, o robô diferencial irá desviar dos obstáculos que encontrar no seu caminho até as coordenasdas (x,y), as coordenadas são solicitadas ao usuário.

Para a detecção dos objetos, o robô utiliza o sensor [LIDAR](https://emanual.robotis.com/docs/en/platform/turtlebot3/appendix_lds_01/), um sensor que mede a distância de possiveis objetos encontrados ao redor do robô utilizando laser.


### Recomendações

É recomendado a utilização do [Ubuntu 20.04 LTS](https://releases.ubuntu.com/20.04/) e [ROS Noetic](http://wiki.ros.org/noetic/) para evitar incompatibilidades.

Para instalar os arquivos necessáros para simulação do TurtleBot 3, se recomendada que o usuário siga o [tutorial criado pelo site Automatic Addison](https://automaticaddison.com/how-to-launch-the-turtlebot3-simulation-with-ros/), que contêm os passos para a instalação dos pacotes necessários para a simulação. 

## Utilizando o pacote

Abra o terminal e digite a linha de comando:

```
$ roslaunch RoboticaMovel tb3control.launch
```

