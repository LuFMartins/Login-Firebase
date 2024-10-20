# Login-Firebase
Projeto desenvolvido no Android Studio utilizando a linguagem Java, com o intuito de criar um aplicativo de autenticação integrado ao Firebase. O app permite que usuários realizem cadastro, login, recuperação de senha garantindo uma experiência segura e prática.

*********************************************************************************************************************

*** RELATÓRIO:

Durante o desenvolvimento do meu aplicativo no Android Studio, o objetivo principal foi criar um app que oferecesse funcionalidades de login, cadastro de usuários e redefinição de senha, utilizando a plataforma Firebase Authentication.

O processo de desenvolvimento teve início com a criação de um layout intuitivo para as telas de login, cadastro e redefinição de senha. Essas interfaces precisavam ser amigáveis e funcionais, proporcionando uma boa experiência ao usuário.

Após criar o projeto no Firebase, foi necessário configurar o app Android para se comunicar com o backend do Firebase. Isso envolveu a inserção do arquivo google-services.json no diretório correto do projeto e a adição das dependências necessárias no arquivo build.gradle. Segui um processo detalhado, assegurando que a autenticação via Firebase estivesse configurada adequadamente para realizar o gerenciamento de usuários.


<div align="center">
  <img src="https://github-production-user-asset-6210df.s3.amazonaws.com/94010799/378187053-ca0f7b0e-a889-4303-a4a8-05b8e9098775.jpeg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20241020%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20241020T122958Z&X-Amz-Expires=300&X-Amz-Signature=5ca0e83f58c5461bdade0fe3fda1969faf8dc74127db3252b2664e3e2834358a&X-Amz-SignedHeaders=host" width="700"/>
</div>

<div align="center">
  <img src="https://github-production-user-asset-6210df.s3.amazonaws.com/94010799/378187406-d08462f7-0e81-404d-9790-03bba17c38cd.jpeg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20241020%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20241020T123203Z&X-Amz-Expires=300&X-Amz-Signature=a859115a8f3025f9fa94bd2b40a9466e32c63ebc7d4b3af80400409d0fed690d&X-Amz-SignedHeaders=host" width="700"/>
</div>

<div align="center">
  <img src="https://github-production-user-asset-6210df.s3.amazonaws.com/94010799/378187410-561e491f-d218-487b-99ab-0d70da3464d7.jpeg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20241020%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20241020T123227Z&X-Amz-Expires=300&X-Amz-Signature=990109266ce3fa5dcc792c37eb01522c42b390f1408d989b312d3ff4c84ba5e3&X-Amz-SignedHeaders=host" width="700"/>
</div>

<div align="center">
  <img src="https://github-production-user-asset-6210df.s3.amazonaws.com/94010799/378187412-bacbd85b-bde4-4501-93fc-46b10bd065e2.jpeg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20241020%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20241020T123247Z&X-Amz-Expires=300&X-Amz-Signature=a7e94147b0433066bd3c8c7c4499f52309ac68b91677d634863a005144182770&X-Amz-SignedHeaders=host" width="700"/>
</div>

<div align="center">
  <img src="https://github-production-user-asset-6210df.s3.amazonaws.com/94010799/378187380-8045dd0f-2600-4972-be81-0c9343fc91b7.jpeg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20241020%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20241020T123334Z&X-Amz-Expires=300&X-Amz-Signature=33e19ab40864eb8c131a14897d8369af3fda8f35324f114c35a58eb1926c5947&X-Amz-SignedHeaders=host" width="700"/>
</div>

*********************************************************************************************************************


Optei por adotar um design com uma pegada de jogos para tornar o aplicativo mais atrativo e ao mesmo tempo intuitivo, especialmente para usuários que buscam algo interativo e simples de usar. A ideia era que, desde o momento em que o usuário abrisse o app, ele sentisse que a interface era fácil de navegar, mas também divertida, com elementos visuais que lembrassem o universo dos games.

Para obter o plano de fundo usado nas minhas telas, acessei o site https://pixabay.com/pt/, onde possuei diversas imagens e ilustrações que podem ser usadas de forma gratuita!

<div align="center">
  <img src="https://github-production-user-asset-6210df.s3.amazonaws.com/94010799/378187385-08094811-32bc-4978-92a4-54f2f8bb3d84.jpeg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20241020%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20241020T123611Z&X-Amz-Expires=300&X-Amz-Signature=0f366de495859298d54032f5872c11802ccf417672c2a7dcd120d0a0f1e9f77c&X-Amz-SignedHeaders=host" width="700"/>
</div>

