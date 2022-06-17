# Jusprovin System
O Jusprovin System é um sistema de gerenciamento de pessoas feito para a empresa Jusprovin (JUSPROVIN ASSESSORIA EMPRESARIAL ONLINE LTDA). 

O objetivo do sistema é de gerir clientes, possívels clientes e funcionários da empresa, visando a fácil utilização e aprendizado do sistema.

Com este sistema a empresa poderá cadastrar, editar, ler e deletar funcionários e/ou clientes. Enviar ordens de faturamento através da geração de boletos em PHP. Cadastrar possíveis clientes para a prospecção da empresa. Segue abaixo o sistema e suas funções.

O layout do sistema foi especificado pela própria empresa.

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

A tela Inicial é a tela após o "Login" no sistema feito por funcionários. Aqui será mostrado um gráfico mediante os cadastros mensais, em comparação ao mês anterior, de <strong>Clientes</strong> e <strong>Prospecções</strong>; As notificações do sistema que são entregues conforme regras de cargos, ou seja, para cada cargo será entregue sua devida notificação; A análise mensal de conversão de clientes, uma área destinada a análise de prospecções convertidas, não convertidas ou em negociação no sistema e, por fim, as prospecções mais recentes no sistema.

As áreas de Gráfico e Prospecções Recentes contam com um chaveamento simples que, ao ser clicado, levará à suas respectivas páginas. A área de notificação possui um chaveamento que levará à área de suporte do sistema.

O sistema conta com um menu dinâmico ao lado esquerdo e um menu fixo superior.

<br>
<br>

<h2>Tela Inicial - Menu Esquerdo e Menu Superior</h2>
<p float="left">
  <img src="https://user-images.githubusercontent.com/58988379/174393770-08f06f30-9d17-42ae-81fc-f332dbc9a2b6.png">
  <img src="https://user-images.githubusercontent.com/58988379/174394418-11529025-8592-49f3-943e-96d61c6d803b.png" width="60%" height="30px">
</p>

- Menu Esquerdo:
   - Conta com a "Logo" da empresa e seu nome, o nome do funcionário e as abas de opções;
   - É composto por sete opções sendo duas delas destinadas a cargos específicos de 'Financeiro' e 'Administrador'. São eles:

   - Prospecção: Essa aba, tem a importância para os setores de marketing e comercial, onde será colocado os dados de possível cliente pelo marketing e também onde o comercial fará a leitura dos contatos disponibilizados pelo marketing para entrar em contato.
   - Clientes: Onde armazenará o banco de informações dos clientes, como sua ficha, seus documentos e o andamento de seus processos.
   - Faturamento: Essa aba vai passar a missão ao financeiro para gerar o meio de cobrança ao cliente. E assim o financeiro cumprirá a sua tarefa do dia.
   - Agendamento: Essa aba é responsável pelo agendamento de processos no sistema, enviando uma notificação quando um processo chega perto de seu fechamento.
   - Classificador: Essa aba é muito importante por isso quero ela bem didática para não ter erros na hora da execução do processo.
   - Financeiro: Essa aba é onde os funcionários marcados como 'Financeiro' receberão os boletos de ordem de faturamento gerados na aba "Faturamento".
   - Administração: Aba dedicada aos 'Administradores' do sistema, onde poderão ter a relação de funcioários e clientes registrados e acesso ao log do sistema.



- Menu Superior:
   - Início: Leverá à tela inicial.
   - Suporte: Levará à tela de Suporte, onde o usuário poderá enviar suas dúvidas e/ou problemas recorrentes ao sistema.
   - Sino de Notificação: Será demonstrado as notificações atuais do sistema.
   
     <img src="https://user-images.githubusercontent.com/58988379/174396204-49566da9-3478-41bf-8c13-a4ca9f418f42.png">
     
   - Expandir: Opção que permitirá função semelhante a tecla "F11", preenchendo toda a tela com o sistema.
   
     <img src="https://user-images.githubusercontent.com/58988379/174396445-ab5e8aca-3d0e-44cd-9a02-88045440b154.png">
     
   - Sair: Opção que permitirá função "LOGOUT" do sistema, levando o usuário novamente a tela inicial de Acesso.
   
     <img src="https://user-images.githubusercontent.com/58988379/174396569-9d93a232-c06d-4832-9067-e19ac641ac15.png">
     

