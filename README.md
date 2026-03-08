# Atividade – Sábado Letivo | Desenvolvimento Mobile com Flutter

## Descrição da atividade

Este repositório contém o projeto desenvolvido para a atividade de **Sábado Letivo da disciplina de Desenvolvimento Mobile**, utilizando o framework **Flutter**.

O objetivo da atividade foi configurar o ambiente de desenvolvimento Flutter, criar um projeto padrão e executar o aplicativo em diferentes plataformas, incluindo **emulador Android, navegador Web e dispositivo físico**.

Durante a atividade também foi realizado o versionamento do projeto utilizando **Git e GitHub**.

---

## Configuração do ambiente

Primeiramente foi necessário configurar o ambiente Flutter no computador.

Como eu já possuía o **Visual Studio Code** instalado, apenas adicionei as extensões necessárias para o desenvolvimento com Flutter:

- Flutter
- Dart

Depois disso foi feita a instalação do **Flutter SDK**.  
Após baixar o SDK, ele foi extraído em uma pasta do sistema e foi necessário configurar a variável de ambiente **PATH**, adicionando o caminho da pasta `flutter/bin`.  

Essa configuração permite que os comandos do Flutter possam ser executados diretamente no terminal.

Para verificar se todas as ferramentas estavam instaladas corretamente, foi utilizado o comando:

```bash
```

flutter doctor

Esse comando analisa o ambiente de desenvolvimento e mostra se existe algum problema na configuração das ferramentas necessárias.

Criação do projeto Flutter

Após configurar o ambiente, foi criado um projeto Flutter padrão utilizando o comando:

```
flutter create meu_app
```

Esse comando gera automaticamente toda a estrutura inicial de um aplicativo Flutter.

Em seguida o projeto foi aberto no Visual Studio Code para visualizar e trabalhar com os arquivos do aplicativo.

Estrutura do projeto

Durante a atividade também foi analisada a estrutura básica de um projeto Flutter.

Alguns dos principais arquivos e pastas são:

lib/

A pasta lib contém o código principal da aplicação em Dart.

main.dart

O arquivo main.dart é o ponto de entrada da aplicação Flutter.

Nele está presente a função:

```
void main() {
  runApp(const MyApp());
}
```

A função main() inicia a aplicação e o método runApp() executa o widget principal do aplicativo.

pubspec.yaml

O arquivo pubspec.yaml é responsável pela configuração do projeto.

Ele é utilizado para definir:

dependências do projeto

versão da aplicação

assets (como imagens e fontes)

Execução do aplicativo

Após a criação do projeto, o aplicativo foi executado em diferentes plataformas.

Execução no emulador Android

Primeiramente foi utilizado um emulador Android para rodar o aplicativo.

Para executar o projeto foi utilizado o comando:

```
flutter run
```

O Flutter compila automaticamente o aplicativo e instala no dispositivo ou emulador selecionado.

Execução na Web

O Flutter também permite executar aplicações na Web.

Para isso foi habilitado o suporte web e o projeto foi executado no navegador utilizando o comando:

```
flutter run -d chrome
```

O aplicativo foi aberto no navegador Google Chrome, onde também foi possível simular a visualização em um dispositivo móvel.

Execução em dispositivo físico

Também foi realizada a execução do aplicativo em um celular físico conectado ao computador via cabo USB.

Para isso foi necessário:

ativar o Modo Desenvolvedor no celular

habilitar a Depuração USB

Após isso o Flutter reconheceu o dispositivo e foi possível instalar e executar o aplicativo diretamente no celular.

Comandos utilizados durante a atividade

Alguns dos principais comandos utilizados foram:

```
flutter doctor
flutter --version
flutter devices
flutter create meu_app
flutter run
flutter run -d chrome
```

Esses comandos foram utilizados para verificar a instalação do Flutter, criar o projeto e executar o aplicativo nas diferentes plataformas.

Vídeo da atividade

No vídeo abaixo é apresentada a demonstração da configuração do ambiente, da estrutura do projeto e da execução do aplicativo nas diferentes plataformas.

Link do vídeo:
[https://drive.google.com/drive/folders/1F-VTNFqHqW3ugdsuBiSU9xHblv9_A7Q0?hl=pt-br](https://drive.google.com/drive/folders/1F-VTNFqHqW3ugdsuBiSU9xHblv9_A7Q0?usp=sharing)

Conclusão

A atividade permitiu compreender o processo inicial de configuração do ambiente Flutter, criação de um projeto padrão e execução da aplicação em diferentes dispositivos.

Essa prática foi importante para entender os conceitos básicos do desenvolvimento mobile utilizando Flutter e o funcionamento das ferramentas utilizadas no processo de desenvolvimento.
