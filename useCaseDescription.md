Caso de Uso: Cadastrar Usuário
Referências: CSU001 
Descrição Geral: O caso de uso inicia-se quando o cliente deseja entrar pela primeira vez no aplicativo para realizar ou não a reserva de um hotel para seu pet.
Ator(es): Cliente (dono do pet)
Pré-condições: O cliente deve ter o aplicativo do sistema instalado no smartphone e ter conexão à internet.
Garantia de sucesso (Pós-condições): O aplicativo exibe a mensagem de que o cadastro do usuário foi realizado e este recebe uma nota de boas vindas em seu e-mail cadastrado no sistema.
Fluxo Básico: 
1. Cliente instala o aplicativo PetHoster em seu smartphone.
2. Cliente abre o aplicativo e seleciona a opção “Cadastrar-se”.
3. Sistema solicita os dados pessoais e a escolha de uma senha.
4. Cliente preenche os campos com seus dados e seleciona a opção “Confirmar”.
5. Sistema valida os dados preenchidos e exibe a mensagem “Cadastro realizado!”.
Fluxo Alternativo:
5a. Sistema verifica e realça algum dado preenchido incorretamente.
5b. Cliente preenche novamente o campo que estava incorreto e confirma os dados.

Caso de Uso: Efetuar Login
Referências: CSU002
Descrição Geral: O caso de uso inicia-se quando o cliente deseja entrar no aplicativo.
Ator(es): Cliente (dono do pet)
Pré-condições: O cliente precisa estar cadastrado no sistema.
Garantia de sucesso (Pós-condições): O aplicativo mostra a tela inicial do sistema para o usuário.
Fluxo Básico: 
1. Cliente abre o aplicativo PetHoster em seu smartphone.
2. Cliente preenche os campos “Usuário” e “Senha” com seus dados cadastrados.
3. Cliente seleciona a opção “Entrar”.
4. Sistema exibe a tela inicial para o cliente.
Fluxo Alternativo:
2a. Cliente preenche os campos “Usuário” e/ou “Senha” com dados incorretos.
2b. Sistema exibe a mensagem de que algum dos dados foi preenchido incorretamente.
2c. Após a terceira tentativa de login, caso apenas o campo “Usuário” esteja correto, é enviado um e-mail automaticamente para o cliente que possibilita que ele redefina sua senha.

Caso de Uso: Cadastrar Animal
Referências: CSU003
Descrição Geral: O caso de uso inicia-se quando o cliente realiza o login no aplicativo ou ao tentar realizar uma reserva para seu pet.
Ator(es): Cliente (dono do pet)
Pré-condições: Cliente já cadastrado no aplicativo e logado no sistema.
Garantia de sucesso (Pós-condições): O aplicativo exibe a mensagem para o usuário de que o cadastro do seu animal de estimação foi realizado.
Fluxo Básico: 
1. Cliente efetua login no aplicativo e seleciona a opção “Cadastrar Animal”.
2. Sistema solicita os principais dados relacionados à descrição e rotina diária do pet.
3. Cliente preenche os campos com os dados do pet e seleciona a opção “Confirmar”.
4. Sistema valida os dados preenchidos e exibe a mensagem “Animal cadastrado!”.
Fluxo Alternativo:
1a. Cliente entra no aplicativo, mas opta por fazer a busca por hotéis disponíveis para seu pet.
1b. Cliente tenta reservar um hotel para seu pet.
1c. Sistema solicita que o cliente cadastre ao menos um animal para agendar a reserva.
4a. Sistema verifica e realça algum dado preenchido incorretamente.
4b. Cliente preenche novamente o campo que estava incorreto e confirma os dados.

