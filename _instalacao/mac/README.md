# SDS: Instalação das ferramentas no Mac

## ATENÇÃO:

**É MUITO IMPORTANTE que todos instalem as mesmas versões para evitar imprevistos durante a construção do projeto, e possibilitar que suas dúvidas sejam respondidas.**

## Ferramentas que você deverá instalar no seu computador Mac:

- JDK 17
- STS
- Postman
- Git

 ## Instalar o Homebrew
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
```
1. Update HomeBrew.
``` 
$ brew update 
```
2. Add the casks tap.
```
$ brew tap homebrew/cask-versions
```

## Java 17 no MacOS
```
$ brew tap AdoptOpenJDK/openjdk
$ brew install --cask adoptopenjdk17
```

- Verificar a instalação: 
```
$ java —version
```

## STS on MacOS 
```
$ brew cask install springtoolsuite
```

## postman 
```
$ brew cask install postman
```

## Git
```
$ brew install git
```

## postgresql 
```
$ brew install postgresql
```
- Se você for criar um banco de dados local, execute o seguinte comando para iniciar o servidor e fazer login nele (basicamente, ele configura um único usuário "admin" com seu nome de usuário com quem você fará o login) :
```
$ brew services start postgresql
```
- Para o servidor
```
brew services stop postgresql
```
- Terminal do Postgres (use ``` \q ``` para sair)
```
$ psql postgres
```

## pgadmin4 
```
$ brew cask install pgadmin4
```
