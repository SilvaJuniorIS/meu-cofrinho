# Meu Cofrinho 🐷✨

Protótipo mobile-first de um aplicativo familiar de tarefas, mesada e recompensas.

## Perfil temporário de apresentação

- Pai: Israel Junior
- Mãe: Luciana Andreia
- Eliza Maria: 12 anos
- Isaías Miguel: 9 anos

A tela de boas-vindas permite escolher a criança antes de entrar no app. Cada perfil tem tarefas, recompensas e progresso próprios. O mascote Faísca aparece na entrada e nas telas do app.

## Demonstração

Abra `index.html` em um navegador moderno ou use o GitHub Pages quando estiver habilitado. Os dados ficam salvos apenas no armazenamento local deste navegador.

### Fluxo da criança
1. Na tela inicial, escolha Eliza ou Isaías e toque em **Entrar no app**.
2. Toque no círculo ao lado de uma tarefa concluída. Ela passa a aguardar confirmação.
3. Acompanhe tarefas, saldo demonstrativo, estrelas e prêmio.

### Fluxo do responsável
1. Toque em **Criança** no topo para abrir o modo responsável.
2. Em **Para confirmar**, aprove ou devolva a tarefa para revisão.
3. Use **Histórico** para ver confirmações e **Perfis e tarefas** para consultar as duas crianças.

### Reset
Use **Resetar** no topo ou **Família → Resetar o app e voltar ao início**. A ação pede confirmação e apaga o progresso temporário das duas crianças deste navegador.

## Limites desta versão

É um protótipo visual e interativo para apresentação e testes. Não há autenticação, sincronização entre dispositivos, notificações push ou pagamentos. Os perfis, tarefas, saldos e recompensas são dados de demonstração, armazenados localmente.

## Estrutura

- `index.html`: protótipo navegável, responsivo e autocontido, com o mascote incorporado.
- `manifest.json`: metadados iniciais para instalação como PWA.
- `README.md`: visão geral e roteiro de demonstração.
