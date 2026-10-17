# Como publicar — Estratégias de Venda

Pasta pronta para hospedar. Não precisa instalar nada, não precisa mexer em código.

**Conteúdo da pasta:**

```
index.html        ← página principal do curso (é esta que vende)
obrigado.html     ← compra aprovada
aguardando.html   ← aguardando pagamento (Pix / boleto)
boas-vindas.html  ← primeiros passos do aluno
404.html          ← página de endereço errado
style.css         ← o visual de todas as páginas
img/              ← as três imagens
```

Todos os botões de compra já apontam para o seu checkout:
`https://chk.eduzz.com/uehzxj2f`

---

## Opção 1 — Netlify (mais rápido, ~2 minutos)

É o caminho mais simples. Não exige conta para publicar.

1. Abra **app.netlify.com/drop**
2. Arraste a pasta `site` inteira para dentro da área indicada na tela
3. Em segundos aparece um endereço do tipo `nome-aleatorio-123.netlify.app` — já está no ar, com HTTPS
4. Clique em **Site configuration → Change site name** e troque para `estrategiasdevendasrda`

Endereço final: **https://estrategiasdevendasrda.netlify.app**

> Crie uma conta gratuita no Netlify logo depois de publicar. Sem conta, o site fica
> temporário e você perde o controle dele.

**Para atualizar depois:** arraste a pasta de novo na área de deploys do site. Substitui tudo.

---

## Opção 2 — GitHub Pages (sua conta já existe: `rdamorim08`)

1. Abra **github.com/new**
2. Nome do repositório: `estrategiasdevendasRDA`
3. Marque **Public** e clique em **Create repository**
4. Na tela seguinte, clique em **uploading an existing file**
5. Arraste todos os arquivos da pasta `site`, **incluindo a pasta `img`**, e clique em **Commit changes**
6. Vá em **Settings → Pages**
7. Em *Source*, escolha **Deploy from a branch**; em *Branch*, escolha **main** e **/ (root)**. Salve.
8. Aguarde de 1 a 3 minutos

Endereço final: **https://rdamorim08.github.io/estrategiasdevendasRDA/**

> Atenção: o repositório precisa ser **Public** para o Pages funcionar no plano gratuito.

---

## Depois de publicar: configurar a Eduzz

No painel da Eduzz, em **Produtos → seu produto → Configurações / Páginas**, aponte cada
situação para o endereço correspondente. Troque `SEU-ENDERECO` pelo endereço que você publicou.

| Situação na Eduzz | Página que deve abrir |
|---|---|
| Compra aprovada / Pagamento confirmado | `SEU-ENDERECO/obrigado.html` |
| Aguardando pagamento (Pix e boleto gerados) | `SEU-ENDERECO/aguardando.html` |
| Boas-vindas / primeiros passos | `SEU-ENDERECO/boas-vindas.html` |

**Exemplo com o Netlify:**

```
https://estrategiasdevendasrda.netlify.app/obrigado.html
https://estrategiasdevendasrda.netlify.app/aguardando.html
https://estrategiasdevendasrda.netlify.app/boas-vindas.html
```

A página `boas-vindas.html` não é disparada automaticamente pela Eduzz. Use-a no e-mail de
entrega do produto ou no botão da `obrigado.html` — ela já está ligada lá.

---

## Domínio próprio (opcional, quando quiser)

Nas duas opções dá para apontar um domínio seu, por exemplo
`estrategias.paracabos.com.br` ou um domínio novo.

- **Netlify:** Domain management → Add a domain
- **GitHub Pages:** Settings → Pages → Custom domain

Em qualquer um dos dois você precisa criar um registro **CNAME** no painel de DNS do domínio
apontando para o endereço do serviço. Se for fazer isso, me chame que eu te passo os valores
exatos para o seu caso.

---

## Antes de divulgar — teste rápido

- [ ] Abrir a página no celular e no computador
- [ ] Clicar em todos os botões e confirmar que abrem o checkout da Eduzz
- [ ] Fazer uma compra de teste (a Eduzz tem modo de teste) e conferir se cai na `obrigado.html`
- [ ] Gerar um Pix de teste e conferir se cai na `aguardando.html`
- [ ] Mandar o link para você mesmo no WhatsApp e ver se a prévia aparece com a imagem certa

---

## Observação sobre a página do ebook

A página do ebook (`PAGINA_VENDAS_EBOOK.html`) ficou de fora desta publicação, conforme
combinado — a principal é a do curso. Quando quiser subir o ebook, é só avisar que eu monto
no mesmo padrão, com link de checkout próprio.
