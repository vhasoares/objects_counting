# Projeto Final da disciplina de Processamento de Imagens
ICMC - USP - 1º Semestre de 2018

Aluno: Victor Hugo Andrade Soares
Nº USP: 10462418
Professor: Moacir Pontti

Tema: Aprendizado de Características

Título: Métodos eficientes para detecção e contagem de animais em imagens aéreas

Resumo: O objetivo deste projeto é utilizar métodos de aprendizado de característica para detecção e contagem eficiente de animais em imagens obtidas por VANTs.


Na pasta "images" encontram-se exemplos de imagens utilizadas neste trabalho. As imagens são de fonte própria, coletadas pessoalmente em fazendas no Mato Grosso do Sul com uso de um Drone.

A princípio estão sendo investigadas as Técnicas Índice de Vegetação ExG e CIVE para detecção e descarte de áreas da imagem com vegetação (e possivelmente sem animais).

Os testes iniciais estão sendo feitos utilizando apenas 1/4 da resolução total da imagem. Além disso, estão sendo investigados os usos do Ajuste de Gamma e Equalização de Histograma para pré-processamento das imagens, a fim de melhorar os resultados obtidos.

Para detecção dos pontos de interesse e aprendizado de característica, uma função para detecção de bordas foi implementada. Antes do aplicacção da detecção de bordas, um filtro de média 3x3 é aplicado para suavizar as transições das irregularidades na vegetação e terreno.

No notebook "Projeto Parcial - Notebook.ipynb", são mostrados e explicados os métodos utilizados até aqui e quais os métodos deverão ser implementados de agora em diante.

No documento "Exemplos Pré-Processados.pdf" estão contidos 6 exemplos de imagens após o pré-processamento e transformação acima descritos.