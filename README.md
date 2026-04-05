--> Navigation - Estudo de Navegação com Jetpack Compose

Projeto desenvolvido para aprender e praticar a navegação entre telas em aplicativos Android utilizando **Jetpack Compose** e o componente **Navigation Compose** do Jetpack.


--> Descrição

Este aplicativo simula um fluxo simples de navegação semelhante ao que encontramos em apps reais: o usuário faz login, acessa um menu principal e pode navegar para diferentes seções — como 'Perfil' e 'Pedidos', e retornar ao menu a qualquer momento.

O objetivo não é criar um app funcional completo, mas sim entender na prática como o 'NavController' e o 'NavHost' funcionam, como definir rotas e como passar a navegação entre composables



--> Fluxo de navegação

Login → Menu → Pedidos
               ↕
             Perfil


O usuário inicia na tela de **Login**, avança para o **Menu** e pode navegar livremente entre **Pedidos** e **Perfil**. A opção "Sair" no menu retorna à tela de Login.



--> Tecnologias utilizadas

- **Kotlin** — linguagem principal do projeto
- **Jetpack Compose** — construção de UI de forma declarativa
- **Navigation Compose** (`androidx.navigation:navigation-compose:2.6.0`) — gerenciamento de navegação entre composables
- **Material 3** — componentes visuais modernos
- **Android SDK 36** / mínimo SDK 24 (Android 7.0+)



--> O que aprendi

- Como configurar um `NavHost` com `rememberNavController()`
- Como definir rotas com `composable(route = "...")`
- Como usar `navController.navigate()` para ir a outra tela
- Como usar `navController.popBackStack()` para voltar
- Como passar o `NavController` como parâmetro para os composables
- Como estruturar um projeto Compose com múltiplas telas em pacotes separados



--> Estrutura do projeto


app/src/main/java/ruyfichman/com/github/navigation/
├── MainActivity.kt          # Ponto de entrada, define o NavHost e as rotas
└── screens/
    ├── LoginScreen.kt       # Tela de login
    ├── MenuScreen.kt        # Menu principal
    ├── PedidosScreen.kt     # Tela de pedidos
    └── PerfilScreen.kt      # Tela de perfil




--> Como executar

1. Clone o repositório
2. Abra no **Android Studio**
3. Aguarde a sincronização do Gradle
4. Execute em um emulador ou dispositivo com Android 7.0 ou superior



--> Autor

Ruy Fichman — projeto de estudo de navegação com Compose



<img width="262" height="579" alt="image" src="https://github.com/user-attachments/assets/f7d47073-f1e3-46c4-9abb-4816626be448" />
<img width="263" height="580" alt="image2" src="https://github.com/user-attachments/assets/c8c90d93-b7ae-409b-bc38-6581bec1c7ce" />
<img width="255" height="590" alt="image3" src="https://github.com/user-attachments/assets/379aaca1-9bba-4085-abca-fca2ef2fb690" />
<img width="264" height="586" alt="image4" src="https://github.com/user-attachments/assets/a565f003-dc0b-4a68-8bb7-980d0aa14065" />


