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
