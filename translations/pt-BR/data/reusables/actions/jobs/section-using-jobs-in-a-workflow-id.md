---
ms.openlocfilehash: dd25f74bf039724130494c7bd4d55e44760f620b
ms.sourcegitcommit: 47bd0e48c7dba1dde49baff60bc1eddc91ab10c5
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 09/05/2022
ms.locfileid: "145094355"
---
Use `jobs.<job_id>` para fornecer ao seu trabalho um identificador exclusivo. A chave `job_id` é uma cadeia de caracteres, e o valor dela é um mapa dos dados de configuração do trabalho. Você precisa substituir `<job_id>` por uma cadeia de caracteres exclusiva para o objeto `jobs`. A `<job_id>` precisa começar com uma letra ou `_` e conter apenas caracteres alfanuméricos, `-` ou `_`.

#### Exemplo: Criando trabalhos

Neste exemplo, dois trabalhos foram criados, e os valores de `job_id` são `my_first_job` e `my_second_job`.

```yaml
jobs:
  my_first_job:
    name: My first job
  my_second_job:
    name: My second job
```
