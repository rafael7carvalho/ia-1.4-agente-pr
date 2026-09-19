# Exercício ia-1.4 — Agente cria arquivo, abre PR e merge

Este arquivo demonstra uma alteração feita em uma branch e integrada à branch principal por meio de um pull request.

## Fluxo de trabalho

1. Criar um repositório público com README inicial e cloná-lo no computador.
2. Criar a branch `adiciona-relato-exercicio` para desenvolver a alteração.
3. Adicionar este arquivo e registrar a alteração em um commit.
4. Enviar a branch ao GitHub e abrir um pull request para revisão.
5. Revisar a alteração e fazer o merge do pull request na branch principal.
6. Atualizar o clone local e verificar o histórico e o estado do pull request.

## Papel dos comandos

- `git switch -c`: cria uma branch e passa a trabalhar nela.
- `git add` e `git commit`: preparam e registram a alteração no histórico local.
- `git push`: envia os commits da branch ao repositório remoto.
- `gh pr create`: abre uma proposta de integração da branch de trabalho à branch principal no GitHub.
- `gh pr diff`: mostra as alterações do pull request para revisão.
- `gh pr merge --merge`: integra a alteração e preserva um commit de merge no histórico.
- `git pull --ff-only`: atualiza a branch local sem criar um merge adicional.

O pull request mantém um registro da alteração proposta e de sua integração ao projeto.
