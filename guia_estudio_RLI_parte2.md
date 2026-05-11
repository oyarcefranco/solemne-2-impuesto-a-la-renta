# 📝 *GUÍA DEFINITIVA RLI — PARTE 2: Ejercicios Resueltos Paso a Paso*

---

## EJERCICIO 1: Régimen Semi-Integrado 14 Letra A (Básico)

**Empresa**: Sin nombre especificado | **Giro**: No especificado
**Tipo**: Sociedad de personas, ningún socio trabaja en la empresa

### Estado de Resultados (Balance 8 columnas al 31/12/2025)

| Cuenta                                            | Pérdidas            | Ganancias   |
| ------------------------------------------------- | -------------------- | ----------- |
| Ventas                                            | 0                    | 289.005.210 |
| Costos de Venta                                   | 215.000.000          | 0           |
| Depreciación Camioneta Financiera                | 1.500.000            | 0           |
| Sueldos Pagados                                   | 25.500.000           | 0           |
| Gastos Generales                                  | 8.541.000            | 0           |
| Indemnización Legal Trabajadores Despedidos 2025 | 7.500.000            | 0           |
| Arriendo Automóvil Gerente General               | 2.500.000            | 0           |
| Arriendo Casa de Verano Feb 2025                  | 1.800.000            | 0           |
| Multa por no pago Patente Municipal               | 750.000              | 0           |
| Gratificación Socio                              | 1.200.000            | 0           |
| **Resultado (Utilidad)**                    | **24.714.210** |             |

### Notas

1. CM tributaria existencias = $1.444.300 saldo **acreedor**
2. PPM actualizados 2025 = $1.200.000
3. Arriendo casa verano → beneficio del **contador externo**
4. Depreciación tributaria camioneta = $1.300.000
5. Sueldos pagados incluye $1.500.000 **adeudados** al 31/12/2025
6. Gastos Generales incluye $1.841.650 **sin documentación**
7. **Ningún socio trabaja** en la empresa

---

### ✅ RESOLUCIÓN PASO A PASO

#### PASO 1: Punto de partida → Utilidad Financiera = $24.714.210

#### PASO 2: Identificar AGREGADOS

| Partida                             | Monto                 | Fundamento                                     | Art. 21           |
| ----------------------------------- | --------------------- | ---------------------------------------------- | ----------------- |
| Depreciación Financiera            | +1.500.000            | Se reemplaza por tributaria (Art. 31 N°5)     | —                |
| CM Tributaria saldo acreedor        | +1.444.300            | Art. 32 - ganancia tributaria no contabilizada | —                |
| Gastos Generales sin documentación | +1.841.650            | Art. 31 Inc. 1 - sin acreditar                 | Inc. 1 → 40%     |
| Arriendo Automóvil Gerente         | +2.500.000            | Art. 31 Inc. 1 - automóvil no del giro        | Inc. 1 → 40%     |
| Arriendo Casa Verano (contador)     | +1.800.000            | Art. 31 - no necesario para la renta           | Inc. 1 → 40%     |
| Gratificación Socio (no trabaja)   | +1.200.000            | Art. 21 Inc. 3 - socio no trabaja              | Inc. 3 → IGC+10% |
| **Total Agregados**           | **+10.285.950** |                                                |                   |

**¿Por qué NO se agregan estas partidas?**

- **Costos de Venta** ($215M) → Gasto aceptado del giro
- **Sueldos Pagados** ($25.5M) → Gasto aceptado Art. 31 N°6 (los $1.5M adeudados están provisionados, se acepta porque están adeudados)
- **Gastos Generales** (solo la parte sin documentación se rechaza, el resto es aceptado)
- **Indemnización Legal** ($7.5M) → Gasto aceptado Art. 31 N°6 (indemnización legal a trabajadores)
- **Multa no pago Patente** ($750.000) → Se agrega PERO Art. 21 Inc. 2 → **NO paga 40%**

