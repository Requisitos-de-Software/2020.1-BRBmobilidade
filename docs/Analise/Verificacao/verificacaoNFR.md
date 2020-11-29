# Verificação - NFR

 Este documento visa verificar o Framework NFR para detectar os erros e defeitos antes de finalizar o projeto. Os NFRs serão analisados a forma como foram escritos e organizados. Foi utilizado o Checklist com critérios de aceitação para fazer essa verificação, o que facilita a identificação de erros.

## Checklist - NFR

1. Os Softgoals são claros?
2. As contribuições são classificadas?
3. Os critérios são classificados em grau de satisfação?
4. Os operadores tem finalidades definidas?
5. Softgoals descritos como objetos?
6. Operadores descritos como verbos?

## Inspeção

A inspeção é feita para a verificação de cada NFR seguindo os critérios desccritos acima.

| Cenário          |Critério 1|Critério 2|Critério 3|Critério 4|Critério 5|Critério 6|
|------------------|----------|----------|----------|----------|----------|----------|
| NFR Desempenho   | ✔        |      ✔   |     ✔    |✔         |✔         |✔         |
| NFR Portabilidade| ✔        |      ✔   |     ✔    |✔         |❌        |✔         |
| NFR Usabilidade  | ✔        |      ✔   |     ✔    |✔         |✔         |✔         |
| NFR Segurança    | ✔        |      ✔   |     ✔    |✔         |❌        |✔         |
| Total            |100%      |      100%|   100%   |100%      | 50%      |100%      |

## Versionamento
| Versão| Data| Alteração | Integrante |
| :------------- :|:--------------:| :-----------:|:----------:|
| 1.0| 08/11 |Adição da verificação dos NFRs|  [Gabriel Hussein](https://github.com/GabrielHussein)|
| 1.1| 29/11 |Adição do nível de aceitação total|  [Arthur Paiva](https://github.com/arthurpaivat)|