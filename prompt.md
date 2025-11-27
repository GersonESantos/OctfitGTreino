## Etapa 1: Olá, modo agente do GitHub Copilot

Bem-vindo ao seu exercício **"Criar aplicativos com o modo agente do GitHub Copilot"**! :robot:

Neste exercício, você usará o modo agente do GitHub Copilot para criar um aplicativo que acompanha suas metas e seu progresso em relação à sua forma física. 🏋️‍♂️🏃‍♀️💪

### O que é o modo agente do GitHub Copilot?

O modo agente do Copilot pode criar aplicativos do zero, refatorar em vários arquivos, escrever e executar testes e migrar código legado para frameworks modernos. Ele pode gerar documentação automaticamente, integrar novas bibliotecas ou ajudar a responder perguntas sobre uma base de código complexa. O modo agente do Copilot ajuda você a ser superprodutivo, contando com um colaborador de IA que entende o ambiente de trabalho. Ele pode orquestrar seu fluxo de desenvolvimento interno, mantendo você no controle.

O modo agente do Copilot opera de forma mais autônoma e dinâmica para alcançar o resultado desejado. Para processar uma solicitação, o Copilot repete os seguintes passos várias vezes, conforme necessário:

Determina o contexto relevante e os arquivos a serem editados de forma autônoma.
Oferece tanto alterações de código quanto comandos de terminal para concluir a tarefa. Por exemplo, o Copilot pode compilar código, instalar pacotes, executar testes e muito mais.
Monitora a correção das edições de código e da saída dos comandos do terminal, e realiza iterações para solucionar problemas.

> [!NOTA]
Você pode aprender mais sobre o modo agente do GitHub Copilot na [Documentação sobre como usar o modo agente](https://code.visualstudio.com/docs/copilot/chat/chat-agent-mode).

### :keyboard: Atividade: Conhecendo seu ambiente de desenvolvimento em modo agente do GitHub Copilot

1. Clique com o botão direito do mouse no botão abaixo para abrir a página **Criar Codespace** em uma nova guia.

   [![Abrir no GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/{{full_repo_name}}?quickstart=1)

   - O plano gratuito do Codespaces que acompanha todas as contas do GitHub é suficiente, desde que você ainda tenha minutos disponíveis.
   - As configurações padrão do Codespace estão corretas.

1. Confirme se o campo **Repositório** corresponde à sua cópia do exercício e não ao original, e clique no botão verde **Criar Codespace**.

   - ✅ Sua cópia: `/{{full_repo_name}}`
   - ❌ Original: `/skills/build-applications-w-copilot-agent-mode`

1. Aguarde um momento para que o Visual Studio Code carregue.

1. Antes de prosseguirmos, vamos dedicar um momento para nos familiarizarmos com a pasta do projeto.

   - A barra de navegação à esquerda permite acessar o explorador de arquivos, o depurador e a função de pesquisa.
   - O painel inferior (Ctrl+J) exibe a saída do depurador, permite executar comandos no terminal e configurar as portas do serviço web.
   - Nossa pasta de documentação contém outro repositório de aplicativos de exemplo que fornecerá ao Copilot o contexto do modo agente para criar seu aplicativo. Mais detalhes nos próximos passos!

1. Na parte superior do VS Code, localize e clique no ícone do Copilot para abrir um painel de bate-papo do Copilot.

   <img width="150" alt="image" src="https://github.com/user-attachments/assets/5e64db46-95cb-415d-badc-b6b8677f10c1" />

1. Se esta for a sua primeira vez usando o GitHub Copilot, você precisará aceitar os termos de uso para continuar.
    - Clique no botão **Aceitar** para continuar.

### :keyboard: Atividade: Use o modo agente do Copilot para criar uma ramificação e publicá-la. 🙋

Excelente trabalho! Vamos pedir ajuda ao Copilot para iniciar uma branch e assim podermos fazer algumas personalizações.

> [!NOTA]
Lembre-se de que o modo agente do Copiloto é conversacional, portanto, ele pode fazer perguntas a você e você também pode fazer perguntas a ele.
Aguarde um momento para que o Copiloto responda e pressione o botão **Continuar** para executar os comandos apresentados pelo modo agente do Copiloto.

1. Se ainda não estiver lá, retorne ao VS Code.
1. Abra a janela de bate-papo do GitHub Copilot, caso ainda não esteja aberta.
1. Copie e cole a seguinte mensagem no chat do GitHub Copilot e selecione **Agente** em vez de **Perguntar** ou **Editar** no menu suspenso onde você está inserindo a mensagem.

   <img src="https://github.com/user-attachments/assets/b9e291be-d835-4de0-ac1c-35a6ec3ea72d" width=30% height=30%>

1. Vamos pedir ao modo agente do Copilot para nos ajudar a lembrar o comando, criar a branch `build-octofit-app` e publicá-la.

   > ![Emblema Estático](https://img.shields.io/badge/-Prompt-text?style=flat-square&logo=github%20copilot&labelColor=512a97&color=ecd8ff)
   >
   > ```prompt
   > Crie e publique uma nova branch do Git chamada build-octofit-app
   > ```

   O modo agente Copilot responderá e solicitará que você **continue** a executar o comando.

   <img src=https://github.com/user-attachments/assets/d1652fc1-78e5-49c6-9303-b455815eea8f width=40% height=40%>

1. Agora que estamos satisfeitos com o comando, pressione o botão "Continuar" para que o modo agente do Copilot o execute para nós. Não é necessário copiar e colar!

1. Após alguns instantes, verifique a barra de status inferior esquerda do VS Code para ver a branch ativa. Ela deverá exibir `build-octofit-app`. Se sim, você concluiu esta etapa!

1. Agora que seu branch foi enviado para o GitHub, Mona já deve estar verificando seu trabalho. Aguarde um momento e fique de olho nos comentários. Você verá as respostas dela com informações sobre o progresso e a próxima lição.

<detalhes>
<summary>Com problemas? 🤷</summary><br/>

Se você não receber feedback, aqui estão algumas coisas para verificar:

- Certifique-se de ter criado a branch com o nome exato `build-octofit-app`. Sem prefixos ou sufixos.
- Verifique se a ramificação foi de fato publicada em seu repositório.

</details>