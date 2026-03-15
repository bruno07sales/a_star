#  Rastreador de Rotas Inteligente com OSMnx
Comparação de Algoritmos de Caminho Mínimo (Dijkstra vs A*)

Produzido em **Python** para cálculo e visualização de rotas em mapas reais utilizando dados do **OpenStreetMap**.
Foi pensado para permitir simular elementos de trânsito, que seja possivel também: editar o mapa e comparar Dijkstra e A*.


##  Funcionalidades

* Cálculo de rotas em mapas reais
* Comparação entre **Dijkstra** e **A***
* Visualização gráfica do mapa
* Animação da busca dos algoritmos
* Simulação de elementos de trânsito:

## Dá para dicionar/editar:
  * 🚦 Semáforos
  * 🏔 Lombadas
  * 🏎 Alteração de velocidade em trechos
  * Salvar edição de mapa

##  O que foi ultilizado 

O sistema utiliza dois algoritmos clássicos de busca em grafos:

* **Dijkstra** – encontra o caminho mínimo explorando o grafo de forma completa.
* **A*** – utiliza uma heurística baseada na distância até o destino para acelerar a busca.

## Tecnologias

* Python
* OSMnx
* NetworkX
* Matplotlib
* Tkinter
