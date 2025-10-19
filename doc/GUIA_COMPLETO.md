# 🎯 GUIA RÁPIDO - Tabela da Vida

## ✨ NOVIDADES DA VERSÃO 2.1

### 🆕 O QUE MUDOU?

#### 1. **Modal WhatsApp Inteligente** 💚
Antes: Apenas abria WhatsApp sem número
Agora: 
- ✅ Modal bonito e interativo
- ✅ Código +55 (Brasil) já preenchido
- ✅ Você só digita: DDD + número
- ✅ Validação automática
- ✅ 5 mensagens variadas (nunca repete)

**Como usar:**
1. Clique em "💚 Mandar Mensagem Agora"
2. Digite apenas: 11987654321 (DDD + número)
3. Escolhe mensagem aleatória tocante
4. Abre WhatsApp direto com a mensagem pronta

#### 2. **Oráculo Expandido** 🔮
Antes: 8 mensagens
Agora: **20 MENSAGENS PROFUNDAS!**

Novas mensagens sobre:
- 💪 Coragem e medo
- 🌅 Recomeços
- 🧘 Solidão construtiva
- ⏰ Viver o presente
- 💎 Suas cicatrizes
- 🚫 Parar de se comparar
- ⭐ Sua importância
- 🎯 Onde gastar sua energia
- 🙏 Fé que move
- 🌱 Regar o que está vivo
- 🗣️ Poder das palavras
- ☮️ Paz interior

---

## 📱 COMO FUNCIONA O WHATSAPP

### Passo a Passo:

1. **Clique no botão verde** "💚 Mandar Mensagem Agora"

2. **Veja o modal aparecer** com:
   ```
   +55 [_____________]
        ↑
   Digite aqui: DDD + número
   ```

3. **Digite SÓ OS NÚMEROS**:
   - Exemplo 1: `11987654321` (São Paulo)
   - Exemplo 2: `21987654321` (Rio de Janeiro)
   - Exemplo 3: `85987654321` (Ceará)

4. **Clique em "✨ Enviar Mensagem de Amor"**

5. **WhatsApp abre com mensagem pronta!**

### ✅ Validações Automáticas:

- Não aceita letras (só números)
- Mínimo 10 dígitos (DDD + 8 ou 9 dígitos)
- Avisa se esquecer de digitar
- Avisa se número muito curto

### 💬 Mensagens Disponíveis (aleatórias):

**Mensagem 1:**
> "Hoje pensei em você... 💭
> 
> A vida é curta demais para não dizer isso: você é importante para mim. ❤️
> 
> Que tal conversarmos mais?"

**Mensagem 2:**
> "Oi! 😊
> 
> Eu estava refletindo sobre a vida e seu nome veio à minha mente.
> 
> Sabe aquelas pessoas que fazem diferença? Você é uma delas. 💛
> 
> Vamos nos falar mais?"

**Mensagem 3:**
> "Olá! 🌟
> 
> Quantos dias já se passaram desde nossa última conversa?
> 
> A vida é muito rápida... e eu não quero deixar passar mais tempo sem te dizer: você é especial para mim.
> 
> Podemos conversar?"

**Mensagem 4:**
> "Ei! 💫
> 
> Sabe aquele sentimento de saudade que bate do nada?
> 
> Então... tô sentindo agora. De você.
> 
> Bora colocar o papo em dia? ❤️"

**Mensagem 5:**
> "Fala! 🙏
> 
> Eu vi algo hoje que me fez perceber: a gente deixa o tempo passar e esquece de falar com quem importa.
> 
> Você importa. Muito.
> 
> Vamos nos reconectar?"

---

## 🔮 COMO FUNCIONA O ORÁCULO

### Passo a Passo:

1. **Clique em "🔮 Consultar o Oráculo da Alma"**

2. **Receba um número de 1 a 20** (aleatório)

3. **Leia:**
   - 💭 **Reflexão profunda** sobre a vida
   - 📖 **Versículo bíblico** relacionado
   - ✨ **Ação prática** para fazer AGORA

4. **Execute a ação sugerida!**

### 💡 Dica PRO:
Clique várias vezes! São 20 mensagens diferentes. 
Cada uma toca um aspecto diferente da sua alma.

---

## 🎨 ATALHOS DO TECLADO

- **Enter** no campo de idade → Calcula a vida
- **Enter** no campo do WhatsApp → Envia mensagem
- **Clique fora do modal** → Fecha o modal
- **×** (X no canto) → Fecha o modal

---

## 📊 ESTATÍSTICAS DO PROJETO

### Versão 2.1:
- ✅ 20 mensagens do oráculo (antes: 8)
- ✅ 5 mensagens WhatsApp variadas
- ✅ Modal interativo profissional
- ✅ Validação de telefone brasileira
- ✅ Código +55 automático
- ✅ Animações suaves
- ✅ Design glassmorphism

---

## 🆘 SOLUÇÃO DE PROBLEMAS

### ❓ "O oráculo não abre"
**Solução:** Verifique se o arquivo `oraculo.json` está na mesma pasta do `index.html`

### ❓ "WhatsApp não abre"
**Solução:** 
1. Verifique se digitou o número completo (DDD + telefone)
2. Certifique-se de que tem WhatsApp instalado
3. Permita pop-ups no navegador

### ❓ "As mensagens não aparecem"
**Solução:** 
1. Use um servidor local (não abra o HTML direto)
2. Execute: `python -m http.server 8000`
3. Acesse: `http://localhost:8000`

### ❓ "Modal não fecha"
**Solução:** 
1. Clique no × (X) no canto superior direito
2. Clique fora do modal (na parte escura)
3. Pressione ESC (se configurado)

---

## 🎯 PARA DESENVOLVEDORES

### Customizar Mensagens WhatsApp:

Edite no `index.html`, linha ~270:
```javascript
const mensagens = [
    "Sua mensagem aqui...",
    "Outra mensagem...",
];
```

### Adicionar Mais Mensagens ao Oráculo:

1. Abra `oraculo.json`
2. Adicione nova entrada:
```json
"21": {
    "reflexao": "Sua reflexão aqui...",
    "biblia": "Versículo aqui...",
    "acao": "Ação prática aqui..."
}
```
3. Atualize o número no JavaScript (linha ~320):
```javascript
const num = Math.floor(Math.random() * 21) + 1; // 21 mensagens
```

### Mudar País (+55 para outro):

Edite no `index.html`, linha ~475:
```html
<input type="text" class="country-code" value="+55" readonly>
```

E no JavaScript, linha ~305:
```javascript
const fullNumber = '55' + phoneNumber; // Mude o 55
```

---

## 💡 DICAS DE USO

1. **Compartilhe:** Envie para amigos que precisam refletir
2. **Use diariamente:** Consulte o oráculo toda manhã
3. **Aja imediatamente:** Não ignore as ações sugeridas
4. **Reconecte:** Mande mensagem para alguém HOJE
5. **Reflita:** Leia as mensagens de idade com atenção

---

## 🌟 PRÓXIMOS PASSOS

Futuras melhorias planejadas:
- [ ] Salvar histórico de oráculos consultados
- [ ] Sistema de favoritos para mensagens
- [ ] Modo escuro/claro
- [ ] Música ambiente relaxante
- [ ] Modo "Reflexão Total" (tela cheia)
- [ ] Compartilhamento social
- [ ] Tradução para outros idiomas

---

**Aproveite a experiência! Cada segundo importa.** ✨

---

_Versão 2.1 - Última atualização: 18/10/2025_
