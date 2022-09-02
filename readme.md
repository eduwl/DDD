# Domain Driven Design

## Introdução

### O que ele é

- Ajudar a manutenabilidade e entendimento do codigo.
- Procurar entender o problema e a complexidade e trazer para código.
- Filosofia ideal para projetos muito complexos e que possuem tempo de desenvolvimento longo.
- Um mindset com filosofias e sistematicas para lidar com problemas do mundo real e trazer para o _Domain Model_.

### O que ele não é

- Contrutor de objeto para o dominio de negocio.
- Divisor de camadas para a aplicação.
- Contrutor de repositorios.

#

## Domain Experts

### Quem são

1. Pessoas ou grupo de pessoas que entendem do assunto (`Domain`).
2. Para cada `Domain` podera existir diferentes **Domain Experts**.
3. Entendem dos negócios e aspectos da empresa.

### Problema na equipe

- Gap de entendimento da equipe entre os assuntos do `Domain` e do `Domain Model`.
- Cada um no seu quadrado, desenvolvedores, domain experts e usuarios nao se converesam.
- Desenvolvedor com problemas de comunicação, o desenvolvedor deve estar em contato com os Domain Experts entender e desenvolver de acordo com o planejamento.
- Domain Experts com problemas de comunicação, o Domain Expert tambem deve estar em contato com o desenvolvedor para diminuir o Gap de entendimento do `Domain`
- Divergência de comunicação `Termos Técnicos`, `Equipe técnica fala uma coisa` e `Equipe de negócios fala outra`, se referindo ao problema (`Domain`).

#

### Exemplo de Divergência de comunicação no cenario imobiliário.

Domain Expert<p>

> Devemos cadastrar um novo `imóvel`.

Desenvolvedor<p>

> Devemos cadastrar uma nova `casa`.

#

## Obiquitous Language

### O que é

1. Prática de constuir uma comum e rigorosa linguagem entre desenvolvedores e usuarios.
2. Linguagem que é compartilhada por todos os envolvidos no projeto.
3. Vocabulário do `Domain`.
4. Usado em todas as formas **falar** e **escrever**.

### Como Definir

- Através de reuniões com os `Domains Experts`.
- Deve ser uma linguagem **natural** usando termos do `Domain`.
- Evite linguagens **artificiais** e termos fora do escopo do `Domain`.
- Deve ser **refinada** e adquirir **fluidez** ao longo do tempo.
- Documente os termos para deixar explicativo para todos inclusive novos integrantes.
- Continuamente o documento deve ser **atualziado**.
- Usado em todos os lugares.
  - Reuniões.
  - Documentações.
  - Código Fonte.

#

### Exemplo

<img src="./images/exemplo.png" alt="Imagem de Exemplo" style="float: center;">