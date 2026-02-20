# Otimização Logística: Estratégia de Hubs em Curitiba/PR 🚚📍

## 📝 Descrição do Projeto
Este projeto nasceu da necessidade de identificar locais estratégicos para a instalação de Hubs Logísticos em Curitiba. O objetivo é reduzir o tempo de entrega (Last Mile) e otimizar a distribuição de mercadorias com base em dados demográficos reais.

## 🚀 O que eu fiz:
1. **Coleta de Dados**: Extração de dados populacionais do Censo 2022 (IBGE) por setores censitários.
2. **Tratamento de Dados (Python)**: Limpeza e filtragem dos dados utilizando a biblioteca Pandas.
3. **Machine Learning**: Aplicação do algoritmo **K-Means** para agrupar os setores censitários e encontrar os "centros de massa" (centroides), que representam os locais ideais para os hubs.
4. **Análise Espacial (QGIS)**: 
   - Geoprocessamento dos pontos gerados.
   - Criação de áreas de influência (Buffers).
   - Cruzamento com o sistema viário para validar o acesso às rodovias.

🛠️ **Tecnologias Utilizadas**

**Linguagem:** Python (Bibliotecas: GeoPandas, Shapely, Pandas, Scikit-Learn, Matplotlib).
**GIS:**: QGIS 3.4
**Dados:** IBGE (Setores Censitários), IPPUC (Sistema Viário Urbano) e DER-PR (Sistema Rodoviário).

## 📊 Resultado Final
Abaixo, a visualização cartográfica dos hubs estratégicos e sua abrangência sobre a malha urbana de Curitiba:

![Mapa Final](hubs_logisticos.png)

---
*Projeto desenvolvido por Leonardo Gabriel Rischter. Conecte-se comigo no https://www.linkedin.com/in/leonardo-rischter/.*






