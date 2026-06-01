# Calculadora de Diluição · Miromi

PWA simples e rápido para calcular a quantidade exata de **produto** e **água** ao diluir
produtos automotivos, em qualquer volume e proporção.

🔗 **App:** https://alexmiromi.github.io/calculadora-diluicao/
📝 Post original: https://www.miromi.com.br/blog/calculadora-de-diluicao

## Como funciona

1. Escolha o **fabricante** (cada marca usa um método) ou um método direto.
2. Escolha o **volume total** que vai preparar.
3. Escolha a **diluição** (1:5, 1:10, etc.).

O resultado aparece na hora: quanto de produto e quanto de água misturar.

### Métodos de cálculo

- **Método 1:1 (meio-a-meio):** `produto = volume / (1 + X)` — 1 parte de produto para X de água.
- **Método 1:2 (meio-a-meio):** `produto = volume / X` — 1 parte em X partes totais.

## PWA

- Instalável no celular e no desktop (ícone na tela inicial).
- Funciona **offline** após a primeira visita (service worker).

## Tecnologia

HTML, CSS e JavaScript puros — sem dependências, sem build. Hospedado no GitHub Pages.

## Licença

Uso livre. Sempre confira a recomendação do fabricante do produto.
