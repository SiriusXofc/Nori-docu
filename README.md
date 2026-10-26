# Nori API documentation

Documentação pública da Nori API, construída com [Mintlify](https://mintlify.com).

O conteúdo cobre apenas endpoints públicos em `https://api.nori.qzz.io`. Rotas autenticadas de dashboard, tickets, painéis, configurações, auditoria, métricas e storage ficam fora deste site.

## Desenvolvimento local

Instale o CLI do Mintlify e execute:

```bash
npm install -g mint
mint dev
```

Abra `http://localhost:3000` para revisar o site.

## Publicação

O repositório é conectado ao deploy da Mintlify. Pushes para `main` são publicados automaticamente quando a integração do GitHub está ativa.

## Fonte do contrato

Os endpoints foram conferidos contra o registro de rotas e os handlers públicos do repositório `api-Nori`. A documentação não inventa rotas protegidas nem expõe segredos de runtime.
