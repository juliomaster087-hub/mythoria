# Mythoria ✦

**Onde cada história ganha vida.**

Mythoria é uma plataforma literária gratuita para leitores e escritores de todos os gêneros. Este repositório contém a primeira versão visual: página inicial, descoberta de histórias, filtros e uma prévia da jornada de criação.

## Estado atual
- [x] Identidade visual fantástica e responsiva
- [x] Página inicial e navegação
- [x] Catálogo demonstrativo
- [x] Busca por título, autor e gênero
- [x] Filtros por gênero
- [x] Prévia do espaço de escrita
- [ ] Cadastro, login e perfis reais
- [ ] Banco de dados de histórias e capítulos
- [ ] Editor com rascunhos privados
- [ ] Publicação de obras
- [ ] Comentários, favoritos e moderação

**Importante:** as histórias exibidas são demonstrativas. Cadastro, publicação e leitura de obras de usuários serão implementados nas próximas etapas. A ideia digitada no formulário de escrita fica apenas no armazenamento local do navegador.

## Executar localmente
Abra o arquivo index.html no navegador ou use um servidor estático, como npx serve .

## Cloudflare
A configuração wrangler.jsonc usa Workers Static Assets. Para publicar manualmente, instale Wrangler e execute:

    npx wrangler deploy

Para builds automáticos, conecte este repositório ao Cloudflare Workers Builds e configure o diretório de assets como a raiz do projeto.

## Próximas etapas
1. Configurar autenticação e banco de dados.
2. Criar o fluxo de escrita, rascunho e publicação.
3. Implementar leitor de capítulos e comunidade.
4. Adicionar moderação, privacidade e proteção de conteúdo.

Feito com imaginação. ✧
