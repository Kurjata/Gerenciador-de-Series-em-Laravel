

# Gerenciador de Séries 🎬

Bem-vindo ao projeto Gerenciador de Séries, uma aplicação web moderna projetada para ajudar os entusiastas de séries a organizar e acompanhar suas séries favoritas.

## Índice

- [Gerenciador de Séries 🎬](#gerenciador-de-séries-)
  - [Índice](#índice)
  - [Tecnologias](#tecnologias)
  - [Recursos](#recursos)
  - [Instalação](#instalação)
  - [Configuração](#configuração)
  - [Contribuição](#contribuição)

## Tecnologias

Este projeto é construído com:

- 🌐 **Frontend**: [Bootstrap](https://getbootstrap.com/)
- 🛠️ **Backend**: [Laravel](https://laravel.com/)
- 📦 **Banco de Dados**: [SQLite](https://www.sqlite.org/index.html)

## Recursos

- Adicione, edite e remova séries.
- Marque episódios como assistidos.
- Avalie e comente sobre séries e episódios.
- Visualização moderna e responsiva.

## Instalação

1. **Clone o Repositório**

```bash
git clone https://github.com/kurjata/series-laravel.git
cd series-laravel
```

2. **Instale as Dependências**

```bash
composer install
npm install
```

3. **Configurar Ambiente**

Copie o arquivo `.env.example` e renomeie para `.env`. Atualize as variáveis de ambiente, especialmente as relacionadas ao banco de dados.

4. **Execute as Migrations**

```bash
php artisan migrate
```

5. **Iniciar Servidor de Desenvolvimento**

```bash
php artisan serve
```

Acesse `http://localhost:8000` no seu navegador.

## Configuração

Certifique-se de configurar corretamente as variáveis de ambiente no arquivo `.env`, especialmente:

```
DB_CONNECTION=sqlite
DB_DATABASE=local_do_seu_arquivo_sqlite
```

## Contribuição

Contribuições são sempre bem-vindas!



---