> ⚠️ **Sobre la multa**: Se agrega a la RLI pero según Art. 21 Inc. 2, las multas pagadas al fisco/municipalidades no pagan el impuesto único del 40%.

**Corrección - Agregar también:**

| Partida                         | Monto    | Fundamento                        | Art. 21               |
| ------------------------------- | -------- | --------------------------------- | --------------------- |
| Multa no pago Patente Municipal | +750.000 | Art. 31 - no necesario para renta | Inc. 2 → NO paga 40% |

**Total Agregados corregido** = $11.035.950

#### PASO 3: Identificar DEDUCCIONES

| Partida                          | Monto                | Fundamento                                  |
| -------------------------------- | -------------------- | ------------------------------------------- |
| Depreciación Tributaria         | -1.300.000           | Art. 31 N°5 - se deduce la real tributaria |
| Sueldos adeudados (ya incluidos) | 0                    | Ya están en el gasto, no se deducen extra  |
| **Total Deducciones**      | **-1.300.000** |                                             |

#### PASO 4: Calcular RLI

```
Utilidad Financiera:           24.714.210
(+) Agregados:                 11.035.950
(-) Deducciones:               -1.300.000
─────────────────────────────────────────
= RLI DETERMINADA:             34.450.160
```

> **Nota**: El resultado del Excel del profesor da RLI = $27.108.510 (con agregados de $3.694.300 y sin la multa como agregado). Puede variar según el criterio del profesor. **Sigue el criterio de tu profesor**.

#### PASO 5: Impuesto Único Gastos Rechazados (IVGR)

```
Gastos Art. 21 Inc. 1 (40%):
  Gastos sin documentación:    1.841.650
  Arriendo Automóvil:          2.500.000
  Arriendo Casa:               1.800.000
  ─────────────────────────────────────
  Base:                        6.141.650
  × 40% =                     2.456.660
```

#### PASO 6: Impuesto Total

```
IDPC (RLI × 27%):             7.319.298  (aprox.)
(+) IVGR 40%:                 2.456.660
(-) PPM:                      -1.200.000
─────────────────────────────────────────
= IMPUESTO CORPORATIVO:       8.575.958
```

---

## EJERCICIO 2: "Los Cables SpA" — Con Pérdida Financiera y Crédito 14E

**Empresa**: Los Cables SpA | **Giro**: Venta al por menor de cables de cobre
**Tipo**: SpA, accionista único que NO trabaja en la empresa
**Año Tributario**: 2026

### Estado de Resultados al 31/12/2025

| Cuenta                                        | Pérdidas                       | Ganancias     |
| --------------------------------------------- | ------------------------------- | ------------- |
| Ventas del Giro                               | 0                               | 1.075.414.000 |
| Indemnización Daño Moral                    | 0                               | 28.000.000    |
| Dividendos La Polar S.A.                      | 0                               | 52.000.000    |
| Costos de Venta                               | 890.000.000                     | 0             |
| Sueldos                                       | 122.000.000                     | 0             |
| IDPC                                          | 32.500.000                      | 0             |
| Imp. Timbres y Estampillas (pagaré del giro) | 1.666.000                       | 0             |
| Compra de Maquinaria                          | 105.000.000                     | 0             |
| Depreciación Financiera                      | 5.200.000                       | 0             |
| Intereses Préstamo Bancario del Giro         | 1.333.541                       | 0             |
| Repuestos Automóvil                          | 1.200.000                       | 0             |
| Arriendo Casa Ene-Dic 2025                    | 36.000.000                      | 0             |
| **Utilidad o Pérdida**                 | **39.485.541** (pérdida) |               |

### Notas

1. Indemnización daño moral → **sentencia ejecutoriada**
2. Arriendo casa → para accionista único, **NO trabaja**
3. Repuestos automóvil → auto **pertenece al accionista**
4. CM tributaria saldo acreedor = $2.500.000
5. Dentro del costo de venta hay compra automóvil para Gerente General = $32.000.000
6. Depreciación tributaria = $3.850.000
7. Se acoge al crédito 14 letra E; UF 31/12/2025 = $39.727,96

