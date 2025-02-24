## Roadmap para se tornar um Desenvolvedor Front-end Sênior Completo

### 1. Performance e Otimização (1-2 semanas)

**Conceitos:**
- Memoização: `React.memo()`, `useMemo()`, `useCallback()`
- Lazy loading: `React.lazy()`, `Suspense`
- Virtualização de listas: `react-virtual`, `react-window`
- Técnicas de debounce e throttle: `lodash.debounce`, `lodash.throttle`
- Análise de performance: Lighthouse, React DevTools

**Materiais:**
- [Documentação oficial do React](https://react.dev)
- [Artigo sobre performance em React](https://kentcdodds.com/blog)
- [Lighthouse - Guia do Google](https://web.dev/lighthouse/)

**Prática:**
- Analise um projeto real com Lighthouse e otimize tempo de carregamento
- Implemente memoização em componentes com re-renderização desnecessária
- Virtualize uma lista longa com `react-window`

---

### 2. Renderização (SSR, CSR, SSG, ISR) (1 semana)

**Conceitos:**
- SSR (Server-Side Rendering)
- CSR (Client-Side Rendering)
- SSG (Static Site Generation)
- ISR (Incremental Static Regeneration)

**Materiais:**
- [Documentação Next.js](https://nextjs.org/docs)
- [Comparativo de renderização](https://www.smashingmagazine.com)

**Prática:**
- Crie um pequeno projeto Next.js usando cada estratégia de renderização
- Compare impacto em performance, SEO e experiência do usuário

---

### 3. Acessibilidade Avançada (a11y) (1 semana)

**Conceitos:**
- Aria: `aria-label`, `aria-hidden`, `role`
- Navegação via teclado e leitores de tela
- Validação de acessibilidade: Axe DevTools

**Materiais:**
- [Web Accessibility - MDN](https://developer.mozilla.org/en-US/docs/Web/Accessibility)
- [Axe DevTools](https://www.deque.com/axe/devtools/)

**Prática:**
- Melhore a acessibilidade de um projeto aplicando essas técnicas
- Valide acessibilidade usando Axe DevTools

---

### 4. Testes (3-4 semanas)

**Conceitos:**
- Testes unitários: Jest + Testing Library
- Testes de integração: Interações entre componentes
- Testes E2E (end-to-end): Cypress, Playwright

**Materiais:**
- [Documentação Jest](https://jestjs.io/)
- [Testing Library](https://testing-library.com/)
- [Cypress](https://www.cypress.io/)

**Prática:**
- Escreva testes unitários para funções e hooks
- Teste componentes e interações de estado
- Crie testes E2E para verificar jornadas completas de usuário

---

### 5. Projeto Final de Validação

- Aplique otimizações de performance
- Escolha e implemente a melhor estratégia de renderização
- Torne a aplicação 100% acessível
- Cubra o projeto com testes unitários, de integração e E2E
