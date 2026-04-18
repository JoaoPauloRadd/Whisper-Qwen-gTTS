# Whisper-Qwen-gTTS

Integração de ferramentas de IA para capturar áudio, transcrever fala, processar o conteúdo com IA generativa e sintetizar a resposta em voz.  
Este projeto foi desenvolvido como solução inspirada no desafio do **Bootcamp Bradesco na DIO de GenAI & Dados**:  
https://www.dio.me/bootcamp/bradesco-genai-dados

## Executar no Google Colab

Acesse o notebook do projeto pelo link abaixo:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1rTLiti0G71pZmM-kNefjBPs5cxzPK3GR?usp=sharing)

## Sobre o projeto

Este repositório apresenta uma solução de IA multimodal focada em interação por voz. A proposta é integrar diferentes etapas de processamento para permitir uma experiência mais natural de comunicação entre usuário e modelo generativo:

- captura de áudio;
- transcrição da fala em texto;
- envio do conteúdo para um modelo de IA generativa;
- geração da resposta textual;
- conversão da resposta em áudio.

Na prática, o fluxo une tecnologias de **Speech-to-Text** e **Text-to-Speech**, permitindo construir aplicações capazes de compreender comandos falados e devolver respostas por voz, inclusive em diferentes idiomas.

## Contexto do desafio

A proposta original do desafio da DIO é aplicar, na prática, conceitos de IA generativa, transcrição de fala e síntese de voz para construir uma solução funcional e relevante para portfólio.

Inspirado nesse cenário, este projeto demonstra como combinar ferramentas modernas para criar um pipeline de conversa por voz com IA. A ideia central é mostrar como serviços e bibliotecas especializadas podem atuar em conjunto para transformar áudio em texto, interpretar o conteúdo com um modelo generativo e devolver a resposta em formato sonoro.

Além de reproduzir o laboratório proposto, a iniciativa também busca adaptar e evoluir a solução para um contexto mais atual, explorando novas combinações de modelos e bibliotecas open source.

## Tecnologias utilizadas

Este projeto utiliza, entre outras ferramentas:

- **Whisper** para transcrição de áudio;
- **Qwen** como modelo de IA generativa para processamento textual;
- **gTTS** para síntese de voz;
- **Python** como linguagem principal;
- **Google Colab** como ambiente de experimentação e execução.

## Objetivo

O objetivo deste projeto é demonstrar, de forma prática, como construir uma aplicação simples de IA conversacional por voz, integrando múltiplas etapas de processamento em um único fluxo.

Além disso, o projeto também serve como material de estudo e portfólio para aprofundar conhecimentos em:

- IA generativa;
- processamento de linguagem natural;
- reconhecimento de fala;
- síntese de voz;
- integração de bibliotecas Python em ambiente Colab.

## Referência do desafio

O desafio que inspirou este projeto explora o desenvolvimento de sistemas que unem **Speech-to-Text** e **Text-to-Speech**, possibilitando conversas por voz com suporte multilíngue.  
Na proposta original, o uso do **Whisper** permite transcrição e tradução de fala, enquanto um modelo generativo interpreta as entradas e produz respostas. Por fim, a integração com o **Google Text-to-Speech (gTTS)** adiciona a etapa de vocalização da resposta.

Essa abordagem abre espaço para diversas aplicações, como assistentes virtuais, acessibilidade, automação de atendimento e experiências conversacionais interativas.

## Materiais de apoio

- **Bootcamp Bradesco na DIO de GenAI & Dados**:  
  https://www.dio.me/bootcamp/bradesco-genai-dados

- **Notebook no Google Colab**:  
  https://colab.research.google.com/drive/1rTLiti0G71pZmM-kNefjBPs5cxzPK3GR?usp=sharing

## Observações

Este projeto tem fins educacionais e demonstrativos, com foco em aprendizado, prática de integração entre ferramentas de IA e fortalecimento de portfólio técnico.
