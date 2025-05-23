# 🧪 Laboratório Prático - Azure Speech e Language Studio

## 📝 Descrição
Este repositório contém anotações e experiências práticas com o uso do Azure Speech Studio e Language Studio, com o objetivo de explorar soluções baseadas em IA para voz e linguagem natural.

## 🎙️ Etapa 1: Azure Speech Studio

### 🎯 Objetivos
- Praticar funcionalidades de reconhecimento e geração de fala usando o Speech Studio.
- Avaliar a qualidade da transcrição e síntese de fala.

### 🛠️ Ferramentas Utilizadas
- Azure Speech Studio
- Azure Portal (para criação de recursos)

### ✅ O que foi feito
- Transcrição de áudio gravado (speech-to-text)
- Geração de fala a partir de texto (text-to-speech)
- Tradução de fala

### 💡 Insights
- O reconhecimento de fala em tempo real tem boa precisão, mesmo com sotaque regional.
- A geração de voz é extremamente natural, com várias opções de entonação.
- A tradução de fala pode ser útil para soluções multilíngues em tempo real.

### 🖼️ Capturas de Tela
Veja a pasta `/images` para exemplos visuais da prática.

| Etapa | Descrição | Imagem |
|-------|-----------|--------|
| 1     | Acesso ao Speech Studio | ![Acesso ao Speech Studio](images/etapa-1-speech-studio/01-acesso-speech-studio.png) |
| 2     | Criação e configuração do recurso Speech no Azure | ![Criação do recurso Speech](images/etapa-1-speech-studio/02-criacao-recurso-speech.png) |
| 3     | Interface da ferramenta de Conversão de Fala em Texto | ![Interface Speech to Text](images/etapa-1-speech-studio/03-interface-speech-to-text.png) |
| 4     | Teste com áudio de exemplo da Microsoft e transcrição precisa | ![Teste com áudio exemplo](images/etapa-1-speech-studio/04-audio-exemplo-microsoft.png) |
| 5     | Teste com áudio próprio sobre IA e transcrição precisa | ![Áudio próprio utilizado](images/etapa-1-speech-studio/05-audio-proprio-ia.png) |
| 6     | Acesso à ferramenta de Tradução de Fala no Speech Studio | ![Acesso à ferramenta de tradução](images/etapa-1-speech-studio/06-acesso-traducao.png) |
| 7     | Seleção dos idiomas: entrada em Português e saída em Inglês | ![Seleção de idiomas](images/etapa-1-speech-studio/07-selecao-idiomas.png) |
| 8     | Tradução bem-sucedida do áudio próprio sobre IA | ![Tradução realizada](images/etapa-1-speech-studio/08-traducao-realizada.png) |
| 9     | Acesso à Galeria de Serviço de Voz no Speech Studio | ![Acesso à galeria de voz](images/etapa-1-speech-studio/09-acesso-galeria-voz.png) |
| 10    | Escolha do idioma (Português) e da voz, com uso de texto sobre IA | ![Escolha de idioma e voz](images/etapa-1-speech-studio/10-escolha-idioma-voz.png) |
| 11    | Reprodução e geração de fala com qualidade e naturalidade | ![Geração da fala](images/etapa-1-speech-studio/11-geracao-fala.png) |

### ⚠️ Dica Importante
Após finalizar seus testes, **lembre-se de excluir o grupo de recursos criado no Azure** para evitar cobranças desnecessárias. Mesmo recursos gratuitos podem gerar custos se ultrapassarem os limites do plano gratuito.

---

## 🧠 Etapa 2: Azure Language Studio

### 🎯 Objetivos
- Explorar funcionalidades de análise de linguagem natural no Azure Language Studio.
- Praticar classificações de texto, análise de sentimentos, extração de entidades e linguagem personalizada.

### 🛠️ Ferramentas Utilizadas
- Azure Language Studio
- Azure Portal (mesmo grupo de recursos da Etapa 1)

### ✅ O que foi feito
- Análise de sentimentos em textos curtos e longos.
- Extração de entidades nomeadas (pessoas, locais, datas).
- Classificação de texto por categorias.
- Teste de modelos personalizados de linguagem (Custom Text Classification e NER).

### 💡 Insights
- A análise de sentimentos é útil para feedbacks de clientes e redes sociais.
- A extração de entidades permite organizar informações automaticamente.
- A criação de modelos personalizados exige planejamento, mas amplia o poder de análise da IA.

### 🖼️ Capturas de Tela
Veja a pasta `/images` para exemplos visuais da prática.

### ⚠️ Dica Importante
Se utilizar novos recursos para o Language Studio, lembre-se de que eles compartilham o grupo de recursos com a Etapa 1. Exclua o grupo ao final para evitar cobranças.

---

📌 Projeto desenvolvido como parte de um laboratório prático com foco em IA aplicada a voz e linguagem natural usando serviços do Microsoft Azure.
