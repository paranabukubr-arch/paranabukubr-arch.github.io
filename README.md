# Site do estúdio (Paranabuku Games)

Site estático, sem build. Contém:
- `index.html` — página do estúdio
- `flight-strike/` — página do jogo
- `privacidade/` — política de privacidade (PT + EN), usar a URL desta página na Play Console e no AdMob
- `app-ads.txt` — autoriza o AdMob a vender anúncios do seu app (`pub-9242628812745246`)

## Antes de publicar
1. Troque `EMAIL_DE_CONTATO` (3 lugares: `index.html` e 2× em `privacidade/index.html`) pelo e-mail de desenvolvedor.
2. Quando o app estiver na loja, troque o botão "Google Play (em breve)" em `flight-strike/index.html` pelo link real.

## Publicar grátis no GitHub Pages
1. No GitHub, crie um repositório público chamado **paranabukugames.github.io** (com o seu usuário/organização no lugar de `paranabukugames`, se for diferente).
2. Envie o conteúdo desta pasta para a raiz do repositório.
3. Settings → Pages → Branch `main` / pasta `/ (root)` → Save.
4. Em alguns minutos o site fica em `https://SEU-USUARIO.github.io/`.

## app-ads.txt
- O AdMob procura o arquivo na **raiz do domínio** do site cadastrado na Play Console (ex.: `https://SEU-USUARIO.github.io/app-ads.txt`). Por isso o site precisa ser o repositório `SEU-USUARIO.github.io` (raiz), e não um subcaminho.
- Depois de publicar, cadastre a URL do site no campo "Site" da ficha da Play Store e confira em AdMob → Apps → app-ads.txt.
