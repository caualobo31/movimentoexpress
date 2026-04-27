# PROMPT — Página de Vendas: Movimento Express

## Contexto

Você é um desenvolvedor frontend sênior e designer de landing pages de alta conversão. Vai criar uma página de vendas completa em HTML/CSS/JS (arquivo único) para um infoproduto low ticket chamado **Movimento Express**.

O produto é um guia digital com +300 atividades físicas e cognitivas para idosos, organizado por objetivo e nível de dificuldade. Qualquer pessoa consegue aplicar — filhos, netos, cuidadores e profissionais de saúde.

O público é amplo: familiares preocupados com o idoso, cuidadores e fisioterapeutas. A comunicação na página é universal (não segmentada por persona).

---

## Direção de Design

### Tom Visual
- **Confiança e segurança** acima de tudo. A pessoa que chega nessa página tem medo — medo de machucar o idoso, medo de fazer errado, medo de gastar dinheiro à toa. O design precisa transmitir: isso é sério, é seguro, foi feito com cuidado.
- Sofisticado mas acessível. Não pode parecer clínica hospitalar, mas também não pode parecer produto genérico de Hotmart.
- Clean, espaçoso, com respiro visual. Nada amontoado.

### Paleta de Cores
- Primária: verde suave/sage ou azul petróleo — transmite saúde, calma, confiança
- Secundária: branco e off-white para fundos
- Acentos quentes: laranja ou dourado suave para CTAs e destaques de preço
- Vermelho apenas para o preço antigo riscado
- Evite: roxo, neon, gradientes chamativos, preto pesado

### Tipografia
- Display/Headlines: fonte com personalidade mas legível. Algo como Playfair Display, DM Serif Display ou Lora. Nada genérico.
- Body: fonte limpa e moderna. Nunca Arial ou Inter. Use algo como DM Sans, Plus Jakarta Sans ou Source Sans 3.
- Importar do Google Fonts.

### Elementos Visuais
- Ícones suaves e arredondados (Lucide, Phosphor ou similar via CDN)
- Bordas arredondadas nos cards (border-radius generoso)
- Sombras sutis para profundidade (box-shadow suave)
- Badges/selos de confiança com design cuidado
- Sem imagens de stock genéricas — usar emojis ou ícones onde normalmente teria foto

### Layout
- Mobile-first (a maioria do tráfego vem do Meta Ads no celular)
- Max-width de ~720px no conteúdo para leitura confortável
- Espaçamento generoso entre blocos (padding 60-80px vertical)
- Botões de CTA grandes, com destaque visual, com micro-animação no hover

---

## Estrutura — 13 Blocos (nesta ordem exata)

### BLOCO 1 — HERO
- Headline: "+300 Atividades Para o Corpo e a Mente de Idosos — Prontas Para Aplicar Hoje"
- Sub-headline: "Exercícios físicos e cognitivos organizados por objetivo e nível de dificuldade. Qualquer pessoa consegue aplicar com segurança."
- 4 bullets com ícones: "Sem equipamento especial" · "Para todos os níveis de mobilidade" · "Atividades para corpo e mente" · "Acesso imediato"
- Botão CTA: "Quero minhas atividades agora" (âncora para o Bloco 10)
- Elemento de prova social leve abaixo do CTA: "+X pessoas já adquiriram" (placeholder)
- Fundo com textura sutil ou gradiente muito suave para se diferenciar do branco puro

### BLOCO 2 — DOR (micro-cena)
- Chamada: "Você percebe que ele fica cada vez mais parado."
- Texto: "Passa o dia na cadeira ou na cama. Levanta com dificuldade. Já não faz sozinho o que fazia antes."
- Texto: "Você quer ajudar, mas não sabe o que é seguro. Tem medo de fazer algo errado. Sente que a cada semana ele perde um pouco mais."
- Texto de transição: "E se existisse um material simples, seguro e organizado pra você abrir e aplicar hoje?"
- Design: fundo levemente diferente (off-white ou cinza muito claro). Texto com destaque sutil nas palavras-chave emocionais. Sem exagero — a dor é sutil, não agressiva.

