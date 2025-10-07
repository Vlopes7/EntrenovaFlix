# Padrão de commits

A equipe adotou o padrão [Conventional Commits](https://www.conventionalcommits.org/pt-br/v1.0.0/) durante o desenvolvimento deste projeto.

## Formato do commit

```bash

<type>[escopo opcional]: <descrição breve>

[corpo opcional]

[rodapé(s) opcional(is)]

```

---

## Tipos de commit

A seguir estão os tipos mais comuns usados no projeto, com uma breve explicação do que cada prefixo indica:

- **`feat`**: Indica a **adição de uma nova funcionalidade** ao projeto.
- **`fix`**: Representa a **correção de um bug**.
- **`docs`**: Refere-se a **alterações na documentação**, como README, comentários ou qualquer outro arquivo de documentação.
- **`style`**: Mudanças que não afetam a lógica do código (semântica), como **formatação, espaços, ponto e vírgula, etc.**
- **`chore`**: Refere-se a **tarefas de manutenção** do projeto, que não afetam o código de produção nem os testes (ex: configuração de ferramentas, dependências, etc.).

---

## Exemplos

- feat(auth): adiciona autenticação por token JWT
- fix(api): corrige erro 500 ao buscar usuários inativos
- docs(readme): atualiza instruções de instalação do projeto
- style(header): ajusta identação e remove espaços em branco
- chore(deps): atualiza dependências do eslint para última versão
