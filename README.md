# 📜 Regular Expressions workshop

I den här workshopen får du steg för steg utforska regular expressions, från de allra enklaste character classes till mer avancerade capture groups, samtidigt som du lär dig JavaScript-metoder som `.test()` och `.match()` och hur de kan användas för att plocka ut exakt den data du behöver.

## 🧑‍💻 Övningar

**Skapa regular expressions för att hämta ut relevanta delar av strängarna nedan**

- Hämta ut #_# från `" Hitta #_# mitt i meningen"`
- Identifiera antalet vokaler och konsonanter i `"The quick brown fox jumps over the lazy dog."`
- Hämta ut mailadresserna från `"Du kan nå mig på gus.davidson@chas1234.org, alternativt gus@chåsacademy.se"`

## 💡 Tips

- I [regexr.com](regexr.com) får du visuell feedback i ett smidigt gränssnitt
- Använd `.match()` för att returnera en array med alla matchningar
- `.test()` tittar på om en sträng och en regex matchar varandra och returnerar en boolean
- Skapa variabler för alla olika regexes samt av strängarna ovan
- Konsollogga resultatet av `.test()` och `.match()` med olika regexes och strängar för att få en klarare uppfattning om hur de fungerar
