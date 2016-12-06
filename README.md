# Guia Rápido para Desenvolvimento de Jogos

keywords: Game Designer, Game Developer, Projeto de Jogos

Desenvolver um jogo é parecido com o ato de produzir um filme ou uma animação, o que está longe de ser simples, principalmente quando se deseja produzir algo que atraia a atenção das pessoas. Jogos de sucesso são pensados (desenhados) em como reter o jogador, como provocar a ânsia em jogar, de percorrer as fases, de descobrir os segredos do jogo e dominá-lo, de ter momentos de abstração completa do entorno, quando o tempo avança numa velocidade ímpar.

Para ampliar as chances de sucesso do seu jogo, antes de mais nada, é bom que haja uma organização mínima dentro da sua ideia. Isto passa por desempenhar ao menos os papeis descritos abaixo. Este é o objetivo deste documento: apresentar os papeis necessários a serem desempenhados para melhor transportar sua ideia original para um jogo que atinja um mínimo de alcance pelo seu público-alvo. 

Os papeis abaixo não esgotam todas as atividades existentes em equipes que desenvolvem jogos complexos, feitos nas grandes empresas. O foco deste documento é auxiliar pequenos grupos, que se organizam nos trabalhos escolares ou entre amigos, ou mesmo para pessoas que pensam em desenvolver sozinhas os seus jogos. De fato, ainda que o jogo seja feito apenas por uma pessoa (indie), é bom que esta pessoa pense nestes papéis, "trocando o boné" quando necessário.

## Fases para desenvolver um jogo:

* Design: 

O design liga o mundo das ideias e da criatividade com algo passível de ser criado. Todo jogo de sucesso tem um design que procurou aplicar receitas para cativar o seu público. Cativar o público significa que ele manterá o interesse no jogo. Para isto, o jogo precisa apresentar algum desafio. No design, as ideias e definições do jogo são colocadas no papel, de modo divulgar os princípios dos jogos e também recolher ideias da sua equipe. 

Isso aí. Documentar é chato, mas, especialmente quando estiver trabalhando com uma equipe, documentar o jogo é a forma de permitir que todos da equipe conhecerão o jogo que está sendo desenvolvido (o escopo), evitando que cada um siga um caminho diferente ou que introduza/retire aspectos que não são amplamente conhecidos. 

A principal regra do design, na minha opinião, é manter o desenho do seu jogo tão simples quanto a sua capacidade de produzí-lo. Ideias complexas, jogos com muitas fases ou que contenham muitos recursos visuais podem requerer mais esforço (tempo e dinheiro) que a equipe possui para produzí-lo.

Mas cuidado! Não confunda Game Design com Game Development. Game Design é uma atividade do Game Development, tal qual a arte, programação etc. E tem mais: Game Design pode ser praticado por qualquer componente da equipe, ao contribuir com ideias, o que é comum, pois ao longo do desenvolvimento é esperado que ideias sejam aprimoradas ou renovadas. Game Design é mais uma função que uma pessoa. 

* Arte:  

