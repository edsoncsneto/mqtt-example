# Setup para o arquivo app_main.c

### Configure as variáveis:
broker.address.uri

broker.address.port

credentials.username

credentials.authentication.password

## Criação do broker (sugestão):
HiveMQ: https://console.hivemq.cloud/

Crie o usuário, senha e o tópico /ifpe/ads/embarcados/esp32/led

## Na extensão do ESP-IDF Explorer
Como configurar extensão (https://github.com/espressif/vscode-esp-idf-extension)

Na extensão, acesse o menu de configuração em SDK Configuration Editor (menuconfig) e defina o SSID e password da rede wi-fi

## Teste
Envie mensagem 1 nesse tópico para ligar o led, e mensagem 0 para apagar
