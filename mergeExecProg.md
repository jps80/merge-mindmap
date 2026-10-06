---
title: Merge Digital Asset Executive Program
markmap:
  colorFreezeLevel: 2
---

## Base financiera
### Tipos
-   Efectivo
    -   Banco Central
-   Saldo en cuenta
    -   Banco Comercial
-   Dinero electrónico
    -   Entidad de Dinero Electrónico
-   Reservas
    -   Banco Central

### Capas del dinero
-   Agregador monetarios
    -   Dónde está representado
    -   Quién lo emite
-   Capas
    -   **M0**
        -   Billetes y monedas en circulación + reservas de los bancos en el banco central | Banco central | Máxima |
        -   Representa el 1% del dinero total del mundo
    -   **M1**
        -   M0 (sin reservas) + depósitos a la vista en bancos comerciales | Banco central + bancos comerciales | Alta — exigibles sin preaviso |  
        -   Representa el 99%
    -   **M2**
        -   M1 + depósitos a plazo hasta 2 años + depósitos disponibles con preaviso hasta 3 meses | Igual | Media |
    -   **M3**
        -   2 + instrumentos negociables (cesiones temporales, participaciones en fondos del mercado monetario, valores de deuda hasta 2 años) | Igual + emisores de instrumentos del mercado monetario | Baja relativa |

### Target Services
-   Definición
    -   conjunto de infraestructuras de pagos y liquidación operadas por el Eurosistema que mueven dinero de banco central en euros entre bancos, cámaras de compensación y depositarios centrales de valores
    -   la liquidación se produce en dinero de banco central (M0), no en dinero comercial
-   Tipos
    -   T2
        -   Pagos mayoristas (€) entre BC y BCom
        -   Tx a Tx
    -   T2S
        -   Liquidación DvP de valores contra dinero de BC
        -   Operación a operación
    -   TIPS
        -   TARGET Instant Payment Settlement
        -   Pagos instantaneos minoristas en dinero de BC
        -   Tx a TX
    -   ECMS
        -   Eurosystem Collateral Management System
        -   Gestión unificada del colateral que los bancos aportan al Eurosistema

## Stablecoins
### Definiciones

- Activo digital que vive en una blockchain y que guarda una paridad con otro activo manteniendo un valor estable
- El token es la promesa de la devolución/canje
    - token → derecho jurídico → emisor → activos/reserva → capacidad de redención

### Tipos (por respaldo)

- Fiat-colateralizadas (off-chain)
    - 1 token = 1 FIAT
        - Dinero en el banco
        - Bonos
        - Otros 
    - arbitraje de redención
        -  Si el precio de mercado cae por debajo de 1$, un actor autorizado compra el token barato y lo redime
    - Ejemplos
        - USDC
        - USDT
        - EURC
- Cripto-colateralizadas (on-chain)
    - 1 token = 1,5 Cripto
    -   sobrecolaterizadas para evitar riesgos
    - arbitraje por liquidaciones automatizadas
    - Ejemplos
        - DAI
- Comodities 
    - La garantía son activos físicos
        - Oro
        - Soja
    - Mantien paridad con activo físico
- Algorítmicas
    -  Paridad se sostiene por incentivos de arbitraje entre dos tokens: uno estable, otro volátil que absorbe el exceso/déficit de oferta
- ¿Por activos RWA financieros?
    - [] Investigar

### Normativo/Legal

- MiCA
    - EMT (Electronic Money Token)
        - el token referencia una única moneda oficial
        - Emisor es una Entidad de dinero electrónico (EMI) o una entidad de crédito 
    - ART (asset-referenced token)
        - es un criptoactivo que busca mantener un valor estable respaldándose en una cesta de activos (múltiples monedas nacionales), en materias primas (commodities), en otras criptomonedas, o en una combinación de todos ellos
        - VIP: el registro oficial de la Unión Europea (manejado por la ESMA) no cuenta aún con emisores de ARTs autorizados operando formalmente con licencia comunitaria dentro de Europa (2026-sep)
    - Consideraciones
        - exige que la reserva cubra los riesgos de los activos referenciados y los riesgos de liquidez derivados de la redención.

### Usos

- | Área                     | Uso de stablecoins                        | Madurez        |
| ------------------------ | ----------------------------------------- | -------------- |
| 🌍 Pagos internacionales | Cross-border payments                     | Alta           |
| 💱 FX                    | Liquidación de divisas 24/7               | Alta           |
| 🏦 Treasury              | Gestión de liquidez corporativa           | Media-alta     |
| 💸 Remesas               | Transferencias internacionales            | Alta           |
| 🛒 Payments              | Merchant payments                         | Media          |
| 📈 Trading               | Settlement de crypto/digital assets       | Alta           |
| 🏛️ RWA                  | Compra/liquidación de activos tokenizados | Alta/creciente |
| 📜 Securities            | DvP de valores tokenizados                | Media          |
| 💰 Fondos                | Suscripciones/redenciones 24/7            | Media          |
| 🏦 Bancos                | Settlement entre instituciones            | Media          |
| 🤖 AI agents             | Pagos máquina-a-máquina                   | Emergente      |
| IoT                      | Machine-to-machine payments               | Emergente      |
| ⚡ Programmable money     | Pagos condicionados                       | Emergente      |
| 🌐 DeFi                  | Lending, liquidity, collateral            | Alta           |
| 🏢 Corporate             | Intercompany settlement                   | Emergente      |
| 🧾 Trade finance         | Pagos condicionados a eventos/documentos  | Emergente      |

