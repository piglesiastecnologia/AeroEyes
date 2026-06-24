# Referências e Evolução de Estudo — AeroEyes

Este documento reúne referências utilizadas para apoiar a concepção do AeroEyes, especialmente nas decisões relacionadas a fatores humanos, carga cognitiva, HMI aeronáutica, interface adaptativa, decluttering e evolução futura do produto.

## Referências Centrais

### 1. Enhancing Safety and Workload Management in eVTOL Cockpits through the Assessment of Pilot’s Perception of HMI Models

**Autores:** Iyad Alomar, Azeem Shafqat
**Publicação:** Aviation, 2026, 30(1), 49–61
**DOI:** https://doi.org/10.3846/aviation.2026.26073

**Relação com o AeroEyes:**

Esta referência foi utilizada como base conceitual para pensar a interface do AeroEyes em um contexto de cockpit com alta carga cognitiva, especialmente em operações com piloto único e uso intensivo de sistemas de apoio à decisão.

O artigo contribuiu para as seguintes decisões do MVP:

* foco em workload management;
* valorização de interfaces “eyes-out”;
* uso de HUD/EFB como inspiração visual;
* importância da consciência situacional;
* cuidado com excesso de informação na interface;
* aplicação do conceito de decluttering;
* interesse futuro em interface adaptativa, multimodal e context-aware;
* uso de métricas relacionadas à carga cognitiva, como NASA-TLX.

No AeroEyes, esses conceitos foram traduzidos em uma interface de baixa fidelidade inspirada em EFB/HUD, com estados de monitoramento, alerta de atenção, alerta crítico e registro de evento.

## Referências Complementares

### 2. Additive Manufacturing in the Aerospace Industry

**Autores:** Lidong Wang, Reed Mosher, Patti Duett
**Publicação:** American Journal of Engineering and Applied Sciences, 2024
**DOI:** https://doi.org/10.3844/ajeassp.2024.116.125

**Relação com o AeroEyes:**

Esta referência não está diretamente ligada ao fluxo do MVP atual, mas foi considerada como material complementar para entendimento do ecossistema aeroespacial e de tendências de inovação na indústria.

O artigo contribui como referência de evolução futura ao discutir:

* inovação tecnológica no setor aeroespacial;
* prototipação e redução de lead time;
* aplicações avançadas em aviação;
* tendências de engenharia aplicada ao contexto aeronáutico;
* possibilidades futuras de integração entre software, hardware, sensores e prototipação física.

No contexto do AeroEyes, essa referência pode apoiar estudos futuros sobre evolução do produto para ambientes mais próximos de sistemas embarcados, simulações avançadas, dispositivos físicos ou protótipos integrados.

### 3. Detection of Driver Drowsiness by Calculating the Speed of Eye Blinking

**Autores:** Muhammad Fawwaz Yusri, Patrick Mangat, Oliver Wasenmüller  
**Publicação:** arXiv, 2021  
**Área:** Computer Vision and Pattern Recognition  
**DOI:** https://doi.org/10.48550/arXiv.2110.11223  
**Link:** https://arxiv.org/abs/2110.11223

**Relação com o AeroEyes:**

Esta referência é diretamente relacionada ao Incremento 1 do AeroEyes, especialmente à proposta de evolução para uma PoC experimental de eye-tracking.

O artigo apresenta uma abordagem de detecção de sonolência baseada na velocidade das piscadas, utilizando métricas derivadas do Eye Aspect Ratio e técnicas de visão computacional para identificação dos olhos. Essa ideia se conecta ao AeroEyes porque o produto também busca transformar sinais oculares em indicadores de atenção, fadiga ou risco de microsono em ambiente controlado.

A referência contribui para o AeroEyes nos seguintes pontos:

- fundamenta a possibilidade de usar sinais oculares como proxy para sonolência;
- apoia a ideia de capturar métricas como piscadas, fechamento ocular e fechamento prolongado;
- reforça a viabilidade de uma PoC com câmera/webcam antes de sensores especializados;
- inspira a classificação de estados como normal, atenção e crítico;
- sustenta a evolução do backlog para histórias relacionadas a eye-tracking experimental;
- evidencia limitações técnicas importantes, como perda de confiabilidade quando a face não está bem posicionada em relação à câmera;
- ajuda a justificar a necessidade de validação em ambiente controlado antes de qualquer aplicação operacional.

No AeroEyes, essa referência apoia principalmente as histórias futuras do Incremento 1, como PoC de integração com sensor de eye-tracking, classificação de severidade do alerta, histórico de eventos por simulação e privacidade no processamento dos dados capturados.

**Aplicação prática no produto:**

Enquanto o MVP atual trabalha com dados simulados, esta referência indica um possível caminho técnico para evoluir o AeroEyes em uma próxima etapa: capturar sinais oculares reais em uma PoC local, calcular métricas derivadas e transformar esses sinais em eventos de atenção/fadiga.

**Limitação considerada:**

A abordagem descrita no artigo depende de condições controladas de captura facial. Por isso, no AeroEyes, essa referência não é usada para afirmar eficácia operacional, mas sim para justificar uma etapa futura de prova de conceito técnica em ambiente controlado.

## Relação das Referências com a Evolução do Produto

As referências apoiam uma trilha de evolução do AeroEyes em três momentos:

### MVP atual

Validação da experiência e do fluxo crítico do piloto em ambiente simulado:

* calibração simulada;
* monitoramento de atenção;
* alerta visual;
* confirmação do alerta;
* registro básico do evento;
* wireframe EFB/HUD-inspired.

### Incremento 1

Evolução para uma PoC experimental de eye-tracking:

* captura experimental de sinais oculares;
* classificação de severidade;
* histórico de eventos por voo;
* painel operacional básico;
* privacidade e processamento local/controlado.

### Estudos futuros

Possíveis caminhos de pesquisa e evolução:

* avaliação com NASA-TLX;
* testes com usuários representativos;
* comparação entre diferentes modelos de HMI;
* estudos sobre confiança em automação;
* investigação de alertas multimodais;
* integração com simuladores de voo;
* evolução para sistemas context-aware;
* análise regulatória para uso operacional futuro.

## Observação

As referências foram utilizadas como apoio acadêmico e conceitual. O AeroEyes, nesta entrega, permanece como MVP de especificação e prototipação em ambiente simulado, sem integração real com cockpit, sensores reais, IA treinada ou certificação aeronáutica.
