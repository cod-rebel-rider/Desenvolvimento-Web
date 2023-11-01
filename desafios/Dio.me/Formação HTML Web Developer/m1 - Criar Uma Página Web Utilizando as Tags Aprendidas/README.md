# Criar Uma Página Web Utilizando as Tags Aprendidas

## O que deve ser feito?

A ideia deste Desafio de Projeto é elaborar um website, utilizando uma estrutura bem básica, utilizando tags aprendidas durante as aulas práticas:

## Requisitos

* Utilizar todas as tags explicadas nas aulas: `<h1>` até `<h6>`, `<p>`, `<mark>`, `<small>`, `<i>`, `<u>`, `<strong>`, `<ol>`, `<ul>`, `<li>`, `<a>`, `<hr>`, `<sub>`, `<sup>`, `<blockquote>`;
* Utilizar novas tags sugeridas: `<font>`, `<del>`, `<p>`, `<abbr>` (a ideia é buscar estas tags na internet, entender como ela funciona e utilizar no texto).

## Explicando Meu Código

Primeiro defini o início de um documento HTML e inclui a seção `<head>`, que é usada para conter informações sobre o documento, como o título da página.

```
<!DOCTYPE html>
<head>
</head>
```

Dentro do `<body>`, tem dois cabeçalhos `<h1>` e `<h2>` que são usados para introduzir o nome e a descrição do perfil profissional.

```
<body>
    <h1>Olá 👋, sou Matheus</h1>
    <h2>Profissional de DevSecOps apaixonado por desenvolvimento web e cibersegurança</h2>
```

Aqui começa a seção de perfil profissional. Você usa um cabeçalho `<h3>` para indicar o início desta seção e, em seguida, usa as tags `<strong>` para destacar informações importantes, como seu nome e um link para seu perfil no LinkedIn usando a tag `<a>`.

```
    <h3>Perfil Profissional</h3>
    
    <strong>Nome:</strong> Matheus Rodrigues
    <br>
    <strong>LinkedIn:</strong> <a href="https://www.linkedin.com/in/matheusrsilverkin/">In/MatheusRSilverkin</a>
```

Na seção de resumo, usei um cabeçalho `<h3>` e um parágrafo `<p>` para descrever a paixão por DevSecOps e as habilidades em automação e segurança cibernética. Também usa as tags `<mark>`, `<u>`, e <sub> para destacar e formatar o texto de maneira apropriada.

```
    <h3> Resumo </h3>
    
    <p>Sou um profissional de <mark>DevSecOps</mark> apaixonado por web e cibersegurança. Tenho experiência em <u>automação e segurança cibernética</u>, e estou constantemente buscando aprimorar minhas habilidades. Atualmente, estou trabalhando em projetos relacionados a infraestrutura como código <sub>(IaC)</sub> e desenvolvimento web.</p>
```

A tag `<hr>` é usada para criar uma linha horizontal que divide as seções do conteúdo.

```
    <hr>
```

Nesta seção, começo a listar das experiências profissionais, começando com um cabeçalho `<h4>` e uma lista ordenada `<ol>`. Cada item da lista é marcado com `<li>`, e você usa as tags `<strong>` e `<i>` para destacar o nome da empresa.

```
    <h4>Experiência Profissional</h4>

    <ol>
        <li>
            <Strong>Nome da Empresa:</Strong> <i>[Nome da Empresa]</i>
```

Dentro de cada item da lista de experiência profissional, tem uma lista não ordenada `<ul>` para listar detalhes sobre o cargo, destacando o cargo com `<strong>`.

```
           <ul>
                <li>
                    <Strong>Cargo:</Strong> <i>DevSecOps Professional</i>
```

Dentro de cada item de experiência profissional tem o período e as principais realizações. Usei `<small>` para formatar a sigla "IaC" como sobrescrito.

```
                </li>
                <li>
                    <Strong>Período:</Strong> <i>[Data de início] - Presente</i>
                </li>
                <li>
                    <Strong>Principais Realizações:</Strong> <i>Desenvolvimento e implementação de soluções de segurança cibernética para proteger os sistemas da empresa. Automação
                        de processos de desenvolvimento e operações para aumentar a eficiência e reduzir erros. Colaboração em projetos de
                        infraestrutura como código <small>(IaC)</small> para melhorar a escalabilidade e a confiabilidade das aplicações.
                    </i>
                </li>
            </ul>
        </li>
    </ol>
```

O restante do código segue um padrão semelhante, listando informações sobre __educação__, __habilidades técnicas__, __projetos__, __artigos__ e __uma curiosidade__.

## Conclusão

Agradeço pelo interesse em ler até aqui. Não se esqueça de deixar uma __estrela__ no meu __repositório__ e me seguir no __GitHub__ e nas minhas outras __redes sociais__.

## Sobre o Bootcamp
![Formação HTML Web Developer](https://hermes.dio.me/tracks/cover/8696d681-011b-4860-a19e-575ac016c00e.png)

### Detalhes da formação
Você quer começar no mundo do Front-end? Então essa é a Formação perfeita para você começar a sua jornada: entenda como trabalhar com HTML, a base para criar suas primeiras páginas WEB! Aprenda na prática a como estruturar a marcação da sua página e como funciona cada tag, conheça os elementos semânticos e outras boas práticas na hora de construir sua primeira página.

⭐Essa é uma excelente formação para começar sua carreira como front-end.

__Atividades:__
- Desafio de Código: Coloque em prática todo o conhecimento adquirido nas aulas e teste o seu conhecimento na resolução de um desafio.

- Desafio de Projeto: Construa o seu portfólio construindo projetos práticos com o conhecimento adquirido ao longo das aulas.


__Ferramentas para o seu aprendizado:__
- Fórum: Espaço para você interagir e tirar suas dúvidas técnicas com a nossa comunidade.

- Rooms: Espaço para você conversar com outros matriculados no bootcamp e aumentar o seu networking.

- Matriculados: Saiba quem está participando da mesma jornada educacional que você.

- Certificado: Baixe e compartilhe os certificados de todas as suas conquistas ao longo dessa formação.


__Clique aqui e saiba mais:__
https://bit.ly/dio-me-html-web-dev
