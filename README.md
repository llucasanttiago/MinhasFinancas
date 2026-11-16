# Minhas Contas

App simples para controlar o dinheiro: o que entra, o que sai, contas fixas, cartão de crédito (com parcelas) e o balanço do mês. Funciona no iPhone como aplicativo, sem internet, e os dados ficam só no celular.

## Como publicar no GitHub (uma vez só)

1. Crie um repositório novo no GitHub (pode ser público) chamado `minhas-contas`.
2. Envie estes arquivos: `index.html`, `manifest.webmanifest`, `sw.js`, `icon-180.png`, `icon-192.png`, `icon-512.png` e este `README.md`.
   **Não envie o `meus-dados.json`**: ele tem os seus dados pessoais.
3. No repositório, vá em **Settings → Pages**. Em "Branch", escolha `main` e a pasta `/ (root)` e salve.
4. Em 1 ou 2 minutos aparece o link, algo como `https://SEU-USUARIO.github.io/minhas-contas/`.

## Como instalar no iPhone

1. Abra o link no **Safari**.
2. Toque em **Compartilhar** (o quadrado com a seta) → **Adicionar à Tela de Início** → **Adicionar**.
3. Abra pelo ícone novo "Minhas Contas".

## Primeira vez

1. Salve o `meus-dados.json` no app **Arquivos** do iPhone.
2. No app, vá em **Mais → Restaurar backup** e escolha o arquivo. Suas contas fixas e as faturas do cartão até dez/2027 já aparecem.

## Uso no dia a dia

- **Entradas:** registre cada dinheiro que entrar. Se for de outra pessoa (aluguel do seu pai), marque a opção "É dinheiro de outra pessoa". Ele não entra no seu saldo.
- **Saídas:** contas fixas aparecem sozinhas todo mês; toque no círculo quando pagar. Outros gastos (mercado, gasolina) você registra em "+ Registrar saída". Repasse do aluguel: categoria "Repasse a terceiros".
- **Cartão:** compras novas em "+ Compra no cartão", com o número de parcelas. O app joga cada parcela na fatura certa. Para atualizar com o banco, importe as faturas do Nubank em OFX em **Mais**.
- **Resumo:** mostra quanto sobra ou falta no mês e quanto ainda falta pagar.

## Backup

Os dados ficam só neste iPhone. Toque em **Mais → Fazer backup** toda semana e salve no app Arquivos.
