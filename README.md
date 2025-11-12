# Etto — Japanese Dictionary

![Swift](https://img.shields.io/badge/Swift-FA7343?logo=swift&logoColor=white)
![iOS](https://img.shields.io/badge/iOS-000000?logo=apple&logoColor=white)
![GitHub Pages](https://img.shields.io/badge/Data-Hosted_on_GitHub-brightgreen)
![License](https://img.shields.io/badge/License-MIT-blue)

> えっと... this is a clean & open Japanese–English dictionary database  

---

## About

**Etto** is an upcoming Japanese flashcard app that will use spaced repetition to help you memorize vocabulary and track your progress toward fluency.  
This repository hosts the **open dictionary data** used in the app — a structured collection of Japanese words with readings, meanings, and JLPT levels.

**Currently in progress:** the database is continuously refined and expanded with more accurate definitions, kanji data, and linguistic properties. Expect regular updates as the project grows.

---

## Structure

Each entry includes:
```json
{
  "kanji": "花",
  "kana": "はな",
  "romaji": "hana",
  "english": "flower",
  "usageLevel": "common",
  "jlptLevel": "N5"
}