Caso de Uso: Editar Animal
Referências: CSU004
Descrição Geral: O caso de uso inicia-se quando o cliente deseja modificar alguma informação relacionada a seu pet.
Ator(es): Cliente (dono do pet)
Pré-condições: Cliente logado no sistema e com ao menos um pet cadastrado no aplicativo.
Garantia de sucesso (Pós-condições): O aplicativo exibe a mensagem para o usuário de que o cadastro do seu animal de estimação foi alterado.
Fluxo Básico: 
1. Cliente clica no menu principal do aplicativo e seleciona a opção “Meus Pets”.
2. Cliente seleciona o pet em questão e clica na opção “Editar”.
3. Cliente altera uma ou mais das informações exibidas.
4. Cliente seleciona a opção “Salvar alterações”.
5. Sistema valida os dados alterados e exibe a mensagem “Cadastro alterado!”.
Fluxo Alternativo:
5a. O sistema verifica e realça algum dado alterado de forma incorreta.
5b. Cliente preenche novamente o campo incorreto e seleciona a opção “Alterar”.

Caso de Uso: Excluir Animal
Referências: CSU005
Descrição Geral: O caso de uso inicia-se quando o cliente deseja excluir os dados de seu pet cadastrados no aplicativo.
Ator(es): Cliente (dono do pet)
Pré-condições: Cliente logado no sistema e com ao menos um pet cadastrado no aplicativo.
Garantia de sucesso (Pós-condições): O aplicativo exibe a mensagem para o usuário de que o cadastro do seu animal de estimação foi excluído.
Fluxo Básico: 
1.  Cliente clica no menu principal do aplicativo e seleciona a opção “Meus Pets”.
2. Cliente seleciona o pet em questão e clica na opção “Excluir”.
3. Sistema pergunta ao usuário(a) se ele(a) tem certeza de que deseja excluir o cadastro do animal selecionado.
4. Cliente seleciona a opção “Sim”.
5. Sistema exibe a mensagem “Cadastro excluído!”.
Fluxo Alternativo:
4a. Cliente seleciona a opção “Cancelar” e o cadastro do pet continua registrado no sistema.

Caso de Uso: Cadastrar Hotel
Referências: CSU006
Descrição Geral: O caso de uso inicia-se quando o administrador do hotel de animais de estimação deseja cadastrar seu estabelecimento no sistema.
Ator(es): Administrador (do hotel)
Pré-condições: O administrador deve ter o aplicativo do sistema para hotéis instalado no smartphone e ter conexão à internet.
Garantia de sucesso (Pós-condições): O aplicativo exibe a mensagem para o usuário de que o cadastro dos seus dados e do hotel foi realizado e recebe uma nota de boas vindas em seu e-mail cadastrado no sistema.
Fluxo Básico: 
1. Administrador instala o aplicativo PetHoster para hotéis em seu smartphone.
2. Administrador abre o aplicativo e seleciona a opção “Cadastrar-se”.
3. Sistema solicita os dados pessoais, dados do hotel e a escolha de uma senha.
4. Administrador preenche os campos com seus dados e seleciona a opção “Confirmar”.
5. Sistema valida os dados preenchidos e exibe a mensagem “Cadastro realizado!”.
Fluxo Alternativo:
5a. Sistema verifica e realça algum dado preenchido incorretamente.
5b. Administrador preenche novamente o campo que estava incorreto e confirma os dados.

Caso de Uso: Editar Hotel
Referências: CSU007
Descrição Geral: O caso de uso inicia-se quando o administrador do hotel deseja modificar alguma informação relacionada a seu estabelecimento.
Ator(es): Administrador (do hotel)
Pré-condições: Administrador logado no sistema e com ao menos um hotel cadastrado no aplicativo.
Garantia de sucesso (Pós-condições): O aplicativo exibe a mensagem para o administrador de que o cadastro do seu hotel foi alterado.
Fluxo Básico: 
1. Administrador abre menu principal do aplicativo e seleciona a opção “Meu Hotel”.
2. Administrador seleciona o hotel em questão e clica na opção “Editar”.
3. Administrador exclui ou altera uma ou mais das informações exibidas.
4. Administrador seleciona a opção “Salvar alterações”.
5. Sistema valida os dados alterados e exibe a mensagem “Cadastro alterado!”.
Fluxo Alternativo:
5a. O sistema verifica e realça algum dado do hotel alterado de forma incorreta.
5b. Administrador preenche novamente o campo incorreto e seleciona a opção “Alterar”.

