# O QUE É UM BANCO DE DADOS ?

"Coleção de dados **Relacionados**" *(Definição muito genérica)*

Porém uma coleção de palavras pode ser um Banco de Dados ?

O uso do termo Banco de Dados tem algumas propriedades explícitas:

* Representa o aspecto de algo do mundo real.
* Coleção logicamente coerente de dados.
* Projetado para uma finalidade específica.
  
<br>

# O QUE É UM SGDB ?

SGBD - Sistema de Gerenciamento de Banco de Dados

Sistema computacional que permite que usuários mantenham um banco de dados.

<br>

## SGBD - Sistema de uso geral:
<br>

    Permite definir, construir, manipular e compartilhar o banco de dados.


**Definição** - Especificar tipos, estruturas e restrições dos dados armazenados (Metadados).

**Construção** - Processo de armazenar os dados em algum meio.

**Manipulação** - Funções de consulta, recuperar dados, atualizar dados, ou seja, refletir as mudanças no mundo real.

**Compartilhamento** - Usuários e programas acessem o Banco de Dados simultaneamente.

<br>
<img src="./assets/sistema_banco_dados.png" width="750" >

<br>

### Exemplos de SGBD's do mercado:

<br>
<img src="./assets/sgbds_exemplos.png" width="750" >

<br>

# SGDB

    Abstração de Dados - Suprimir ao usuário detalhes da organização e armazenamento dos dados. O modelo de dados permite essa abstração

<br>

## Modelos de Alto Nível <- Modelos de Dados Representativos -> Modelos de Baixo Nível

<br>

* Modelos de Alto Nível = Modelos de Entidade e Relacionamento (Entidade, atributos e relacionamento)

* Modelos de Relacionamento (Relacional) = Linguagem SQL

* Modelos de Baixo Nível = Acesso a estrutura de armazenamento e índices

<br>

**Esquema do Banco de Dados:** Refere-se a descrição do banco de dados. <br>
Normalmente não muda. O que muda é o conteúdo do Banco de Dados.

<br>
<img src="./assets/esquema_banco_de_dados.png" width="750" >

<br>
Dados do banco de dados mudam com frequência.

