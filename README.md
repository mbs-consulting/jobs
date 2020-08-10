###### MBS Consulting
# Job Board


Estamos contratando uma pessoa para integrar a equipe técnica da **MBS Consulting**. Temos o privilégio de conduzir todo esse processo de perto e com muito cuidado, sabemos também das frustrações e atrapalhações que o RH ou grandes empresas acabam gerando nesse caminho. Então sem requisitos sem noção, vídeos de TikTok, testes que nos tomam dias e etc. Queremos **conversar**.

<br>

- [Sobre a Empresa e Projetos](#Sobre-a-Empresa-e-Projetos)
- [Sobre Formato e Alocação](#Sobre-formato-e-alocação)
- [Sobre Skills e Perfis](#Sobre-Skills-e-Perfis)
- [Sobre Experiência](#Sobre-Experiência)
- [Sobre Formação](#Sobre-Formação)
- [Dúvidas e Contato](#Dúvidas-e-Contato)

<br>
<br>

## Sobre a Empresa e Projetos

A MBS Consulting é uma empresa de consultoria com atuação nacional, temos uma trajetória que já somam 25 anos. Nossos projetos são voltados a Cultura Organizacional, Planejamento Estratégico e Transformação Digital (licença para uso *buzzword* - e é aqui onde você irá atuar conosco).


**Projetos**

A equipe técnica e os projetos de TI hoje são basicamente voltados para o que chamamos de **automação de processos**, ancoradas na disciplina de BPM - que trata sobre gestão de processos. Neste contexto é comum utilizarmos ferramentas BPMS (citando algumas: [Camunda](https://camunda.com/), [Bizagi](https://www.bizagi.com/en/platform/studio), [Orquestra](https://www.smlbrasil.com.br/bpm)) junto com desenvolvimento: customizações nessas plataformas, aplicações web, SPAs, APIs, BFFs, etc. Não há muitas restrições neste sentido, entendemos que devemos resolver um problema alinhado ao objetivo e escopo do projeto. Como somos uma consultoria, *stack* tecnológica e ferramentas vão ser escolhidas de acordo com o contexto do projeto, maturidade do cliente e inclusive da nossa equipe.

Os nossos clientes variam entre a área pública e privada, com escopos, desafios técnicos e contextos muito variados. Não são projetos "curtos", em média 1 a 2 anos, e alguns onde permanecemos mais tempo apoiando a sustentação ou evoluindo as soluções. Alguns dos nossos clientes:

<br>

![Clientes MBS](https://static.wixstatic.com/media/1920d2_e542453cc25341a7a55afc324beec82f~mv2.png/v1/fill/w_600,h_494,al_c,q_85,usm_0.66_1.00_0.01/Logos_Clientes-2.webp)

<br>

**Trabalhos que desenvolvemos recentemente**

Para que você possa ter uma noção do que fazemos no dia-a-dia aqui vai uma lista de trabalhamos que estivemos envolvidos recentemente:

- Desenvolvemos uma POC junto ao cliente para facilitar a adoção da plataforma Camunda. Quanto as tecnologias, foi construída uma API em Node com Express para intermediar a comunicação entre clientes e a camada REST do Camunda. Para *showcase* o front-end foi construído como um SPA utilizando Vue.js. Por fim, adotamos o uso de *ExternalTasks* em Camunda com serviços também em Node.
  >  Ancoramos a decisão nas orientações da Camunda: [Blog - Scaling Camunda Adoption in Your Company – Phases of Adoption](https://camunda.com/blog/2020/07/scaling-camunda-adoption-in-your-company-phases-of-adoption/)

- Evoluímos a adoção do Camunda no mesmo cliente com a implementação de um primeiro processo. Optamos por um de baixo acoplamento mas com alto volume de uso. Aliada a implementação do processo em si, desenvolvemos um dashboard no formato SPA utilizando Vue.js com foco nos gestores daquele processo de negócio.
 
- Seguindo a empreitada de adoção do Camunda, construímos e ministramos uma série de treinamentos a este cliente (foi o primeiro passo na realidade). Montamos tanto treinamentos "não técnicos" sobre processos, BPM e BPMN, como treinamentos técnicos sobre automação e a plataforma Camunda em si.

- Desenvolvemos uma biblioteca de componentes UI para estender as funcionalidades do BPMS Orquestra. No momento, por particularidades dessa plataforma, optamos por uma implementação somente com Javascript. Estamos avaliando a implementação via WebComponents ou com algum framework que tenha um *footprint* pequeno. Planejamos que esta seja nossa primeira contribuição *open-source*.

- Evoluímos nosso *tooling* com o BPMS Orquestra, incrementando nosso workflow front-end com uso de Webpack e Gulp.
- Conduzimos alguns estudos e testes para o uso do Camunda BPM via containers na plataforma OpenShift.

<br>

> Créditos desta seção de "trabalhos recentes" para o pessoal do Basecamp (DHH e companhia) na postagem das vagas deles.

## Sobre Formato e Alocação

**Formato**

A forma de contratação é **PJ**. E sendo muito franco, assim conseguimos negociar melhores valores. Caso você nunca tenha trabalhado neste formato podemos tirar suas dúvidas e apoiar essa transição. Tudo negociado é acordado em contrato, que prevê inclusive um aviso prévio em caso de dissolução. Nossa intenção é que você tenha segurança no que está sendo combinado.



**Alocação**

Infelizmente ainda não conseguimos trabalhar em um modelo *full-remoto*, então precisamos que você seja de **Porto Alegre / RS (ou região)** e esteja no escritório eventualmente. Quando digo eventualmente é porque há realmente muita flexibilidade com horários e trabalho presencial, não aquele discurso de flexibilidade das 9h às 10h. Entendemos que autonomia e independência são fundamentais, de verdade.

>  **Durante a pandemia:** por óbvio não será exigido de nenhuma maneira que você trabalhe presencialmente nesse período maluco que estamos vivendo.



**Viagens**

Como temos atuação em todo o Brasil, eventualmente também viajamos para atuar junto ao cliente. Não há nenhuma obrigatoriedade que você faça as viagens com a equipe, e sim um **convite**, pois é um momento de integração. Não se trata de uma alocação no cliente ou viagens durante todo período de projeto. São viagens curtas, muito raramente maiores que uma semana (seg-sex), e obviamente as despesas são cobertas, desde acomodação (hotel), passagens e diárias para alimentação.

## Sobre Skills e Perfis
Nada mirabolante, sem Estagiário Sênior, Full Stack Júnior, *"ninja"*... Estamos avaliando **2 perfis** no momento:

- **Front-end:** Temos uma demanda de projeto específica para front e uma carência maior desse perfil. Seremos os maiores incentivadores que você possa desenvolver-se para o perfil Full Stack que faz todo sentido no nosso contexto. E quando falo em incentivo, é tanto como mentoria quanto financeiro(!).

  **Conhecimentos que entendemos necessários:**

  - Javascript (conhecendo ES6+)
  - CSS
  - HTML

  É isso. JS/CSS/HTML. E a gente sabe que "só isso" pode englobar muita coisa.

- **Full Stack:** Se você tiver experiência como Full Stack melhor ainda. Em contrapartida entendemos que isso representa outro patamar financeiro, sem rodeios.

  **Conhecimentos que entendemos necessários:**

  - Javascript
  - CSS
  - HTML
  - Alguma linguagem Back-end (Seja JS com Node, Java, C#, Ruby...)
  - PL/SQL / T-SQL (não precisa ser nenhum especialista, o básico atende!)
  - REST
  
  Certamente se você é Full Stack deve ter outros conhecimentos, quando conversarmos você pode nos contar!

## Sobre Experiência

Esperamos que você tenha experiência(s) anterior(es) programando, então a quantidade de anos atuando na área é um parâmetro importante. Sabemos que alguns tem experiências mais intensas ou ainda se engajam mais no seu desenvolvimento pessoal. Estaremos abertos e atentos para estas questões para chegar no entendimento entre perfil Sênior ou Pleno.

Nossa intenção é ser transparente. Não temos nenhuma fórmula mágica que enquadre você em um perfil ou outro (nem acredito que exista isso). Então chegaremos juntos nesse entendimento, algo que fique confortável para você e que faça sentido para nós. Pronto. E de forma aberta.



## Sobre Formação

Não é uma exigência que você tenha feito faculdade, de forma alguma. É interessante, mas entendemos que não é obrigatório.



## Dúvidas e Contato

Se você tem interesse ou ficou com alguma dúvida, é só falar comigo:

- **Email:** pedro@mbsconsulting.com.br
- **Linkedin:** [linkedin.com/in/pedbernardo](https://www.linkedin.com/in/pedbernardo/)
