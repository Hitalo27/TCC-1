# Skilled Experience Catalogue: A Skill-Balancing Mechanism for Non-Player Characters using Reinforcement Learning

Glavin, Frank G.; Madden, Michael G. "Skilled Experience Catalogue: A Skill-Balancing Mechanism for Non-Player Characters using Reinforcement Learning", Aug - 2018. doi: https://ieeexplore.ieee.org/document/8490405

## 1. Fichamento de Conteúdo

O artigo apresenta um mecanismo inovador para ajustar a habilidade de personagens não jogáveis (NPCs) em jogos, com foco em jogos de tiro em primeira pessoa (FPS). O problema central abordado é a desproporção de habilidades entre o NPC e os oponentes humanos, o que pode afetar a experiência de jogo. Os autores, Frank G. Glavin e Michael G. Madden, propõem o Skilled Experience Catalogue (SEC), que utiliza um sistema de aprendizado por reforço para registrar políticas de aprendizado em diferentes pontos durante uma fase de treinamento. Essa abordagem permite que o NPC ajuste sua proficiência em armas de acordo com seu desempenho em tempo real, possibilitando uma experiência de jogo mais equilibrada. Os resultados demonstram que o SEC consegue igualar a performance dos NPCs contra oponentes de diversas habilidades, mostrando potencial para ser aplicado em diferentes gêneros de jogos, além de melhorar a dinâmica de jogo.

## 2. Fichamento Bibliográfico 

O objetivo deste mecanismo é aproximar o nível de habilidade de um NPC ao de um oponente em tempo real (página 1)

O NPC continua a aprender em tempo real usando aprendizado por reforço, mas sua política é ajustada, conforme necessário, carregando os marcos mais adequados para as circunstâncias atuais. (página 1)

Os marcos da linha do tempo de experiência são armazenados ao registrar a política de RL em intervalos definidos durante a fase de treinamento. (página 3)

Se o KDD entre o NPC e o oponente exceder um valor de 5... a política reverterá para o marco anterior do SEC. (página 4)

A abordagem é limitada pelo limite superior de desempenho que o NPC pode alcançar, e, portanto, o componente de aprendizado deve ser bem definido para evitar potenciais estagnações em mínimos locais durante a fase de aprendizado. (página 1)


## 3. Fichamento de Citações 

"The objective of this mechanism is to approximately match the skill level of an NPC to an opponent in real-time."

"The NPC continues to learn in real-time using reinforcement learning but its policy is adjusted, as required, by loading the most suitable milestones for the current circumstances."

"The success of our approach relies on the implicit assumption that, during the training phase, the skill-level grows monotonically as the learning time increases."

"Our application of SEC is concerned with balancing the Assault Rifle skill of a Deathmatch NPC playing against a single opponent."

"The results for SEC are very promising and show that, using a threshold mechanism and milestones from the learning timeline, we can closely match the level of five different fixed-strategy opponents."