<div align="center">

## Contact with Administration (Contact)

<img src="https://raw.githubusercontent.com/AMXX4u/contact-admin/main/assets/main.png?token=GHSAT0AAAAAAB4BEINDX4PWVMUD4KM7PTBOY5WG2WQ"></img>

</div>

<p align="center">
  <a href="#requirements">Wymagania ℹ</a> ×
  <a href="#description">Opis 📄</a> ×
  <a href="#configure">Konfiguracja 🛠</a> ×
  <a href="#screenshots">Screenshot 📷</a>
</p>

---

### Description 
- Kontakt z administracją serwera w MOTD
- Po wpisaniu `/kontakt` plugin pokazuję MOTD, w którym można zobaczyć adminów
- Kontakt pokazuję dodatkowo status adminów, tzn. status online / offline

### Configure
<details>
  <summary><b>amxx.cfg</b></summary>

```cfg
// Pokazywać wszystkich adminów w konsoli gracza?
amxx4u_contact_console "1"

// Pokazywać informację na czacie dla gracza, że lista adminów została wydrukowana w konsoli?
amxx4u_contact_chat "1"

// Pokazywać forum w wydrukowanej liście adminów?
amxx4u_contact_show_board "1"

// Jaką nazwę forum wyświetlać w wydrukowanej liście adminów?
amxx4u_contact_board "AMXX4u.pl"

// Pokazywać zaproszenie do Discord'a w wydrukowanej liście adminów?
amxx4u_contact_show_discord "1"

// Jakie zaproszenie wyświetlać w wydrukowanej liście adminów?
amxx4u_contact_discord "https://discord.amxx4u.pl/"

```
</details>

<details>
  <summary><b>contact.ini</b></summary>

```ini

; Poniżej znajduję sie przykład dodawania nowego admina do kontaktu.
; Steam - Najlepiej podawać nick ze steam, nie link do profilu.
; "Nick" "Discord#0000" "Steam" "Ranga"

"AMXX4u" "Paweł#8547" "AMXX4u" "Właściciel"
"Pawel." "Paweł#8547" "AMXX4u" "Opiekun"

```
</details>

### Screenshots

<details>
  <summary><b>Contact</b></summary>

- MOTD

  <img src="https://raw.githubusercontent.com/AMXX4u/contact-admin/main/assets/motd.png?token=GHSAT0AAAAAAB4BEINCGBB2AWWV2FXVTZMSY5WGYUA"></img>

- Console

  <img src="https://raw.githubusercontent.com/AMXX4u/contact-admin/main/assets/console.png?token=GHSAT0AAAAAAB4BEINDAN3JNMJTZBZDDOGEY5WGZKQ"></img>

- Chat

  <img src="https://raw.githubusercontent.com/AMXX4u/contact-admin/main/assets/chat.png?token=GHSAT0AAAAAAB4BEINDK24CWRZ55FOOBOSIY5WGZZA"></img>
</details>

### Requirements 
- AMXModX 1.9 / AMXModX 1.10
- ReHLDS 3.12.0.780
- ReAPI v5.21.0.252-dev
- ReGameDLL 5.21.0.556-dev
