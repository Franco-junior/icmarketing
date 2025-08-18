# Simone

### Metodologia e Observações Iniciais

A análise a seguir é baseada na observação cuidadosa do mapa de calor e do ponto de fixação (o círculo vermelho) presente no vídeo. Os valores são estimativas calculadas com base na duração das cenas e no comportamento visual demonstrado. O desvio padrão (`±`) representa uma margem de erro estimada para cada métrica.

Para cada anúncio, primeiramente identifiquei as **Áreas de Interesse (AOIs)** mais relevantes, como o produto, o logo, rostos humanos e textos principais. Em seguida, calculei as métricas para cada uma dessas AOIs.

---

### Análise por Anúncio

#### 1. Anúncio: Google (0:15 - 1:08)

Este anúncio demonstra a funcionalidade da busca do Google em diversos cenários. A atenção do espectador é altamente focada na tarefa, seguindo a interação do usuário na tela.

**Áreas de Interesse (AOIs):**
*   **AOI 1: Barra de Busca:** Onde o texto é inserido.
*   **AOI 2: Sugestões de Busca:** A lista de autocompletar que aparece abaixo da barra.
*   **AOI 3: Resultados da Busca:** Os links e descrições na página de resultados.
*   **AOI 4: Elementos Especiais:** Mapas, tradutor e outros resultados diretos.

**Análise das Métricas (Estimativa):**

| Métrica | AOI 1: Barra de Busca | AOI 2: Sugestões | AOI 3: Resultados | AOI 4: Elem. Especiais |
| :--- | :--- | :--- | :--- | :--- |
| **Fixation count** | 6 ± 2 | 8 ± 3 | 12 ± 4 | 7 ± 2 |
| **Mean fixation duration (ms)** | 350 ± 50 | 220 ± 40 | 380 ± 60 | 410 ± 50 |
| **Dwell time (%)** | 20% ± 5% | 15% ± 5% | 40% ± 10% | 25% ± 5% |
| **TTFF (ms)** | 400 ± 100 | 1100 ± 200 | 2500 ± 300 | 2300 ± 300 |
| **Revisit count** | 2 ± 1 | 1 ± 1 | 3 ± 1 | 2 ± 1 |
| **Transitions (principais)** | Barra → Sugestões | Sugestões → Resultados | Resultados → Elem. Especiais | Elem. Especiais → Resultados |

**Conclusão (Google):** A atenção é direcionada de forma muito funcional. O TTFF para a barra de busca é quase imediato. As sugestões são escaneadas 
rapidamente (baixa duração de fixação), enquanto os resultados e elementos especiais recebem fixações mais longas, indicando processamento e tomada de decisão. A maior parte do tempo (Dwell time) é gasta nos resultados, que é o objetivo final da busca.

---

#### 2. Anúncio: LinkedIn (1:14 - 2:13)

Um anúncio com forte apelo emocional e humano, mostrando diferentes profissionais em suas jornadas.

**Áreas de Interesse (AOIs):**
*   **AOI 1: Rostos Humanos:** Foco principal durante quase todo o anúncio.
*   **AOI 2: Ação/Contexto:** O que as pessoas estão fazendo (trabalhando, tocando, etc.).
*   **AOI 3: Logo + Slogan Final:** A mensagem da marca no final do vídeo.

**Análise das Métricas (Estimativa):**

| Métrica | AOI 1: Rostos Humanos | AOI 2: Ação/Contexto | AOI 3: Logo + Slogan |
| :--- | :--- | :--- | :--- |
| **Fixation count** | 35 ± 8 | 10 ± 4 | 5 ± 2 |
| **Mean fixation duration (ms)** | 450 ± 70 | 280 ± 50 | 500 ± 80 |
| **Dwell time (%)** | 75% ± 10% | 15% ± 5% | 10% ± 3% |
| **TTFF (ms)** | 250 ± 100 (em cada nova cena) | 1500 ± 300 | 50000 ± 500 |
| **Revisit count** | 12 ± 4 (entre diferentes rostos) | 3 ± 2 | 1 ± 1 |
| **Transitions (principais)** | Rosto → Ação | Rosto (pessoa 1) → Rosto (pessoa 2) | Rosto Final → Slogan |

