# ModTemplate

Template de mod para **Minecraft 1.20.1** com **Minecraft Forge 47.4.28**.

## Requisitos

- JDK 17 instalado e selecionado como `JAVA_HOME`.
- Acesso à internet na primeira execução do Gradle Wrapper.

## Desenvolvimento

No Linux/macOS:

```sh
./gradlew runClient
```

No Windows:

```bat
gradlew.bat runClient
```

O exemplo registra um bloco, um item de comida, uma aba criativa e uma configuração comum.

## Gerar o mod

```sh
./gradlew build
```

O JAR será gerado em `build/libs/`.

Antes de publicar, personalize `mod_id`, `mod_name`, `mod_authors` e `mod_group_id` em `gradle.properties`.