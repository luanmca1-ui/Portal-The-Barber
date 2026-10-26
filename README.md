# Portal The Barber Express — código do servidor (compilado)

Arquivos gerados automaticamente pelo build do portal. **Não editar à mão.**

- `portal-core-<hash>.mjs`: código do servidor (mesmo conteúdo publicado no site), em módulo ES.
  A Edge Function `portal` do Supabase importa este arquivo pelo jsDelivr, fixado pelo commit,
  no momento da publicação da função — assim ela não baixa nada do site a cada inicialização.
- Sem senhas, chaves ou dados: os segredos ficam nas variáveis do Supabase e os dados no banco.
