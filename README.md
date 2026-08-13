# Página de venda — Máquina de Sorvete Soft LSD-425

Landing page de venda da máquina de sorvete LSD-425 (Petrolina/PE e Juazeiro/BA), com botão direto para o WhatsApp.

## Arquivos

| Arquivo | O que é |
|---|---|
| `index.html` | A página completa (HTML, CSS e textos) |
| `foto.jpg` | Foto real da máquina — também usada na prévia do link |
| `video.mp4` | Vídeo da máquina funcionando |

## Endereço da página

https://governadamente-max.github.io/maquina-sorvete/

## Como publicar no GitHub Pages

1. No GitHub, crie um repositório **público** chamado `maquina-sorvete`, **sem** marcar
   "Add a README file" (o repositório precisa estar vazio).
2. Suba os arquivos desta pasta:

   ```
   git remote add origin https://github.com/governadamente-max/maquina-sorvete.git
   git push -u origin main
   ```

3. No repositório: **Settings → Pages**.
4. Em *Source*, escolha **Deploy from a branch**, branch **main**, pasta **/ (root)** e salve.
5. Em 1–2 minutos a página fica no ar no endereço acima.

> O nome do repositório precisa ser exatamente `maquina-sorvete`. Se você usar outro nome,
> troque também as 4 linhas do `index.html` que começam com `<link rel="canonical"`,
> `<meta property="og:url"`, `<meta property="og:image"` e `<meta name="twitter:image"` —
> senão a prévia do link (imagem que aparece no WhatsApp e no Facebook) não vai funcionar.

## Contato da página

- **Carvalho** — (74) 98866-0565
- O botão do WhatsApp já abre a conversa com uma mensagem pronta.

## Como alterar o preço ou o texto

Abra o `index.html` em qualquer editor de texto e procure por `19.000` para trocar o valor.
Para trocar a foto ou o vídeo, basta substituir os arquivos `foto.jpg` e `video.mp4`
mantendo os mesmos nomes.
