# 🎮 Seu Persona GTA

🔗 **Acesse o site:**  https://cesaraugusto-snc.github.io/Persona-GTA/)
Página interativa de seleção de personagem inspirada no visual de GTA. Você escolhe uma lenda de **Dev City** ou envia uma selfie e uma IA transforma a sua foto em um personagem de videogame.


## ✨ Funcionalidades

- **Seleção de personagem:** clique em um dos avatares (Lucia, Jason ou CJ) e a página troca a imagem, o nome e a cor do nome.
- **Selfie com IA:** clique no botão 📸, envie uma foto e receba a sua versão em estilo videogame (contorno preto grosso, cores vivas, meio corpo e fundo transparente). O personagem aparece com o nome **"Você"**.
- **Layout responsivo:** funciona em desktop e celular. As medidas acompanham a altura da tela (`vh` / `dvh`) para o nome não ser cortado e o rodapé não ficar desproporcional.

## 🛠️ Tecnologias

- HTML5
- CSS3 (Flexbox, `media queries`, unidades `vh`/`dvh`)
- JavaScript puro
- [Google Fonts](https://fonts.google.com/): Bangers
- [Puter.js](https://developer.puter.com/): geração de imagem com IA (`puter.ai.txt2img`)

## 📁 Estrutura do projeto

```
GTA Projeto/
├── index.html
├── style.css
├── scripts.js
└── img/
    ├── BG2.jpg      # fundo da página
    ├── Lucia.png
    ├── Jason.png
    └── CJ.png
```

## 🚀 Como executar

1. Baixe ou clone o projeto.
2. Confira se a pasta `img/` está junto do `index.html` com as imagens listadas acima.
3. Abra o `index.html` no navegador (ou use a extensão **Live Server** do VS Code).

> A fonte e a IA são carregadas pela internet, então é preciso estar conectado. Para usar a selfie, a Puter pode pedir que você entre na sua conta.

## 🧠 Como funciona

| Função | O que faz |
| --- | --- |
| `escolherPersonagem(nome, imagem, cor)` | Atualiza o nome, a imagem e a cor do personagem exibido. |
| `lerFoto(foto)` | Lê a foto enviada, manda para a IA da Puter gerar o personagem e exibe o resultado. |

## 📱 Responsividade

- **Desktop:** nome, personagem e textos dimensionados pela altura da tela.
- **Celular (até 768px):** personagem e nome proporcionais à altura visível, textos centralizados e degradê escuro no rodapé para dar leitura.

## ⚠️ Atenção ao publicar online

Servidores diferenciam letras maiúsculas e minúsculas nos nomes de arquivo. Use sempre o mesmo nome no HTML e na pasta (por exemplo, `Lucia.png` em todos os lugares), senão a imagem pode não carregar fora do Windows.

## 📄 Aviso

Projeto de estudo, sem fins comerciais. GTA e os personagens citados pertencem aos seus respectivos donos (Rockstar Games).

## 👤 Autor

Feito por **César**.
