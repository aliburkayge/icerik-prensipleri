# İçerik Prensipleri

Türkçe kısa video (Reels, TikTok, Shorts) senaryosu yazarken ve denetlerken kullanılan bir [Claude](https://claude.com/claude-code) skill'i.

Doldurulacak bir şablon değil. Claude'a "şu 3 adımı uygula" demek yerine, izleyicinin dikkatinin nasıl çalıştığını öğretir ve her seferinde o fikir için baştan akıl yürütmesini ister.

## İçinde ne var

- **İzleyici psikolojisi:** tek kişiye yazmak, değer/zaman oranı, senaryoyu satır satır okumak, merak döngüleri, spesifiklik, basit anlatım, gereksizi atmak, itirazı önceden karşılamak.
- **Yazma ve denetim modu:** denetim çıktısı puan tablosu değil; en fazla üç sorun, hangi satır, izleyici orada ne düşünüyor, somut düzeltme.
- **Türkçe yazım notları:** konuşma dili, çeviri kokusundan kaçmak, İngilizce terimleri nasıl kullanmak, transkript hataları.
- **Dürüstlük sınırı:** rakam, isim, tarih, müşteri hikâyesi ya da sonuç iddiası uydurulmaz. Başkasının sonucu kullanıcının kendi sonucuymuş gibi yazılmaz; kazanç vaadi ve kaynaksız istatistik yazılmaz.
- **Baştan sona örnek:** formül modunda yazılmış bir senaryo, teşhisi ve düzeltilmiş hâli.

## Kurulum

```bash
git clone https://github.com/aliburkayge/icerik-prensipleri ~/.claude/skills/icerik-prensipleri
```

Windows'ta `~` yerine kullanıcı klasörünü kullan (`C:\Users\<kullanıcı>\.claude\skills\icerik-prensipleri`).

## Kullanım

Skill'in açıklamasına uyan isteklerde Claude onu kendiliğinden kullanır. Örnek istekler:

- "Şu fikir için 40 saniyelik bir Reels senaryosu yaz: …"
- "Bu senaryoyu denetle: …"
- "Bu hook'u daha iyi nasıl yazarım?"

## Not

Metindeki sayılar (ilk değerin geleceği saniye aralığı, yeni döngünün açılacağı yer gibi) gözlenen eğilimlerdir; kaynakları yoktur ve platformlar değişir. Skill bunları kural değil ön kabul olarak sunar. Tek istisna dürüstlük sınırıdır.

## Lisans

[MIT](LICENSE)
