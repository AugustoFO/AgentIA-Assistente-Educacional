
# 🧠 Assistente Educacional com Gemini e Google ADK

Este projeto é um **agente educacional inteligente, empático e gratuito**, criado com a API Gemini (Google) e a SDK do Google ADK. Ele funciona como um tutor pessoal para estudantes que desejam se preparar para o ENEM, vestibulares, concursos ou apenas organizar melhor seus estudos.

---

## 🌍 Por que este projeto foi criado?

O Brasil enfrenta profundas desigualdades educacionais. Muitos estudantes não têm acesso a professores particulares, cursinhos pagos ou acompanhamento escolar de qualidade. Este assistente foi idealizado como uma **forma de democratizar o acesso à educação de qualidade**, utilizando inteligência artificial para orientar qualquer pessoa, gratuitamente, com empatia e eficiência.

---

## 💡 Funcionalidades

O agente educacional oferece:

1. **Coleta de Perfil do Estudante**  
   Com perguntas acolhedoras, entende suas dificuldades, preferências e metas de estudo.

2. **Plano de Estudos Automatizado e Personalizado**  
   Monta um plano adequado à realidade e disponibilidade do estudante. Divide por semanas/dias úteis sem sobrecarregar.

3. **Geração de Questões com Feedback Didático**  
   Cria questões sobre os temas desejados, aguarda a resposta e só depois apresenta o gabarito com explicações.

4. **Interação Empática e Proativa**  
   Se o estudante estiver perdido ou inseguro, o agente toma a iniciativa de sugerir caminhos e perguntas de apoio.

5. **Acompanhamento com Contexto**  
   O agente entende e mantém o histórico da conversa para oferecer orientações mais precisas.

6. **Despedida Natural e Motivadora**  
   Ao final, se despede com mensagens positivas e incentivo aos estudos.

---

## ▶️ Como usar

### 1. Requisitos

- Conta no [Google Colab](https://colab.research.google.com/)
- API Key da [Google Generative AI](https://ai.google.dev/)
- Python 3.10+ (no ambiente local) ou rodar diretamente no Colab

### 2. Passo a passo

1. Clone ou acesse o notebook do projeto.
2. Instale as bibliotecas necessárias (o notebook já faz isso automaticamente):
   ```python
   %pip install google-genai google-adk
   ```
3. Defina sua chave de API do Google:
   ```python
   os.environ["GOOGLE_API_KEY"] = SUA_CHAVE_AQUI
   ```
4. Execute o notebook ou script. O agente iniciará com uma saudação e já estará pronto para conversar.

---

## 💬 Exemplos de interação

- "Não sei por onde começar. Me ajuda?"
- "Tenho só 2 horas por dia, quero estudar para o ENEM"
- "Quero questões sobre ecologia"
- "Pode montar um plano de estudos de 3 semanas com foco em matemática?"

---

## ⚙️ Tecnologias utilizadas

- [Google Gemini API (genai)](https://ai.google.dev/)
- [Google ADK (Agent Development Kit)](https://github.com/google/adk)
- Python 3
- Google Colab (ou ambiente local)
- Markdown para formatação das respostas

---

## 🤝 Contribuições

Sugestões, melhorias e colaborações são muito bem-vindas. Vamos juntos tornar o acesso à educação mais justo e acessível para todos!

---

## 📜 Licença

Este projeto está sob a licença MIT.

