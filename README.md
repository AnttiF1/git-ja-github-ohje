# **Git ja Versionhallinta: Ohje**

---

## 🎯 **Mitä on versionhallinta?**
Versionhallinta säilöö tiedot ja niiden muutokset. Se:
- Toimii varmuuskopiona.
- Mahdollistaa yhteistyön esim. **GitHubin** kautta.

---

## 💻 **Mikä on Git?**
**Git** on hajautettu versiohallintajärjestelmä, jolla seurataan muutoksia ja työskennellään tehokkaasti ryhmässä.

---

## 🌐 **Mikä on GitHub?**
**GitHub** on verkkopalvelu, jossa Git-repositorioita voi jakaa, hallita ja käyttää varmuuskopiona.

---

## 🛠️ **Peruskomennot**
```bash
# Alusta uusi Git-repositorio
git init

# Lisää tiedostot indeksiin
git add .

# Tee commit
git commit -m "Viesti"

# Kytke paikallinen repositorio GitHubiin
git remote add origin https://github.com/Tunnus/Repositorio.git

# Vie tiedot GitHubiin
git push -u origin master

# Hae muutokset GitHubista
git pull

# Tarkista tilanne
git status

# Näytä commitit
git log

# Luo uusi haara
git branch haara

# Siirry haaraan
git checkout haara

# Yhdistä haara päähaaraan
git merge haara
