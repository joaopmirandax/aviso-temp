# Aviso Temporizado ⏳

## 📋 Sobre o Projeto
O **Aviso Temporizado** é uma aplicação React desenvolvida para demonstrar o controle de ciclo de vida de componentes com temporizadores. Ele exibe uma mensagem de boas-vindas na tela que desaparece automaticamente após 3 segundos.

## ⚙️ Funcionalidades
- **Ocultamento Automático:** Utilização de `setTimeout` para alterar a visibilidade do aviso em 3000ms.
- **Gerenciamento de Memória:** Implementação da função de limpeza (`clearTimeout`) no `useEffect` para evitar vazamentos de memória (*memory leaks*) caso o componente seja desmontado.
- **Feedback Visual:** Transição para um estado neutro informando que o aviso expirou.

## 🛠️ Tecnologias Utilizadas
- React.js (Hooks: `useState` e `useEffect`)
- CSS3
- JavaScript (ES6+)

## 👤 Autor
Desenvolvido por **João Pedro Miranda**.
