---
menu: "main"
description: "Sobre mim"
---

Olá! Sou o **Daniel Herszenhut**, mestrando em Engenharia de Transportes no [PET/COPPE/UFRJ](http://pet.coppe.ufrj.br/index.php/pt/) e assistente de pesquisa no [Projeto Acesso a Oportunidades](https://www.ipea.gov.br/acessooportunidades/sobre/). Busco entender, com a minha pesquisa, como o custo monetário das viagens impacta análises de desigualdade em termos de acesso a atividades.

Meus interesses de pesquisa se concentram principalmente no campo da Mobilidade Urbana, estando mais intimamente relacionados à Justiça nos Transportes. Acredito na importância do uso da ciência de dados para expandir a fronteira do conhecimento e participo do desenvolvimento de [pacotes de *R*]({{< ref "/projects.pt" >}}) que têm como objetivo facilitar a vida daqueles que trabalham nessas áreas.

No meu tempo livre gosto de praticar atividades ao ar livre e estudar/tocar música, especialmente instrumentos de percussão. 


```r
library("oneclust")

set.seed(42)
x <- sample(c(
  rnorm(50, sd = 0.2),
  rnorm(50, mean = 1, sd = 0.3),
  rnorm(100, mean = -1, sd = 0.25)
))

oneclust(x, 3)

## $cluster
##   [1] 3 1 3 2 1 1 1 3 2 3 2 2 3 1 1 1 1 1 2 1 1 1 1 1 2 3 2 2 1 1 1 2 1 1 1 3 1
##  [38] 1 3 1 3 2 1 1 3 2 3 2 1 1 3 3 1 2 3 3 1 1 1 1 3 3 1 1 1 1 1 3 2 2 2 2 2 1
##  [75] 1 2 3 2 1 2 1 3 2 3 1 2 3 1 3 1 1 2 1 1 2 3 3 1 2 3 2 3 1 1 2 1 3 1 1 1 1
## [112] 3 1 1 1 1 1 3 1 2 2 1 1 2 1 1 2 2 2 1 2 1 2 1 3 2 2 1 3 3 2 2 2 1 1 3 1 1
## [149] 3 1 2 3 2 3 1 3 1 2 1 1 2 3 1 2 2 3 2 1 1 3 3 1 1 1 1 3 1 3 1 3 1 2 3 2 1
## [186] 3 1 1 1 1 1 1 1 1 1 2 3 3 1 1
## 
## $cut
## [1]   1 101 152
```
