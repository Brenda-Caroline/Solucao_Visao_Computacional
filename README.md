# Solucao_Visao_Computacional
Códigos referentes a solução proposta para a disciplina de Visão Computacional.

Os códigos foram feitos no google colab. Consistem em 3 arquivos: um arquivo para realizar a segmentação do PlusMe com o SAM2; um arquivo para realizar a sobreposição das imagens com predições de estimativa de pose e imagens com predição de segmentação; e um arquivo para realizar a análise e avaliação das heurísticas propostas.

Foram disponibilizados os arquivos nas extensões .py e .ipynb

Para este trabalho, não foi treinado nenhum modelo. Utilizou-se modelos pré-treinados para a realização deste.

Para a estimativa de pose, utilizou-se o modelo de pose extra-large do yolo11. A ultralytics tem um GitHub onde disponibiliza seu conteúdo: https://github.com/ultralytics/ultralytics. 
No link possui os modelos da ultralytics: https://github.com/ultralytics/ultralytics/tree/main/ultralytics/models e nesse link está disponível os arquivos .yaml de cada tarefa do yolo11. 
Além disso, no site da ultralytics: https://docs.ultralytics.com/pt/tasks/pose/#models possui os modelo em pytorch (extensão .py) com os pesos do modelo para baixar.

Para a segmentação com SAM2 utilizando o ultralytics, também é possível baixar o arquivo pytorch com os pesos dos modelos pré-treinados: https://docs.ultralytics.com/models/sam-2/#how-to-use-sam-2-versatility-in-image-and-video-segmentation
