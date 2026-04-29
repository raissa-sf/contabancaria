# 🏦 Banco do Brazil com Z 

<br />

<div align="center">
  <img src="https://img.shields.io/github/languages/top/raissa-sf/contabancaria?style=flat-square" />
  <img src="https://img.shields.io/github/repo-size/raissa-sf/contabancaria?style=flat-square" />
  <img src="https://img.shields.io/github/languages/count/raissa-sf/contabancaria?style=flat-square" />
  <img src="https://img.shields.io/github/last-commit/raissa-sf/contabancaria?style=flat-square" />
</div>


------


## 2. Arquitetura do Sistema

O projeto está estruturado com as seguintes **Classes** e **Interfaces**, cada uma com responsabilidades bem definidas:

| Classe / Interface | Descrição |
| :--- | :--- |
| **Menu** | Classe principal da aplicação. Contém o método `main` e é responsável por exibir o menu inicial com todas as funcionalidades do sistema. |
| **Cores** | Classe utilitária usada para aplicar cores ao menu, melhorando a experiência visual no terminal. |
| **Conta** | Classe base (Abstrata) que define a estrutura genérica e atributos de uma conta bancária. |
| **ContaCorrente** | Classe que estende `Conta` e representa uma conta corrente, com suas características específicas como o limite. |
| **ContaPoupanca** | Classe que estende `Conta` e representa uma conta poupança, incluindo o atributo de aniversário da conta. |
| **ContaRepository** | Interface que declara o contrato de métodos que devem ser implementados para a manipulação das contas. |
| **ContaController** | Classe que implementa a interface `ContaRepository`, contendo toda a lógica de negócio e manipulação dos dados. |


## 3. Requisitos

Para executar os códigos localmente, você precisará de:

- [Java JDK 21](https://www.oracle.com/br/java/technologies/downloads/#jdk21)
- [STS (Spring Tool Suite)](https://spring.io/tools)


## 4. Como Executar os projetos no STS

### 4.1. Importando os Projetos

1. Abra o STS e selecione a pasta do Workspace onde você clonou o repositório.
2. No menu superior do STS, clique na opção: File 🡲 Import...
3. Na janela Import, selecione a opção: General 🡲 Existing Projects into Workspace e clique no botão Next.
4. Na janela Import Projects, no item Select root directory, clique no botão Browse... e selecione a pasta onde você clonou o projeto.
5. O STS reconhecerá automaticamente o projeto.
6. Clique no botão Finish para concluir a importação.


### 4.2. Executando um projeto Java

1. Na guia Package Explorer, localize o projeto.
2. Abra a Classe Menu.java.
3. Clique no botão Run  para executar a aplicação.
4. Caso seja perguntado qual é o tipo do projeto, selecione a opção Java Application.
5. O console exibirá a aplicação.



## Contribuições

Este repositório é parte de um projeto educacional, mas contribuições são sempre bem-vindas! Caso tenha sugestões de novas funcionalidades ou correções na lógica bancária, sinta-se à vontade para:

- Criar uma **issue** para relatar bugs ou sugerir melhorias.
- Enviar um **pull request** com suas alterações de código.
- Compartilhar o projeto com colegas que estejam aprendendo Java!

**Como contribuir:**

1. Faça um **Fork** do projeto.
2. Crie uma **Branch** para sua modificação (`git checkout -b feature/NovaFuncionalidade`).
3. Dê um **Commit** nas suas alterações (`git commit -m 'Adiciona nova funcionalidade'`).
4. Faça um **Push** para a sua Branch (`git push origin feature/NovaFuncionalidade`).
5. Abra um **Pull Request** para análise.



## Contato

Desenvolvido por **Raissa Santos Feitosa** Para dúvidas, sugestões ou colaborações, entre em contato através dos canais abaixo:

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/raissa-santos-feitosa-73485b1a3/)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/raissa-sf)

---
*Sinta-se à vontade para abrir uma **issue** caso encontre algo que possa ser melhorado!*