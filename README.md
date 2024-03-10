# Fluxo da página de doação de alimentos


## Descrição geral

O objetivo da página de doação de alimentos é conectar doadores e beneficiários de alimentos, facilitando o combate à fome e ao desperdício. O escopo da página é permitir que diferentes tipos de doadores (empresas, restaurantes e ONGs) se cadastrem para doar alimentos, e que beneficiários (pessoas físicas) visualizem os pontos de doação de alimentos e possam solicitar ou retirar os alimentos.

| Elemento | Descrição |
| :--- | :--- |
| Descrição geral | O objetivo e o escopo do sistema |
| Atores | As entidades que interagem com o sistema |
| Casos de uso | As ações que os atores podem realizar no sistema |
| Cenários | As sequências de passos que descrevem como os casos de uso são executados |
| Requisitos não funcionais | As características de qualidade do sistema |

## Atores

- Doador: é uma entidade que se cadastra para doar alimentos, podendo ser uma empresa, um restaurante ou uma ONG. Um doador pode criar, editar e excluir seus dados de cadastro, bem como os dados dos alimentos disponíveis para doação.
- Beneficiário: é uma pessoa física que visualiza os pontos de doação de alimentos e pode solicitar ou retirar os alimentos. Um beneficiário pode criar, editar e excluir seus dados de cadastro, bem como filtrar e ordenar os pontos de doação de acordo com seus critérios.
- Administrador: é uma entidade responsável pelo gerenciamento da página de doação de alimentos. Um administrador pode criar, editar e excluir os dados de todos os doadores e beneficiários, bem como monitorar e avaliar o funcionamento da página.

