# AutoTrend BlogAI

Micro SaaS que cria e publica artigos automaticamente sobre os assuntos mais comentados da semana.
services:
  - type: web
    name: autotrend-blogai
    env: node
    plan: free
    branch: main
    buildCommand: cd api && npm install
    startCommand: node index.js
    rootDir: api

