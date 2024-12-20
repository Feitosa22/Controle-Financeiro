## Curso de roteador de aplicativos Next.js - inicial

Este é o modelo inicial para o curso Next.js App Router. Ele contém o código inicial do aplicativo de painel.

Roteamento aninhado
Next.js usa roteamento de sistema de arquivos onde pastas são usadas para criar rotas aninhadas. Cada pasta representa um segmento de rota que mapeia para um segmento de URL .![alt text](folders-to-url-segments.avif)
Você pode criar interfaces de usuário separadas para cada rota usando arquivos layout.tsxe page.tsx.
Para criar uma rota aninhada, você pode aninhar pastas umas dentro das outras e adicionar page.tsxarquivos dentro delas. Por exemplo:![alt text](dashboard-route.avif)
/app/dashboard/page.tsxestá associado ao /dashboardcaminho. Vamos criar a página para ver como funciona!
