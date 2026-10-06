# CROMA! — site e suporte

Site institucional do CROMA!, em Português (Brasil), com página de suporte própria. HTML e CSS estáticos, responsivos e sem dependências de compilação. As imagens fornecidas foram preservadas.

## Publicar no GitHub Pages

1. Envie os arquivos deste projeto para a branch `main` do repositório `andrezinc/site_macre`.
2. No GitHub, abra **Settings → Pages → Build and deployment → Source** e escolha **GitHub Actions**.
3. Em **Actions**, aguarde o fluxo **Publicar CROMA! no GitHub Pages**. Se necessário, execute-o em **Run workflow**.
4. Confirme que as páginas estão acessíveis antes de usar as URLs em um cadastro.

URLs previstas após a publicação:

- Site: `https://andrezinc.github.io/site_macre/`
- **URL de suporte:** `https://andrezinc.github.io/site_macre/suporte.html`

No campo **Português (Brasil) — URL de suporte**, use a segunda URL quando a publicação estiver concluída. Ela ainda não está publicada apenas por existir nesta pasta.

## Canal de atendimento

O botão de atendimento abre o aplicativo de e-mail do visitante, com o assunto “Suporte CROMA!”, para **andrcosta72@gmail.com**. O endereço também aparece na página para quem prefere copiar e enviar pelo próprio serviço de e-mail. Não há formulário que armazene ou envie dados pelo site.

Não foi inventado um link de loja do aplicativo.

## Visualizar localmente

Na pasta do projeto:

```sh
python3 -m http.server 8000
```

Abra `http://localhost:8000`. A navegação funciona também no subdiretório do GitHub Pages, pois os caminhos internos são relativos.

## Arquivos

- `index.html`: apresentação do aplicativo e seus recursos.
- `suporte.html`: perguntas frequentes e canal de atendimento.
- `styles.css`: identidade visual, acessibilidade e adaptação para celular.
- `.github/workflows/pages.yml`: publicação no GitHub Pages após envio para `main`.

As fontes são carregadas pelo Google Fonts. Se esse serviço estiver indisponível, o navegador usa Arial. O conteúdo e a navegação não dependem de JavaScript.
