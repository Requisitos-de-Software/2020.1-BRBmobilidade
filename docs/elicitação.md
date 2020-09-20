# Elicitação de requisitos

Os requisitos são declarações que identificam uma capacidade ou fator de qualidade que ressalta uma necessidade de um produto ou processo voltados a uma solução. Por isso, devemos elicitar os requisitos em prol de uma possível melhoria tanto no processo quanto no produto em si.

A Elicitação de Requisitos é em sumo o processo de obter o máximo de informações sobre o produto em questão e explicitá-las.

A atividade de elicitação deve ser orientada à satisfação do cliente, no caso, orientada aos cidadãos do DF que possuem acesso ao cartão cidadão. Portanto, deve-se aprender a entender as necessidades do cliente, seus conhecimentos e suas reais necessidades.

Para a elicitação, são usadas [Técnicas](#Técnicas) que têm como intuito a coleta de fatos, tais esses que podem ser retirados de agentes (usuários) ou fontes como outros sistemas da empresa, manuais de uso, documentação do próprio sistema, etc.

Além de definir as técnicas, deve ser feita uma [Priorização](#priorização) dos requisitos baseada no perfil dos usuários e na solução geral do produto.

## Técnicas

Para diferentes projetos, diferentes técnicas de elicitação devem ser levantadas. No caso do BRB Mobilidade, o app é limitado apenas a uma parcela da população do DF.

As técnicas escolhidas para elicitação de requisitos do app BRB Mobilidade foram:
- [Instropecção](#introspecção)
- [Observação](#observação)

### Introspecção

  Introspecção é uma técnica muito rica e profunda. Consiste em entender quais propriedades o sistema deve possuir para que seja um sucesso.

#### Contexto

O contexto desta introspecção é de um úsario que busca recarregar o seu cartão.

#### Necessidades Técnicas

- Que o app tenha uma ferramenta para disponilizar locais de recarga
- Que o app possa gerar boleto

#### Necessidades Sociais

- Que tenha opção de ver informações do ponto de recarga (horário de funcionamento, endereço, telefone)

#### Necessidades Individuais

- Customizar o valor de recarga
- Acesso ao saldo atual do cartão
- Acesso ao extrato do cartão
- Poder alterar o cartão

### Observação

A obeservação é uma técnica que possibilita observar no próprio ambiente na qual o software será implantado, as tarefas sendo executadas pelos interessadas, sem interferir no ambiente.

#### Pontos Positivos

- Fácil usabilidade
- Controle de saldo (recarga pelo aplicativo e acesso ao extrato)
- Acesso as linhas e horarios dos ônibus
- Poder cadastrar vários cartões
- Informação sobre pontos de recarga

#### Pontos Negativos
- Área do estudante é a mesma do site, utilizando um navegador dentro do próprio aplicativo
- Não possui acesso as linhas e horariros dos ônibus sem fazer login
- Não possui acesso as informações do ponto de recarga
- A única opção de recarga pelo aplicativo é através de boleto bancário

## Priorização 
  Se há um levantamento de requisitos também é necessário priorizar tais requisitos, de forma a gerar desde o início do desenvolvimento um valor agregado aos clientes a cada entrega. Existem várias formas de priorizar os requisitos levantados pela equipe de desenvolvimento. A priorização não deve ter como base a percepção da equipe de desenvolvimento e sim de acordo com a percepção e necessidades do cliente. Após discutir e estudar com o grupo foi decidido utilizar a técnica de priorização MoSCoW.

### MoSCoW
  O método MoSCoW é uma técnica de priorização simples mas eficaz, é usada para gerenciar recursos eficientemente e organizar entregas com um maior valor atrelado a elas. Esse método possui muitas vantagens, entre elas pode ser apontada a fácil compreensão da técnica a todos os envolvidos incluindo os clientes, fácil de se trabalhar, linguagem simples e não requer conhecimento prévio da técnica para começar a utilizar a tornando a técnica ideal para o projeto do grupo por ser a primeira experiência trabalhando com requisitos de todos os integrantes. Porém entre as desvantagens podemos apontar a necessidade do cliente realmente conhecer o negócio para que a priorização seja feita de forma adequada, encoraja decisões mais subjetivas quanto à priorização de cada interessado e alguns critérios podem chegar a ser ignorados. 

  A nomenclatura é tão simples quanto a técnica, o nome MoSCoW deriva da nomenclatura das 4 categorias de priorização da técnica. Must have, Should have, Could have e Would have. As vogais 'o' estão presentes apenas para que o nome da técnica seja mais reconhecível e pronunciável.

#### Must have
  Prioritários e críticos para o negócio, são extremamente necessários de serem cumpridos para que a entrega seja feita de forma adequada, se um dos requisitos da categoria Must have não é concluído a entrega não pode ser considerada um sucesso. Geralmente estão relacionados a normas ou regras de auditoria ou que afetam diretamente a imagem da empresa que está interessada no produto.

#### Should have
  Importantes mas não necessários para entregar neste momento, pode-se ter outro meio de atender a necessidade Should have que não impacte o andamento da categoria Must have, ou também pode-se esperar um tempo até que comece a ser trabalhado.

#### Could have
  Requisitos desejáveis mas não necessários, geralmente atrelados a providenciar uma satisfação maior aos clientes com um certo esforço de desenvolvimento da equipe. Podem ser atendidos caso haja disponibilidade de recursos ou tempo desde que não ultrapassem a hierarquia de priorização MoSCoW.

#### Would have
  Requisitos menos críticos, com pouco retorno sobre os recursos e tempo investidos e com pouca prioridade, necessitando de concordância dos clientes. Geralmente atrelados a mudanças mais estéticas. Não são planejados para um entrega próxima mas também não serão descartados podendo entrar em uma mudança futura.



## Versionamento
| Versão| Data| Alteração | Integrante |
| :------------- :|:--------------:| :-----------:|:----------:|
| 1.0| 19/09 |Adição da priorização e técnica MoSCoW| [Gabriel Hussein](https://github.com/GabrielHussein)|
| 1.01| 19/09 |Adição da introspecção e observação| [Danilo Domingo](https://github.com/danilow200)|
| 1.02| 20/09 |Adição explicação de Elicitação dos requisitos| [Arthur Paiva](https://github.com/danilow200)|
