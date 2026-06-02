
# PythonPayment

Projeto prático desenvolvido com o objetivo de aprimorar meus conhecimentos em **Python** e **Flask**, utilizando como base os conteúdos da **Rocketseat**. 

O sistema consiste em um fluxo básico de pagamentos via **Pix**, utilizando **SQLite** como banco de dados local para persistência rápida de informações.
## Tech Stack

* **Python**
* **Flask**
* **SQLite**
* **QRcode**
* **Pillow**

## Status

🚧 Em desenvolvimento / Inicial

## Installation

Como o projeto está em estágio inicial, os passos básicos para rodar localmente são:

### 1. Clonar o Repositório
```bash
git clone https://github.com/EuFontoura/PythonPayment.git
cd PythonPayment
```
### Instalar as dependências
```bash
pip install -r requirements.txt
```
### Iniciar o servidor localmente
```bash
flask run
```
O servidor estará rodando por padrão em http://127.0.0.1:5000/

## Como testar (API Endpoint)
Atualmente, o projeto possui um único método POST implementado. Você pode testá-lo utilizando ferramentas como Insomnia ou Postman.

### Criar Pagamento/Pix
**Método:** POST

**URL:** http://127.0.0.1:5000/payments/pix

**Corpo da Requisição (JSON):**
```bash
{
  "valor": 100.00
}
```
