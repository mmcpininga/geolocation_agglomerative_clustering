# geolocation_agglomerative_clustering
Geolocation Clustering using the Agglomerative Algorithm

O problema consiste em agrupar os dados (coordenadas de latitude e longitude) com base na sua geolocalização e respeitando as restrições.

Restrição: 

1) Distância máxima de 1.6km entre os pontos e seu centróide.

A figura abaixo mostra os pontos em azul antes do agrupamento com o algoritmo aglomerativo.

![image](https://user-images.githubusercontent.com/18504119/120047713-9e5c4900-bfeb-11eb-8fc3-3af8911081b7.png)

A figura abaixo demonstra o resultado dos clusters com cores diferentes e centróides com um marcador preto. 
Utilizando o algoritmo aglomerativo, o problema foi resolvido já que foi respeitada a restrição da distância de 1.6km entre os pontos e o centróide.

![image](https://user-images.githubusercontent.com/18504119/120856300-049a1c00-c556-11eb-8c12-1540e2ba40ea.png)


Installation:
pip install folium

