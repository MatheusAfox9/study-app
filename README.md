#Arquitetura de Pastas:

node_modules/: Contém todas as dependências do projeto, ou seja, as bibliotecas do projeto.
package.json: O arquivo de configuração principal do projeto. Ele lista todas as dependências do projeto.
app.json: Configuração do React Native que define detalhes sobre o aplicativo, o pai.
assets/: Armazenar recursos gráficos (imagens, ícones), que são importados nas telas ou componentes.
Pasta src/: A pasta src/ geralmente contém todo o código-fonte do aplicativo.
contexts/: fica dentro da pasta src/ é utilizada para armazenar o gerenciamento de estado global com Context, contexto para o gerenciamento dos dados do aplicativo. (como os cartões de estudo).
screens/: fica dentro da pasta src/ são os arquivos das telas do aplicativo. (como o EdicaoCartaoScreen).

#Objetivos dos arquivos




#Blibliotecas

async-storage (Banco de dados local)

Provider - Provedor do estado local, os cartões ficarem gravados

Picker - abertura de Calendário 
