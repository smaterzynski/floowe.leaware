# Event Storming: AS-IS (Stan Bieżący)

## Przegląd

Ten dokument przedstawia kluczowe wydarzenia i procesy w obecnej aplikacji Floowe.

## Kluczowe Procesy

### 1. Onboarding

**Wydarzenia:**
- **Konto Założone**
  - Actor: Użytkownik
  - Command: Załóż Konto
  - Trigger: Użytkownik chce rozpocząć korzystanie
  - Data: Email, hasło, nazwa firmy, branża, grupa docelowa
  - Aggregates: User Profile, Company Settings
  - Policies: Wyślij email weryfikacyjny, Utwórz domyślne ustawienia

- **Integracje Skonfigurowane**
  - Actor: Użytkownik
  - Command: Skonfiguruj Integracje
  - Trigger: Użytkownik łączy zewnętrzne platformy
  - Data: WordPress plugin, tokeny social media
  - Aggregates: Integration Settings, Connected Platforms
  - Policies: Zweryfikuj połączenia, Zapisz tokeny

### 2. Content Creation

**Wydarzenia:**
- **Pomysły na Artykuły Wygenerowane**
  - Actor: System AI
  - Command: Wygeneruj Pomysły
  - Trigger: Użytkownik żąda nowych pomysłów
  - Data: Lista tematów, trendy branżowe, słowa kluczowe
  - Aggregates: Content Ideas, SEO Analysis, Trending Topics
  - Policies: Analizuj konkurencję, Oceń potencjał SEO

- **Artykuł Utworzony**
  - Actor: System AI
  - Command: Utwórz Artykuł
  - Trigger: Użytkownik wybiera pomysł
  - Data: Tytuł, treść, nagłówki, słowa kluczowe
  - Aggregates: Article, SEO Metadata, Content Structure
  - Policies: Wplecenie słów kluczowych, Generuj posty SM

- **Artykuł Zedytowany**
  - Actor: Użytkownik
  - Command: Edytuj Artykuł
  - Trigger: Użytkownik modyfikuje treść
  - Data: Zmieniony tekst, wybrane grafiki
  - Aggregates: Article Draft, Media Gallery
  - Policies: Zapisz wersję roboczą, Zachowaj historię

### 3. Distribution

**Wydarzenia:**
- **Treść Opublikowana**
  - Actor: Użytkownik/System
  - Command: Opublikuj Treść
  - Trigger: Użytkownik klika 'Publikuj' LUB Zaplanowana publikacja
  - Data: Artykuł, posty SM, wybrane kanały
  - Aggregates: Published Content, Distribution Queue
  - Policies: Wyślij do WordPress, Postuj na social media

### 4. Analytics

**Wydarzenia:**
- **Statystyki Zaktualizowane**
  - Actor: System
  - Command: Śledź Wydajność
  - Trigger: Ciągły monitoring ruchu
  - Data: Ruch na stronie, pozycje w wyszukiwarkach, engagement
  - Aggregates: Analytics Dashboard, SEO Performance
  - Policies: Aktualizuj dashboard, Generuj raporty

## Systemy Zaangażowane

- Auth Service
- User Database
- Integration Manager
- AI Content Generator
- SEO Engine
- Publishing Engine
- Analytics Module

## Integracje Zewnętrzne

- WordPress API
- Facebook API
- LinkedIn API
- Twitter API
- Google Trends API
- OpenAI API
- Unsplash API
