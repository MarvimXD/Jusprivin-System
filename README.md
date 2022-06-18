# Jusprovin System
O Jusprovin System é um sistema de gerenciamento de pessoas feito para a empresa Jusprovin (JUSPROVIN ASSESSORIA EMPRESARIAL ONLINE LTDA). 

O objetivo do sistema é de gerir clientes, possíveis clientes e funcionários da empresa, visando a fácil utilização e aprendizado do sistema.

Com este sistema a empresa poderá cadastrar, editar, ler e deletar funcionários e/ou clientes. Enviar ordens de faturamento através da geração de boletos em PHP. Cadastrar possíveis clientes para a prospecção da empresa. Segue abaixo o sistema e suas funções.

<strong>O layout do sistema foi especificado pela própria empresa.</strong>

<br>
<br>


<h2>Tela de Acesso</h2>
<img src="https://user-images.githubusercontent.com/58988379/174391889-9c541b32-0f6a-4a8e-b7ab-5d4205fd0c15.png">

A tela de Acesso é a tela inicial do sistema, onde tanto os <strong style="color:blue;">Clientes</strong> quanto os <strong>Funcionários</strong> poderão inserir suas credenciais e ter o seu devido acesso ao sistema. 

O cadastro no sistema para novos funcionários deverá ser realizado pelos <strong>Administradores</strong> do mesmo e, para novos clientes, deverá ser realizado por funcionários destinados a tal função.

<br>
<br>

<h2>Tela Inicial</h2>
<img src="https://user-images.githubusercontent.com/58988379/174392906-b3b58db5-bbcc-4d2c-bc50-4ac24000df80.png">

A tela Inicial é a tela após o "Login" no sistema feito por funcionários. Aqui será mostrado um gráfico mediante os cadastros mensais, em comparação ao mês anterior, de <strong>Clientes</strong> e <strong>Prospecções</strong>; 

As notificações do sistema que são entregues conforme regras de cargos, ou seja, para cada cargo será entregue sua devida notificação; 

A análise mensal de conversão de clientes, uma área destinada a análise de prospecções convertidas, não convertidas ou em negociação no sistema;

Por fim, as prospecções mais recentes no sistema.

As áreas de Gráfico e Prospecções Recentes contam com um chaveamento simples que, ao ser clicado, levará à suas respectivas páginas. A área de notificação possui um chaveamento que levará à área de suporte do sistema.

O sistema conta com um menu dinâmico ao lado esquerdo e um menu fixo superior.

<br>
<br>

<h2>Tela Inicial - Menu Esquerdo e Menu Superior</h2>
<p float="left">
  <img src="https://user-images.githubusercontent.com/58988379/174393770-08f06f30-9d17-42ae-81fc-f332dbc9a2b6.png">
  <img src="https://user-images.githubusercontent.com/58988379/174394418-11529025-8592-49f3-943e-96d61c6d803b.png" width="60%" height="30px">
</p>
(Clique nas imagens para uma melhor visualização)

- Menu Esquerdo:
   - Conta com a "Logo" da empresa e seu nome, o nome do funcionário e as abas de opções;
   - É composto por sete opções sendo duas delas destinadas a cargos específicos de 'Financeiro' e 'Administrador'. São eles:

      - Prospecção: Essa aba, tem a importância para os setores de marketing e comercial, onde será colocado os dados de possível cliente pelo marketing e também onde o comercial fará a leitura dos contatos disponibilizados pelo marketing para entrar em contato.
      - Clientes: Onde armazenará o banco de informações dos clientes, como sua ficha, seus documentos e o andamento de seus processos.
      - Faturamento: Essa aba vai passar a missão ao financeiro para gerar o meio de cobrança ao cliente. E assim o financeiro cumprirá a sua tarefa do dia.
      - Agendamento: Essa aba é responsável pelo agendamento de processos no sistema, enviando uma notificação quando um processo chega perto de seu fechamento.
      - Classificador: Essa aba é muito importante por isso quero ela bem didática para não ter erros na hora da execução do processo.
      - Financeiro: Essa aba é onde os funcionários marcados como 'Financeiro' receberão os boletos de ordem de faturamento gerados na aba "Faturamento".
      - Administração: Aba dedicada aos 'Administradores' do sistema, onde poderão ter a relação de funcionários e clientes registrados e acesso ao log do sistema.



