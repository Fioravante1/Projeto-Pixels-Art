<h1 align="center">
    <img alt="Trybe" src="https://github.com/Fioravante1/Project-Lessons-Learned/blob/Fioravante-Chiozzi-lessons-learned/trybe-logo.png">
</h1>


<h1 align="center">Projeto Pixels Art</h1> 

<p align=center>
<a href="https://www.linkedin.com/in/fioravantechiozzi/" target="blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/linkedin.svg" alt="Fioravante" height="20" width="20" /></a>
<a href="https://github.com/Fioravante1/" target="blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/github.svg" alt="Fioravante" height="20" width="20" /></a>
 </p>

_"A Trybe é uma escola do futuro para qualquer pessoa que queira melhorar de vida e construir uma carreira de sucesso em tecnologia, onde a pessoa só paga quando conseguir um bom trabalho."_

O programa conta com mais de 1.500 horas de aulas presenciais e online e aborda introdução ao desenvolvimento de software, front-end, back-end, ciência da computação, engenharia de software, metodologias ágeis e habilidades comportamentais.

---

## Requisitos Obrigatórios:

* Neste projeto, você implementará um editor de arte com pixels.

**Ou seja, dada uma paleta de cores e um quadro composto por pixels, você vai permitir que quem usa consiga pintar o que quiser no quadro!** 👩‍🎨

### 1 - Adicione à página o título "Paleta de Cores".

- O título deverá ficar dentro de uma tag `h1` com o `id` denominado `title`;

- O texto do título deve ser **exatamente** "Paleta de Cores".

**O que será verificado:**

- Verifica se contém um elemento `h1` com o id `title` com o título correto

### 2 - Adicione à página uma paleta de quatro cores distintas.

- A paleta de cores deve ser um elemento com `id` denominado `color-palette`, ao passo que cada cor individual da paleta de cores deve possuir a `classe` `color`;

- A cor de fundo de cada elemento da paleta deverá ser a cor que o elemento representa. **A única cor não permitida na paleta é a cor branca.**;

- Cada elemento da paleta de cores deverá ter uma borda preta, sólida e com 1 pixel de largura;

- A paleta de cores deverá listar todas as cores disponíveis para utilização lado a lado, e deverá ser posicionada abaixo do título "Paleta de Cores";

- A paleta de cores não deve conter cores repetidas.

**O que será verificado:**

- A paleta de cores deve ser um elemento com `id` denominado `color-palette`

- Verifica se cada cor individual da paleta de cores possui a `classe` chamada `color`.

- Verifica se a cor de fundo de cada elemento da paleta é a cor que o elemento representa. **A única cor não permitida na paleta é a cor branca.**

- Verifica se cada elemento da paleta de cores tem uma borda preta, sólida e com 1 pixel de largura;

- Verifica se a paleta lista todas as cores disponíveis para utilização, lado a lado.

- Verifica se a paleta de cores está posicionada abaixo do título \'Paleta de Cores\'

- Verifica se a paleta de cores não contém cores repetidas.

### 3 - Adicione a cor **preta** como a primeira cor da paleta de cores.

**O que será verificado:**

- Verifica se a primeira cor da paleta é preta

- Verifica se as demais cores podem ser escolhidas livremente.

### 4 - Adicione à página um quadro de pixels, com 25 pixels.

- O quadro de "pixels" deve ter 5 elementos de largura e 5 elementos de comprimento;

- O quadro de "pixels" deve possuir o `id` denominado `pixel-board`, ao passo que cada "pixel" individual dentro do quadro deve possuir a `classe` denominada `pixel`;

- A cor inicial dos "pixels" dentro do quadro, ao abrir a página, deve ser branca;

-  O quadro de "pixels" deve aparecer abaixo da paleta de cores.

**O que será verificado:**

- Verifica se o quadro de pixels possui o `id` denominado `pixel-board`

- Verifica se cada pixel individual dentro do quadro possui a `classe` denominada `pixel`.

- Verifica se a cor inicial dos pixels dentro do quadro, ao abrir a página, é branca.

- Verifica se o quadro de pixels aparece abaixo da paleta de cores

### 5 - Faça com que cada elemento do quadro de pixels possua 40 pixels de largura, 40 pixels de altura e seja delimitado por uma borda preta de 1 pixel.

**O que será verificado:**

- Verifica se o quadro de pixels tem altura e comprimento de 5 elementos

- Verifica se 40 pixels é o tamanho total do elemento, incluindo seu conteúdo e excluindo a borda preta, que deve ser criada à parte.

### 6 - Defina a cor preta como cor inicial. Ao carregar a página, a cor preta já deve estar selecionada para pintar os pixels

- O elemento da cor preta deve possuir, inicialmente, a `classe` `selected`;

- Note que o elemento que deverá receber a classe `selected` deve ser um dos elementos que possuem a classe `color`, como especificado no **requisito 2**.

**O que será verificado:**

- Verifica se o elemento da cor preta possui, inicialmente, a `classe` `selected`

- Verifica se nenhuma outra cor da paleta tem a `classe` `selected`

### 7 - Clicar em uma das cores da paleta faz com que ela seja selecionada e utilizada para preencher os pixels no quadro.

- A `classe` `selected` deve ser adicionada à cor selecionada na paleta, ao mesmo tempo em que é removida da cor anteriormente selecionada;

- Somente uma das cores da paleta deve ter a `classe` `selected` de cada vez;

- Note que os elementos que deverão receber a classe `selected` devem ser os mesmos elementos que possuem a classe `color`, como especificado no **requisito 2**.