### BLOCO 3 — MECANISMO (Movimento Express)
- Chamada: "A solução se chama Movimento Express"
- Texto: "+300 atividades para corpo e mente, organizadas por objetivo, nível de dificuldade e condição do idoso."
- Texto: "Não é uma lista solta de exercícios. É um material estruturado pra você encontrar a atividade certa em segundos e aplicar com segurança — mesmo sem experiência."
- 6 cards/ícones com as categorias:
  - Mobilidade e Equilíbrio
  - Força e Resistência
  - Coordenação Motora
  - Memória e Raciocínio
  - Estímulo Sensorial
  - Socialização e Bem-Estar
- Botão CTA: "Quero conhecer os planos" (âncora para Bloco 10)

### BLOCO 4 — VEJA POR DENTRO (3 exemplos)
- Chamada: "Veja por dentro do material"
- Sub-chamada: "Cada atividade vem com passo a passo, nível de dificuldade e recomendações de segurança."
- 3 cards lado a lado (empilhados no mobile):

  Card 1 — Físico:
  - Título: "Caminhada Guiada com Apoio"
  - Tag: "Equilíbrio"
  - Texto: "Atividade simples que pode ser feita no corredor de casa, com ou sem apoio. Indicada para todos os níveis."

  Card 2 — Cognitivo:
  - Título: "Jogo das Associações"
  - Tag: "Memória e Raciocínio"
  - Texto: "Dinâmica com palavras que ativa a memória de curto prazo. Não precisa de nenhum material. Funciona sentado."

  Card 3 — Misto:
  - Título: "Circuito das Cores"
  - Tag: "Coordenação + Atenção"
  - Texto: "O idoso associa cores a movimentos simples. Trabalha corpo e mente ao mesmo tempo. Adaptável para mobilidade reduzida."

### BLOCO 5 — COMO FUNCIONA (5 passos)
- Chamada: "Do acesso à aplicação em 5 passos"
- Layout: vertical com numeração (1-5) e ícones, com linha conectora entre os passos
- Passo 1: "Receba o acesso no seu email imediatamente após a compra"
- Passo 2: "Abra o material e escolha pela necessidade do idoso"
- Passo 3: "Leia as recomendações de segurança da atividade e verifique se é adequada para o idoso" ← ESTE PASSO EM DESTAQUE VISUAL (badge, cor diferente, borda, ícone de escudo — algo que chame atenção e transmita cuidado/responsabilidade)
- Passo 4: "Siga o passo a passo da atividade — simples como seguir uma receita"
- Passo 5: "Veja o idoso mais ativo, estimulado e confiante"

### BLOCO 6 — QUEM CRIOU
- Chamada: "Quem está por trás do Movimento Express"
- Layout: foto placeholder (círculo com ícone de pessoa) + texto ao lado
- Texto: "Desenvolvido por [Nome], [credencial]. Este material reúne atividades testadas na prática, adaptadas para serem aplicadas com segurança por qualquer pessoa — profissional ou não."
- Design: sóbrio, limpo, sem exagero. Uma seção curta que gera confiança.

### BLOCO 7 — PARA QUEM É
- Chamada: "Feito para quem cuida"
- 5 cards ou lista com ícones:
  - "Filhos e netos que querem ajudar o idoso a se manter ativo"
  - "Cuidadores que precisam de atividades práticas e seguras"
  - "Fisioterapeutas que buscam material organizado e pronto"
  - "Educadores físicos e terapeutas ocupacionais"
  - "Qualquer pessoa que convive com um idoso e quer fazer a diferença"

### BLOCO 8 — O QUE ESTÁ INCLUSO + STACK
- Chamada: "Tudo que você recebe no Movimento Express"
- Lista com check marks e valores ao lado:
  - +300 atividades físicas e cognitivas organizadas por objetivo e nível — R$297
  - Guia de aplicação segura (cuidados por tipo de atividade) — R$47
  - Fichas de acompanhamento de evolução — R$37
  - Ebook: Exercícios para idosos com mobilidade reduzida — R$47
  - Ebook: Atividades cognitivas para estímulo da memória — R$37
- Valor total exibido: R$465
- Os valores individuais em cinza/discreto, o total em destaque

