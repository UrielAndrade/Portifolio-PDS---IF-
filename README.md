<div align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d1/Instituto_Federal_de_Rond%C3%B4nia_-_Marca_Vertical_2015.svg/1200px-Instituto_Federal_de_Rond%C3%B4nia_-_Marca_Vertical_2015.svg.png" width="120" alt="IFRO Logo" />
  <h1>🎮 HUB DE PORTFÓLIOS — IFRO</h1>
  <p><em>Campus Ji-Paraná • Prática de Desenvolvimento de Software (PDS)</em></p>
  
  <h3>👨‍💻 Equipe de Desenvolvimento:</h3>
  <p>
    <b><a href="#player-1--uriel-andrade">Uriel Andrade</a></b> &nbsp;•&nbsp; 
    <b><a href="#player-2--arthur-braga">Arthur Braga</a></b> &nbsp;•&nbsp; 
    <b><a href="#player-3--alisson-caio">Alisson Caio</a></b>
  </p>

  <p>
    <img src="https://img.shields.io/badge/Blazor-512BD4?style=for-the-badge&logo=blazor&logoColor=white" />
    <img src="https://img.shields.io/badge/.NET_8-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" />
    <img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white" />
    <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
    <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
  </p>
</div>

---

## 🕹️ Sobre o Projeto

Este projeto é um **Hub Central** unificado construído em **C# Blazor WebAssembly/Server**. Ele atua como uma tela de "Seleção de Personagem" de um fliperama clássico, onde cada desenvolvedor da equipe possui seu próprio portfólio pessoal e completamente isolado. 

Para garantir que o estilo visual e a identidade de cada desenvolvedor fossem preservados, aplicamos regras estritas de **CSS Isolation (Scoped CSS)**, garantindo que o estilo Cyberpunk de um não interfira no design Clean do outro.

---

## 👾 Select Your Player (Portfólios)

Nossa aplicação hospeda os seguintes perfis:

### ⚡ Player 1: Uriel Andrade
* **Role:** Backend Developer
* **Estética:** Cyberpunk / Neon
* **Características:** Design sombrio, focado em linhas neon verdes e roxas, com animações de scanlines e glitch no melhor estilo hacker dos anos 80/90. 

### 🧊 Player 2: Arthur Braga
* **Role:** Fullstack Developer & Robótica
* **Estética:** Clean / Moderno
* **Características:** Uma interface super polida, minimalista, responsiva e focada na experiência do usuário (UX), com espaços em branco generosos, fontes sem serifa modernas e contrastes refinados.

### ⚔️ Player 3: Alisson Caio
* **Role:** Front-End Developer
* **Estética:** Hollow Knight / Metroidvania
* **Características:** Profundo e misterioso. Baseado na estética "Soul", com tons frios, azuis etéreos, fundos imersivos e ícones forjados nos confins de Hallownest.

---

## 🚀 Como Executar Localmente

### Pré-requisitos
- [.NET 8.0 SDK](https://dotnet.microsoft.com/download) ou superior instalado.
- O terminal da sua preferência.

### Rodando o Servidor
1. Clone este repositório ou navegue até o diretório raiz do projeto:
```bash
cd Portifolio-PDS---IF-
```
2. Restaure as dependências do projeto:
```bash
dotnet restore
```
3. Inicie a aplicação com o Hot Reload ativo:
```bash
dotnet watch run
```
4. O terminal irá gerar um link `localhost` (geralmente `http://localhost:5000` ou `https://localhost:5001`). Acesse-o no seu navegador e escolha seu Player!

---

## 🛠️ Arquitetura e Isolamento

O maior desafio (e triunfo) deste repositório compartilhado foi o gerenciamento de folhas de estilo. 
- Cada portfólio vive na sua própria pasta (`Uriel_Pages`, `Braga_Pages`, `Alisson_Pages`).
- O CSS global de cada participante foi convertido rigorosamente para **Scoped CSS** (`*.razor.css`).
- Utilizou-se escopo por contêineres e seletores isolados para assegurar que variáveis dinâmicas (como `:root` localizadas) funcionassem de forma estável no Blazor.

---
<div align="center">
  <p>Criado com ☕ e muito código. <b>IFRO - PDS 2024+</b></p>
</div>