- Stablecoins
    - como dinero de movimiento
    - como dinero de liquidación
    - como collateral
    - como dinero programable

### Perspectiva técnica

-   Capas
    -  Emisión
    -  Settlement - Interoperabilidad

### Referencias
- USDT - Tether
- USDC - Circle
- PYUSD - Paypal

### Otros
- Identidad (KYC/KYB)
- Custodia
- On compliance

### Conceptos
- Depeg
- Custodia
- On compliance

## Tokenización

### Definiciones
-   Representar activos del mundo real como tokens digitales con propiedad y lógica programabla en Blockchain
-   Los derechos y naturaleza legal NO cambian por ser tokens (con respecto del activo subyantece)

### Security tokens

-   Activos o derecho financiero regulado con la misma validez que legal que el valor tradicional
-   Ejplos
    -   Acciones
    -   Bonos
    -   Participaciones
    -   Deudas
    -   Bienes reales
-   No cambia la naturaleza, solo por donde se emite/transfiere/custodia
-   Les aplica MiFID II

### Depositos bancarios
-   El dinero que le entregas al banco (ingreso, nóminas) se convierten en un "deposito bancario"
-   Es un pasivo del banco frente a un tercero 
-   Es un apuntable contable en la BBDD del banco
-   Problemas
    -   Tiempos de liquidación
    -   Sujetos a horarios bancarios
    -   Sin programabilidad
-   Deposito tokenizado es igual representado mediante un token digital en una BC 
-   Regulación aplicable
    -  CRR/CRD, PSD2/PSD3, BRRD, Directiva de Garantía de Depósitos
- Casos de uso 
    -   Pagos B2B intraempresariales 24/7
    -   Liquidicación DvP de valores tokenizados 
    -   Tesorería corporativa
    -   Trade finance y cadenas de suministro con pagos condicionales
    -   
- Perspectiva técnica
-   Aspecto	Depósito Tradicional	Depósito Tokenizado
Representación	Registro en core banking (base de datos centralizada)	Token en DLT (habitualmente ERC-20 con extensiones de control)
Liquidación	T+1 / T+2 vía SEPA, TARGET2	Atomic settlement (DvP, PvP) casi instantáneo
Horario	Horario bancario / ventanas de liquidación	24/7/365
Programabilidad	Nula (fuera del core del banco)	Alta (smart contracts, condicionalidad)
Identidad / KYC	Interno al banco	On-chain vía allowlists, SSI/eIDAS2, ERC-3643
Redes típicas	SWIFT, SEPA, TARGET2	Fnality, Partior, JPM Coin/Kinexys, Onyx, redes permissioned tipo Besu/Canton

### Conceptos
-   Cash leg
     -  la parte monetaria de una transacción financiera en la que se intercambian dos cosas: por un lado un activo (valor, bono, acción, token…) y por otro el dinero que lo paga.
- Asset leg (pata del activo):
    -  el instrumento que se entrega (bono, acción, token de RWA, materia prima, etc.).
- Reserva fraccionaria regulada
    -   Uel % de dinero líquido que un Banco está obligado a mantener
    -   Determinada por el regulador

## Normativo
### MiCA (StableCoin)
#### Emisor
- Reembolso a la par
  - En cualquier momento
  - Sin comisión
  - Art. 49
- Reserva separada
  - Al menos 30% en bancos
  - 60% si es significativa
  - Resto en activos líquidos
  - Art. 54
- Plan de recuperación
  - Comisiones
  - Límites o suspensión de reembolsos
  - Plan de reembolso ordenado si falla
  - Art. 55
- Prohibido pagar intereses
  - Art. 50

#### Comercializadores y préstamos
- Exchange o app no garantiza la paridad
  - Debe informar con claridad
  - Actuar en interés del cliente
  - Custodiar bien
- MiCA no regula los préstamos en criptoactivos
  - Manda el contrato
- En España
  - Préstamo en stablecoins ≈ préstamo de cosa fungible
  - Se devuelve la misma cantidad de tokens
  - Art. 1753 Código Civil

#### Jurisprudencia
- Unión Europea
  - Sin sentencias conocidas sobre pérdida de paridad bajo MiCA
- Estados Unidos
  - Tether pagó multas en 2021
    - Nueva York
    - CFTC
  - Motivo: informar mal de sus reservas
- Caso Terra
  - Do Kwon (fundador)
  - Condenado a 15 años de prisión
  - Diciembre de 2025
  - Fraude sobre la estabilidad del token

#### Idea clave
- MiCA no garantiza el precio en el mercado
- Garantiza el derecho a cobrar 1 € del emisor
- Diferencia con un depósito
  - El depósito tiene FGD (Fondo de Garantía de Depósitos)