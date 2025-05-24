# 🧪 Laboratório Prático - Azure Speech e Language Studio

## 📝 Descrição
Este repositório contém anotações e experiências práticas com o uso do Azure Speech Studio e Language Studio, com o objetivo de explorar soluções baseadas em IA para voz e linguagem natural.
O projeto foi dividido em **duas etapas**:  
- **Etapa 1 – Speech Studio:** exploração de recursos como conversão de fala em texto, tradução de fala em tempo real e geração de fala a partir de texto.  
- **Etapa 2 – Language Studio:** utilização de ferramentas para análise de sentimentos, extração de opiniões, classificação de texto e detecção de idioma.

## 🎙️ Etapa 1: Azure Speech Studio

## 🎯 Objetivos da Etapa
- Explorar e testar as principais funcionalidades do Azure Speech Studio:
  - Conversão de fala em texto (speech-to-text)
  - Tradução de fala em tempo real
  - Geração de fala a partir de texto (text-to-speech)

## 🛠️ Ferramentas Utilizadas
- Azure Speech Studio
- Microsoft Azure Portal
- Áudio de exemplo da Microsoft Learn
- Áudio próprio sobre Inteligência Artificial

### ✅ O que foi feito e Insights Obtidos
- Transcrição de áudios (speech-to-text)
- Geração de fala a partir de texto (text-to-speech)
- Tradução automática de fala entre idiomas  
➡️ [Ver insights detalhados](./insights/etapa-1-speech.md)

### 🖼️ Capturas de Tela
Na pasta `/images` etapa-1-speech-studio contém o passo a passo com prints para exemplos visuais da prática. conforme abaixo:

| Etapa | Descrição | Imagem |
|-------|-----------|--------|
| 1     | Acesso ao Speech Studio | ![Acesso ao Speech Studio](images/etapa-1-speech-studio/01-acesso-speech-studio.png) |
| 2     | Criação e configuração do recurso Speech no Azure | ![Criação do recurso Speech](images/etapa-1-speech-studio/02-criacao-recurso-speech.png) |
| 3     | Interface da ferramenta de Conversão de Fala em Texto | ![Interface Speech to Text](images/etapa-1-speech-studio/03-interface-speech-to-text.png) |
| 4     | Teste com áudio de exemplo da Microsoft e Resultado transcrição precisa | ![Teste com áudio exemplo](images/etapa-1-speech-studio/04-audio-exemplo-microsoft.png) |
| 5     | Teste com áudio próprio sobre IA e Resultado transcrição precisa | ![Áudio próprio utilizado](images/etapa-1-speech-studio/05-audio-proprio-ia.png) |
| 6     | Acesso à ferramenta de Tradução de Fala | ![Acesso à ferramenta de tradução](images/etapa-1-speech-studio/06-acesso-traducao.png) |
| 7     | Seleção dos idiomas: entrada em Português e saída em Inglês | ![Seleção de idiomas](images/etapa-1-speech-studio/07-selecao-idiomas.png) |
| 8     | Tradução bem-sucedida do áudio próprio sobre IA | ![Tradução realizada](images/etapa-1-speech-studio/08-traducao-realizada.png) |
| 9     | Acesso à Galeria de Serviço de Voz | ![Acesso à galeria de voz](images/etapa-1-speech-studio/09-acesso-galeria-voz.png) |
| 10    | Escolha do idioma (Português) e da voz, uso de texto sobre IA | ![Escolha de idioma e voz](images/etapa-1-speech-studio/10-escolha-idioma-voz.png) |
| 11    | Reprodução e geração de fala natural | ![Geração da fala](images/etapa-1-speech-studio/11-geracao-fala.png) 

---

## 🧠 Etapa 2: Azure Language Studio

## 🎯 Objetivos da Etapa
- Explorar funcionalidades do Azure Language Studio com foco em:
  - Análise de sentimentos
  - Análise de opiniões
  - Classificação de texto
  - Detecção de idioma

## 🛠️ Ferramentas Utilizadas
- Azure Language Studio
- Portal Azure (para criação e configuração dos recursos)
- Textos em português e inglês 

### ✅ O que foi feito
- Análise de sentimentos em diferentes contextos
- Classificação de opiniões com modelo pré-treinado
- Detecção de idioma com textos variados  
➡️ [Ver insights detalhados](./insights/etapa-2-language.md)

### 🖼️ Capturas de Tela
Na pasta `/images` etapa-2-language-studio contém o passo a passo com prints para exemplos visuais da prática. conforme abaixo:

| Etapa | Descrição                                                                                         | Imagem                                                                                             |
|-------|---------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------|
| 1     | Acesso ao Azure para criação do recurso de Serviço de Linguagem (IA + Machine Learning)          | ![Criação do Serviço de Linguagem](images/etapa-2-language-studio/01-criacao-servico-linguagem.png) |
| 2     | Seleção do grupo de recursos (mesmo da Etapa 1) e definição do nome                               | ![Grupo de Recursos e Nome](images/etapa-2-language-studio/02-grupo-nome-recurso.png)              |
| 3     | Acesso ao Language Studio e seleção do recurso criado no Azure                                    | ![Acesso ao Language Studio](images/etapa-2-language-studio/03-acesso-language-studio.png)         |
| 4     | Escolha da funcionalidade de Classificar Texto: Análise de Sentimentos e Extração de Opiniões | ![Escolha da Funcionalidade](images/etapa-2-language-studio/04-escolha-classificacao-texto.png)           |
| 5     | Análise de sentimento aplicada à opinião de um usuário (exemplo do Microsoft Learn)               | ![Análise de Sentimento](images/etapa-2-language-studio/05-analise-sentimento.png)                 |
| 6     | Resultado da classificação da opinião com análise detalhada do sentimento (modelo pré-treinado)   | ![Classificação de Opinião](images/etapa-2-language-studio/06-classificacao-opiniao.png)           |
| 7     | Acesso à funcionalidade de detecção de idioma                                                         | ![Funcionalidade de Detecção de Idioma](images/etapa-2-language-studio/07-acesso-deteccao-idioma.png)  |
| 8     | Teste de detecção de idioma com texto sobre IA (utilizado na Etapa 1)                             | ![Detecção de Idioma com Texto de IA](images/etapa-2-language-studio/08-teste-texto-ia.png)        |
| 9     | Resultado da detecção – idioma identificado corretamente como português                           | ![Resultado da Detecção](images/etapa-2-language-studio/09-resultado-deteccao.png)                 |

---

## 🔗 Links Úteis
- [Azure Speech Studio](https://speech.microsoft.com/) – Plataforma para testar e desenvolver soluções com reconhecimento de fala e conversão de texto.
- [Azure Language Studio](https://language.azure.com/) – Plataforma para análise de sentimentos, extração de opinião, classificação e tradução de texto.
- [Documentação Microsoft Learn](https://learn.microsoft.com/pt-br/training/) – Portal de aprendizagem da Microsoft com módulos e trilhas de capacitação.
- [Lab Speech no Microsoft Learn](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/09-speech.html) – Laboratório oficial sobre Azure Speech Studio.
- [Lab Text Analysis no Microsoft Learn](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/06-text-analysis.html) – Laboratório oficial sobre Azure Language Studio.

---

📌 Projeto desenvolvido como parte de um laboratório prático com foco em IA aplicada a voz e linguagem natural usando serviços do Microsoft Azure.
