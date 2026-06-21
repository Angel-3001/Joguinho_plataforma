**Autora:** Angel Andrade Carmo e Lima Sales.

**Instituição:** Ilum Escola de Ciência, Centro Nacional de Pesquisa em Energia e Materiais (CNPEM).

# Joguinho de plataforma

#### Como executar o código
1. Instale o Pygame, digitando no Karnel:
   pip install pygame
2. Baixe o arquivo "jogo_plataforma.ipynb" e "pixel enemy.png" e certifique-se de que eles estão na mesma pasta.
3. Então execute todo o código do notebook baixado.

### Descrição do projeto
Projeto realizado para a matéria de Prática em Ciência de Dados (PCD), lecionada pelos professores Leandro Nascimento Lemos, Daniel Roberto Cassar e James Moraes de Almeida. Foi orientado que um projeto individual fosse desenvolvido, com o objetivo de se desafiar e mostrar o que foi aprendido durante essa matéria. Então foi inicialmente pensado em fazer um jogo didático que usa-se dos conceitos de matemática e ciências no geral, porém, depois de realizar um planejamento prévio, acreditou-se ser melhor um jogo mais simples, com o objetivo de aprender novos conceitos e treinar aquilo que já foi aprendido. Com isso, o projeto desenvolvido foi um jogo de plataforma, com código organizado inteiramente com estrutura de classes e utilizando pygame.

### Introdução
Inicialmente foi pensado em fazer um jogo de RPG baseado em alguma das disciplinas, focado em didática e melhor concepção dos conteúdos, porém, como tive que aprender PyGame do zero, achei melhor fazer algo mais simples, então fiz dois tutoriais do próprio site, criando, primeiro, um jogo de carros, extremamente simples, e depois fazendo um jogo de plataforma. A partir disso, com ajuda de IA, do aluno Joaquim Ferola Fonseca, da T25, e do próprio tutorial, aprimorei o código, adicionando inimigos, plataformas mais rápidas e menores e criando um camera offset. Isso fez com que tivesse mais compreensão de Pygame e das classes, objetos incrivelmente úteis.
Porém eu gostaria de tentar aplicar esses  conceitos futuramente em um jogo didático - como o jogo Menace. Para isso, deixei o código o mais fácil possível de se entender posteriormente, para poder melhorá-lo depois e aprender, com o objetivo de usar o Pygame para criar jogos que simulem, por exemplo, a vida de laboratório.
A biblioteca Pygame é extremamente útil, pois permite usar recursos relativamente simples para poder fazer representações gráficas e manipulação de objetos, por isso foi escolhida para esse projeto. Além disso, ela é reforçada pela utilização de classes para melhor organização e uso, então isso me ajudou a compreender melhor um conceito novo em python - eu já havia visto um pouco sobre classes em Java, mas não me aprofundei tanto.

### Objetivos
* Aprender a usar a biblioteca PyGame e classes;
* Construir habilidades sobre desenvolvimento de jogos;
* Criar um jogo a partir de tutoriais para usar de material de estudo para futuros projetos.

### Metodologia
Primeiro pensei no objetivo do projeto, que já foi descrito anteriormente, então, como não conhecia a biblioteca usada, foi feito um estudo a partir dos tutoriais do próprio site, disponíveis nas referências. O primeiro tutorial realizado cria um jogo de carros, com fundo, sprites, esquema de colisão e movimento, além de recebimento de inputs. A partir disso, foi possível passar para o segundo tutorial, que cria um jogo de plataforma básico, com sistema de gravidade e plataformas estáticas. Então, usando o ChatGPT e o auxílio de estudantes que já usaram o Pygame, refinei o código, deixando-o mais organizado, completo e comentando. Dessa forma foi possível aprender a usar a biblioteca praticando, depurando o código, testando e analisando passo a passo.

### Resultados e Discussões
O resultado foi um jogo de plataforma com inimigos móveis. Criando o jogo, pude realmente compreender várias mecânicas úteis para se usar posteriormente, compreendendo melhor como usar as classes, subclasses e superclasses da própria biblioteca do Pygame, além de entender melhor como funciona o desenvolvimento de um jogo. Mesmo que simples, a criação e refinamento foram processos complexos, uma vez que encontrei diversos erros, como na criação dos inimigos, na movimentação das plataformas, no scroll da câmera e outros. Alguns resquísios da depuração do código ainda estão no código, uma vez que o que mais foi usado foi a análise do tipo de erro que era reportado ou, no caso de um mal funcionamento do código, prints que ajudassem a mapear o código como um todo. Com isso, foi possível entender também como lidar com certos problemas, uma vez que foi precisa uma profunda análise do código para depurá-lo e refiná-lo.
Mesmo que tenha cumprido com seu objetivo, melhorias futuras seriam interessantes, para testar outros tipos de ferramente, como tragetória, manipulação de projéteis, mecânica de recompensa e fases, além de aprender a usar e fazer outros tipos de displays, fazendo menus secundários, seleção de dificuldade, personalização de jogabilidade, etc. Isso não pode ser feito por agora por conta de limitação de tempo, mas esse é um objetivo futuro.
Além de melhorias de mecânica, alguns erros ainda podem ser consertados, como um bug sem origem conhecida, onde, em momentos aparentemente aleatórios, no começo do jogo, ele trava, ficando parado até que seja reiniciado. Isso é algo que não foi possível ser concertado ainda, mas pode ser melhorado. Ademais, os inimigos às vezes são criados na linha de plataforma e, como eles se movem, acabam se sobrepondo a elas, então seria interessante concertar isso, fora que, em alguns casos, o inimigo aparece sem se mover no eixo x, o que é outro bug conhecido, mas que ainda não pode ser analisado a fundo.

### Conclusão
Com isso, é possível apontar que o jogo foi bem sucedido, mas ainda faltam alguns pontos de refinamento, como os bugs mencionados e possíveis melhorias. Porém, mesmo incompleto, pude me sentir desafiada ao ter que aprender uma nova biblioteca, com diversas ferramentas, e uma estrutura de código inteiramente inusitada, usando classes e funções para rodar o código como um todo. A partir disso, posso dizer que escolher esse jogo como projeto de PCD foi acertivo, pois não foi somente uma tarefa mecânica, estava dentro dos meus limites e consegui me desafiar para criar o código.

### Referências
CODERSLEGACY. **Python PyGame Tutorial – The Complete Guide**. CodersLegacy, [s.d.]. Disponível em: https://coderslegacy.com/python/python-pygame-tutorial/. Acesso em: 21 de mai. 2026.

CODERSLEGACY. **Pygame Platformer – Game Development**. CodersLegacy, [s.d.]. Disponível em: https://coderslegacy.com/python/pygame-platformer-game-development/. Acesso em: 18 mai. 2026.
