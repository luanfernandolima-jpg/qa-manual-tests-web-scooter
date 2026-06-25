\# Bug Report - Campo Endereço permite avanço sem preenchimento



\## Descrição

O sistema permite que o usuário avance para a próxima etapa mesmo sem preencher o campo Endereço, sem exibir mensagem de validação ou bloqueio do fluxo.



\---



\## Passos para reproduzir

1\. Acessar a página inicial do sistema.

2\. Navegar até a seção "Como Funciona".

3\. Clicar no botão "Fazer pedido".

4\. Na tela "Para quem é a scooter?", localizar o formulário.

5\. Preencher:

&#x20;  - Nome: Carlos

&#x20;  - Sobrenome: Oliveira

6\. Deixar o campo Endereço em branco.

7\. Tentar avançar para a próxima etapa (clicando em outro campo ou usando Tab).

8\. Selecionar uma estação de metrô válida.

9\. Preencher telefone: +11111 11

10\. Tentar prosseguir para a próxima tela.



\---



\## Resultado atual

O sistema permite avançar para a próxima etapa mesmo com o campo Endereço vazio, sem exibir mensagem de erro ou bloqueio.



\---



\## Resultado esperado

O sistema deve impedir a navegação enquanto o campo Endereço estiver vazio e exibir uma mensagem de validação indicando que o campo é obrigatório.



\---



\## Ambiente

\- Navegador: Chrome

\- Resolução: 1020 x 1080



\---



\## Severidade

Alta (impacta validação de campo obrigatório e integridade do fluxo)



\## Observações

\- O campo deveria ficar destacado em vermelho quando inválido.

\- Validação deveria ocorrer ao sair do campo ou ao tentar avançar.

