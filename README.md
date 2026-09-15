# rclone-personal-oauth

Site estático para o aplicativo OAuth pessoal `rclone-personal`.

## Publicar no GitHub Pages

1. Crie um repositório público chamado, por exemplo, `rclone-personal-oauth`.
2. Extraia esta pasta em `K:\GIT HUB PAGES\rclone-personal-oauth`.
3. Abra PowerShell nessa pasta e execute:

```powershell
git init
git add .
git commit -m "Publica páginas OAuth do rclone-personal"
git branch -M main
git remote add origin https://github.com/SEUUSUARIO/rclone-personal-oauth.git
git push -u origin main
```

4. No GitHub, abra **Settings > Pages**.
5. Em **Build and deployment**, selecione **Deploy from a branch**.
6. Escolha `main` e `/ (root)`.
7. Salve.

## URLs esperadas

```text
https://SEUUSUARIO.github.io/rclone-personal-oauth/
https://SEUUSUARIO.github.io/rclone-personal-oauth/privacy.html
https://SEUUSUARIO.github.io/rclone-personal-oauth/terms.html
```

## Google Auth Platform

**Página inicial do aplicativo**
```text
https://SEUUSUARIO.github.io/rclone-personal-oauth/
```

**Política de Privacidade**
```text
https://SEUUSUARIO.github.io/rclone-personal-oauth/privacy.html
```

**Termos de Serviço**
```text
https://SEUUSUARIO.github.io/rclone-personal-oauth/terms.html
```

**Domínio autorizado**
```text
SEUUSUARIO.github.io
```

Não inclua `https://` no campo de domínio autorizado.

## Nunca envie para o GitHub

- `rclone.conf`
- client secret
- access token
- refresh token
- chaves privadas
- arquivos `.env`
- credenciais Google
