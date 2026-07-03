# Portal de Notícias NewsPHP

Sistema de portal de notícias completo construído com PHP e CodeIgniter 3.

## Funcionalidades

- **Gestão de Conteúdo**: Posts, categorias, tags e páginas customizadas
- **Galeria de Imagens**: Upload e organização de imagens por álbuns
- **Sistema de Comentários**: Comentários com moderação
- **RSS Feeds**: Integração com feeds RSS externos
- **Enquetes**: Criação e gestão de votações
- **Newsletter**: Sistema de inscrições e envio de emails
- **Utilizadores**: Registo, login, perfil e lista de leitura
- **Painel Admin**: Dashboard completo para gestão do portal
- **SEO**: URLs amigáveis, meta tags e sitemap XML
- **Multilingual**: Suporte a múltiplos idiomas
- **Publicidade**: Espaços para anúncios em várias posições

## Tecnologias

- PHP 7+
- CodeIgniter 3
- MySQL/MariaDB
- HTML5/CSS3/JavaScript
- jQuery
- CKEditor (editor WYSIWYG)
- Bootstrap

## Requisitos

- PHP 7.0 ou superior
- MySQL 5.5+ ou MariaDB
- Servidor Apache com mod_rewrite
- cPanel (opcional, para hospedagem)

## Instalação

1. Clone o repositório para o seu servidor

2. Crie uma base de dados MySQL e importe o ficheiro `BASE-DE-DADOS.sql`

3. Configure a ligação à base de dados em `portal/application/config/database.php`:
```php
$db['default']['hostname'] = 'localhost';
$db['default']['username'] = 'seu_utilizador';
$db['default']['password'] = 'sua_senha';
$db['default']['database'] = 'nome_da_base';
```

4. Aceda ao painel admin em `www.seusite.com/admin`

**Credenciais padrão:**
- Email: admin@admin.com
- Senha: admin

## Estrutura do Projeto

```
newsphp-777/
├── portal/
│   ├── application/    # Código da aplicação
│   │   ├── controllers/
│   │   ├── models/
│   │   ├── views/
│   │   ├── config/
│   │   └── libraries/
│   ├── assets/        # Ficheiros estáticos
│   │   ├── admin/
│   │   └── front/
│   ├── system/        # Core do CodeIgniter
│   └── index.php
├── BASE-DE-DADOS.sql  # Estrutura da base de dados
└── Instalacao.txt     # Guia de instalação
```

## Screenshots

Adicione screenshots do seu projeto na pasta `/screenshots` e referencie-os aqui.

## Segurança

- Proteção CSRF ativa
- XSS filtering global
- Passwords encriptadas com Bcrypt
- Prepared statements para queries SQL

## Autor

Patrick Henrique

## Licença

Este projeto é para fins de aprendizagem e portefólio.