Compreende pensar, desenhar e produzir toda parte visual e sonorização do jogo. Além de métodos convencionais como papel e lápis para criar os esboços em conjunto com mesas digitalizadoras, existem ferramentas específicas para desenho dos modelos, como o [Maya](http://www.autodesk.com.br/products/maya/overview), [Blender](https://www.blender.org/) para modelagem e  outras para criação dos áudios. Outra forma de lidar com a arte, caso sua você ou sua equipe não tenha esta habilidade, é buscar em bancos públicos de artes digitais que combinem com o seu desenho de jogo, ou mesmo contratar alguém para executar esta parte. Usar bancos públicos de imagem ou imagens já conhecidas podem comprometer a marca visual que vai ajudar a diferenciar seu jogo da concorrência.

* Programação: 

Programação envolve usar os conhecimentos de desenvolvimento de software para auxiliar na montagem dos aspectos comportamentais que o jogo terá. As plataformas de criação de jogos, como o Unity ou o Cocos2D possuem motores de execução "engines" que limitam os tipos de linguagem de programação que poderão ser usadas. Você pode consultar na [Wikipedia](https://en.wikipedia.org/wiki/Game_engine) para ver detalhes sobre quais linguagens cada plataforma suporta.

Engines, em geral, usam uma linguagem capaz de ser compilada, para tarefas mais pesadas  (em geral, C# ou C++) e outra, interpretada, conhecida como linguagem `script`, para tarefas mais simples (em geral Lua). Aqui ocorrerá a programação das condições físicas de trajetória, colisão, rebatimento, rotação, travessia e outros detalhes que envolvem o comportamento dos objetos.

Também são nas plataformas de desenvolvimento de jogos que serão importados os recursos visuais e sonoros  criados pela time de Arte, contendo os gráficos, as texturas e os sons, que serão aplicados aos objetos do jogo. 

* Produção:  

Compreende o planejamento do tempo e dos recurso para chegar ao fim do prazo com o jogo pronto (e dentro do custo). Inclui o gerenciamento, a coordenação, a cobrança de prazos e a responsabilidade por fazer a comunicação fluir entre a equipe.

Esta fase ocorre em paralelo com as demais e compreende:

  a. o planejamento do tempo, dos recursos e dos custos.
  b. a coordenação e cobrança de prazos, junto as equipes
  c. assegurar que as equipes estejam se comunicando.
  d. adaptar o planejamento, quando necessário.
  e. envolver o responsável pelo design para ajustes quando necessário.

___

# Detalhando as etapas

Abaixo seguem algumas sugestões para serem pensada especificamente para o design e a arte. A parte de programação e produção não estão detalhadas por pertencerem a área já bem exploradas por outras áreas do conhecimento.

## 1. Fase do Design

### A - Definições Gerais:
- Nome do Jogo;
- Objetivo (o que o jogo vai fazer);
- Objetivo das fases, se houver;
- Plataforma;
- Qual é a audiência do seu jogo (idade, cultura, diversão ou trabalho, etc)

### B - Sobre as regras

#### B.1 - gameplay:

- Quais são as regras gerais do jogo?
- Como ele começa?
- Como o jogo é ganho?
- Como ele é pontuado?
- Como ele é perdido?
- Quais são as fases.

#### B.2 - regras do mundo onde ocorre (física do jogo)?
- como o jogador interage com os objetos?
- como os objetos de comportam? são fixos? colidem?
- como funciona a pontuação?
- O que pode acontecer no jogo e o que não pode?
- Como o jogador vai aprender as regras do jogo? Enquanto joga ou por um manual? Aparecerão instruções na tela?


### C - Sobre o Balanço do Jogo:

- Níveis de dificuldade na medida que o jogo avança?
- O que o jogo faz para manter o balanço entre dificuldade e habilidade (balanço)?
- O jogo oferece vidas, energia ou algo renovável para o usuário?
- Níveis de experiência, capacidade, vidas que devem ser acumuladas?
- Níveis aumentam dificuldade pelo ganho de habilidade ou por chance menos favoráveis (ou ambos)?
- Como o jogador vai aprender as regras do jogo? Enquanto joga ou por um manual? Aparecerão instruções na tela?
- Para aumentar as habilidades o jogador deve encontrar ferramentas, poderes ao longo do jogo?
- O jogador saberá usar as novas habilidades, capacidades, ferramentas?

### D - Contando a estória do jogo
- Existirá uma estória para contextualizar o jogador?
- Ela será contada por uma narrativa inicial, ou o jogador irá interagir com os objetos para descobrir a estória?
- A estória depende do caminho que o personagem percorre? (múltiplas estórias)

## 2 - Arte

Dentro dos aspectos abordados por quem cumprir o papel da arte, estão as ilustrações conceituais, o storyboard, a prototipagem da arte, a arte final (production artwork) e a arte com fins promocionais. As ilustrações conceituais servem para auxiliar no "Game Design", pois vão ilustrar aspectos fundamentais do jogo, em esboços. O storyboard tem o mesmo papel das ilustrações conceituais, mas serve para denotar ações e movimentos, ou seja, desenrolares temporais do jogo. A prototipagem serve para gerar arte já em formato digital que possa ser usada pela equipe de produção e programação no desenvolvimento da lógica, a prototipagem tem formatos simples e rápidos de serem produzidos, e que serão substituídos pela arte final no decorrer do desenvolvimento.

Idealização da Arte Final compreende as imagens, figuras, músicas, fontes das letras e todos os aspectos estéticos, no formato final.  *Atenção:* Não esqueça os direitos autorais aqui. No Brasil regra de jogo não podem ser patenteadas, mas desenhos, figuras, logos e outros detalhes podem ter direto de marcas.

Uma boa para quem tem pouco tempo ou habilidade com a arte, é pesquisar bases de dados com "assets" <sup id="b1">[1](#f1)</sup> disponíveis para uso na Internet, com ou sem pagamento de "royalties", que combinem com seus objetivos de jogo e idealização de cenários. Alguns engines, como o Unity, já trazem uma biblioteca razoável para prototipagem.


Esta etapa inclui as fases abaixo.

- Esboços conceituais
- Storyboard
- Prototipagem da arte, para dar início ao desenvolvimento.
- Arte Final, contendo:
 - Cenários (fundo ou skybox), para cada fase.
 - Definição de luzes
 - Comportamento da câmera (fixa ou acompanha o personagem principal)
 - Objetos que o jogador irá interagir (formato, desenho)
 - Personagens (formato, desenho)
 - Quais são os sons usados no jogo:
  - na abertura;
  - nas fases;
  - na hora de fazer um ponto;
  - ao fracassar;
  - para chamar a atenção ao surgir um objeto;
  - etc
- Arte para fins de marketing
___

## Os finalmentes:

Espero que tenha gostado deste guia (:+1:). Apesar de simples, que tenha servido ao menos para despertar sua atenção para a organização necessária no desenvolvimento de um jogo, desde a ideia até a concretização. Não pare por aqui, para saber mais sobre o assunto, recomendo começar pela Internet ou consultar as referências do texto.

___

## Glossário e Notas

<b id="f1">1</b> *Assets*: formam a "biblioteca" de elementos e comportamentos do jogo, como os personagens gráficos, objetos físicos, cenários, padronagens (texturas), sons e scripts, sendo que os scripts, responsáveis por fornecer os comportamentos aos objetos, serão deixados para serem pesquisados/desenvolvidos na fase de programação. [↩](#b1)
___

## Refências:

The Art of Game Design: A Book of Lenses, Second Edition 2nd Edition. Autor: Jesse Schell
Disponível na [Amazon](https://www.amazon.com/gp/product/1466598646/ref=as_li_tl?ie=UTF8&camp=1789&creative=390957&creativeASIN=1466598646&linkCode=as2&tag=wwwlifebinder-20&linkId=TVQMXFVTZUVJB3MH) ou em outras lojas. 
___

[Joy](https://github.com/rgrcnh/gamedevelopguide/blob/master/pics/joy.png)

Rogério "rgrcnh" Cunha