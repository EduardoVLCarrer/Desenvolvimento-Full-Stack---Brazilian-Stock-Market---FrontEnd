# Stock Analysis Front-End

Interface Web desenvolvida em HTML, CSS e JavaScript para consumo da Stock Analysis API, permitindo realizar análises de ações e visualizar os resultados em formato de tabela.

---

## 🎯 Funcionalidades

- Enviar ticker para análise via API
- Listar ações classificadas como `SIM` ou `NAO`
- Consultar análises específicas por ticker
- Exibir dados retornados da API em tabela HTML
- Tratamento de erros de comunicação com a API

---

## 🛠️ Tecnologias Utilizadas

- HTML5
- CSS3
- JavaScript (Fetch API)

---

## 📋 Pré-requisitos

- Navegador Web (Chrome, Edge ou Firefox)
- Back-End rodando localmente em:
```
http://localhost:5000
```

---

## ▶️ Como Executar

### Opção 1 — Abrir diretamente no navegador
1. Navegue até a pasta do projeto
2. Abra o arquivo `index.html` no navegador

> Observação: alguns navegadores podem limitar requisições locais. Caso ocorra, utilize a opção 2.

### Opção 2 — Servidor local simples (recomendado)

Com Python instalado:

```bash
python -m http.server 5500
```

Depois acesse:
```
http://localhost:5500
```

---

## ⚙️ Configuração de API

O Front-End consome a API em:
```
http://localhost:5000
```

Caso o endereço ou porta do Back-End seja alterado, ajuste as URLs no arquivo:
```
javascript/script.js
```

---

## ℹ️ Observações

- O Front-End depende diretamente da API para funcionamento.
- Certifique-se de que o Back-End esteja rodando antes de utilizar a interface.
