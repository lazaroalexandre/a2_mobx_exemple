# a2_mobx_exemple

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.



# Mobx

    Gerenciamento de estado que simplifica a reatividade de dados para as interfaces dos usuários


# Estrutura

    # Observable:
        
        Qualquer dado que pode ser alterado (variáveis que terão interação)


    # Computed:

        Sincronia entre observables (Resposta diferente de acordo com o resultado da ação dos observables)


    # Actions:

        Mudança de estado (método que interagirá com os observables)


    # Reactions:

        Respostas das actions (evento)


# Bibliotecas

    mobx
    flutter_mobx
    build_runner
    mobx_codegen


# Execução no Terminal

    # Rodar o Build Runner:

        flutter pub run build_runner watch

    
    # Rodar o Flutter:

        flutter run -d chrome