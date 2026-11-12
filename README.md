# ⚖️ Fatos Jurídicos - Blog Jurídico Automatizado & Captação de Leads

> **Projeto em produção:** [fatosjuridicos.com.br](https://fatosjuridicos.com.br/)

O **Fatos Jurídicos** é um portal criado para esclarecer dúvidas comuns sobre o direito civil, trabalhista e do consumidor, traduzindo termos técnicos em uma linguagem simples e acessível. 

Além de entregar conteúdo educativo, a plataforma foi estruturada estrategicamente para converter leitores que se identificam com os problemas abordados em potenciais clientes por meio de contato direto via WhatsApp.

---

## 🛠️ Tecnologias e Ferramentas

- **Hospedagem:** Hostinger
- **CMS / Gestão de Conteúdo:** WordPress
- **Linguagens:** PHP (base do WordPress), CSS (estilização e responsividade), HTML e JavaScript (interações de tela e gatilhos de contato)
- **Modelos de Inteligência Artificial:** Claude (Anthropic) e Google AI Studio (Gemini)
- **Orquestração de Automações:** n8n
- **Canal de Atendimento e Conversão:** WhatsApp

---

## ⚙️ Arquitetura do Projeto

### 1. Portal de Conteúdo (WordPress)
- Interface leve, rápida e otimizada para leitura em dispositivos móveis.
- Ajustes finos de layout feitos em **CSS** para destacar as mensagens importantes.

### 2. Automação de Produção de Artigos (n8n + IA)
- **Ideação e Estruturação:** Utilização do **Claude** e do **Google AI Studio (Gemini)** para pesquisa de temas recorrentes e redação humanizada, evitando jargões jurídicos pesados.
- **Fluxo com n8n:** Criação da rotina automatizada que conecta os modelos de IA à API do WordPress, agendando e publicando novos artigos periodicamente sem intervenção manual.

### 3. Atendimento e Atração de Leads
- O tráfego do blog é direcionado para o WhatsApp nos momentos em que o leitor mais sente a dor descrita no artigo.
- Preparação de base para um agente conversacional de triagem automática no canal de mensagens.

---

## 📌 Status do Projeto e Próximos Passos

- [x] Registro e publicação do domínio oficial (`fatosjuridicos.com.br`)
- [x] Configuração da hospedagem na Hostinger e instalação do WordPress
- [x] Ajustes de layout e estilização personalizada com CSS
- [x] Implementação de chamada para ação (CTA) com link direto para o WhatsApp
- [ ] Construção do fluxo no n8n para agendamento de publicações
- [ ] Integração das chaves de API do Claude e Gemini com o n8n
- [ ] Desenvolvimento de um agente de IA para atendimento prévio das dores dos clientes no WhatsApp

---

## 📁 Estrutura deste Repositório

- `/prompts`: Arquivos contendo as instruções e diretrizes refinadas utilizadas nas IAs (Claude e Gemini) para geração de conteúdo jurídico seguro e didático.
- `/n8n-workflows`: Arquivos `.json` exportados com os nós e rotinas do n8n (adicionados conforme o desenvolvimento do fluxo).
