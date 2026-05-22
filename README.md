# XTREINOS ANBU E-SPORT

Sistema de gerenciamento de campeonatos para guildas, desenvolvido em HTML, CSS e JavaScript puro.

O projeto permite cadastrar guildas, registrar quedas, calcular pontuações automaticamente e gerar um ranking em tempo real.

---

# Funcionalidades

* Cadastro de guildas
* Sistema de 4 quedas
* Cálculo automático de pontos
* Soma automática de kills
* Ranking dinâmico
* Destaque para TOP 1, TOP 2 e TOP 3
* Salvamento automático no navegador
* Layout responsivo
* Interface gamer/anime

---

# Sistema de Pontuação

| Colocação | Pontos |
| --------- | ------ |
| 1º        | 12     |
| 2º        | 10     |
| 3º        | 9      |
| 4º        | 8      |
| 5º        | 7      |
| 6º        | 6      |
| 7º        | 5      |
| 8º        | 4      |
| 9º        | 3      |
| 10º       | 2      |
| 11º       | 1      |
| 12º       | 0      |

Cada kill adiciona +1 ponto.

---

# Tecnologias Utilizadas

* HTML5
* CSS3
* JavaScript Vanilla

---

# Estrutura do Projeto

```text
/
├── index.html
├── logo.png
└── README.md
```

---

# Como Executar

## Método 1 — Localmente

1. Baixe os arquivos
2. Coloque:

   * `index.html`
   * `logo.png`

na mesma pasta.

3. Abra o arquivo:

```text
index.html
```

no navegador.

---

## Método 2 — GitHub Pages

1. Crie um repositório no GitHub
2. Envie os arquivos do projeto
3. Vá em:

```text
Configurações → Páginas
```

4. Em:

```text
Fonte
```

selecione:

```text
Implantar a partir de uma ramificação
```

5. Escolha:

* Branch: `main`
* Pasta: `/(raiz)`

6. Clique em:

```text
Salvar
```

O GitHub irá gerar um link público do site.

---

# Armazenamento

Atualmente o sistema utiliza:

```javascript
localStorage
```

Os dados ficam salvos apenas no navegador do usuário.

---

# Melhorias Futuras

* Integração com Firebase
* Ranking em tempo real
* Login de administradores
* Histórico de campeonatos
* Exportação de resultados
* Tema gamer avançado
* Painel administrativo
* Estatísticas detalhadas

---

# Autor

Projeto desenvolvido para gerenciamento de treinos e campeonatos da ANBU E-SPORT.

---

# Licença

Este projeto é livre para estudos e modificações.
