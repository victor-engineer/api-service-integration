# api-service-integration
# CoinGecko API Integration

Este projeto demonstra como integrar a API pública do CoinGecko usando Java puro com a classe `HttpClient`, disponível a partir do Java 11.

## Visão Geral

O projeto consulta informações sobre criptomoedas utilizando a API do CoinGecko e exibe os dados em formato JSON.

## Tecnologias Utilizadas

- Java 11 ou superior
- API HTTP (`HttpClient`, `HttpRequest`, `HttpResponse`)

## Endpoints da API

A API CoinGecko fornece diversos endpoints para acessar dados sobre criptomoedas. Alguns dos endpoints utilizados neste projeto incluem:

- **Preço Simples de Criptomoedas:**
  ```plaintext
  https://api.coingecko.com/api/v3/simple/price?ids=bitcoin,ethereum&vs_currencies=usd

-**Lista completa de Criptomoedas**
https://api.coingecko.com/api/v3/coins/list

