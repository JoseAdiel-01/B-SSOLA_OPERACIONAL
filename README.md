# B-SSOLA_OPERACIONAL
Sistema IoT para monitoramento de condições ambientais e segurança ocupacional.
# 🧭 Bússola Operacional

### Sistema IoT para monitoramento de condições ambientais e segurança ocupacional.

## 📌 Sobre o projeto

A Bússola Operacional é um projeto acadêmico de Internet das Coisas (IoT) desenvolvido com o objetivo de monitorar condições ambientais em ambientes de trabalho, auxiliando na identificação de situações potencialmente perigosas e contribuindo para a segurança dos trabalhadores.

O sistema utiliza sensores conectados a um microcontrolador ESP32 para coletar informações ambientais e emitir alertas locais quando determinados parâmetros ultrapassam os limites estabelecidos.

## 🎯 Objetivo

Desenvolver uma solução tecnológica compacta, acessível e de baixo custo para monitoramento ambiental e identificação de possíveis riscos ocupacionais.

## 🔧 Tecnologias e componentes

### Hardware
- ESP32 DevKit
- Sensor BME280 – temperatura e umidade
- Sensor MQ-135 – qualidade do ar
- Sensor KY-037 – detecção de som
- Display OLED 0.96"
- LEDs indicadores
- Buzzer para alertas sonoros

### Software
- Python 3
- REST API
- Banco de dados
- HTML, CSS e JavaScript
- Arduino IDE

## ⚙️ Funcionamento

1. Os sensores realizam a coleta de dados ambientais.
2. O ESP32 processa as informações recebidas.
3. O sistema verifica os parâmetros monitorados.
4. Quando uma condição de alerta é identificada, são acionados os indicadores locais.
5. Os dados podem ser encaminhados para armazenamento e visualização por meio da arquitetura de comunicação do projeto.

## 🏗️ Arquitetura

ESP32 → REST API → Banco de Dados → Interface de Monitoramento

## 📊 Status do projeto

Em desenvolvimento.

## 🎓 Contexto acadêmico

Projeto desenvolvido no curso de Análise e Desenvolvimento de Sistemas.

## 👨‍💻 Desenvolvimento

Repositório destinado à documentação, implementação e evolução da Bússola Operacional.