<div align="center">
  <img src="https://github-production-user-asset-6210df.s3.amazonaws.com/94010799/378187383-bf1b77a9-31f3-4dfa-bbb0-c61afa8825a1.jpeg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20241020%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20241020T123948Z&X-Amz-Expires=300&X-Amz-Signature=defe353fdf34bf1af3246f4ae1e74a38244a6009c88b773182b15bfec9804dc7&X-Amz-SignedHeaders=host" width="700"/>
</div>

<div align="center">
  <img src="https://github-production-user-asset-6210df.s3.amazonaws.com/94010799/378187391-3f06b005-2b8c-42c1-b46a-b8dfe93e9698.jpeg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20241020%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20241020T124002Z&X-Amz-Expires=300&X-Amz-Signature=33e499da335c6d2bde6c23be5e8aec6b9ada2d3059ec38d575e77afdba59c475&X-Amz-SignedHeaders=host" width="700"/>
</div>

<div align="center">
  <img src="https://github-production-user-asset-6210df.s3.amazonaws.com/94010799/378187388-d91d5dda-8ced-4947-8b0c-7462fbcb1b3c.jpeg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20241020%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20241020T124018Z&X-Amz-Expires=300&X-Amz-Signature=91163305308c7533018e4ed79a18c246f50b1fa539ae71fa24e6a3428cad3a6d&X-Amz-SignedHeaders=host" width="700"/>
</div>

<div align="center">
  <img src="https://github-production-user-asset-6210df.s3.amazonaws.com/94010799/378187395-ce5a5ab6-7b5b-4a0b-8068-f4346a54f6e7.jpeg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20241020%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20241020T124034Z&X-Amz-Expires=300&X-Amz-Signature=c5a07f62f855919661c4e9ee016c4c29a450746b9aab5f2f09680b7eb712a11b&X-Amz-SignedHeaders=host" width="700"/>
</div>

Obs: Nos prints acima: alguns botões estão roxo, e o ultimo está verde. Na parte de estilização, tentei mudar todos os botões para verde, mas não mudava. Depois de um tempo, descobri, tentando tirar a TitleBar da minha simulação, que era preciso mudar o tema da minha "AndroidManifest.xml"

De:
android:theme="@style/Theme.LoginFirebase"
Para:
android:theme="@style/Theme.AppCompat.Light.NoActionBar"

Assim, tirando aquela barra com o nome do projeto da minha simulação, consegui mudar as cores que vinham como padrões para aquelas que eu queria.

*********************************************************************************************************************

Durante o processo de desenvolvimento, optei por usar o binding para facilitar a associação dos elementos da minha Activity.

O binding é uma abordagem moderna e eficiente para trabalhar com a interface do usuário no Android, oferecendo uma maneira mais segura e prática de vincular elementos da UI ao código, reduzindo a quantidade de código repetitivo e potencialmente propenso a erros.

<div align="center">
  <img src="https://github-production-user-asset-6210df.s3.amazonaws.com/94010799/378187398-e78d19c4-c5f5-41dd-948c-220f870a4909.jpeg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20241020%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20241020T124843Z&X-Amz-Expires=300&X-Amz-Signature=f4b33459c7a9d6ddb203c0d31461ab4a71cdbe0929eda02510604dadbd2b3218&X-Amz-SignedHeaders=host" width="700"/>
</div>

*********************************************************************************************************************

A cada nova Activity que eu criava, realizava testes contínuos para garantir que as funcionalidades estivessem funcionando corretamente. Esse processo de testar em cada etapa foi essencial para evitar que algo saísse dos trilhos, garantindo que os componentes da interface e as interações com o usuário respondessem como esperado.

Ao final do processo, foi muito gratificante ver os dados sendo cadastrados com sucesso no Firebase. Esse momento foi um marco importante no desenvolvimento, pois confirmou que as funcionalidades que eu havia planejado estavam todas em pleno funcionamento. Entre essas funcionalidades, destacar a verificação de e-mails duplicados no cadastro e o sistema de recuperação de senha foram grandes conquistas.

Esse fluxo de validação de dados, especialmente na integração com o Firebase, trouxe confiança ao projeto, pois assegurou que o sistema fosse robusto e atendesse às necessidades planejadas. Ver tudo funcionando conforme o esperado me deu uma sensação de realização e mostrou o quanto o esforço investido valeu a pena.

<div align="center">
  <img src="https://github-production-user-asset-6210df.s3.amazonaws.com/94010799/378187401-d8a6d4c9-24e2-48eb-9521-c0752c79fa4e.jpeg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20241020%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20241020T124924Z&X-Amz-Expires=300&X-Amz-Signature=c3ddd8aba216c19b504bf7210e0185318b8e22cc2e4f6e2f8d92948e67987cf6&X-Amz-SignedHeaders=host" width="700"/>
</div>
