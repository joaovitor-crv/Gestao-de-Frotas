# Painéis de Consumo de Combustível — CRV

Página única com os três painéis em abas:

| Aba | Página original |
|---|---|
| Colhedoras | https://joaovitor-crv.github.io/Consumo-de-colhedora/ |
| Transbordos | https://joaovitor-crv.github.io/consumo-transbordo/ |
| Caminhões | https://joaovitor-crv.github.io/Consumo-de-caminh-es/ |
| Fadiga e Rastreador | `fadiga.html` neste repositório, lendo a planilha PENDÊNCIAS LIBERTY do Google Planilhas |

**Link:** https://joaovitor-crv.github.io/paineis-consumo/

Cada aba abre a página publicada do repositório de cada painel. Por isso o seletor de semanas, o botão **Gerar PDF** e as metas são os mesmos da página original, e uma semana nova publicada em um desses repositórios aparece aqui automaticamente, sem mexer neste repositório.

A aba Fadiga e Rastreador mostra a cópia da planilha lida às 09:00 e às 15:00, de segunda a sábado, pelo GitHub Actions (`.github/workflows/ler-planilha-fadiga.yml`, que grava `dados/fadiga.csv`). O botão **Atualizar** lê a planilha na hora. Para rodar a leitura agendada à mão: Actions → "Ler planilha de fadiga e rastreador" → Run workflow. A planilha precisa continuar compartilhada como "qualquer pessoa com o link pode ver".

Para abrir direto numa aba, use `#colhedoras`, `#transbordos`, `#caminhoes` ou `#fadiga` no final do link.
