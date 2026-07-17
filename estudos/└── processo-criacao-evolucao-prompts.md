# Processo de Criação e Evolução de Prompts

## Objetivo

Este fluxo representa minha abordagem de aprendizado e experimentação em Engenharia de Prompts.

A proposta é demonstrar as etapas utilizadas desde a compreensão da necessidade até a avaliação, melhoria e evolução dos resultados gerados pela Inteligência Artificial.

O processo envolve:

- Entendimento do objetivo;
- Definição de contexto;
- Escolha da técnica adequada;
- Criação do prompt;
- Avaliação dos resultados;
- Ajustes e evolução contínua.

---

## Fluxo de Aprendizado e Evolução na Criação de Prompts

```mermaid
flowchart TD

A[Início do estudo] --> B[Entender o objetivo da solicitação]

B --> C[Definir o contexto necessário]

C --> D[Escolher a abordagem do prompt]

D --> E{Aplicar técnica estudada}

E --> F[Método CLARO]
E --> G[Zero-Shot]
E --> H[Uso de Personas]

F --> I[Criar primeira versão do prompt]
G --> I
H --> I

I --> J[Testar prompt utilizando IA]

J --> K[Avaliar resposta gerada]

K --> L{Resultado atende ao objetivo?}

L -->|Não| M[Identificar pontos de melhoria]

M --> N[Ajustar prompt]

N --> J

L -->|Sim| O[Registrar aprendizado]

O --> P[Documentar processo e evolução]

P --> Q[Aplicar conhecimento em novos cenários]
