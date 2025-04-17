
# Explorando a Análise de Texto do Azure

Usando o recurso de Análise de Texto do Azure para executar uma análise semântica no texto, extrair frases chave e ainda resumir um texto.

## 🛠 Habilidades
NLP, Azure, Endpoints...

## Configurando a Análise do Texto

Para configurar e habilitar a Análise do Texto do Azure, usei o AI Language, que possue modelos prontos para muitos casos, para a análise semântica utilizei o "Extract Information", para a extração de frases chave foi utilizado o "Extract key phrases" e, por último, utilizei o "Summarize text" para resumir um texto.

## Inputs

Utilizei a frase do laboratório para executar uma análise de sentimentos com o Azure AI Language service. O mesmo utiliza o Natural Language Processing (NLP) para extrair o sentido semântico do texto ou mesmo formular respostas em linguagem natural.

![Analise de Sentimentos](https://github.com/goncasthiago/languageStudioAzure/blob/main/img/AnalyzedSentiment_input.png?raw=true)

Outro teste feito foi utilizar o Azure AI Language para extrair frases chaves dentro de um texto

![Frases Chave](https://github.com/goncasthiago/languageStudioAzure/blob/main/img/ExtractKeyPhrases_input.png?raw=true)

Por último, continuei utilizando a ferramenta para resumir o texto e tirar alguns insights do mesmo com a funcionalidade Summarize.

![Resumo](https://github.com/goncasthiago/languageStudioAzure/blob/main/img/Summarization_input.png?raw=true)


## Outputs

Os outputs foram bem satisfatórios, principalmente levando em consideração que não foi necessário programar ou treinar nada, o modelo já está pronto e funcional para uso.

Os testes trouxeram muitas informações sobre o texto e foi bem interessante ver o quanto de coisa podemos fazer com essa funcionalidade, ainda mais, automatizando o processo com um grande volume de informações.

Segue abaixo as análises feitas pelo Azure AI Language Service:

#### Análise de Sentimentos

![s1](https://github.com/goncasthiago/languageStudioAzure/blob/main/img/AnalyzedSentiment_s1.png?raw=true)

![s2](https://github.com/goncasthiago/languageStudioAzure/blob/main/img/AnalyzedSentiment_s2.png?raw=true)

![s3](https://github.com/goncasthiago/languageStudioAzure/blob/main/img/AnalyzedSentiment_s3.png?raw=true)

![s4](https://github.com/goncasthiago/languageStudioAzure/blob/main/img/AnalyzedSentiment_s4.png?raw=true)

#### Palavras Chave

![s1](https://github.com/goncasthiago/languageStudioAzure/blob/main/img/ExtractKeyPhrases_s1.png?raw=true)

#### Resumo

![s1](https://github.com/goncasthiago/languageStudioAzure/blob/main/img/ExtractKeyPhrases_s1.png?raw=true)


## Microsoft Learn

[Analyze Text](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/06-text-analysis.html)


[Explore Speech](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/09-speech.html)


## Feedback

Se você tiver algum feedback, por favor me deixe saber por meio de thiagodebia@gmail.com


## Demonstração

Todo output pode ser revisto nos arquivos response.json e text_samples.json

