# nvidianemoguardrails-microsoftfoundry-otel-jaeger-dockercompose
Scripts do Docker Compose para subida de um ambiente de testes do NVIDIA NeMo Guardrails com capacidade de AI Gateway. Inclui monitoramento/geração de traces com Jaeger + OpenTelemetry, com implementação de guardrails evitando menções a termos políticos. IA testada: Microsoft Foundry.

Saiba mais sobre o projeto open source NVIDIA NeMo Guardrails em: **https://github.com/NVIDIA-NeMo/Guardrails**

## Testes

Para os testes aqui descritos foram configurados guardrails a fim de evitar menções a termos políticos.

Envio de uma requisição de uma requisição inválida via REST Client no Visual Studio Code:

![Requisição inválida no VS Code](img/01-req-invalida.png)