# sistema-cadastro-veiculos-powerapps
Aplicativo feito no Power Apps para gerenciamento de cadastros de veículos 

# Sistema de Cadastro de Veículos — Power Apps

## Sobre o projeto

Este projeto foi desenvolvido como atividade acadêmica utilizando o Microsoft Power Apps. Seu objetivo é disponibilizar um aplicativo para cadastro de veículos, permitindo registrar suas principais informações, calcular o IPVA conforme a regra definida na aplicação e armazenar os dados no SharePoint.

## Funcionalidades

- Cadastro de veículos.
- Registro de RENAVAM e placa.
- Seleção de montadora e cor.
- Registro do ano de fabricação.
- Cadastro da descrição e do valor do veículo.
- Registro da data do seguro.
- Inclusão de foto do veículo.
- Cálculo automático do IPVA.
- Armazenamento dos dados na lista do SharePoint.
- Limpeza dos campos após o cadastro bem-sucedido.

## Tecnologias utilizadas

- **Microsoft Power Apps:** desenvolvimento da interface e da lógica da aplicação.
- **Microsoft SharePoint / Microsoft Lists:** armazenamento dos registros dos veículos.
- **Power Fx:** implementação das fórmulas, validações e cálculos.

## Demonstração do aplicativo

### 1. Tela principal

<!-- INSIRA AQUI O PRINT DA TELA PRINCIPAL DO APLICATIVO -->

*Figura 1 — Tela principal do sistema de cadastro de veículos.*

### 2. Cadastro e cálculo do IPVA

<img width="320" height="560" alt="image" src="https://github.com/user-attachments/assets/e0f74ff2-ec38-4b1c-801b-a8050469739c" />

### 3. Dados armazenados no SharePoint

<img width="1896" height="492" alt="image" src="https://github.com/user-attachments/assets/7b7daff2-2486-4187-b3dc-e79d30e3203b" />


*Figura 3 — Registro do veículo armazenado no SharePoint.*

## Acesso ao aplicativo

**Link para acessar o Power Apps:** https://make.powerapps.com/e/default-eabe64c5-68f5-4a76-8301-9577a679e449/canvas/?action=edit&app-id=%2Fproviders%2FMicrosoft.PowerApps%2Fapps%2F37586d5e-3a11-4d9e-80b2-27a493f1552f

O acesso depende das permissões da conta Microsoft utilizada. Para visualizar e utilizar todas as funcionalidades, pode ser necessário ter acesso ao aplicativo e à lista do SharePoint vinculada a ele.

## Regra de cálculo do IPVA

O aplicativo utiliza a seguinte regra de cálculo:

- Veículos com ano de fabricação posterior a 2005: IPVA calculado em 4% do valor do veículo.
- Veículos fabricados até 2005: IPVA igual a zero, conforme a regra adotada no projeto.

**Fórmula aplicada:**

`IPVA = Valor do veículo × 0,04`

A fórmula é aplicada somente quando o ano de fabricação é superior a 2005.

## Objetivo acadêmico

O projeto tem como finalidade aplicar os conhecimentos desenvolvidos em aula sobre criação de aplicativos no Power Apps, manipulação de dados, integração com o SharePoint e implementação de regras de negócio por meio do Power Fx.

---

**Projeto desenvolvido para fins acadêmicos.**
