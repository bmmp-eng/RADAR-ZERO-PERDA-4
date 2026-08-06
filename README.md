# Radar Zero Perda

Dashboard de sincronização entre Logística e Comercial para escoamento de estoque próximo do vencimento ou em ruptura oculta, desenvolvido durante o curso de Vibe Coding da CESAR School (2026).

## O que o projeto faz

- Cruza dados reais de saldo de estoque e validade de lotes (planilha `SALDO_ESTOQUE_ATUAL_ARM_05_CD-REC`).
- Sinaliza **Rupturas Ocultas** (saldo disponível zerado ou negativo) e **Risco de Validade** (lotes prestes a vencer).
- Permite auditar e liberar saldos travados por Reserva, Empenho ou Pedido.
- Ordena os produtos por vencimento mais próximo e maior quantidade, para priorizar ação comercial.
- Exporta um CSV filtrado para a equipe comercial agir sobre os itens críticos.

## Como rodar

Basta abrir o arquivo `index.html` em qualquer navegador — não precisa de instalação, servidor ou backend. Os dados já vêm embutidos no próprio arquivo.

## Stack

- HTML + Tailwind CSS (via CDN)
- JavaScript puro (sem frameworks)
- Chart.js para os gráficos

## Autor

Bruno Medeiros Marinho do Passo — Turma 2025.B
