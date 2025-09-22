# controle-versao-atividade

Atividade prática de **Gerenciamento de Configuração de Software** usando Git e GitHub.

## Objetivo
Praticar versionamento com **branches, commits e merges** seguindo o fluxo:



## Estrutura de branches
- **master**: versão estável (simula produção)
- **develop**: integra funcionalidades antes de ir para a master
- **feature/cadastro-usuarios**: exemplo de branch de funcionalidade

## Fluxo de trabalho
1. Desenvolver na branch `feature/*` (commits pequenos e claros).
2. Abrir Pull Request **feature → develop** e fazer o merge.
3. Validar a `develop` e abrir PR **develop → master** para simular entrega.

## Mensagens de commit (exemplos)
- `feat(cadastro-usuarios): estrutura inicial`
- `feat(cadastro-usuarios): adiciona função cadastrarUsuario()`
- `docs: adiciona README inicial`
- `merge: integra feature/cadastro-usuarios em develop`
- `merge: integra develop em master (entrega)`

## O que imprimir para a entrega
- Branches **master / develop / feature**
- Histórico de commits
- PRs Merged: `feature → develop` e `develop → master`