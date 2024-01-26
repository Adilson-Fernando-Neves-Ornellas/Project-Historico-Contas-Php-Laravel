## Requisitos

* PHP 8.2 ou superior
* Composer
* Node.js 20 ou superior

## Como rodar o projeto baixado
Instalar as dependências do PHP
```
composer install
```

Instalar as dependências do Node.js
```
npm install
```

Duplicar o arquivo ".env.example" e renomear para ".env"
Alterar no arquivo .env o nome da base de dados para "celke". Exemplo: DB_DATABASE=celke

Gerar a chave
```
php artisan key:generate
```

Executar as migration
```
php artisan migrate
```

Executar as seed
```
php artisan db:seed
```

Iniciar o projeto criado com Laravel
```
php artisan serve
```

Executar as bibliotecas Node.js
```
npm run dev
```

Acessar o conteúdo padrão do Laravel
```
http://127.0.0.1:8000/
```

## Sequencia para criar o projeto
Criar o projeto com Laravel
```
composer create-project laravel/laravel laravel-meu-projeto
```

Acessar op diretório onde está o projeto
```
cd laravel-meu-projeto
```

Iniciar o projeto criado com Laravel
```
php artisan serve
```

Acessar o conteúdo padrão do Laravel
```
http://127.0.0.1:8000/
```

Criar Controller
```
php artisan make:controller NomeDaController
```
```
php artisan make:controller ContaController
```

Criar a VIEW
```
php artisan make:view nomeDaView
```
```
php artisan make:view contas/create
```

Criar a migration
```
php artisan make:migration create_contas_table
```

Executar as migration
```
php artisan migrate
```

Criar a model
```
php artisan make:model Conta
```

Criar o arquivo Request com validações
```
php artisan make:request ContaRequest
```

Criar seed
```
php artisan make:seeder ContaSeeder
```

Executar as seed
```
php artisan db:seed
```

Instalar o Vite
```
npm install
```

Instalar o framework Bootstrap
```
npm i --save bootstrap @popperjs/core
```

Instalar o sass
```
npm i --save-dev sass
```

Executar as bibliotecas Node.js
```
npm run dev
```

Traduzir para português
https://github.com/lucascudo/laravel-pt-BR-localization

Instalar a biblioteca para gerar PDF
```
composer require barryvdh/laravel-dompdf
```

Instalar o sweetalert2
```
npm install sweetalert2
```