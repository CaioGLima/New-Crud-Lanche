# New-Crud-Lanche


Projeto para estudo de Crud, ainda não finalizado... Utilizando o colab.
Sistema de lanchonete 

Requisitos:
A Lanchonete Tech deseja um sistema simples de caixa para linha de comando. Este projeto
deve ser desenvolvido em APENAS UM ARQUIVO Python (.py), sem uso de POO e sem
salvar em arquivos externos. Todos os dados ficarão em memória (dicionários/listas). O
objetivo é consolidar conteúdos vistos em aula: funções, modularização no próprio arquivo,
laços (while/for), listas, dicionários, strings, conversões e input/print.

• Menu principal em loop (while True) com três áreas: Produtos, Pedidos e Relatórios.
• Dados SOMENTE em memória: dicionários e listas (sem CSV/TXT/bancos).
• Validação de entradas (número, vazio, negativo, códigos inexistentes).
• Cálculo de subtotal, desconto por cupom e taxa de serviço opcional.
• Emissão de recibo no fechamento do pedido (texto no terminal).

Fluxo de Uso
• 1) Produtos: listar / cadastrar (permitir alterar nome/preço se código já existir) /
ativar-inativar.
• 2) Pedidos: inserir itens por código até '0' encerrar; validar se código existe e se produto
está ativo; perguntar cupom e taxa (S/N); exibir recibo.
• 3) Relatórios: faturamento total; item mais vendido; ticket médio; top 3 produtos (por
quantidade).
