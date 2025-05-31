## Adaptação para Sala de Aula: "Ferro ou Madeira? Análise de Rotas de Caminhão"

**Objetivo:** Encontrar pontos de equilíbrio e determinar em quais distâncias cada carga é viável usando uma reta numérica.

**Contexto Simplificado e Pré-Cálculos:**
Um caminhão transportará uma carga máxima de 30 toneladas. Temos duas opções:

1.  **Carga A - Ferro Sucata:**
    *   Lucro Bruto (sem custos de viagem): **R$ 9.000,00**  
    *(Pré-calculado: custo da mercadoria = R$ 4.500,00, venda por R$ 13.500,00)*

2.  **Carga B - Madeira (Pinus Picado):**
    *   Lucro Bruto (sem custos de viagem): **R$ 15.000,00**  
    *(Pré-calculado: custo da mercadoria = R$ 7.500,00, venda por R$ 22.500,00)*

**Custo da Viagem por Km (Pré-calculado):**
O custo total para rodar 1 km com o caminhão (combustível, pedágio, motorista) é de **R$ 3,75**.  
*(Pré-cálculos simplificados: Diesel R$ 6,00/Litro (2 km/L → R$ 3,00/km), Pedágio R$ 0,50/km, Motorista R$ 0,25/km)*

**O Problema:**
O lucro total da viagem depende da distância percorrida (`d` em km). Ele é calculado por:
    *   `Lucro Ferro (Lf) = 9.000 - 3.75 * d`
    *   `Lucro Madeira (Lm) = 15.000 - 3.75 * d`

**Sua Tarefa:**

1.  **Encontre o Ponto de Equilíbrio para cada carga:**  
    O ponto onde o lucro se torna ZERO (custo da viagem = lucro bruto).  
    *   **Ferro:** `9.000 - 3.75 * d = 0` → `3.75d = 9.000` → `d = ?`
    *   **Madeira:** `15.000 - 3.75 * d = 0` → `3.75d = 15.000` → `d = ?`

2.  **Desenhe uma Reta Numérica:**  
    *   Marque os pontos de equilíbrio encontrados.
    *   Identifique as zonas onde:
        *   Ambas as cargas dão **LUCRO**
        *   Apenas uma carga dá **LUCRO**
        *   Ambas as cargas dão **PREJUÍZO**

3.  **Responda:**
    *   Até que distância **ambas** as cargas são lucrativas?
    *   A partir de que distância **nenhuma** carga é lucrativa?
    *   Em uma viagem de 1.800 km, qual carga dá mais lucro? E em uma de 2.800 km?
    *   Por que a carga de madeira é mais vantajosa quando ambas são viáveis?

---

**Resolução Esperada (Professor):**

1.  **Cálculo dos Pontos de Equilíbrio:**
    *   **Ferro:** `3.75d = 9.000` → `d = 9.000 / 3.75` → **d = 2.400 km**
    *   **Madeira:** `3.75d = 15.000` → `d = 15.000 / 3.75` → **d = 4.000 km**

2.  **Reta Numérica e Análise:**

    ```
    Prejuízo (Ambas) | Lucro Apenas MADEIRA | Lucro AMBAS | Lucro AMBAS
    <--------------|---------------------|------------|------------>
    0           2.400km             4.000km         Distância (d)

    Zonas:
    *   d < 2.400 km: Ambas dão LUCRO (Lm > Lf)
    *   2.400 km ≤ d < 4.000 km: Apenas MADEIRA dá LUCRO (Ferro: PREJUÍZO)
    *   d ≥ 4.000 km: Ambas dão PREJUÍZO
    ```

3.  **Respostas:**
    *   Ambas são lucrativas em viagens **inferiores a 2.400 km**.
    *   Nenhuma é lucrativa em viagens **iguais ou superiores a 4.000 km**.
    *   **1.800 km:**
        *   `Lf = 9.000 - 3.75 * 1.800 = 9.000 - 6.750 = R$ 2.250`
        *   `Lm = 15.000 - 3.75 * 1.800 = 15.000 - 6.750 = R$ 8.250` (Mais lucro!)
    *   **2.800 km:**
        *   `Lf = 9.000 - 3.75 * 2.800 = 9.000 - 10.500 = -R$ 1.500` (Prejuízo!)
        *   `Lm = 15.000 - 3.75 * 2.800 = 15.000 - 10.500 = R$ 4.500` (Lucro!)
    *   A madeira dá mais lucro porque seu **lucro bruto (R$ 15.000)** é maior que o do ferro (R$ 9.000). Como o **custo por km é igual para ambas (R$ 3.75)**, a madeira "aguenta" custos de viagem maiores antes de zerar o lucro, e sempre terá um lucro maior do que o ferro na mesma distância enquanto ambas forem positivas.

**Pontos Fortes para a Sala:**
*   **Foco no Objetivo:** Pré-cálculos eliminam etapas distractoras (combustível, pedágio, salário).
*   **Conceito Central Claro:** Ponto de Equilibrio = Custo Total da Viagem consome o Lucro Bruto.
*   **Visualização Poderosa:** A reta numérica torna abstrato (funções lineares) em concreto (zonas de decisão).
*   **Números Amigáveis:** Divisões e multiplicações simples (9.000 ÷ 3.75 = 2.400; 15.000 ÷ 3.75 = 4.000).
*   **Contexto Engajador:** Logística é um problema real e a linguagem informal ("ferro até entupir") cativa.
*   **Extensão Fácil:** Pode-se perguntar qual o lucro exato em pontos específicos (como 1.800 km e 2.800 km) para reforçar a substituição na função.