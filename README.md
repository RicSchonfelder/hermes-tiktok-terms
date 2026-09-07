# Hermes TikTok Terms

Páginas estáticas relacionadas à integração do Hermes com o TikTok: termos de uso, política de privacidade e callback de autorização OAuth.

## Arquivos

- `index.html`: página inicial da integração.
- `privacy.html`: política de privacidade.
- `oauth-callback.html`: página de retorno após autorização OAuth.
- `tiktokOL8xjhmviPncf4obFpKZZ8H4son6ZP8x.txt`: arquivo de verificação exigido pelo TikTok.

## Publicação

Publique os arquivos em um domínio HTTPS que esteja configurado no aplicativo TikTok. O endereço de callback configurado no TikTok deve apontar para `oauth-callback.html`.

Antes de publicar, confirme no painel do TikTok as URLs de termos, privacidade e redirect URI. Não coloque client secret, access token ou qualquer credencial neste repositório.
