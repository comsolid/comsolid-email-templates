# Template para e-mails do COMSOLiD

Usando ferramenta de criação de e-mails responsivos [mjml](https://mjml.io/).

Templates para:

* Confirmação de Inscrição
* Confirmação de Reinscrição
* Confirmação de Submissão de Evento
* Recuperação de Senha

## Instalação

```bash
npm install
```

## Desenvolvimento

_Watch_ de um arquivo:

```bash
npx mjml --watch confirmacao-submissao.mjml -o dist/confirmacao-submissao.html
```

Executar servidor `http` embutido:

```bash
npm run serve
```

## Produção

Gerar arquivo minificado:

```bash
npx mjml --config.minify -r confirmacao-submissao.mjml -o dist/confirmacao-submissao.html
```
