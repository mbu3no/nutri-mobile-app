# NutriApp

Aplicativo mobile desenvolvido com Expo e React Native para cálculo de macronutrientes e necessidades diárias com base em dados físicos do usuário.

O app foi criado como projeto prático vinculado à UNIFEI (Universidade Federal de Itajubá), com foco em nutrição aplicada. A partir do peso, altura e idade, calcula uma estimativa de proteína diária, consumo de água e gasto calórico basal.

## Funcionalidades

- Tela inicial com acesso rápido ao WhatsApp para agendamento de consulta e localização da clínica no Google Maps
- Formulário de entrada com validação dos campos numéricos
- Cálculo automático de proteína, hidratação e calorias com base na fórmula de Mifflin-St Jeor
- Navegação fluida entre telas com Expo Router

## Tecnologias

- Expo 53
- React Native 0.79
- React 19
- Expo Router 5
- TypeScript

## Como rodar o projeto

Instale as dependências:

```bash
npm install
```

Inicie o servidor de desenvolvimento:

```bash
npx expo start
```

No terminal aparecerão as opções para abrir o app no emulador Android, simulador iOS ou pelo aplicativo Expo Go no seu celular.

Para rodar diretamente em uma plataforma específica:

```bash
# Android
npm run android

# iOS
npm run ios

# Web
npm run web
```