**O que será verificado:**

- Verifica se somente uma cor da paleta de cores tem a classe `selected` de cada vez

- Verifica se os pixels dentro do quadro não têm a classe `selected` quando são clicados

### 8 - Clicar em um pixel dentro do quadro após selecionar uma cor na paleta faz com que o pixel seja preenchido com a cor selecionada.

**O que será verificado:**

- Verifica se ao carregar a página deve ser possível pintar os pixels de preto

- Verifica se após selecionar uma outra cor na paleta, é possível pintar os pixels com essa cor

- Verifica se somente o pixel que foi clicado foi preenchido com a cor selecionada, sem influenciar na cor dos demais pixels.

### 9 - Crie um botão que, ao ser clicado, limpa o quadro preenchendo a cor de todos seus pixels com branco.

**O que será verificado:**

- Verifica se o botão tem o `id` denominado `clear-board`

- Verifica se o botão está posicionado entre a paleta de cores e o quadro de pixels

- Verifica se o texto do botão é \'Limpar\'

- Verifica se ao clicar no botão, o quadro de pixels é totalmente preenchido de branco

## Requisitos Bônus:

### 10 - Faça o quadro de pixels ter seu tamanho definido pela pessoa usuária.

- Crie um input e um botão que permitam definir um quadro de pixels com tamanho entre 5 e 50. Ao clicar no botão, deve ser gerado um quadro de **N** pixels de largura e **N** pixels de altura, onde **N** é o número inserido no input;

 - Ou seja, se o valor passado para o input for 7, ao clicar no botão, vai ser gerado um quadro de 49 pixels (7 pixels de largura x 7 pixels de altura);

- O input deve ter o `id` denominado `board-size` e o botão deve ter o `id` denominado `generate-board`;

- O input só deve aceitar número maiores que zero. Essa restrição **deve** ser feita usando os atributos do elemento `input`;

- O botão deve conter o texto "VQV";

- O input deve estar posicionado entre a paleta de cores e o quadro de pixels;

- O botão deve estar posicionado ao lado do input;

- Se nenhum valor for colocado no input ao clicar no botão, mostre um `alert` com o texto: "Board inválido!";

- O novo quadro deve ter todos os pixels preenchidos com a cor branca.

**O que será verificado:**

- Verifica se existe um input com o id `board-size`

- Verifica se existe um botão com o id `generate-board`

- Verifica se o input só aceita número maiores que zero. Essa restrição deve ser feita usando os atributos do elemento `input`

- Verifica se o botão contém o texto \'VQV\'

- Verifica se o input está posicionado entre a paleta de cores e o quadro de pixels

- Verifica se o botão está posicionado ao lado do input

- Verifica se nenhum valor for colocado no input ao clicar no botão, um `alert` é exibido com o texto: \'Board inválido!\'

- Verifica se ao clicar no botão com um valor preenchido, o tamanho do board muda.

- Verifica se o novo quadro tem todos os pixels preenchidos com a cor branca

### 11 - Limite o tamanho mínimo e máximo do board.

- Caso o valor digitado no input `board-sze` fuja do intervalo de 5 a 50, faça:

  - Valor menor que 5, considerar 5 como padrão;

  - Valor maior que 50, considerar 50 como padrão.

**O que será verificado:**

- Verifica se a altura máxima do board é 50

- Verifica se a altura do board é 5 quando um valor menor é colocado no input

- Verifica se a altura do board é 50 quando um valor maior é colocado no input

### 12 - Faça com que as cores da paleta sejam geradas aleatoriamente ao carregar a página.

- A cor preta ainda precisa estar presente e deve ser a primeira na sua paleta de cores.

**O que será verificado:**

- Verifica se as cores geradas na paleta são diferentes a cada carregamento da página

- Verifica se a cor preta ainda está presente e é a primeira na sua paleta de cores

---

## Depois de terminar o desenvolvimento

Para **"entregar"** seu projeto, siga os passos a seguir:

* Vá até a página **DO SEU** _Pull Request_, adicione a label de _"code-review"_ e marque seus colegas
  * No menu à direita, clique no _link_ **"Labels"** e escolha a _label_ **code-review**
  * No menu à direita, clique no _link_ **"Assignees"** e escolha **o seu usuário**
  * No menu à direita, clique no _link_ **"Reviewers"** e digite `students`, selecione o time `tryber/students-sd-010-b`

Se ainda houver alguma dúvida sobre como entregar seu projeto, [aqui tem um video explicativo](https://vimeo.com/362189205).

⚠ Lembre-se de garantir que todas as _issues_ comentadas pelo **Lint** estão resolvidas! ⚠

---

### Revisando um pull request

À medida que você e as outras pessoas que estudam na Trybe forem entregando os projetos, vocês receberão um alerta via Slack para também fazer a revisão dos Pull Requests das outras pessoas estudantes. Atenção às mensagens do "Pull Reminders" no Slack!

Use o material que você já viu sobre [Code Review](https://course.betrybe.com/real-life-engineer/code-review/) para te ajudar a revisar os projetos que chegaram para você.

# Avisos Finais

Ao finalizar e submeter o projeto, não se esqueça de avaliar sua experiência preenchendo o formulário. Leva menos de 3 minutos!

Link: [FORMULÁRIO DE AVALIAÇÃO DE PROJETO](https://bit.ly/3ta7hA0)

O avaliador automático não necessariamente avalia seu projeto na ordem em que os requisitos aparecem no readme. Isso acontece para deixar o processo de avaliação mais rápido. Então, não se assuste se isso acontecer, ok?

---
