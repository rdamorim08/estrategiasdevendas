# Como atualizar o site no GitHub

Site no ar em: **https://rdamorim08.github.io/estrategiasdevendas/**

Esta é a versão 4. Substitui a anterior inteira.

## O que mudou nesta versão

1. **Nova foto de topo.** A imagem do xadrez sem o texto cravado entrou no lugar da antiga, que era o slide com "ESTRATÉGIAS DE VENDA" escrito por cima. O enquadramento foi ajustado para você aparecer à direita, livre do título.
2. **Seu retrato voltou para a seção "Quem ensina".** A foto da poltrona, recortada em proporção 4 por 5 e otimizada para carregar rápido.
3. A seção do autor voltou ao layout de duas colunas, com o texto à esquerda e a foto à direita. No celular, a foto desce para baixo do texto.

## Arquivos da pasta

```
index.html        página principal do curso
obrigado.html     compra aprovada
aguardando.html   aguardando pagamento (Pix ou boleto)
boas-vindas.html  primeiros passos do aluno
404.html          endereço errado
style.css         o visual de todas as páginas
img/hero.jpg      foto do xadrez, usada no topo
img/bio.jpg       seu retrato, usado na seção "Quem ensina"
img/3d3r.jpg      o quadro dos 3 D's e 3 R's
```

Todos os botões de compra apontam para `https://chk.eduzz.com/uehzxj2f`.

## Como subir a atualização

1. Abra **github.com/rdamorim08/estrategiasdevendas**
2. Clique em **Add file** e depois em **Upload files**
3. Arraste todos os arquivos desta pasta, **incluindo a pasta `img`**
4. Role até o fim e clique em **Commit changes**
5. Aguarde de 1 a 3 minutos e recarregue o site

O GitHub substitui os arquivos de mesmo nome automaticamente, inclusive as imagens.

> Se o site continuar mostrando a versão antiga depois de 3 minutos, force a recarga com
> **Cmd + Shift + R** no Mac. É o navegador guardando a versão anterior em cache.
> Com imagens trocadas, isso acontece com frequência.

## Conferir depois de subir

- [ ] Abrir o site no celular e no computador
- [ ] Confirmar que o topo mostra a foto do xadrez sem texto escrito por cima
- [ ] Confirmar que o seu retrato aparece na seção "Quem ensina"
- [ ] Clicar em todos os botões e confirmar que abrem o checkout da Eduzz
- [ ] Clicar no Instagram do rodapé e confirmar que abre o perfil `rafaelamorimof`
- [ ] Clicar no YouTube do rodapé e confirmar que abre o canal `@RAFAELAMORIMOF`
- [ ] Abrir `/obrigado.html`, `/aguardando.html` e `/boas-vindas.html` direto na barra de endereço

## Endereços para configurar na Eduzz

| Situação | Endereço |
|---|---|
| Compra aprovada | `https://rdamorim08.github.io/estrategiasdevendas/obrigado.html` |
| Aguardando pagamento | `https://rdamorim08.github.io/estrategiasdevendas/aguardando.html` |
| Boas-vindas (e-mail de entrega) | `https://rdamorim08.github.io/estrategiasdevendas/boas-vindas.html` |

A página de boas-vindas não tem gatilho automático na Eduzz. Ela serve para o e-mail de entrega do produto. O botão da página de compra aprovada já leva o aluno até ela.

## A terceira imagem que você mandou

O banner "Oi turma, eu sou o Rafael Amorim" já tem texto e chamada próprios, então não entrou no site. Ele funciona melhor como capa de vídeo no YouTube, como primeiro slide de um story ou como abertura da aula 0.1 do curso. Se quiser usar em alguma página, me diga onde que eu encaixo.

## Domínio próprio, quando quiser

Em **Settings**, **Pages**, campo **Custom domain**, você pode apontar um domínio seu. Depois é preciso criar um registro CNAME no painel de DNS do domínio apontando para `rdamorim08.github.io`. Se for fazer isso, me chame que eu te passo os valores exatos.
