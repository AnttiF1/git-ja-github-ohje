# **Git ja Versionhallinta: Tiivis Ohje**

---

## 🌟 Mitä on versionhallinta?
Versionhallinta säilyttää tiedot ja niiden muutokset.  
Hyödyt:
- **📂 Varmuuskopiot:** Tallentaa tiedon nykyisen ja aiemmat versiot.  
- **🤝 Yhteistyö:** Mahdollistaa tiedon jakamisen ja muutosten hallinnan, esim. GitHubin avulla.

---

## 🛠️ Mikä on Git?
**Git** on hajautettu versionhallintajärjestelmä, joka:  
- **🔍 Seuraa muutoksia:** Tallentaa tiedostojen muokkaukset versioina.  
- **👩‍💻 Helpottaa yhteistyötä:** Yhdistää tiimin muutokset sujuvasti.

---

## 🌐 Mikä on GitHub?
**GitHub** on verkkopalvelu Git-repositorioiden jakamiseen ja hallintaan.  
- ✅ Käytä samaa projektia eri laitteilla.  
- 🤝 Jaa ja kehitä projekteja yhdessä muiden kanssa.

---

## 🔑 Peruskomennot

### Repositorion alustaminen
```bash
git init
```

### Tiedostojen hallinta
```bash
# Lisää tiedostot indeksiin
git add .

# Tee commit
git commit -m "Viesti"
```

### Tilan tarkistus
```bash
# Näytä työkansion tila
git status

# Katso commit-historia
git log
```

---

## 🔗 Työskentely GitHubin kanssa

### Kytke paikallinen repositorio GitHubiin
```bash
git remote add origin https://github.com/Kayttaja/Repositorio.git
```

### Vie muutokset GitHubiin
```bash
git push -u origin main
```

### Synkronoi muutokset GitHubista
```bash
git pull
```

---

## 🌿 Haarat (Branch)

### Haarojen hallinta
```bash
# Luo uusi haara
git branch uusi_haara

# Vaihda haaraan
git checkout uusi_haara

# Yhdistä haara päähaaraan
git merge uusi_haara
```
