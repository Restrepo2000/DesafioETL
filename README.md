# Projeto de ETL - Geração de Cupons de Desconto

Este é um projeto simples de ETL (Extração, Transformação e Carregamento) para gerar cupons de desconto para usuários que fizeram mais de 10 compras em uma loja fictícia de roupas.

## Como Funciona

1. **Extração (E)**: Os dados dos usuários e suas compras são extraídos de um arquivo CSV usando a biblioteca pandas.

2. **Transformação (T)**: Usando a biblioteca random e string, são gerados cupons de desconto únicos para cada usuário que fez mais de 10 compras.

3. **Carregamento (L)**: Os cupons de desconto são carregados em um DataFrame pandas e salvos em um arquivo CSV.

## Pré-requisitos

- Python 3.x instalado
- Biblioteca pandas instalada (`pip install pandas`)

## Como Executar

1. Clone este repositório:

git clone https://github.com/Restrepo2000/DesafioETL.git

2. Navegue até o diretório do projeto:

cd DesafioETL

3. Execute o script principal:

python etl_cupons_desconto.py

4. Verifique se o arquivo `cupons_mais_10.csv` foi gerado com sucesso.

## Personalização

- Você pode personalizar as mensagens de cupons de desconto no arquivo `etl_cupons_desconto.py`.
- Certifique-se de ajustar os nomes dos arquivos e formatos de armazenamento conforme necessário.

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para enviar pull requests ou relatar problemas.

