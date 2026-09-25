# Site SBMP

Site institucional da Sociedade Brasileira de Medicina Personalizada, desenvolvido em código (sem WordPress).

## Estrutura

- `index.html` — site institucional (Início, Quem somos, Diretoria, Associados, Artigos, Imprensa) com menu fixo.
- `associar/` — formulário de associação, integrado ao Asaas, com a mesma barra de menu.
- `logo.png`, `associar/logo-sbmp.png` — identidade visual.

## Observação

Nesta versão, os dados de **Associados**, **Artigos** e **Na mídia** são exemplos (mockup),
apenas para demonstrar o formato. Na versão final:

- **Associados** é gerado automaticamente da base unificada (apenas associados ativos; só nome, especialidade e UF).
- **Diretoria** recebe fotos, minicurrículos e links reais.
- **Artigos** e **Na mídia** são cadastrados em planilha.
- **Instagram** puxa o feed da conta profissional (Meta Business).

## Publicação (GitHub Pages)

Repositório configurado para GitHub Pages servir a partir da raiz.
