# Posts sueltos — Aster DEX

Posts individuales (no hilos) para intercalar entre los hilos grandes. Cada uno funciona solo.

---

## Post 1 — La matemática del 1001x (gancho viral)

A 1001x de apalancamiento en Aster:

Un movimiento del 0,10% en contra = liquidación total.

Entras largo en ETH a $2.500.
Toca $2.497,50.
Cero.

$2,50 de movimiento en un activo de $2.500.

El apalancamiento extremo no es una herramienta, es una cuenta atrás. Úsalo sabiendo lo que es.

---

## Post 2 — El funding es la fee real

Todo el mundo compara perp DEXs mirando fees de maker/taker.

Error de principiante.

Long de $10k en BTC en un mercado sobrecalentado (funding +0,1%/hora):
• Fee de entrada (taker 0,035%): $3,50
• Funding: 2,4% al día = $240

Y ojo: el funding se paga sobre la posición, no sobre tu margen. A 20x, esos $240 son el 48% diario de tu margen.

La fee es ruido. Compara funding, no fees.

*(Nota: +0,1%/hora es un régimen extremo, no el funding típico (~0,01% cada 8h). En mercados tranquilos funding y fee son comparables — el post describe el escenario donde el funding domina, que es donde la gente se quema.)*

---

## Post 3 — Colateral que trabaja (el edge silencioso de Aster)

En la mayoría de perp DEXs tu margen es dinero muerto.

En Aster puedes postear como colateral:
• asBNB (BNB en staking, ~6% APY)
• USDF (stable delta-neutral, ~7-10%)

Con funding negativo de -0,03%, ese yield lo compensa y puede voltear el carry a positivo.

El detalle: haircuts del 15-25% y colas de redención de hasta 7 días en estrés. Eficiencia a cambio de complejidad. Como todo en DeFi.

---

## Post 4 — Órdenes ocultas (por qué importan)

Pones una limit buy grande de BTC en un orderbook público y estás gritando tu intención a todos los bots de MEV.

Sandwich, front-running, caza de stops.

Las hidden orders de Aster Pro: ni precio ni tamaño visibles hasta que se ejecuta la orden. Liquidez del libro principal, visibilidad cero.

Es la feature menos sexy y más útil del stack.

---

## Post 5 — No KYC + MiCA (ángulo España/UE)

Aster no pide KYC: conectas wallet y tradeas. Non-custodial.

Y desde el 1 de julio, MiCA deja los derivados FUERA de su alcance → los perp DEXs operan en un vacío regulatorio en la UE.

Dos cosas que nadie te cuenta:
1. Restringido en EE.UU., UK y Canadá (y el VPN viola sus términos). España: sin problema.
2. Sin KYC ≠ sin Hacienda. Tus PnL de perps tributan igual. El exchange no informa, tú sí debes hacerlo.

---

## Post 6 — Simple vs Pro en una imagen

Aster tiene dos modos y elegir mal te cuesta dinero:

🟡 SIMPLE (1001x): un click, sin stops manuales, funding por bloque. Para scalps de <15 min. Punto.

🟡 PRO: orderbook, órdenes ocultas, brackets TP/SL, funding cada hora. Para todo lo que dure más que un scalp.

La regla: si tu posición va a vivir más de 15 minutos, no tienes nada que hacer en Simple.

*(Acompañar con tabla visual comparando: leverage, funding, órdenes, caso de uso)*

---

**Notas**:
- Posts 1 y 2 son los de mayor potencial de alcance (cifras contraintuitivas).
- Post 5 conecta con Angel-TAX → oportunidad de mencionar el proyecto propio de forma natural.
- Verificar cifras de funding/fees en vivo antes de publicar cada uno.
