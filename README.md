# ☕ Coffee Beans Experience

Experiência interativa de alta fidelidade visual (Awwwards / Apple-style motion), clonada e otimizada por **Lucas Lavarini**.

## 🚀 Tecnologias & Engenharia Reversa
- **Híbrido 2.5D / 3D Canvas Scrubbing:** 96 frames pré-renderizados em WebP sincronizados com o scroll da viewport (`desktop` e `mobile`).
- **WebGL Hardware Alpha-Matte Video Shader:** Decodificação de vídeos com transparência na GPU sem dependência de codecs pesados ou ProRes.
- **Tipografia:** `Abril Fatface` + `Plus Jakarta Sans`.
- **Paleta Visual:** `#FAF7F2` (Linen / Papel cru de cafeteria artesanal) & `#23120B` (Espresso Noir).
- **Performance:** 60-120 FPS cravados, bundle ultra-leve.

## 🛠️ Como Rodar Localmente
```bash
npx serve .
```
Ou abra o `index.html` em um servidor local.

## 🌐 Deploy
Publicado via Vercel com caching de 1 ano imutável em `/media/**` e `/assets/**`.
