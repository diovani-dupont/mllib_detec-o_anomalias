**MLlib na detecção de anomalias**

Neste estudo, utilizamos o MLlib, uma biblioteca de aprendizado de máquina do Apache Spark, para analisar as temperaturas de um grupo de cidades ao redor do mundo. Aplicamos o algoritmo k-means, um método popular de clusterização, para agrupar as cidades com base em seus padrões de temperatura e detectar possíveis anomalias.

O algoritmo k-means foi escolhido por sua eficiência e capacidade de identificar padrões nos dados de temperatura, agrupando cidades com características semelhantes em clusters. Ao analisar os clusters formados, pudemos identificar três tipos principais de anomalias: pontuais, contextuais e de cluster.

As anomalias pontuais são temperaturas individuais que se desviam significativamente das médias do cluster a que pertencem. As anomalias contextuais ocorrem quando uma cidade apresenta um padrão de temperatura diferente do esperado em um determinado contexto ou período de tempo. Já as anomalias de cluster referem-se às cidades que não se encaixam bem em nenhum dos clusters formados, possuindo padrões de temperatura únicos ou incomuns.

A detecção dessas anomalias permitiu uma melhor compreensão dos padrões de temperatura nas diferentes cidades ao redor do mundo, além de identificar eventos ou condições incomuns que podem estar afetando essas temperaturas. Essa análise também pode ser útil para monitorar e prever fenômenos climáticos, informar políticas públicas e auxiliar na tomada de decisões relacionadas ao planejamento urbano e à gestão de recursos energéticos.

Em resumo, o uso do MLlib e do algoritmo k-means neste estudo proporcionou uma análise valiosa das temperaturas de um grupo de cidades ao redor do mundo, identificando anomalias e revelando informações sobre os padrões de temperatura e eventos climáticos incomuns.

![image](https://user-images.githubusercontent.com/109030838/230744774-96f19347-3a74-4703-8f51-15630b975fa9.png)
