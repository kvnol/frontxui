---
description: >-
  Algumas decisões tomadas pelo time de design por desconhecimento de como
  funciona o front-end, pode acabar acarretando diversos problemas na hora da
  codificação dos layouts entregues, por isso alguns
---

# Evite fazer isso no seu design

### Blend modes

Mesmo hoje em dia o `mix-blend-mode` já existir no CSS há algum tempo e suportado pelos principais browsers atualizados, muitas vezes é melhor evitar esses efeitos de camadas, principalmente em casos de banners com imagens manipuladas. Usar o blend-mode para adicionar um efeito diferente no `:hover` pode até sem um bom recurso, mas se sua peça visual é estática, sem animações de camadas, talvez seja melhor optar por uma imagem exportada ao invés do dev encher o CSS de mix-blend-mode.

### Iconografia despadronizada

Ao invés de baixar `.png` de ícones no Google Imagens, talvez seja melhor utilizar uma família de ícones, assim como já utilizamos famílias de tipografias, conectando essa iconografia com nosso design system pensado justamente para a identidade visual do nosso produto. Algumas famílias de ícones mais conhecidas são:

* [Material Design Icons](https://fonts.google.com/icons)
* [Unicons](https://iconscout.com/unicons)
* [Ionicons](https://ionic.io/ionicons)
* [Font Awesome](https://fontawesome.com)

E se você usa Styled Components no seu projeto, o [Styled Icons](https://styled-icons.dev/) é uma boa sugestão também para utilizar essas e outras iconografias.

### Inconsistência no tamanho dos elementos

Evitar as inconsistências de tamanhos de elementos iguais componentizando os mesmos pode e irá ajudar muito o time de desenvolvimento, pois eles também poderão reaproveitar os módulos sem precisar criar hotfixes para páginas específicas onde o componente tem um visual diferente.

Uma boa prática que também ajuda muito na componentização de elementos pelo time de desenvolvimento é reparar e ajustar os valores quebrados (47.84px ao invés de 48px), com estes valores arredondados os elementos acabam se encaixando muito melhor nas páginas e dessa forma facilitando o alinhamento. Leia sobre grid 8pt, isso pode ajudar nessa padronização de tamanhos.

### Pontos de toque fracos no mobile e tablet

É boa prática de usabilidade e de acessibilidade ter elementos tocáveis/clicáveis com uma boa área, evitando assim cliques fora do elemento certo ou que dificulte a leitura. O mínimo de um ponto de toque recomendado pela Apple é de 44x44px e de 48x48px pelo Google, levando em conta que o tamanho mínimo sugerido para o texto é de 14px.

#### Aprofunde-se

* [10 Common UI Design Mistakes](https://careerfoundry.com/en/blog/ui-design/common-ui-design-mistakes/)
* [Everything you should know about 8 point grid system in UX design - UX Planet](https://uxplanet.org/everything-you-should-know-about-8-point-grid-system-in-ux-design-b69cb945b18d)
* [Size matters! Accessibility and Touch Targets - Medium](https://medium.com/@zacdicko/size-matters-accessibility-and-touch-targets-56e942adc0cc)
* [Touch target size - Google](https://support.google.com/accessibility/android/answer/7101858?hl=en)
* [Accessibility - Apple Developer](https://developer.apple.com/design/human-interface-guidelines/accessibility)
