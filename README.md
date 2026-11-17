# SIMULADO3-PR-TICO-SISTEMAS-DISTRIBU-DOS


Responda brevemente:
Questão 1. Qual é a função do semáforo no processamento dos pedidos?
R - O semáforo controla a quantidade de pedidos processados simultaneamente, limitando a três.

Questão 2. Por que é necessário sincronizar os dados entre o servidor principal e a réplica?
R- Para manter os estoques do servidor principal e da réplica atualizados e iguais.

Questão 3. O que significa tolerância a falhas e como ela aparece neste programa?
R-  É a capacidade do sistema de continuar funcionando mesmo quando ocorre uma falha. No programa, a réplica assume quando o servidor principal fica offline.

Questão 4. Para que serve o "Lock" no programa e como o controle de acesso aos recursos
ajuda a prevenir problemas de concorrência?

Questão 5. Considerando a sequência de eventos, a sincronização do estoque deve
acontecer antes ou depois do processamento dos pedidos? Explique a relação de
causalidade.
R-  Depois do processamento dos pedidos, pois primeiro o estoque principal precisa ser atualizado e, depois, esses dados são enviados para a réplica.

