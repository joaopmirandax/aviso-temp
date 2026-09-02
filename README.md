# Aviso Temporizado

Projeto prático em React focado em manipulação de temporizadores dentro do ciclo de vida dos componentes. Exibe uma mensagem de boas-vindas que some da tela depois de 3 segundos.

### O que o projeto faz
- Exibe a mensagem de boas-vindas assim que a tela carrega.
- Dispara um `setTimeout` de 3000ms para alterar a visibilidade do aviso.
- Trata o encerramento do temporizador no *cleanup* do `useEffect` (`clearTimeout`), evitando acúmulo de processos e vazamento de memória se o componente for fechado antes da hora.

### Tecnologias
- React (useState e useEffect)
- JavaScript
- CSS

---
**Autor:** João Pedro Miranda
