# 🏗️ FABAD-BETON™ – Wielojęzyczna Witryna Firmowa

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Flowbite](https://img.shields.io/badge/Flowbite-1A56DB?style=for-the-badge&logo=flowbite&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

Wielojęzyczna (Polski / Czeski), nowoczesna strona internetowa stworzona dla betoniarni **FABAD-BETON™** z siedzibą w Bogatyni. Witryna prezentuje pełną ofertę firmy – produkcję betonu, produkcję prefabrykatów (klocki LEGO, płyty drogowe), handel stalą oraz wynajem minikoparki.

---

## ✨ Główna Funkcjonalność

- **🌍 Wielojęzyczność (PL / CZ):** Pełna obsługa języka polskiego i czeskiego z dedykowanymi podstronami (`index.html` / `indexCZ.html`).
- **🌙 Tryb Ciemny / Jasny (Dark / Light Mode):** Przełącznik motywu z zapamiętywaniem wyboru użytkownika (`localStorage`) i automatyczną detekcją preferencji systemowych.
- **📱 Pełna Responsywność (RWD):** Dedykowany układ i funkcjonalne menu mobilne dopasowane do smartfonów, tabletów i komputerów.
- **📊 Interaktywny Cennik & Specyfikacja:** Tabela techniczna minikoparki wraz z cennikiem wynajmu.
- **🖼️ Karuzela Realizacji:** Dynamiczna galeria prezentująca park maszynowy oraz ukończone projekty.
- **🗺️ Integracja z Google Maps:** Interaktywny moduł ułatwiający dojazd do siedziby firmy przy ul. Lipowej 2 w Bogatyni.

---

## 🛠️ Stos Technologiczny (Tech Stack)

- **Frontend:** HTML5, CSS3, JavaScript (Vanilla JS)
- **Stylizowanie & UI:** [Tailwind CSS](https://tailwindcss.com/), [Flowbite UI](https://flowbite.com/)
- **Animacje:** GSAP (GreenSock Animation Platform) + ScrollTrigger
- **Typografia & Ikony:** Google Fonts (Roboto), FontAwesome / SVG Icons
- **Inne:** Google Maps API / Embed

---

## 📁 Struktura Projektu

```text
├── assets/
│   ├── css/           # Pliki stylów / kompilacja Tailwind
│   ├── js/            # Skrypty JS (motyw, nawigacja, przełącznik języka)
│   └── img/           # Zdjęcia realizowane, zdjęcia maszyn i logo
├── index.html         # Strona główna (PL)
├── indexCZ.html       # Strona główna (CZ)
├── index2.html        # Wynajem Minikoparki (PL)
├── index2CZ.html      # Wynajem Minikoparki (CZ)
├── index3.html        # Kontakt & Mapa (PL)
├── index3CZ.html      # Kontakt & Mapa (CZ)
└── README.md          # Dokumentacja projektu