## Páginas 
![TP3D3OCm38NldiBYpWeLX1yuie95N1g99fAJ3j1HgXuwGIV8OgtW4Ah2yPE_zvxamWUISBlE83m6ijFCc2csV3QZ8J4kG_9ORgz3V4p64ch6Fr5jnNWNtjSgs7gr8-raETG7GzfHVCNdccvsHtHgQN_g1sU3ywdbpHuPXOCHqhG4keFPDReeFK29kPZf4l8JAb09AgWJDD0a](https://github.com/LaiFrance/PUC-MINAS-GRUPO-2-DOACAO-DE-ALIMENTOS/assets/91226847/cc8bcf94-b55d-4c09-be36-26fd43fe1c27)


| Caso de uso | Ator | Descrição | Cenário |
| :--- | :--- | :--- | :--- |
| Cadastrar-se como doador | Doador | Um doador pode se cadastrar na página de doação de alimentos, fornecendo seus dados pessoais e os dados dos alimentos disponíveis para doação | - O doador acessa a página de doação de alimentos e clica no botão "Cadastrar-se como doador" <br> - O doador preenche um formulário com seus dados pessoais e clica no botão "Enviar" <br> - O doador recebe uma mensagem de confirmação de cadastro e é redirecionado para a sua área de doador <br> - O doador preenche um formulário com os dados dos alimentos disponíveis para doação e clica no botão "Enviar" <br> - O doador recebe uma mensagem de confirmação de cadastro dos alimentos e pode visualizar os seus dados na sua área de doador |
| Cadastrar-se como beneficiário | Beneficiário | Um beneficiário pode se cadastrar na página de doação de alimentos, fornecendo seus dados pessoais | - O beneficiário acessa a página de doação de alimentos e clica no botão "Cadastrar-se como beneficiário" <br> - O beneficiário preenche um formulário com seus dados pessoais e clica no botão "Enviar" <br> - O beneficiário recebe uma mensagem de confirmação de cadastro e é redirecionado para a sua área de beneficiário <br> - O beneficiário pode visualizar os pontos de doação de alimentos cadastrados na página, podendo filtrar e ordenar os pontos de acordo com seus critérios |
| Editar cadastro | Doador ou beneficiário | Um doador ou um beneficiário pode editar seus dados de cadastro, alterando ou excluindo as informações fornecidas anteriormente | - O doador ou o beneficiário acessa a sua área de usuário e clica no botão "Editar cadastro" <br> - O doador ou o beneficiário altera as informações que deseja modificar e clica no botão "Salvar" <br> - O doador ou o beneficiário recebe uma mensagem de confirmação de edição e pode visualizar os seus dados atualizados na sua área de usuário |
| Excluir cadastro | Doador ou beneficiário | Um doador ou um beneficiário pode excluir seus dados de cadastro, removendo todas as informações da página de doação de alimentos | - O doador ou o beneficiário acessa a sua área de usuário e clica no botão "Excluir cadastro" <br> - O doador ou o beneficiário confirma a sua intenção de excluir o seu cadastro e clica no botão "Excluir" <br> - O doador ou o beneficiário recebe uma mensagem de confirmação de exclusão e é redirecionado para a página inicial |
| Visualizar pontos de doação | Beneficiário | Um beneficiário pode visualizar os pontos de doação de alimentos cadastrados na página, podendo filtrar e ordenar os pontos de acordo com seus critérios | - O beneficiário acessa a sua área de beneficiário e visualiza os pontos de doação de alimentos cadastrados na página <br> - O beneficiário pode filtrar os pontos de doação de acordo com seus critérios, como localização, tipo de alimento, validade, etc., usando os campos de filtro disponíveis na página <br> - O beneficiário pode ordenar os pontos de doação de acordo com seus critérios, como distância, quantidade, data, etc., usando os campos de ordenação disponíveis na página <br> - O beneficiário pode clicar em um ponto de doação para ver mais detalhes sobre o doador e os alimentos disponíveis |
| Solicitar ou retirar alimentos | Beneficiário | Um beneficiário pode solicitar ou retirar alimentos de um ponto de doação, informando a quantidade e o tipo de alimento desejado, e recebendo uma confirmação do doador | - O beneficiário visualiza os pontos de doação de alimentos e clica em um ponto de doação que lhe interessa <br> - O beneficiário informa a quantidade e o tipo de alimento que deseja solicitar ou retirar e clica no botão "Solicitar" ou "Retirar" <br> - O beneficiário recebe uma mensagem de confirmação da sua solicitação ou retirada e é redirecionado para a sua área de beneficiário <br> - O doador recebe uma notificação da solicitação ou retirada do beneficiário e pode confirmar ou recusar a mesma |
| Gerenciar dados | Administrador | Um administrador pode gerenciar os dados de todos os doadores e beneficiários cadastrados na página, podendo criar, editar e excluir os dados conforme necessário | - O administrador acessa a sua área de administrador e visualiza os dados de todos os doadores e beneficiários cadastrados na página <br> - O administrador pode criar, editar e excluir os dados de qualquer doador ou beneficiário, usando os botões "Criar", "Editar" e "Excluir" disponíveis na página <br> - O administrador recebe uma mensagem de confirmação de cada ação realizada e pode visualizar os dados atualizados na sua área de administrador |
| Monitorar e avaliar a página | Administrador | Um administrador pode monitorar e avaliar o funcionamento da página de doação de alimentos, verificando o número de doadores, beneficiários, alimentos doados e solicitados, bem como a satisfação e o feedback dos usuários | - O administrador acessa a sua área de administrador e visualiza as estatísticas e os indicadores da página de doação de alimentos, como o número de doadores, beneficiários, alimentos doados e solicitados, etc. <br> - O administrador pode gerar relatórios e gráficos sobre o funcionamento da página, usando os botões "Gerar relatório" e "Gerar gráfico" disponíveis na página <br> - O administrador pode visualizar a satisfação e o feedback dos usuários, usando os botões "Ver avaliações" e "Ver comentários" disponíveis na página |

| Requisito não funcional | Descrição |
| :--- | :--- |
| Desempenho | A página de doação de alimentos deve ser capaz de suportar um grande número de acessos simultâneos, sem comprometer a velocidade e a qualidade do serviço |
| Segurança | A página de doação de alimentos deve proteger os dados dos doadores e beneficiários, usando criptografia, autenticação e autorização |
| Usabilidade | A página de doação de alimentos deve ser fácil de usar, com uma interface intuitiva, simples e agradável |
| Disponibilidade | A página de doação de alimentos deve estar disponível 24 horas por dia, 7 dias por semana, com um mínimo de falhas e interrupções |
| Manutenibilidade | A página de doação de alimentos deve ser fácil de modificar, corrigir e atualizar, seguindo boas práticas de desenvolvimento e documentação |


     
