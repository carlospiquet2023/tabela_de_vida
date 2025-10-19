# ⏳ Tabela da Vida

> **Uma experiência emocional e espiritual que transforma a maneira como você vê o tempo.**

![Projeto Tabela da Vida](https://img.shields.io/badge/Status-Completo-success)
![Versão](https://img.shields.io/badge/Versão-2.0-blue)
![Licença](https://img.shields.io/badge/Licença-MIT-green)

---

## 🌟 O Que É?

**Tabela da Vida** não é apenas um projeto web — é uma **jornada de reflexão profunda** sobre o tempo, propósito e a urgência de viver plenamente.

Inspirado na expectativa de vida média do brasileiro (75 anos), este projeto visualiza sua vida em **75 quadrados**, cada um representando um ano. Mas vai muito além: é uma experiência que combina:

- 📊 **Visualização da vida** em tempo real
- 💭 **Mensagens motivacionais personalizadas** por faixa etária
- 🔮 **Oráculo da Alma** com 8 mensagens profundas e passagens bíblicas
- 💬 **Integração com WhatsApp** para reconectar com quem você ama
- 🎨 **Design imersivo** com animações e partículas flutuantes
- 🎵 **Atmosfera contemplativa** que induz reflexão

---

## 🚀 Funcionalidades

### 1. **Visualização da Vida**
- Digite sua idade
- Veja quantos anos já viveu (quadrados vermelhos)
- Veja quantos anos te restam (quadrados verdes)
- Estatísticas precisas: anos vividos, anos restantes, porcentagem de vida

### 2. **Mensagens Personalizadas**
Cada faixa etária recebe uma mensagem única e impactante:

- **0-10 anos**: Mensagem de esperança e descoberta
- **11-20 anos**: Incentivo à ousadia e aprendizado
- **21-30 anos**: Alerta sobre decisões cruciais
- **31-40 anos**: Reflexão sobre a metade da vida
- **41-50 anos**: Urgência para não adiar sonhos
- **51-60 anos**: Alerta vermelho sobre o tempo
- **61-75 anos**: Mensagem intensa sobre aproveitar cada segundo

### 3. **🔮 Oráculo da Alma**
- **20 mensagens inspiradoras** que combinam:
  - Reflexões profundas sobre vida, dor, perdão e propósito
  - Passagens bíblicas cuidadosamente selecionadas
  - Ações práticas para você fazer AGORA

Exemplos de temas:
- Silêncio e introspecção
- Transformação através da dor
- Valor do tempo
- O poder do perdão
- Propósito de vida
- Amor incondicional
- Gratidão
- Força interior
- Coragem diante do medo
- Recomeços e novos caminhos
- Autoconhecimento
- Viver o presente
- E muito mais!

### 4. **💚 Reconexão Humana**
- Modal interativo para digitar número do WhatsApp
- Código do Brasil (+55) já preenchido automaticamente
- 5 mensagens variadas aleatórias
- Validação de número (DDD + telefone)
- Incentivo para falar com quem você ama HOJE

### 5. **Design Transformador**
- Gradiente animado de fundo
- 30 partículas flutuantes simulando estrelas
- Animações suaves em cada interação
- Cores que evocam emoções específicas
- Tipografia moderna (Google Fonts - Poppins)
- Totalmente responsivo (mobile-first)

---

## 📁 Estrutura do Projeto

```
Tabela_da_vida/
│
├── index.html              # Arquivo principal (HTML + CSS + JavaScript)
├── mensagens_idade.json    # Mensagens personalizadas por faixa etária
├── oraculo.json            # 8 mensagens do Oráculo da Alma
└── README.md               # Este arquivo
```

---

## 🛠️ Como Usar

### Opção 1: Abrir Diretamente
1. Baixe todos os arquivos para uma pasta
2. Abra o arquivo `index.html` no seu navegador
3. Pronto! O projeto funciona 100% offline

### Opção 2: Servidor Local (Recomendado)
Se você tiver problemas ao carregar os JSONs localmente, use um servidor local:

**Com Python:**
```bash
python -m http.server 8000
```

**Com Node.js (http-server):**
```bash
npx http-server
```

**Com VS Code:**
- Instale a extensão "Live Server"
- Clique com botão direito no `index.html`
- Selecione "Open with Live Server"

Depois acesse: `http://localhost:8000` (ou a porta que aparecer)

---

## 🎨 Paleta de Cores

| Cor | Hex | Uso |
|-----|-----|-----|
| Roxo Escuro | `#0f0c29` | Fundo principal |
| Roxo Médio | `#302b63` | Gradiente |
| Roxo Claro | `#24243e` | Detalhes |
| Vermelho | `#ff6b6b` | Anos vividos, urgência |
| Verde | `#2ed573` | Anos restantes, esperança |
| Amarelo | `#feca57` | Destaque, motivação |
| Azul | `#48dbfb` | Reflexões, perguntas |
| Roxo Vibrante | `#9b59b6` | Oráculo |
| Dourado | `#ffd700` | Versículos bíblicos |

---

## 💡 Tecnologias Utilizadas

- **HTML5**: Estrutura semântica
- **CSS3**: Animações, gradientes, backdrop-filter, grid/flexbox
- **JavaScript ES6+**: Fetch API, async/await, DOM manipulation
- **JSON**: Armazenamento de dados estruturados
- **Google Fonts**: Tipografia Poppins

---

## 🎯 Propósito do Projeto

Este projeto nasceu da ideia de que **alguém pode precisar dessas palavras**.

Vivemos numa sociedade que adia sonhos, que deixa para amanhã o que deveria ser feito hoje, que esquece de dizer "eu te amo" para quem importa.

**Tabela da Vida** é um lembrete visual e emocional de que:
- ⏰ O tempo é finito
- ❤️ As pessoas importam AGORA
- 🌱 Ainda há tempo para mudar
- 💪 Você é mais forte do que pensa
- 🙏 A vida tem propósito

---

## 🌈 Melhorias Futuras

Algumas ideias para evoluir o projeto:

- [ ] Adicionar música ambiente (piano instrumental suave)
- [ ] Modo "Reflexão Total" (tela escura, só a mensagem)
- [ ] Salvar progresso no localStorage
- [ ] Compartilhar resultados nas redes sociais
- [ ] Mais mensagens no oráculo (expandir para 12 ou 24)
- [ ] Adicionar metas de vida (bucket list interativa)
- [ ] Tradução para outros idiomas
- [ ] Versão PWA (Progressive Web App)
- [ ] Modo escuro/claro

---

## 🤝 Contribuições

Este é um projeto de código aberto. Se você quiser adicionar:
- Novas mensagens ao oráculo
- Melhorias de design
- Funcionalidades extras
- Correções

Sinta-se à vontade para fazer um fork e contribuir!

---

## 📜 Licença

Este projeto está sob a licença MIT. Sinta-se livre para usar, modificar e distribuir.

---

## 💬 Mensagem Final

> *"Você não está aqui por acaso. Cada batida do seu coração é um lembrete de que ainda há tempo para viver o que te faz vibrar."*

Se este projeto tocou você de alguma forma, **compartilhe**. Pode ser exatamente o que alguém precisa ouvir hoje.

---

**Desenvolvido com ❤️ para fazer você refletir, sentir e VIVER.**

🌟 **Viva cada segundo como se importasse. Porque importa.** 🌟
