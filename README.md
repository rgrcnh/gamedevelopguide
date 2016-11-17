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

* Arte:  

Compreende pensar, desenhar e produzir toda parte visual e sonorização do jogo. Além de métodos convencionais como papel e lápis para criar os esboços em conjunto com mesas digitalizadoras, existem ferramentas específicas para desenho dos modelos, como o Maya, Blender para modelagem e  outras para criação dos áudios. Outra forma de lidar com a arte, caso sua você ou sua equipe não tenha esta habilidade, é buscar em bancos públicos de "assets" as artes que combinam com o seu desenho de jogo, ou mesmo contratar alguém para executar esta parte. Usar bancos públicos de imagem ou imagens já conhecidas podem comprometer a marca visual que vai ajudar a diferenciar seu jogo da concorrência.

* Programação: 

Programação envolve usar os conhecimentos de desenvolvimento de software para auxiliar na montagem dos aspectos comportamentais que o jogo terá. As plataformas de criação de jogos, como o Unity ou o Cocos2D possuem motores de execução "engines" que limitam os tipos de linguagem de programação que poderão ser usadas. Você pode consultar na wikipedia para ver detalhes sobre quais linguagens cada plataforma suporta.

Engines, em geral, usam uma linguagem capaz de ser compilada, para tarefas mais pesadas  (em geral, C# ou C++) e outra, interpretada, conhecida como linguagem de script, para tarefas mais simples (em geral Lua). Aqui ocorrerá a programação das condições físicas de trajetória, colisão, rebatimento, rotação, travessia e outros detalhes.
Também são nas plataformas de desenvolvimento de jogos que serão importados os recursos ("assets") criados pela time de Arte, contendo os gráficos, as texturas e os sons, que serão aplicados aos objetos do jogo. 

* Produção:  

Compreende o planejamento do tempo e dos recurso para chegar ao fim do prazo com o jogo pronto (e dentro do custo). Inclui o gerenciamento, a coordenação, a cobrança de prazos e a responsabilidade por fazer a comunicação fluir entre a equipe.

Esta fase ocorre em paralelo com as demais e compreende:

  a. o planejamento do tempo, dos recursos e dos custos.
  b. a coordenação e cobrança de prazos, junto as equipes
  c. assegurar que as equipes estejam se comunicando.
  d. adaptar o planejamento, quando necessário.
  e. envolver o responsável pelo design para ajustes quando necessário.

---

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

Idealização Sobre a Arte (imagens, figuras, música, formato das fontes das letras, etc). *Atenção:* Não esqueça os direitos autorais aqui. No Brasil regra de jogo não podem ser patenteadas, mas desenhos, figuras, logos e outros detalhes podem ter direto de marcas.

Uma boa ideia aqui é pesquisar no google bases de dados com "assets" disponíveis para uso, sem pagamento de "royalties", que combinem com seus objetivos de jogo e idealização de cenários.

Os Assets formam a "biblioteca" de elementos e comportamentos do jogo, como os personagens gráficos, objetos físicos, cenários, padronagens (texturas), sons e scripts, sendo que os scripts, responsáveis por fornecer os comportamentos aos objetos, serão deixados para serem pesquisados/desenvolvidos na fase de programação.

Esta etapa inclui as fases abaixo.

- Esboço dos cenários (fundo ou skybox), para cada fase.
- Definição de luzes
- Comportamento da câmera (fixa ou acompanha o personagem principal)
- Esboço dos objetos que o jogador irá interagir (formato, desenho)
- Esboço dos personagens (formato, desenho)
- Quais são os sons usados no jogo:
 - na abertura;
 - nas fases;
 - na hora de fazer um ponto;
 - ao fracassar;
 - para chamar a atenção ao surgir um objeto;

---


## Os finalmentes:

Espero que tenha gostado deste guia (:+1:). Apesar de simples, que tenha servido ao menos para despertar sua atenção para a organização necessária no desenvolvimento de um jogo, desde a ideia até a concretização. Não pare por aqui, para saber mais sobre o assunto, recomendo ler a referência abaixo.

The Art of Game Design: A Book of Lenses, Second Edition 2nd Edition. Autor: Jesse Schell
Disponível na [Amazon](https://www.amazon.com/gp/product/1466598646/ref=as_li_tl?ie=UTF8&camp=1789&creative=390957&creativeASIN=1466598646&linkCode=as2&tag=wwwlifebinder-20&linkId=TVQMXFVTZUVJB3MH) ou em outras lojas.  

---

![Joy](https://gist.githubusercontent.com/rgrcnh/60af13a2b0ac37d0872542288049d0f6/raw/e7c318469ada9d6808ca455765134a55e03e646e/joy.png)

Rogério "rgrcnh" Cunha