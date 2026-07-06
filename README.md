# Mudar referência de url no — SGEBD_APP

## 1. Local

Em `../app/src/main/java/com/example/sgebd/MainActivity.kt` alterar a variável `SITE_URL`:


# Modo publicar em dev

## 1.1. Opção A: Gerar com o Android Studio

No menu `Build -> Generate App Bundle(s) / APK(s) -> Build APK(s)`. Executar e aguardar.

## 1.2. Opção B: Gerar via Linha de Comando (CMD / Terminal)

Abra o terminal na pasta raiz do projeto e execute o comando correspondente:

* **Para gerar APK de Desenvolvimento (Debug):**
  ```bash
  gradlew assembleDebug

## 2. Usuários de Seed (desenvolvimento)

O arquivo que estará em `app/build/outputs/apk/debug` com o nome `app-debug.apk`;
