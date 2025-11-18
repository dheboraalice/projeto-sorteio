# projeto-sorteio 🎉🥳


**O Azarado Mais Sortudo**
Este projeto foi criado com uma proposta divertida e diferente: aqui, o vencedor não é o primeiro a ser sorteado, e sim o último.
A ideia é celebrar aquele participante que, aparentemente, tem o maior azar… mas que no fim das contas acaba sendo o mais sortudo de todos.


**🧐 Como o projeto funciona**
O sistema lê um arquivo contendo uma lista de pessoas, normalmente em formato CSV, com nome e e-mail.
Todos os participantes são carregados e armazenados em memória.

**O sorteio acontece de forma eliminatória:**
a cada rodada, um participante é sorteado e removido da lista;
o processo continua até que reste apenas uma pessoa.
O último sobrevivente é declarado o grande vencedor — o verdadeiro azarado mais sortudo.


### 1. **Clone o Repositório**

```bash
git clone https://github.com/dheboraalice/projeto-sorteio
cd sorteio
```

### 2. **Instale as Dependências**

O projeto utiliza [Node.js](https://nodejs.org/) para rodar. Certifique-se de que está instalado em sua máquina e rode o seguinte comando:

```bash
npm install
```

### 3. **Forneça a Lista de Alunos**

Prepare um arquivo CSV contendo o nome e o e-mail dos alunos, no seguinte formato (nome;email):

```
João Silva;joao@example.com
Maria Oliveira;maria@example.com
```

Salve o arquivo como `data/dados.csv` na pasta `src` do projeto.

### 4. **Execute o Sorteio**

Para executar o sorteio invertido e selecionar o "azarado mais sortudo", utilize o seguinte comando:

```bash
npm start
```

## Tecnologias Utilizadas

- **Node.js**: Plataforma para execução do código JavaScript no backend.
- **TypeScript**: Linguagem de programação que aumenta a robustez do código.
- **terminal-kit**: Biblioteca usada para criar uma interface de terminal interativa e exibir a barra de progresso.
