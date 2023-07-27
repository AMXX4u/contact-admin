<div align="center">

## Contact with Administration (Contact)

<img src="https://raw.githubusercontent.com/AMXX4u/contact-admin/main/assets/contact.png"></img>

</div>

<p align="center">
  <a href="#requirements">Wymagania ℹ</a> ×
  <a href="#description">Opis 📄</a> ×
  <a href="#configure">Konfiguracja 🛠</a> ×
  <a href="#screenshots">Screenshot 📷</a>
</p>

---

### Description 
- Kontakt z administracją serwera w MOTD bądź menu
- Po wpisaniu `/kontakt` plugin pokazuję MOTD / Menu, w którym można zobaczyć adminów oraz dodatkowe szczegóły po kliknięciu
- Kontakt pokazuję dodatkowo status adminów, tzn. status online / offline
- Kontakt również oferuję opcje drukowania administracji oraz dodatkowych informacji w konsoli
- Kontakt można konfigurować dowolnie za pomocą cvarów
- Kontakt posiada opcje wyświetlania avatarów adminów w MOTD (ustawiamy przez config)

### Configure
<details>
  <summary><b>amxx.cfg</b></summary>

```cfg
// Pokazywać wszystkich adminów w konsoli gracza?
amxx4u_contact_console "1"

// Gdzie pokazywać administracje? (Menu - 0 | MOTD - 1 | 2 - Menu jako glowne, motd opcjonalne (wyswietlana opcja w menu)
amxx4u_contact_show_type "2"

// Gdzie pokazywać informacje o wydrukowanych adminach? 0 - wyłączone | 1 - Chat | 2 - Konsola | 3 - Konsola oraz chat
amxx4u_contact_info "1"

// Pokazywać forum w wydrukowanej liście adminów?
amxx4u_contact_show_board "1"

// Jaką nazwę forum wyświetlać w wydrukowanej liście adminów?
amxx4u_contact_board "AMXX4u.pl"

// Pokazywać zaproszenie do Discord'a w wydrukowanej liście adminów?
amxx4u_contact_show_discord "1"

// Jakie zaproszenie wyświetlać w wydrukowanej liście adminów?
amxx4u_contact_discord "https://discord.amxx4u.pl/"

// Pokazywać IP TS3 w konsoli?
amxx4u_contact_show_ts3 "1"

// Jaka IP ma być wyświetlane w konsoli?
amxx4u_contact_ts3 "ts3.katujemy.eu"

```
</details>

<details>
  <summary><b>contact.ini</b></summary>

```ini

; Poniżej znajduję sie przykład dodawania nowego admina do kontaktu.
; Steam - Najlepiej podawać nick ze steam, nie link do profilu.
; "Avatar" "Nick" "Discord#0000" "Steam" "Ranga"

"https://i.imgur.com/ZR87aq7.png" "AMXX4ua" ".pawel_" "AMXX4u" "Wlasciciel" 
"https://i.imgur.com/6IYyxrx.png" "u4XXMA" ".pawel_" "AMXX4u" "Opiekun"

```
</details>

### Screenshots

<details>
  <summary><b>Contact</b></summary>

- MOTD

  <img src="https://raw.githubusercontent.com/AMXX4u/contact-admin/main/assets/motd_v2.png"></img>

- Menu

  <img src="https://raw.githubusercontent.com/AMXX4u/contact-admin/main/assets/menu.png"></img>

- Console

  <img src="https://raw.githubusercontent.com/AMXX4u/contact-admin/main/assets/console_v2.png"></img>

- Chat

  <img src="https://raw.githubusercontent.com/AMXX4u/contact-admin/main/assets/chat_v2.png"></img>
</details>

### Requirements 
- AMXModX 1.9 / AMXModX 1.10
