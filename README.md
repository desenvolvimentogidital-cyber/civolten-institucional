# CIVOLTEN — Site Institucional

Site público independente da plataforma privada **CIVOLTEN Orçamentos**. Esta aplicação estática não acessa o banco de dados do sistema de orçamentos, não utiliza autenticação nem compartilha configurações com ele.

## Publicação na Vercel

1. Abra https://vercel.com/new e importe o repositório `desenvolvimentogidital-cyber/civolten-institucional`.
2. Mantenha a **Root Directory** em `./`, o framework em **Other** (HTML estático), e deixe Build Command vazio.
3. Publique em produção. A Vercel servirá `index.html` na raiz.

## Conteúdo

- `index.html`: site e seções de apresentação;
- `assets/styles.css`: layout desktop/mobile;
- `assets/script.js`: menu responsivo;
- `assets/images/`: identidade visual e imagens otimizadas;
- `vercel.json`: cabeçalhos HTTP de segurança;
- `robots.txt`: descoberta pública.

## Antes da divulgação

Imagens de serviços e projetos são **ilustrativas**, não fotografias de obras executadas pela CIVOLTEN. Antes de usar comercialmente, revise os serviços descritos, inclua fotografias autorizadas, e forneça um contato oficial para orçamentos. O site não tem formulário de contato funcional e não inventa telefone, e-mail, projetos concluídos nem avaliações de clientes.

Este repositório deve permanecer **totalmente separado** do repositório `CIVOLTEN` usado pelo sistema financeiro interno.
