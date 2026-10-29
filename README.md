# CAPA LAB Android

Aplicativo Android para gerar configurações de sensibilidade do Free Fire, com interface offline dentro de WebView.

## Gerar APK
1. Abra a aba **Actions** deste repositório.
2. Selecione **Build CAPA LAB APK** e clique em **Run workflow**.
3. Aguarde a execução terminar.
4. Na execução, baixe o artefacto **CapaLab-debug-apk**.
5. Extraia o ZIP e instale `app-debug.apk` no Android.

O workflow também executa automaticamente quando há um push na branch `main`.

## Build local
Requer Java 17 e Android SDK API 35. Execute `gradle assembleDebug` na pasta do projeto.

**Aviso:** APK de debug para testes, não assinado para publicação na Play Store. As sensibilidades são sugestões de partida; não garantem capa. O app não modifica o jogo, não injeta código e não altera o DPI do aparelho.