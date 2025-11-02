# 🤖 AURORA AI - System Prompt para Roblox

<div align="center">

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Open Source](https://img.shields.io/badge/Open%20Source-💚-green)](https://github.com/JokaGameTV/aurora-ai-roblox)
[![YouTube](https://img.shields.io/badge/YouTube-@JokaGameTV-red?logo=youtube)](https://youtube.com/@JokaGameTV)

**Aprenda a criar jogos Roblox usando ChatGPT!**

[📥 Download Prompt](SYSTEM_PROMPT_GPT.md) • [📺 Tutoriais](https://youtube.com/@JokaGameTV) • [💬 Discord](https://discord.gg/YNcChkrBsV) • [📱 TikTok](https://tiktok.com/@JokaGameTV)

</div>

---

## 🎯 O que é AURORA AI?

**AURORA** é uma mentora de IA especializada em ensinar crianças e iniciantes a criar jogos no Roblox Studio usando ChatGPT.

### ✨ Features

- 🎓 **Didática:** Explica como se você nunca tivesse programado antes
- 💻 **Código Completo:** Sem placeholders ou "TODO"
- 🐛 **Troubleshooting:** Ajuda com erros comuns
- 🎬 **Otimizado para vídeos:** Respostas concisas e diretas
- 🛡️ **Seguro:** Conteúdo apropriado para crianças 8+
- 🆓 **Gratuito:** MIT License - use livremente!

---

## 🚀 Início Rápido

### Método 1: Copiar e Colar (Recomendado para iniciantes)

1. **Baixe** o arquivo [`SYSTEM_PROMPT_GPT.md`](SYSTEM_PROMPT_GPT.md)
2. **Abra** no Bloco de Notas
3. **Copie TUDO** (Ctrl+A → Ctrl+C)
4. Abra uma **nova conversa** no [ChatGPT](https://chat.openai.com)
5. **Cole** (Ctrl+V) e envie
6. Aguarde: `AURORA AI ATIVADA ✅`

### Método 2: Custom GPT (Mais conveniente)

1. Acesse: [chat.openai.com/gpts/editor](https://chat.openai.com/gpts/editor)
2. Clique em **"Create a GPT"**
3. Copie o conteúdo de [`SYSTEM_PROMPT_GPT.md`](SYSTEM_PROMPT_GPT.md)
4. Cole em **"Instructions"**
5. **Nome:** "AURORA - Roblox Game Dev"
6. **Descrição:** "Mentora para criar jogos Roblox - JokaGameTV"
7. Salve e use sempre que quiser!

**Vantagem:** Não precisa copiar/colar toda vez!

---

## 🎮 O que você vai criar

Seguindo a **Série 1**, você vai construir um jogo de Roleplay completo com:

- ✅ Sistema de moedas
- ✅ Emprego de entregador de pizza
- ✅ Sistema de casas (3 tipos)
- ✅ Interface visual (HUD + Botões)
- ✅ Sistema de pontos de entrega

**Tempo:** 2-4 horas do zero ao jogo jogável!

---

## 📺 Tutoriais

Acompanhe a série completa no YouTube:

### 🟢 Série 1 - Iniciante
**ChatGPT + Roblox Studio** (esta série)
- Sistema de moedas e economia
- Empregos e recompensas
- Interface visual completa
- Jogo funcional e jogável

### 🟡 Série 2 - Intermediário *(em breve)*
**Claude Code + MCP + Criação 3D**
- Desenvolvimento 10x mais rápido
- Criação 3D em tempo real
- Mapas completos automatizados

### 🔴 Série 3 - Avançado *(em breve)*
**Integrações com APIs**
- NPCs com IA conversacional
- Vozes realistas (ElevenLabs)
- Economia dinâmica (Google Sheets)

**Canal:** [@JokaGameTV](https://youtube.com/@JokaGameTV)

---

## 🤝 Como Usar

### Exemplo de primeira pergunta:
```
AURORA, cria o sistema de moedas para meu jogo
```

### AURORA vai responder com:
1. **Contexto:** Explicação do que será criado
2. **Código Completo:** Lua comentado e funcional
3. **Explicação Didática:** O que cada parte faz
4. **Onde Colocar:** Instruções exatas no Roblox Studio
5. **Como Testar:** Passo a passo para validar
6. **Erros Comuns:** Problemas típicos e soluções

---

## 🐛 Problemas Comuns

### "RemoteEvent is not a valid member"
**Causa:** RemoteEvent não foi criado ainda
**Solução:** Verificar se pasta RemoteEvents existe em ReplicatedStorage e usar :WaitForChild()

### "Economy is not a valid member"
**Causa:** ModuleScript no lugar errado ou nome incorreto
**Solução:** Verificar se Economy.lua está em ReplicatedStorage/Modules com nome EXATO

### Interface não aparece
**Causa:** ClientInit não está em StarterPlayerScripts
**Solução:** Deve ser LocalScript (não Script) em StarterPlayerScripts

### Moedas não atualizam
**Causa:** Leaderstats não foi criado
**Solução:** Verificar função InitializePlayer em Economy.lua e checar Output (F9)

### Mais ajuda?
💬 Entre no nosso [Discord](https://discord.gg/YNcChkrBsV)

---

## 🌟 Showcase

Criou um jogo usando AURORA? Compartilhe!

1. 🎮 Publique no Roblox
2. 📸 Tire screenshots/vídeo
3. 🔗 Compartilhe nas redes com **#AuroraAI #JokaGameTV**
4. ⭐ Dê uma star neste repo!

**Galeria de projetos:** [Issues #showcase](https://github.com/JokaGameTV/aurora-ai-roblox/issues?q=label%3Ashowcase)

---

## 🤝 Contribuindo

Quer melhorar a AURORA?

1. 🍴 Fork este repositório
2. 🔧 Faça suas melhorias no `SYSTEM_PROMPT_GPT.md`
3. ✅ Teste no ChatGPT
4. 📬 Envie um Pull Request
5. 💚 Agradecemos sua contribuição!

**Issues e sugestões são sempre bem-vindas!**

### Ideias para contribuir:
- 🐛 Reportar bugs/erros no prompt
- 💡 Sugerir novos exemplos de código
- 📚 Adicionar mais troubleshooting
- 🌍 Traduzir para outros idiomas
- 🎨 Melhorar explicações didáticas

---

## 📜 Licença

**MIT License** - Copyright (c) 2025 JokaGameTV

✅ Pode usar em seus vídeos/cursos
✅ Pode modificar para suas necessidades
✅ Pode distribuir para seus alunos
✅ Pode criar Custom GPT
✅ Não precisa pedir permissão

📝 Pedimos apenas que mencione os créditos:
*"System Prompt AURORA AI criado por JokaGameTV"*

---

## 🔗 Links

### 📺 JokaGameTV
- **YouTube:** [@JokaGameTV](https://youtube.com/@JokaGameTV)
- **TikTok:** [@JokaGameTV](https://tiktok.com/@JokaGameTV)
- **GitHub:** [github.com/jokagametv](https://github.com/jokagametv)
- **Discord:** [discord.gg/YNcChkrBsV](https://discord.gg/YNcChkrBsV)

### 📁 Recursos
- **System Prompt:** [SYSTEM_PROMPT_GPT.md](SYSTEM_PROMPT_GPT.md)
- **Issues/Suporte:** [GitHub Issues](https://github.com/JokaGameTV/aurora-ai-roblox/issues)
- **Discussões:** [GitHub Discussions](https://github.com/JokaGameTV/aurora-ai-roblox/discussions)

### 📚 Documentação
- **Tutorial Completo:** Veja no YouTube [@JokaGameTV](https://youtube.com/@JokaGameTV)
- **Série 2:** *(em breve)*
- **Série 3:** *(em breve)*

---

## 💚 Agradecimentos

**Obrigado por usar a AURORA AI!**

Este prompt foi criado com muito carinho para democratizar o ensino de programação. Se te ajudou:

1. ⭐ Dê uma estrela neste repositório
2. 📺 Inscreva-se no [JokaGameTV](https://youtube.com/@JokaGameTV)
3. 💬 Compartilhe com amigos
4. 🎮 Publique seu jogo no Roblox!

**Vamos juntos formar a próxima geração de desenvolvedores de jogos!** 🚀

---

<div align="center">

**Desenvolvido com 💚 por JokaGameTV**

[⭐ Star](https://github.com/JokaGameTV/aurora-ai-roblox) • [🐛 Issues](https://github.com/JokaGameTV/aurora-ai-roblox/issues) • [💡 Discussions](https://github.com/JokaGameTV/aurora-ai-roblox/discussions)

```
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
   🤖 AURORA AI v2.1 | Criado com 💚 por JokaGameTV
   📺 YouTube & TikTok: @JokaGameTV
   🆓 Open Source (MIT) | 🌟 Compartilhe Livremente!
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

</div>
