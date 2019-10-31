# Estrada-Inteligente

## Membros
* Iury Lima Rosal (422067)
* Vinícius Almeida (413129)
* Luís Gustavo (418210) 
* Lucas Aragão (421601)

## Introdução
Nos dias atuais, o uso da tecnologia em vias auxilia no gerenciamento do tráfego e na manutenção das vias, tudo para a melhoria de fluxo de veículos e, ao mesmo tempo, provocando menos demora na entrega de mercadorias via uso de rodovias. O projeto visa o uso de sensores para a identificação de engarrafamento, fazer um controle do limite de velocidade na via e por identificar dentre duas vias aquela com melhor fluxo de carros. Tudo podendo ser monitorado e visualizado com o auxilio de um aplicativo em paralelo ao hardware com auxilio de conexão bluetooth.

## Funcionamento
2 conjuntos de sensores de infravermelho agirão em conjunto para detectar a velocidade dos carros, onde sera calculado o tempo em que um veiculo passará entre dois sensores, que por sua vez será calculado a velocidade através do tempo e da distância entre dois sensores.

Com a velocidade de uma via calculada, o mesmo processo será aplicada para uma outra via, assim podendo armazenar ambas velocidades e podendo calcular a velocidade media das duas vias. Uma vez que tudo isso foi calculado, basta comparar qual via tem uma maior velocidade media e mandar essa informação para o aplicativo através do modulo bluetooth da placa.

Por fim, para identificar o congestionamento da via, será checado se um sensor infravermelho passar muito tempo bloqueado e ,uma vez que isso seja concretizado, o aplicativo indicará que a via está congestionada.

## Diagrama de blocos
![alt text](https://github.com/viniciusAC/Estrada-Inteligente/blob/master/Doc/diagrama_de_blocos.jpeg)

## Cronograma
| Semanas                          | Objetivo                                            |
| -------------------------------- |:---------------------------------------------------:|
| **14/10 - 21/10** > Semana 1     | Planejamento e Documentação do Projeto              |
| **21/10 - 28/10** > Semana 2     | Compra dos Materiais e Estudo da Codificação        |
| **28/10 - 04/11** > Semana 3     | Teste dos Materiais e Desenvolvimento do Código     |
| **04/10 - 11/10** > Semana 4     | Inicio de montagem e testes                         |
| **11/10 - 18/10** > Semana 5     | Montagem e Ajustes                                  |
| **18/10 - 02/12** > Semana 6 e 7 | Testes, Ajustes e Entrega                           | 
