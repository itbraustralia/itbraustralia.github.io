# IT.BR Australia - Website

> Este é o site da nossa comunidade


## Pré-requisitos

- [Git](http://git-scm.com/downloads);
- [Ruby](http://www.ruby-lang.org/pt/downloads/);
- [Jekyll](http://jekyllrb.com/);


## Como usar

Para rodar esta página na sua máquina, siga estas etapas:

- Clone este repositório
- Acesse a pasta gerada
- Execute o comando `bundle`
- Execute `jekyll serve` ou `jekyll serve -w`

git clone git@github.com:itbraustralia/itbraustralia.github.io.git


## Criando um post

- Crie um novo markdown baseado no arquivo `post-example.md`. Este arquivo precisa estar no formato `<ano-mes-dia-url>.md`
- Copie o arquivo para dentro da pasta `_posts`;
- Acesse a página do blog. Ele deve estar listado como um dos nossos posts;
- Atualize o conteúdo e atualize o navegador;

### E quanto às imagens?

Para as images você precisa criar:

- `<nome-da-imagem>.jpg`: imagem padrão;
- `<nome-da-imagem>_placeholder.jpg`: imagem para ser carregada inicialmente. Como usamos lazy load para as imagens, esta imagem é necessária. Caso esteja em dúvida, copie a imagem `<nome-da-imagem>.jpg` e mude o nome para este padrão;
- `<nome-da-imagem>_thumb@2x.jpg`: imagem com resolução para macOS; 


## Como contribuir

Contribuições são mais que bem vindas! [Abra um pull request](https://github.com/itbraustralia/itbraustralia.github.io/pulls) com as suas alterações ou [crie uma issue](https://github.com/itbraustralia/itbraustralia.github.io/issues) com as suas sugestões.