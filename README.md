# Caio Vinicius | Desenvolvimento Dinâmico

Página de apresentação do aluno Caio Vinicius, feita para a disciplina de **Desenvolvimento Dinâmico** no Centro Universitário Jorge Amado (UniJorge). O projeto usa HTML, Tailwind CSS e JavaScript puro para mostrar na prática manipulação de DOM, eventos, requisições assíncronas e estado.

## Funcionalidades

- **Saudação e relógio ao vivo**: a mensagem muda conforme o horário e a hora é exibida no fuso de Salvador.
- **Projetos filtráveis**: a lista é gerada a partir de um array em JavaScript e filtrada por tecnologia.
- **Playground interativo** com três exemplos:
  - **DOM**: altera título, cor e tags de um cartão em tempo real.
  - **Fetch API**: consulta CEPs na API ViaCEP com `async/await` e tratamento de erros.
  - **Estado reativo**: lista de tarefas com adicionar e remover, refletindo o array de estado.
- **Formulário de contato** com validação e avisos (toasts). É apenas uma demonstração e não envia mensagens.
- **Menu responsivo** para celular e respeito à preferência de movimento reduzido.

## Tecnologias

- HTML5
- [Tailwind CSS](https://tailwindcss.com/) via CDN
- JavaScript ES6+
- Google Fonts (Inter, Outfit e JetBrains Mono)
- API [ViaCEP](https://viacep.com.br/)

## Como executar

Não precisa instalar nada.

1. Baixe o arquivo `index.html`.
2. Abra no navegador com um duplo clique, ou use a extensão Live Server do VS Code.

É necessário ter internet, pois o Tailwind, as fontes e a API de CEP são carregados da web.

## Estrutura

```
.
├── index.html
└── README.md
```

Todo o HTML, CSS e JavaScript está em um único arquivo.

## Autor

**Caio Vinicius**
Desenvolvedor Full Stack em Salvador, Bahia
Estudante de Análise e Desenvolvimento de Sistemas na UniJorge
GitHub: [@caioba19](https://github.com/caioba19)