# 🩺 Sistema de Triagem Médica Automatizada

## Descrição

Este projeto é um sistema simples de triagem médica desenvolvido em Python, que classifica automaticamente a gravidade da condição de um paciente com base nos sintomas relatados e sinais vitais fornecidos (temperatura, pressão arterial e frequência cardíaca). O objetivo é auxiliar no direcionamento inicial do atendimento, priorizando casos mais urgentes. O sistema inclui validações de entrada para garantir a integridade dos dados inseridos.

## Funcionalidades

- **Triagem urgente**: Identifica emergências com sintomas críticos e sinaliza para procura imediata de atendimento médico.
- **Triagem moderada**: Detecta sintomas menos graves que exigem acompanhamento médico, mas não urgência.
- **Triagem leve**: Classifica condições leves que, embora não urgentes, devem ser avaliadas por um médico.
- **Validação de entradas**: Garante que os dados inseridos, como temperatura, pressão arterial e frequência cardíaca, estejam dentro de intervalos realistas e válidos.

## Como Usar

1. Clone este repositório para sua máquina local:
    ```bash
    git clone https://github.com/seu-usuario/nome-do-repositorio.git
    ```

2. Acesse o diretório do projeto:
    ```bash
    cd nome-do-repositorio
    ```

3. Execute o script Python para iniciar o sistema de triagem:
    ```bash
    python triagem.py
    ```

4. O sistema pedirá para você inserir os sintomas e sinais vitais do paciente. Após a entrada dos dados, o sistema fornecerá uma classificação de triagem.

## Requisitos

- Python 3.x
- Nenhuma dependência externa necessária

## Exemplo de Execução

```bash
Sistema de Triagem de Emergência

Selecione os sintomas, separados por vírgulas (digite os números):
1. Dor no peito
2. Falta de ar
3. Dor abdominal
4. Sangramento
5. Desmaio
6. Confusão mental
7. Febre alta
8. Dor de cabeça intensa
9. Dificuldade para falar
10. Dor nas costas
11. Dor nas articulações
12. Vômito
13. Diarreia

Digite os números dos sintomas escolhidos: 1, 3, 7

Agora, informe os sinais vitais do paciente:
Temperatura (°C): 38.5
Pressão arterial sistólica (ex: 120): 110
Frequência cardíaca (bpm): 100

Sinais vitais do paciente:
Sintomas: Dor no peito, Dor abdominal, Febre alta
Temperatura: 38.5°C
Pressão arterial: 110 mmHg
Frequência cardíaca: 100 bpm

Classificação de triagem: Moderado - Precisa de médico, mas não é urgente.
