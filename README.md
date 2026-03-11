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

  <img width="2341" height="837" alt="Captura de tela 2026-03-11 130527" src="https://github.com/user-attachments/assets/661a841f-7507-4a10-be01-39bc11523b69" />

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