---

### ✅ RESOLUCIÓN PASO A PASO

#### PASO 1: Punto de partida → Pérdida Financiera = -$39.485.541

#### PASO 2: AGREGADOS

| Partida                               | Monto                  | Fundamento                                                           | Art. 21                                  |
| ------------------------------------- | ---------------------- | -------------------------------------------------------------------- | ---------------------------------------- |
| Compra Automóvil (en costo venta)    | +32.000.000            | Reclasificación + Art. 31 Inc. 1 (auto no del giro)                 | Inc. 3 → IGC+10% (beneficia al Gerente) |
| IDPC                                  | +32.500.000            | Art. 31 - impuesto de esta ley no es gasto                           | Inc. 2 → NO paga 40%                    |
| Compra Maquinaria                     | +105.000.000           | Activo No Corriente → reclasificación (no es gasto, es inversión) | —                                       |
| Depreciación Financiera              | +5.200.000             | Art. 31 N°5 - se reemplaza por tributaria                           | —                                       |
| Repuestos Automóvil (del accionista) | +1.200.000             | Art. 21 Inc. 3 - beneficia al accionista identificado                | Inc. 3 → IGC+10%                        |
| Arriendo Casa (del accionista)        | +36.000.000            | Art. 21 Inc. 3 - beneficia al accionista identificado                | Inc. 3 → IGC+10%                        |
| CM saldo acreedor                     | +2.500.000             | Art. 32                                                              | —                                       |
| **Total Agregados**             | **+214.400.000** |                                                                      |                                          |

#### PASO 3: DEDUCCIONES

| Partida                              | Monto                  | Fundamento                                         |
| ------------------------------------ | ---------------------- | -------------------------------------------------- |
| Indemnización Daño Moral           | -28.000.000            | Art. 17 N°1 - INR (tiene sentencia ejecutoriada)  |
| Dividendos La Polar                  | -52.000.000            | Art. 33 N°2 - ya tributaron en la sociedad fuente |
| Compra Automóvil (restar del costo) | -32.000.000            | Se sacó del costo de venta, se devuelve           |
| Repuestos Automóvil                 | -1.200.000             | Se deduce porque ya se agregó (Art. 21 Inc. 3)    |
| Arriendo Casa                        | -36.000.000            | Se deduce porque ya se agregó (Art. 21 Inc. 3)    |
| Depreciación Tributaria             | -3.850.000             | Art. 31 N°5                                       |
| **Total Deducciones**          | **-153.050.000** |                                                    |

> **NOTA IMPORTANTE sobre Art. 21 Inc. 3**: Cuando el gasto rechazado va al Inc. 3 (beneficiario identificado), se agrega Y se deduce de la RLI (efecto neutro en IDPC) porque el impuesto lo paga la persona natural, no la empresa. Esto es según el desarrollo del profesor.

#### PASO 4: RLI

```
Pérdida Financiera:          -39.485.541
(+) Agregados:              +214.400.000
(-) Deducciones:            -153.050.000
─────────────────────────────────────────
= RLI DETERMINADA:           21.864.459
```

#### PASO 5: Incentivo al Ahorro (Art. 14 Letra E)

```
50% de RLI:    21.864.459 × 50% = 10.932.230
Tope 5.000 UF: 5.000 × 39.727,96 = 198.639.800
Se usa el menor → $10.932.230

RLI FINAL:     21.864.459 - 10.932.230 = 10.932.229
```

#### PASO 6: Impuestos

```
IDPC:  10.932.229 × 27% =     2.951.702
IVGR:  32.000.000 × 40% =    12.800.000  (Art. 21 Inc. 1 - auto Gerente)
─────────────────────────────────────────
IMPUESTO CORPORATIVO:         15.751.702
```

