# Visualização dos Embeddings da Obra As Vítimas-Algozes, de Joaquim Manuel de Macedo

Visualização dos embeddings das janelas de sentenças na Obra As Vítimas-Algozes, de Joaquim Manuel de Macedo geradas pelo BERTimbau utilizando o Embedding Projector.
https://projector.tensorflow.org/

## O que são janelas

A janela é um fragmento de uma sentenças onde o centro desta janela é composto por uma palavras alvo.

> **Sentença:**
>
> E o negro feiticeiro é um perigo real de todos os dias .
>
> **Janelas de tamanho 5**
>
> E o **__negro__** feiticeiro é	

## Projeções dos embeddings das janelas
Projeções dos embeddings das janelas consolidados pela média dos embeddings dos tokens. Os embeddings dos tokens são das última camadas do BERTimbau Large em português.

### As projeções dos embeddings de sentenças estão relacionados com os seguintes metadados:

- id	(Id da sentença) 
    -  Ex:  id: **1, 2, 3**
- Janela	(Fragmento da sentença) 
    -  Ex:  Janela: **E o **__negro__** feiticeiro é	**
- Sentence	(Sentença) 
    -  Ex:  Sentence: **E o negro feiticeiro é um perigo real de todos os dias .**
- tamanho da janela	(Número de tokens das janelas)
    -  Ex:  tamanho da janela: **3, 5, 7**
- Palavra alvo	(Palavra central da janela)
    -  Ex:  Palavra alvo: **negro, negra, negros, negras**
- Classe (Grupo da palavra alvo)
  -  Ex: Classe **negro** se refere às palavras: **negro, negra, negros, negras**

