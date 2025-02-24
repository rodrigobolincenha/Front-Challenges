# Frontend Mentor - Blog Preview Card Solution

Esta é minha solução para o desafio [Blog preview card challenge no Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS).

## Índice

- [Visão Geral](#visão-geral)
  - [O Desafio](#o-desafio)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [Meu Processo](#meu-processo)
  - [Tecnologias Utilizadas](#tecnologias-utilizadas)
  - [O Que Aprendi](#o-que-aprendi)
  - [Desenvolvimento Contínuo](#desenvolvimento-contínuo)
  - [Recursos Úteis](#recursos-úteis)
- [Autor](#autor)

## Visão Geral

### O Desafio

Os usuários devem ser capazes de:

- Visualizar o layout ideal independente do tamanho da tela
- Ver estados de hover para elementos interativos
- Experimentar uma animação suave ao carregar o card

### Screenshot

![](./design/desktop-preview.jpg)

### Links

- URL da Solução: [Adicionar URL da solução]
- URL do Site: [Adicionar URL do site]

## Meu Processo

### Tecnologias Utilizadas

- HTML5 Semântico
- CSS Custom Properties
- Flexbox
- Mobile-first workflow
- Animações CSS
- Metodologia BEM para nomenclatura de classes

### O Que Aprendi

- Aprofundei meus conhecimentos em Flexbox para layouts responsivos:

```css
.card-container {
  display: flex;
  flex-direction: column;
  gap: var(--spacing-md);
}
```

- Implementei animações suaves usando CSS:

```css
.card {
  animation: fadeIn 0.8s ease-out;
}

@keyframes fadeIn {
  from {
    opacity: 0;
    transform: translateY(20px);
  }
  to {
    opacity: 1;
    transform: translateY(0);
  }
}
```

- Utilizei variáveis CSS para melhor manutenção:

```css
:root {
  --yellow: hsl(47, 85%, 63%);
  --gray-950: hsl(0, 0%, 7%);
  --spacing-md: 1.5rem;
}
```

### Desenvolvimento Contínuo

Pretendo focar em:

- Aprimorar minhas habilidades com animações CSS
- Explorar mais técnicas de acessibilidade
- Melhorar a organização do código CSS
- Aprofundar conhecimentos em design responsivo

### Recursos Úteis

- [MDN Web Docs](https://developer.mozilla.org) - Excelente documentação sobre Flexbox e animações CSS
- [CSS-Tricks](https://css-tricks.com) - Guia completo sobre Flexbox
- [Web.dev](https://web.dev) - Ótimos recursos sobre performance e boas práticas

## Autor

- Website - [Rodrigo Alves Bolincenha]
- Frontend Mentor - [@rodrigobolincenha](https://www.frontendmentor.io/profile/rodrigobolincenha)
- LinkedIn - [Rodrigo Bolincenha](https://www.linkedin.com/in/rodrigo-bolincenha)
