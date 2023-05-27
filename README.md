# Alura Play - Requisições
## Sobre:

Este repositório contém um projeto que facilita o cadastro e exibição de vídeos do YouTube em uma página inicial usando requisições internas em JavaScript.

- **Cadastro de vídeos:** O projeto permite que os usuários cadastrem vídeos do YouTube diretamente na página inicial. Ao preencher os campos necessários, como título, descrição e URL do vídeo, o sistema realiza uma requisição interna em JavaScript para salvar os dados no banco de dados.
- **Requisições assíncronas:** O uso de requisições assíncronas em JavaScript permite que o cadastro de vídeos seja realizado de forma fluida e sem a necessidade de recarregar a página. Isso proporciona uma experiência de usuário mais suave e interativa.
- **Exibição dos vídeos:** Após o cadastro, os vídeos são exibidos automaticamente na página inicial, proporcionando uma vitrine de vídeos atualizada. A exibição é realizada por meio de um componente JavaScript que busca os vídeos cadastrados no banco de dados e os exibe em um layout responsivo e amigável.

## Como executar o projeto?

Os passos para acessar o projeto são bem simples, mas seguem a seguinte ordem:

```bash
# Terminal

git clone https://github.com/MateusMaciel340/alura-play-requisicoes

cd alura-play-requisicoes/

```

```bash
# index.html -> live server
json-server --watch db.json
```

## Tecnologias

As seguintes ferramentas foram utilizadas na construção do projeto:

### Frontend

- HTML
- CSS
- JavaScript

## Contribuidores

<table>
    <thead>
        <tr>
            <td>
                <img src="https://avatars.githubusercontent.com/u/55550732?v=4" width="150px"/>
            </td>
        </tr>
    </thead>
    <tbody>
        <tr>
            <th>Mateus Maciel</th>
        </tr>
    </tbody>
</table>

## Como contribuir?

1. Faça um fork do projeto.
2. Crie uma nova ramificação com suas alterações: `git checkout -b minha-feature`
3. Salve as alterações e crie uma mensagem de confirmação contando o que você fez: `git commit -m "arquivo modificado"`
4. Envie suas alterações: `git push origin minha-feature`

## Licença

Este projeto é licenciado sob a licença Alura Cursos.