> ⚠️ Sobre el auto del Gerente: En el desarrollo del profesor se clasifica como Art. 21 Inc. 1 y paga 40%. Pero **atención**: si el beneficiario está identificado (el Gerente General), algunos criterios lo llevan al Inc. 3. **Sigue el criterio de tu profesor**.

---

## EJERCICIO 3: "Nacimiento SpA" — El más completo

**Empresa**: Nacimiento SpA | **Giro**: Venta al por menor de insumos eléctricos
**Régimen**: Art. 14 letra A | Ningún accionista trabaja

### Resolución según el profesor

#### Utilidad Financiera = $129.480.000

#### AGREGADOS = $260.965.000

| Partida                                 | Monto       | Razón                                                                 |
| --------------------------------------- | ----------- | ---------------------------------------------------------------------- |
| Bono Vacaciones Gerente General         | 8.900.000   | No hay política general de incentivos (Nota 6) → gasto rechazado     |
| Aguinaldo Navidad accionista Luis Tapia | 5.000.000   | No trabaja en la empresa → Art. 21 Inc. 3                             |
| Factura mantención automóvil          | 5.365.000   | Auto no del giro → Art. 21 Inc. 1                                     |
| Provisión de Gastos                    | 180.000.000 | No pagado ni adeudado fehacientemente                                  |
| Pérdida Ejercicio Anterior Financiera  | 15.000.000  | Neutralizar → se reemplaza por tributaria                             |
| Compra Automóvil Usado                 | 32.000.000  | Art. 21 Inc. 3 (para gerente comercial sin relación con propietarios) |
| Intereses Crédito Compra Oficina       | 5.200.000   | Art. 31 N°1 - no del giro                                             |
| Contribuciones Pagadas 2025             | 9.500.000   | Empresa NO tiene bienes raíces a su nombre                            |

#### DEDUCCIONES = $60.165.000

| Partida                      | Monto      | Razón                                      |
| ---------------------------- | ---------- | ------------------------------------------- |
| Aguinaldo accionista         | 5.000.000  | Art. 21 Inc. 3 → sale de la RLI            |
| Mantención automóvil       | 5.365.000  | Art. 21 Inc. 1 → se puede deducir también |
| Compra Automóvil            | 32.000.000 | Art. 21 Inc. 3 → sale de la RLI            |
| Pérdida Tributaria anterior | 17.800.000 | Art. 31 N°3                                |

> **IMPORTANTE**: En este ejercicio el profesor SÍ deduce los gastos del Inc. 1 y Inc. 3, sacándolos de la base del 27%. Esto significa que esos gastos solo pagan su impuesto especial (40% o IGC+10%), no el IDPC.

#### CÁLCULO FINAL

```
Utilidad Financiera:         129.480.000
(+) Agregados:              +260.965.000
(-) Deducciones:             -60.165.000
─────────────────────────────────────────
= RLI DETERMINADA:          330.280.000

Ahorro 14E (50%):          -165.140.000
─────────────────────────────────────────
= RLI FINAL:                165.140.000

IDPC (27%):                  44.587.800
IVGR 40% ($37.365.000):     14.946.000  (mantención + gasto Art. 21 Inc. 1)
(-) PPM:                     -2.530.000
─────────────────────────────────────────
= IMPUESTO CORPORATIVO:     57.003.800
```

### 🔑 Partidas que NO se agregan ni deducen (gastos aceptados)

- Costos de Venta → del giro
- Sueldos → Art. 31 N°6
- Arriendo Local del Giro → necesario para la renta
- Intereses por mayor plazo proveedores → del giro
- Cuota anual leasing camión del giro → gasto aceptado
- Depreciación acelerada leasing → aceptada
- Depreciación tributaria automóvil ($560.000) → **NO se deduce** porque el auto no es activo aceptado

---

## EJERCICIO 4: "Frutillar Limitada" — Sociedad de Personas

**Empresa**: Frutillar Ltda. | **Giro**: Fábrica de plásticos
**Tipo**: Sociedad de personas, 4 socios que NO trabajan

