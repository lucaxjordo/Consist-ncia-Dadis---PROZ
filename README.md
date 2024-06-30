# Consistencia Dados - PROZ
Trabalho turma ENT - Professfor Juliano

Consistência de Dados em Sistemas Distribuídos

-  Introdução
  Este repositório contém um trabalho acadêmico sobre a importância da consistência e validação de dados em sistemas de software distribuídos. O trabalho abrange fundamentos teóricos, exemplo prático, desafios e melhores práticas para garantir a consistência de dados em     diferentes cenários. Além disso, o projeto destaca a importância da validação de dados, essencial para manter a integridade e precisão dos dados em sistemas distribuídos.


-  Objetivos da Apresentação
  Discutir a importância da consistência de dados em sistemas de software e a validação de dados.
  Apresentar os conceitos fundamentais da consistência de dados.
  Explicar os diferentes tipos de consistência e suas aplicações.
  Demonst  rar técnicas e ferramentas para garantir consistência e validação de dados.
  Analisar estudos de caso e exemplos práticos.
  Identificar desafios e melhores práticas na manutenção da consistência e validação de dados.


-  Estudos de Caso e Exemplos Práticos
  Código de Transações Bancárias
    Um exemplo de código simples de transações bancárias, focando no aspecto de validação de dados mais do que na interação com banco de dados.
  Pontos Fortes de Validação de Dados do Código
    Validação de Entrada de Dados: O código verifica se as opções do menu e os valores de transação são válidos, evitando entradas inválidas que poderiam causar erros no sistema.
  
  Validação de Depósitos: 
    O código garante que apenas valores positivos sejam aceitos para depósitos, evitando erros como depósitos de valores negativos ou zero.
  
  Validação de Saques:
    Saldo Suficiente: Verifica se há saldo suficiente antes de permitir um saque.
    Limite de Saque: Garante que o valor do saque não exceda o limite permitido.
    Número Máximo de Saques: Controla o número máximo de saques permitidos por dia, assegurando que não sejam realizados mais saques do que o permitido.
    Registro de Transações: Mantém um extrato das transações realizadas, registrando depósitos e saques de forma detalhada para futura referência e verificação.
  
  Feedback ao Usuário: 
    Fornece mensagens claras ao usuário em caso de falha na operação, explicando o motivo da falha, o que ajuda na compreensão e correção de erros.
