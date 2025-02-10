# OCR CNH

Este projeto demonstra a utilização do **AWS Textract** para extração de dados da **Carteira Nacional de Habilitação (CNH)**. O objetivo é exemplificar como processar imagens de documentos e extrair informações textuais de forma automatizada.

---

## Pré-requisitos

Antes de executar o projeto, certifique-se de que os seguintes requisitos estão atendidos:

- **Python** (versão 3.x recomendada)
- **UV** (gerenciador de pacotes Python)
- **Conta AWS** com acesso ao serviço **Textract**

---

## Configuração do Ambiente

### 1. Configuração do IAM na AWS
Para utilizar o AWS Textract, é necessário configurar um usuário no **IAM** com permissões adequadas. Siga os passos abaixo:

1. Acesse o console da AWS e navegue até o serviço **IAM**.
2. Crie um novo usuário e atribua a política **AmazonTextractFullAccess**.
3. Gere as credenciais de acesso (Access Key e Secret Key) e configure-as no seu ambiente local.

### 2. Configuração do Projeto
Clone este repositório e instale as dependências necessárias.

---

## Instalação

Para instalar as dependências do projeto, execute o seguinte comando:

```bash
uv install
