# RB Pratas: levantamento de requisitos para loja virtual

**Autora:** Caroline de Santana  
**Ano:** 2026  
**Contexto:** projeto para um negócio real  
**Minha atuação:** compreensão da operação e definição inicial de escopo  
**Status:** levantamento inicial; sistema ainda não entregue.

## Contexto e problema

A RB Pratas possui loja física e realiza vendas por Instagram e WhatsApp.

O projeto surgiu do interesse em ampliar as possibilidades de venda por meio de uma loja virtual e oferecer ao proprietário autonomia para administrar produtos e pedidos.

O estoque é controlado manualmente, o que precisa ser considerado na definição da solução.

## Objetivo

Estruturar os requisitos de uma loja virtual que permita apresentar produtos, receber pedidos e apoiar a administração da operação.

O aumento das vendas é um objetivo do negócio, ainda sem resultados medidos.

## Minha atuação nesta etapa

- Reuni informações iniciais sobre a operação da loja.
- Identifiquei as categorias de produtos e os canais de venda existentes.
- Organizei as necessidades de clientes e do administrador.
- Levantei funcionalidades para catálogo, pedidos e painel administrativo.
- Identifiquei decisões pendentes sobre pagamento, estoque e entrega.

A documentação representa o levantamento inicial. Os requisitos ainda precisam ser detalhados e validados com o responsável pelo negócio.

## Partes interessadas identificadas

| Parte interessada | Necessidade |
| --- | --- |
| Proprietário | Administrar produtos e acompanhar pedidos |
| Clientes | Consultar peças, preços e condições de compra |
| Responsável pela preparação e entrega | Receber informações necessárias para atender cada pedido |

A responsabilidade pela preparação e entrega ainda precisa ser definida no detalhamento da operação.

## Requisitos funcionais iniciais

| ID | Requisito | Situação |
| --- | --- | --- |
| RF01 | Exibir anéis, brincos, correntes e pulseiras, considerando suas variações | Identificado |
| RF02 | Permitir cadastrar e editar produtos no painel administrativo | Identificado |
| RF03 | Permitir ativar e desativar produtos | Identificado |
| RF04 | Oferecer checkout e opção de finalizar pelo WhatsApp | Fluxos a detalhar |
| RF05 | Permitir consultar e gerenciar pedidos | Identificado |
| RF06 | Permitir atualizar o status dos pedidos | Fluxo inicial definido |
| RF07 | Considerar entrega local com taxa por endereço | Cálculo e abrangência a definir |

Os identificadores foram criados para organizar esta documentação. Não indicam funcionalidades implementadas ou requisitos homologados.

## Fluxo inicial de acompanhamento

Os estados inicialmente previstos para os pedidos são:

1. Recebido.
2. Em separação.
3. Saiu para entrega.
4. Entregue.

Ainda é necessário definir o tratamento de pagamento pendente, cancelamento e situações excepcionais.

## Regras propostas para validação

- Produtos desativados devem deixar de estar disponíveis para novas compras, preservando o histórico dos pedidos.
- O cliente deve conhecer a taxa de entrega e o valor total antes de confirmar a compra.
- Pedidos finalizados pelo WhatsApp precisam de um procedimento definido para registro e acompanhamento.
- A disponibilidade das variações deve considerar o estoque compartilhado entre os canais de venda.

Estas são propostas de análise. A aplicação de cada regra depende de validação com o proprietário.

## Decisões pendentes

| Decisão | Impacto no projeto |
| --- | --- |
| Forma de pagamento | Define confirmação e tratamento do pedido |
| Controle e reserva de estoque | Evita divergências entre vendas físicas e digitais |
| Área e taxa de entrega | Define onde a loja atende e quanto cobra |
| Plataforma e hospedagem | Influencia custos, administração e manutenção |
| Fotos e informações das peças | Viabiliza o cadastro inicial do catálogo |
| Orçamento e responsabilidades | Define condições de implantação e continuidade |

A referência inicial para entregas locais é o Cambuci, em São Paulo.

## Entrega desta etapa

Organização do escopo inicial, dos requisitos identificados e das decisões necessárias para avançar.

Não há, nesta versão, loja virtual publicada, painel implementado ou vendas geradas pelo sistema.

## Competências demonstradas

- Levantamento inicial de necessidades.
- Identificação de partes interessadas.
- Definição de escopo.
- Organização de requisitos funcionais.
- Identificação de regras de negócio.
- Mapeamento de dependências e decisões pendentes.
- Comunicação entre necessidades do negócio e solução tecnológica.

## Próximos passos

Validar o escopo com o proprietário, detalhar os fluxos de compra e administração, definir regras de estoque e entrega e estabelecer as condições de implementação.

## Evidências

Este documento consolida o briefing relatado e organiza propostas para validação.

Não há sistema ou protótipo anexado nesta etapa.

[Voltar ao portfólio](../README.md)
