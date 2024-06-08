# INTENTEXTRARESULT
👨‍🏫PROJETO CRIADO PARA O CURSO DE ANDROID STUDIO EM KOTLIN.

<img src="./IMAGENS/FOTO_1.png" align="center" width="500"> <br>
<img src="./IMAGENS/FOTO_2.png" align="center" width="500"> <br>

## DESCRIÇÃO:
- Este aplicativo Android permite que os usuários mudem o nome exibido na tela principal ao clicar em um botão. 

- Este aplicativo demonstra como usar intents para passar dados entre atividades e como usar contratos de Activity Result para receber resultados de atividades secundárias. Ele fornece uma maneira simples de interagir com o usuário e atualizar dinamicamente a interface do usuário com base nas interações do usuário.

## FUNCIONALIDADES:
1. **Interface Simples**:
   - A tela principal contém um TextView centralizado que exibe uma saudação "Olá Utilizador" com um tamanho de fonte grande.
   - Abaixo do TextView, há um botão "Mudar nome".

2. **Funcionalidade de Mudança de Nome**:
   - Ao clicar no botão "Mudar nome", o aplicativo inicia uma nova atividade (MainActivity2) usando um Intent.
   - O nome atual é passado para a nova atividade como um extra no Intent.
   - A nova atividade permite que o usuário insira um novo nome e, em seguida, retorna o novo nome para a atividade principal.
   - O resultado é recebido na atividade principal usando um contrato de Activity Result.

3. **Atualização Dinâmica do Nome**:
   - Quando a nova atividade retorna com o novo nome, a atividade principal atualiza dinamicamente o TextView para exibir a saudação "Olá" seguida pelo novo nome.

## EXECUTANDO O PROJETO
### INSTALANDO O APK:
   - **Download do APK**: Acesse a pasta `./APK/` e encontre o arquivo `NomeDoApp.apk`.
   - **Transferência para o dispositivo**: Transfira o arquivo APK para o seu dispositivo Android. Isso pode ser feito via cabo USB, Google Drive, email ou qualquer outro método de transferência de arquivos.
   - **Instalação**:
     1. No dispositivo Android, vá para `Configurações` > `Segurança` e habilite a opção `Fontes desconhecidas` (Isso permite a instalação de aplicativos fora da Google Play Store).
     2. Navegue até o local onde o APK foi salvo (usando um gerenciador de arquivos).
     3. Toque no arquivo `NomeDoApp.apk` para iniciar a instalação.
     4. Siga as instruções na tela para concluir a instalação.
   - **Execução**: Após a instalação, você pode abrir o aplicativo diretamente da tela de instalação ou encontrá-lo na gaveta de aplicativos do seu dispositivo.

### ANDROID STUDIO:
#### ABRINDO O PROJETO:
   - **Preparação do ambiente**:
     1. Certifique-se de que você tenha o [Android Studio](https://developer.android.com/studio) instalado em sua máquina.
     2. Instale as dependências necessárias (SDKs, emuladores, etc.) conforme indicado pela documentação do Android Studio.

   - **Abrindo o projeto no Android Studio**:
     1. Abra o Android Studio.
     2. Na tela de boas-vindas, selecione `Open an existing project`.
     3. Navegue até o diretório `./CODIGO` onde o projeto foi clonado e selecione-o.
     4. Aguarde enquanto o Android Studio indexa o projeto e baixa as dependências necessárias.

   - **Executando o projeto**:
     1. Conecte um dispositivo Android via USB ou configure um emulador de dispositivo Android no Android Studio.
     2. Certifique-se de que o dispositivo/emulador está selecionado na barra de dispositivos do Android Studio.
     3. Clique no botão `Run` (ícone de play) para compilar e executar o aplicativo.

   - **Depuração**:
     - Para iniciar a depuração, clique no botão `Debug` (ícone de inseto) e siga as instruções do Android Studio para definir pontos de interrupção e inspecionar variáveis.

#### GERANDO O APK:
   Depois de melhorar o projeto, você pode gerar o APK novamente. Siga os passos abaixo para gerar o APK usando o Android Studio:

   1. **Abrir o Projeto**:
      - Abra o Android Studio.
      - Vá para `File` > `Open...` e selecione o diretório `./CODIGO` do seu projeto.

   2. **Construir o Projeto**:
      - Certifique-se de que todas as dependências estejam atualizadas e que o projeto esteja compilando corretamente.
      - Vá para `Build` > `Clean Project` para limpar o projeto.
      - Depois, vá para `Build` > `Rebuild Project` para reconstruir o projeto.

   3. **Gerar o APK**:
      - Vá para `Build` > `Build Bundle(s) / APK(s)` > `Build APK(s)`.
      - O Android Studio começará a compilar o projeto e a gerar o APK.
      - Após a conclusão, uma notificação aparecerá no canto inferior direito da tela com a mensagem `APK(s) generated successfully.`
      - Clique na notificação ou vá para `locate` para encontrar o APK gerado, que geralmente está localizado em `./app/build/outputs/apk/release/`.

   4. **Testar o APK**:
      - Transfira o APK gerado para o seu dispositivo Android e instale-o conforme as instruções na seção **EXECUTANDO O PROJETO** > **APK** acima.

## CREDITOS:
- [PROJETO FEITO PELO VILHALVA](https://github.com/VILHALVA)
- [PROJETO CRIADO PARA O CURSO DE ANDROID STUDIO EM KOTLIN](https://github.com/VILHALVA/CURSO-DE-ANDROID-STUDIO-EM-KOTLIN)



