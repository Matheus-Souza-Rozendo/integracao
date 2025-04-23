# Enunciado

Modelar e implementar um banco de dados relacional para controle de treinamentos oferecidos a funcionários de uma empresa.

Cada treinamento tem um nome, duração, instrutor e data de realização. Funcionários podem se inscrever em vários treinamentos, mas não podem participar de dois ao mesmo tempo. Treinamentos têm uma quantidade máxima de participantes.

# Entregas

Trabalho a ser realizado em grupos de 3 a 4 componentes. Informar a composição dos grupos em espaço apropriado no Moodle até 23h59 de 24/04/2025.

Entregar, até o dia 11/05/2025, via Moodle, os seguintes itens:

## 2.1 Modelos conceitual e lógico

Podem ser entregues arquivos gerados no BrModelo ou em qualquer outro software. No caso de arquivos gerados em softwares diferentes do BrModelo, entregar os modelos em formato PDF ou como imagem (JPEG, PNG etc).

## 2.2 Arquivo texto contendo script SQL

- Script para a criação das tabelas e para a inserção de registros de exemplo.
- Incluir tantos registros quantos forem necessários para testar as consultas definidas no item 2.3 deste enunciado.

## 2.3 Arquivo texto com as seguintes consultas SQL

1. Listar os treinamentos com mais de 10 participantes.
2. Listar os nomes dos funcionários que participaram de todos os treinamentos de um determinado instrutor.
3. Listar os treinamentos que ocorreram em um determinado período (período informado na consulta).
4. Listar os funcionários com treinamentos simultâneos (inconsistência).
5. Listar os instrutores que ofereceram treinamentos com menos de 5 participantes.
6. Calcular a média de treinamentos por funcionário.
7. Listar os funcionários que participaram de treinamentos com duração acima da média.
8. Mostrar treinamentos em que o número de participantes ultrapassou o limite máximo.

## 2.4 Implementação do banco de dados

- A implementação deve estar disponível em uma máquina virtual fornecida pela UFSC (informações aqui), em alguma outra máquina virtual que possa ser acessada pela Internet, ou em uma imagem Docker.

## 2.5 Documento com informações para acesso

- Documento contendo as informações para acesso à máquina virtual e ao banco de dados implementado do item 2.4.

# Apresentação

O grupo apresentará o trabalho ao professor em 14/05/2025. A apresentação consistirá em:

1. Discussão sobre os modelos conceitual e lógico.
2. Execução do banco de dados criado pelo grupo.
3. Execução de consultas SQL solicitadas pelo professor (sem consulta a qualquer material).

# Avaliação

- **Item 2.1. Peso: 15%**: Os modelos devem refletir corretamente os requisitos do cenário descrito no enunciado, bem como as demais decisões tomadas pelo grupo no projeto do banco de dados. Além disso, devem estar consistentes entre si.
- **Item 2.2. Peso: 5%**: O script deve poder ser executado sem erros, produzindo o schema que permita a execução das consultas solicitadas.
- **Item 2.3. Peso: 35%**: As consultas devem retornar resultados corretos. Todas as consultas têm o mesmo peso na avaliação.
- **Itens 2.4 e 2.5. Peso: 5%**: A máquina virtual deve funcionar corretamente a partir dos passos descritos no documento fornecido pelo grupo, sem requerer configurações adicionais.
- **Item 3.1. Peso: 5%**: O grupo deve fornecer respostas consistentes ao professor com respeito aos modelos conceitual e lógico.
- **Item 3.2. Peso: 5%**: O grupo deve ser capaz de colocar o banco de dados em execução.
- **Item 3.3. Peso: 30%**: O grupo deve executar as consultas corretamente.
