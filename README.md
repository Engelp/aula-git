# GIT E GITHUB

Guia prático para iniciantes

### Instalação

https://git.scm.com/download

# SCENES

- [x] Você deseja criar pontos na história da produção do seu projeto
  ->Comandos: -git add [arquivo];
              -git commit -m "mensagem";

- [x] Você deseja verificar mudanças feitas no seu projeto
  ->Comandos: -git log;
              -git status;
              -git show;

- [x] Você começa um nova funcionalidade no seu projeto, sem estragar o que ja foi feito.
  ->Comandos: -git branch feature/[nome da branch];
              -git checkout feature/[nome da branch] (ramo secundário);
              -git checkout master (ramo principal);

- [x] Você adiciona as novas funcionalidades ao seu projeto em produção.
  ->Comandos: - git merge [nome da branch];

- [x] Você quer deletar a branch da nova funcionalidade, depois de aplicar em seu projeto.
  ->Comandos: - git branch -D [nome da branch]; (precione a tecla TAB para verificar as branch's)

- [x] Você quer colocar seu projeto na nuvem.
  ->Comandos: - git remote add origin [link do repositorio no git hub];
              - git remote -v
              - git push -u origin master (primeira vez)