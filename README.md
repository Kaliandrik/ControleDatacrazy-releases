# Monitoramento DataCrazy — instaladores

Este repositório guarda **só os instaladores** do Monitoramento DataCrazy (Proserv).
Não tem código nem senha: o código fica em um repositório privado.

- **Baixar:** pela ProservStore ou em [Releases](../../releases/latest).
- Os computadores com o programa instalado procuram versão nova aqui sozinhos
  (ao abrir e a cada 4 horas) e mostram "Nova atualização no sistema".

Cada versão publicada precisa ter os 3 arquivos gerados por `npm run dist`:
`Monitoramento-DataCrazy-Setup-<versão>.exe`, o `.exe.blockmap` e o `latest.yml`.
O texto da versão vira a lista de "Novidades" na ProservStore (uma linha por item).
