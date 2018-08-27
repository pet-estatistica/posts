# Posts do Site PET #

Este repositório tem por objetivo facilitar a elaboração, revisão,
armazenamento e versionamento das matérias a serem escritas para o [site
do PET-Estatística].

As matérias são publicadas toda semana e os temas compreendem assuntos
diversos sobre Estatística, Academia, Programação e Computação. As
matérias estão disponíveis no endereço pet-estatistica.github.io/site/

## Fluxo de trabalho ##

A elaboração dos *posts* é realizada individualmente, conforme rodízio
definido em reunião. Para aprovação e posterior publicação da matéria
será necessária revisão, de um membro do grupo, também definido conforme
rodízio.

A rodada de publicações está definida, com as respectivas datas, na
tabela abaixo.

| Autor                          | Entrega Para Revisão | Revisor                        |   Status   |
|--------------------------------|----------------------|--------------------------------|------------|
|  Lineu Alberto C. de Freitas   |        05/09         |  Jhenifer Caetano Veloso       | issue #02  |
|  Jhenifer Caetano Veloso       |        12/09         |  Nilton da Silva Reis Filho    | issue #03  |
|  Nilton da Silva Reis Filho    |        19/09         |  Altamiro Antonio Basiewics    | issue #04  |
|  Altamiro Antonio Basiewics    |        26/09         |  William Henrique de P. Ramos  | issue #05  |
|  William Henrique de P. Ramos  |        03/10         |  Augusto Buzzoni Calcanhoto    | issue #06  |
|  Augusto Buzzoni Calcanhoto    |        10/10         |  Jayme Gomes dos Santos Junior | issue #07  |
|  Jayme Gomes dos Santos Junior |        17/10         |  Walmes Marques Zeviani        | issue #08  |
|  Walmes Marques Zeviani        |        24/10         |  Willian Meira Schlichta       | issue #09  |
|  Willian Meira Schlichta       |        31/10         |  Vinicius César Pedroso        | issue #10  |
|  Vinicius César Pedroso        |        07/11         |  Nívea da Silva Zamaro         | issue #11  |
|  Nívea da Silva Zamaro         |        14/11         |  Lineu Alberto C. de Freitas   | issue #12  |

Sugere-se que as modificações, tanto para elaboração quanto para a
revisão, sejam realizadas utilizando o versionamento Git, ou seja, que
considere mais de um *commit* par cada matéria. Ainda para um melhor
aproveitamento da interface do Github, cada matéria programada para
publicação deverá ter um *issue* que a representa. Este *issue* será
atribuído ao respectivo autor, que após a finalizar a matéria deve
*issue* comunicar o revisor, em um comentário no *issue* que por sua vez
fará as suas contribuições também em forma de comentário. Assim neste
projeto a *issue* servirá como meio de comunicação entre o revisor e o
autor. Após publicação no site o *issue* deve ser fechado.

O armazenamento dos posts no repositório seguirá a definição de um
arquivo por matéria, nomeado da seguinte forma `post-?.Rmd`, onde `?`
representa o contador do *issue* que representa aquela matéria. Assim
cada post terá seu desenvolvimento centrado neste arquivo. Ainda se
forem utilizada figures, elas devem ser armazenadas no diretório
`./figures/`.

Diferentemente dos outros projetos do PET, este repositório terá seu
desenvolvimento somente no ramo principal (*branch master*). A
referenciação das *issues* pode (e é aconselhável) que seja feita nas
mensagem de *commit*. Um exemplo de mensagem de commit que referencia um
*issue* (e.g. *issue#0*) é:

```bash
git commit -m "Incorpora as sugestões da revisão na matéria #0"
```

[site do PET-Estatística]: https://pet-estatistica.github.io/site/
