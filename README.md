# 🚗 Estética Automotiva

Sistema de **agendamentos para uma estética automotiva**, feito em Java e executado no terminal. Foi desenvolvido para praticar os pilares de **Programação Orientada a Objetos**, com foco em encapsulamento e herança.

> Trabalho acadêmico do curso **Técnico em Desenvolvimento de Sistemas** do SENAC.

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)

## Funcionalidades

- Cadastro de clientes, funcionários, veículos e serviços
- Agendamento de serviços, com conclusão e cancelamento
- Listagens de clientes, funcionários, veículos, serviços e agendamentos
- Busca de clientes e veículos
- Remoção de cadastros

## Modelagem

| Classe | Papel |
| --- | --- |
| `Pessoa` | Classe pai com os dados comuns |
| `Cliente` e `Funcionario` | Classes filhas de `Pessoa` (herança) |
| `Veiculo`, `Servico` e `Agendamento` | Entidades do domínio |
| `Gerenciamento` | Regras de negócio e menus do sistema |
| `App` | Ponto de entrada, com dados de exemplo para teste |

Os atributos ficam privados e são acessados por getters e setters (encapsulamento).

## Como executar

Com o JDK instalado, na raiz do projeto:

```bash
javac -d bin src/*.java
java -cp bin App
```
