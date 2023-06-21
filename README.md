# 👥 agendadorDeClientes - Versão 0.1.0.

Aplicação destinada a solucionar demandas relacionadas ao agendamento de clientes, automatizando o contato para agendamento através de uma plataforma simplificada e eficiente, que conta com sistema de pagamento embarcado e, dessa forma, otimizando a produtividade da empresa que aderir ao sistema.

## 🖥️ frontEnd:

### 💻 telaDoCliente:
#### 🌐 landingPage:
- [ ] Deve conter uma sessão explicando um pouco sobre a empresa;
- [ ] Deve conter uma sessão de portfólio simples;
- [ ] Deve conter um campo para contato;
- [ ] Deve conter links para as redes sociais da empresa;

#### 📝 telaDeCadastro:
- [ ] Deve conter um formulário para cadastro do cliente;
- [ ] Deve conter opção de cadastro via conta do Google e/ou Facebook;

#### 🔑 telaDeLogin:
- [ ] Deve conter um formulário para efetuar o login do cliente cadastrado;
- [ ] Deve conter opção de login via conta do Google e/ou Facebook para aqueles que optarem por esse método de cadastro;

#### 🗓️ telaDoAgendador:
- [ ] Deve conter uma tabela com os horários disponíveis, de acordo com a disponibilidade do estabelecimento e o local de atendimento escolhido;
- [ ] A partir do momento em que o cliente efetuar o agendamento, deverá questionar se deseja fazer pagamento de forma online ou presencialmente;
- [ ] Caso escolha pelo pagamento online, deverá redirecionar para a tela de pagamento;

#### 💳 telaDePagamento:
- [ ] Deve conter o sistema de pagamento integrado com a plataforma de agendamento, com as opções de pix, cartão de crédito e débito;
- [ ] Deve conter campo para que seja possível aplicar cupom de desconto no caso do cliente possuir algum;
- [ ] Ao confirmar o método de pagamento, o cliente deverá receber um e-mail de confirmação do seu agendamento;

### 🧑‍💼 telaDoAdm:
#### 📊 telaDeGestão;
- [ ] Deve conter um calendário com os cards de agendamento de cada cliente do mês - com future `realtime`;
- [ ] Cada card deve informar o nome do cliente e horário agendado;
- [ ] Caso seja clicado, o card deve mostrar também o contato e possíveis observações a respeito do cliente; 
- [ ] Deve ser possível editar, movimentar (realocando os clientes dentro da agenda), excluir e criar manualmente novos cards pelo ADM;

## 🌐 backEnd:
### 👤 usuário:
- [ ] Deve poder navegar pela landing page;
- [ ] Deve poder se cadastrar;
- [ ] Deve poder fazer login na sua conta;

### 🧑‍💼 cliente:
- [ ] Deve poder navegar pela landing page;
- [ ] Deve poder fazer login na sua conta;
- [ ] Deve poder efetuar seu agendamento online;

### 👨‍💼 adm:
- [ ] Deve poder navegar pela landing page;
- [ ] Deve poder fazer login como ADM;
- [ ] Deve poder editar, mover, excluir e criar os cards de agendamento dos clientes;
- [ ] Deve poder monitorar em tempo real o calendário com os agendamentos;
