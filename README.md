# Entendendo Maven seus comandos e uso.

## Comando para pegar um template de projeto no repositório

> mvn archetype:generate -DgroupId=one.digitalinnovation -DartifactId=quick-start-maven -Darchetype=maven-archetype-quickstart -DinteractiveMode=false

## Comandos

***nvm compile***

serve para compilar todas as classes da aplicação adiciona uma pastar target e coloca todos os asquivos compilados lá

***nvm test***

Encontra as classes de test e executa os tests dentro de cada pasta

***nvm package***

Empacota o projeto e cria o arquivo .jar que vai ser publicado

***nvm clean***

Limpa a pasta target limpando diretório de trabalho

## Manven archetype

Arquetipos são usados para definir template com configurações pré existentes de cenários já estabelecidos e projetos. Usar um archetype de terceiros pode ter seus proprios comando e instruções para funcionar.

> https://maven.apache.org/archetypes/

Exemplo

Maven Plugin Site Archetype
maven-archetype-plugin-site is an archetype which generates a sample Maven plugin's site:

´´mvn archetype:generate -DarchetypeGroupId=org.apache.maven.archetypes -DarchetypeArtifactId=maven-archetype-plugin-site -DarchetypeVersion=1.4´´


## pom.xml

Arquivo usado para executar o projeto ele possui atributos:

* Nome do projeto
* Dependências
* Módulos
* Configurações de build
* Detalhes do projeto ( nome, descrição, licença, url)
* Configurações de ambiente (repositórios, tracking, profiles)
