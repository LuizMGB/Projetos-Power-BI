A principal função utilizada foi:
- Transformar colunas em linhas (*unpivotting* em inglês)

Os dados em questão são sobre a quantidade de vendas de casa por região da Inglaterra. Neste caso, o objetivo é preparar os dados que não vieram num formato interessante para importar diretamente para o Power BI:
<img width="1920" height="825" alt="image" src="https://github.com/user-attachments/assets/677a7b36-5dcc-4c6b-b732-9ea56668df88" />
<img width="1920" height="1018" alt="image" src="https://github.com/user-attachments/assets/0b1bf026-a35a-403a-a01c-0faea643313e" />


Além de remover as linhas vazias superiores e promover novos cabeçalhos, é necessário transformar as colunas em linhas, ou seja, inverter a tabela, com excessão da primeira coluna "Data". Assim, é possível combinar todos os cabeçalhos da tabela original, regiões da Inglaterra, em uma única coluna "Regiões", ou "Localização" neste caso, resultando em uma tabela muito mais *clean* para o Power BI entender:
<img width="1919" height="875" alt="image" src="https://github.com/user-attachments/assets/4bd33c62-0892-4de2-8b3a-2dc525b0972c" />


O resultado final é um dashboard contendo:
- Matriz
- *Treemap*
- *Slicer* para filtrar por Ano

<img width="1406" height="790" alt="image" src="https://github.com/user-attachments/assets/94437b64-18c9-442a-9a0d-3188b7297380" />


A matriz é uma boa maneira de utilizar como filtro para o *treemap*, pois ao clicar em um dos anos, ou em mais de um utilizando *Ctrl+Click*, o gráfico mostra as vendas em todas as regiões naquele ano. O *treemap* é interessante para comparar visual e instantaneamente quantidades de vendas por regiões inglesas. Também é possível filtrar por "Localização" clicando em um ou mais dos cabeçalhos da matriz, refletindo no *treemap*. Clicando diretamente nos valores da matriz, filtra-se por "Ano" e "Localização" simultaneamente.

<img width="272" height="153" alt="image" src="https://github.com/user-attachments/assets/5f37a9a8-4a5b-4187-8a6a-b847bc06b081" /> <img width="272" height="153" alt="image" src="https://github.com/user-attachments/assets/1aa1b367-4380-4ed4-899e-7d7ebf05ebaf" /> <img width="272" height="153" alt="image" src="https://github.com/user-attachments/assets/52422bac-cf02-4e40-979e-99adc1412ef3" />

