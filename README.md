# AeroEyes — MVP Sprint 2 PUC-Rio

Este repositório reúne os artefatos da entrega do MVP da Sprint 2 da pós-graduação em Engenharia de Software da PUC-Rio.

O projeto **AeroEyes** é uma proposta de produto para apoio à segurança operacional em aviação, focada na identificação e comunicação de sinais de fadiga do piloto em ambiente simulado. O MVP tem como objetivo validar a experiência de uso, a clareza dos alertas e a organização do backlog ágil, sem integração real com cockpit, sensores reais ou operação aeronáutica produtiva.

## Objetivo do MVP

Validar, em ambiente simulado/controlado, se uma interface inspirada em EFB/HUD consegue apoiar o piloto na percepção de sinais de fadiga por meio de:

* calibração biométrica simulada;
* monitoramento de atenção com dados simulados;
* alerta visual de fadiga;
* confirmação do alerta pelo piloto;
* registro básico do evento;
* wireframes do fluxo crítico do piloto.

## Escopo

### O que o MVP faz

* Representa o fluxo principal do piloto em uma interface EFB/HUD-inspired.
* Simula a calibração e o monitoramento de atenção.
* Exibe alertas visuais de fadiga em estados de atenção e crítico.
* Permite confirmação do alerta ou indicação de falso positivo.
* Registra o evento de forma simplificada.
* Demonstra o conceito de decluttering para redução de carga cognitiva.

### O que o MVP não faz

* Não integra com cockpit real.
* Não utiliza sensor real de eye-tracking.
* Não possui modelo de IA treinado.
* Não realiza operação aeronáutica real.
* Não armazena dados biométricos reais.
* Não representa produto certificado para uso operacional.

## Artefatos da Entrega

A estrutura principal do repositório é:

```text
AeroEyes/
├── canvas-url.txt
├── product-backlog.pdf
├── sprint-backlog.pdf
└── wireframes/
    ├── 01 - Pre-flight Calibration.png
    ├── 01B - Calibration Complete.png
    ├── 02 - Normal Monitoring.png
    ├── 03 - Attention Alert.png
    ├── 04 - Critical Alert.png
    ├── 05A - Event Registered - Confirmed.png
    ├── 05B - Event Registered - False Positive.png
    └── links-figma.txt
```

## Lean Inception

O arquivo `canvas-url.txt` contém o link para o board da Lean Inception no Miro.

A Lean Inception foi utilizada para estruturar:

* visão do produto;
* definição do que é / não é / faz / não faz;
* objetivos do produto;
* personas;
* jornadas de usuários;
* brainstorming de features;
* revisão técnica, de negócio e UX;
* sequencer;
* MVP Canvas;
* glossário do domínio.

## Product Backlog

O arquivo `product-backlog.pdf` apresenta o backlog do produto, contendo:

* épicos;
* user stories;
* prioridades;
* story points;
* critérios de aceitação;
* Definition of Ready;
* Definition of Done;
* requisitos não funcionais;
* enablers de governança, segurança e privacidade.

O backlog contempla o MVP inicial e também o planejamento do Incremento 1, voltado para uma futura PoC de eye-tracking e painel operacional.

## Sprint Backlog

O arquivo `sprint-backlog.pdf` apresenta os itens selecionados para a Sprint 1.

A Sprint 1 foi planejada para validar o fluxo crítico do piloto:

1. Calibração biométrica simulada;
2. Monitoramento de atenção com dados simulados;
3. Alerta visual de fadiga;
4. Confirmação do alerta pelo piloto;
5. Registro básico do evento;
6. Wireframe do fluxo piloto no EFB.

## Wireframes

A pasta `wireframes/` contém as telas exportadas do protótipo criado no Figma.

O protótipo representa uma interface de baixa fidelidade, inspirada em EFB/HUD, com foco em:

* clareza visual;
* baixa sobrecarga cognitiva;
* alerta visual não intrusivo;
* decluttering em situação de fadiga;
* ação clara para confirmação do alerta;
* registro do evento simulado.

As telas principais são:

* **Pre-flight Calibration**: início da calibração simulada;
* **Calibration Complete**: baseline adquirido;
* **Normal Monitoring**: estado normal de monitoramento;
* **Attention Alert**: alerta de atenção/fadiga;
* **Critical Alert**: alerta crítico;
* **Event Registered - Confirmed**: evento confirmado pelo piloto;
* **Event Registered - False Positive**: evento marcado como falso positivo.

O arquivo `wireframes/links-figma.txt` contém o link para o protótipo no Figma.

## Requisitos Não Funcionais Considerados

O MVP considera requisitos não funcionais desde a especificação inicial, incluindo:

* privacidade;
* minimização de dados;
* uso de dados simulados;
* não armazenamento de dados biométricos reais;
* rastreabilidade mínima de eventos;
* clareza de alertas;
* redução de carga cognitiva;
* separação entre ambiente simulado e uso operacional real.

## Observação Acadêmica

Este projeto é um MVP acadêmico desenvolvido para a disciplina da Sprint 2 da pós-graduação em Engenharia de Software da PUC-Rio.

O AeroEyes, nesta entrega, não é um sistema embarcado real, não possui certificação aeronáutica e não deve ser utilizado em contexto operacional. O objetivo é validar a proposta de valor, a experiência de uso, o backlog ágil e a prototipação do fluxo crítico em ambiente simulado.

## Referências e Fundamentação

O AeroEyes foi inspirado por estudos relacionados a fatores humanos, carga cognitiva, interfaces adaptativas, segurança operacional e detecção de sonolência por sinais oculares.

As referências utilizadas apoiaram principalmente a definição da interface EFB/HUD-inspired, o conceito de decluttering, a priorização de alertas visuais, o uso de métricas de carga cognitiva e a evolução futura para uma PoC de eye-tracking baseada em métricas como piscadas, fechamento ocular e sinais de microsono.

As referências completas e a relação de cada uma com o produto estão documentadas no arquivo [`references.md`](./references.md).

## Autoria

Projeto desenvolvido por Pamela Iglesias como parte da pós-graduação em Engenharia de Software da PUC-Rio.
