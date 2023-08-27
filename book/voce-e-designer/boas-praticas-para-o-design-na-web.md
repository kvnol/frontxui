---
description: >-
  Algumas práticas da parte do time de design para o time de desenvolvimento são
  essenciais para uma boa conexão entre as equipes, facilitando o entendimento
  de regras essenciais do protótipo, fácil exp
---

# Boas práticas para o design na web

### Organização de layers

Um layout com layers organizadas facilitam muito a vida não só do time de desenvolvimento que precisará encontrar algum grupo de elementos para exportação mas também para o próprio time de design que precisará dar manutenções naqueles layouts ou design system mantido no Figma ou outra ferramenta de prototipação de UX.

### Componentização

Como já dito anteriormente e com certeza será dito posteriormente a componentização facilitará muito, mas muito mesmo a comunicação entre os times pois é muito melhor termos aqueles 3 tipos de botões, 6 tamanhos de títulos para todo nosso produto ao invés de uma página ter um título principal com 25px e em outra página o título principal com 23px, essa componentização de elementos por menores que sejam faz muita diferença e pensando nisso, o Atomic Design se encaixa muito bem:

* [Atomic Design: como criar sistemas de componentes](https://brasil.uxdesign.cc/atomic-design-como-criar-sistemas-de-componentes-8723301c5a37)

### Variações

Quando já temos essas componentizações fica muito mais simples de desdobrarmos as variantes desses módulos, pois muitas vezes eles são similares mas com pequenas variações nos tamanhos (small, medium, large), nas cores (primary, secondary, tertiary) e nos estados (hover, active, disabled).

### Breakpoints

Os breakpoints levantam muitas discussões e até polêmicas, pois há quem prefira construir um layout com pontos pré-definidos para cada dispositivo (376px para mobile, 768px para tablet, 1024px para desktop, etc) porém a palavra "breakpoint" é justamente o contrário, pois tratamos justamente os pontos de quebras e deixando o layout fluido ao, por exemplo, corrigir o título que estouraria no grid e ali diminuiríamos o tamanho do mesmo.

* [How do you use breakpoints and fluid grids for responsive web design?](https://www.linkedin.com/advice/3/how-do-you-use-breakpoints-fluid-grids-responsive-web)

Há também outra discussão no design responsivo como um todo se é melhor trabalhar no layout desktop com a tela completa e ir ajustando para baixo, ou seja, indo para o mobile ou ao contrário também conhecido como mobile first onde primeiramente pensamos no layout mais simples, focado no conteúdo.

* [Is Mobile First Always The Best Approach?](https://cleancommit.io/blog/is-mobile-first-always-the-best-approach/)

### Acessibilidade

É importante o time de design se atentar também com questões de acessibilidade. Normalmente, em tese, um time de desenvolvimento de software responsável por um projeto precisa se preocupar em deixar o projeto acessível, desde utilização de cores para pessoas com daltonismo a pessoas com algum tipo de deficiência visual, etc.

Existem ferramentas que nos ajudam a criar um projeto que siga algumas guidelines. Alguns deles são:

* [eMAG - Modelo de Acessibilidade em Governo Eletrônico](https://emag.governoeletronico.gov.br/)
* [WebAIM's WCAG 2 Checklist](https://webaim.org/standards/wcag/checklist)
* [Web Content Accessibility Guidelines (WCAG) 2.1](https://www.w3.org/TR/WCAG21/)
* [The A11Y Project](https://www.a11yproject.com/)

### SEO

Da mesma forma que Acessibilidade na web deveria ser algo obrigatório, implementações relacionadas a SEO estão ligadas com o quão provável a sua aplicação tem chances de aparecer primeiro em resultados de busca, podendo possivelmente converter seus acessos em vendas.

Quando o design de um sistema onde um cliente final chegará através de buscas possui claramente estratégias e técnicas de SEO em sua construção, mais chances de ser implementado corretamente esse sistema tem. Algumas referências:

* [Search Engine Optimization (SEO) Starter Guide](https://developers.google.com/search/docs/beginner/seo-starter-guide)
* [O que é SEO (Search Engine Optimization): o guia completo para você conquistar o topo do Google](https://rockcontent.com/br/blog/o-que-e-seo/)
