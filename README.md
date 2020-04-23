# Windows

1. Faca o download da ultima versao do Flutter estavel [aqui](https://storage.googleapis.com/flutter_infra/releases/stable/windows/flutter_windows_v1.2.1-stable.zip "aqui");
2. Extraia o conteúdo .zip para alguma pasta, ela será o caminho da SDK, escolha com cuidado;

# Atualizando o PATH (Windows)

Abra o menu iniciar e comece a pesquisar por "variáveis de ambiente", assim que encontrar, edite o `PATH` e adicione o caminho completo do `flutter/bin` dentro.

Apos isso, voce ja podera executar os comandos do Flutter! Teste digitando esse:

`$ flutter doctor -v`

# Criando e executando seu primeiro projeto

Para criar e testar seus primeiros apps, execute esses comandos:

1. Crie seu primeiro projeto executando essa linha de comando no terminal: 

	`$  flutter create meu_app`

2. Um diretório `meu_app` foi criado, contendo o aplicativo inicial do Flutter. Entre neste diretório: 

	`$  cd meu_app`

3. Para iniciar o aplicativo no Simulador, assegure-se de que o Simulador esteja em execução e execute no terminal:

	`$ flutter run`

[Configurando Android Studio](https://github.com/engapplabs/setup-windows/blob/master/android-studio-setup.md  "Configurando Android Studio")

[Configurando o VSCode](https://github.com/engapplabs/setup-windows/blob/master/visual-studio-ide.md "Configurando VSCode")
