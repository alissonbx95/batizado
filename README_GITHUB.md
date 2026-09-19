# Batizado do Arthur — GitHub Pages

Arquivos deste pacote:

- `index.html` — convite público que os convidados vão abrir.
- `gerador.html` — sua página privada de apoio para criar links personalizados.
- `.nojekyll` — evita processamento desnecessário do Jekyll no GitHub Pages.

## Publicação no GitHub Pages

1. Crie um repositório no GitHub, por exemplo `batizado-arthur`.
2. Faça upload dos três arquivos acima para a raiz do repositório.
3. Vá em `Settings` > `Pages`.
4. Em `Build and deployment`, escolha `Deploy from a branch`.
5. Selecione a branch `main`.
6. Selecione a pasta `/(root)`.
7. Clique em `Save`.

Depois da publicação, o convite ficará em um endereço parecido com:

`https://SEU-USUARIO.github.io/batizado-arthur/`

O gerador ficará em:

`https://SEU-USUARIO.github.io/batizado-arthur/gerador.html`

## Personalização

Abra `gerador.html`, digite o nome da pessoa e clique em `Gerar link`.

Exemplos:

`https://SEU-USUARIO.github.io/batizado-arthur/index.html?nome=Maria`

`https://SEU-USUARIO.github.io/batizado-arthur/index.html?nome=Alex`

`https://SEU-USUARIO.github.io/batizado-arthur/index.html?nome=Família%20Silva`

É sempre o mesmo `index.html`; o nome muda pelo parâmetro `?nome=`.

## Atualizações

Quando quiser alterar o convite, substitua apenas o `index.html` no GitHub e faça o commit.
O endereço publicado continua o mesmo.

Se alterar apenas o gerador, substitua somente o `gerador.html`.