Caso de Uso: Desativar Hotel
Referências: CSU008
Descrição Geral: O caso de uso inicia-se quando o administrador do hotel deseja desativar o hotel.
Ator(es): Administrador (do hotel)
Pré-condições: Administrador logado no sistema e com ao menos um hotel cadastrado no aplicativo.
Garantia de sucesso (Pós-condições): O aplicativo exibe a mensagem para o administrador de que o cadastro do seu hotel foi desativado e este não aparece mais nos resultados de busca.
Fluxo Básico: 
1. Administrador abre menu principal do aplicativo e seleciona a opção “Meu Hotel”.
2. Administrador seleciona o hotel em questão e clica na opção “Desativar”.
3. Sistema pergunta ao administrador se ele(a) tem certeza de que deseja desativar hotel.
4. Administrador seleciona a opção “Sim”.
5. Sistema solicita que o administrador digite sua senha de acesso ao aplicativo mais uma vez para desativar o hotel.
6. Administrador digita a senha no campo solicitado e clica na opção “Confirmar”.
7. Sistema exibe a mensagem “Hotel desativado!”
Fluxo Alternativo:
4a. Administrador seleciona a opção “Cancelar” e o cadastro do hotel continua registrado no sistema.

Caso de Uso: Buscar Hotel
Referências: CSU009
Descrição Geral: O caso de uso inicia-se quando o cliente deseja encontrar um ou mais hotéis disponíveis para hospedar o seu pet.
Ator(es): Cliente (dono do pet)
Pré-condições: Cliente logado no sistema.
Garantia de sucesso (Pós-condições): O aplicativo exibe os resultados de busca de acordo com o que o cliente digitou na ferramenta.
Fluxo Básico: 
1. Cliente acessa a ferramenta de busca do aplicativo na tela inicial.
2. Cliente digita a palavra-chave que deseja para encontrar os hotéis desejados.
3. Cliente marca/preenche os filtros de busca (tipo de animal, peso, categoria, data de check-in e check-out do pet no hotel, etc) necessários para que o sistema atenda ao que ele deseja.
4. Sistema exibe a lista de hotéis cadastrados que atende ao que o cliente procura.
Fluxo Alternativo:
3a. Cliente não marca/preenche algum filtro de busca necessário para que esta funcione, como, por exemplo, a data de check-in e check-out do pet no hotel.
3b. Sistema realça e avisa da obrigatoriedade do campo que faltou ser preenchido.
4a. Caso não haja hotel cadastrado que atenda ao que o cliente procura, o sistema exibe a mensagem “Não foram encontrados resultados para sua busca”.

Caso de Uso: Avaliar Hotel 
Referências: CSU010
Descrição Geral: O caso de uso inicia-se quando o cliente deseja avaliar um hotel em que seu pet já esteve hospedado.
Ator(es): Cliente (dono do pet)
Pré-condições: Cliente logado com ao menos uma reserva agendada e concluída para seu pet no sistema.
Garantia de sucesso (Pós-condições): O aplicativo grava a avaliação e/ou comentário do usuário e exibe com os dos demais clientes do estabelecimento. 
Fluxo Básico:
1. Cliente acessa o menu principal do aplicativo.
2. Cliente seleciona a opção “Reservas Anteriores”.
3. Sistema exibe a lista de hotéis cadastrados em que o cliente já hospedou o seu pet.
4. Cliente seleciona a opção “Avaliar Hotel” no estabelecimento desejado.
5. Cliente avalia o hotel em uma escala de 1 a 5 estrelas e preenche o campo de comentário (opcional) contando sua experiência com o estabelecimento.
6. Sistema grava a avaliação do cliente e a contabiliza com as demais e exibe o comentário deste na seção da página do hotel no aplicativo.
Fluxo Alternativo:
1a. Cliente acessa a ferramenta de busca e digita o nome do hotel que hospedou seu pet.
1b. Sistema exibe o hotel em questão na página de resultados da busca.
1c. Cliente entra na página do hotel no aplicativo e seleciona a opção “Avaliar Hotel”.
3a. Cliente não marca/preenche algum filtro de busca necessário para que esta funcione, como, por exemplo, a data de check-in e check-out do pet no hotel.
3b. Sistema realça e avisa da obrigatoriedade do campo que faltou ser preenchido.
4a. Caso não haja hotel cadastrado que atenda ao que o cliente procura, o sistema exibe a mensagem “Não foram encontrados resultados para sua busca”.

