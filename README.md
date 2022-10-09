# Tela-de-login
Conceito: 
- Tela de login para um site genérico, com cores mais escura no fundo para evidenciar o centro da tela que possui uma cor mais clara, com ícones auxiliando o usuário a entender a sua ação.
- Público-alvo: A maior parte do público desktop, sem opções de acessibilidade.
- O site não terá transições animadas e responsividade, e todos os campos de inserção de dados terão os placeholders apagados ao usuário digitar alguma coisa.
- Por enquanto, o site ainda não possui validação das credenciais.

Explicação do funcionamento da página:
Começando do frame “Tela de login”:
- O botão de “CADASTRAR CONTA” levando para o frame “Tela de cadastro”.
- O botão “Entrar” conferindo os dados e levando ao site com seus dados autenticados, caso os dados estejam ausentes ou incorretos o frame mostrará um erro.
- Ao passar o mouse por cima de “Esqueceu sua senha/usuário?” aparecerá uma linha em baixo da frase.

No frame “Tela de cadastro”:
- O botão “registar conta” levará ao site com a sua conta e os seus dados cadastrados no sistema, caso os dados estejam ausentes ou incorretos o frame mostrará um erro.
- O botão “Já tem uma conta?” retornará ao frame “Tela de login”

No frame “Tela de envio do código por e-mail”:
- A opção “Esqueceu sua senha/usuário?” do frame “Tela de login” levará para este frame.
- Levará ao frame “Tela de recebimento do código” caso o campo seja preenchido com um e-mail válido, caso os dados estejam ausentes ou incorretos o frame mostrará um erro.
- Após a inserção do e-mail solicitado, o usuário receberá em sua caixa de e-mail, o código requerido pelo próximo frame.

No frame “Tela de recebimento do código”:
- O usuário irá digitar o código recebido e então o sistema verificará se o código informado pelo usuário é válido para então passar para o próximo frame.
- Caso os dados estejam ausentes ou incorretos o frame mostrará um erro.

No frame “Tela de Redefinir dados da conta”:
- Neste frame, ao clicar no botão enviar os dados anteriores do usuário serão deletados, e substituídos pelos inseridos pelo usuário.
- O botão enviar irá voltar para o frame “Tela de login” para o usuário entrar na sua conta com seus novos dados.
- Caso os dados estejam ausentes ou incorretos o frame mostrará um erro.

Cores dos elementos das páginas
- Plano de fundo: #EBEBEB;
- Cor da Div central: #FFFFFF;
- Cor da Borda da div central: #000000;
- Cor do link “Esqueceu sua senha/usuário?” e da linha abaixo da frase, ao passar o mouse, no frame de Login: #144999;
- Cor da borda e do botão ENTRAR no frame de Login: #44E0FF;
- Cor do botão ENTRAR, no frame de Login, ao passar com o mouse por cima do mesmo: #3BADC4;
- Cor dos demais botões do site: #F82A15;
- Cor dos demais botões do site ao passar com o mouse por cima do mesmo: #DA2B18;
