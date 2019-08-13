# IA_trab_final

Inteligência Artificial - Mestrado Profissional em Computação Aplicada
Prof. Dr. Jefferson O. Andrade

Campus Serra - Instituto Federal do Espírito Santo
2019/01

Trabalho Final de IA
Aluno: Lúcio Antônio Stange Venturim

Este trabalho se propõe a utilizar o modelo desenvolvido pelo aluno do mestrado em Engenharia de Controle e Automação, Rodrigo Piol Capucho, em sua dissertação de mestrado de título “Sistema De Reconhecimento De Gestos E Sequencias De Movimento De Uma Mão A Partir De Sensores Inerciais Para O Controle De Uma Cadeira De Rodas Robotizada Usando Redes Neurais Convolutivas”, com técnicas diferentes das aplicadas. O trabalho do aluno tem como proposta utilizar técnicas de reconhecimento de padrões para detectar automaticamente um gesto e atribui-lo a uma classe de controle.

Como metas, serão duas frentes: uma é utilizar extração de características antes da aplicação dos métodos de classificação, o que não foi realizado explicitamente no trabalho citado, e a outra é a aplicação de diferentes métodos de classificação - o k-Nearest Neighbours (k-NN) e o Support Vector Machine (SVM).

O desenvolvimento será com a linguagem Python 3.6, através do ambiente de desenvolvimento Colaboratory, do Google. O código com as alterações será exibido aqui. Os resultados dos modelos gerados serão comparados com os encontrados no trabalho citado.

A base de dados utilizada é a disponibilizada em Pinojoke (2015), que possui 1800 gestos individuais captados de 20 indivíduos utilizando sensores inerciais (acelerômetros e giroscópios).


Referências

PINOJOKE. Gestures InertialSensors EAAI - Raw data respository. 2015. Disponível em:
<https://github.com/pinojoke/Gestures_InertialSensors_EAAI>. Acesso em: 12 ago. 2019.
