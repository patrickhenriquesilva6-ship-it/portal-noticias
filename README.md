# Portal de Notícias Vale do Aço

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

```

## Screenshots

Adicione screenshots do seu projeto na pasta `/screenshots` e referencie-os aqui.

## Segurança

- Proteção CSRF ativa
- XSS filtering global
- Passwords encriptadas com Bcrypt
- Prepared statements para queries SQL


