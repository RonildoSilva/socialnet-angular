# SocialNet (Angular + Firebase)

> Início de uma rede social em Angular 13 com Angular Material, Bootstrap 5 e Firebase: telas de login, registro e home protegida por guard de rota.

![status](https://img.shields.io/badge/status-incompleto-orange) ![angular](https://img.shields.io/badge/Angular-13-red) ![firebase](https://img.shields.io/badge/Firebase-9-orange) ![material](https://img.shields.io/badge/Angular%20Material-13-blue)

## Sobre
Projeto pessoal iniciado em dezembro de 2021. Foram criados o módulo de rotas, os componentes de login, registro e home, um módulo com os componentes do Angular Material e o guard `SocialNetGuard`. A integração com o Firebase (`@angular/fire`) está configurada, mas não há fluxo de autenticação nem persistência implementados.

## Estrutura de pastas
```text
src/app/
├── app-routing/            rotas
├── components/{home,login,register}/
├── guards/social-net.guard.ts
└── shared/material/material.module.ts
firebase.json               configuração de hosting
DEP.md                      dependências instaladas
```

## Como executar
```bash
npm install && npm start   # http://localhost:4200
```

## Status
Incompleto; parado na tela de login.

## Autor
Ronildo Silva · ronildo.comp@gmail.com
