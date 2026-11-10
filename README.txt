SAVIOR STORE — VERSÃO CORRIGIDA PARA GITHUB PAGES E ACODE

PÁGINA INICIAL
- index.html: apresentação pública da loja (é a página que o GitHub Pages abre automaticamente).
- entrar.html: login e criação de conta.

ESTRUTURA
- css/style.css: estilos.
- js/data.js: dados e armazenamento local.
- js/auth.js: login, registo e sessão.
- js/admin.js: gestão administrativa.
- js/reseller.js: funcionalidades do revendedor.
- admin/dashboard.html: painel administrativo.
- revendedor/: páginas separadas do revendedor.

PUBLICAR NO GITHUB PELO TELEMÓVEL
1. Extrair este ZIP.
2. Abrir o repositório Savior-Store no GitHub.
3. Remover ou substituir os ficheiros antigos que estejam na raiz, para evitar versões duplicadas.
4. Enviar o CONTEÚDO desta pasta para a raiz do repositório. Não enviar a pasta SaviorStore_GITHUB_CORRIGIDA como uma pasta dentro do repositório.
5. Confirmar que index.html, css/, js/, admin/ e revendedor/ aparecem directamente na página principal do repositório.
6. Em Settings > Pages, escolher Deploy from a branch, branch main e folder /(root), se ainda não estiver configurado.

TESTAR NO ACODE
Abra a pasta extraída e execute index.html. A apresentação pública aparece primeiro. Use Entrar / Criar conta para abrir entrar.html.

CONTAS DE DEMONSTRAÇÃO
Administrador: admin / admin123
Revendedor: revendedor / revendedor123

NOTA
Protótipo académico front-end. Os dados ficam no localStorage do navegador e não sincronizam entre dispositivos. As imagens externas precisam de Internet. Não usar as credenciais de demonstração em produção.
