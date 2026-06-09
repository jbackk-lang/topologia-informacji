# Topologia Informacji — Model 2.1

Topologia Informacji to formalny model opisujący ruch, transformację i stabilność informacji
w ujęciu topologicznym. Model 2.1 zawiera pełny zestaw jednostek, operatorów, reguł oraz
warunków stabilności, a także sprzężenie zwrotne φ.

---

## 🔷 Jednostki

- **I** — informacja (ruch)
- **S** — kształt
- **T** — transformacja globalna
- **Tw** — skręt lokalny
- **ΔS** — różnica kształtu z progiem
- **N** — napięcie
- **R** — rezonans
- **Ø** — zero topologiczne
- **Λ** — amplituda zmiany
- **τ** — orientacja czasowa
- **ρ** — gęstość informacyjna
- **φ** — sprzężenie zwrotne

/applications/
    ├── text-analysis.md
    ├── ai-diagnostics.md
    ├── overload-detection.md
    ├── stability-engineering.md
    ├── semantic-topology.md
    └── timdr-real-world.md


---

## 🔷 Operatory

- `I → S`
- `T(I, Λ)`
- `Tw(I, Λ)`
- `ΔS(ρ, ρ*)`
- `S↻(τ)`
- `S↺`
- `S ⊗ S`
- `Res(S₁, S₂)`
- `φ(S)`
- `N`
- `Ø`

---

## 🔷 Reguły

- **R1–R7** — reguły podstawowe
- **R8** — skala zmienia klasę topologiczną
- **R9** — orientacja czasowa określa trajektorię
- **R10** — gęstość decyduje o stabilności cyklu

---

## 🔷 Warunki stabilności

- `Λ_eff = Λ · τ`
- `ρ < ρ_krytyczne`
- `|ρ₁ – ρ₂| > ρ*` dla aktywacji ΔS

---

## 🔷 Zawartość repo

- `/axioms` — reguły i warunki stabilności
- `/operators` — definicje operatorów
- `/filter` — wersje filtra (2.0, 2.1, 2.2)
- `/mapping` — mapowanie topologii na architekturę AI i odwrotnie
- `/examples` — przykłady zastosowań (torus-Möbius, TIMDR)

---
## Reguła ρ/ΔS → sprawdzanie założeń

**R10. (Diagnoza założeń)**  
Jeśli w analizie problemu:

- współczynnik gęstości ρ rośnie monotonicznie,
- albo różnica kształtu ΔS rośnie w kolejnych krokach,

to:

1. Najpierw badamy **założenia problemu** (modelu, równania, funkcji),
2. Dopiero potem szukamy „lepszego dowodu” lub „sprytniejszej techniki”.

Innymi słowy:

> Wzrost ρ lub ΔS jest sygnałem, że **diabeł siedzi w założeniach**,  
> a nie w rachunku.

---

## 🔷 Licencja

MIT
