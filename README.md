# 🌸 Fluência Livre

Web app gratuito e responsivo voltado para o desenvolvimento da proficiência em inglês sem barreiras financeiras, reunindo trilhas temáticas, prática por habilidades, teste de nível e um tutor de IA contextual para estudos nas trilhas.

## ✨ Funcionalidades

- **💸Acesso gratuito e progresso local:** foco em quem busca evoluir no inglês no próprio ritmo, com persistência de preferências e progresso no navegador (`localStorage`) e fluxo de conta/login.
- **🗺️ Trilhas temáticas:**
  - 💬 *Fluência do dia a dia*
  - 💻 *Business & Tech/Dev*
  - ✈️ *Viagem e turismo*
  - 🎓 *Acadêmico, provas e proficiência*
- **🎧 Prática por habilidades:** atividades interativas em **Listening**, **Speaking**, **Reading** e **Writing** com apoio de áudio via Web Speech API (com fallback seguro), transcrição alternável e verificação de tentativas.
- **📝 Teste de proficiência:** avaliação de nível com bloqueio automático do assistente de IA enquanto o teste estiver ativo, preservando a integridade da medição.
- **🤖 Tutor de IA nas trilhas:** assistente flutuante no canto da tela para tirar dúvidas de vocabulário, traduções no contexto da lição e dicas durante os exercícios (desabilitado durante o teste).
- **🎨 Interface e acessibilidade:** visual claro com detalhes em rosa, suporte a modo escuro (`dark mode`), modal de configurações e ícones vetoriais (SVG).

## 📁 Estrutura do projeto

- `fluencia-livre.html` — Protótipo/aplicação web responsiva com interface, filtros, trilhas, teste e tutor de IA.
- Backend / Frontend modular (quando integrado à arquitetura completa): rotas e componentes para trilhas, lições, avaliação de proficiência e assistente.

## 🚀 Como executar localmente

1. Clone ou baixe o repositório:
   ```bash
   git clone [https://github.com/SEU-USUARIO/fluencia-livre.git](https://github.com/SEU-USUARIO/fluencia-livre.git)
   cd fluencia-livre
