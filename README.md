# Registo Cais

Aplicação web para registar entradas e saídas de estafetas, viaturas e pessoas.

Os registos podem ser exportados para CSV ou impressão. A aplicação também suporta uso offline e, quando disponível no navegador, ditado por voz.

Por defeito, os dados ficam no `localStorage` do navegador. O repositório também contém a estrutura opcional de sincronização com Supabase.

Para testar localmente:

```bash
python -m http.server 8080
```

Depois, abra `http://localhost:8080`.
