# Projeto Java de Gestão de Funcionários

Este projeto Java implementa um sistema simples de gestão de funcionários, onde é possível realizar operações básicas como adicionar, remover e manipular dados de funcionários. Além disso, o projeto inclui funcionalidades para cálculos estatísticos sobre os dados dos funcionários.

## Funcionalidades

- Adicionar novos funcionários com informações como nome, data de nascimento, salário e função.
- Remover funcionários existentes.
- Aumentar o salário de todos os funcionários em 10%.
- Agrupar funcionários por função e exibir os nomes de cada função.
- Filtrar e listar funcionários que fazem aniversário em determinados meses.
- Identificar o funcionário mais velho e calcular sua idade.
- Ordenar os funcionários por ordem alfabética.
- Calcular o total dos salários de todos os funcionários.
- Converter os salários dos funcionários para salários mínimos.

## Requisitos

- JDK (Java Development Kit) - versão 20.0.1 ou superior
- IntelliJ IDEA (ou IDE de sua preferência)

## Estrutura do Projeto
 - projeto-java-gestao-funcionarios/
 - ├── src/
 - │ └── com/
 - │ └── example/
 - │ ├── Funcionario.java
 - │ ├── Pessoa.java
 - │ └── Principal.java
 - ├── .gitignore
 - └── README.md

## Instalação e Execução

1. **Clonar o repositório:**

   ```bash
   git clone https://github.com/seu-usuario/nome-do-repositorio.git

   ## Importar o projeto no IntelliJ IDEA:

1. Abra o IntelliJ IDEA.
2. Selecione `File` > `Open` e navegue até o diretório do projeto clonado.
3. Selecione o arquivo `pom.xml` ou o diretório principal do projeto.

## Executar o projeto:

1. No IntelliJ IDEA, localize o arquivo `Principal.java` na estrutura de pastas do projeto.
2. Clique com o botão direito do mouse no arquivo `Principal.java` e escolha `Run 'Principal.main()'`.

## Detalhes Técnicos

- O projeto utiliza classes Java para representar funcionários e pessoas, utilizando a biblioteca `java.time` para lidar com datas e `java.math.BigDecimal` para precisão em operações monetárias.
- As operações de manipulação de coleções são realizadas usando Java Streams para agrupamento, filtragem e ordenação.
- A formatação de saída é feita para apresentar os dados de maneira clara e formatada.

 ´´´
    
    Desenvolvido por Marcos Correa
