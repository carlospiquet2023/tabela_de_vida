# 🎵 Sistema de Músicas Relaxantes

## 📍 Localização
**Canto Superior Direito** - Design discreto e elegante

## ✨ Características

### Loop Infinito ♾️
- As músicas tocam **continuamente** até você pausar
- Perfeito para relaxar enquanto usa o site
- Não há interrupções ou necessidade de reiniciar

### Carregamento Automático 🔄
O sistema **busca automaticamente** todas as músicas da pasta `musicas/`

### Design Minimalista 🎨
- Posicionamento discreto no canto superior direito
- Efeito glassmorphism com blur
- Gradiente suave (azul escuro → roxo)
- Animações suaves ao interagir
- Pode ser minimizado em um círculo dourado

## 🎼 Como Adicionar Mais Músicas

### Método 1: Via Arquivo (Recomendado)
1. Coloque seus arquivos `.mp3` na pasta `musicas/`
2. Abra o arquivo `index.html`
3. Localize a seção (aproximadamente linha 1493):
   ```javascript
   const musicasRelaxantes = [
       'harpa.mp3'
       // Adicione aqui
   ];
   ```
4. Adicione seus arquivos:
   ```javascript
   const musicasRelaxantes = [
       'harpa.mp3',
       'calmaria.mp3',
       'paz-interior.mp3',
       'meditacao.mp3'
   ];
   ```

### Método 2: Formato dos Nomes
O sistema **formata automaticamente** os nomes:
- Remove `.mp3`
- Substitui `-` e `_` por espaços
- Capitaliza a primeira letra

**Exemplos:**
```
harpa.mp3          → Harpa
calmaria.mp3       → Calmaria
paz-interior.mp3   → Paz interior
musica_suave.mp3   → Musica suave
```

## 🎛️ Controles Disponíveis

### ▶️ Play/Pause
- **Botão grande dourado** no centro
- Alterna entre tocar e pausar
- Feedback visual imediato

### 🔊 Volume
- Slider horizontal na parte inferior
- Arraste para ajustar de 0% a 100%
- Volume inicial: **30%** (suave para relaxar)

### ⏱️ Barra de Progresso
- Mostra o progresso da música atual
- **Clique** em qualquer posição para pular
- Exibe tempo atual e duração total

### − Minimizar
- Clique no botão `−` no canto superior direito
- Player se transforma em **círculo dourado** 🎵
- Clique novamente para expandir

## 📂 Estrutura de Arquivos

```
Tabela_da_vida/
├── index.html           (código principal)
├── musicas/            (pasta de músicas)
│   ├── harpa.mp3
│   ├── calmaria.mp3    (adicione aqui)
│   └── paz.mp3         (adicione aqui)
└── MUSICAS_RELAXANTES.md (este guia)
```

## 🎯 Fontes Recomendadas de Música

### Músicas Livres de Direitos Autorais
1. **YouTube Audio Library**
   - https://www.youtube.com/audiolibrary
   - Categoria: Ambiente / Relaxamento

2. **Free Music Archive**
   - https://freemusicarchive.org
   - Busque: "ambient", "meditation", "calm"

3. **Incompetech**
   - https://incompetech.com
   - Filtro: "Ambient", "Peaceful"

4. **Pixabay Music**
   - https://pixabay.com/music
   - Categoria: "Relaxing", "Meditation"

### Termos de Busca
- "royalty free relaxing music"
- "meditation music no copyright"
- "ambient music creative commons"
- "calming background music free"

## 🔧 Personalização Avançada

### Alterar Volume Inicial
No arquivo `index.html`, linha ~1506:
```javascript
audio.volume = 0.3; // 30% - ajuste para 0.5 (50%) ou outro valor
```

### Alterar Posição do Player
No CSS, linha ~420:
```css
.music-player {
    top: 20px;      /* Distância do topo */
    right: 20px;    /* Distância da direita */
    /* Para mover para esquerda: left: 20px; */
    /* Para mover para baixo: bottom: 20px; */
}
```

### Alterar Cores
```css
/* Gradiente do player */
background: linear-gradient(135deg, 
    rgba(20, 20, 40, 0.95),   /* Azul escuro */
    rgba(30, 30, 60, 0.95)    /* Roxo escuro */
);

/* Botão play/pause */
background: linear-gradient(135deg, #ffd700, #ffa500); /* Dourado */
```

## 🐛 Solução de Problemas

### Música não toca
- ✅ Verifique se o arquivo está em `musicas/`
- ✅ Confirme que é `.mp3` (não `.mp4`, `.wav`, etc)
- ✅ Verifique se o nome está correto na lista
- ✅ Teste com outro navegador

### Player não aparece
- ✅ Limpe o cache do navegador (Ctrl + Shift + Delete)
- ✅ Recarregue a página (Ctrl + F5)
- ✅ Verifique se não há erros no Console (F12)

### Volume muito baixo/alto
- ✅ Ajuste o slider de volume no player
- ✅ Verifique o volume do sistema operacional
- ✅ Altere `audio.volume` no código (linha 1506)

### Loop não funciona
- ✅ O atributo `loop` está no HTML (linha 1048)
- ✅ Isso garante loop infinito automático
- ✅ Não é necessário configurar nada

## 💡 Dicas de Uso

1. **Startup Automático**
   - As músicas NÃO tocam automaticamente (políticas dos navegadores)
   - O usuário deve clicar em ▶️ para iniciar

2. **Música de Fundo**
   - Volume inicial em 30% para não incomodar
   - Usuário pode ajustar conforme preferência

3. **Múltiplas Músicas**
   - Adicione várias músicas na lista
   - Usuário ouve todas em sequência

4. **Mobile Friendly**
   - Player responsivo para celulares
   - Controles touch-friendly

## 📊 Estatísticas

- **Tamanho do Player**: 280px × auto
- **Posição**: Superior direita (20px das bordas)
- **Volume Padrão**: 30%
- **Loop**: Infinito ♾️
- **Formato Suportado**: MP3

## 🎉 Recursos Futuros (Sugestões)

- [ ] Equalizer visual
- [ ] Modo escuro/claro
- [ ] Playlist visível
- [ ] Modo aleatório (shuffle)
- [ ] Efeitos de fade in/out
- [ ] Suporte a outros formatos (WAV, OGG)

---

**Desenvolvido com 💛 para proporcionar momentos de paz e reflexão**

♾️ **Loop Infinito | Relaxe e Respire**
