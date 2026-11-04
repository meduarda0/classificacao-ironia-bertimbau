# Classificação de Ironia em Notícias com BERTimbau

Projeto de Processamento de Linguagem Natural (PLN) desenvolvido para identificar automaticamente a presença de ironia em notícias, utilizando o modelo pré-treinado BERTimbau.

## Objetivo

Desenvolver um modelo de classificação binária capaz de identificar notícias que contêm ironia e notícias que não apresentam esse recurso linguístico.

## Tecnologias e ferramentas

- Python
- PyTorch
- Hugging Face Transformers
- BERTimbau (`neuralmind/bert-base-portuguese-cased`)
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- Google Colab

## Metodologia

1. Carregamento dos conjuntos de treinamento e teste.
2. Preparação e combinação dos textos disponíveis.
3. Divisão dos dados de treinamento em conjuntos de treino e validação.
4. Tokenização dos textos utilizando o tokenizer do BERTimbau.
5. Ajuste fino (*fine-tuning*) do modelo pré-treinado para classificação binária.
6. Avaliação do modelo utilizando a métrica de acurácia.
7. Geração de previsões e criação do arquivo de submissão para a competição.

## Resultados na competição

Participação em uma competição de classificação de ironia em notícias na plataforma Kaggle.

- **Colocação:** 4º lugar
- **Acurácia:** 0,92420 (92,42%)
- **Plataforma:** Kaggle

A competição possui acesso privado. Por esse motivo, os arquivos de dados utilizados foram incluídos neste repositório para permitir que outras pessoas possam executar e analisar o projeto.

## Estrutura do repositório

- `classificacao_ironia_bertimbau.ipynb`: notebook com o código de desenvolvimento e treinamento do modelo.
- `train.jsonl`: conjunto de dados de treinamento.
- `test.csv`: conjunto de dados utilizado para gerar as previsões.
- `sample_submission.csv`: modelo de arquivo para submissão das previsões.

## Como executar

1. Acesse o repositório e baixe os arquivos do projeto.
2. Abra o notebook no Google Colab.
3. Faça o upload dos arquivos `train.jsonl`, `test.csv` e `sample_submission.csv` para o ambiente do Colab.
4. Execute as células do notebook em ordem.
5. Ao final, o arquivo `submission.csv` será gerado com as previsões do modelo.

## Objetivo acadêmico

Projeto desenvolvido no contexto de estudos em Inteligência Artificial, com aplicação de técnicas de Processamento de Linguagem Natural e aprendizado de máquina para classificação de textos em português.
