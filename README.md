# 🎲 Triviapeli

**Tervetuloa Triviapeliin!**  
Tämä on selainpohjainen peli, jossa testataan käyttäjän tietämystä eri aiheista. Peli on tehty **vain natiivilla JavaScriptillä, HTML:llä ja CSS:llä**, ilman ulkoisia kirjastoja.

🌐 **Live-versio:** [Pelaa Netlify-sivulla](https://aapelinilasto.netlify.app/)


---

## 🧠 Pelin kuvaus

Kun käyttäjä saapuu sivulle, hän näkee otsikon **"Tervetuloa Triviapeliin!"** ja häntä pyydetään syöttämään:
- **Käyttäjänimi**
- **Sähköpostiosoite**

Kun tiedot on täytetty oikein ja **“Aloita”**-nappia painetaan, peli alkaa.

### 🔹 Pelin kulku
1. Pelaajalle esitetään **yksi kysymys kerrallaan**.  
2. Jokaisessa kysymyksessä on **4 vastausvaihtoehtoa**, joista valitaan yksi pudotusvalikosta (`<select>`).  
3. Pelaaja lähettää vastauksensa **“Lähetä”**-napilla.  
4. Peli antaa välittömän palautteen: ✅ *Oikein!* tai ❌ *Väärin!*  
5. Seuraava kysymys ilmestyy automaattisesti, kun edellinen on vastattu.  
6. Lopuksi näytetään **pisteet**, esim. `4/6`, sekä **Top 5 tulokset**.

---

## 🏆 Leaderboard

Peli tallentaa tulokset selaimen **Local Storageen**.  
Jos pelaajan pistemäärä on parempi kuin yksi top 5 -tuloksista, hänen tuloksensa lisätään automaattisesti **leaderboardiin**.

---

## 💻 Käyttöohjeet

### Pelaaminen
1. Avaa peli selaimessa (linkki yllä).  
2. Syötä nimi ja sähköposti.  
3. Paina **“Aloita”** aloittaaksesi pelin.  
4. Vastaa kysymyksiin ja katso, kuinka hyvin pärjäät!

---

## 🧩 Teknologiat


**HTML5**                     Sivun rakenne

**CSS3**                      Ulkoasu ja muotoilu

**JavaScript (ES6)**          Pelilogiikka ja Local Storage -toiminnallisuus

---

## ⚙️ Kehittäjälle

Alla Github-linkki projektiini:

https://github.com/aapelinilasto47/javascript-project-1


---

## 🧑‍💻 Tekijä

Projektin kehittäjä: **Aapeli Nilasto**
Julkaistu: **Netlifyssä ja Githubissa**  


---

## 📸 Kuvankaappaus (valinnainen)

Lisää tänne kuvakaappaus pelistä, esimerkiksi:
```
![Triviapeli kuvankaappaus](./screenshot.png)
```

---

✨ *Hauskoja pelihetkiä ja onnea tietovisailuun!*
