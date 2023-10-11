# Santander Dev Week 2023 - Amazon Books

## Descrição do Projeto

Este projeto foi desenvolvido durante a Santander Dev Week 2023. O objetivo é criar mensagens de marketing personalizadas para clientes da Amazon que compraram livros relacionados à ciência de dados no último ano, usando a API do ChatGPT (OpenAI).

O projeto segue o processo ETL (Extract, Transform, Load):

- **Extract**: Extraímos a lista de IDs de usuário a partir de um arquivo CSV. Para cada ID, fazemos uma requisição GET para obter os dados do usuário correspondente.
- **Transform**: Utilizamos a API do OpenAI do CHAT-GPT para gerar uma mensagem de marketing personalizada para cada usuário.
- **Load**: Criamos uma nova coluna chamada "mensagens" na tabela de dados. A coluna contém as mensagens personalizadas para cada cliente.

## Como executar o projeto

1. Clone este repositório.
2. Abra o arquivo `SantanderDevWeek2023_AmazonBooks.ipynb` no Google Colab.
3. Execute todas as células.
   **obs: A chave API criada não está mais ativa**
4. A tabela contento todas as mensagens personalizadas está incluida no repositório em formato xlsm e csv

## Dependências

Este projeto requer:

- Python
- Pandas
- OpenAI
- Google Colab

## Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## Autor

Laís Maranhão

## Contato

Se você tiver alguma dúvida sobre este projeto, sinta-se à vontade para entrar em contato comigo: laiiss@live.com

## Contribuições

Contribuições são sempre bem-vindas!
 
