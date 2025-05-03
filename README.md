# Lista Padronizada de Ferramentas e Tecnologias

## 1. Frameworks e Bibliotecas

### Front-end
- [Next.js](https://nextjs.org/) — Framework React fullstack.
- [Chakra UI](https://chakra-ui.com/) — Componentes acessíveis e prontos para uso.
- [Tailwind CSS](https://tailwindcss.com/) — Framework CSS utilitário.
- [Bootstrap](https://getbootstrap.com/) — Framework tradicional para UI com CSS e JS.
- [DaisyUI](https://daisyui.com/) — Componentes baseados em Tailwind.
- [MagicUI](https://magicui.design/docs/components/text-reveal) — Biblioteca com efeitos e animações para Next.js.
- [ShadCN UI](https://ui.shadcn.dev/) — Componentes acessíveis integrados ao Tailwind.

### Back-end
- [Django](https://www.djangoproject.com/) — Framework web em Python.
- [Node.js](https://nodejs.org/pt) — Ambiente de execução JavaScript.
- [TypeScript](https://www.typescriptlang.org/) — Superset tipado de JavaScript.
- [Python](https://www.python.org/) — Linguagem principal para backend.

### Containers e Infraestrutura
- [Docker](https://www.docker.com/) — Contêineres e orquestração.
- [Pulumi](https://www.pulumi.com/) — IaC com linguagens modernas.

## 2. DATABASES

- [MySQL](https://www.mysql.com/) — Sistema de gerenciamento de banco de dados relacional amplamente usado em aplicações web, conhecido pela velocidade e confiabilidade.
- [PostgreSQL](https://www.postgresql.org/) — Banco de dados relacional open-source avançado, com suporte a extensões, JSON, e operações complexas. (Ideal para Django).
- [SQLite](https://www.sqlite.org/) — Banco de dados relacional leve, embutido e sem servidor, ideal para protótipos, testes ou aplicações locais.

## 2. Design, UI e Tipografia

### UI Kits e Sistemas de Design
- [Metronic](https://keenthemes.com/metronic/) — UI kit avançado para dashboards.
  - [Demo](https://preview.keenthemes.com/metronic8/demo8/index.html)
  - [Documentação](https://preview.keenthemes.com/html/metronic/docs/index)

### Design Visual e Wireframes
- [Figma](https://www.figma.com/) — Design colaborativo de interfaces.
- [Canva](https://www.canva.com/) — Criação de layouts, apresentações e materiais gráficos.
- [Whimsical](https://whimsical.com/) — Fluxogramas, wireframes e mapas mentais.
- [Excalidraw](https://excalidraw.com/) — Fluxogramas para apresentações.
- [Storyset](https://storyset.com/) — Ilustrações animadas para UI.

## 3. Integrações e Comunicação

### WhatsApp
- [Waha](https://waha.dev/) — Integração com WhatsApp Business.
- [WhatsApp Business API](https://www.whatsapp.com/business/api) — API oficial.
- [Baileys (GitHub)](https://github.com/WhiskeySockets/Baileys) — Biblioteca JS para conexão via Web WhatsApp.

## 4. DevOps e Infraestrutura

- **Serviços**:
  - [AWS EC2](https://aws.amazon.com/ec2/) — Infraestrutura em nuvem.
  - [Vercel](https://vercel.com/) — Deploy contínuo e escalável para *frontends*. 

- **CI/CD & IaC**:
  - [Pulumi](https://www.pulumi.com/) — Infraestrutura como código.
  - [Terraform](https://www.terraform.io/) — IaC declarativa e amplamente utilizada.

## 5. Testes (Automatizados e Manuais)

- [Robot Framework](https://robotframework.org/) — Framework de testes automatizados.
  - [User Guide](https://robotframework.org/robotframework/latest/RobotFrameworkUserGuide.html)

## 6. Visualização e Manipulação de SVG

- [SVG Viewer](https://www.svgviewer.dev/) — Visualizador e editor SVG online.
- [Heroicons](https://heroicons.com/outline) — Ícones SVG prontos para uso.

## 7. Modelagem e Diagramas

- [Lucidchart](https://www.lucidchart.com/) — Diagramação UML e fluxos.
- [Draw.io / diagrams.net](https://app.diagrams.net/) — Editor gratuito de diagramas.
- [Creately](https://creately.com/) — Diagramas, mapas mentais e modelos visuais.

## 8. Documentação Técnica

- [Docsify](https://docsify.js.org/#/) — Gerador de documentação estática com Markdown.
- [JS Wiki](https://js.wiki/modules) — Wiki moderna baseada em Node.js.
- [Readme.so](https://readme.so/pt/editor) — Editor de arquivos README.md.
- [Dillinger](https://dillinger.io/) — Editor de Markdown online.

## 9. Ferramentas de Apoio

- [Notion](https://www.notion.so/) — Organização de projetos e documentação.
- [Notion Icons](https://notionicons.so/) — Ícones para Notion e outros projetos.
- [Postman](https://www.postman.com/) — Testes de APIs REST.
- [Regex101](https://regex101.com/) — Teste e debug de expressões regulares.
- [Carbon](https://carbon.now.sh/) — Gerador de imagens com trechos de código.
- [CodePen](https://codepen.io/trending) — Exemplos de HTML, CSS, JS em tempo real.
- [Creative Tim](https://www.creative-tim.com/) — Componentes e templates de UI.

## 10. Autenticação e Identidade

- [Clerk](https://clerk.com/) — Autenticação com suporte a redes sociais e integração com Next.js.

## 11. Bibliotecas Úteis para Django

### Core e Extensões do Django
- Django — Framework web principal.
- django-extensions — Comandos e extensões úteis.
- django-cors-headers — Suporte a CORS.
- django-debug-toolbar — Debug visual no navegador.
- python-decouple — Gerenciamento de variáveis de ambiente.

### REST APIs e Autenticação
- djangorestframework — Framework REST para Django.
- djangorestframework-simplejwt — Autenticação via JWT.
- drf-spectacular — Geração de documentação OpenAPI 3 para DRF.
- dj-rest-auth — Endpoints REST de autenticação prontos.
- django-allauth — Autenticação com e-mail, social login e mais.

### Armazenamento e Cache
- django-storages — Armazenamento em nuvem (S3, etc.).
- boto3 — SDK da AWS para Python.
- django-redis — Cache backend usando Redis.

### Dados e Manipulação de Arquivos
- pandas — Análise e manipulação de dados.
- django-pandas — Integração de querysets com pandas.
- PyMuPDF — Leitura e manipulação de PDFs.
- pdfplumber — Extração de texto/tabular de PDFs.
- pillow — Manipulação de imagens.
- holidays — Datas de feriados nacionais e regionais.

### Testes e Desenvolvimento
- pytest — Framework de testes.
- pytest-django — Integração pytest + Django.
- icecream — Ferramenta de debug com prints.
- ipython — Shell interativo avançado.

### Banco de Dados e Deploy
- mysqlclient — Driver MySQL para Django.
- gunicorn — WSGI HTTP Server para produção.
- gevent — Suporte a IO assíncrono com Gunicorn.

### Integrações Externas
- google-auth — Autenticação e integração com APIs Google.
- requests — Requisições HTTP fáceis com Python.
- cryptography — Criptografia e segurança.