# Prova técnica para desenvolvimento de sites

**Premissa**
> Nosso novo cliente precisa de um site para que os visitantes enviem mensagem a ele pelo contato e possam ver uma página com a história da empresa.
> As mensagens enviadas pelo formulário de contato, deverão ficar armazenadas em uma tela gerencial, porém deverão ser enviadas para o email de contato da empresa.
> A página com o histórico da empresa, ele pretende atualizar de 6 em 6 meses, porque está aumentando o seu parque fabril e quer colocar semestralmente no histórico da empresa, a sua evolução

### Especificação
#### Formulário de contato
| Campo | Tipo |
| ----- | ---- |
| Nome  | string |
| Telefone | string |
| Email | string |
| Mensagem | string |


### Regras de negócio
- O site deverá de alguma maneira permitir configurar o email de contato da empresa.
- Os formulários da página de contato deverão validar para que não sejam enviados em branco ou com email falso.
- Ao enviar uma mensagem de contato, o site deverá exibir uma mensagem de confirmação ao visitante.

### Funcionalidades esperadas
- Tela para configurar o email de contato
- Tela atualizar o histórico da empresa
- Tela para verificar as mensagens de contato recebidas
- Receber por email as mensagens de contato

## Teste de mesa
> Dado o site desenvolvido, deve ser possível realizar o cadastro do histórico e enviar mensagens de contato.
- Ao atualizar o histórico da empresa, deve refletir automaticamente para o visitante
- Ao enviar uma mensagem de contato, deverá ficar disponível na tela do gestor da empresa para que ele possa ler a mesma.
- Ao enviar uma mensagem de cotnato, ela deverá ser encaminhada para o email da empresa que ele configurou.
- Ao enviar um formulário em que os campos estejam em branco ou preenchidos de maneira errônea, deverá avisar o visitante que há problemas de validação

### Avaliação
> De princípio, não estamos havaliando conhecimento em cima de uma framework/tecnologia, mas sim, em cima da solução apresentada, ou seja, o mais importante é a modelagem e forma de desenolvimento

- De maneira textual, responda a questão abaixo
1. Como você garantiu a qualidade da sua aplicação?
2. Como você garantiu a atualização do site?

### Dicas
- Espera-se que seja escrito utilizando as frameworks de desenvolvimento atuais tanto para a apresentação (frontend) quanto o processamento/armazenamento (backend)

### Entrega
- O prazo de entrega é de 7 dias após o fork.
- As alterações realizadas após este prazo não serão avaliadas
- Commit o seu projeto neste mesmo projeto github
- Crie um arquivo **Respostas.md** com as respostas das questões e os passos para compilar/executar a aplicação
- Qualquer dúvida, entre em contato pelo email: [xama@xamasistemas.com.br](mailto:xama@xamasistemas.com.br)
