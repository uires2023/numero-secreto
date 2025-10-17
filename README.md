<h1 align="center">🎯 Número Secreto</h1>

<p align="center">
  <img src="https://raw.githubusercontent.com/uires2023/numero-secreto/main/img/preview.png" width="600px" alt="Tela do jogo Número Secreto">
</p>

<p align="center">
  <a href="https://uires2023.github.io/numero-secreto/">
    <img src="https://img.shields.io/badge/▶️%20Jogar%20Agora-008000?style=for-the-badge&logo=githubpages&logoColor=white" alt="Jogar Agora">
  </a>
</p>

---

## 🕹️ Sobre o projeto

O **Número Secreto** é um jogo interativo de adivinhação feito com **HTML**, **CSS** e **JavaScript**.  
O jogador deve descobrir qual é o número secreto gerado aleatoriamente pelo sistema.  
A cada tentativa, o jogo indica se o número informado é **maior ou menor** que o número correto.

<p align="center">
  <img src="https://raw.githubusercontent.com/uires2023/numero-secreto/main/img/game-example.png" width="500px" alt="Exemplo de jogo">
</p>

---

## 🚀 Como executar localmente

### 1️⃣ Clone o repositório
```bash
git clone git@github.com:uires2023/numero-secreto.git
```

### 2️⃣ Acesse a pasta do projeto
```bash
cd numero-secreto
```

### 3️⃣ Execute o jogo
Clique duas vezes em **index.html** ou rode:
```bash
start index.html
```

---

## ⚙️ Estrutura do projeto

```bash
numero-secreto/
├── img/            # imagens e ícones do jogo
├── index.html      # estrutura principal
├── style.css       # estilos visuais
└── app.js          # lógica e regras do jogo
```

---

## ✨ Lógica principal do jogo

```js
const numeroSecreto = Math.floor(Math.random() * 10) + 1;
let tentativa;

while (tentativa !== numeroSecreto) {
  tentativa = Number(prompt("Adivinhe o número secreto (de 1 a 10):"));
  
  if (tentativa === numeroSecreto) {
    alert("🎉 Parabéns! Você acertou!");
  } else if (tentativa > numeroSecreto) {
    alert("📉 Tente um número menor!");
  } else {
    alert("📈 Tente um número maior!");
  }
}
```

---

## 🧠 Tecnologias utilizadas

| 🧩 Tecnologia | 💬 Descrição |
|---------------|--------------|
| 🧱 **HTML5** | Estrutura da interface |
| 🎨 **CSS3** | Estilos e layout visual |
| ⚡ **JavaScript (ES6+)** | Lógica e interatividade |
| 🌐 **Git / GitHub** | Versionamento e hospedagem |

---

## 🌎 Publicação no GitHub Pages

1. Vá em **Settings → Pages**  
2. Escolha a branch `main` e a pasta `/ (root)`  
3. Clique em **Save**  
4. Seu jogo ficará disponível em:  
   🔗 [https://uires2023.github.io/numero-secreto/](https://uires2023.github.io/numero-secreto/)

---

## 🔮 Melhorias futuras

- ✅ Adicionar contador de tentativas  
- ✅ Exibir histórico de palpites  
- ✅ Melhorar design responsivo  
- ✅ Adicionar sons e efeitos visuais  

---

## 👤 Autor

| [<img src="https://avatars.githubusercontent.com/u/155882833?v=4" width=120><br><sub>**Uires Carlos de Oliveira**</sub>](https://github.com/uires2023) |
| :---: |
| 🎓 Estudante de Engenharia de Software (UnB) <br> 🎷 Músico e entusiasta em tecnologia |
📧 **[uires.urs@gmail.com](mailto:uires.urs@gmail.com)**

---

## 🪪 Licença

Este projeto está sob a licença **MIT**.  
Sinta-se livre para usar, estudar e compartilhar 💚  

---

⭐ **Se gostou, deixe uma estrela no repositório!**


