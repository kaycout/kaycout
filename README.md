# Estudo de Caso: Salão de Cabeleireiro "Cabelos Incríveis"

### Cabelos Incríveis 

## Contexto:
O salão de cabeleireiro "Cabelos Incríveis" é um estabelecimento localizado em uma área movimentada da cidade. O salão oferece uma variedade de serviços, incluindo cortes de cabelo, coloração, tratamentos capilares, manicure e pedicure. Eles têm uma equipe de cabeleireiros talentosos e uma base de clientes fiéis.
### Desafio:
O salão de cabeleireiro "Cabelos Incríveis" está enfrentando dificuldades para gerenciar eficientemente seus clientes, agendamentos, estoque de produtos e informações dos funcionários. Eles precisam de um sistema de banco de dados para ajudar a organizar e automatizar esses processos. 
### Requisitos do Sistema:
• Gerenciamento de Clientes: Cadastro de novos clientes com informações como nome, endereço, telefone, e-mail, preferências de serviços, histórico de serviços realizados, etc. 
O registro de serviços realizados por cada cliente, incluindo datas, tipos de serviço, cabeleireiro responsável, etc.
O Possibilidade de atualização e exclusão de informações de clientes. 
### Agendamento de Serviços:
Capacidade de agendar serviços para clientes, incluindo data, horário, tipo de serviço, cabeleireiro responsável, etc. o Visualização rápida de disponibilidade de horários e cabeleireiros para agendamentos.   
### Gerenciamento de Estoque:
Controle de estoque de produtos utilizados no salão, como tinturas, shampoos, condicionadores, etc.
Registro de entrada e saída de produtos, incluindo quantidades e datas. 
### Informações dos Funcionários: 
Cadastro de informações dos funcionários, incluindo nome, função, horário de trabalho, salário, etc.
Atribuição de serviços realizados por cada funcionário e acompanhamento de seu desempenho.


# Especificação de elementos do banco de dados.

• Tabelas:
 Clientes ▪ Cliente_ID (Chave Primária) ▪ Nome ▪ Endereço ▪ Telefone ▪ E-mail ▪ Preferências o Serviços ▪ Serviço_ID (Chave Primária)
 ▪ Tipo ▪ Descrição ▪ Preço o Agendamentos ▪ Agendamento_ID (Chave Primária) 
 ▪ Cliente_ID (Chave Estrangeira referenciando a tabela Clientes) ▪ Serviço_ID (Chave Estrangeira referenciando a tabela Serviços)
 ▪ Data ▪ Horário ▪ Cabeleireiro o Estoque ▪ Produto_ID (Chave Primária)
 ▪ Nome ▪ Quantidade ▪ Data_Entrada ▪ Data_Saída o Funcionários ▪ Funcionário_ID (Chave Primária) ▪ Nome ▪ Função ▪ Horário_Trabalho ▪ Salário

 # Modelo Lógico com as normalizações
