## 🛒 Lista de Compras

Projeto desenvolvido em C# como exercício da Academia do Programador, com foco em Programação Orientada a Objetos, CRUD em console, validações e relacionamento entre entidades.

O sistema simula uma aplicação de organização de compras domésticas, permitindo cadastrar categorias, produtos, listas de compras e itens vinculados às listas.

---

## 📌 Funcionalidades

### 📂 Módulo de Categorias
- Cadastrar categorias
- Editar categorias
- Excluir categorias
- Visualizar categorias
- Seleção de cor para categorias
- Validação de nomes duplicados

### 📦 Módulo de Produtos
- Cadastrar produtos
- Editar produtos
- Excluir produtos
- Visualizar produtos
- Relacionamento com categorias
- Preço aproximado por produto

### 🛍️ Módulo de Lista de Compras
- Criar listas de compras
- Editar listas
- Excluir listas
- Visualizar listas
- Status da lista (Aberta / Concluída)
- Data de criação automática
- Cálculo de total gasto

### 📋 Módulo de Itens da Lista
- Adicionar itens à lista
- Remover itens da lista
- Visualizar itens da lista
- Cálculo automático baseado em quantidade × preço

---

## 🧠 Conceitos Trabalhados

- Programação Orientada a Objetos
- Herança
- Classes Abstratas
- Encapsulamento
- Repositórios Genéricos
- Relacionamento entre entidades
- CRUD em Console
- Validações de domínio
- Generics
- Enum
- Organização em módulos
- Separação de responsabilidades

---

## 🏗️ Estrutura do Projeto

```txt
ListaDeCompras.ConsoleApp
│
├── Compartilhado
│   ├── EntidadeBase
│   ├── RepositorioBase
│   ├── TelaBase
│   ├── Interfaces
│
├── ModuloCategoria
│
├── ModuloProduto
│
├── ModuloListaCompras
│
├── Utilidades
│
└── Program.cs
```


## ▶️ Como Executar
**Pré-requisitos**
- .NET SDK instalado

**Clone o repositório**


```
git clone https://github.com/alexandrerocha15/Lista-de-Compras.git
```

**Execute o projeto**
```
dotnet run
```