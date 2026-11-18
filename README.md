# Instalação do projeto

Clone o repositório e entre na pasta do projeto:

```bash
git clone git@github.com:SimaoNevesCurado/checkers.git <NOME_DA_PASTA>
ou
git clone https://github.com/SimaoNevesCurado/checkers.git <NOME_DA_PASTA>

cd <NOME_DA_PASTA>
```

## API (Laravel)

Na raiz do projeto, instale as dependências e configure a base de dados:

```bash
cd api
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate:fresh --seed
```

Inicie a API:

```bash
composer run dev
```

## Frontend (Vue)

Num novo terminal, a partir da raiz do projeto:

```bash
cd frontend
npm install
npm run dev
```

## WebSockets (Socket.IO)

Num novo terminal, a partir da raiz do projeto:

```bash
cd websockets
npm install
npm run dev
```
