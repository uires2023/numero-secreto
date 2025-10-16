<h1 align="center">🎯 Número Secreto</h1>

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/status-concluído-brightgreen?style=flat-square" alt="Status">
  <img src="https://img.shields.io/github/license/uires2023/numero-secreto?style=flat-square" alt="Licença">
</p>

---

## 🕹️ Sobre o projeto

O **Número Secreto** é um jogo interativo de adivinhação feito com **HTML**, **CSS** e **JavaScript**.  
O jogador deve descobrir qual é o número secreto gerado aleatoriamente pelo sistema.  
A cada tentativa, o jogo indica se o número informado é **maior** ou **menor** que o número correto.

<p align="center">
  <img src="https://raw.githubusercontent.com/uires2023/numero-secreto/main/img/preview.png" alt="Imagem do jogo" width="600px">
</p>

---

## 💡 Demonstração

Se quiser jogar online, acesse o link do GitHub Pages:

🔗 **https://uires2023.github.io/numero-secreto/**

---

## 🧠 Tecnologias utilizadas

- HTML5  
- CSS3  
- JavaScript (ES6+)  
- Git e GitHub  

---

## ⚙️ Estrutura do projeto

```bash
numero-secreto/
├── img/            # imagens e ícones usados no jogo
├── index.html      # estrutura principal da página
├── style.css       # estilos visuais
└── app.js          # lógica do jogo

## 💡 Trecho principal do jogo

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
## 🧠 Tecnologias utilizadas

| Tecnologia          | Descrição                      |
| ------------------- | ------------------------------ |
| 🧩 **HTML5**        | Estrutura da interface do jogo |
| 🎨 **CSS3**         | Estilos e layout visual        |
| ⚡ **JavaScript**    | Lógica e interatividade        |
| 🧭 **Git / GitHub** | Versionamento e hospedagem     |


## 🌐 Publicação no GitHub Pages

Vá em Settings → Pages

Selecione a branch main e a pasta / (root)

Clique em Save

Seu jogo ficará disponível em:
🔗 https://uires2023.github.io/numero-secreto/

👨‍💻 Autor

<img src="https://avatars.githubusercontent.com/u/155882833?v=4" width=120><br><sub>Uires Carlos de Oliveira</sub>
🎓 Estudante de Engenharia de Software — UnB
🎷 Músico e entusiasta em tecnologia
📧 Contato: uires.urs@gmail.com

🪪 Licença

Este projeto está sob a licença MIT.
Sinta-se livre para estudar, modificar e compartilhar! 💚

