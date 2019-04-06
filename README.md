Lista 2 - Ordenação
=========================
Welison Lucas Almeida Regis - 2019.1

Lieverton Santos Silva - 2019.1

## PROPOSTA

- Utilizou-se os algoritmos quadráticos **`insertion sort`, `selection sort`, `bubble sort` e `shell sort` aplicados em um `dataset`** (arquivo "data.csv") do jogo FIFA 19.
- O arquivo **`csv`** proposto possui o registro de **18208 jogadores descritos por 89 atributos**. Para o dado problema, utilizou-se todos os registros dos jogadores filtrando os campos de interesse — ID (não sequencial), nome, foto do jogador, nacionalidade, nome do clube e logo do clube.
- O objetivo do atual `notebook` é utilizar os algoritmos de ordenação para **separar os jogadores por clubes (literais)** e, ao final, **gerar um jogador aleatório e apresentar todo o elenco do clube ao qual pertence o atleta**.
- É representado também a **comparação gráfica (histograma) dos algoritmos de ordenação** com a lista totalmente desordenada, assim como também é apresentado o desempenho dos mesmos algoritmos caso estejam passando em uma lista já ordenada.
- Ao final, é **apresentada a logo do clube e todos os jogadores que compõem o elenco com suas respectivas fotos e descrições**.

## PRÉ-REQUISITO(S)
O projeto utiliza variável de ambiente (env) para a devida execução. Portanto:

1. Acesse o site da [Anaconda](https://www.anaconda.com/distribution/), baixe a versão mais recente do _software_ e instale.


## ACESSO À APLICAÇÃO
Para testar a aplicação, execute os seguintes passos:
1. Faça uma cópia do repositório para o seu computador em um lugar de sua preferência.
	* Através do _git_, faça um _git clone_:

```
    $ git clone https://github.com/EDAII/Lista2_WelisonRegis_LievertonSilva
```

2. Entre na pasta do projeto:
```
    $ cd Lista2_WelisonRegis_LievertonSilva
```

3. Crie o ambiente com os pré-requisitos do projeto através do conda:
```
    $ conda create --name sort_algorithms --file requirements.txt python=3.7
```

4. Ative o ambiente:
```
    $ conda activate sort_algorithms
```

5. Abra o projeto com o jupyter notebook:
```
    $ jupyter notebook lista2_sort_algorithms.ipynb
```

**Observação:** caso queira desativar o ambiente, digite `conda deactivate`; já se quiser remover o ambiente criado anteriormente, digite `conda env remove -n sort_algorithms`.

## FUNCIONAMENTO
Com o notebook aberto, execute uma célula por vez:

```
    shift + ENTER
``` 
