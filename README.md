# CamTech

App Android (Capacitor) com login por e-mail/senha e usuário master.

## Gerar o APK (sem instalar nada)
1. Crie um repositório no GitHub e envie esta pasta.
2. Aba **Actions** > **Build APK** > **Run workflow**.
3. Ao terminar, baixe o artefato **CamTech-apk** (app-debug.apk) e instale no celular.

## Gerar localmente
npm install && npx cap add android && npx cap sync android && cd android && ./gradlew assembleDebug
