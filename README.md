# IPTV Client Manager

Gerenciador de clientes IPTV (React Native + Expo)

Este projeto é um painel completo para gerenciar clientes de IPTV, com cadastro, filtros, buscas, vencimentos, notificações locais e muito mais. Baseado em React Native, Expo, Context API e AsyncStorage.

---

## 🚀 Como rodar o projeto

1. **Clone o repositório:**
   ```sh
   git clone https://github.com/welfalcao/IPTV-Maneger-.git
   cd IPTV-Maneger-
   ```

2. **Instale as dependências:**
   ```sh
   pnpm install   # ou npm install
   ```

3. **Rode o app no Expo:**
   ```sh
   pnpm dev       # ou npm start, ou npx expo start
   ```

4. **Abra no seu celular:**
   - Instale o app [Expo Go](https://expo.dev/go) no Android/iOS
   - Escaneie o QR code que aparece no terminal/aplicação web

---

## 📦 Como gerar um APK para Android

### O jeito mais moderno (Expo EAS Build)

1. **Instale o EAS CLI (se necessário):**
   ```sh
   npm install -g eas-cli
   ```

2. **Faça login na sua conta Expo:**
   ```sh
   npx expo login
   # Ou
   eas login
   ```

3. **Configure o projeto para EAS Build:**
   ```sh
   npx eas build:configure
   ```

4. **Gere o APK:**
   ```sh
   npx eas build -p android --profile preview
   ```
   Quando terminar, será exibido um link para baixar o APK pronto!

- Para builds em modo release/pronto para Play Store, use:
  ```sh
  npx eas build -p android --profile production
  ```

### Build legacy (Expo Classic)
_Com Expo SDK <= 48_
- Rode:
  ```sh
  npx expo build:android -t apk
  ```
  *(Pode pedir para migrar para EAS Build, que é recomendado)*

---

## ☑️ Requisitos para build EXPO
- Node.js (18+ recomendado)
- Conta no [Expo](https://expo.dev/)
- Instale o EAS CLI (veja acima)
- Android Studio é **opcional** (roda tudo em nuvem)

---

## 📝 Dicas
- Para testar notificações, simule um cliente com data de vencimento próxima.
- O projeto usa fontes Inter do Google Fonts (Expo).
- Se der erro em build, me mande a mensagem aqui para que eu te ajude!

---

## 📂 Estrutura de pastas sugerida
```
.
├── app/
├── assets/
├── components/
├── context/
├── hooks/
├── screens/
├── services/
├── constants/
├── package.json
├── app.json
├── README.md
└── ...
```

---

## 📢 Precisa de mais ajuda?
Me envie mensagens com prints ou logs de erro – posso te ajudar a resolver qualquer etapa do build, publicação ou melhorias do projeto!

---
