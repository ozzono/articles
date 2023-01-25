# Crítica e comentário sobre validação técnica durante recrutamento

Nesse comentário vou tratar sobre as formas mais comuns de realizar a validação de conhecimento e habilidade técnica de programadores e desenvolvedores de software em geral.

## Conteúdo considerado nesse artigo

- Formas de validação técnica:
  - [Ferramentas online de avaliação técnica: hackerrank e outras](#hackerrank-e-assemelhados);
  - [Projeto completo compartilhado com repositório do Git](#projeto-completo-compartilhado-com-reposit%C3%B3rio-git);
  - [Codificação ao vivo (_live coding_) - programação em par (_pair programming_)](#codifica%C3%A7%C3%A3o-ao-vivo-live-coding)
  - [Entrevista Técnica](#entrevista-t%C3%A9cnica)
  - [Acrescentar código a projeto iniciado](#editar-código-a-projeto-iniciado)
- [Opinião](#opini%C3%A3o)
- [Aos recrutadores](#aos-recrutadores)

## HackerRank e assemelhados

São ferramentas de mercado que se dedicam em desenvolver testes de código a fim de aferir grau de conhecimento de diversas tecnologias, incluíndo as mais usadas na atualidade.  
Ferramentas como HackerRank são interessantes e tem seu espaço. Falham por aplicar uma limitação de tempo muito estrita, o que pode, inclusive, impedir que o candidato sequer entregue o trabalho, implicando na ausência de desempenho, o que é o pior dos casos para todos.
Recentemente tive contato com ferramenta dessa categoria que te permite concluir os testes dentro de 24h sendo que cada teste tem sua própria duração. Essa facilidade permite que se realize todos os testes com maior liberdade e evita a existência de testes que somem 120m contínuos, por exemplo.

|Prós|Contras|
|-|-|
|Os testes costumam rápidos;|Tem limitação estrita de tempo e alguns teste chegam a somar 180 minutos.|
|Inclui testes de banco de dados além de testes de código e de lógica;|O teste é limitado, tornando-o superficial e insuficiente;|
||O teste é realizado via web, o que é muito ruim;|
||Lenditão na entrega do resultado, a depender da plataforma.|

##### [[voltar para topo]](#conteúdo-considerado-nesse-artigo)

## Projeto completo compartilhado com repositório Git

Normalmente recebe o apelido de _desafio de código_ em que a equipe técnica detalha o que deve ser desenvolvido e, via de regra, compartilhado de volta usando ferramentas de versionamento de código como o  Github.  
Esse tipo de desafio tem enorme flexibilidade e dá margem para que se verifique o grau de conhecimento dos exatos tópicos de interesse. Entre as desvantagens desse tipo de avaliação temos o fato de que costumam ser lentos, demorando em média uma semana, o que não só pode desestimular o candidato como também pode potencialmente deixar a sensação de tempo desperdiçado. O esforço desse tipo de avaliação também pode gerar sobrecarga no volume de trabalho do candidato, especialmente se estiver em recrutamentos simultâneos.  
Considere também que o canditado pode já ter desenvolvido num desafio anterior algo parecido com o que será exigido nesse novo processo, ou seja, ele vai apenas reescrever e adaptar as partes necessárias para atender a descrição. Nesse caso vale a pena olhar o Github antes, tal como descrito [aqui](#avalia%C3%A7%C3%A3o-de-reposit%C3%B3rios-p%C3%BAblicos).

|Prós|Contras|
|-|-|
|Enorme flexibilidade;|Avaliação lenta;|
|Possibilidade de aferir com profundidade conhecimento tão somente dos tópicos de interesse;|Possível desestímulo em razão da demora;|
||Possível sensação de tempo desperdiçado ao final da avaliação;|
||Possível sobrecarga do candidato;|
||Possibilidade do candidato já ter feito algo semelhante antes e apenas repetir e adaptar.|

##### [[voltar para topo]](#conteúdo-considerado-nesse-artigo)

## Codificação ao vivo (live coding)

Modalidade de desafio em que o candidato é convidado a escrever código junto com seus avaliadores e à medida que é feito o teste o avaliador faz perguntas chave para aferir o grau de conhecimento do candidato além da sua fluência na tecnologia em questão.  
Entrevistas como essa costumam ser rápidas e seriam algo semelhante a uma mescla entre a [Entrevista Técnica](#entrevista-t%C3%A9cnica) e o [Projeto completo](#projeto-completo-compartilhado-com-reposit%C3%B3rio-git), feitas as ressalvas de complexidade e tempo do desafio.  
Cabe observar com cautela a forma como o avaliador se porta. Dada a situação é muito fácil que o candidato se sinta pressionado e acuado, problema que também pode ocorrer durante a [entrevista técnica](#entrevista-técnica).  
Trata-se de um momento para aferir conhecimento e não para fazer investigação policial por motivo de grave crime consumado.

|Prós|Contras|
|-|-|
|Entrevista relativamente curta|Dada a limitação de tempo torna-se difícil abordar aspectos técnicos avançados;
||Exige cautela para evitar demasiada pressão no candidato.|

##### [[voltar para topo]](#conteúdo-considerado-nesse-artigo)

## Entrevista Técnica

Entrevista direta com pessoa reconhecida pela empresa por ter mais experiência e conhecimento de tecnologia e desenvolvimento. Via de regra aborda as tecnologias e desafios que fazem parte do dia a dia da empresa.  
A entrevista técnica normalmente é realizada pelo chamado _tech lead_, profissional com mais tempo de carreira e com vivência nas tecnologias e problemas que fazem parte do negócio da empresa. Infelizmente essa entrevista é por demais subjetiva e não necessariamente reflete o verdadeiro grau de conhecimento e experiências do candidato, o que acaba por possibilitar uma contratação fadada ao fracasso e à frutração de todas as partes.  
Por sua vez, o entrevistador tem a oportunidade de abordar desafios que são impossíveis de contemplar em desafio de código, tais como concorrência, uso otimizado de recursos, segurança sob diversos aspectos entre tantos outros.

|Prós|Contras|
|-|-|
|Costuma ser rápida, durando em média 1h;|Depende da leitura subjetiva do _tech lead_.|
|Permite ao entrevistador questionar questões que via de regra não tem como ser abordados em desafios de código.||

##### [[voltar para topo]](#conteúdo-considerado-nesse-artigo)

## Editar código a projeto iniciado

Edição de código já iniciado e funcional, implementando alguma nova regra de negócio ou funcionalidade de acordo com a descrição do desafio.  
Nesse formato o candidato recebe um repositório já pronto e funcional e cabe a este implementar algo novo conforme solicitado. Esse tipo de desafio é o que mais se aproxima do dia a dia de desenvolvimento em que é preciso navegar por código já escrito por outra pessoa e, mais importante, entender o que está escrito e encontrar um caminho para implementar o que é pedido. Se bem elaborado haverá a necessidade de entender de diversas tecnologias e conceitos tais como git, banco de dados, testes automatizados ou REST bem como a compreensão de paradigmas de desenvolvimento como MVC ou talvez algum _design pattern_. Esse formato também seria um híbrido entre [ferramentas online de avaliação técnica](#hackerrank-e-assemelhados), dado que não é preciso construir um projeto do zero, e [desafio de código compartilhado](#projeto-completo-compartilhado-com-reposit%C3%B3rio-git), dado que está próximo do dia a dia da própria empresa que está recrutando. Abrange, portanto, vantagens das duas abordagens.

|Prós|Contras|
|-|-|
|Se a solicitação for razoável, o desafio é rapido, podendo durar 1h;||
|Possibilidade de avaliar importantes conhecimentos acessórios como git, banco de dados, REST, MVC, _design patterns_, testes automatizados;||
|Avalia capacidade de compreensão de código legado e de implementação de novas funciodalidades.||

##### [[voltar para topo]](#conteúdo-considerado-nesse-artigo)

## Avaliação de repositórios públicos

Acessar e avaliar repositórios públicos escritos e mantidos pelo candidato a fim de aferir sua abrangência de conhecimento.  
Nesse formato o candidato na verdade não faz nada, dado que supostamente já está tudo feito em projetos nos quais atuou no passado e que deixou público em seu perfil em plataformas como o Github. Cabe, portanto, a um _tech lead_ ler o código e validar se o candidato tem o conhecimento necessário.

|Prós|Contras|
|-|-|
|Avaliação sem demanda de esforço por parte do candidato;|Se o candidato  não expôs material usando tecnologia exigida pela equipe técnica, faz-se necessário realizar algum outro teste;|
|Avaliação rápida.||

##### [[voltar para topo]](#conteúdo-considerado-nesse-artigo)

## Opinião

Após já ter sido submetido a todos esses tipos de avaliação acredito que a melhor forma de aferir o conhecimento de um desenvolvedor de software consiste na soma de algum teste técnico seguido de entrevista técnica de modo que é possível avaliar tanto a fluência na linguagem em que se pretende trabalhar quanto a compreensão acerca dos desafios mais comuns ao se manter um serviço web de alta escala e demanda bem como permite fazer a revisão do código submetido a fim de compreender a forma como o candidato raciocina e resolve problemas. Pessoalmente eu escolheria a [edição de repositório com código legado](#edi%C3%A7%C3%A3o-de-reposit%C3%B3rio-j%C3%A1-desenvolvido) ou a [avaliação de repositórios públicos](#avalia%C3%A7%C3%A3o-de-reposit%C3%B3rios-p%C3%BAblicos) compartilhados e mantidos pelo candidato seguidos de entrevista técnica com um _techlead_ ou mais. A envio de [desafio de código com projeto](#projeto-completo-compartilhado-com-repositório-git) combinado com [entrevista técnica](#entrevista-técnica) com foco em comentar o código escrito e compartilhado também permite entender o quanto o candidato entender do código que escreveu e alternativas ao que foi apresentado.

##### [[voltar para topo]](#conteúdo-considerado-nesse-artigo)

## Aos recrutadores

Aos recrutadores e techleads que participam dos processos seletivos fica o convite para que, além de aplicar qualquer dos formatos de validação técnica, incluam também ao processo alguma devolutiva, o famoso _feedback_, nesse caso _feedback técnico_, a fim de que o candidato possa conhecer a própria falha e também se preparar melhor para as próximas oportunidades que surgirem. Esse feedback não precisa ser detalhado e completo; pode ser apenas um resumo ou mesmo as as notas feitas pelo entrevistador que o levou a concluir negativamente a respeito do candidato.
