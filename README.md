# HTTP Server Simples

Este repositório é uma modificação do exemplo oficial [simple HTTP server](https://github.com/espressif/esp-idf/tree/v5.5/examples/protocols/http_server/simple) do ESP-IDF (versão 5.5).
Como requisito da seleção do Desafio Potiguar de Inovação em Automação e Eletrônica, foi adicionado no exemplo da Espressif uma página com um botão que muda de cor ao ser pressionado.

## Aviso de Licença

Este projeto inclui código proveniente do projeto ESP-IDF da Espressif Systems (licenciado sob a Apache License 2.0).
Modificações realizadas por Pedro Santos (2025).


## Como usar

1. Configure o ambiente ESP-IDF conforme a documentação oficial.
2. Compile o projeto:
```bash
   idf.py build
```   
Faça o flash no seu dispositivo:
```bash
idf.py -p PORT flash monitor
```
Substituindo PORT pela porta que seu ESP32 está conectado
Conecte-se à rede Wi-Fi configurada e acesse a URL adicionada no navegador para visualizar o botão.