- Menu Superior:
   - Conta com seis opções. São elas:
   
      - Menu: Opção que permitirá comprimir ou expandir o menu esquerdo.
      - Início: Leverá à tela inicial.
      - Suporte: Levará à tela de Suporte, onde o usuário poderá enviar suas dúvidas e/ou problemas recorrentes ao sistema.
      - Sino de Notificação: Será demonstrado as notificações atuais do sistema.
   
        <img src="https://user-images.githubusercontent.com/58988379/174396204-49566da9-3478-41bf-8c13-a4ca9f418f42.png">
     
      - Expandir: Opção que permitirá função semelhante a tecla "F11", preenchendo toda a tela com o sistema.
   
        <img src="https://user-images.githubusercontent.com/58988379/174396445-ab5e8aca-3d0e-44cd-9a02-88045440b154.png">
     
      - Sair: Opção que permitirá função "LOGOUT" do sistema, levando o usuário novamente a tela inicial de Acesso.
   
        <img src="https://user-images.githubusercontent.com/58988379/174396569-9d93a232-c06d-4832-9067-e19ac641ac15.png">
     

<br>
<br>

<h2>Prospecção</h2>

<img src="https://user-images.githubusercontent.com/58988379/174398109-4e69d56d-3e6b-42db-b39f-0970d3b7a3f1.png">

A tela de Prospecção conta com uma lista de prospecções cadastradas e botão " + " que levará a tela de cadastro de novas prospecções.

Ao clicar em algum nome listado, o usuário será redirecionado a página contendo o perfil da prospecção selecionada.

<br>

   - Cadastrar Prospecção
      
      - Página destinada ao cadastro de novas prospecções no sistema, contando com os campos de Nome, E-mail, Telefone, Celular e Serviço Contratado.

   <img src="https://user-images.githubusercontent.com/58988379/174398388-2558ffe0-a361-438c-9308-675d2a36bd93.png">

<br>

   - Perfil da Prospecção
      
      - Página destinada aos funcionários marcados com cargo de "Marketing", onde poderão acessar os dados do cliente, bem como excluí-lo. Poderão também atualizar seu histórico de atendimento, definindo seu 'Status' e sua descrição.

   <img src="https://user-images.githubusercontent.com/58988379/174399155-37a76280-8f22-4f9b-ae7b-c445400f01ef.png">
   <img src="https://user-images.githubusercontent.com/58988379/174399274-9c004fa0-88fb-45b2-a739-50121f946eda.png">

     

<br>
<br>

<h2>Clientes</h2>

<img src="https://user-images.githubusercontent.com/58988379/174416345-1b5cd6eb-b7ff-4a2e-9889-4d7cfdddf02f.png">

A página de clientes mostra uma lista com todos os clientes previamente cadastrados no sistema, sejam eles Pessoa Jurídica ou Pessoa Física;

Ao clicar em algum nome listado, o usuário será redirecionado a página contendo o perfil do cliente selecionado;

Os usuários têm a opção de cadastrar novos clientes clicando no botão " + " logo no início da página.


<br>

   - Cadastrar Cliente
      
      - Através dessa página o usuário (funcionário) poderá cadastrar um novo cliente no sistema, inserindo os seus dados conforme a imagem abaixo;
      - É dada a opção de mudança de formulário entre Pessoa Física e Pessoa Jurídica, alterando algumas informações de cadastro.

   <img src="https://user-images.githubusercontent.com/58988379/174416411-6246f893-c91c-46b5-af98-e244d2744bba.png">
   <img src="https://user-images.githubusercontent.com/58988379/174416597-8ba04b57-5591-4bd8-96ae-331040145ac4.png">