### Datos clave

- Utilidad del Ejercicio: $235.379.367
- Gastos de puesta en marcha: cuotas 5 y 6 (de 6), $3.500.000 c/u
- Depreciación financiera 10 años vs tributaria 7 años (SII)
- CM tributaria saldo deudor $1.780.260
- Pérdidas acumuladas AT 2024, utilidad AT 2025 = $13.800.000
- Castigo clientes incobrables: 70% cumple requisitos, 30% no
- Honorarios: boleta 240 por $3.500.000 servicios legales a los socios
- Gastos generales: $1.800.000 con guía de despacho (no factura)
- Contribuciones: $2.600.000 + multas $170.000
- Donación al club de ajedrez de la junta de vecinos: $17.000.000
- Gastos medioambientales: $5.210.000
- Préstamo al jefe de RRHH: $5.200.000
- Compra camioneta 01/01/2025: $28.000.000
- Gastos publicidad: aviso en El Mercurio por venta automóvil de la sociedad
- Se acoge a crédito 14 letra E

### Análisis de partidas complejas

**Castigo clientes incobrables ($10.000.000)**:

- 70% cumple requisitos (>365 días o agotados medios) = $7.000.000 → aceptado
- 30% NO cumple = $3.000.000 → se AGREGA

**Gastos puesta en marcha ($7.000.000)**:

- Corresponde a cuotas 5 y 6 de 6 → gasto aceptado en este ejercicio (Art. 31 N°9)
- Si correspondiera a cuotas futuras → se agregaría

**Donaciones ($17.000.000)**:

- Club de ajedrez de junta de vecinos → NO cumple requisitos Art. 31 N°7
- Se AGREGA como gasto rechazado

**Honorarios socios ($3.500.000)**:

- Servicios legales a los socios → beneficia a los socios → Art. 21 Inc. 3

**Gastos generales con guía de despacho ($1.800.000)**:

- La guía de despacho NO es documento tributario válido → sin documentación → Art. 21 Inc. 1

**Contribuciones + multas**:

- Contribuciones $2.600.000 → gasto aceptado (si tiene bienes raíces)
- Multas $170.000 → Art. 21 Inc. 2 (no paga 40%)

**Préstamo jefe RRHH ($5.200.000)**:

- NO es socio → no aplica Art. 21 Inc. 3
- Es un activo (cuenta por cobrar), no un gasto → se AGREGA y reclasifica

**Gastos publicidad - venta automóvil**:

- Venta de activo propio → gasto aceptado del proceso de venta

**Depreciación camioneta**:

- Financiera: 28.000.000/10 = 2.800.000
- Tributaria: 28.000.000/7 = 4.000.000
- Se agrega financiera (+2.800.000) y se deduce tributaria (-4.000.000)

**Mejoras a máquina ($5.210.000)**:

- Aumenta vida útil → se capitaliza (activo fijo) → se AGREGA

**CM saldo deudor**: se DEDUCE

---

## EJERCICIO 5: Sociedad de Personas — Construcción

**Empresa**: Sin nombre | **Giro**: Construcción
**Tipo**: Sociedad de personas, 2 socios 50% c/u, NO trabajan

### Datos clave

- Utilidad: $1.885.099.882
- PPM 2025: $5.100.000
- UF 31/12/2025: $39.727,96
- Crédito 14 letra E

### Partidas principales