Caso de Uso: Agendar Reserva
Referências: CSU011
Descrição Geral: O caso de uso inicia-se quando o cliente escolhe um hotel para hospedar seu pet durante um determinado período.
Ator(es): Cliente (dono do pet)
Pré-condições: Cliente logado no sistema e com ao menos um pet cadastrado no aplicativo.
Garantia de sucesso (Pós-condições): O aplicativo exibe a mensagem para o usuário de que a reserva do hotel para seu pet foi efetuada.
Fluxo Básico:
1. Cliente acessa a página do hotel desejado para hospedar seu pet.
2. Cliente seleciona a opção “Agendar Reserva”.
3. Sistema exige que o cliente selecione para qual animal cadastrado é a reserva.
4. Sistema exibe os quartos e serviços disponíveis para o pet no hotel desejado.
5. Sistema exibe o valor a ser cobrado pela hospedagem.
6. Sistema valida os dados e exibe a mensagem “Reserva Concluída!”.
7. Sistema envia e-mail para o usuário com dados da reserva.
Fluxo Alternativo:
3a. Hotel não atende o tipo de animal cadastrado pelo cliente.
3b. Cliente refina a busca de hotéis para as características do animal cadastrado.

Caso de Uso: Editar Reserva
Referências: CSU012
Descrição Geral: O caso de uso inicia-se quando o cliente deseja alterar o período de reserva do hotel para seu pet.
Ator(es): Cliente (dono do pet)
Pré-condições: Cliente logado no sistema e com ao menos uma reserva de hotel agendada para o pet no sistema.
Garantia de sucesso (Pós-condições): O aplicativo exibe a mensagem para o usuário de que a reserva do hotel para seu pet foi alterada.
Fluxo Básico:
1. Cliente acessa o menu principal do aplicativo e seleciona a opção “Reservas”.
2. Cliente seleciona o hotel em questão e clica na opção “Editar Reserva”.
3. Sistema exibe datas anteriores e posteriores à reserva agendada com quartos disponíveis para o pet no hotel.
4. Cliente aumenta ou diminui o período de estadia do seu pet no hotel desejado.
5. Sistema exibe o novo valor da reserva para o usuário.
6. Cliente seleciona a opção “Confirmar”.
7. Sistema exibe a mensagem “Reserva Alterada!”.
8. Sistema estorna o valor antigo da reserva e cobra o novo valor da forma de pagamento escolhida.
Fluxo Alternativo:
3a. Sistema exibe mensagem de que não há datas disponíveis para alteração da reserva.

Caso de Uso: Excluir Reserva
Referências: CSU013
Descrição Geral: O caso de uso inicia-se quando o cliente deseja cancelar o período a reserva do hotel agendada para seu pet.
Ator(es): Cliente (dono do pet)
Pré-condições: Cliente logado no sistema e com ao menos uma reserva de hotel agendada para o pet no sistema.
Garantia de sucesso (Pós-condições): O aplicativo exibe a mensagem para o usuário de que a reserva do hotel para seu pet foi cancelada.
Fluxo Básico:
1. Cliente acessa o menu principal do aplicativo e seleciona a opção “Reservas”.
2. Cliente seleciona o hotel em questão e clica na opção “Excluir Reserva”.
3. Sistema pergunta ao cliente se este tem certeza que deseja cancelar a reserva selecionada.
4. Cliente seleciona a opção “Sim”.
5. Sistema exibe a mensagem “Reserva Cancelada!”.
Fluxo Alternativo:
3a. Cliente seleciona a opção “Cancelar” e a reserva em questão continua inalterada.

