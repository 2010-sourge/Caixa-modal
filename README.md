# 🗂️ Modal Pop-up — Confirmation Dialog

Um componente de **modal de confirmação** responsivo, construído com **HTML e CSS** (e opcionalmente JavaScript para interatividade).

## 📋 Sobre o Projeto

Este projeto implementa um **pop-up modal de confirmação** — aquela janela que aparece quando o usuário tenta realizar uma ação irreversível, como deletar um item. O design é limpo e moderno, com fundo escurecido para destacar o modal.

No exemplo, o modal pergunta:
> *"Are you sure want to permanently delete this Photo?"*

Com as opções **Yes, Delete!** e **Cancel**.

## ✨ Funcionalidades

- ✅ Modal centralizado na tela
- ✅ Fundo com overlay escurecido (backdrop)
- ✅ Ícone de alerta (!) em destaque
- ✅ Botão de confirmação (azul) e cancelamento (rosa/vermelho)
- ✅ Design limpo e minimalista
- ✅ Totalmente responsivo

## 🛠️ Tecnologias Utilizadas

| Tecnologia | Uso |
|------------|-----|
| HTML5      | Estrutura do modal |
| CSS3       | Estilização e overlay |
| JavaScript | Abrir/fechar o modal (toggle) |

## 📁 Estrutura do Projeto

```
projeto/
├── index.html
├── style.css
```

## 🚀 Como Usar

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/seu-usuario/modal-popup.git
   ```

2. **Acesse a pasta do projeto:**
   ```bash
   cd modal-popup
   ```

3. **Abra no navegador:**
   ```bash
   open index.html
   ```
   Ou use a extensão **Live Server** no VS Code (`http://127.0.0.1:5500`).

## 🎨 Design

O modal segue um padrão de UI amplamente utilizado em sistemas web:

- **Overlay** — fundo roxo/escurecido que bloqueia o conteúdo ao fundo
- **Card branco** — caixa central com bordas arredondadas e sombra suave
- **Ícone de alerta** — círculo vermelho com `!` para indicar ação crítica
- **Dois botões** — ação principal (azul) e cancelamento (rosa), com cores distintas para guiar o usuário

## 🧩 Como Funciona

```
Usuário clica em "Deletar"
        ↓
Modal aparece com overlay
        ↓
Usuário escolhe:
  ├── "Yes, Delete!" → executa a ação
  └── "Cancel"       → fecha o modal
```

## 📱 Responsividade

O modal é centralizado com `flexbox` e se adapta a diferentes tamanhos de tela, mantendo a legibilidade e usabilidade em dispositivos móveis.

---

> Projeto desenvolvido para praticar criação de componentes UI reutilizáveis com HTML, CSS e JavaScript.