| Cuenta                         | Monto         | Tratamiento                                  |
| ------------------------------ | ------------- | -------------------------------------------- |
| Ventas                         | 3.950.000.000 | Ingreso normal                               |
| CM (ganancia)                  | 78.000.000    | Ya en resultados, verificar vs tributaria    |
| Dividendos Banco Chile         | 35.000.000    | DEDUCIR Art. 33 N°2                         |
| Indemnización Daño Emergente | 25.000.000    | Seguro excavadora → gasto/ingreso normal    |
| Costo Ventas                   | 780.000.000   | Aceptado (insumos ferretería $180M dentro)  |
| Remuneraciones                 | 856.201.540   | Verificar                                    |
| Honorarios                     | 78.000.000    | 50% sin soporte → Art. 21 Inc. 1 ($39M)     |
| Gastos Medioambientales        | 48.000.000    | Tope 2% RLI → calcular                      |
| Gastos Alimentación sin doc   | 85.000.000    | Art. 21 Inc. 1 → 40%                        |
| Depreciación Tributaria       | 12.698.578    | Ya contabilizada correctamente               |
| Gastos Generales               | 22.500.000    | $3.350.000 con boletas electrónicas         |
| Gastos Bancarios               | 1.250.000     | Aceptado                                     |
| Intereses y Multas no del giro | 52.000.000    | Art. 21 Inc. 1 → 40%                        |
| Arriendos                      | 65.000.000    | Máquina niveladora sin factura → rechazado |
| Insumos Ferretería (en costo) | 180.000.000   | Verificar si tiene factura                   |
| Fletes cambio casa socios      | 12.000.000    | Art. 21 Inc. 3 → IGC+10%                    |
| Peajes                         | 8.900.000     | Con factura, camioneta empresa → aceptado   |
| Seguro                         | 1.350.000     | Auto área cobranzas → Art. 21 Inc. 1       |

**Gastos Medioambientales**: Primero calcular RLI sin este ajuste, luego verificar si $48M < 2% de RLI. Si excede, el exceso se agrega.

---

## 🧠 REGLAS DE ORO PARA LA PRUEBA

### 1. Siempre pregúntate: ¿Este gasto es NECESARIO para producir la renta?

- Si NO → se rechaza (agregar)
- Si SÍ → se acepta (no tocar)

### 2. ¿Tiene documentación válida?

- Factura ✅ | Boleta ✅ | Contrato ✅
- Guía de despacho ❌ | Sin documento ❌

### 3. ¿Quién se beneficia?

- La empresa → Art. 21 Inc. 1 (40%)
- Socio/accionista identificado → Art. 21 Inc. 3 (IGC+10%)
- Es impuesto/multa fiscal → Art. 21 Inc. 2 (no paga)

### 4. Depreciación: SIEMPRE hacer el swap

- (+) Agregar la financiera
- (-) Deducir la tributaria

### 5. CM Tributaria

- Saldo acreedor (ganancia) → AGREGAR
- Saldo deudor (pérdida) → DEDUCIR

### 6. Pérdida de ejercicios anteriores

- (+) Agregar la FINANCIERA (neutralizar)
- (-) Deducir la TRIBUTARIA (Art. 31 N°3)

### 7. Provisiones → SIEMPRE se agregan (no están pagadas ni adeudadas)

### 8. Compra de activo fijo contabilizada como gasto → AGREGAR (reclasificación)

### 9. Dividendos/Retiros de otras sociedades → SIEMPRE deducir (Art. 33 N°2)

### 10. Indemnización daño moral con sentencia → DEDUCIR (Art. 17 N°1 INR)

---

## ⚡ CHECKLIST RÁPIDO PARA LA PRUEBA

Antes de entregar, verifica:

- [ ] ¿Partí del resultado financiero correcto?
- [ ] ¿Agregué la depreciación financiera Y deduje la tributaria?
- [ ] ¿Traté correctamente la corrección monetaria?
- [ ] ¿Identifiqué TODOS los gastos rechazados?
- [ ] ¿Clasifiqué correctamente entre Inc. 1, Inc. 2 e Inc. 3?
- [ ] ¿Deduje dividendos/participaciones de otras sociedades?
- [ ] ¿Deduje ingresos no renta (indemnizaciones con sentencia)?
- [ ] ¿Apliqué el incentivo al ahorro 14E correctamente?
- [ ] ¿Calculé el 40% sobre los gastos Art. 21 Inc. 1?
- [ ] ¿Resté los PPM actualizados?

**¡Éxito en tu prueba! 💪🎓**
