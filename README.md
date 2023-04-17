# MODERNIST 

## **Resumo**

Colocar o resumo aqui.

## **Diretórios**

Relação e descrição dos principais diretórios do cohebert:
* **dataset** - Diretório com os conjuntos de dados.
* **notebooks** - Diretório com o notebooks dos experimentos.
* **projecao** - Diretório com os arquivos de projeções.

## **Instalação**

**Requisitos**

* Python 3.6.9
* [Transformer Huggingface 4.5.1](https://huggingface.co/transformers/)
* [PyTorch 1.8.1](https://pytorch.org/)
* [Spacy 3.7.13](https://spacy.io/)

**Download - Clone**

```
!git clone https://github.com/dev-leandrodias/MODERNIST.git
```

## 1. Dataset

A pasta **"dataset"** contêm os arquivos dos conjuntos de dados utilizados.

## 2. Notebooks

A pasta **"notebooks"** contêm os arquivos dos notebooks utilizados em nossos experimentos. Os arquivos estão divididos para cada conjuntos de dados e seu idioma.

## 3. Projeções de Embeddings

Projeções de *embeddings* sentenças e palavras gerados pelo **BERT** tamanho **large** utilizando a ferramenta **Embedding Projector** (https://projector.tensorflow.org/).

Os arquivos utilizados pelo projetor estão na pasta **"projecao"** e divididos em três pastas: **"sentenca"** e **"token"**. As pastas indicam se foi utilizado *embeddings* consolidados das **sentenças**, *embeddings* de **tokens** ou combinados. 
Cada pasta **"sentenca"** e **"token"** ,  possui os arquivos para os conjuntos de dados. As projeções ocorrem para as palavras e sentenças das obras.


### 3.1 Projeções dos *embeddings* de sentenças

Projeções dos *embeddings* das sentenças consolidados pela média dos *embeddings* dos tokens. Os *embeddings* dos tokens são das 4 últimas camadas do **BERTimbau Large** em português ou **BERT Large** em inglês e concatenados.

As projeções dos *embeddings* de sentenças estão relacionados com os seguintes **metadados**:


### 3.2 Projeções dos *embeddings* de palavras
Projeções de *embeddings* das palavras consolidados pela média dos *embeddings* dos tokens para as palavras que estão fora do vocabulário do modelo. Os *embeddings* dos tokens são recuperados das 4 últimas camadas do **BERTimbau Large** em português ou **BERT Large** em inglês e concatenados.

As projeções dos *embeddings* de palavras podem se relacionar com os seguintes **metadados**:



## Referências

**BERTimbau** : Souza, F., Nogueira, R., Lotufo, R., 2020. Bertimbau: Pretrained bert models for brazilian portuguese, in: Brazilian Conference on Intelligent Systems, Springer. Springer, Rio Grande, Brazil. pp. 403–417. https://link.springer.com/chapter/10.1007/978-3-030-61377-8_28

**Embedding Projector** : Smilkov, D., Thorat, N., Nicholson, C., Reif, E., Vi ́egas, F.B., Wattenberg, M., 2016. Embedding projector: Interactive visualization and interpretation of embeddings. arXiv preprint arXiv:1611.05469. https://arxiv.org/pdf/1611.05469.pdf

## Citando & Autores

Se achar este repositório útil, sinta-se à vontade para citar nossa [publicação](https://repositorio.ufsc.br/handle/123456789/243399):

```bibtex 
@misc{dias-2022-MODERNIST,
    title = "Mineração de padrões morfo-semânticos em textos literários com o BERT",
    author = "DIAS, Leandro da Silveira",    
    location = {Online},
    year = {2022},
    pages = {56},
    address = {Florianopolis, SC, Brasil},
    school = {Universidade Federal de Santa Catarina},
    url = {https://repositorio.ufsc.br/handle/123456789/243399}        
}
```
