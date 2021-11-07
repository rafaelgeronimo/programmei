Esse repositório não contém código. Aqui estão reunidos os principais fatos sobre o desafio proposto. Em breve, detalhes sobre o desenvolvimento.
Para acesso aos códigos, visite os repositórios:

- [Backend](https://github.com/rafaelgeronimo/today-backend)
- [Frontend](https://github.com/rafaelgeronimo/today-frontend)

## Sobre
Desafio técnico proposto pela [Trybe](https://www.betrybe.com/), simulando um teste solicitado pela empresa fictícia **Ebytr**.

<Details open>
    <summary>
        <strong style="font-size: 2rem">Enunciado:</strong>
    </summary>
    <p>
        A empresa <strong>Ebytr</strong> está passando por problemas de produtividade/controle porque as pessoas colaboradoras vêm tendo dificuldade na organização de suas tarefas individuais. Por esse motivo, a diretora de produto Carolina Bigonha decidiu implantar uma nova forma de organizar as tarefas.
Você foi a pessoa contratada para desenvolver um sistema capaz de auxiliar as pessoas colaboradoras a se organizar e ter mais produtividade.
        Na <strong>Ebytr</strong> o time de desenvolvimento utiliza a Stack <strong>MERN</strong> para criar suas aplicações. Foi combinado com a <strong>Ebytr</strong> que você utilizará essa mesma Stack para resolver o problema de organização e produtividade da empresa.
Abaixo estão (i) os requisitos técnicos, (ii) as funcionalidades e (iii) critérios de avaliação do desafio.
    </p>
    <ol>
        <h4>Requisitos técnicos:</h4>
        <li>
            Front-End em React;
        </li>
        <li>
            Back-End em NodeJS, com MongoDB;
        </li>
        <li>
            Arquitetura em camadas;
        </li>
    </ol>
    <ol>
        <h4>Funcionalidades</h4>
        <li>
            Visualizar a lista de tarefas;
            <ul>
                <li>
                    Esta lista deve ser ordenável por ordem alfabética, data de criação ou por status;
                </li>    
            </ul>
        </li>
        <li>
            Inserir uma nova tarefa na lista;
        </li>
        <li>
            Remover uma tarefa da lista;
        </li>
        <li>
            Atualizar uma tarefa da lista;
        </li>
        <li>
            A tarefa deve possuir um status editável: pendente, em andamento ou pronto;
        </li>
    </ol>
</Details>

### Pontos importantes do desafio:
- O sistema terá uma tela de login para que a pessoa usuária possa entrar no sistema e visualizar apenas as tarefas que lhe cabem.
- O cadastro de novas pessoas usuárias e exclusão das mesmas é realizado apenas pela pessoa administradora.
- Uma vez logado no sistema, a pessoa usuária terá acesso à tela principal da aplicação, onde poderá realizar o cadastro de novas tarefas e o gerenciamento das mesmas.
- Componentes do ciclo de uso:
    - **Título**: um campo para que seja informado o título da tarefa. **[Obrigatório]**.
    - **Descrição**: um campo de texto onde será possível escrever um texto maior, com mais detalhes sobre a tarefa. **[Não é obrigatório]**.
    - **Data início e fim**: será possível escolher a data para início da tarefa e a entrega da mesma. **[Não é obrigatório]**
    - **Botão de salvar**: Um botão para que seja possível cadastrar a tarefa no sistema.
    - **Checkbox de tarefa concluída**: Um checkbox onde a pessoa usuária pode definir a tarefa como concluída. Pode ser acessível já durante o cadastro da tarefa. Tarefas concluídas não são exibidas na tela inicial. Deverá existir uma rota para listar apenas as tarefas que já foram concluídas.
    - **Botão para excluir tarefa**: Deverá ser exibido apenas na tela de tarefas concluídas e permitirá à pessoa usuária remover a tarefa definitivamente do sistema.

## Feito com
Conforme proposto no desafio, o desenvolvimento desse projeto foi realizado utilizando a stack **MERN**.
Dessa forma, o _frontend_ foi desenvolvido em **React** enquanto o _backend_ foi desenvolvido com **Express**, **MongoDB** e **Node.JS**.
Mais informações nos respectivos repositórios listados abaixo.

## Iniciando
Para informações detalhadas de como configurar o projeto para executar localmente, acesse os respectivos repositório preparados para cada um dos meios:

### - [Today Backend](https://github.com/rafaelgeronimo/today-backend)
### - [Today Frontend](https://github.com/rafaelgeronimo/today-frontend)
