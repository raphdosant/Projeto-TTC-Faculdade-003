# 🗂️ Descompactação (.zip)

* Faça o download dos arquivos **ttc.z01** e **ttc.zip** e descompacte o `.zip` usando o WinRAR.
* Isso foi feito porque o GitHub só aceita arquivos de até 25 MB, e o arquivo total tem 28 MB.


# 📌 Projeto Laravel com XAMPP

Este projeto foi desenvolvido utilizando o framework **Laravel**, com gerenciamento de dependências via **Composer** e ambiente local configurado com **XAMPP**.

---

## 🚀 Tecnologias Utilizadas

* PHP
* Laravel
* Composer
* XAMPP (Apache + MySQL)
* Blade (template engine do Laravel)
* HTML, CSS

---

## ⚙️ Requisitos

Antes de rodar o projeto, você precisa ter instalado:

* PHP (versão compatível com Laravel)
* Composer
* XAMPP ou outro servidor local
* Navegador (Chrome, Edge, etc.)

---

## ▶️ Executando o Projeto

Você pode rodar o projeto de duas formas:

### 🔹 Usando o servidor do Laravel:

```bash
php artisan serve
```

### 🔹 Usando o XAMPP:

* Inicie o Apache e MySQL no painel do XAMPP
* Coloque o projeto dentro da pasta `htdocs`
* Acesse no navegador:

```
http://localhost/nome-do-projeto/public
```

---

## 🗄️ Banco de Dados

* Gerenciado via phpMyAdmin (XAMPP)
* Porta padrão: `3306`
* Acesso:

```
http://localhost/phpmyadmin
```

---

## 📂 Estrutura do Projeto

* `app/` → lógica da aplicação (Controllers, Models)
* `resources/views/` → arquivos Blade (frontend)
* `routes/` → definição de rotas
* `public/` → arquivos públicos (CSS, JS, imagens)

---

## 📌 Downloads e Referências

👉 Coloque aqui os links que você usou:

* 🔗 Composer: [[Clique aqui...](https://getcomposer.org/download/)]
* 🔗 XAMPP: [[Clique aqui...](https://www.apachefriends.org/pt_br/index.html)]
* 🎥 Vídeo de referência: [[Clique aqui...](https://www.youtube.com/playlist?list=PLnDvRpP8BnewYKI1n2chQrrR4EYiJKbUG)]

---

## ✍️ Autor

* Grupo Faculdade

---

## 📄 Licença

Este projeto é apenas para fins de estudo.


# 🎁 Comandos composer e artisan (Laravel)

## ======================== COMPOSER ========================

* Criar projeto: composer create-project laravel/laravel nome-do-projeto

* Instalar dependências: composer install

* Atualizar dependências: composer update

* Instalar pacote: composer require nome/pacote

* Remover pacote: composer remove nome/pacote

## ======================== ARTISAN ========================

* Criar Model: php artisan make:model NomeModel

* Model + Migration: php artisan make:model NomeModel -m

* Model completo: php artisan make:model NomeModel -mfsc

* Criar Controller: php artisan make:controller NomeController

* Controller com CRUD: php artisan make:controller NomeController
* –resource

* Criar Migration: php artisan make:migration create_nome_tabela

* Rodar migrations: php artisan migrate

* Resetar banco: php artisan migrate:fresh

* Seeder: php artisan make:seeder NomeSeeder php artisan db:seed

* Factory: php artisan make:factory NomeFactory

* Listar rotas: php artisan route:list

* Instalar autenticação: composer require laravel/breeze –dev php artisan
* breeze:install php artisan migrate

* Limpar cache: php artisan cache:clear php artisan config:clear php
* artisan route:clear php artisan view:clear

* Rodar servidor: php artisan serve
