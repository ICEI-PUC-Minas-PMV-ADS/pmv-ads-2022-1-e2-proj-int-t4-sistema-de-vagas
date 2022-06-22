# Registro de Testes de Software
<div align = "center">
  
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
|Caso de Teste |CT 01 - Cadastrar usuários no site (empresas e candidatos) | 
|--------------------|------------------------------------|
| RF 01 | O sistema deve permitir o cadastro de empresas recrutadoras | 
| RF 02 | O sistema deve permitir o cadastro de pessoas candidatas a posições de trabalho | 
| Passos	| 1) Acessar o navegador 2) Informar o endereço do site 3) Visualizar a página principal 4) Clicar no botão "Registrar-se" 5) Completar o formulário de informações. |
| Critérios de Êxito | As informações dos usuários devem ser salvas no banco de dados - Os dados salvos devem ser passíveis de visualização antes de serem salvos. | 
|Resultado| Cadastro de usuários concluido com êxito |
|Evidência | <img alt="imagem" src="https://raw.githubusercontent.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2022-1-e2-proj-int-t4-site_vagasIC/main/docs/img/4Tela de cadastro.png">|
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

|Caso de Teste | CT-02 - Publicação e pesquisa de vagas de emprego |
|--------------------|------------------------------------|
| RF 03 | O sistema deve permitir a publicação de posições de trabalho|
|Passos | 1) Acessar o navegador 2) Informar o endereço do site 3) Visualizar a página principal 4) Clicar no botão Vagas 5) Clicar no botao "registrar vaga" |
|Critérios de Êxito | Conseguir salvar e compartilhar o link de uma vaga registrada pela empresa.|
|Resultado| Publicação e pesquisa de vagas realizada com sucesso|
|Evidência |<img alt="imagem" src="https://raw.githubusercontent.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2022-1-e2-proj-int-t4-site_vagasIC/main/docs/img/6Tela de vagas candidato.png"><img alt="imagem" src="https://raw.githubusercontent.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2022-1-e2-proj-int-t4-site_vagasIC/main/docs/img/18Tela de nova vaga.png">|                                      

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
|Caso de Teste | CT 03 - Pesquisar vagas de emprego |
|--------------------|------------------------------------|
| RF 04 | O sistema deve permitir a pesquisa por vagas de emprego|
|Passos | 1) Acessar o navegador 2) Informar o endereço do site 3) Visualizar a página principal 4) Clicar no botão Vagas 5) Clicar no botao "pesquisar vaga".|
|Critérios de Êxito | Ter resultado de vagas após a pesquisa.|
|Resultado| Pesquisa de vagas e resultado concluido com êxito.|
|Evidência | 
<img alt="imagem" src="https://raw.githubusercontent.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2022-1-e2-proj-int-t4-site_vagasIC/main/docs/img/5Tela inicial candidato.png">
<img alt="imagem" src="https://raw.githubusercontent.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2022-1-e2-proj-int-t4-site_vagasIC/main/docs/img/6Tela de vagas candidato.png">|

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
|Caso de Teste | CT 04 - Candidatura para vagas |
|--------------------|------------------------------------|
| RF 06 | O sistema deve permitir ao usuário a candidatura para as vagas de trabalho |
|Passos | 1) Acessar o navegador 2) Informar o endereço do site 3) Visualizar a página principal 4) Clicar no botão Vagas 5) Clicar no botão "pesquisar vaga" 6) Selecionar a vaga desejada 7) Clicar em "Candidatar-se" |
|Critérios de Êxito | A candidatura deve ser salva no banco com as informações do candidato e apresentar as informações à empresa que registrou a vaga.|
|Resultado| Candidatura para vagas concluido com êxito.|
|Evidência |<img alt="imagem" src="https://raw.githubusercontent.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2022-1-e2-proj-int-t4-site_vagasIC/main/docs/img/7Tela de candidatura feita.png">|

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
|Caso de Teste | CT 05 -  Cadastro de currículo |
|--------------------|------------------------------------|
| RF 08 | O sistema deve possuir filtro de busca para critérios conforme demanda| 
|Passos | 1) Acessar o navegador 2) Informar o endereço do site 3) Visualizar a página principal 4) Clicar no botão perfil 5) Clicar no botão "COnfigurar CV" 6) Cadastrar o formulário 7) Clicar em "Finalizar"|
|Critérios de Êxito | Usuário conseguir finalizar cadastro com êxito.|
|Entradas| Usuários, currículo, formulário|
|Objetivo do teste | Constatar se formulário para cadastro de informações de currículos está ocorrendo com êxito|
|Evidência |<img alt="imagem" src="https://raw.githubusercontent.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2022-1-e2-proj-int-t4-site_vagasIC/main/docs/img/6Tela de vagas candidato.png">|
  
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
|Caso de Teste | CT 06 - Recebimento de informaçoes de vagas |
|--------------------|------------------------------------|
| RF 12 | O sistema deve permitir o cadastro de email para recebimento de vagas de trabalho|
|Passos | 1) Acessar o navegador 2) Informar o endereço do site 3) Visualizar a página principal 4) Clicar no botão "Registrar-se" 5) Completar o formulário de informações 6) Clicar no botão "receber informações sobre vagas relacionadas ao meu currículo"|
|Critérios de Êxito | Chegar no email do candidato vagas que correspondem as informações do curriculo que ele registrou e salvar vagas de interesse|
|Resultado| Recebimento de informações de vagas realizado com sucesso.|
|Evidência |<img alt="imagem" src="https://raw.githubusercontent.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2022-1-e2-proj-int-t4-site_vagasIC/main/docs/img/8Tela de vagas salvas.png">|

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
|Caso de Teste | CT 07 - Recebimento de informações de candidatos|
|--------------------|------------------------------------|
| RF 13 | O sistema deve permitir o cadastro de email para recebimento de pessoas candidatas|
|Passos | 1) Acessar o navegador 2) Informar o endereço do site 3) Visualizar a página principal 4) Clicar no botão "Registrar-se" 5) Completar o formulário de informações 6) Clicar no botão "receber informações sobre candidatos registrados".|
|Critérios de Êxito | Chegar aviso no email da empresa com candidatos que se registraramna vaga|
|Resultado| Recebimento de informações de cadidatos concluido com êxito|
|Evidência | <img alt="imagem" src="https://raw.githubusercontent.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2022-1-e2-proj-int-t4-site_vagasIC/main/docs/img/20Tela de candidatos.png">|

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
|Caso de Teste | CT 08 - Registro de dúvidas e ajuda para candidatos e empresas|
|--------------------|------------------------------------|
| RF 17 | O sistema deve conter uma página com espaço para envio de dúvidas, sugestões, elogios e/ou reclamações|
|Passos | 1) Acessar o navegador 2) Informar o endereço do site 3) Visualizar a página principal 4) Rolar até o rodapé da página 5) Clicar em "Ajuda"|
|Critérios de Êxito | Chegar email para os mantenedores do site com as mansagens de quem entrou em contato|
|Resultado| Registro de dúvidas e ajuda concluido com êxito|
|Evidência |<img alt="imagem" src="https://raw.githubusercontent.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2022-1-e2-proj-int-t4-site_vagasIC/main/docs/img/Tela de FAQ.png">>|
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
