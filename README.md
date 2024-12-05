**Arquitetura das Pastas**

/assets
Contém os recursos estáticos do aplicativo, como ícones e imagens: Android/iOS.

logo.png: Logo do aplicativo.
/src
O diretório principal do código-fonte do projeto.

/config
firebaseConfig.js: Configuração do Firebase para autenticação e armazenamento de dados.
/contexts
Armazena os contextos do React para gerenciar o estado global:

AuthContext.js: Gerencia o estado de autenticação do usuário (login, logout, etc.).
CartoesEstudoContext.js: Gerencia o estado relacionado aos cartões de estudo (carregamento, adição, edição e exclusão).
/screens
Contém as telas do aplicativo:

EdicaoCartaoScreen.js: Tela para editar os cartões de estudo.
ListaCartaoScreen.js: Tela que exibe a lista de cartões de estudo.
LoginScreen.js: Tela de login do aplicativo.
RegistroScreen.js: Tela para registro de novos usuários.
TarefasVencimentoProximoScreen.js: Tela que exibe tarefas com vencimento próximo.

**Evidencias study_app**

![image](https://github.com/user-attachments/assets/f21087f6-895c-4599-9aba-29b02ca8ed88)
![image](https://github.com/user-attachments/assets/df4fae70-6b0d-4e62-9405-278fc3d1b586)
![image](https://github.com/user-attachments/assets/5a6024b9-090e-4723-8009-7469324f8908)

**Bibliotecas Utilizadas**

Bibliotecas Principais
react-native: Framework para desenvolvimento de aplicativos móveis nativos.
expo: Framework que simplifica o desenvolvimento de aplicativos React Native.
Navegação
@react-navigation/native e @react-navigation/stack: Gerenciam a navegação entre telas do aplicativo.
@react-navigation/native-stack: Navegação otimizada para maior desempenho.
Gerenciamento de Estado
@react-native-async-storage/async-storage: Armazena dados localmente no dispositivo.
Integrações e Funcionalidades
firebase: Integração com o Firebase para autenticação e banco de dados.
expo-local-authentication: Implementa autenticação local (como biometria).
react-native-dotenv: Permite o uso de variáveis de ambiente.
react-native-modal-datetime-picker: Permite selecionar datas e horários em modais.
Interface de Usuário
react-native-vector-icons: Biblioteca de ícones vetoriais.
react-native-safe-area-context e react-native-screens: Gerenciam áreas seguras e transições de tela.
react-native-web: Permite rodar aplicativos React Native no navegador.


