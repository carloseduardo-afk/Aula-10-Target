# 🎯 Target - App de Metas Financeiras

Este repositório contém o desenvolvimento do projeto **Target**, um aplicativo para gestão de metas financeiras pessoais. O projeto foi construído seguindo um guia didático focado em **React Native**, **Expo Router** e **TypeScript**.

## 📂 Estrutura do Projeto

Com base na arquitetura implementada, o projeto está organizado da seguinte forma:

* **`src/app`**: Contém as rotas e telas do aplicativo.
    * `index.tsx`: Tela principal (Dashboard).
    * `target.tsx`: Tela para criação de novas metas.
    * `in-progress/[id].tsx`: Rota dinâmica para detalhes de uma meta específica.
    * `transaction/[id].tsx`: Rota dinâmica para registro de transações (guardar/resgatar).
    * `_layout.tsx`: Configuração global de navegação e carregamento de fontes.
* **`src/theme`**: Centralização da identidade visual.
    * `colors.ts`: Tokens de cores com diferentes intensidades.
    * `fontFamily.ts`: Configuração da tipografia (Inter).
* **`assets`**: Ícones adaptativos para Android e iOS e imagens do sistema.

## 🛠️ Tecnologias e Conceitos Aplicados

* **Expo Router**: Navegação baseada em arquivos e rotas dinâmicas.
* **TypeScript**: Tipagem estática para maior segurança no desenvolvimento.
* **Design Tokens**: Padronização de estilos para evitar repetição de código.
* **Path Mapping**: Uso de `@/` para facilitar as importações dentro da pasta `src`.

## 🚀 Como rodar o projeto

1.  Certifique-se de ter o **Node.js** instalado.
2.  Instale as dependências:
    ```bash
    npm install
    ```
3.  Inicie o servidor do Expo:
    ```bash
    npx expo start
    ```
4.  Escaneie o QR Code com o app **Expo Go** no celular ou use um emulador Android/iOS.

---
**Projeto desenvolvido como atividade acadêmica para a disciplina de Sistemas Móveis.**
