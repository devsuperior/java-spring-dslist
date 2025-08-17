# SDS: Instalação das ferramentas no Linux (Ubuntu/Debian)

## ATENÇÃO:

**É MUITO IMPORTANTE que todos instalem as mesmas versões para evitar imprevistos durante a construção do projeto, e aumentar as chances de que suas dúvidas sejam respondidas.**

## Ferramentas que você deverá instalar no seu computador Linux:

- Curl
- Git
- Java JDK 17
- Maven
- STS
- Postman
- Docker
- Postgresql
- pgAdmin

## Playlist mostrando a instalação:

https://www.youtube.com/playlist?list=PLNuUvBZGBA8mcAF-YX7RJhA26TBLdG5yk

## Curl

- Instalar o curl
```
sudo apt-get install -y curl
```
- Conferir a instalação: 
```
curl
```

## Git

- Instalar: 
```
sudo apt-get install -y git
```

- Conferir a instalação: 
```
git
```

## Java JDK 17

- Instalar Java: 
```
sudo apt install openjdk-17-jdk
```

- Verificar a instalação: 
```
java -version
```
- Configurar JAVA_HOME:
  - Verificar caminho Java: 
  ```
  sudo update-alternatives --config java
  ```
  - Edite o arquivo .bashrc: 
  ```
  sudo gedit ~/.bashrc
  ```
  - Copie o código abaixo no final do arquivo (observe a versão do seu JDK). Salve o arquivo.
  ```
  JAVA_HOME=/usr/lib/jvm/java-17-openjdk-amd64
  export JAVA_HOME
  export PATH=$PATH:$JAVA_HOME
  ```
  - Abra um novo terminal e teste: 
  ```
  echo $JAVA_HOME
  ```


## Maven

- Instalar Maven: 
```
sudo apt-get install maven
```
- Verificar a instalação: 
```
mvn -v
```

## STS

- Google: STS
- Baixar
- Descompactar (exemplo: /home/user/apps)
- Iniciar STS
  - Selecione um workspace (exemplo: /home/user/Workspaces/ws-sts)
- Liberar permissão na pasta do workspace: 
```
sudo chmod -R ugo+rw /home/user/Workspaces/ws-sts
```

## Postman

- Instalar com snap: 
```
snap install postman
```
## Docker
```
https://docs.docker.com/engine/install/ubuntu/
```

## Postgresql

```
https://www.postgresql.org/download/linux/ubuntu/
```

## pgAdmin

```
https://www.pgadmin.org/download/pgadmin-4-apt/
```
