# Posts do Site PET #



Este repositório tem por objetivo facilitar a elaboração, revisão,

armazenamento e versionamento das matérias a serem escritas para o [site

do PET-Estatística].



As matérias são publicadas, preferencialmente, nas terças e

sextas-feiras de toda semana e os temas compreendem assuntos diversos

sobre Estatística, Academia, Programação e Computação. As matérias estão

disponíveis no endereço www.pet.est.ufpr.br.



## Fluxo de trabalho ##



A elaboração dos *posts* é realizada individualmente, conforme rodízio

definido em reunião. Para aprovação e posterior publicação da matéria

serão necessárias duas revisões. A primeira revisão será de

responsabilidade do revisor, também definido conforme rodízio e a

segunda é feita em grupo no dia programado para publicação.



A rodada de publicações está definida, com as respectivas datas, na

tabela abaixo. É recomendável que o autor da matéria a disponibilize

para o revisor ao menos 48 horas antes da data de publicação, tendo

assim tempo hábil para incorporação de sugestões e eventuais correções.



|  Autor   | Entrega Para Revisão | Revisor  |   Status   |
|:--------:|:--------------------:|:--------:|:----------:|
|  Lineu   |        21/08         | Jhenifer | issue #95  |
| Jhenifer |        28/08         |  Nilton  | issue #96  |
|  Nilton  |        04/09         | Altamiro | issue #97  |
| Altamiro |        11/09         | William  | issue #98  |
| William  |        18/09         | Augusto  | issue #99  |
| Augusto  |        25/09         |  Jayme   | issue #100 |
|  Jayme   |        09/10         |  Walmes  | issue #101 |
|  Walmes  |        16/10         | William2 | issue #102 |
| William2 |        23/10         | Vinicius | issue #103 |
| Vinicius |        30/10         |  Nivea   | issue #104 |
|  Nivea   |        06/11         |  Lineu   | issue #105 |



Sugere-se que as modificações, tanto para elaboração quanto para a

revisão, sejam realizadas utilizando o versionamento Git, ou seja, que

considere mais de um *commit* par cada matéria. Ainda para um melhor

aproveitamento da interface do GitLab, cada matéria programada para

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



[site do PET-Estatística]: https://pet-estatistica.github.io/
