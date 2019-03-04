# Windows

1. Faca o download da ultima versao do Flutter estavel [aqui](https://storage.googleapis.com/flutter_infra/releases/stable/windows/flutter_windows_v1.2.1-stable.zip "aqui");
2. Extraia o conteúdo .zip para alguma pasta, ela será o caminho da SDK, escolha com cuidado;
3. Localize o arquivo ***flutter_console.bat*** dentro da pasta raiz da SDK e execute-o com dois cliques.

# Atualizando o PATH (Windows)

Abra o menu iniciar e comece a pesquisar por "variáveis de ambiente", assim que encontrar, edite o `PATH` e adicione o caminho completo do `flutter/bin` dentro.

Apos isso, voce ja podera executar os comandos do Flutter! Teste digitando esse:

`$ flutter doctor -v`

# Android Studio (Windows)
1. Baixe e instale o [Android Studio](https://developer.android.com/studio "Android Studio");
2. Inicie o Android Studio e termine o guia de instalação. Será instalado tudo o que você necessita para começar a desenvolver em Android usando o Flutter (Android SDK, Android SDK Platform-Tools, Android SDK Build-Tools)

# Mobile (Android/Windows)

Para se preparar para executar e testar seu app Flutter em um dispositivo Android, você precisará de um dispositivo Android com o Android 4.1 (nível de API 16) ou superior

1. Ative as opções do desenvolvedor e a depuração USB no seu dispositivo. Instruções detalhadas estão disponíveis na [documentação do Android](https://developer.android.com/studio/debug/dev-options "documentação do Android").

2. Windows: instale o [Google USB Driver](https://developer.android.com/studio/run/win-usb "Google USB Driver")

3. Usando um cabo USB, conecte o telefone ao computador. Se solicitado em seu dispositivo, autorize seu computador a acessar seu dispositivo.

4. No terminal, execute o comando` flutter devices` para verificar se o Flutter reconhece seu dispositivo Android conectado.

Por padrão, o Flutter usa a versão do Android SDK em que sua ferramenta `adb` se baseia. Se você quiser que o Flutter use uma instalação diferente do Android SDK, deverá definir a variável de ambiente `ANDROID_HOME` para esse diretório de instalação.

# Emulador (Android/Windows)

Para se preparar para executar e testar seu aplicativo Flutter no emulador do Android, siga estas etapas:

1. Ative a [VM Acceleration](https://developer.android.com/studio/run/emulator-acceleration "VM Acceleration") em sua máquina.

2. Inicie o **Android Studio> Ferramentas> Android> AVD Manager** e selecione **Criar dispositivo virtual**. (O submenu **Android** só está presente quando dentro de um projeto Android.)

3. Escolha uma definição de dispositivo e selecione **Avançar**.

4. Selecione uma ou mais imagens do sistema para as versões do Android que você deseja emular e selecione **Avançar**. Uma imagem x86 ou x86_64 é recomendada.

5. Em Desempenho emulador, selecione **Hardware - GLES 2.0** para ativar a aceleração de hardware.

6. Verifique se a configuração do AVD está correta e selecione **Concluir**.

	Para detalhes sobre as etapas acima, consulte [Gerenciando AVDs](https://developer.android.com/studio/run/managing-avds "Gerenciando AVDs").

7. No Android Virtual Device Manager, clique em **Executar** na barra de ferramentas. O emulador é iniciado e exibe a tela padrão para sua versão do sistema operacional e dispositivo selecionados.

Após isso, basta configurar uma IDE, nos da EngApp recomendamos o uso do VSCode da Microsoft, por ser uma IDE mais leve, visualmente bonita para nos, leve e agradável
