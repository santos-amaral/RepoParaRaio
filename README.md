# Repositório de Versionamento do SENAI

## Título secundário

# Como contribuir neste repositório

## Fluxo

1. Atualize `main`.
2. Crie uma branch: `git checkout -b feature/sua-tarefa`.
3. Faça commits pequenos e claros.
4. Abra merge para `main` só depois de testar no navegador.

## Mensagem de commit

```
Tipo: resumo em até 50 caracteres

Corpo opcional explicando o porquê.
```

Tipos: `Adiciona`, `Corrige`, `Remove`, `Documenta`, `Ajusta`.

## O que não entra no Git

Arquivos listados em `.gitignore`. Confira com `git status` antes de `git add .`.

## Conflito

1. Não apague o código do colega sem ler.
2. Decida com o par o conteúdo final.
3. Teste a página depois do merge.

# Portfólio SENAI — UC Versionamento

Repositório de trabalho da Unidade Curricular **Versionamento** (16 h)  
Curso: Qualificação Profissional — Programador Front-End.

## Objetivo

Praticar Git em um projeto real de interface: clonar, commitar, ramificar, mesclar, marcar versões e ignorar arquivos.

## Estrutura

```
repo-aula-versionamento/
├── README.md
├── .gitignore
├── LICENSE
├── CONTRIBUTING.md
├── docs/
│   ├── convencoes.md
│   └── fluxos-git.md
├── src/
│   ├── index.html
│   ├── css/style.css
│   └── js/main.js
└── assets/img/
```

## Comandos iniciais

```bash
git status
git log --oneline
git branch -a
```

## Regras da turma

1. Commits em português, no imperativo: `Adiciona seção de habilidades`.
2. Uma alteração lógica por commit.
3. Branch de feature: `feature/nome-curto`.
4. Nunca commitar `node_modules`, `.env` ou arquivo pessoal.

Leia `CONTRIBUTING.md` e `docs/` antes da primeira tarefa.