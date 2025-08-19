# 📟 Calculadora em um único arquivo (HTML + CSS + JS)

Este projeto é uma **calculadora responsiva** desenvolvida em um único arquivo HTML, contendo **JavaScript** e **CSS embutidos**. O objetivo é demonstrar como criar uma aplicação completa, moderna e funcional sem depender de múltiplos arquivos.

---

## 🚀 Funcionalidades

* Operações básicas: **adição, subtração, multiplicação, divisão**
* **Porcentagem** e **inversão de sinal (±)**
* **Copiar resultado** para a área de transferência
* **Histórico simplificado** exibindo a última operação
* **Limpar entrada (CE)**, **limpar tudo (C)** e **backspace (⌫)**
* **Suporte ao teclado**:

  * `0-9` → números
  * `+`, `-`, `*`, `/` → operadores
  * `,` ou `.` → decimal
  * `Enter` ou `=` → calcular
  * `Esc` → limpar tudo
  * `Delete` → limpar entrada
  * `Backspace` → apagar último dígito
  * `n` → inverter sinal
  * `Ctrl + C` → copiar resultado
* **Tema claro/escuro** alternável com um clique
* Interface adaptada para **desktop e mobile**

---

## 📂 Estrutura

O projeto consiste em **um único arquivo**:

```
calculadora.html
```

Dentro dele estão definidos:

* O **HTML** da interface
* O **CSS** com variáveis de tema e estilos responsivos
* O **JavaScript** que gerencia a lógica da calculadora

---

## ▶️ Como usar

1. Baixe ou copie o arquivo `calculadora.html`.
2. Abra-o em qualquer navegador moderno (Chrome, Edge, Firefox, Safari).
3. Use o mouse, toque (em dispositivos móveis) ou o teclado para operar.

---

## 🎨 Customização

Você pode alterar facilmente as cores do tema modificando as variáveis no `:root`:

```css
:root{
  --bg:#0f1220;
  --panel:#151936;
  --kbd:#1a1f44;
  --accent:#7aa2ff;
}
```

Também é possível adicionar novos botões (ex.: memória M+/M-/MR) ou ajustar limites de exibição no JavaScript.

---

## 📜 Licença

Este projeto é livre para uso, modificação e estudo. 🚀
