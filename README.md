# 🅿️ ParkEasy – Sistema de Controle de Estacionamento

> Sistema completo de gerenciamento de estacionamento desenvolvido em Java com Programação Orientada a Objetos.

---

## 📋 Sobre o Projeto

O **ParkEasy** é um sistema de controle de estacionamento desenvolvido como projeto de estudo e aplicação de conceitos de **Programação Orientada a Objetos (POO)** em Java. O sistema permite o gerenciamento completo do fluxo de veículos em um estacionamento, desde o cadastro até o cálculo automático de tarifas.

**Status:** ✅ Concluído &nbsp;|&nbsp; **Data de conclusão:** 25/03/2025

---

## ✨ Funcionalidades

- 🚗 **Cadastro de Veículos** – Registro de placa, modelo, marca e dados do proprietário (nome e CPF)
- 🕐 **Controle de Entrada e Saída** – Registro automático com carimbo de data/hora
- 💰 **Cálculo de Tarifas** – Cálculo automático do valor da estadia com base no tempo de permanência
- 🔍 **Pesquisa por Placa** – Listagem e consulta de veículos atualmente estacionados
- 📊 **Relatório de Receita** – Geração da receita total acumulada com formatação monetária

---

## 🏗️ Modelagem de Classes

```
├── Proprietario.java   # Dados do dono do veículo (nome e CPF)
├── Veiculo.java        # Dados do veículo (placa, modelo, marca) + referência ao Proprietário
└── Controle.java       # Lógica principal: entradas, saídas, cálculos e relatórios
```

### Diagrama de Relacionamento

```
Proprietario
    └── (composição) ──▶ Veiculo
                              └── (gerenciado por) ──▶ Controle
```

### Conceitos de POO Aplicados

| Conceito | Aplicação |
|---|---|
| **Encapsulamento** | Atributos privados com getters/setters em todas as classes |
| **Composição** | `Veiculo` contém um objeto `Proprietario` |
| **Abstração** | Separação clara de responsabilidades entre as classes |
| **Reutilização** | Métodos modulares e reutilizáveis na classe `Controle` |

---

## 🚀 Como Executar

### Pré-requisitos

- Java JDK 8 ou superior
- Terminal / IDE de sua preferência (IntelliJ, Eclipse, VS Code)

### Passos

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/parkeasy.git

# Acesse o diretório
cd parkeasy

# Compile os arquivos
javac *.java

# Execute o programa
java Main
```

---

## 🛠️ Tecnologias Utilizadas

- **Linguagem:** Java
- **Paradigma:** Programação Orientada a Objetos (POO)
- **Ferramentas:** JDK, IDE Java

---

## 📚 Aprendizados

Este projeto foi desenvolvido com foco no domínio prático dos pilares da POO:

- Estruturação de sistemas com múltiplas classes interdependentes
- Aplicação de encapsulamento para proteger a integridade dos dados
- Manipulação de coleções para controle de estado do sistema
- Formatação de saídas monetárias e temporais em Java
# 🅿️ ParkEasy – Sistema de Controle de Estacionamento

> Sistema completo de gerenciamento de estacionamento desenvolvido em Java com Programação Orientada a Objetos.

---

## 📋 Sobre o Projeto

O **ParkEasy** é um sistema de controle de estacionamento desenvolvido como projeto de estudo e aplicação de conceitos de **Programação Orientada a Objetos (POO)** em Java. O sistema permite o gerenciamento completo do fluxo de veículos em um estacionamento, desde o cadastro até o cálculo automático de tarifas.

**Status:** ✅ Concluído &nbsp;|&nbsp; **Data de conclusão:** 25/03/2025

---

## ✨ Funcionalidades

- 🚗 **Cadastro de Veículos** – Registro de placa, modelo, marca e dados do proprietário (nome e CPF)
- 🕐 **Controle de Entrada e Saída** – Registro automático com carimbo de data/hora
- 💰 **Cálculo de Tarifas** – Cálculo automático do valor da estadia com base no tempo de permanência
- 🔍 **Pesquisa por Placa** – Listagem e consulta de veículos atualmente estacionados
- 📊 **Relatório de Receita** – Geração da receita total acumulada com formatação monetária

---

## 🏗️ Modelagem de Classes

```
├── Proprietario.java   # Dados do dono do veículo (nome e CPF)
├── Veiculo.java        # Dados do veículo (placa, modelo, marca) + referência ao Proprietário
└── Controle.java       # Lógica principal: entradas, saídas, cálculos e relatórios
```

### Diagrama de Relacionamento

```
Proprietario
    └── (composição) ──▶ Veiculo
                              └── (gerenciado por) ──▶ Controle
```

### Conceitos de POO Aplicados

| Conceito | Aplicação |
|---|---|
| **Encapsulamento** | Atributos privados com getters/setters em todas as classes |
| **Composição** | `Veiculo` contém um objeto `Proprietario` |
| **Abstração** | Separação clara de responsabilidades entre as classes |
| **Reutilização** | Métodos modulares e reutilizáveis na classe `Controle` |

---

## 🚀 Como Executar

### Pré-requisitos

- Java JDK 8 ou superior
- Terminal / IDE de sua preferência (IntelliJ, Eclipse, VS Code)

### Passos

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/parkeasy.git

# Acesse o diretório
cd parkeasy

# Compile os arquivos
javac *.java

# Execute o programa
java Main
```

---

## 🛠️ Tecnologias Utilizadas

- **Linguagem:** Java
- **Paradigma:** Programação Orientada a Objetos (POO)
- **Ferramentas:** JDK, IDE Java

---

## 📚 Aprendizados

Este projeto foi desenvolvido com foco no domínio prático dos pilares da POO:

- Estruturação de sistemas com múltiplas classes interdependentes
- Aplicação de encapsulamento para proteger a integridade dos dados
- Manipulação de coleções para controle de estado do sistema
- Formatação de saídas monetárias e temporais em Java

---

