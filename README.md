# LLMs e Moléculas: Avaliando a Tradução de SMILES para Nomes através de Transfer Learning

Este projeto tem como objetivo ajustar um modelo de linguagem (LLM) para entender representações SMILES de moléculas químicas. O foco principal é a criação e avaliação do modelo, e todos os detalhes conceituais estão descritos no artigo associado a este projeto: [Acesse o artigo aqui](https://drive.google.com/file/d/1UAN8SeCQ7klRLOvNLqo4hFPSpDQq_JQw/view?usp=sharing).

## Estrutura do Projeto

Este repositório contém os seguintes notebooks:

1. **`1_create_tokenizer_to_extend.ipynb`**  
   Este notebook é responsável pela criação de um tokenizador para lidar com as estruturas SMILES.
2. **`2_train_and_test_smiles.ipynb`**  
   Aqui, os modelos BART e FLANT5 tem seus tokenizadores expandidos, passando também por um finetunning instruindo para traduções de SMILES para o nome das moléculas químicas. Além disso, a inferência nos dados de teste também é feita nesse notebook, salvando-as em um csv na pasta results.

3. **`3_avaliando_o_modelo.ipynb`**  
   Neste notebook, são realizadas as avaliações do modelo treinado, incluindo métricas de performance.

## Observações

- Os arquivos mais pesados, como dados de teste e os modelos, estão salvos em [https://drive.google.com/drive/folders/1EE9IpJlbNcFLaDSQkFfkrs1d1P14nX06?usp=sharing]
