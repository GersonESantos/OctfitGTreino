Etapa 2: Configuração inicial da aplicação: Estrutura de diretórios, requisitos do Python e MongoDB

Nesta etapa, realizaremos o seguinte:

- Crie a estrutura de diretórios do aplicativo octofit-tracker.
- Crie os diretórios octofit-tracker/backend e octofit-tracker/frontend.
- Crie o arquivo octofit-tracker/backend/requirements.txt.

> [!NOTA]
Copie e cole a(s) seguinte(s) mensagem(ns) no chat do GitHub Copilot e selecione "Agente" em vez de "Perguntar" ou "Editar" no menu suspenso onde você está inserindo a mensagem.
Lembre-se de que o modo agente do Copiloto é conversacional, portanto, ele pode fazer perguntas a você e você também pode fazer perguntas a ele.
Aguarde um momento para que o Copiloto responda e pressione o botão "Continuar" para executar os comandos apresentados pelo modo agente do Copiloto.
> - Manter os arquivos criados e atualizados pelo modo agente do Copilot até que a operação seja concluída.
O modo agente tem a capacidade de avaliar sua base de código, executar comandos, adicionar, refatorar ou excluir partes do seu código e se autocorrigir automaticamente caso você ou o agente cometa algum erro durante o processo.

**Abra uma nova sessão do Copilot Chat clicando no ícone de mais `+` no painel do Copilot Chat.**

### :keyboard: Atividade: Solicitar ao GitHub Copilot no modo agente para iniciar a criação do nosso aplicativo

> ![Emblema Estático](https://img.shields.io/badge/-Prompt-text?style=flat-square&logo=github%20copilot&labelColor=512a97&color=ecd8ff)
>
> ```prompt
Vamos executar os comandos passo a passo.
>
Siga as instruções
>
> - Siga a estrutura do aplicativo OctoFit Tracker
> - Siga as instruções para a criação do ambiente virtual em Python.
> - Crie o arquivo requirements.txt
> - Instale os requisitos do Python a partir do arquivo criado
>```

1. Agora que criamos a estrutura de diretórios do aplicativo, configuramos um ambiente virtual Python e o modo agente do Copilot nos ajudou a escrever um arquivo `requirements.txt` para instalar todas as dependências do projeto, vamos confirmar nossas alterações na branch `build-octofit-app`.

1. Com as novas alterações concluídas, faça o **commit** e o **push** das alterações para o branch `build-octofit-app`.

1. Aguarde um momento para que Mona verifique seu trabalho, dê um feedback e compartilhe a próxima lição para que possamos continuar trabalhando!

<detalhes>
<summary>Com problemas? 🤷</summary><br/>

Se você não receber feedback, aqui estão algumas coisas para verificar:

- Certifique-se de que as alterações do commit foram feitas no seguinte arquivo, no branch `build-octofit-app`, e enviadas/sincronizadas para o GitHub:
  - `octofit-tracker/backend/requirements.txt` e contém o pacote `Django==4.1`
- Se a Mona encontrar algum erro, basta corrigi-lo e enviar as alterações novamente. A Mona verificará seu trabalho quantas vezes forem necessárias.

</details>