**Conclusão (LinkedIn):** A atenção é massivamente dominada pelos rostos humanos (`Dwell time` de 75%), o que é esperado para anúncios que buscam criar conexão emocional. A duração média da fixação nos rostos é alta, sugerindo que o espectador está processando emoções e a história. O logo e o slogan no final recebem atenção focada e de longa duração, consolidando a mensagem da marca.

---

#### 3. Anúncio: Nike (2:19 - 3:52)

Anúncio de alta energia e ação, centrado em um jogo de "pega-pega" em uma cidade.

**Áreas de Interesse (AOIs):**
*   **AOI 1: Personagem Principal:** O homem que está sendo perseguido e/ou perseguindo.
*   **AOI 2: Outras Pessoas/Obstáculos:** As multidões e pessoas que interagem com o personagem.
*   **AOI 3: Logo + Slogan Final ("tag", "play"):** O CTA da marca no final.

**Análise das Métricas (Estimativa):**

| Métrica | AOI 1: Personagem Principal | AOI 2: Outras Pessoas | AOI 3: Logo + Slogan |
| :--- | :--- | :--- | :--- |
| **Fixation count** | 60 ± 10 | 15 ± 5 | 4 ± 2 |
| **Mean fixation duration (ms)** | 200 ± 40 | 180 ± 30 | 450 ± 70 |
| **Dwell time (%)** | 80% ± 10% | 15% ± 5% | 5% ± 2% |
| **TTFF (ms)** | 150 ± 50 | 800 ± 200 | 85000 ± 500 |
| **Revisit count** | N/A (foco contínuo) | 5 ± 2 | 1 ± 1 |
| **Transitions (principais)** | Personagem → Obstáculo → Personagem | | Personagem → Slogan |

**Conclusão (Nike):** O olhar do espectador está quase que inteiramente "travado" no personagem principal, seguindo seus movimentos. O `Fixation count` é altíssimo e a `Mean fixation duration` é baixa, característico de um acompanhamento visual de um objeto em rápido movimento. O cérebro não está 
processando profundamente cada frame, mas sim rastreando a ação. Isso mantém o engajamento e a adrenalina, com a marca aparecendo no final para associar-se a esses sentimentos.

---

#### 4. Anúncio: Apple HomePod (3:54 - 4:52)

Um anúncio minimalista, focado exclusivamente no design e na interface visual do produto.

**Áreas de Interesse (AOIs):**
*   **AOI 1: Corpo do Produto:** A malha e a forma geral do HomePod.
*   **AOI 2: Interface Superior (UI):** As animações coloridas, ícones e informações na tela superior.
*   **AOI 3: Logo + Nome do Produto Final:** O texto "HomePod" no final.

**Análise das Métricas (Estimativa):**

| Métrica | AOI 1: Corpo do Produto | AOI 2: Interface Superior | AOI 3: Logo + Nome |
| :--- | :--- | :--- | :--- |
| **Fixation count** | 12 ± 4 | 25 ± 6 | 3 ± 1 |
| **Mean fixation duration (ms)** | 300 ± 50 | 480 ± 80 | 600 ± 100 |
| **Dwell time (%)** | 25% ± 8% | 70% ± 10% | 5% ± 2% |
| **TTFF (ms)** | 300 ± 100 | 800 ± 200 | 50000 ± 500 |
| **Revisit count** | 4 ± 2 | 8 ± 3 | 0 |
| **Transitions (principais)** | Corpo → Interface → Corpo | | Interface → Logo |

**Conclusão (Apple):** A atenção é quase que totalmente capturada pela interface animada no topo do produto. As fixações longas indicam que o espectador está intrigado e processando a beleza e a funcionalidade das animações. O design do produto serve como um contexto, mas a "magia" que atrai o olhar está na UI. A simplicidade do anúncio força o foco total no produto.

