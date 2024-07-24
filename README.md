# quiz-game
Quiz Game em javascript
[acesse aqui](https://lfernandoetec.github.io/quiz-game/)
***
# Prompt do bing
gere uma imagem em estilo carton para um jogo de problemas no hardware que represente Problema de Fonte de Alimentação
***
# Explicações do Código

- **HTML e CSS:** A estrutura HTML e o estilo CSS são definidos no início, configurando a aparência e a disposição dos elementos no jogo.

- **Array `gameData`:** Contém os dados de cada fase do jogo, incluindo a descrição do problema, a imagem ilustrativa, e as respostas possíveis, onde a primeira resposta é sempre a correta.

- **Função `shuffleArray`:** Embaralha as respostas para que a ordem de exibição seja aleatória em cada execução do jogo, garantindo que a resposta correta não seja sempre na mesma posição visual.

- **Função `exibirFase`:** Exibe a fase atual com a imagem, título, problema, e respostas embaralhadas. Esta função também configura os botões para que a resposta escolhida seja verificada.

- **Função `verificarResposta`:** Verifica se a resposta escolhida pelo jogador é correta. Se for, avança para a próxima fase; caso contrário, solicita ao jogador que tente novamente.

- **Função `proximaFase`:** Incrementa o índice da fase e exibe a próxima fase. Se todas as fases forem completadas, reinicia o jogo.
***

# Game Design Document (GDD)

## Título do Jogo
Jogo de Identificação de Problemas em Computadores

## Plataforma
Web (HTML5, CSS, JavaScript)

## Público-Alvo
- Idade: 12+
- Interesse: Pessoas interessadas em aprender sobre manutenção básica de computadores e resolução de problemas de hardware.

## Objetivos de Aprendizagem
- **Identificação de Problemas:** Ensinar aos jogadores como identificar problemas comuns em computadores.
- **Resolução de Problemas:** Demonstrar as soluções apropriadas para cada tipo de problema apresentado.
- **Conhecimento de Hardware:** Familiarizar os jogadores com os componentes básicos do hardware de um computador e suas funções.

## Resumo do Jogo
O jogador deve resolver problemas comuns em computadores através de um jogo interativo baseado em fases. Em cada fase, o jogador é apresentado a um problema específico, e deve escolher a solução correta entre várias opções embaralhadas. O objetivo é selecionar a resposta correta para progredir para a próxima fase.

## Mecânica do Jogo
1. **Fases:**
   - O jogo é dividido em múltiplas fases, cada uma representando um problema específico de hardware em um computador.
   - O jogador deve resolver cada fase selecionando a solução correta entre as alternativas fornecidas.

2. **Sistema de Resposta:**
   - As respostas são apresentadas em uma ordem aleatória.
   - A primeira resposta na lista de dados (`gameData`) é sempre a correta, mas é embaralhada antes de ser exibida.

3. **Progressão:**
   - O jogador avança para a próxima fase ao selecionar a resposta correta.
   - Se a resposta estiver incorreta, o jogador é informado e pode tentar novamente.

4. **Feedback:**
   - Mensagens de feedback positivo ou negativo são fornecidas com base na escolha do jogador.

## Estrutura das Fases
### Fase 1: Problema de Conexão de Cabos
- **Descrição:** Um computador com cabos desconectados.
- **Respostas:**
  1. Reconectar os cabos. (Correta)
  2. Trocar a placa-mãe.
  3. Atualizar o sistema operacional.
  4. Aumentar a memória RAM.

### Fase 2: Problema de RAM
- **Descrição:** Um computador com uma placa de RAM solta.
- **Respostas:**
  1. Reencaixar a RAM. (Correta)
  2. Atualizar o antivírus.
  3. Trocar o processador.
  4. Formatar o disco rígido.

### Fase 3: Problema de Sobreaquecimento
- **Descrição:** Um computador com superaquecimento e ventoinha parada.
- **Respostas:**
  1. Limpar e ventilar o computador. (Correta)
  2. Aumentar a resolução da tela.
  3. Desinstalar programas desnecessários.
  4. Trocar o monitor.

### Fase 4: Problema de Disco Rígido
- **Descrição:** Um computador com um disco rígido danificado.
- **Respostas:**
  1. Substituir o disco rígido. (Correta)
  2. Atualizar os drivers de áudio.
  3. Aumentar a capacidade da memória RAM.
  4. Limpar a pasta de downloads.

### Fase 5: Problema de Fonte de Alimentação
- **Descrição:** Um computador com uma fonte de alimentação queimada.
- **Respostas:**
  1. Trocar a fonte de alimentação. (Correta)
  2. Atualizar o navegador de internet.
  3. Aumentar o brilho da tela.
  4. Desfragmentar o disco rígido.

## Interface de Usuário
- **Tela Inicial:** Apresenta o título do jogo e instruções básicas.
- **Área de Jogo:** Mostra a imagem do problema atual, descrição do problema, e opções de resposta.
- **Botões de Resposta:** Quatro botões clicáveis, cada um representando uma possível solução para o problema apresentado.
- **Feedback:** Alertas informando o jogador sobre a correção da resposta e promovendo o avanço para a próxima fase.

## Tecnologias Utilizadas
- **HTML:** Estrutura da página e elementos do jogo.
- **CSS:** Estilos visuais e layout.
- **JavaScript:** Lógica do jogo, controle de fluxo e interação do usuário.

## Considerações Finais
O jogo oferece uma experiência educativa simples que permite aos jogadores aprender sobre problemas comuns de hardware de uma forma interativa e envolvente. O uso de imagens e descrições claras ajuda a tornar os conceitos mais acessíveis para o público-alvo. Este jogo pode ser expandido com mais fases, feedback detalhado, e um sistema de pontuação para aumentar ainda mais o engajamento e a retenção do conhecimento.
