# Currency Converter (Laravel)

Este projeto é uma aplicação em Laravel que permite converter valores entre diferentes moedas, incluindo criptomoedas. A aplicação utiliza uma API externa para obter as cotações e as armazena em cache no Redis para otimizar o tráfego de rede e reduzir a dependência da API externa. O sistema permite adicionar novas moedas e configurar intervalos de atualização das cotações.

## Funcionalidades

- Conversão de moedas, incluindo criptomoedas (ex: Dólar para Euro, Bitcoin para Ethereum, etc.).
- Integração com API externa para obter cotações atualizadas.
- Cache das cotações utilizando Redis, com atualização periódica.
- Adição de novas moedas pelo usuário.
- Suporte a diferentes taxas de câmbio e personalizações.

## Tecnologias Utilizadas

- **Laravel** - Framework principal.
- **Redis** - Utilizado para armazenamento temporário das cotações.
- **API de Câmbio** - Integração com API externa para obter os valores atualizados.
- **Criptomoedas** - Suporte à conversão de moedas digitais.
  
## Requisitos

- PHP >= 8.1
- Composer
- Redis
- Laravel 10.x

