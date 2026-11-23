# Repo de materiais (template do Chama DM)

Este repo guarda os materiais que o Chama DM entrega por DM. O site é servido em
`https://repo.dimus.com.br/<cliente>/` (Worker `chamadm-repos`, código em `OpenClawDimus/manychat/repo-worker`).

## Como editar

Edite `materiais.json`. Cada material:

| Campo | O que é |
|---|---|
| `slug` | parte final da URL: `/<cliente>/m/<slug>` (minúsculas, números e `-`) |
| `titulo` | título da página e do material no Chama DM |
| `resumo` | texto curto embaixo do título (opcional) |
| `destino` | link `https://` do botão (PDF, Drive, formulário…) |
| `botao` | texto do botão (opcional, padrão "Acessar o material") |

A mudança vale em até 5 minutos. Depois, em Repo Connect, clique em Sincronizar.

Não coloque segredo, senha ou dado pessoal aqui: o repo é público.
