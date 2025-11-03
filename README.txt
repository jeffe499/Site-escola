Site final - Colégio Estadual Presidente Vargas (versão final)

Arquivos principais:
- index.html
- projetos.html
- about.html
- professores.html
- alunos.html
- secretaria.html
- calendario.html
- matricula.html
- estilos/styles.css
- scripts/main.js, scripts/news.js, scripts/gallery.js, scripts/projects.js
- data/*.json (school, news, projects, teachers, boletim)
- imagens/*.svg (logo e fotos)

Instruções:
- Você pode abrir index.html diretamente. O site contém dados embutidos e funciona offline.
- Para testar fetch() (data/*.json) em navegadores que bloqueiam file://, rode:
    python -m http.server 8000
  e acesse http://localhost:8000

Funcionalidades principais (demo):
- Notícias com modal e filtro
- Projetos: listagem, busca, filtro, paginação, modal de detalhe
- Professores com perfis
- Galeria com lightbox
- Formulários de contato e matrícula (salvos no localStorage)
- Newsletter (localStorage)
