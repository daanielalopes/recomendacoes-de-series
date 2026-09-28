# Recomendações de Séries

Site estático que reúne recomendações de séries organizadas por gênero. Para cada série há uma sinopse e informações sobre onde assistir e número de temporadas.

## 🎬 Gêneros

- **Ação**
- **Comédia**
- **Drama**
- **Terror**

## ✨ Funcionalidades

- Página inicial com séries em destaque de cada gênero.
- Páginas dedicadas para cada categoria (`paginas/ação`, `paginas/comédia`, `paginas/drama`, `paginas/terror`).
- Sinopse e detalhes (temporadas / onde assistir) de cada série.
- Imagens de capa das séries organizadas por gênero na pasta `img/`.

## 🛠️ Tecnologias

- HTML
- CSS

## 📁 Estrutura do projeto

```
.
├── index.html          # Página inicial com destaques
├── sitefinal.css       # Estilos globais do site
├── logo.png            # Logo / favicon
├── img/                # Imagens das séries, separadas por gênero
│   ├── ação/
│   ├── comédia/
│   ├── drama/
│   └── terror/
└── paginas/            # Páginas de cada gênero (HTML + CSS)
    ├── ação/
    ├── comédia/
    ├── drama/
    └── terror/
```

## 🚀 Como executar

Por ser um site estático, basta abrir o arquivo `index.html` no navegador. Também é possível servi-lo localmente:

```bash
# na raiz do projeto
python3 -m http.server 8000
```

Depois acesse http://localhost:8000 no navegador.