### BLOCO 9 — BÔNUS DETALHADOS
- Chamada: "E você ainda recebe esses bônus:"
- 4 cards de bônus, cada um com:
  - Tag "BÔNUS" + número
  - Título do bônus
  - Descrição curta (1-2 linhas)
  - Valor riscado → "GRÁTIS"

  Bônus 1 — Guia de Aplicação Segura:
  "Orientações claras de segurança para cada tipo de atividade. Pensado para quem não é profissional de saúde aplicar sem medo."
  R$47 → GRÁTIS

  Bônus 2 — Fichas de Acompanhamento:
  "Registre quais atividades foram feitas e acompanhe a evolução do idoso semana a semana."
  R$37 → GRÁTIS

  Bônus 3 — Exercícios para Mobilidade Reduzida:
  "Atividades adaptadas para idosos que passam a maior parte do tempo sentados ou acamados."
  R$47 → GRÁTIS

  Bônus 4 — Atividades Cognitivas para Memória:
  "Jogos e dinâmicas simples que estimulam o cérebro e ajudam a manter a mente ativa."
  R$37 → GRÁTIS

### BLOCO 10 — PREÇO + CTA (BLOCO PRINCIPAL DE CONVERSÃO)
⚠️ ESTE É O BLOCO MAIS IMPORTANTE DA PÁGINA. Todos os botões de CTA da página inteira apontam para cá via âncora (#preco ou #planos). Precisa ser visualmente impactante, confiável e decisivo.

- ID da seção: "planos" (para âncora)
- Fundo diferenciado: cor de fundo suave contrastante com o resto da página (pode ser o verde/azul primário bem claro, ou um gradiente muito sutil)
- Borda ou card central elevado com sombra mais forte

Layout do card de conversão:
1. **Mockup do produto** no topo ou à esquerda: imagem placeholder de mockup mostrando o material principal + os 4 bônus (usar um container estilizado como se fosse um mockup 3D de ebook/tablet — pode ser feito em CSS puro com transforms e sombras, ou um placeholder com borda e ícone). Mostrar visualmente que são vários materiais empilhados/agrupados.

2. **Título:** "Movimento Express — Acesso Completo"

3. **Lista do que recebe** com checkmarks verdes:
   - ✓ +300 atividades físicas e cognitivas
   - ✓ Organizadas por objetivo e nível de dificuldade
   - ✓ Passo a passo simples para qualquer pessoa aplicar
   - ✓ Recomendações de segurança em cada atividade
   - ✓ Bônus: Guia de Aplicação Segura
   - ✓ Bônus: Fichas de Acompanhamento
   - ✓ Bônus: Exercícios para Mobilidade Reduzida
   - ✓ Bônus: Atividades Cognitivas para Memória
   - ✓ Acesso imediato e vitalício

4. **Bloco de preço:**
   - Texto pequeno: "De" seguido do valor antigo
   - Valor antigo: "R$465" em vermelho, riscado (text-decoration: line-through), fonte grande
   - Texto: "Por apenas"
   - Valor atual: "R$37" em fonte muito grande, bold, cor de destaque (verde escuro ou azul petróleo). Este é o elemento visual mais chamativo do bloco inteiro.
   - Abaixo: "Pagamento único · Acesso imediato · Sem mensalidade"

5. **Botão CTA principal:**
   - Texto: "QUERO O MOVIMENTO EXPRESS AGORA"
   - Botão grande, largo (100% da largura do card), cor de destaque forte (laranja/dourado ou verde vibrante — precisa contrastar com o fundo)
   - Border-radius arredondado
   - Sombra no botão
   - Micro-animação: pulse sutil ou hover com scale
   - Abaixo do botão em texto pequeno: "Acesso enviado por email imediatamente após o pagamento"
   - Link do botão: placeholder "https://checkout.exemplo.com" (será substituído depois)

6. **Selos de confiança** abaixo do botão, em linha:
   - 🔒 Pagamento 100% Seguro
   - ⚡ Acesso Imediato
   - 🛡️ Garantia de 15 Dias
   - 💳 Pix, Cartão ou Boleto
   - Cada selo com ícone + texto pequeno, alinhados horizontalmente (wrap no mobile)

7. **Elemento de urgência leve** (opcional): um texto sutil tipo "Preço promocional por tempo limitado" acima do preço ou abaixo dos selos. Sem countdown fake — apenas texto.

### BLOCO 11 — GARANTIA
- Chamada: "Risco zero. 15 dias de garantia total."
- Texto: "Acesse o material, explore as atividades, teste com o idoso. Se não fizer sentido pra você, devolvemos 100% do valor. Sem perguntas, sem burocracia."
- Ícone de escudo grande
- Botão CTA: "Quero começar com garantia" (âncora para Bloco 10)
- Design: fundo diferenciado, transmitindo segurança. Pode usar borda ou card com ícone de escudo proeminente.

### BLOCO 12 — FAQ
- Chamada: "Perguntas Frequentes"
- Accordion (clicável, expande/colapsa):

  "Precisa de equipamento?"
  "Não. A maioria das atividades usa apenas o corpo ou objetos simples que você já tem em casa."

  "Serve para idoso acamado?"
  "Sim. O material tem atividades adaptadas para diferentes níveis, incluindo idosos com mobilidade muito reduzida."

  "Eu não sou profissional de saúde. Consigo aplicar?"
  "Sim. Cada atividade tem passo a passo simples. Se consegue seguir uma receita, consegue aplicar."

  "Tem atividades para a mente também?"
  "Sim. O material inclui atividades cognitivas para memória, raciocínio e atenção, além dos exercícios físicos."

  "Como recebo o material?"
  "Imediatamente após o pagamento, o acesso é enviado por email."

  "E se eu não gostar?"
  "Você tem 15 dias pra pedir reembolso total. Sem perguntas."

### BLOCO 13 — CTA FINAL
- Headline: "+300 Atividades Prontas Para Manter o Idoso Ativo, Seguro e Com a Mente Estimulada"
- Texto: "Você não precisa ser profissional. Precisa de um bom material."
- Botão CTA: "Quero o Movimento Express agora" (âncora para Bloco 10)
- Fundo com a cor primária (verde/azul) e texto branco para fechar a página com força visual

---

## Requisitos Técnicos

- **Arquivo único**: HTML + CSS + JS inline (tudo em um arquivo .html)
- **Mobile-first**: responsivo, testado para 375px (iPhone SE) até 1440px
- **Performance**: sem frameworks pesados. Vanilla JS para o accordion e scroll suave. CSS puro para animações.
- **Scroll suave**: todos os botões CTA fazem smooth scroll até o Bloco 10 (#planos)
- **Fontes**: Google Fonts (importar no head). Usar fontes distintas e elegantes conforme direção de design acima.
- **Ícones**: usar emojis ou SVG inline. Não depender de CDN externo para ícones se possível. Se usar CDN, Lucide ou Phosphor.
- **Imagens**: não usar imagens externas. Criar placeholders visuais em CSS puro (mockups estilizados, formas geométricas, ícones). Onde normalmente teria foto de idoso, usar um container estilizado com ícone.
- **Animações**: 
  - Fade-in nos blocos ao scroll (Intersection Observer)
  - Pulse sutil no botão CTA principal do Bloco 10
  - Hover effects nos cards e botões
  - Accordion suave no FAQ
- **Acessibilidade**: contraste adequado, alt texts, semântica HTML (section, article, nav)
- **Sticky CTA mobile**: barra fixa no bottom do mobile com botão CTA que ancora pro Bloco 10. Aparece após o usuário passar o Bloco 1. Discreta mas visível.

---

## Observações Finais

- Não invente textos além da copy fornecida. Use exatamente os textos dos blocos.
- Placeholders para preencher depois: foto do criador, nome do criador, credencial, link do checkout, número de pessoas que adquiriram.
- O Bloco 10 é o coração da página. Capriche. Todo o resto da página existe para levar a pessoa até ele.
- A página precisa funcionar sem JavaScript (accordion pode ser detalhes/summary como fallback).
- Teste visual: a página deve parecer que foi feita por uma agência, não por um template. Sofisticada, confiável, humana.
