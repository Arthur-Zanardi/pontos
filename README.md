# pontos
É o sistema de pontos que estou fazendo e implementando (sozinho) para a empresa que trabalho atualmente.
  
  Visão de funcionamento do projeto em geral:
    - basicamente, tem uma tela de login (com a integração no banco de dados), e ao entrar, o funcionário terá 4 botões (botão de chegada, botão de almoço, botão da tarde e botão de largada). e assim vai.
  Estrutura do projeto:
    - Eu fiz a interface gráfica em python, o banco de dados SQL em postgreSQL
  Bibliotecas utilizadas:
    - customTkinter (interface simples porém dinâmica)
    - datetime ( do próprio python pra poder capturar os horarios e fazer as conversões do formato de hora )
    - psycopg2 ( para interagir com o banco de dados postgreSQL)
    - reportlab ( para gerar relatórios em pdf, de todos os dados selecionádos )
    - tem um crud para os funcionários ( só preciso terminar a parte de editar o quadro de horas dos funcionários mas tudo bem )
    - vou fazer um crud para os pontos em si agr. mas por enquanto é isso.
  
