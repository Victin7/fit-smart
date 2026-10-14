# BossFit — versão web

Primeira versão do BossFit: um coach fitness no navegador, com login, treino do dia, plano alimentar e gamificação.

<p>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/Chart.js-FF6384?style=flat-square&logo=chartdotjs&logoColor=white" alt="Chart.js" />
  <img src="https://img.shields.io/badge/Firebase-Auth_·_Firestore-FFCA28?style=flat-square&logo=firebase&logoColor=black" alt="Firebase" />
</p>

## Funcionalidades

- Login com e-mail e senha ou Google, verificação de e-mail e recuperação de senha (Firebase Authentication)
- Dados do usuário salvos no Firestore
- Treino inteligente do dia, com ajuste de dificuldade (mais fácil ou mais difícil) e geração de novo treino
- Cálculo de IMC, plano alimentar por objetivo e quiz para montar o perfil
- Gamificação com XP, níveis, sequência de dias e conquistas
- Chat de coach para dúvidas sobre treino e dieta
- Gráfico de evolução com Chart.js e timer de descanso

> Este é o protótipo em HTML/JavaScript puro. A evolução do projeto, o **BossFit AI** (React, TypeScript e Supabase), está em um repositório separado.

## Como usar

O projeto é um único arquivo `index.html`, sem build e sem dependências para instalar.

```bash
git clone https://github.com/Victin7/fit-smart.git
```

Depois, é só abrir o `index.html` no navegador. O login e os dados do usuário usam o Firebase do projeto (configurado no próprio `index.html`).

## Autor

**Victor Sousa dos Anjos** · estudante de Análise e Desenvolvimento de Sistemas (UNICID)  
[LinkedIn](https://www.linkedin.com/in/victor-s-anjos) · [GitHub](https://github.com/Victin7)
