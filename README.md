# 📊 Análise de Sentimentos com Azure AI Language Studio

Este repositório contém a prática realizada no desafio da DIO sobre **Análise de Sentimentos** utilizando o **Azure Language Studio**.  
Por questões de custos, utilizei **simulação de cenários** em vez de execução completa no ambiente pago.  
A documentação reflete fielmente os passos que seriam realizados e os possíveis resultados obtidos.

---

## 🎯 Objetivos do Desafio

- Explorar os serviços de **IA do Azure** voltados para linguagem natural.  
- Compreender como funciona a **análise de sentimentos** em textos.  
- Documentar de forma clara e organizada os passos realizados.  
- Publicar no GitHub como material de apoio para estudos futuros.  

---

## 🛠️ Ferramentas Utilizadas

- **Azure Language Studio**  
- **Azure Speech Studio / Speech Playground**  
- **Azure Portal**  
- **GitHub**  

*(Ferramentas utilizadas em modo de simulação/documentação, sem consumo de recursos pagos.)*

---

## 🚀 Passos Simulados (com base nos labs oficiais)

1. Acessar o [Azure Portal](https://portal.azure.com/) e/ou o site do Azure AI Foundry.  
2. Criar um recurso de **Language Service / Azure AI Services** configurado para capacidades de linguagem natural (por exemplo: análise de sentimentos, extração de entidades, etc.).  
3. No playground do **Speech**: uso do serviço de transcrição em tempo real com upload de arquivos de áudio (como no lab “Explore Speech” – aka.ms/ai900-speech). :contentReference[oaicite:0]{index=0}  
4. No playground de **Language / Text Analytics**: uso de funções como análise de sentimentos, extração de entidades, extração de frases-chave, sumarização de textos (conforme lab “Analyze Text” – aka.ms/ai900-text-analysis). :contentReference[oaicite:1]{index=1}  
5. Inserção de frases de teste para análise de sentimentos.  
6. Interpretação dos resultados exibidos pelo modelo de IA para cada frase.

---

## 📝 Exemplos de Teste

- Entrada: `"Estou muito feliz com o resultado do projeto!"`  
  Resultado: **Positivo (score: 0.95)** ✅  

- Entrada: `"Esse atraso no sistema me deixou frustrado."`  
  Resultado: **Negativo (score: 0.88)** ❌  

- Entrada: `"A entrega foi feita no prazo, mas poderia ter sido melhor."`  
  Resultado: **Neutro (score: 0.63)** ⚖️  

*(Os scores representam a confiança da IA no sentimento detectado.)*

---

## 📚 Recursos Oficiais Consultados

- Lab “Explore Speech in Azure AI Foundry portal” ([aka.ms/ai900-speech](https://aka.ms/ai900-speech)) — transcrição de fala em tempo real, upload de áudio, uso do Speech Playground. :contentReference[oaicite:2]{index=2}  
- Lab “Analyze Text in Azure AI Foundry portal” ([aka.ms/ai900-text-analysis](https://aka.ms/ai900-text-analysis)) — análise de texto com funcionalidades de sentimento, extração de entidade, frase-chave e sumarização. :contentReference[oaicite:3]{index=3}  

---

## 📊 Possíveis Aplicações Reais

- **Monitoramento de redes sociais**: identificar sentimentos sobre marcas/produtos.  
- **Atendimento ao cliente**: entender a satisfação em tempo real.  
- **Chatbots inteligentes**: responder de acordo com o tom emocional do usuário.  
- **Análise de feedbacks**: otimizar produtos/serviços a partir das opiniões coletadas.  

---

## 📚 Insights Pessoais

- A união entre **Speech → Texto** (como no lab de speech) e **Texto → Sentimento / Análise Semântica** (como no lab de text analysis) abre possibilidades gigantes para uso prático: atendimento automático, transcrição de reuniões, análise de áudio de vídeo, etc.  
- Mesmo em simulação, percebi que escolher bons exemplos de texto (frases com emoção clara) ajuda a entender onde o modelo pode falhar (ex: sarcasmo, frases neutras com conotação).  
- A documentação do Azure + os labs oficiais são excelentes referências para montar projetos reais – vale sim salvar prints dessas páginas ou até baixar materiais públicos para justificar.

---

## 👨‍💻 Autor

- **Anderson Moisés da Silva de Oliveira**  
- Estudante de **Análise e Desenvolvimento de Sistemas (ADS)**  
- Participante da **Trilha .NET + Azure AI** pela [DIO](https://www.dio.me/)  

---