Caso de Uso: Editar Quarto
Referências: CSU014
Descrição Geral: O caso de uso inicia-se quando o administrador seleciona o menu “Meu hotel” e clica em “Editar quarto”.
Ator(es):  Administrador (do hotel)
Pré-condições: O administrador deve estar logado no sistema.
Garantia de sucesso (Pós-condições): O aplicativo exibe a mensagem para o administrador de que o quarto foi editado com sucesso.
Fluxo Básico: 
1. Administrador do hotel instala o aplicativo PetHoster em seu smartphone.
2. Administrador seleciona o menu “Meu hotel”.
3. Administrador clica em “Buscar quarto”, e em seguida seleciona o quarto que deseja editar.
4. Administrador clica em “Editar quarto”.
5. Administrador edita as informações e clica no botão “Confirmar”.
6. Sistema retorna a mensagem “Quarto editado com sucesso”.
Fluxo Alternativo:
5. Administrador clica no botão “Cancelar”.

Caso de Uso: Buscar Quarto
Referências: CSU015
Descrição Geral: O caso de uso inicia-se quando o cliente procura um hotel para agendar a reserva, com o objetivo de buscar os quartos do hotel.
Ator(es): Cliente (dono do pet)
Pré-condições: Cliente logado no sistema e com ao menos um pet cadastrado no aplicativo.
Garantia de sucesso (Pós-condições): O aplicativo exibe os resultados de busca de acordo com o que o cliente digitou na ferramenta.
Fluxo Básico:
1. Cliente acessa a página do hotel desejado para hospedar seu pet.
2. Cliente seleciona a opção “Agendar Reserva”.
3. Sistema exige que o cliente selecione para qual animal cadastrado é a reserva.
4. Sistema exibe os quartos e serviços disponíveis para o pet no hotel desejado.
Fluxo Alternativo:
3a. Hotel não atende o tipo de animal cadastrado pelo cliente.

Caso de Uso: Cadastrar Quarto
Referências: CSU016 
Descrição Geral: O caso de uso inicia-se quando o administrador seleciona o menu “Meu hotel” e clica em “Novo quarto”.
Ator(es): Administrador (dono do hotel)
Pré-condições: O administrador deve ter o aplicativo do sistema instalado no smartphone e ter conexão à internet.
Garantia de sucesso (Pós-condições): O aplicativo exibe a mensagem de que o cadastro do quarto foi realizado com sucesso.
Fluxo Básico: 
1. Administrador do hotel instala o aplicativo PetHoster em seu smartphone.
2. Administrador seleciona o menu “Meu hotel”
3. Administrador clica em “Novo quarto”.
4. Administrador preenche os dados do quarto e uma descrição.
5. Administrador clica no botão salvar.
6. Sistema retorna a mensagem “Quarto cadastrado com sucesso”.
Fluxo Alternativo:
5a. Sistema verifica e realça algum dado preenchido incorretamente.
5b. Cliente preenche novamente o campo que estava incorreto e confirma os dados.

Caso de Uso: Buscar Reserva
Referências: CSU017
Descrição Geral: O  caso de uso inicia-se quando o cliente deseja encontrar uma reserva de hotel que foi agendada para seu pet.
Ator(es): Cliente (dono do pet)
Pré-condições: Cliente logado no sistema.
Garantia de sucesso (Pós-condições): O aplicativo exibe a lista de reservas agendadas ou concluídas para seus pets cadastrados.
Fluxo Básico: 
1. Cliente abre o menu principal do aplicativo.
2. Cliente seleciona a opção "Reservas".
3. Sistema exibe a lista de reservas agendadas ou concluídas para os pets cadastrados do cliente.
Fluxo Alternativo:
3a. Caso o cliente ainda não tenha agendado nenhuma reserva no aplicativo, sistema exibe a mensagem "Você não realizou nenhuma reserva até o momento".

