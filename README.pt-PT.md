# README---Multilingual - Português (PT-PT)
Como Deixar o README.md em Múltiplas Línguas

### 📌 Sobre Este Projeto

Este é um modelo de README.md multilíngue para projetos no GitHub. Permite aos desenvolvedores disponibilizar documentação em vários idiomas de forma eficiente.

Na criação do meu primeiro projeto no GitHub, fui apresentado ao conceito do README.md, um arquivo importante que ilustra e descreve todo o projeto no GitHub. Ao produzir este documento, surgiu a dúvida de como disponibilizá-lo em diferentes línguas, já que estes projetos podem ser vistos por utilizadores de todo o mundo. Neste artigo, entenda como deixar a descrição dos seus projetos em várias línguas e por que isso é importante para torná-los mais acessíveis.

### 1. Criação de Ficheiros README Separados

A forma mais simples e direta de suportar múltiplas línguas é criar versões separadas do README.md para cada idioma. Cada ficheiro deve seguir a convenção README.lang.md, onde lang representa o código do idioma (ex: en para inglês, pt para português, es para espanhol). Por exemplo:

Crie ficheiros como README.[CÓDIGO-IDIOMA].md (ex: README.pt-PT.md, README.es-ES.md).

- README.md (padrão)
- README.pt-PT.md (português)
- README.es-ES.md (espanhol)

No README principal (geralmente em inglês), pode incluir links para as versões traduzidas:

# README em Diferentes Idiomas

(Choose your language below / Escolha o seu idioma abaixo / Elija su idioma abajo)
- [![English](https://img.shields.io/badge/Language-English-blue)](README.md)
- [![Português](https://img.shields.io/badge/Language-Português-green)](README.pt-PT.md)
- [![Español](https://img.shields.io/badge/Language-Español-red)](README.es-ES.md)
---

🌐 Como Usar READMEs Multilíngues -> Ficheiros Separados (Recomendado) -> ligue-os no README.md principal (ver exemplo acima).

### 2. Secções Multilíngues num Único README
   
Outra abordagem é manter todas as traduções num único ficheiro README.md. Pode organizar o conteúdo em secções, cada uma dedicada a um idioma específico. Isto é útil para projetos pequenos ou quando as traduções não são extensas.

## Abordagem em Único Ficheiro 

### English  
[English version of the README content]  

### Português  
[Versão em português do conteúdo do README]  

### Español  
[Versión en español del contenido del README]  .

---
### 3. Uso de GitHub Actions para Alternar Idiomas
Para uma solução avançada, pode usar GitHub Actions ou outros scripts automatizados para detetar o idioma preferido do visitante e mostrar o README correspondente. Isto requer a criação de um script que atualize o README.md principal consoante o idioma selecionado, embora seja uma opção mais complexa e menos comum.

### 4. Internacionalização (i18n) com Ferramentas Externas
Existem também ferramentas de i18n que ajudam a gerir e automatizar traduções de ficheiros de documentação, incluindo o README.md. Estas ferramentas podem ser integradas no seu fluxo de trabalho para simplificar a manutenção de várias versões do README em diferentes idiomas.

### Conclusão
Disponibilizar o README.md em múltiplos idiomas é um investimento que pode tornar o seu projeto mais inclusivo e acessível. Escolha a abordagem que melhor se adapta ao tamanho e às necessidades do seu projeto, garantindo que utilizadores de diferentes regiões possam interagir com ele de forma eficaz.