## Links das visualizações 
>### Visualizações de janelas com palavra central **"negro"**:
>- [Visualização de todas as janelas de tamanhao 3 ate 19](https://projector.tensorflow.org/?config=https://raw.githubusercontent.com/dev-leandrodias/BERTimbautv1visualizacao/main/config/1-alvo/all.json)
>- [Visualização da janela de tamanho 3](https://projector.tensorflow.org/?config=https://raw.githubusercontent.com/dev-leandrodias/BERTimbautv1visualizacao/main/config/1-alvo/janela-3.json)
>- [Visualização da janela de tamanho 5](https://projector.tensorflow.org/?config=https://raw.githubusercontent.com/dev-leandrodias/BERTimbautv1visualizacao/main/config/1-alvo/janela-5.json)
>- [Visualização da janela de tamanho 7](https://projector.tensorflow.org/?config=https://raw.githubusercontent.com/dev-leandrodias/BERTimbautv1visualizacao/main/config/1-alvo/janela-7.json)
>- [Visualização da janela de tamanho 9](https://projector.tensorflow.org/?config=https://raw.githubusercontent.com/dev-leandrodias/BERTimbautv1visualizacao/main/config/1-alvo/janela-9.json)
>- [Visualização da janela de tamanho 11](https://projector.tensorflow.org/?config=https://raw.githubusercontent.com/dev-leandrodias/BERTimbautv1visualizacao/main/config/1-alvo/janela-11.json)
>- [Visualização da janela de tamanho 13](https://projector.tensorflow.org/?config=https://raw.githubusercontent.com/dev-leandrodias/BERTimbautv1visualizacao/main/config/1-alvo/janela-13.json)
>- [Visualização da janela de tamanho 15](https://projector.tensorflow.org/?config=https://raw.githubusercontent.com/dev-leandrodias/BERTimbautv1visualizacao/main/config/1-alvo/janela-15.json)
>- [Visualização da janela de tamanho 17](https://projector.tensorflow.org/?config=https://raw.githubusercontent.com/dev-leandrodias/BERTimbautv1visualizacao/main/config/1-alvo/janela-17.json)
>- [Visualização da janela de tamanho 19](https://projector.tensorflow.org/?config=https://raw.githubusercontent.com/dev-leandrodias/BERTimbautv1visualizacao/main/config/1-alvo/janela-19.json)
>
>### Visualizações de janelas com palavra central **"negro"** e **"escravo"**:
>- [Visualização de todas as janelas de tamanhao 3 ate 19](https://projector.tensorflow.org/?config=https://raw.githubusercontent.com/dev-leandrodias/BERTimbautv1visualizacao/main/config/2-alvo/all.json)
>- [Visualização da janela de tamanho 3](https://projector.tensorflow.org/?config=https://raw.githubusercontent.com/dev-leandrodias/BERTimbautv1visualizacao/main/config/2-alvo/janela-3.json)
>- [Visualização da janela de tamanho 5](https://projector.tensorflow.org/?config=https://raw.githubusercontent.com/dev-leandrodias/BERTimbautv1visualizacao/main/config/2-alvo/janela-5.json)
>- [Visualização da janela de tamanho 7](https://projector.tensorflow.org/?config=https://raw.githubusercontent.com/dev-leandrodias/BERTimbautv1visualizacao/main/config/2-alvo/janela-7.json)
>- [Visualização da janela de tamanho 9](https://projector.tensorflow.org/?config=https://raw.githubusercontent.com/dev-leandrodias/BERTimbautv1visualizacao/main/config/2-alvo/janela-9.json)
>- [Visualização da janela de tamanho 11](https://projector.tensorflow.org/?config=https://raw.githubusercontent.com/dev-leandrodias/BERTimbautv1visualizacao/main/config/2-alvo/janela-11.json)
>- [Visualização da janela de tamanho 13](https://projector.tensorflow.org/?config=https://raw.githubusercontent.com/dev-leandrodias/BERTimbautv1visualizacao/main/config/2-alvo/janela-13.json)
>- [Visualização da janela de tamanho 15](https://projector.tensorflow.org/?config=https://raw.githubusercontent.com/dev-leandrodias/BERTimbautv1visualizacao/main/config/2-alvo/janela-15.json)
>- [Visualização da janela de tamanho 17](https://projector.tensorflow.org/?config=https://raw.githubusercontent.com/dev-leandrodias/BERTimbautv1visualizacao/main/config/2-alvo/janela-17.json)
>- [Visualização da janela de tamanho 19](https://projector.tensorflow.org/?config=https://raw.githubusercontent.com/dev-leandrodias/BERTimbautv1visualizacao/main/config/2-alvo/janela-19.json)
>
>### Visualizações de janelas com palavra central **"negro"**, **"crioulo"** e **"escravo"**:
>- [Visualização de todas as janelas de tamanhao 3 ate 19](https://projector.tensorflow.org/?config=https://raw.githubusercontent.com/dev-leandrodias/BERTimbautv1visualizacao/main/config/3-alvo/all.json)
>- [Visualização da janela de tamanho 3](https://projector.tensorflow.org/?config=https://raw.githubusercontent.com/dev-leandrodias/BERTimbautv1visualizacao/main/config/3-alvo/janela-3.json)
>- [Visualização da janela de tamanho 5](https://projector.tensorflow.org/?config=https://raw.githubusercontent.com/dev-leandrodias/BERTimbautv1visualizacao/main/config/3-alvo/janela-5.json)
>- [Visualização da janela de tamanho 7](https://projector.tensorflow.org/?config=https://raw.githubusercontent.com/dev-leandrodias/BERTimbautv1visualizacao/main/config/3-alvo/janela-7.json)
>- [Visualização da janela de tamanho 9](https://projector.tensorflow.org/?config=https://raw.githubusercontent.com/dev-leandrodias/BERTimbautv1visualizacao/main/config/3-alvo/janela-9.json)
>- [Visualização da janela de tamanho 11](https://projector.tensorflow.org/?config=https://raw.githubusercontent.com/dev-leandrodias/BERTimbautv1visualizacao/main/config/3-alvo/janela-11.json)
>- [Visualização da janela de tamanho 13](https://projector.tensorflow.org/?config=https://raw.githubusercontent.com/dev-leandrodias/BERTimbautv1visualizacao/main/config/3-alvo/janela-13.json)
>- [Visualização da janela de tamanho 15](https://projector.tensorflow.org/?config=https://raw.githubusercontent.com/dev-leandrodias/BERTimbautv1visualizacao/main/config/3-alvo/janela-15.json)
>- [Visualização da janela de tamanho 17](https://projector.tensorflow.org/?config=https://raw.githubusercontent.com/dev-leandrodias/BERTimbautv1visualizacao/main/config/3-alvo/janela-17.json)
>- [Visualização da janela de tamanho 19](https://projector.tensorflow.org/?config=https://raw.githubusercontent.com/dev-leandrodias/BERTimbautv1visualizacao/main/config/3-alvo/janela-19.json)
>
>### Visualizações de janelas com palavra central **"negro(a)"**, **"crioulo(a)"**, **"escravo(a)"**, **"criado(a)"**, **"escravo(a)"**, **"senhor(a)"**, **"branco(a)"**:
<!-- >- [Visualização de todas as janelas de tamanhao 3 ate 19](https://projector.tensorflow.org/?config=https://raw.githubusercontent.com/dev-leandrodias/BERTimbautv1visualizacao/main/config/3-alvo/all.json) -->
>- [Visualização da janela de tamanho 3](https://projector.tensorflow.org/?config=https://raw.githubusercontent.com/dev-leandrodias/BERTimbautv1visualizacao/main/config/14-alvo/janela-3.json)
>- [Visualização da janela de tamanho 5](https://projector.tensorflow.org/?config=https://raw.githubusercontent.com/dev-leandrodias/BERTimbautv1visualizacao/main/config/14-alvo/janela-5.json)
>- [Visualização da janela de tamanho 7](https://projector.tensorflow.org/?config=https://raw.githubusercontent.com/dev-leandrodias/BERTimbautv1visualizacao/main/config/14-alvo/janela-7.json)
>- [Visualização da janela de tamanho 9](https://projector.tensorflow.org/?config=https://raw.githubusercontent.com/dev-leandrodias/BERTimbautv1visualizacao/main/config/14-alvo/janela-9.json)
>- [Visualização da janela de tamanho 11](https://projector.tensorflow.org/?config=https://raw.githubusercontent.com/dev-leandrodias/BERTimbautv1visualizacao/main/config/14-alvo/janela-11.json)
>- [Visualização da janela de tamanho 13](https://projector.tensorflow.org/?config=https://raw.githubusercontent.com/dev-leandrodias/BERTimbautv1visualizacao/main/config/14-alvo/janela-13.json)
>- [Visualização da janela de tamanho 15](https://projector.tensorflow.org/?config=https://raw.githubusercontent.com/dev-leandrodias/BERTimbautv1visualizacao/main/config/14-alvo/janela-15.json)
>- [Visualização da janela de tamanho 17](https://projector.tensorflow.org/?config=https://raw.githubusercontent.com/dev-leandrodias/BERTimbautv1visualizacao/main/config/14-alvo/janela-17.json)
>- [Visualização da janela de tamanho 19](https://projector.tensorflow.org/?config=https://raw.githubusercontent.com/dev-leandrodias/BERTimbautv1visualizacao/main/config/14-alvo/janela-19.json)

<!-- **Link** para o Embedding Projector com pooling através do arquivo config_pool.json:
<https://projector.tensorflow.org/?config=https://raw.githubusercontent.com/dev-leandrodias/BERTimbautv1visualizacao/config/1-alvo.json> -->



# Visualização dos Embeddings das sentenças das Obras 
- A Escrava Isaura, de Bernardo Guimarães, publicado em 1875 
- As Vítimas-Algozes, de Joaquim Manuel de Macedo, publicado em 1869
- Memórias Póstumas de Brás Cubas, de Machado de Assis, publicado em 1880
- O Cortiço, de Aluíso Azevedo, publicado em 1890
- Úrsula, de Maria Firmina, publicado em 1859



## Projeções dos embeddings das sentenças
Projeções dos embeddings das janelas consolidados pela média dos embeddings dos tokens. Os embeddings dos tokens são das última camadas do BERTimbau Large em português.

### As projeções dos embeddings de sentenças estão relacionados com os seguintes metadados:

- id (Id da sentença)
    -  Ex:  id: **1, 2, 3**
- Sentença (Sentença)
    -  Ex:  Sentence: **E o negro feiticeiro é um perigo real de todos os dias .**
- Posição da palavra alvo ( é a possição que se encontra a palavra alvo dentro da sentença)
    -  Ex:  Posição da palavra alvo: **3, 5, 7**
- Palavra alvo (palavra alvo)
    - Ex: Palavra alvo: **negro, negra, negros, negras**
- Classe (Grupo da palavra alvo)
    - Ex: Classe **negro** se refere às palavras: **negro, negra, negros, negras**
- Obra (Nome da Obra literaria)
    - Ex: Obra: **A Escrava Isaura**
- Autor (Nome do autor)
    - Ex: Autor: **Maria Firmina**
- Ano (Ano de publicação)
    - Ex: Ano: **1869**
- Movimento (Movimento literario da obra)
    - Ex: Movimento: **Realismo**
- tamanho sentença (numero de palavras e/ou simbolos da sentena.)
    - Ex: tamanho sentença: **35**


>### Visualizações de sentrenças com palavra: **negro**, **negros**, **negrinho**, **negrinhos**, **negra**, **negras**,**negrinha**, **negrinhas**, **crioulo**, **crioulos**, **crioulinho**, **crioulinhos**, **crioula**, **crioulas**, **crioulinha**, **crioulinhas**, **mulato**, **mulatos**, **mulatinho**, **mulatinhos**, **mulata**, **mulatas**,**mulatinha**, **mulatinhas**, **criado**, **criados**, **criadinho**, **criadinhos**, **criada**, **criadas**, **criadinha**, **criadinhas**, **escravo**, **escravos**, **escravinho**, **escravinhos**, **escrava**, **escravas**, **escravinha**, **escravinhas**, **senhora**, **senhor**,**branco**, **branca**

## Geração dos arquivos
>- [Visualização das sentrenças](https://projector.tensorflow.org/?config=https://raw.githubusercontent.com/dev-leandrodias/BERTimbautv1visualizacao/main/config/todos-as-obras/all.json)


## Projeções dos embeddings das janelas

Projeções dos embeddings das janelas consolidados pela média dos embeddings dos tokens. Os embeddings dos tokens são das última camadas do BERTimbau Large em português.

### As projeções dos embeddings de sentenças estão relacionados com os seguintes metadados

- id (Id da sentença)
  - Ex:  id: **1, 2, 3**
- Sentença (Sentença)
  - Ex:  Sentence: **E o negro feiticeiro é um perigo real de todos os dias .**
- Janela (Fragmento da sentença)
  - Ex:  Janela: **E o *negro* feiticeiro é**
- Posição da palavra alvo ( é a possição que se encontra a palavra alvo dentro da sentença)
  - Ex:  Posição da palavra alvo: **3, 5, 7**
- Palavra alvo (palavra alvo)
  - Ex: Palavra alvo: **negro, negra, negros, negras**
- Classe (Grupo da palavra alvo)
  - Ex: Classe **negro** se refere às palavras: **negro, negra, negros, negras**
- Obra (Nome da Obra literaria)
  - Ex: Obra: **A Escrava Isaura**
- Autor (Nome do autor)
  - Ex: Autor: **Maria Firmina**
- Ano (Ano de publicação)
  - Ex: Ano: **1869**
- Movimento (Movimento literario da obra)
  - Ex: Movimento: **Realismo**
- tamanho janela (numero de palavras e/ou simbolos da janela.)
  - Ex: tamanho janela: **7**

>### Visualizações de sentrenças com palavra: **negro**, **negros**, **negrinho**, **negrinhos**, **negra**, **negras**,**negrinha**, **negrinhas**, **crioulo**, **crioulos**, **crioulinho**, **crioulinhos**, **crioula**, **crioulas**, **crioulinha**, **crioulinhas**, **mulato**, **mulatos**, **mulatinho**, **mulatinhos**, **mulata**, **mulatas**,**mulatinha**, **mulatinhas**, **criado**, **criados**, **criadinho**, **criadinhos**, **criada**, **criadas**, **criadinha**, **criadinhas**, **escravo**, **escravos**, **escravinho**, **escravinhos**, **escrava**, **escravas**, **escravinha**, **escravinhas**, **senhora**, **senhor**,**branco**, **branca**

## Geração dos arquivos
>
>- [Visualização da janelas tamanho 7](https://projector.tensorflow.org/?config=https://raw.githubusercontent.com/dev-leandrodias/BERTimbautv1visualizacao/main/config/todos-as-obras-janela-7/janelas-7.json)



Os arquivos utilizados pelo Embedding Projector foram gerados pelo notebook: https://github.com/dev-leandrodias/BERTimbautv1visualizacao/blob/main/ExemplosVisualizacaoEmbeddingBERT_pt_br.ipynb.


## Referências

**BERTimbau** : Souza, F., Nogueira, R., Lotufo, R., 2020. Bertimbau: Pretrained bert models for brazilian portuguese, in: Brazilian Conference on Intelligent Systems, Springer. Springer, Rio Grande, Brazil. pp. 403–417. https://link.springer.com/chapter/10.1007/978-3-030-61377-8_28

**Embedding Projector** : Smilkov, D., Thorat, N., Nicholson, C., Reif, E., Vi ́egas, F.B., Wattenberg, M., 2016. Embedding projector: Interactive visualization and interpretation of embeddings. arXiv preprint arXiv:1611.05469. https://arxiv.org/pdf/1611.05469.pdf
