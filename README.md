# CMJ Force Plate Dashboard
### Víctor Garrido — Ciencias del Deporte · Fuerza y Condicionamiento

## 🚀 [Abrir la aplicación](https://vgarrido1995.github.io/cmj-dashboard/)

> **Accede directo desde el navegador, sin instalar nada:** [https://vgarrido1995.github.io/cmj-dashboard/](https://vgarrido1995.github.io/cmj-dashboard/)

---

Herramienta de monitoreo neuromuscular basada en z-score individual para entrenadores y científicos del deporte.

## Métricas soportadas
- **CMJ:** Altura del salto, Impulso propulsivo, RSI-mod, RSI clásico, Peak force
- **IMTP:** Peak force isométrica
- **RFD:** RFD máx, RFD temprana (0–100 ms), RFD tardía (100–200 ms), RFD a 150 ms

## Uso rápido
1. Abrir `index.html` en el navegador (no requiere servidor)
2. Crear atleta en "Ingreso de datos"
3. Ingresar valores de la sesión (uno o múltiples separados por coma)
4. Ver z-score y semáforo en tiempo real

## Decisiones basadas en z-score
| z-score | Significado | Acción |
|---|---|---|
| ≥ +1.5 | Excepcional | Potenciar carga |
| +0.5 a +1.4 | Por encima del promedio | Mantener |
| −0.9 a +0.4 | Rango normal | Programa previsto |
| −1.0 a −1.4 | Leve descenso | Monitorear |
| −1.5 a −1.9 | Descenso significativo | Reducir carga |
| ≤ −2.0 | Caída severa | Comunicar al médico |

## Referencias
- Gathercole et al. (2015). IJSPP 10(1):84-92.
- Claudino et al. (2017). J Sci Med Sport 20(4):397-402.
- Bourdon et al. (2017). IJSPP 12(Suppl 2):S2161.
- Hopkins (2000). Sports Med 30(1):1-15.

## Datos
Los datos se guardan localmente en el navegador (localStorage). Usar "Exportar JSON" para backup.
