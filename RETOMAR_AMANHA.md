# Retomar amanhã — Lista de Enxoval

## Projeto
- Repositório: https://github.com/luihzpg/enxoval_gitpages_supabase
- Pasta local: `/mnt/lab_disk/mdown-workspace/tasks_projects/projects_detail/enxoval_gitpages_supabase`
- Projeto original de referência: `shop_gitpages_supabase` — não editar.

## O que já foi feito
- Criado projeto separado para o enxoval.
- Frontend em `index.html`.
- SQL próprio em `supabase-setup.sql`.
- Tabela planejada: `enxoval_items`.
- Workflow de deploy em `.github/workflows/deploy.yml`.
- Workflow de keepalive em `.github/workflows/supabase-keepalive.yml`.
- Código enviado para a branch `main`.
- A URL e a chave pública do novo Supabase já foram configuradas no frontend.

## Pendências para concluir
1. No Supabase, abrir **SQL Editor** e executar todo o conteúdo de `supabase-setup.sql`.
2. No GitHub, abrir **Settings → Pages** e configurar:
   - Source: **Deploy from a branch**
   - Branch: `gh-pages`
   - Folder: `/ (root)`
3. Testar o endereço:
   https://luihzpg.github.io/enxoval_gitpages_supabase/
4. Adicionar ao GitHub Actions os secrets `SUPABASE_URL` e `SUPABASE_ANON_KEY` se quiser ativar o keepalive automático.

## Validação feita
- Push para o GitHub: concluído.
- Supabase: ainda retornava `404` para `enxoval_items`, indicando que o SQL não foi executado.
- GitHub Pages: ainda não estava habilitado no repositório.

Não colocar senha do banco no README, no Git ou no Telegram.
