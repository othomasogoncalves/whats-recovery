# WhatsApp Recovery

## Objetivo
Desenvolver um sistema seguro que recupere clientes há mais de 40 dias sem comprar através de uma planilha CSV com nome e telefone pelo WhatsApp, substutuindo um trabalho manual imposssível de realizar.

## Problemas Identificados
- Clientes sendo perdidos sem poder de reação.
- Tarefa humanamente inviável, enviar mensagens para mil pessoas semanalmente sobrecarregaria qualquer funcionário.

## Usuários do Sistema
- Admin
- Usuários

## Requisitos Funcionais
- RF01 - Entender comando de inicialização.
- RF02 - Recepcionar Admin.
- RF03 - Solicitar e processar planilha CSV.
- RF04 - Solicitar mensagem à ser enviada.
- RF05 - Confirmar envio.
- RF06 - Realizar envio inteligente.
- RF07 - Retornar feedback de envios.
- RF08 - Emitir dashboards com métricas importantes, como: quantos envios foram sucedidos, falhas, envio diário, semanal e mensal.
  
## Requisitos Não Funcionais
- RNF01 - O sistema deve possuir autenticação.
- RNF02 - O sistema deve ser web e responsivo para dispositivos móveis.
- RNF03 - Lógica inteligente que simula envio humano para evitar bans no número logado.
- RNF04 - O tempo de resposta deve ser inferior a 3 segundos.
- RNF05 - Apenas admin realiza disparo, usuários só visualizam a operação em andamento e as métricas.

## Regras de Negócio
- RN01 - É permitido somente um disparo por vez.
- RN02 - Apenas administradores podem pausar o envio.
