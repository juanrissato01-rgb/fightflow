# 🥊 FightFlow

App web para professores e academias de luta gerenciarem alunos, mensalidades e cobranças.

## Funcionalidades

- **Dashboard**: alunos ativos, receita prevista no mês, pagas, pendentes, vencendo em 3 dias e inadimplentes, gráfico de receita dos últimos 6 meses e próximos vencimentos
- **Alunos**: cadastro completo (nome, WhatsApp, nascimento, data de entrada, modalidade, plano, valor, vencimento, forma de pagamento e observações); editar, pausar/reativar e excluir
- **Planos**: Mensal, Trimestral, Semestral, Anual ou Personalizado, com o próximo vencimento calculado automaticamente
- **Mensalidades**: filtros (pagas, pendentes, vencendo em breve, atrasadas, canceladas), botão "Marcar como pago" e histórico de cada mensalidade
- **Cobranças**: fila de lembretes do dia sem repetir quem já foi avisado, mais o histórico de mensagens
- **Automações**: escolha quando avisar (3 dias antes, no vencimento, 2 e 5 dias depois) e personalize a mensagem do WhatsApp com variáveis (`{nome}`, `{modalidade}`, `{valor}`, `{vencimento}`, `{nome_academia}`, `{pix}`)
- **Relatórios**: total recebido, pendente e inadimplentes; exportação em CSV e PDF
- **Configurações**: nome da academia e chave Pix

## Como usar

Acesse pelo GitHub Pages ou abra o `index.html` no navegador. Não precisa instalar nada.

Os dados ficam salvos no `localStorage` do navegador, ou seja, só no aparelho onde foram cadastrados. As mensagens de WhatsApp são abertas para você enviar; nada é enviado automaticamente.
