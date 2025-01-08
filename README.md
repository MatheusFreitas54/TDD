# TDD com PHPUnit

Este repositório foi criado para praticar **Test-Driven Development (TDD)** utilizando **PHP**, **Composer** e **PHPUnit**, com o objetivo de aprimorar habilidades de desenvolvimento guiado por testes.

## Objetivo do Projeto

Explorar e praticar os princípios do **TDD**, incluindo:

- Escrever testes antes de implementar o código.
- Garantir que o código seja testável, sustentável e de fácil manutenção.
- Aprender a criar testes unitários e de integração com o PHPUnit.

Além disso, este projeto utiliza o **Composer** para gestão de dependências e **PHPUnit** para criar e executar testes automatizados.

---

## Estrutura do Projeto

A estrutura do projeto segue uma organização simples para práticas de TDD:

```plaintext
src/               # Código principal do projeto
tests/             # Testes automatizados com PHPUnit
composer.json      # Arquivo de dependências do Composer
```

---

## Requisitos

Antes de iniciar, certifique-se de que você tenha os seguintes softwares instalados:

- **PHP** (versão 8.0 ou superior)
- **Composer** (gestor de dependências do PHP)

### Instalação do Composer

Caso ainda não tenha o Composer instalado, siga as instruções no site oficial: [https://getcomposer.org/](https://getcomposer.org/)

---

## Configuração do Projeto

### Clonando o Repositório

Clone este repositório para sua máquina local:

```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio
```

### Instalando Dependências

Execute o seguinte comando para instalar as dependências:

```bash
composer install
```

---

## Testes

O projeto utiliza o **PHPUnit** para criar e rodar testes automatizados. Para executar os testes, use o comando:

```bash
vendor/bin/phpunit
```

Os arquivos de teste estão localizados na pasta `tests/`. Certifique-se de que todos os novos recursos desenvolvidos estejam devidamente cobertos por testes.

### Configuração do PHPUnit

O arquivo `phpunit.xml` contém as configurações para o PHPUnit. Caso necessário, edite-o para ajustar às necessidades do seu projeto.

---

## Conceitos Estudados

### Test-Driven Development (TDD)
- Escrever testes antes de implementar o código.
- Garantir que o código seja testável e sustentável.

### Composer
- Gestão de dependências
- Autoloading com PSR-4

### PHPUnit
- Criação de testes unitários e de integração
- Execução de testes e relatórios de cobertura

---