# Tutorial Katalon

Neste tutorial veremos uma breve introdução sobre o  Katalon Studio, um conjunto de ferramentas  para testes de automação de aplicativos da Web, API, dispositivos móveis e desktop. 

## Primeiros passos

### A ferramenta 

O Katalon é uma solução de automação de teste que aproveita o mecanismo principal do Selenium. Embora use várias funcionalidades do Selenium, não é simplesmente um wrapper do Selenium.

Selenium é uma biblioteca de testes automatizados mais adequadas para testadores que possuem boas habilidades de programação

 Já para o Katalon, o conhecimento sobre as tecnologias relacionadas ao  aplicativo em teste  não é obrigatório, a plataforma esconde todas as complexidades técnicas nos bastidores e fornece uma interface amigável com o modo manual para usuários tecnicamente mais avançados.


### Licença e Instalação 

Para a instalação do Katalon, basta seguir o passo a passo:

- A ferramenta está disponível para todos os testadores, tanto na versão gratuita quanto na licenciada, disponível no [Site Oficial](https://katalon.com/)
- Clique em "Start Free Trial"
- Forneça as informações solicitadas, como seu nome, ID de e-mail válido (Para obter o software ,precisamos nos registrar usando um endereço de e-mail comercial), senha .
- Leia e concorde com a política de privacidade
- Clique em Baixar
- Selecione a versão de download necessária( neste tutorial estamos utilizando a  versão Katalon Studio – Standalone Edition ).


[FIGURA 1](https://drive.google.com/file/d/1RfAt0kkMwcuUYswEWRIhJ1QT2ywdD60l/view?usp=sharing)

- Clique em Aceitar e Baixar
- Quando o download estiver concluído, visite a pasta onde foi baixado a ferramenta Katalon Studio
- Para instalá-lo, execute Katalon.exe
- Insira as credenciais da conta que você usou ao se inscrever


## Primeiro Teste

Com tudo funcionando, vamos começar a criar nosso primeiro projeto no Katalon Studio,para isso  precisamos clicar no link do n
“New Project” que está no painel superior esquerdo. 

[FIGURA 2](https://drive.google.com/file/d/1a7DsHJqMTrJw_n_gtZA_ICFBWLtLpc1A/view?usp=sharing)

- Selecione web nas opções de tipo 
- Deixar projeto em branco 
- Para url do repositório, não inseriremos nada (embora tenha em mente que você pode ter este projeto dentro de um repositório no github, bitbucket, etc.)
- Selecione o local onde queremos salvar nosso projeto local 
- Adicione uma descrição
- Clique em ok  

[FIGURA 3](https://drive.google.com/file/d/1LUXsejZp_eidof2vHjKwA7omzwnkEzdj/view?usp=sharing)

Agora vamos utilizar a funcionalidade  record web ( localizado no cando superior da tela), isso abre um “gravador” onde devemos primeiro inserir a URL que queremos gravar, e depois é só clicar no ícone do navegador. 

[FIGURA 4](https://drive.google.com/file/d/1WZw8vzV-w5EPEWYb1Bf3Emf_Cb_2xp1r/view?usp=sharing)

Depois de fazer isso, um navegador da web será aberto em nossa máquina e começará a registrar tudo o que fazemos nela: o que clicamos, os formulários que preenchemos etc. 

[FIGURA 5](https://drive.google.com/file/d/12U3wPE65aG90NqljBfNK_Pulbv9YO9oz/view?usp=sharing)

Agora você verá o navegador aberto para a URL que inserimos, então basta usar o site como desejar, para este tutorial acessaremos o site de testes [Soucedemo](https://www.saucedemo.com/)

[FIGURA 6](https://drive.google.com/file/d/1PI8Ljk2usIQdbI7H8AYhJYBILCUaFX7S/view?usp=sharing)

 Para este tutorial fizemos o seguinte teste
 - Saucedemo.com aberto 
 - Escrever um dos Logins validos, neste caso o “Standard_user”
 - Escrever uma das senha validas, neste caso “secret_sauce ”
 - Clicar no botão  login  que nos redirecionou para a página inicial 
 
 Como você pode ser observado na [FIGURA 7](https://drive.google.com/file/d/1rmCdQG-sMt2ph7aXzTSlWb4GDkK2Oin3/view?usp=sharing) ver, todas essas ações foram registradas na ordem em que as fizemos. 
 
 Agora, vamos apenas clicar no botão parar de gravar no canto superior direito do gravador. Você notará que uma nova etapa foi adicionada automaticamente que diz fechar o navegador, isso é apenas para fechar a janela do navegador que foi aberta automaticamente, para evitar que muitos deles sejam abertos em nossa máquina. 
 
 Também podemos executá-los sempre que quisermos apenas clicando no botão verde de reprodução.  A partir desta lista você pode escolher qualquer navegador web (instalado em seu computador) que quiser
[FIGURA 8](https://drive.google.com/file/d/15cK2hYXw25wz1ulqT2fbcsdZ-NKSbjKQ/view?usp=sharing)

 Após a execução dos testes podemos observar na aba "LOG VIEWER" os resultados obtidos pelos testes.
[FIGURA 9](https://drive.google.com/file/d/17XlGfUKl5wBlnCo1ipuEstBH5SRAOvLH/view?usp=sharing)
