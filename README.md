
# Cadastro de Produto com Interface Gráfica (Java + CSV)

Este projeto é um exemplo didático utilizado na disciplina de **Projeto de Software**, com o objetivo de demonstrar a interação entre o **Diagrama de Classes** e o **Diagrama de Sequência**.

A funcionalidade implementada é o **Cadastro de Itens**, onde os dados são inseridos por meio de uma **interface gráfica (Swing)** e armazenados em um banco de dados **MySQL**.

---

## Funcionalidade Principal

- Cadastro de produto com os campos:
  - Nome
  - Categoria
  - Preço
  - Status
  - Quantidade em Estoque
- Armazenamento dos dados em banco de dados MySQL
- Interface simples com Java Swing

---

## Estrutura do Projeto

- `Item`: classe modelo que representa o item
- `ItemDAO`: responsável por salvar e carregar os dados do banco
- `CadastrarItemForm`: interface gráfica para entrada dos dados

---

## Diagrama de Classes

O diagrama de classes ilustra a estrutura do sistema, com a classe `Item` representando os produtos, e a classe `ItemDAO` sendo responsável pela persistência dos dados no banco. 
As classes `CadastrarItemForm`, `EditarItemForm` e `ExcluirItemForm` representam as interfaces gráficas que interagem com o usuário.

### Astah

![C - Cadastro de Produto](https://github.com/MiguelToller/Trabalho-Restaurante/blob/main/Diagramas/Diagramas%20Classe/CadastrarItem%20Diagram.png)

---

![C - Cadastro de Produto](https://github.com/MiguelToller/Trabalho-Restaurante/blob/main/Diagramas/Diagramas%20Classe/EditarItem%20Diagram.png)

---

![C - Cadastro de Produto](https://github.com/MiguelToller/Trabalho-Restaurante/blob/main/Diagramas/Diagramas%20Classe/ExcluirItem%20Diagram.png)

---

## Diagrama de Sequência

O diagrama de sequência descreve a interação entre os objetos ao longo do tempo, detalhando como as solicitações de cadastro, edição e exclusão de produtos fluem no sistema.

### Astah

![DS - Cadastro de Produto](https://github.com/MiguelToller/Trabalho-Restaurante/blob/main/Diagramas/Diagramas%20Sequencia/CadastrarItem%20Sequencia.png)

---

![DS - Cadastro de Produto](https://github.com/MiguelToller/Trabalho-Restaurante/blob/main/Diagramas/Diagramas%20Sequencia/EditarItem%20Sequencia.png)

---

![DS - Cadastro de Produto](https://github.com/MiguelToller/Trabalho-Restaurante/blob/main/Diagramas/Diagramas%20Sequencia/ExcluirItem%20Sequencia.png)

---

## Casos de Uso

### 1. Cadastrar Produto
O usuário insere os dados do produto na interface gráfica, e os dados são salvos no banco de dados MySQL.

### 2. Editar Produto
O usuário pode modificar as informações de um produto existente.

### 3. Excluir Produto
O usuário pode remover um produto do sistema.

### 4. Visualizar Produtos
O sistema permite visualizar os produtos cadastrados.

---

![DCS - Cadastro de Produto](https://github.com/MiguelToller/Trabalho-Restaurante/blob/main/Diagramas/Diagramas%20Extra/Diagrama%20UseCase.png)

---

## Como Executar

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/cadastro-produto-java.git
   ```
2. Compile os arquivos `.java`:
   ```bash
   javac *.java
   ```
3. Execute a interface gráfica:
   ```bash
   java ProdutoForm
   ```

---

## Objetivos Didáticos

- Compreender o uso prático de diagramas UML (classes e sequência)
- Aplicar a arquitetura orientada a objetos
- Trabalhar com persistência de dados
- Desenvolver interfaces gráficas com Swing

---

## Organização dos Arquivos

```
├───Descrições
├───Diagramas
│   ├───Diagramas Classe
│   ├───Diagramas Extra
│   └───Diagramas Sequencia
├───SistemaRestaurante
│   ├───build
│   │   └───classes
│   │       ├───Conexao
│   │       ├───dao
│   │       ├───model
│   │       └───sistema
│   ├───drivers
│   ├───nbproject
│   │   └───private
│   └───src
│       ├───Conexao
│       ├───dao
│       ├───model
│       └───sistema
└───SistemaRestauranteCliente
    ├───nbproject
    │   └───private
    └───src
        └───sistemarestaurantecliente
```

---

### Descrição dos Diretórios e Arquivos

- **`Item.java`**: Classe que representa o modelo de dados.
- **`Carrinho.java`**: Classe que representa o modelo de dados.
- **`ItemCarrinho.java`**: Classe que representa o modelo de dados.
- **`Pedido.java`**: Classe que representa o modelo de dados.

- **`CadastrarItem.form`**: Interface gráfica (Swing) para entrada de dados.
- **`EditarItem.form`**: Interface gráfica (Swing) para alteração de dados.
- **`ExcluirItem.form`**: Interface gráfica (Swing) para exclusão de dados.
  
- **`CarrinhoDAO.java`**: Responsável por salvar e carregar produtos do banco.
- **`ItemCarrinhoDAO.java`**: Responsável por salvar e carregar produtos do banco.
- **`ItemDAO.java`**: Responsável por salvar e carregar produtos do banco.
- **`PedidoDAO.java`**: Responsável por salvar e carregar produtos do banco.
  
- **`CadastrarItem.java`**: Interface gráfica (Swing) para entrada de dados.
- **`EditarItem.java`**: Interface gráfica (Swing) para alteração de dados.
- **`ExcluirItem.java`**: Interface gráfica (Swing) para exclusão de dados.
  
- **`Banco.txt`**: Arquivo onde os dados são persistidos.
- **`LICENSE`**: Arquivo de licença MIT.
- **`README.md`**: Este arquivo com instruções e explicações do projeto.

---


## Licença

Este projeto está licenciado sob os termos da licença MIT.  
Consulte o arquivo [LICENSE](LICENSE) para mais informações.

---

## Autores

**Luiz Miguel Toller Marconatto**  
**Eduardo Carvalho Ceretta**  
**Gabriel Machado Orling de Oliveira**  

Curso de Ciência da Computação – Universidade Franciscana (UFN)  

E-mail: luizmigueltoller@gmail.com  
GitHub: [@MiguelToller](https://github.com/MiguelToller)
