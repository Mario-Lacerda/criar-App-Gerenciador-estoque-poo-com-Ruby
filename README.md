# Desafio Dio  Criando um App Gerenciador de Estoque com Programação Orientada a Objetos com Ruby



Criar um projeto de **gerenciador de estoque** em **Ruby**, utilizando **Programação Orientada a Objetos (POO)**. A POO é um paradigma que organiza o código em torno de **objetos** e **classes**, permitindo reutilização e modularidade. Vou apresentar uma estrutura básica e alguns exemplos de implementação.



## Estrutura do Projeto:

1. **Módulo de Produtos**: Responsável por gerenciar os produtos em estoque.
2. **Módulo de Vendas**: Gerencia as vendas e atualiza o estoque.
3. **Módulo de Relatórios**: Fornece relatórios sobre o estado atual do estoque e histórico de vendas.



## Solução Procedural em Ruby:

- Ruby suporta tanto paradigmas orientados a objetos quanto procedurais. Neste projeto, usaremos o paradigma procedural.
- Cada tarefa será realizada por uma função específica, tornando o código reutilizável e fácil de entender.



## Exemplo de Função de Adição de Produto:

Ruby



```ruby
def adicionar_produto(nome, quantidade)
  # Lógica para adicionar produto ao estoque
end
```



Código gerado por IA. Examine e use com cuidado. [Mais informações em perguntas frequentes](https://www.bing.com/new#faq).



## Implementação dos Módulos:

### Módulo de Produtos (`produtos.rb`):

Ruby



```ruby
def adicionar_produto(nome, quantidade)
  # Adiciona um novo produto ao estoque
end

def remover_produto(nome)
  # Remove um produto do estoque
end

def atualizar_quantidade(nome, nova_quantidade)
  # Atualiza a quantidade de um produto específico
end
```

Código gerado por IA. Examine e use com cuidado. [Mais informações em perguntas frequentes](https://www.bing.com/new#faq).



### Módulo de Vendas (`vendas.rb`):

Ruby



```ruby
def registrar_venda(produto, quantidade)
  # Registra uma venda e atualiza o estoque
end

def calcular_total_vendas
  # Calcula o total de vendas realizadas
end
```



Código gerado por IA. Examine e use com cuidado. [Mais informações em perguntas frequentes](https://www.bing.com/new#faq).



### Módulo de Relatórios (`relatorios.rb`):

Ruby



```ruby
def gerar_relatorio_estoque
  # Gera um relatório do estoque atual
end

def gerar_relatorio_vendas
  # Gera um relatório das vendas realizadas
end
```

Código gerado por IA. Examine e use com cuidado. [Mais informações em perguntas frequentes](https://www.bing.com/new#faq).

## Programa Principal (`main.rb`):

Ruby



```ruby
require_relative 'produtos'
require_relative 'vendas'
require_relative 'relatorios'

# Exemplo de execução de funções
adicionar_produto('Teclado', 50)
registrar_venda('Teclado', 1)
gerar_relatorio_estoque
```Desafio Dio  Criando um App Gerenciador de Estoque com Programação Orientada a Objetos com Ruby
