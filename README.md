# Power BI - Adventure Works Sales Refactor

Este repositório tem como **intuito o estudo e prática de Business Intelligence com Power BI**.  
O projeto consiste em **remodelar o painel Adventure Works**, disponibilizado pela Microsoft como dataset para estudo, criar novos insights e explorar como o design e a modelagem de dados podem transformar a análise de negócios.

O Adventure Works é uma empresa fictícia de venda de bicicletas esportivas e produtos relacionados.  

---

## 🎯 Objetivos do Projeto
- **Praticar modelagem de dados** e criação de medidas DAX no Power BI.  
- **Refatorar o painel original**, aplicando boas práticas de design e visualização.  
- **Estudar sobre criação de temas para PBI** criando um tema em JSON totalmente personalizado.

---

## 📈 Comparativo: Antes e Depois

### 🔹 Painel Original
O painel inicial apresentava uma visão limitada, com poucos indicadores e foco restrito nas vendas mensais.  
A análise era mais superficial, sem segmentações geográficas ou comparativos de desempenho entre períodos.

![Painel original](../adventureworks-sales-refactor/Reports/dashpadrao.png)

---

### 🔹 Painel Refatorado
O novo painel oferece uma **visão executiva completa**, com mais métricas e análises detalhadas por tempo, região e categoria.  
Inclui comparativos **ano a ano**, **mapas interativos**, **ranking de produtos** e **indicadores de performance** que facilitam a tomada de decisão.

![Painel original](../adventureworks-sales-refactor/Reports/dasheditado.png)

---

## 🎨 Criação de Tema Personalizado
Além da refatoração dos visuais e medidas, desenvolvi um novo tema para o dashboard.
Esse tema foi construído diretamente em JSON, permitindo controlar cores, estilos de linhas, fontes e padrões visuais de forma centralizada.

### 🔎 Benefícios
Padronização: facilita a criação de novos dashboards, já que todos seguem o mesmo estilo visual.

Consistência: garante que relatórios diferentes mantenham identidade visual única.

Eficiência: reduz tempo de configuração manual de cada visual, pois o estilo já está definido no tema.

Exploração técnica: foi muito interessante pesquisar como alterar os visuais diretamente no JSON, entendendo a estrutura e possibilidades de personalização avançada do Power BI.

Segue abaixo trecho do meu tema:
```
{
    "name": "Adventure Sales",
    "dataColors": [
        "#011638",
        "#364156",
        "#cdcdcd",
        "#dff8eb",
        "#214e34",
        "#973131"
    ]
}
```
Tema completo pode ser visto [aqui](https://github.com/Felisouza/adventureworks-sales-refactor/blob/main/tema.json)

---

## 🚀 Resultados Obtidos
- **Melhoria na clareza visual e na estrutura analítica** do relatório.  
- **Aumento da capacidade de interpretação dos dados**, com filtros e segmentações intuitivas.  
- **Criação de novas medidas DAX** que ampliaram a visão sobre o desempenho anual, trimestral e mensal.  
- **Análises geográficas e por categoria**, permitindo identificar regiões e produtos com maior impacto nas vendas.  
- **Identificação dos campeões de venda**, trazendo visibilidade estratégica para o negócio.