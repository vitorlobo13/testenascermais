# Nascer+

## Visão Geral do Projeto

O **Nascer+** é um aplicativo móvel e web desenvolvido para auxiliar profissionais da área de obstetrícia no gerenciamento e acompanhamento de suas gestantes. O objetivo principal é simplificar o dia a dia desses profissionais, oferecendo ferramentas para cadastro de pacientes, acompanhamento de fichas de pré-natal, gestão financeira e cálculo da Data Provável do Parto (DPP).

Desenvolvido com foco na usabilidade e praticidade, o Nascer+ busca ser uma ferramenta essencial para otimizar o trabalho e garantir um acompanhamento mais eficiente e organizado das gestantes.

## Funcionalidades Principais

O aplicativo Nascer+ oferece as seguintes funcionalidades:

*   **Cadastro de Gestantes**: Registro completo de informações da gestante, incluindo nome, maternidade, classificação de risco, e foto de perfil.
*   **Cálculo de DPP**: Ferramenta integrada para calcular a Data Provável do Parto (DPP) com base na Data da Última Menstruação (DUM) ou ultrassonografia.
*   **Ficha de Acompanhamento (Checklist)**: Criação e gerenciamento de cartões e subtópicos para registrar o progresso do pré-natal, exames, consultas e outras informações relevantes. Cada item pode ser marcado como concluído.
*   **Edição de Gestantes**: Permite a atualização de todas as informações da gestante, incluindo a foto de perfil, a qualquer momento após o cadastro inicial.
*   **Gestão Financeira**: Controle de contratos e pagamentos, permitindo registrar o valor do contrato, pagamentos recebidos e visualizar o saldo devedor. Também indica contratos pendentes de entrega.
*   **Busca de Gestantes**: Funcionalidade de busca rápida para localizar gestantes pelo nome na lista principal.
*   **Persistência de Dados Local**: Armazenamento dos dados das gestantes localmente no dispositivo, garantindo acesso offline às informações.
*   **Multiplataforma**: Disponível como aplicativo Android (APK) e versão web para usuários de iPhone, garantindo ampla acessibilidade.

## Tecnologias Utilizadas

O Nascer+ é construído utilizando as seguintes tecnologias:

*   **Flutter**: Framework de UI do Google para a construção de aplicativos compilados nativamente para mobile, web e desktop a partir de um único código-fonte.
*   **Dart**: Linguagem de programação otimizada para UI, utilizada no desenvolvimento com Flutter.
*   **`shared_preferences`**: Pacote Flutter para persistência de dados simples, utilizado para armazenar as informações das gestantes localmente.
*   **`intl`**: Pacote para internacionalização e formatação de datas.
*   **`url_launcher`**: Pacote para abrir URLs externas, como clientes de e-mail.
*   **`image_picker`**: Pacote para selecionar imagens da galeria do dispositivo.

## Estrutura do Projeto

O projeto segue uma estrutura organizada, com as principais pastas e arquivos sendo:

nascermais-main/
├── lib/
│   ├── main.dart             # Ponto de entrada do aplicativo e navegação principal
│   ├── models/               # Definições dos modelos de dados (Gestante, Pagamento, etc.)
│   │   └── gestante.dart
│   └── screens/              # Telas da aplicação
│       ├── ajustes_screen.dart
│       ├── cadastro_screen.dart
│       ├── detalhes_pagamento_screen.dart
│       ├── detalhes_screen.dart
│       ├── editar_gestante_screen.dart # Nova tela de edição de gestantes
│       ├── financeiro_screen.dart
│       ├── home_screen.dart
│       └── subtopicos_screen.dart
├── pubspec.yaml            # Gerenciamento de dependências e metadados do projeto
├── README.md               # Este arquivo
└── web/                    # Arquivos da versão web do aplicativo

## Como Executar o Projeto

Para executar o projeto Nascer+ localmente, siga os passos abaixo:

### Pré-requisitos

*   [Flutter SDK](https://flutter.dev/docs/get-started/install ) instalado e configurado.
*   Um editor de código como [VS Code](https://code.visualstudio.com/ ) com a extensão Flutter, ou [Android Studio](https://developer.android.com/studio ).

### Passos

1.  **Clone o repositório:**
    ```bash
    git clone <URL_DO_SEU_REPOSITORIO>
    cd nascermais-main
    ```

2.  **Instale as dependências:**
    ```bash
    flutter pub get
    ```

3.  **Execute o aplicativo:**
    *   **Para Web:**
        ```bash
        flutter run -d chrome
        ```
        O aplicativo será aberto no seu navegador padrão.
    *   **Para Android:**
        Conecte um dispositivo Android ou inicie um emulador e execute:
        ```bash
        flutter run
        ```

## Contribuição

Contribuições são bem-vindas! Se você tiver sugestões de melhorias, relatar bugs ou quiser adicionar novas funcionalidades, sinta-se à vontade para abrir uma *issue* ou enviar um *pull request*.

## Licença

Este projeto está licenciado sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.

## Contato

Para dúvidas ou feedback, entre em contato com vitorlobo10@gmail.com.

---

**Desenvolvido com ❤️ para quem vive o nascer.**


