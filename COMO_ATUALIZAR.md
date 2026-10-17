# Como atualizar o site no GitHub

Site no ar em: **https://rdamorim08.github.io/estrategiasdevendas/**

Esta pasta é a versão 2. Substitui a anterior inteira.

## O que mudou nesta versão

1. Todo contato passou a ser **rdamorim08@gmail.com**. O endereço antigo não aparece mais em lugar nenhum.
2. Os travessões foram retirados de todos os textos. As frases foram reescritas, não apenas cortadas, para o texto continuar fluindo bem.
3. O endereço do site foi corrigido nas prévias de compartilhamento, agora apontando para `estrategiasdevendas` e não mais para o nome antigo.
4. O ícone de fechar das perguntas frequentes virou um sinal de menos de verdade.

## Arquivos da pasta

```
index.html        página principal do curso
obrigado.html     compra aprovada
aguardando.html   aguardando pagamento (Pix ou boleto)
boas-vindas.html  primeiros passos do aluno
404.html          endereço errado
style.css         o visual de todas as páginas
img/              hero.jpg, bio.jpg, 3d3r.jpg
```

Todos os botões de compra apontam para `https://chk.eduzz.com/uehzxj2f`.

## Como subir a atualização

1. Abra **github.com/rdamorim08/estrategiasdevendas**
2. Clique em **Add file** e depois em **Upload files**
3. Arraste todos os arquivos desta pasta, **incluindo a pasta `img`**
4. Role até o fim e clique em **Commit changes**
5. Aguarde de 1 a 3 minutos e recarregue o site

O GitHub substitui os arquivos de mesmo nome automaticamente. Você não precisa apagar nada antes.

> Se o site continuar mostrando a versão antiga depois de 3 minutos, force a recarga:
> **Cmd + Shift + R** no Mac. É o navegador guardando a versão anterior em cache.

## Conferir depois de subir

- [ ] Abrir o site no celular e no computador
- [ ] Clicar em todos os botões e confirmar que abrem o checkout da Eduzz
- [ ] Procurar o e-mail no rodapé e confirmar que está o rdamorim08@gmail.com
- [ ] Abrir `/obrigado.html`, `/aguardando.html` e `/boas-vindas.html` direto na barra de endereço
- [ ] Mandar o link para você mesmo no WhatsApp e ver se a prévia mostra a imagem certa

## Endereços para configurar na Eduzz

No painel da Eduzz, em **Produtos**, no seu produto, em **Configurações** ou **Páginas**:

| Situação | Endereço |
|---|---|
| Compra aprovada | `https://rdamorim08.github.io/estrategiasdevendas/obrigado.html` |
| Aguardando pagamento | `https://rdamorim08.github.io/estrategiasdevendas/aguardando.html` |
| Boas-vindas (e-mail de entrega) | `https://rdamorim08.github.io/estrategiasdevendas/boas-vindas.html` |

A página de boas-vindas não tem gatilho automático na Eduzz. Ela serve para o e-mail de entrega do produto. O botão da página de compra aprovada já leva o aluno até ela.

## Domínio próprio, quando quiser

Em **Settings**, **Pages**, campo **Custom domain**, você pode apontar um domínio seu, por exemplo `estrategiasdevendas.com.br`. Depois é preciso criar um registro CNAME no painel de DNS do domínio apontando para `rdamorim08.github.io`. Se for fazer isso, me chame que eu te passo os valores exatos.
