IAConfiável — Protótipo da Home

Este repositório contém um protótipo estático da página Home para uma IA que aprende apenas a partir de conteúdos científicos confiáveis.

Arquivos:
- `index.html` — página Home com cards, CTA, área para enviar fontes e feedback.
- `styles.css` — estilos do protótipo.
- `about.html` — página "Sobre Nós" simples.

Como abrir localmente:
- A forma mais simples é abrir `index.html` no navegador (duplo clique).
- Para servir via servidor local (recomendado), rode um servidor HTTP simples. Exemplo com Python (PowerShell):

```powershell
python -m http.server 8000
```

Em seguida abra http://localhost:8000 no navegador.

Próximos passos sugeridos:
- Implementar backend para receber e moderar fontes e feedbacks.
- Indexar PDFs e extrair metadados automaticamente.
- Implementar autenticação para contribuidores e curadores.
- Guardar e exibir metadados das fontes junto às respostas da IA.

Observação: este é um protótipo visual; nenhuma funcionalidade de backend está implementada aqui.