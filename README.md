# Binary Options API

## TODO: 
Este é um projeto modular e escalável em Java para integrar várias corretoras de trading, incluindo IQ Option, Quotex e Exnova. A plataforma suporta leitura de candlesticks, cálculo de indicadores, abertura e fechamento de ordens, persistência de dados históricos e operações em andamento, além de oferecer uma arquitetura moderna com Spring Boot.

## Estrutura do Projeto

Esboço da estrutura do projeto é organizada em vários módulos para facilitar a modularização, manutenção e escalabilidade.

```plaintext
trading-platform/
├── trading-core/
│   ├── src/main/java/com/yourcompany/trading/core/
│   └── src/test/java/com/yourcompany/trading/core/
├── iqoption-adapter/
│   ├── src/main/java/com/yourcompany/trading/iqoption/
│   └── src/test/java/com/yourcompany/trading/iqoption/
├── quotex-adapter/
│   ├── src/main/java/com/yourcompany/trading/quotex/
│   └── src/test/java/com/yourcompany/trading/quotex/
├── exnova-adapter/
│   ├── src/main/java/com/yourcompany/trading/exnova/
│   └── src/test/java/com/yourcompany/trading/exnova/
├── api-gateway/
│   ├── src/main/java/com/yourcompany/trading/apigateway/
│   └── src/test/java/com/yourcompany/trading/apigateway/
├── user-service/
│   ├── src/main/java/com/yourcompany/trading/userservice/
│   └── src/test/java/com/yourcompany/trading/userservice/
├── order-service/
│   ├── src/main/java/com/yourcompany/trading/orderservice/
│   └── src/test/java/com/yourcompany/trading/orderservice/
├── candlestick-service/
│   ├── src/main/java/com/yourcompany/trading/candlestickservice/
│   └── src/test/java/com/yourcompany/trading/candlestickservice/
├── common/
│   ├── src/main/java/com/yourcompany/trading/common/
│   └── src/test/java/com/yourcompany/trading/common/
├── docker-compose.yml
└── pom.xml
