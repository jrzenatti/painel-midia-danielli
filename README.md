# publicar/

Esta pasta é um repositório Git **separado** do resto do projeto, feito só
para publicar o dashboard no GitHub Pages.

## Regra de ouro

**Só `index.html` entra aqui.** Nunca copie `credenciais.ini`, os scripts
Python, ou qualquer arquivo da wiki para dentro desta pasta. O repositório
deste diretório é **público** (decisão do usuário, 26/08/2026, aceitando que
os números reais de venda e investimento da Danielli ficam publicamente
acessíveis) — qualquer coisa colocada aqui e enviada com `git push` fica
visível para qualquer pessoa na internet.

`index.html` é gerado automaticamente por `../gerar_html.py`, que já copia o
resultado pra cá. Não editar a mão.

## Como publicar (primeira vez)

Ver instruções completas na wiki: `wiki/conexoes/Dashboard de Acompanhamento - Danielli.md`.
