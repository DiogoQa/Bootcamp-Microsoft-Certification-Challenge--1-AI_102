# Desafios de Código: Associando Conceitos de IA com Lógica de Programação.
---

<img src="img/code.png" referrerpolicy="same-origin" style="display: block; object-fit: cover; border-radius: 0px; width: 100%; height: 30vh; opacity: 1; object-position: center 50%;">

## Sobre

Este repositório contém uma série de desafios de código focados em conceitos de IA com Lógica de Programação:

---
<a name="indice"></a>
## Índice

1. [Desafio 1 - Associando os Conceitos de IA](#desafio-1)
2. [Desafio 2 - Associando os Benefícios da IA no Azure](#desafio-2)
3. [Desafio 3 - Associando os Serviços de IA do Azure](#desafio-3)

---

# Desafio 1
<a name="desafio-1"></a>

# Associando os Conceitos de IA

## Descrição
Para fortalecer seus conhecimentos, complete o código deste desafio, associando os conceitos de IA com suas respectivas definições. Não se preocupe com a linguagem de programação, com o tempo você vai perceber que ela é apenas um detalhe. Portanto, aproveite esse momento para sair da sua zona de conforto e conhecer uma das linguagens suportadas pela IA.

## Entrada
A entrada consistirá no conceito de IA para o qual você deve retornar a descrição. Nesse contexto, os seguintes conceitos são considerados válidos para este desafio de código:
- "aprendizado supervisionado"
- "aprendizado não supervisionado"
- "redes neurais"
- "processamento de linguagem natural"

## Saída
A saída esperada é a descrição associada ao conceito fornecido como entrada. Seguem as saídas possíveis:
- "análise e geração de linguagem humana"
- "sistemas inspirados no cérebro humano para processamento de dados"
- "descoberta de padrões em dados não rotulados"
- "treinamento de modelos com dados rotulados"

## Exemplos
A tabela abaixo apresenta exemplos com alguns dados de entrada e suas respectivas saídas esperadas. Certifique-se de testar seu programa com esses exemplos e com outros casos possíveis.

| Entrada | Saída |
|---------|--------|
| aprendizado supervisionado | treinamento de modelos com dados rotulados |
| aprendizado não supervisionado | descoberta de padrões em dados não rotulados |
| redes neurais | sistemas inspirados no cérebro humano para processamento de dados |
| processamento de linguagem natural | análise e geração de linguagem humana |

```python
def descrever_conceito(conceito):
    if conceito == "aprendizado supervisionado":
        return "treinamento de modelos com dados rotulados"
    elif conceito == "aprendizado não supervisionado":
        return "descoberta de padrões em dados não rotulados"
    elif conceito == "aprendizado por reforço":
        return "aprendizado baseado em recompensas e punições"
    elif conceito == "redes neurais":
        return "sistemas inspirados no cérebro humano para processamento de dados"
    elif conceito == "processamento de linguagem natural":
        return "análise e geração de linguagem humana"
 
entrada = input()
print(descrever_conceito(entrada))
```

[Voltar ao Índice](#indice)

# Desafio 2
<a name="desafio-2"></a>

# Associando os Benefícios da IA no Azure

## Descrição
Neste desafio, você deve associar as vantagens da Inteligência Artificial no Azure com suas respectivas definições. Cada vantagem possui uma descrição específica que você precisará identificar e retornar de acordo com a entrada fornecida. O objetivo é reforçar sua familiaridade com os principais benefícios da IA no Azure, independentemente da linguagem de programação escolhida.

## Entrada
A entrada consistirá na vantagem da IA no Azure para a qual você deve retornar a descrição. Nesse contexto, as seguintes vantagens são consideradas válidas para este desafio de código:
- "análise preditiva"
- "processamento de linguagem natural"
- "automação"
- "personalização"

## Saída
A saída esperada é a descrição associada à vantagem fornecida como entrada. Seguem as saídas possíveis:
- "automatização de tarefas repetitivas e processos"
- "oferecer experiências personalizadas aos usuários"
- "habilidade de entender e gerar linguagem humana"
- "capacidade de prever tendências e comportamentos futuros"

## Exemplos
A tabela abaixo apresenta exemplos com alguns dados de entrada e suas respectivas saídas esperadas. Certifique-se de testar seu programa com esses exemplos e com outros casos possíveis.

| Entrada | Saída |
|---------|--------|
| análise preditiva | capacidade de prever tendências e comportamentos futuros |
| processamento de linguagem natural | habilidade de entender e gerar linguagem humana |
| automação | automatização de tarefas repetitivas e processos |
| personalização | oferecer experiências personalizadas aos usuários |

```python
def descrever_vantagem(vantagem):
    if vantagem == "análise preditiva":
        return "capacidade de prever tendências e comportamentos futuros"
    elif vantagem == "processamento de linguagem natural":
        return "habilidade de entender e gerar linguagem humana"
    elif vantagem == "automação":
        return "automatização de tarefas repetitivas e processos"
    elif vantagem == "personalização":
        return "oferecer experiências personalizadas aos usuários"

entrada = input()
print(descrever_vantagem(entrada))
```

[Voltar ao Índice](#indice)

# Desafio 3
<a name="desafio-3"></a>

# Associando os Serviços de IA do Azure

## Descrição
Neste desafio, seu objetivo é associar corretamente os serviços de Inteligência Artificial do Azure com suas descrições específicas. Cada serviço oferece uma funcionalidade distinta, e sua tarefa será identificar o serviço correspondente à descrição fornecida na entrada. Este desafio foi criado para aprimorar seus conhecimentos sobre os recursos de IA do Azure, sem focar em uma linguagem de programação específica.

**Saiba mais em:** Serviços de IA do Azure

## Entrada
A entrada consistirá no serviço de IA no Azure para o qual você deve retornar a descrição. Nesse contexto, os seguintes serviços são considerados válidos para este desafio de código:
- "Azure Machine Learning"
- "Azure OpenAI Service"
- "Azure AI Vision"
- "Azure Bot Services"

## Saída
A saída esperada é a descrição associada ao serviço fornecido como entrada. Seguem as saídas possíveis:
- "análise e interpretação de imagens e vídeos"
- "criação e gerenciamento de bots inteligentes"
- "plataforma para construir, treinar e implantar modelos de ml"
- "integração de modelos avançados de linguagem da OpenAI"

## Exemplos
A tabela abaixo apresenta exemplos com alguns dados de entrada e suas respectivas saídas esperadas. Certifique-se de testar seu programa com esses exemplos e com outros casos possíveis.

| Entrada | Saída |
|---------|--------|
| Azure Machine Learning | plataforma para construir, treinar e implantar modelos de ml |
| Azure Bot Services | criação e gerenciamento de bots inteligentes |
| Azure OpenAI Service | integração de modelos avançados de linguagem da OpenAI |
| Azure AI Vision | análise e interpretação de imagens e vídeos |

```python
def descrever_servico(servico):
    if servico == "Azure Cognitive Services":
        return "serviços pré-construídos para visão, fala, linguagem e tomada de decisão"
    elif servico == "Azure Machine Learning":
        return "plataforma para construir, treinar e implantar modelos de ml"
    elif servico == "Azure Bot Services":
        return "criação e gerenciamento de bots inteligentes"
    elif servico == "Azure OpenAI Service":
        return "integração de modelos avançados de linguagem da OpenAI"
    elif servico == "Azure AI Vision":
        return "análise e interpretação de imagens e vídeos"

entrada = input()
print(descrever_servico(entrada))
```

[Voltar ao Índice](#indice)
