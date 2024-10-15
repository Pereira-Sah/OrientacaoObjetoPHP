Desenvolver o sistema proposto abaixo, em dupla ou individualmente: 
 
Crie uma aplicação web que permita o gerenciamento da folha de pagamento de um funcionário utilizando PHP Orientado à objetos. 
 
1. Crie um formulário que permita ao usuário inserir as informações de um novo funcionário (com os campos código, nome, salário, cargo e horas trabalhadas).  
  
2. Na mesma página, exiba uma lista de funcionários com suas respectivas informações de pagamento. 
  
4. Crie uma classe Funcionario que tenha as seguintes propriedades:  
codigo: Um identificador único para cada funcionário (um número inteiro gerado automaticamente).  
nome: O nome do funcionário.  
salario: O salário base do funcionário.  
cargo: O cargo do funcionário.  
hrsTrabalhadas: As horas trabalhadas no mês. 

  

5.  A classe deve ter os seguintes métodos:  
__construct($nome, $salario, $cargo, $hrsTrabalhadas): Construtor que inicializa as propriedades.  
getCodigo(): Retorna o ID do funcionário.  
getNome(): Retorna o nome do funcionário.  
getSalario(): Retorna o salário base do funcionário.  
getCargo(): Retorna o cargo do funcionário.  
getHrTrabalhadas): Retorna as horas trabalhadas.  
calcularPagamento(): Calcula e retorna o pagamento total do funcionário considerando horas extras (salário por hora * horas trabalhadas). 
  
6. Para gerenciar os funcionários crie a classe FolhaDePagamento. Esta classe deve ter os seguintes métodos:  
addFuncioario(Funcionario $funcionario): Adiciona um novo funcionário à lista (array).  
listarFuncionarios(): Retorna um array com todos os funcionários.  
