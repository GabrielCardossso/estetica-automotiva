<img src="./.github/readme/header.svg" width="100%" alt="estetica-automotiva: Trabalho acadêmico · SENAC" />

<img src="./.github/readme/sobre.svg" width="100%" alt="Sobre o projeto: Sistema de agendamentos para uma estética automotiva, feito em Java e executado no terminal, para praticar os pilares de Programação Orientada a Objetos, com foco em encapsulamento e herança." />

<img src="./.github/readme/stack.svg" width="100%" alt="Stack: Java, POO, Terminal, JDK, Git, GitHub" />

<img src="./.github/readme/funcionalidades.svg" width="100%" alt="Funcionalidades: Cadastros (Clientes, funcionários, veículos e serviços, pelo menu de cadastros no terminal.); Agendamento de serviços (Liga cliente, veículo e serviço com data e horário, e permite concluir ou cancelar.); Listagens (Lista clientes, funcionários, veículos, serviços e agendamentos, com o status de cada agendamento.); Busca e remoção (Busca de clientes e veículos e remoção de qualquer cadastro.); Herança (Cliente e Funcionario herdam os dados comuns da classe pai Pessoa.); Encapsulamento (Atributos privados, acessados só por getters e setters.)" />

<img src="./.github/readme/estrutura.svg" width="100%" alt="Estrutura de pastas: src/ (todo o código Java), App.java (ponto de entrada + dados de exemplo), Gerenciamento.java (regras de negócio e menus), Pessoa.java (classe pai), Cliente.java (filha de Pessoa), Funcionario.java (filha de Pessoa), Veiculo.java (entidade do domínio), Servico.java (entidade do domínio), Agendamento.java (cliente + veículo + serviço), .gitignore (ignora bin/ e configs de IDE), README.md" />

<img src="./.github/readme/secao-01-modelagem.svg" width="100%" alt="Modelagem" />

| Classe | Papel |
| --- | --- |
| [`Pessoa`](src/Pessoa.java) | Classe pai com os dados comuns |
| [`Cliente`](src/Cliente.java) e [`Funcionario`](src/Funcionario.java) | Classes filhas de `Pessoa` (herança) |
| [`Veiculo`](src/Veiculo.java), [`Servico`](src/Servico.java) e [`Agendamento`](src/Agendamento.java) | Entidades do domínio |
| [`Gerenciamento`](src/Gerenciamento.java) | Regras de negócio e menus do sistema |
| [`App`](src/App.java) | Ponto de entrada, com dados de exemplo para teste |

Os atributos ficam privados e são acessados por getters e setters (encapsulamento).

<img src="./.github/readme/secao-02-como-executar.svg" width="100%" alt="Como executar" />

Com o JDK instalado, na raiz do projeto:

```bash
javac -d bin src/*.java
java -cp bin App
```

O sistema abre um menu no terminal. O `App` já carrega alguns dados de exemplo para você testar os cadastros, as listagens e os agendamentos sem começar do zero.

<a href="https://github.com/GabrielCardossso"><img src="./.github/readme/rodape.svg" width="100%" alt="Obrigado! Feito por Gabriel Cardoso" /></a>
