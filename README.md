# 📊 Power BI Analyst: Relatório de Vendas

Projeto prático da **DIO** em Power BI: replicação de duas páginas do curso e criação de uma terceira página de visuais, usando o dataset do repositório [julianazanelatto/power_bi_analyst](https://github.com/julianazanelatto/power_bi_analyst).

## 📌 Sumário

- [Objetivo](#-objetivo)
- [Estrutura do repositório](#-estrutura-do-repositório)
- [Páginas do relatório](#-páginas-do-relatório)
- [Passo a passo da página 3](#-passo-a-passo-da-página-3)
- [Publicação e compartilhamento](#-publicação-e-compartilhamento)
- [Aprendizados](#-aprendizados)

## 🎯 Objetivo

Praticar a criação de visuais no Power BI: importar dados, montar páginas de relatório, configurar mapas e gráficos de pizza, ajustar dicas de ferramentas e publicar o resultado.

## 📁 Estrutura do repositório

```
├── dataset/          # dados usados no relatório
├── images/           # capturas de tela das páginas
├── relatorio.pbix    # projeto Power BI
└── README.md
```

## 🖼️ Páginas do relatório

### Página 1: _(nome da página)_
_Descreva os visuais replicados e o que mostram._

![Página 1](images/pagina-1.png)

### Página 2: _(nome da página)_
_Descreva os visuais replicados e o que mostram._

![Página 2](images/pagina-2.png)

### Página 3: Análise geográfica e de lucro (criada por mim)

| Visual | Tipo | Campos | Título do visual |
|---|---|---|---|
| 1 | Mapa | País (localização) + Soma de Sales + Unidades vendidas | Vendas e Unidades por País |
| 2 | Mapa | País (localização) + Soma de Profit | Lucro por País |
| 3 | Pizza | Segmento (legenda) + Soma de Profit (valores) | Lucro por Segmento |

![Página 3](images/pagina-3.png)

## 🛠️ Passo a passo da página 3

1. Criei uma nova página no relatório e a renomeei.
2. **Mapa 1:** arrastei `Country` para *Localização*, `Sales` para *Tamanho da bolha* e `Units Sold` para *Dicas de ferramenta*.
3. **Mapa 2:** arrastei `Country` para *Localização* e `Profit` para *Tamanho da bolha*.
4. **Pizza:** arrastei `Segment` para *Legenda* e `Profit` para *Valores*.
5. Ajustei a disposição dos visuais para ficarem alinhados e sem sobreposição.
6. Renomeei os títulos de cada visual para algo claro e direto.
7. Revisei os campos usados nas **dicas de ferramentas** para exibir apenas o que é relevante.

> ✍️ _Ajuste os nomes dos campos conforme aparecem no seu dataset._

## 🚀 Publicação e compartilhamento

- Relatório publicado no **Power BI Service**.
- Compartilhado como suplemento no **PowerPoint** (ou salvo como `.pbix` neste repositório).

🔗 Link do relatório: _(cole aqui, se aplicável)_

## 💡 Aprendizados

- Diferença entre usar um campo como *Tamanho* e como *Dica de ferramenta* nos mapas.
- Como nomes claros de visuais melhoram a leitura do relatório.
- Quando faz sentido usar pizza (poucos segmentos) em vez de barras.
- Fluxo completo: dados → visuais → publicação → compartilhamento.

## 📚 Referências

- [Repositório base do curso](https://github.com/julianazanelatto/power_bi_analyst)
- [Documentação do Power BI](https://learn.microsoft.com/pt-br/power-bi/)
