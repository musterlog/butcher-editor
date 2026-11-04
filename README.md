# Butcher Hero Editör v2 / Butcher Hero Editor v2

Butcher Hero (Android) için promosyon kodu ve kayıt düzenleme aracı.

A promo code and save editing tool for Butcher Hero (Android).

- [Türkçe](#türkçe)
- [English](#english)

---

## Türkçe

Butcher Hero (Android) için tarayıcıda çalışan küçük bir araç. İki iş yapar:

1. **Bugünün promosyon kodunu gösterir.** Dünyanın neresinde olursan ol, o an oyunda çalışan kodu gösterir. Tek dokunuşla kopyalanır.
2. **Oyunun kayıt dosyasını (`game_data.bin`) düzenler.** Dosyayı açar, değerleri gösterir. İstediğini değiştirirsin ve oyunun kabul ettiği yeni dosyayı indirirsin.

Hiçbir şey kurman gerekmez. Sayfa tamamen telefonunda çalışır, kayıt dosyan hiçbir yere gönderilmez. Sadece sayfanın kaç kez açıldığı sayılır (GoatCounter).

### Neleri düzenleyebilirsin

| Bölüm | Ne yapar |
|---|---|
| Elmas ve VIP puanı | Elmas miktarını ve VIP seviyeni belirler (8.000 puan = VIP 10). |
| Ruhlar | Sıradan, büyük, dev, elit, yüce, ilahi ve kaotik ruh miktarları. |
| Materyaller | Büyü tozu, jeot ve büyü taşı. |
| Demirci | Eşya bileme karakterini açar. Demirci parası da buradan ayarlanır. |
| Mitik eşyalar | 11 mitik eşyayı (3 silah, kask, kalkan, 6 aksesuar) tek tek ekler veya çıkarır ve seviyelerini ayarlar. |
| Karakter | Vuruş gücü, can, can çalma, can yenilenmesi, kritik şansı, kritik hasarı, kaçınma ve yürüme hızı. |
| Satın alımlar | Reklamsız, Ruh bileti, Kristal bileti ve Kaotik ruh teklifi. |
| Etkinlik jetonları | Etkinlik süresini satın almadan, jeton harcayarak uzatmanı sağlar. |
| Sıfırlamalar | Günlük VIP sandığını hemen açılabilir yapar, tükenmiş canavar ve ağaç noktalarını doldurur. |

### Nasıl kullanılır

#### 1. Dosyayı al

1. Oyunu tamamen kapat.
2. Dosya yöneticisiyle telefonda `Android/data/com.multicastgames.butcher/files` klasörünü aç.
3. İçindeki `game_data.bin` dosyasının bir kopyasını yedek olarak sakla.
4. Editörde **Dosya seç** düğmesiyle bu dosyayı seç.

#### 2. Düzenle

Değiştirmek istediğin sayıları yaz, açmak istediklerinin düğmesini aç. Dokunmadığın her şey olduğu gibi kalır.

#### 3. Geri koy

1. Oyunun kapalı olduğundan emin ol.
2. **İndir** düğmesiyle yeni `game_data.bin` dosyasını indir.
3. Dosyayı aynı klasöre at ve eskisinin üzerine yaz.
4. Oyunu aç.

**Not:** Bazı Android sürümleri `Android/data` klasörüne dosya yöneticisiyle girmeye izin vermez. Bu durumda dosyayı bilgisayardan USB ile (ADB) alıp geri koyabilirsin.

### Promosyon kodu hakkında

- Oyun, kodun tarihini dünya saatine (UTC) göre kontrol eder. Bu yüzden aynı anda her ülkede aynı kod çalışır.
- Sayfa, açtığın anda çalışan ve en uzun süre geçerli kalacak kodu gösterir. Sayfa açık kaldıkça kod kendiliğinden yenilenir.
- Her kod hesap başına bir kez kullanılır.

### Önemli

- Düzenlemeden önce mutlaka yedek al.
- Karakter değerlerine çok büyük sayılar girmek oyunu bozabilir.
- Bu araç resmî değildir, oyunun geliştiricisiyle bir bağı yoktur. Kişisel ve tek oyunculu kullanım içindir. Sorumluluk kullanana aittir.
- Oyun sunucudan veri çekerse (bulut kaydı, A/B testleri) bazı değişiklikler geri dönebilir.
- Araç Android içindir. iPhone'da oyunun kayıt dosyasına erişilemez.

---

## English

A small browser tool for Butcher Hero (Android). It does two things:

1. **Shows today's promo code.** Wherever you are in the world, it shows the code that works in the game right now. One tap copies it.
2. **Edits the game's save file (`game_data.bin`).** It opens the file and shows the values. You change what you want and download a new file the game accepts.

Nothing to install. The page runs entirely on your phone; your save file is never uploaded anywhere. Only page visits are counted (GoatCounter).

### What you can edit

| Section | What it does |
|---|---|
| Gems and VIP points | Sets your gem balance and VIP level (8,000 points = VIP 10). |
| Souls | Common, large, huge, elite, great, divine and chaotic souls. |
| Materials | Magic dust, geodes and enchantment stones. |
| Blacksmith | Unlocks the item-sharpening character. Blacksmith coins are set here too. |
| Mythic items | Adds or removes each of the 11 mythic items (3 weapons, helmet, shield, 6 accessories) and sets their level. |
| Character | Hit power, health, lifesteal, health regen, crit chance, crit damage, evasion and walk speed. |
| Purchases | No Ads, Soul Pass, Crystal Pass and the Chaotic Soul offer. |
| Event booster tokens | Lets you extend an event's time by spending a token instead of buying it. |
| Resets | Makes the daily VIP chest ready now and refills depleted monster and tree spawners. |

### How to use

#### 1. Get the file

1. Fully close the game.
2. Open `Android/data/com.multicastgames.butcher/files` on your phone with a file manager.
3. Keep a copy of `game_data.bin` there as a backup.
4. In the editor, choose this file with **Choose file**.

#### 2. Edit

Type the numbers you want and switch on what you want unlocked. Anything you don't touch stays as it was.

#### 3. Put it back

1. Make sure the game is closed.
2. Download the new `game_data.bin` with **Download**.
3. Put the file into the same folder, replacing the old one.
4. Open the game.

**Note:** Some Android versions don't let file managers open the `Android/data` folder. In that case, copy the file to and from a computer over USB (ADB).

### About the promo code

- The game checks a code's date against world time (UTC), so the same code works in every country at the same moment.
- The page shows the code that works when you open it and stays valid the longest. While the page is open, the code updates by itself.
- Each code works once per account.

### Important

- Always make a backup before editing.
- Very large character values may break the game.
- This tool is unofficial and not affiliated with the game's developer. It is meant for personal, single-player use, at your own risk.
- If the game pulls data from its server (cloud save, A/B tests), some changes may be reverted.
- The tool is for Android. On iPhone the game's save file can't be reached.

---

✦ Bıçağı **musterlog** bileydi, [Claude](https://claude.ai) tuttu.

✦ **musterlog** sharpened the knife, [Claude](https://claude.ai) held it.
