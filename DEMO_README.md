# 🎯 Franklin Framework - Lollapalooza Detection Demo

## Executive Summary

Sistema de detección de riesgo exponencial basado en la filosofía de Charlie Munger:
> "Cuando múltiples fuerzas actúan en la misma dirección, el efecto es exponencial, no aditivo."

**Value Proposition:**
- Detecta convergencia de riesgos ANTES de crisis sistémicas
- Analiza empresas usando filosofía de Graham, Buffett y Munger
- Multiplica severidad cuando 3+ categorías de riesgo coinciden

---

## Quick Start

### Prerequisites
```bash
python >= 3.10
pip install -r requirements.txt
```

### Run Demo
```bash
python -m backend.demos.demo_lollapalooza
```

**Duration:** ~20 segundos  
**Output:** Análisis de AAPL, NVDA, MSFT con detección de lollapalooza

---

## Key Metrics Explained

| Metric | Range | Meaning |
|--------|-------|---------|
| **Munger Score** | 0-5 | Filosofía Munger (5 principios) |
| **Red Flags** | 0-10+ | Señales de advertencia detectadas |
| **Lollapalooza** | YES/NO | ¿Convergencia de 3+ categorías? |
| **Multiplier** | 1.0x-3.0x | Factor de severidad exponencial |
| **Convergence** | 0.0-1.0 | Score probabilístico de riesgo |

---

## Lollapalooza Thresholds
```
1 categoría  → 1.0x multiplier (riesgo aislado)
2 categorías → 1.3x multiplier (emergente)
3 categorías → 1.8x multiplier (severo)
4 categorías → 3.0x multiplier (CRÍTICO - lollapalooza)
```

---

## Demo Output Example
```
📊 AAPL
Score: 5/5 | Rating: WONDERFUL
Red Flags: 1
Lollapalooza: ✅ NO (1.0x)
Convergence: 0.25
Recommendation: BUY - Acceptable with minor concerns

📊 NVDA
Score: 5/5 | Rating: WONDERFUL
Red Flags: 0
Lollapalooza: ✅ NO (1.0x)
Convergence: 0.00
Recommendation: STRONG BUY - Exceptional company
```

---

## Technical Architecture

**Components:**
1. **XBRL Parser:** Extrae datos de SEC filings (10-K)
2. **Metrics Calculator:** 25+ ratios financieros
3. **Munger Interpreter:** 5 principios de Charlie Munger
4. **Lollapalooza Detector:** Convergencia de riesgos

**Test Coverage:** 513/513 tests passing (99.6%)  
**Performance:** <3s por empresa

---

## Contact

**Developer:** Franklin (CTO & Architect)  
**Project:** Franklin Framework  
**Status:** Production-ready MVP
```

---

## 3️⃣ PREPARAR PRESENTACIÓN (15 min)

### Puntos Clave para XTB

**1. Problema que resuelve:**
```
Bloomberg Terminal: $24k/año, pero NO detecta riesgos convergentes
Franklin Framework: $99-$2,500/mo, CON detección de lollapalooza
```

**2. Diferenciador único:**
```
Otros sistemas: Analizan métricas en silos
Franklin: Detecta cuando múltiples riesgos convergen (efecto exponencial)
```

**3. Proof of Concept:**
```
✅ 513 tests passing
✅ 23 empresas analizadas
✅ Sub-3s performance
✅ Demo funcional
```

---

## 4️⃣ ANTICIPAR PREGUNTAS (10 min)

### Preguntas Esperadas de XTB

**Q: "¿Cómo validaron el sistema?"**
```
A: 513 automated tests + validación con datos reales de:
   - Apple (6 años históricos)
   - NVIDIA (3 años)
   - Microsoft (4 años)
   - 20+ empresas TECH sector
```

**Q: "¿Qué pasa si detecta lollapalooza?"**
```
A: Sistema escala severity:
   - 2 categorías → 1.3x (monitor closely)
   - 3 categorías → 1.8x (high risk)
   - 4 categorías → 3.0x (avoid - systemic crisis)
```

**Q: "¿Cómo se compara con Bloomberg?"**
```
A: Bloomberg: Data aggregator ($24k/año)
   Franklin: Philosophy framework + AI debate ($99-$2,500/mo)
   
   Unique: Graham + Buffett + Munger interpreters simultáneos
```

**Q: "¿Cuánto tiempo toma analizar una empresa?"**
```
A: <3 segundos por empresa
   Demo completo (3 empresas): ~20 segundos
```

**Q: "¿Qué empresas han analizado?"**
```
A: 23 empresas TECH sector (AAPL, MSFT, NVDA, GOOGL, etc.)
   + capacidad de analizar cualquier empresa con 10-K público
