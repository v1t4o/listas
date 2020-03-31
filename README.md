# Listas

## Configurações mailman:

### Em mailman/admin/LISTA/general:

  - Uma frase resumo identificando esta lista (opcional)
  - Prefixo colocado na linha de assunto das postagens nas listas (opcional)
  - Ocultar o remetente da mensagem, substituindo-o pelo endereço do nome da lista: não
  - Onde as respostas para as mensagens desta lista deverão ser direcionadas: Remetente
  - Enviar lembretes mensais de senha? Não
  - Enviar mensagem de boas vindas para novos membros inscritos: Não
  - Enviar mensagens de boas vindas para membros quando eles são desinscritos: Não
  - Os moderadores de lista devem obter uma notificação imediata de novas requisição, assim como também as notícias diárias coletadas? Não
  - O administrador deverá receber notificações de inscrições e desinscrições? Não
  - Enviar um email para o remetente quando sua postagem está aguardando aprovação? Não
  - Tamanho máximo em kilobytes (KB) do corpo da mensagem: 0

### Em mailman/admin/LISTA/privacy/subscribing:

  - Que passos são requeridos para a inscrição? Confirmar e aprovar

### Em mailman/admin/LISTA/privacy/sender:

  - Por padrão, as postagens de novos membros da lista devem ser moderadas: Sim
  - Ação a ser tomada quando um membro moderado posta para a lista: Descartar
  - * Lista se endereços de não membros no qual as postagens devam ser aceitas automaticamente: Colocar endereços *
  - Ação a ser tomada para postagem de não membros no qual nenhuma ação explicita é definida: Descartar
  - As mensagens para os não-membros, que são automaticamente descartadas, devem ser redirecionadas ao moderador da lista: Não

### Em mailman/admin/LISTA/digest:

  - Legenda adicionado a cada digest: Deixar vazio

### Em mailman/admin/LISTA/nondigest:

  - Rodapé adicionado ao email enviado para os membros regulares da lista: Deixar vazio

### Em mailman/admin/LISTA/bounce:

  - O Mailman deverá te enviar, o dono da lista, quaisquer mensagens de bounce que falharam ao ser detectadas pelo processador de bounces? Sim é recomendado: não
  - O Mailman deverá te notificar, o dono da lista, quando os bounces fazem a inscrição da lista ser desativada: Não
  - O Mailman deverá te notificar, o dono da lista, quando os bounces fizerem um membro ser descadastrado: Não



  



