# 🐆 Trabalho 2 - Notícias de Onça (Colab)

Este repositório contém os códigos e notebooks utilizados para treinar e avaliar modelos BERT em português, aplicados em diferentes categorias de classificação de texto.

## 📂 Estrutura do Repositório
- `data_prep.py` → preparação dos dados (limpeza, divisão em treino/validação/teste).
- `train_bert.py` → treinamento do modelo BERT para uma categoria específica.
- `evaluate_bert.py` → avaliação do modelo treinado com métricas e exemplos de erros.
- `IA2.ipynb` → notebook principal para execução no Google Colab.

## 🚀 Como abrir no Google Colab
Você pode abrir o notebook diretamente no Colab clicando no link abaixo:

[![Abrir no Colab](https://colab.research.google.com/github/HaruoArai/trabalho2-completo-ia/blob/main/IA2.ipynb)

## ⚙️ Como rodar os scripts no Colab
1. Clone este repositório dentro do Colab:
   ```python
   !git clone https://github.com/HaruoArai/trabalho2-completo-ia-colab
   ```python
   %cd trabalho2-completo-ia-colab

2. Instale as dependências necessárias:
   ```python
   !pip install torch torchvision torchaudio transformers pandas scikit-learn matplotlib

4. Execute os scripts:
   ```python
   !python data_prep.py
   ```python
   !python train_bert.py onca
   ```python
   !python evaluate_bert.py onca
   
## 📌 Categorias disponíveis
- onca → análise de sentimentos (Negativo, Neutro, Positivo).
- caseiro → análise de sentimentos (Negativo, Neutro, Positivo).
- fakenews → classificação binária (Não, Sim).

