# Objetivos

Construir um programa para executar o jogo da vida de John Conway. O programa será implementado em linguagem R, em notebook do R Markdown.

Os membros do grupo podem usar a IDE RStudio ou o Kernel do Kaggle.  

# Atividades
- [x] Camada de input - função que captura a dimensão da tela (em pixels) e a condição inicial do sistema;
- [ ] Teste a camada de input e adicione mensagens de erro;
  - [x] dimensão entre 10 e 500
  - [ ] Número aleatório pra definir a dimensão
  - [ ] Não aceitar nada que não seja um número (dúvida: pode ser valor quebrado?)
  - [ ] obj não pode ser diferente de: "glider","lines","points","squares","cruxx"
  - [ ] número de objetos (no) não pode ser zero
- [ ] Gerar - função cria uma matriz de zeros com a dimensão fornecida pelo usuário;
- [ ] Função inicial - objetos (quadrado, cruz, linha, glider) são incluídos na matriz inicial (obs: espaços ocupados possuem o valor 1);
- [ ] Função plotar - transforma a matriz de zeros e uns em uma figura com pixels brancos e pretos;
- [ ] Implemente as regras de negócio do Jogo da Vida
- [ ] ... Vou inserir outras atividades em breve ...
- [ ] Quando tudo estiver pronto :tada:
