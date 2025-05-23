# 🚀 Systex Template Laravel

[![Laravel](https://img.shields.io/badge/Laravel-11-red.svg)](https://laravel.com/)
[![PHP](https://img.shields.io/badge/PHP-8.2-blue.svg)](https://www.php.net/)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
[![Status](https://img.shields.io/badge/status-Production-brightgreen.svg)]()
[![Made by Systex](https://img.shields.io/badge/Made%20by-Systex%20Sistemas-blue.svg)](https://systex.com.br/)

---

## 📜 Descrição

Template base para desenvolvimento de sistemas com Laravel, utilizando autenticação, dashboard, painel administrativo e layout profissional (Mazer). Ideal para acelerar a criação de novos projetos web com uma base sólida, limpa e bem estruturada.

---

## 🚀 Tecnologias

- **PHP 8.2**
- **Laravel 11**
- **Blade**
- **Tailwind CSS / Bootstrap**
- **MySQL / MariaDB**
- **JavaScript (Vite)**
- **Git e GitHub**

---

## ✨ Funcionalidades do Template

- 🔐 Autenticação completa (login, logout, reset de senha)
- 🖥️ Layout responsivo baseado no template **Mazer**
- 🎯 Dashboard inicial configurado
- 🔥 Estrutura MVC organizada
- 🔐 Middleware `auth` e `admin`
- 🚀 Pronto para deploy em hospedagens, VPS ou cloud
- 📦 Suporte a build front-end com Vite
- 📈 Escalável, limpo e modular

---

## 📦 Instalação

1️⃣ Clone este repositório:

```bash
git clone https://github.com/manoelfilhodev/systex-template.git
cd systex-template
```

2️⃣ Instale as dependências PHP:
```bash
composer install
```

3️⃣ Instale as dependências frontend (opcional):
```bash
npm install && npm run build
```
4️⃣ Configure o ambiente:
```bash
cp .env.example .env
php artisan key:generate
```
5️⃣ Configure o banco no .env e execute as migrations:
```bash
php artisan migrate
```
6️⃣ Rode o servidor local:
```bash
php artisan serve
Acesse: http://localhost:8000
```

## 🔥 Como Usar como Template
No GitHub, clique em "Use this template" para criar um novo projeto baseado nesse repositório.

## 🧠 License
Este projeto está licenciado sob a licença MIT - veja o arquivo LICENSE para mais detalhes.

## 💻 Desenvolvido por
SYSTEX Sistemas Inteligentes
🌐 systex.com.br
📧 contato@systex.com.br

## Feito com 💻, ☕ e 🚀 por Manoel Filho • SYSTEX Sistemas Inteligentes