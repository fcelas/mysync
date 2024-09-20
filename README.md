# MySync

MySync é um aplicativo de transporte inspirado no Uber, desenvolvido com Flutter.

## Características

- Tela de login
- Mapa interativo usando Google Maps
- Barra de pesquisa para destinos
- Painel deslizante com informações da viagem

## Pré-requisitos

- Flutter (versão 2.x ou superior)
- Dart (versão 2.x ou superior)
- Android Studio ou VS Code

## Configuração

1. Clone o repositório:
   ```
   git clone https://github.com/seu-usuario/mysync.git
   ```

2. Navegue até o diretório do projeto:
   ```
   cd mysync
   ```

3. Instale as dependências:
   ```
   flutter pub get
   ```

4. Configure sua chave de API do Google Maps:
   - Android: Adicione sua chave no arquivo `android/app/src/main/AndroidManifest.xml`
   - iOS: Adicione sua chave no arquivo `ios/Runner/AppDelegate.swift`

5. Execute o aplicativo:
   ```
   flutter run
   ```

## Construindo o APK

Para construir o APK de release, execute:

```
flutter build apk --release
```

O APK será gerado em `build/app/outputs/flutter-apk/app-release.apk`.

