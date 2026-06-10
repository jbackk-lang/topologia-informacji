# Topologia Informacji — Model 2.1  
### Formalny model ruchu, transformacji i stabilności informacji  
(oparty na jednostkach, operatorach, regułach i sprzężeniu zwrotnym φ)

Topologia Informacji 2.1 to kompletny model opisujący **jak informacja porusza się, zmienia, skręca, rezonuje i stabilizuje się** w przestrzeni topologicznej.  
Model definiuje pełny zestaw **jednostek**, **operatorów**, **reguł**, **warunków stabilności** oraz **sprzężenie zwrotne φ** .

---

## 1. Jednostki (alfabet topologiczny)

Model używa 13 jednostek opisujących różne aspekty informacji:

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


---

## 2. Operatory

Model definiuje operatory przekształcające informację:

- **I → S**  
- **T(I, Λ)**  
- **Tw(I, Λ)**  
- **ΔS(ρ, ρ\*)**  
- **S↻(τ)**  
- **S↺**  
- **S ⊗ S**  
- **Res(S₁, S₂)**  
- **φ(S)**  
- **N**, **Ø**  


Każdy operator zmienia klasę topologiczną, orientację, gęstość lub stabilność.

---

## 3. Reguły (R1–R10 + rozszerzenia)

- **R1–R7** — reguły podstawowe  
- **R8** — skala zmienia klasę topologiczną  
- **R9** — orientacja czasowa określa trajektorię  
- **R10** — gęstość decyduje o stabilności cyklu  


Dodatkowo repo zawiera:

### **R15 — Zakaz mnożenia nieskończoności**  
Nieskończoność **jest unikalna** i nie może być kopiowana ani rozszczepiana na ∞₁, ∞₂, ∞₃  
.

Duplikacja ∞ niszczy brzeg kierunkowy i spójność przestrzeni  
.

---

## 4. Warunki stabilności

Model definiuje trzy kluczowe warunki:

- **Λ_eff = Λ · τ**  
- **ρ < ρ_krytyczne**  
- **|ρ₁ – ρ₂| > ρ\*** dla aktywacji ΔS  


To pozwala wykrywać stabilne i niestabilne cykle informacji.

---

## 5. Reguła ρ/ΔS — diagnoza założeń

Jeśli w analizie problemu:

- **ρ rośnie monotonicznie**, albo  
- **ΔS rośnie w kolejnych krokach**,  

to problem leży **w założeniach**, a nie w rachunku  
.

> „Wzrost ρ lub ΔS jest sygnałem, że diabeł siedzi w założeniach.”  


---

## 6. Zawartość repozytorium

```
/axioms      — reguły i warunki stabilności
/operators   — definicje operatorów
/filter      — wersje filtra (2.0, 2.1, 2.2)
/mapping     — mapowanie topologii na architekturę AI
/examples    — przykłady (torus–Möbius, TIMDR)
```


---

## 7. Powiązania z innymi modelami

- **TIMDR** — topologia informacji → dynamika czasu i rezonansu  
- **FIELDCORE** — pole i rezonanse → fizyczna interpretacja operatorów  
- **fundamental‑ai‑model** — mapowanie topologii na architekturę AI  
- **MAPA‑PO‑HELU** — struktura materii jako zastosowanie operatorów i reguł  

---

## 8. Licencja

MIT License  

