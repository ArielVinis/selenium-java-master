# Selenium: Testes Automatizados de Aceitação em Java

## Sobre o Projeto

Este repositório contém a implementação de testes automatizados de aceitação utilizando Selenium e Java. O projeto foi desenvolvido como parte do curso "Selenium: testes automatizados de aceitação em Java" da Alura.

🔗 **Repositório:** [selenium-java-master](https://github.com/ArielVinis/selenium-java-master)

## Objetivos

- Entender o que é o Selenium e sua aplicação em testes de aceitação (end-to-end/UI).
- Desenvolver testes automatizados para uma aplicação de leilões previamente desenvolvida.
- Aplicar boas práticas na escrita de testes, como o uso de Page Objects.
- Aprender a configurar o Selenium em um projeto Maven.
- Executar testes automatizados utilizando o ChromeDriver e outros navegadores compatíveis.

## Tecnologias Utilizadas

- **Java**: Linguagem principal para os testes.
- **Selenium WebDriver**: Para automação de interação com a interface da aplicação.
- **JUnit**: Framework para execução dos testes.
- **Maven**: Gerenciamento de dependências e build do projeto.
- **ChromeDriver**: Driver utilizado para interação com o navegador Chrome.

## Funcionalidades Testadas

Os testes foram desenvolvidos para validar funcionalidades essenciais da aplicação de leilões, incluindo:

- **Login**: Testes para autenticação de usuários.
- **Cadastro de Leilão**: Validação da criação de novos leilões.
- **Lances em Leilões**: Garantia do funcionamento correto do processo de lances.
- **Regra de Lances**: Validação para impedir que um mesmo usuário insira dois lances consecutivos.

## Estrutura do Projeto

O projeto segue o padrão de Page Objects, garantindo um código mais organizado e reutilizável:

```
selenium-java-master/
├── src/
│   ├── main/java/pages/        # Page Objects
│   ├── test/java/tests/        # Testes automatizados
│   ├── resources/              # Recursos auxiliares
│
├── pom.xml                     # Configuração do Maven
└── README.md                    # Documentação do projeto
```

## Como Executar os Testes

1. **Clone o repositório:**
   ```sh
   git clone https://github.com/ArielVinis/selenium-java-master.git
   cd selenium-java-master
   ```

2. **Instale as dependências:**
   ```sh
   mvn clean install
   ```

3. **Execute os testes:**
   ```sh
   mvn test
   ```

## Considerações Finais

Este projeto foi uma excelente oportunidade para aprender e aplicar testes de aceitação com Selenium, proporcionando maior confiabilidade ao software. O desenvolvimento dos testes continuará, conforme novas funcionalidades forem adicionadas à aplicação.

📌 **Sugestões e contribuições são bem-vindas!** Sinta-se à vontade para abrir uma issue ou enviar um pull request. 🚀
