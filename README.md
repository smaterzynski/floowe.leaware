# Floowe – Analiza Produktu, Event Storming i Specyfikacja Funkcjonalności  
## Zadanie Techniczne – Techniczny PM / Business Analyst (AI & Automation)

---

## 📌 Cel Zadania
Analiza produktu Floowe (https://floowe.com), identyfikacja kluczowych procesów, przygotowanie Event Stormingu AS-IS/TO-BE oraz zaprojektowanie nowych funkcjonalności z kompletną specyfikacją.

---

# 🧩 KROK 1 — Analiza Aplikacji Floowe

## 🔥 Podstawowa wartość
Floowe to platforma SaaS automatyzująca tworzenie i dystrybucję treści marketingowych** w oparciu o AI.  
Pomaga firmom oraz osobom zajmującym się pozycionowaniem i copywritingiem poprawiać widoczność w Google, generować ruch organiczny i prowadzić spójną komunikację w social media.

---

## 🎯 Co rozwiązuje?
- brak czasu na regularne pisanie treści,
- brak wiedzy SEO,
- brak zasobów do prowadzenia bloga i social media,
- potrzeba spójnej komunikacji wielokanałowej obsługiwanej z jednego miejsca ( brak rozproszonych systemów i wielokrotnego logowania )

---

## 🛠️ Kluczowe funkcjonalności
- Generowanie artykułów SEO (LLM)
- Generowanie postów social media z artykułów
- Edytor WYSIWYG
- Generowanie/wybór grafik (AI/stock/upload)
- Publikacja na blogu (WordPress/Webflow/API)
- Publikacja w social media (FB/X/LinkedIn)
- Dashboard analityczny (traffic, keyword positions, channels)
- Automatyzacja całego procesu tworzenia treści

---

## 👥 Grupa docelowa
- MŚP prowadzące działania SEO i social media,
- marketing managerowie,
- agencje marketingowe,
- firmy usługowe, SaaS, e-commerce, 'pozycjonerzy' ;) 

---

## 💸 Model biznesowy
SaaS subscription z 14-dniowym trialem.
Prawdopodobne progi:
- liczba treści/miesiąc,
- liczba kanałów social,
- liczba użytkowników,
- integracje premium.

---

## 🎨 UX/UI – obserwacje
- jasne CTA, value-first messaging,
- pattern „3-step guided flow”,
- dashboard-style UI,
- karty analityczne, wykresy, statystyki,
- sekcja social proof i use cases.

---

## 🔌 Potencjalne integracje
- CMS: WordPress, Webflow, custom API,
- Social: Meta, LinkedIn, X,
- Analytics: Google Analytics, Search Console,
- AI: LLM (Claude/GPT), image generation API.

---

# 🧩 KROK 2 — Kluczowe przepływy użytkownika

### 1) Rejestracja i onboarding 
- konto (email/SSO),
- konfiguracja firmy, języka, rynku,
- integracje CMS/social (opcjonalnie).

### 2) Generowanie artykułu SEO
- brief → draft AI → edycja → zatwierdzenie → publikacja.

### 3) Generowanie social postów
- AI generuje posty → edycja → harmonogram → publikacja.

### 4) Publikacja artykułu na stronie
- publikacja przez REST API → zapis statusu → link do posta.

### 5) Analiza wyników
- pobieranie GA/GSC,
- wykresy: traffic, keywords, channels,
- rekomendacje iteracyjne.

---