---

#### 5. Anúncio: Lexus (4:55 - 5:56)

Este anúncio cria uma analogia visual entre a performance de um dançarino e a engenharia do carro.

**Áreas de Interesse (AOIs):**
*   **AOI 1: O Carro:** Cenas do exterior, rodas e detalhes do veículo.
*   **AOI 2: O Dançarino:** Movimentos corporais e expressão do artista.
*   **AOI 3: Peças Mecânicas/Motor:** Cenas em close-up da engenharia.
*   **AOI 4: Logo Final:** Logo da Lexus e slogan.

**Análise das Métricas (Estimativa):**

| Métrica | AOI 1: O Carro | AOI 2: O Dançarino | AOI 3: Peças Mecânicas | AOI 4: Logo Final |
| :--- | :--- | :--- | :--- | :--- |
| **Fixation count** | 22 ± 5 | 20 ± 5 | 8 ± 3 | 4 ± 1 |
| **Mean fixation duration (ms)** | 380 ± 60 | 350 ± 50 | 300 ± 50 | 550 ± 80 |
| **Dwell time (%)** | 45% ± 8% | 35% ± 8% | 15% ± 5% | 5% ± 2% |
| **TTFF (ms)** | 200 ± 100 | 1000 ± 200 | 7000 ± 500 | 58000 ± 500 |
| **Revisit count** | 8 ± 3 | 7 ± 3 | 2 ± 1 | 1 ± 1 |
| **Transitions (principais)** | Carro ↔ Dançarino | Dançarino ↔ Peças | Carro ↔ Peças | |

**Conclusão (Lexus):** O anúncio promove um alto número de `Transitions` e `Revisits` entre o carro e o dançarino, forçando o espectador a fazer a conexão mental que a marca deseja. O tempo de atenção é bem dividido entre os dois elementos principais, mostrando que a estratégia de analogia visual 
foi bem-sucedida em manter o interesse em ambas as partes.

---

#### 6. Anúncio: Heineken (5:59 - 7:31)

Anúncio narrativo com um protagonista que se destaca em uma festa por sua habilidade única, culminando com ele conseguindo uma Heineken.

**Áreas de Interesse (AOIs):**
*   **AOI 1: Protagonista:** O homem de terno azul e depois de camisa branca.
*   **AOI 2: Outros Personagens:** Pessoas com quem ele interage (o homem do olho de vidro, Bruce Lee, etc.).
*   **AOI 3: O Produto (Garrafa):** A garrafa de Heineken, especialmente quando se torna o objetivo.
*   **AOI 4: Logo Final:** O logo da Heineken e o slogan.

**Análise das Métricas (Estimativa):**

| Métrica | AOI 1: Protagonista | AOI 2: Outros Personagens | AOI 3: O Produto (Garrafa) | AOI 4: Logo Final |
| :--- | :--- | :--- | :--- | :--- |
| **Fixation count** | 45 ± 8 | 25 ± 6 | 15 ± 4 | 5 ± 2 |
| **Mean fixation duration (ms)** | 400 ± 60 | 380 ± 50 | 420 ± 70 | 500 ± 80 |
| **Dwell time (%)** | 50% ± 10% | 25% ± 8% | 20% ± 5% | 5% ± 2% |
| **TTFF (ms)** | 500 ± 150 | 2500 ± 300 | 6000 ± 400 | 85000 ± 500 |
| **Revisit count** | 10 ± 3 | 6 ± 2 | 5 ± 2 | 1 ± 1 |
| **Transitions (principais)** | Protagonista ↔ Outros | Protagonista ↔ Produto | | |

**Conclusão (Heineken):** Sendo um anúncio narrativo, a atenção segue a história. O `Dwell time` é alto no protagonista. O que é interessante é como 
a atenção ao produto aumenta drasticamente na segunda metade, quando ele se torna o "prêmio" da jornada do herói. As fixações longas em todos os elementos indicam alto engajamento com a história e os personagens, com a Heineken sendo posicionada como o clímax da experiência.