<br>

   - Perfil do Cliente
      
      - Ao clicar em algum nome na listagem de clientes na página de clientes, o usuário será redirecionado ao perfil do cliente selecionado;
      - Através dessa página os usuários (funcionários) poderão acessar as informações do cliente bem como sua pasta pessoal, contendo seus documentos e processos referentes ao serviço contratado com a empresa;
      - Administradores do sistema podem excluir e/ou editar as informações referentes ao cliente selecionado.
      
      <br>
      
      <img src="https://user-images.githubusercontent.com/58988379/174416713-fc1fb544-6305-4c91-b5d2-e6a7345a66d5.png">
 
     <br>
     <br>

      - Abas do Perfil:
      
          - As abas do perfil são as divisórias da "pasta geral" do perfil do cliente.
          
          <br>
          
          <img src="https://user-images.githubusercontent.com/58988379/174416888-126e6edd-7e01-426f-bbab-412949477da0.png">
         
     <br>
     <br>

      - Cliente > Pasta:
      
          - Essa aba é responsável por guardar os documentos referentes ao cliente selecionado;
          - Uma vez guardado, o documento poderá ser baixado por qualquer funcionário do sistema que tenha as permissões certas;
          - É disponibilizado também a opção de adicionar um documento logo no início da página, através do botão " + ".
          
          <br>
          
          <img src="https://user-images.githubusercontent.com/58988379/174417010-a8996f96-d0a6-4d2e-ad44-454b59481b5f.png">  
    
     <br>
     <br>

      - Cliente > Pasta > Cadastrar Documento:
      
          - Através dessa página é possível a adição de documentos à pasta digital do cliente;
          - Documentos aceitos: PDF e/ou DOCX.
          
          <br>
          
          <img src="https://user-images.githubusercontent.com/58988379/174417122-91f035d8-08d5-4f56-949b-a576677626db.png">  

    
     <br>
     <br>

      - Cliente > Histórico:
      
          - Através dessa página é possível ver os históricos adicionados referentes ao cliente selecionado;
          - É possível o cadastro de um novo histórico clicando no botão " + " no início da página.
          
          <br>
          
          <img src="https://user-images.githubusercontent.com/58988379/174417368-7d338273-34ed-45a0-a99d-7f889a0d7894.png">  

    
     <br>
     <br>

      - Cliente > Histórico > Inserir Histórico:
      
          - Através dessa página é possível inserir novos históricos referentes ao cliente selecionado;
          - Já é pré-inserido o nome do funcionário que está adicionando o histórico, sendo desabilitada a opção de alteração.
          
          <br>
          
          <img src="https://user-images.githubusercontent.com/58988379/174417424-e9ca7f19-2dc2-4606-8fc0-0d56deac2777.png">  
    
     <br>
     <br>

      - Cliente > Processo:
      
          - Através dessa página é possível visualizar os processos previamente inseridos referentes ao cliente selecionado;
          - É possível a adição de um novo processo clicando no botão " + " no início da página.
          
          <br>
          
          <img src="https://user-images.githubusercontent.com/58988379/174417496-c6e690a7-5d57-40cc-b9c3-98ffa53dbe43.png">  

    
     <br>
     <br>

      - Cliente > Processo > Inserir Processo:
      
          - Através dessa página é possível inserir novos processos referentes ao cliente selecionado;
          - Já é pré-inserido o nome do funcionário que está adicionando o processo, sendo desabilitada a opção de alteração.
          
          <br>
          
          <img src="https://user-images.githubusercontent.com/58988379/174417545-63a6a88a-0eb8-4be6-84cb-60d8b2d04dc7.png">  

    
     <br>
     <br>

      - Cliente > Restrito:
      
          - Através dessa página é possível fazer o cadastro de um "Login" para que o cliente tenha acesso a sua própria área dentro do sistema;
          - É possível também visualizar e/ou adicionar processos referentes a solicitação de serviço que o cliente tenha feito;
          - Os processos adicionados nessa página poderão ser visualizados pelo cliente em sua respectiva área definida, que poderá ser acessada pelo "Login" criado através dessa página;
          - Tanto o cliente quanto o funcionário poderão fazer o download do documento previamente inserido em seu processo na página restrito.
          
          <br>
          
          <img src="https://user-images.githubusercontent.com/58988379/174417634-6df49aa3-cfa1-4793-ad95-f8eb19d04eb3.png">  

    
     <br>
     <br>

      - Cliente > Restrito > Inserir Processo:
      
          - Através dessa página é possível inserir novos processos referentes ao cliente selecionado;
          - Para este formulário basta a inserção da descrição do processo e do documento desejado.
          
          <br>
          
          <img src="https://user-images.githubusercontent.com/58988379/174417703-e09de2b1-e8d0-43f3-b190-b82c0bcb572b.png">  


<br>
<br>

<h2>Área Restrita do Cliente</h2>

<img src="https://user-images.githubusercontent.com/58988379/174417792-9c2c6b90-5fb0-4c76-b959-45cb9909f3bc.png">

Assim que feito o "login", na tela inicial descrita anteriormente, inserindo as credenciais previamente cadastradas na aba "Restrito", o cliente irá se deparar com a sua área restrita;

Poderá ter acesso aos documentos de processos inseridos previamente na aba "Restrito" bem como fazer o 'download' dos mesmos.


<br>
<br>

<h2>Faturamento</h2>

<img src="https://user-images.githubusercontent.com/58988379/174417996-e426904c-2da8-4aef-ab04-93bc6aabfc10.png">

Através dessa página, o funcionário poderá lançar ordens de faturamento, criando PDF's referentes ao serviço contratado pelo cliente;

A página conta com um sistema de pesquisa, para facilitar a busca por um cliente específico.

<br>

   - Ordem de Faturamento
      
      - Através dessa página o usuário (funcionário) poderá gerar um boleto que será enviado para a aba "Financeiro > Ordem de Faturamento" automaticamente;
      - O usuário (funcionário) deverá inserir os últimos campos indicados, são eles: Serviço Contratado, Forma de Pagamento, Preço, Quantidade de Parcelas e a Descrição.

   <img src="https://user-images.githubusercontent.com/58988379/174418110-5c091483-4191-4edc-b21f-c79732703c5a.png">

<br>




















