# Marketing Mix Modeling com Google Meridian

Um projeto demonstrativo para análise e otimização de investimentos em marketing usando Google Meridian.

## Sobre o Projeto

Este projeto implementa um modelo de Marketing Mix (MMM) utilizando o Google Meridian, uma biblioteca de código aberto baseada em TensorFlow desenvolvida pelo Google para análise avançada de eficácia de marketing.

O Marketing Mix Modeling permite quantificar o impacto de diferentes canais de marketing nas vendas, calculando ROI e identificando oportunidades de otimização de orçamento.

## Funcionalidades

- Geração de dados sintéticos para canais de marketing
- Modelagem de efeitos não-lineares e saturação de mídia
- Captura de sazonalidade e tendências temporais
- Cálculo de ROI por canal de marketing
- Simulação de cenários de realocação de orçamento
- Visualização intuitiva dos resultados

## Pré-requisitos

- Python 3.7+
- TensorFlow 2.x
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Google Meridian

## Instalação

1. Clone este repositório:
```
git clone https://github.com/seu-usuario/meridian-mmm-projeto.git
cd meridian-mmm-projeto
```

2. Instale as dependências:
```
pip install numpy pandas matplotlib seaborn tensorflow
```

3. Instale o Google Meridian:
```
pip install git+https://github.com/google/meridian
```


## Fluxo de Trabalho

O projeto segue as seguintes etapas:

1. **Preparação de Dados**: Geração de dados sintéticos ou carregamento de dados reais, com canais de marketing e métricas de vendas

2. **Modelagem**: Configuração e treinamento do modelo Meridian para capturar efeitos de marketing

3. **Análise de Atribuição**: Decomposição das vendas em contribuições por canal e outros fatores

4. **Cálculo de ROI**: Determinação do retorno sobre investimento para cada canal

5. **Otimização**: Simulação de cenários de realocação de orçamento para maximizar resultados

6. **Visualização**: Geração de gráficos e insights acionáveis

## Dicas de Implementação

### Verificando a Estrutura do Meridian

A API do Meridian pode evoluir com o tempo. Para verificar a estrutura atual do pacote:

```python
import meridian
print([item for item in dir(meridian) if not item.startswith("_")])
```

### Adaptando Importações

Dependendo da versão do Meridian, você pode precisar ajustar as importações:

```python
# Exemplo de importações
import meridian
# Verifique a documentação atual para a forma correta de importar
# os componentes específicos como MediaMixModel
```

## Resultados

Os principais resultados incluem:

- Decomposição precisa das vendas por canal de marketing
- Identificação de canais com maior e menor ROI
- Recomendações de realocação de orçamento
- Projeção de impacto financeiro das otimizações

## Recursos Adicionais

- [Documentação Oficial do Google Meridian](https://github.com/google/meridian)
- [Guia de Marketing Mix Modeling](https://medium.com/google-cloud/introduction-to-marketing-mix-modeling-in-google-cloud-part-1-theory-and-concepts-72babe4c1115)
- [LightweightMMM - Alternativa ao Meridian](https://github.com/google/lightweight_mmm)


## Licença

Este projeto está licenciado sob a licença MIT - veja o arquivo LICENSE para detalhes.


*Este projeto é apenas para fins demonstrativos e educacionais. Não é um produto oficial do Google.*
