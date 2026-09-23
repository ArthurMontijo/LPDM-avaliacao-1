# LPDM-avaliacao-1

## Cartão de Perfil Profissional

Aplicativo Android desenvolvido em **Kotlin** utilizando **Jetpack Compose**.
O projeto apresenta um cartão de perfil profissional em uma única tela, contendo foto, apresentação, nome, profissão e informações de contato.

## Tecnologias utilizadas

- Kotlin
- Android Studio
- Jetpack Compose
- Material Design
- Material Icons

## Funcionalidades

O aplicativo apresenta:

* Imagem de perfil no topo da tela;
* Mensagem de boas-vindas;
* Nome completo: Arthur Vieira Montijo;
* Profissão: Estudante de Informática;
* Descrição sobre o perfil;
* Telefone para contato;
* E-mail;
* Rede social;
* Ícones do Material Design;
* Fundo na cor cinza claro.

## Estrutura do projeto

A principal tela do aplicativo está localizada em:

```text
app
└── java
    └── com.example.lpdmavaliacao1
        └── MainActivity.kt
```

O tema do aplicativo está localizado em:

```text
app
└── java
    └── com.example.lpdmavaliacao1
        └── ui
            └── theme
                └── Theme.kt
```

A imagem utilizada no cartão está localizada em:

```text
app
└── src
    └── main
        └── res
            └── drawable
                └── pngwing_com__1_.png
```

## Composables utilizados

### CartaoPerfil

É o principal Composable do aplicativo.
Responsável por montar o cartão de perfil utilizando:

* Column
* Row
* Box
* Image
* Text
* Spacer
* Icon

### Contato

É um Composable reutilizável criado para apresentar cada informação de contato com seu respectivo ícone.

São utilizados três contatos:

* Telefone
* E-mail
* Rede social

## Recursos do Jetpack Compose utilizados

O projeto utiliza alguns recursos importantes do Jetpack Compose:

* `Column` para organizar os elementos verticalmente;
* `Row` para organizar os contatos horizontalmente;
* `Box` para posicionar a imagem;
* `Modifier` para tamanho, espaçamento e fundo;
* `painterResource()` para carregar a imagem;
* `Icons.Default` para os ícones de contato;
* `Text` para apresentar as informações.

## Como executar o projeto

1. Abra o projeto no **Android Studio**.
2. Aguarde o carregamento e a sincronização do Gradle.
3. Conecte um celular Android ou utilize um emulador.
4. Clique no botão **Run ▶**.
5. Escolha o dispositivo para executar o aplicativo.

## Requisitos da avaliação

O projeto foi desenvolvido seguindo os requisitos da atividade:

* Kotlin;
* Jetpack Compose;
* Uma única tela;
* Uso de `Column`, `Row` e `Box`;
* Uso de função Composable própria;
* Uso de `Modifier`;
* Imagem utilizando `painterResource()`;
* Ícones utilizando Material Icons;
* Fundo diferente da cor branca;
* Informações profissionais e de contato.

## Autor

**Arthur Vieira Montijo**

### Curso

**LABORATÓRIO DE PROGRAMAÇÃO PARA DISPOSITIVOS MÓVEIS (LPDM)**

### Módulo

**3º Módulo**

### Professor

**MSc Rodrigo de Lima Cunha**

## Repositório

Nome do repositório:

`LPDM-avaliacao-1`
