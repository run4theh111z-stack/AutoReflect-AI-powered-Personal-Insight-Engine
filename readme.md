# 🧾 AutoReflect – AI-powered Personal Insight Engine

Projekt automatyzacji autorefleksji i analizy mocnych/słabych stron z wykorzystaniem OpenAI GPT i Make.com

---

## 🧠 Na czym polega projekt?

AutoReflect to zautomatyzowany system dziennika rozwojowego:

1. Użytkownik wysyła wiadomość startową przez **Telegram** (np. informację o przebiegu dnia)
2. **Make.com** analizuje wiadomość i wyodrębnia potencjalne problemy, cele i emocje
3. Dane trafiają do **dziennika w Notion** (API)
4. Następnie **ChatGPT** przeszukuje zbiory wiedzy (prompt + context) i generuje możliwe **rozwiązania** i **rekomendacje**
5. System przesyła podsumowanie, wskazówki oraz źródła wiedzy z powrotem na Telegramie

---

## ⚙️ Użyte technologie

-

---

## 💬 Przykładowy flow

### Wejście:

```
"Dziś byłem bardzo nieproduktywny. Przeglądałem media społecznościowe, miałem trudności ze skupieniem, nie skończyłem zaplanowanych zadań."
```

### System wykonuje:

- Klasyfikację emocji i celów
- Wpis do Notion
- Generowanie rekomendacji
- Zwrotka przez Telegram

### Wynik:

```
🧠 Podsumowanie: brak skupienia i utrata kontroli nad czasem
✅ Rekomendacja: ogranicz czas ekranowy, zaplanuj 2x pomodoro rano
🔗 Źródło: "Atomic Habits", link do artykułu o dopaminie i produktywności
```

---

## 🖼️ Screenshoty

### 🔁 Scenariusz w Make.com



### 💬 Przykładowy dialog w Telegramie



### 📒 Wpis w Notion



---

## 📌 Status projektu

Projekt działa jako MVP (Minimum Viable Product) i jest używany do codziennej refleksji. Planowane rozszerzenia:

- Dodanie harmonogramu dziennych przypomnień (CRON)
- Lepsze szablony promptów i personalizacja reakcji
- Eksport do PDF i wykresy produktywności

---

## 👤 Autor

Michał Kowalewski\
🌐 [https://github.com/run4theh111z-stack](https://github.com/run4theh111z-stack)

---

## 📜 Licencja

Projekt edukacyjny / MVP\
© 2025 Michał Kowalewski. Do użytku niekomercyjnego.