Caso de Uso: Buscar Animal
Referências: CSU018
Descrição Geral: O  caso de uso inicia-se quando o cliente deseja encontrar um animal dentre os seus pets cadastrados.
Ator(es): Cliente (dono do pet)
Pré-condições: Cliente logado no sistema.
Garantia de sucesso (Pós-condições): O aplicativo exibe os animais cadastrados do usuário na página “Meus Pets”.
Fluxo Básico: 
1. Cliente abre o menu principal do aplicativo.
2. Cliente seleciona a opção "Meus pets".
3. Sistema exibe os animais cadastrados do cliente.
Fluxo Alternativo:
3a. Caso o cliente ainda não tenha agendado nenhum pet no aplicativo, sistema exibe a mensagem "Você não possui nenhum pet".


Caso de Uso: Apagar Quarto
Referências: CSU019
Descrição Geral: O caso de uso inicia-se quando o administrador seleciona o menu “Meu hotel” e clica em “Apagar quarto”.
Ator(es): Administrador (dono do hotel)
Pré-condições: O administrador deve ter o aplicativo do sistema instalado no smartphone e ter conexão à internet.
Garantia de sucesso (Pós-condições): O aplicativo exibe a mensagem de que o quarto foi deletado com sucesso.
Fluxo Básico: 
1. Administrador do hotel instala o aplicativo PetHoster em seu smartphone.
2. Administrador seleciona o menu “Meu hotel”.
3. Administrador clica em “Buscar quarto”, e em seguida seleciona o quarto que deseja deletar.
4. Administrador clica em “Deletar quarto”.
5. Administrador clica no botão “Confirmar”.
6. Sistema retorna a mensagem “Quarto deletado com sucesso”.
Fluxo Alternativo:
5. Administrador clica no botão “Cancelar”.

Caso de Uso: Editar Usuário
Referências: CSU020
Descrição Geral: O caso de uso inicia-se quando o usuário deseja editar seu perfil.
Ator(es):  Cliente (dono do pet)
Pré-condições: O usuário deve estar logado no sistema.
Garantia de sucesso (Pós-condições): O aplicativo exibe a mensagem para o usuário de que os seus dados foram alterados com sucesso
Fluxo Básico:
1. Usuário abre menu principal do aplicativo e seleciona a opção “Meu Perfil”.
2. Usuário seleciona o hotel em questão e clica na opção “Editar”.
3. Usuário altera seus dados conforme desejar.
4. Usuário seleciona a opção “Salvar alterações”.
5. Sistema valida os dados alterados e exibe a mensagem “Perfil alterado com sucesso!!”.
Fluxo Alternativo:
3a. Administrador seleciona a opção “Cancelar” e os dados não são alterados.

Caso de Uso: Excluir Usuário
Referências: CSU021
Descrição Geral: O  caso de uso inicia-se quando o cliente deseja excluir todos os seus dados do sistema.
Ator(es): Cliente (dono do pet)
Pré-condições: Cliente logado no sistema.
Garantia de sucesso (Pós-condições): O aplicativo desloga o cliente do sistema e informa que sua conta foi excluída.
Fluxo Básico: 
1. Cliente abre o menu principal do aplicativo.
2. Cliente seleciona a opção "Dados da conta".
3. Sistema exibe os dados do cliente cadastrados.
4. Cliente marca a opção "Desejo excluir minha conta".
5. Sistema pergunta ao usuário se ele tem certeza da decisão.
6. Cliente seleciona a opção "OK".
7. Sistema pede ao cliente que ele digite sua senha cadastrada no aplicativo.
8. Cliente digita a senha e seleciona a opção "Confirmar".
9. Sistema pede ao usuário que ele digite o código de verificação enviado via SMS para seu número de telefone cadastrado.
10. Usuário digita o código de verificação recebido.
11. Sistema verifica o código preenchido, desloga o usuário do aplicativo e exibe a mensagem "Conta excluída com sucesso!".
Fluxo Alternativo:
6a. Cliente seleciona a opção "Cancelar" e seu cadastro no sistema segue inalterado.
9a. Cliente não recebe o código ou o digita incorretamente.
9b. Sistema envia outro código de verificação via SMS para o cliente em um prazo de até 1 minuto.