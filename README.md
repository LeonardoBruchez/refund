# 💸 Refund

> Aplicação web para solicitação de reembolso de despesas, feita com HTML, CSS e JavaScript puro.

Este é um **projeto de teste**, criado para praticar manipulação do DOM, eventos e formatação de valores em JavaScript sem frameworks.

---

## ✨ Funcionalidades

- **Cadastro de despesas** com nome, categoria e valor
- **Máscara de moeda automática:** o valor é formatado em Real (R$) enquanto você digita
- **Ícone por categoria:** Alimentação, Hospedagem, Serviços, Transporte e Outros
- **Contador de despesas** com singular e plural ("1 despesa" / "2 despesas")
- **Soma automática** do valor total das solicitações
- **Remoção de despesas** da lista, com atualização dos totais
- **Limpeza do formulário** após cada envio

## 🛠️ Tecnologias

- HTML5
- CSS3
- JavaScript (Vanilla)

## 🚀 Como executar

1. Clone o repositório:
   ```bash
   git clone <url-do-repositorio>
   ```
2. Abra o arquivo `index.html` no navegador.

Se preferir, use uma extensão como o **Live Server** no VS Code.

## 📁 Estrutura

```
├── img/          # Ícones das categorias e da interface
├── index.html    # Estrutura da página
├── styles.css    # Estilos
└── scripts.js    # Lógica da aplicação
```

## 🧠 Aprendizados

- Criação de elementos com `document.createElement` e `append`
- Diferença entre `.value` (campos de formulário) e `.textContent` (conteúdo de elementos)
- Formatação de moeda com `toLocaleString("pt-BR", { style: "currency", currency: "BRL" })`
- Uso de expressões regulares para tratar valores digitados
- Delegação de eventos para remover itens da lista

---

<p align="center">
  Desenvolvido por <a href="https://bruchez.dev"><strong>Leonardo Bruchez</strong></a> · <a href="https://bruchez.dev">bruchez.dev</a>
</p>
