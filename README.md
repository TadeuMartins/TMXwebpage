# TMX Smart Industry — Tadeu Martins (layout com hero e galeria)

## Como editar
Abra `index.html` e ajuste o bloco:
```html
<script id="site-content" type="application/json">
{ ... }
</script>
```
- `theme.heroImage` → já aponta para `assets/hero.png` (troque a imagem nessa pasta se quiser).
- `galeria.imagens` → lista de imagens que aparecem na galeria (use caminhos da pasta `assets/`).
- `trajetoria`, `formacoes`, `artigos`, `tmxsmartpm`, `livro`, `contato`.

## Publicar no GitHub Pages
1. Crie o repositório `SEUUSUARIO.github.io` e envie todos os arquivos desta pasta (incluindo `assets/`).
2. Em Settings → Pages, selecione **Deploy from a branch** (`main`, `/ (root)`).
3. Para usar `tmxsmartindustry.com.br`, adicione o arquivo **CNAME** (já incluído neste pacote) e aponte seu DNS para os IPs do GitHub Pages (A: 185.199.108.153 / .109 / .110 / .111) e um CNAME `www` → `SEUUSUARIO.github.io`.
4. Ative **Enforce HTTPS** quando o certificado for emitido.

## Dica
Para trocar imagens, substitua os arquivos em `assets/` mantendo os nomes, ou edite os caminhos no JSON.
