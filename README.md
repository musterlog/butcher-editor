# Butcher Hero Editör v3 / Butcher Hero Editor v3

Butcher Hero (Android) için promosyon kodu ve kayıt düzenleme aracı.

A promo code and save editing tool for Butcher Hero (Android).

**Site:** https://musterlog.github.io/butcher-editor/

- [Türkçe](#türkçe)
- [English](#english)
- [Deutsch](#deutsch)
- [Français](#français)
- [Italiano](#italiano)
- [Polski](#polski)
- [Русский](#русский)
- [한국어](#한국어)

---

## Türkçe

Butcher Hero (Android) için tarayıcıda çalışan küçük bir araç. İki iş yapar:

1. **Geçerli promosyon kodlarını gösterir.** Dünyanın neresinde olursan ol, o an oyunda çalışan iki kodu gösterir. Tek dokunuşla kopyalanır.
2. **Oyunun kayıt dosyasını (`game_data.bin`) düzenler.** Dosyayı açar, değerleri gösterir. İstediğini değiştirirsin ve oyunun kabul ettiği yeni dosyayı indirirsin.

Sayfa 8 dilde kullanılabilir: Türkçe, İngilizce, Almanca, Fransızca, İtalyanca, Lehçe, Rusça ve Korece. Dil, telefonunun diline göre kendiliğinden seçilir, üstteki menüden değiştirilebilir.

Hiçbir şey kurman gerekmez. Sayfa tamamen telefonunda çalışır, kayıt dosyan hiçbir yere gönderilmez. Sadece sayfanın kaç kez açıldığı sayılır (GoatCounter).

### Neleri düzenleyebilirsin

| Bölüm | Ne yapar |
|---|---|
| Elmas ve VIP | Elmas miktarını ve VIP seviyeni belirler (8.000 puan = VIP 10). |
| Ruhlar | Sıradan, büyük, dev, elit, yüce, ilahi ve kaotik ruh miktarları. |
| Materyaller | Büyü tozu, jeot ve büyü taşı. |
| Adalar | İstediğin adaya kadar bütün adaları tek dokunuşla açar (17 ada). O adalara giden kapılar da otomatik açılır, ilerideki kapılar kapalı kalır. |
| Demirci | Eşya bileme karakterini açar. Demirci parası da buradan ayarlanır. |
| Mitik eşyalar | 11 mitik eşyayı (3 silah, kask, kalkan, 6 aksesuar) tek tek ekler veya çıkarır, seviyelerini istediğin gibi ayarlar. |
| Karakter | Vuruş gücü, can, can çalma, can yenilenmesi, kritik şansı, kritik hasarı, kaçınma ve yürüme hızı. |
| Satın alımlar | Reklamsız, Ruh bileti, Kristal bileti ve Kaotik ruh teklifi. |
| Etkinlik jetonları | Etkinlik süresini satın almadan, jeton harcayarak uzatmanı sağlar. |
| Sıfırlamalar | Günlük VIP sandığını hemen açılabilir yapar, tükenmiş canavar ve ağaç noktalarını doldurur, promosyon kodu hakkını yeniler. |
| Zaman Onarımı | Saati ileri alıp geri döndüysen büyü taşı, jeot, boss bileti ve mağazanın ücretsiz ürünleri gelmeyi keser. İleri tarihte kalmış zamanlayıcıları bulup bugüne çeker. |

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
- Sayfa her zaman şu an geçerli iki kodu gösterir, ikisi de çalışır. Sayfa açık kaldıkça kodlar kendiliğinden yenilenir.
- **Oyun her hesaba ömür boyu yalnızca bir promosyon kodu kullandırır.** Bir kod kullandıktan sonra diğer bütün kodlar "geçersiz" görünür. Yeni bir kod girmek için editörde Sıfırlamalar bölümündeki "Promosyon kodu hakkı" düğmesini açıp kaydı telefona geri yükle.

### Önemli

- Düzenlemeden önce mutlaka yedek al.
- Karakter değerlerine çok büyük sayılar girmek oyunu bozabilir.
- Bu araç resmî değildir, oyunun geliştiricisiyle bir bağı yoktur. Kişisel ve tek oyunculu kullanım içindir. Sorumluluk kullanana aittir.
- Oyun sunucudan veri çekerse (bulut kaydı, A/B testleri) bazı değişiklikler geri dönebilir.
- Araç Android içindir. iPhone'da oyunun kayıt dosyasına erişilemez.

---

## English

A small browser tool for Butcher Hero (Android). It does two things:

1. **Shows the valid promo codes.** Wherever you are in the world, it shows the two codes that work in the game right now. One tap copies a code.
2. **Edits the game's save file (`game_data.bin`).** It opens the file and shows the values. You change what you want and download a new file the game accepts.

The page is available in 8 languages: Turkish, English, German, French, Italian, Polish, Russian and Korean. It picks your phone's language automatically, and you can change it from the menu at the top.

Nothing to install. The page runs entirely on your phone; your save file is never uploaded anywhere. Only page visits are counted (GoatCounter).

### What you can edit

| Section | What it does |
|---|---|
| Gems and VIP | Sets your gem balance and VIP level (8,000 points = VIP 10). |
| Souls | Common, large, huge, elite, great, divine and chaotic souls. |
| Materials | Magic dust, geodes and enchantment stones. |
| Islands | Unlocks every island up to the one you tap (17 islands). The gates to those islands open automatically, gates further on stay closed. |
| Blacksmith | Unlocks the item-sharpening character. Blacksmith coins are set here too. |
| Mythic items | Adds or removes each of the 11 mythic items (3 weapons, helmet, shield, 6 accessories) and sets any level you want. |
| Character | Hit power, health, lifesteal, health regen, crit chance, crit damage, evasion and walk speed. |
| Purchases | No Ads, Soul Pass, Crystal Pass and the Chaotic Soul offer. |
| Event tokens | Lets you extend an event's time by spending a token instead of buying it. |
| Resets | Makes the daily VIP chest ready now, refills depleted monster and tree spawners, and resets your promo code use. |
| Time repair | If you moved the clock forward and back, enchantment stones, geodes, boss tickets and free shop items stop coming. Finds timers stuck in the future and moves them back to today. |

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

### About the promo codes

- The game checks a code's date against world time (UTC), so the same code works in every country at the same moment.
- The page always shows the two codes that work right now; either one works. While the page is open, the codes update by themselves.
- **The game lets each account redeem only one promo code, ever.** After that, every other code shows as "invalid". To enter a new one, switch on "Promo code use" under Resets in the editor and put the save back on your phone.

### Important

- Always make a backup before editing.
- Very large character values may break the game.
- This tool is unofficial and not affiliated with the game's developer. It is meant for personal, single-player use, at your own risk.
- If the game pulls data from its server (cloud save, A/B tests), some changes may be reverted.
- The tool is for Android. On iPhone the game's save file can't be reached.

---

## Deutsch

Ein kleines Browser-Tool für Butcher Hero (Android). Es kann zwei Dinge:

1. **Zeigt die gültigen Promo-Codes.** Egal, wo du auf der Welt bist: Es zeigt die zwei Codes, die gerade im Spiel funktionieren. Ein Tippen kopiert einen Code.
2. **Bearbeitet den Spielstand (`game_data.bin`).** Es öffnet die Datei und zeigt die Werte. Du änderst, was du willst, und lädst eine neue Datei herunter, die das Spiel akzeptiert.

Die Seite gibt es in 8 Sprachen: Türkisch, Englisch, Deutsch, Französisch, Italienisch, Polnisch, Russisch und Koreanisch. Sie wählt automatisch die Sprache deines Handys; du kannst sie im Menü oben ändern.

Nichts zu installieren. Die Seite läuft komplett auf deinem Handy, dein Spielstand wird nirgendwohin hochgeladen. Gezählt werden nur die Seitenaufrufe (GoatCounter).

### Was du bearbeiten kannst

| Bereich | Was er macht |
|---|---|
| Edelsteine und VIP | Legt deine Edelsteine und dein VIP-Level fest (8.000 Punkte = VIP 10). |
| Seelen | Gewöhnliche, große, riesige, Elite-, höhere, göttliche und chaotische Seelen. |
| Materialien | Magiestaub, Geoden und Verzauberungssteine. |
| Inseln | Schaltet mit einem Tippen alle Inseln bis zur gewählten frei (17 Inseln). Die Tore zu diesen Inseln öffnen sich automatisch, spätere Tore bleiben geschlossen. |
| Schmied | Schaltet den Charakter zum Schärfen von Gegenständen frei. Auch die Schmiedemünzen werden hier eingestellt. |
| Mythische Gegenstände | Fügt jeden der 11 mythischen Gegenstände (3 Waffen, Helm, Schild, 6 Accessoires) einzeln hinzu oder entfernt ihn und stellt jede gewünschte Stufe ein. |
| Charakter | Schlagkraft, Gesundheit, Lebensraub, Gesundheitsregeneration, kritische Trefferchance, kritischer Schaden, Ausweichen und Laufgeschwindigkeit. |
| Käufe | Werbefrei, Soul Pass, Crystal Pass und das Angebot „Chaotische Seele“. |
| Event-Marken | Damit verlängerst du die Zeit eines Events mit einer Marke, statt sie zu kaufen. |
| Zurücksetzen | Macht die tägliche VIP-Truhe sofort verfügbar, füllt erschöpfte Spawn-Punkte von Monstern und Bäumen auf und setzt die Promo-Code-Nutzung zurück. |
| Zeitreparatur | Wenn du die Uhr vor- und wieder zurückgestellt hast, kommen Verzauberungssteine, Geoden, Boss-Tickets und Gratisartikel im Shop nicht mehr. Findet die in der Zukunft hängenden Timer und setzt sie auf heute zurück. |

### So funktioniert es

#### 1. Datei holen

1. Schließe das Spiel vollständig.
2. Öffne auf dem Handy mit einem Dateimanager den Ordner `Android/data/com.multicastgames.butcher/files`.
3. Bewahre eine Kopie von `game_data.bin` als Sicherung auf.
4. Wähle die Datei im Editor über **Datei auswählen**.

#### 2. Bearbeiten

Gib die gewünschten Zahlen ein und schalte ein, was du freischalten willst. Alles, was du nicht anfasst, bleibt unverändert.

#### 3. Zurücklegen

1. Stelle sicher, dass das Spiel geschlossen ist.
2. Lade die neue `game_data.bin` über **Herunterladen** herunter.
3. Lege die Datei in denselben Ordner und ersetze die alte.
4. Starte das Spiel.

**Hinweis:** Manche Android-Versionen lassen Dateimanager nicht in den Ordner `Android/data`. Dann kopierst du die Datei per USB (ADB) über einen Computer hin und zurück.

### Zu den Promo-Codes

- Das Spiel prüft das Datum eines Codes anhand der Weltzeit (UTC). Deshalb funktioniert in jedem Land zur gleichen Zeit derselbe Code.
- Die Seite zeigt immer die zwei Codes, die gerade gültig sind; beide funktionieren. Solange die Seite offen ist, werden die Codes automatisch aktualisiert.
- **Das Spiel lässt pro Konto für immer nur einen einzigen Promo-Code zu.** Danach wird jeder weitere Code als „ungültig“ angezeigt. Um einen neuen einzugeben, schalte im Editor unter Zurücksetzen „Promo-Code-Nutzung“ ein und spiele den Spielstand wieder auf dein Handy.

### Wichtig

- Mache vor dem Bearbeiten immer eine Sicherung.
- Sehr große Charakterwerte können das Spiel kaputt machen.
- Dieses Tool ist inoffiziell und hat nichts mit dem Entwickler des Spiels zu tun. Es ist für die persönliche Nutzung im Einzelspieler gedacht, auf eigene Gefahr.
- Wenn das Spiel Daten vom Server lädt (Cloud-Speicherstand, A/B-Tests), können manche Änderungen zurückgesetzt werden.
- Das Tool ist für Android. Auf dem iPhone ist der Spielstand nicht zugänglich.

---

## Français

Un petit outil dans le navigateur pour Butcher Hero (Android). Il fait deux choses :

1. **Affiche les codes promo valides.** Où que vous soyez dans le monde, il affiche les deux codes qui fonctionnent dans le jeu en ce moment. Un appui copie un code.
2. **Modifie la sauvegarde du jeu (`game_data.bin`).** Il ouvre le fichier et affiche les valeurs. Vous changez ce que vous voulez et téléchargez un nouveau fichier accepté par le jeu.

La page est disponible en 8 langues : turc, anglais, allemand, français, italien, polonais, russe et coréen. Elle choisit automatiquement la langue de votre téléphone ; vous pouvez la changer dans le menu en haut.

Rien à installer. La page fonctionne entièrement sur votre téléphone, votre sauvegarde n’est envoyée nulle part. Seules les visites de la page sont comptées (GoatCounter).

### Ce que vous pouvez modifier

| Section | Ce qu’elle fait |
|---|---|
| Gemmes et VIP | Définit vos gemmes et votre niveau VIP (8 000 points = VIP 10). |
| Âmes | Âmes communes, grandes, énormes, d’élite, supérieures, divines et chaotiques. |
| Matériaux | Poussière magique, géodes et pierres d’enchantement. |
| Îles | Débloque d’un appui toutes les îles jusqu’à celle choisie (17 îles). Les portes vers ces îles s’ouvrent automatiquement, les suivantes restent fermées. |
| Forgeron | Débloque le personnage qui aiguise les objets. Les pièces du forgeron se règlent aussi ici. |
| Objets mythiques | Ajoute ou retire chacun des 11 objets mythiques (3 armes, casque, bouclier, 6 accessoires) et règle le niveau de votre choix. |
| Personnage | Puissance de frappe, santé, vol de vie, régénération de santé, chances de coup critique, dégâts critiques, esquive et vitesse de marche. |
| Achats | Sans publicité, Soul Pass, Crystal Pass et l’offre Âme chaotique. |
| Jetons d’événement | Permet de prolonger un événement en dépensant un jeton au lieu de l’acheter. |
| Réinitialisations | Rend le coffre VIP quotidien disponible tout de suite, remplit les points d’apparition épuisés des monstres et des arbres et réinitialise l’utilisation du code promo. |
| Réparation du temps | Si vous avez avancé puis reculé l’horloge, les pierres d’enchantement, les géodes, les tickets de boss et les articles gratuits de la boutique ne reviennent plus. Trouve les minuteurs bloqués dans le futur et les ramène à aujourd’hui. |

### Mode d’emploi

#### 1. Récupérer le fichier

1. Fermez complètement le jeu.
2. Ouvrez le dossier `Android/data/com.multicastgames.butcher/files` sur votre téléphone avec un gestionnaire de fichiers.
3. Gardez une copie de `game_data.bin` comme sauvegarde.
4. Dans l’éditeur, choisissez ce fichier avec **Choisir un fichier**.

#### 2. Modifier

Saisissez les nombres voulus et activez ce que vous voulez débloquer. Tout ce que vous ne touchez pas reste tel quel.

#### 3. Remettre le fichier

1. Vérifiez que le jeu est fermé.
2. Téléchargez le nouveau `game_data.bin` avec **Télécharger**.
3. Placez le fichier dans le même dossier en remplaçant l’ancien.
4. Lancez le jeu.

**Remarque :** certaines versions d’Android empêchent les gestionnaires de fichiers d’ouvrir le dossier `Android/data`. Dans ce cas, copiez le fichier depuis et vers un ordinateur par USB (ADB).

### À propos des codes promo

- Le jeu vérifie la date d’un code selon l’heure mondiale (UTC). Le même code fonctionne donc au même moment dans tous les pays.
- La page affiche toujours les deux codes valides en ce moment ; les deux fonctionnent. Tant que la page reste ouverte, les codes se mettent à jour tout seuls.
- **Le jeu ne permet d’utiliser qu’un seul code promo par compte, une fois pour toutes.** Ensuite, tous les autres codes s’affichent comme « invalides ». Pour en saisir un nouveau, activez « Utilisation du code promo » dans Réinitialisations, puis remettez la sauvegarde sur votre téléphone.

### Important

- Faites toujours une sauvegarde avant de modifier.
- Des valeurs de personnage très élevées peuvent casser le jeu.
- Cet outil n’est pas officiel et n’a aucun lien avec le développeur du jeu. Il est destiné à un usage personnel en solo, à vos risques et périls.
- Si le jeu récupère des données depuis son serveur (sauvegarde cloud, tests A/B), certaines modifications peuvent être annulées.
- L’outil est fait pour Android. Sur iPhone, la sauvegarde du jeu n’est pas accessible.

---

## Italiano

Un piccolo strumento nel browser per Butcher Hero (Android). Fa due cose:

1. **Mostra i codici promozionali validi.** Ovunque tu sia nel mondo, mostra i due codici che funzionano nel gioco in questo momento. Un tocco copia un codice.
2. **Modifica il salvataggio del gioco (`game_data.bin`).** Apre il file e mostra i valori. Cambi quello che vuoi e scarichi un nuovo file che il gioco accetta.

La pagina è disponibile in 8 lingue: turco, inglese, tedesco, francese, italiano, polacco, russo e coreano. Sceglie automaticamente la lingua del telefono e puoi cambiarla dal menu in alto.

Non serve installare nulla. La pagina funziona interamente sul telefono, il salvataggio non viene inviato da nessuna parte. Vengono contate solo le visite alla pagina (GoatCounter).

### Cosa puoi modificare

| Sezione | Cosa fa |
|---|---|
| Gemme e VIP | Imposta le gemme e il livello VIP (8.000 punti = VIP 10). |
| Anime | Anime comuni, grandi, enormi, d’élite, superiori, divine e caotiche. |
| Materiali | Polvere magica, geodi e pietre d’incantamento. |
| Isole | Sblocca con un tocco tutte le isole fino a quella scelta (17 isole). I portali verso quelle isole si aprono automaticamente, quelli successivi restano chiusi. |
| Fabbro | Sblocca il personaggio che affila gli oggetti. Qui si impostano anche le monete del fabbro. |
| Oggetti mitici | Aggiunge o rimuove ciascuno degli 11 oggetti mitici (3 armi, elmo, scudo, 6 accessori) e imposta il livello che vuoi. |
| Personaggio | Potenza del colpo, salute, furto di vita, rigenerazione della salute, probabilità di critico, danno critico, schivata e velocità di camminata. |
| Acquisti | Senza pubblicità, Soul Pass, Crystal Pass e l’offerta Anima caotica. |
| Gettoni evento | Permettono di prolungare un evento spendendo un gettone invece di comprarlo. |
| Ripristini | Rende subito disponibile il forziere VIP giornaliero, ripristina i punti di comparsa esauriti di mostri e alberi e azzera l’uso del codice promozionale. |
| Riparazione del tempo | Se hai spostato l’orologio avanti e poi indietro, pietre d’incantamento, geodi, biglietti dei boss e oggetti gratuiti del negozio smettono di arrivare. Trova i timer bloccati nel futuro e li riporta a oggi. |

### Come si usa

#### 1. Prendi il file

1. Chiudi completamente il gioco.
2. Con un file manager apri sul telefono la cartella `Android/data/com.multicastgames.butcher/files`.
3. Conserva una copia di `game_data.bin` come backup.
4. Nell’editor scegli questo file con **Scegli file**.

#### 2. Modifica

Scrivi i numeri che vuoi e attiva ciò che vuoi sbloccare. Tutto ciò che non tocchi resta com’è.

#### 3. Rimettilo a posto

1. Assicurati che il gioco sia chiuso.
2. Scarica il nuovo `game_data.bin` con **Scarica**.
3. Metti il file nella stessa cartella, sostituendo quello vecchio.
4. Avvia il gioco.

**Nota:** alcune versioni di Android non permettono ai file manager di aprire la cartella `Android/data`. In questo caso copia il file da e verso un computer tramite USB (ADB).

### Sui codici promozionali

- Il gioco controlla la data di un codice in base all’ora mondiale (UTC), quindi lo stesso codice funziona nello stesso momento in tutti i paesi.
- La pagina mostra sempre i due codici validi in questo momento; funzionano entrambi. Finché la pagina resta aperta, i codici si aggiornano da soli.
- **Il gioco permette a ogni account di usare un solo codice promozionale in assoluto.** Dopo il primo, tutti gli altri risultano «non validi». Per inserirne uno nuovo, attiva «Uso del codice promozionale» in Ripristini e rimetti il salvataggio sul telefono.

### Importante

- Fai sempre un backup prima di modificare.
- Valori del personaggio molto alti possono rompere il gioco.
- Questo strumento non è ufficiale e non ha legami con lo sviluppatore del gioco. È pensato per uso personale in single player, a tuo rischio.
- Se il gioco scarica dati dal server (salvataggio cloud, test A/B), alcune modifiche potrebbero essere annullate.
- Lo strumento è per Android. Su iPhone il salvataggio del gioco non è accessibile.

---

## Polski

Małe narzędzie w przeglądarce do gry Butcher Hero (Android). Robi dwie rzeczy:

1. **Pokazuje ważne kody promocyjne.** Bez względu na to, gdzie jesteś na świecie, pokazuje dwa kody, które działają w grze w tej chwili. Jedno dotknięcie kopiuje kod.
2. **Edytuje zapis gry (`game_data.bin`).** Otwiera plik i pokazuje wartości. Zmieniasz, co chcesz, i pobierasz nowy plik, który gra zaakceptuje.

Strona jest dostępna w 8 językach: tureckim, angielskim, niemieckim, francuskim, włoskim, polskim, rosyjskim i koreańskim. Sama wybiera język telefonu, a zmienić go można w menu u góry.

Nie trzeba niczego instalować. Strona działa w całości na telefonie, a zapis gry nie jest nigdzie wysyłany. Liczone są tylko odwiedziny strony (GoatCounter).

### Co możesz edytować

| Sekcja | Co robi |
|---|---|
| Klejnoty i VIP | Ustawia liczbę klejnotów i poziom VIP (8000 punktów = VIP 10). |
| Dusze | Dusze zwykłe, duże, ogromne, elitarne, wielkie, boskie i chaotyczne. |
| Materiały | Magiczny pył, geody i kamienie zaklinania. |
| Wyspy | Jednym dotknięciem odblokowuje wszystkie wyspy aż do wybranej (17 wysp). Bramy do tych wysp otwierają się automatycznie, dalsze pozostają zamknięte. |
| Kowal | Odblokowuje postać ostrzącą przedmioty. Tu ustawia się też monety kowala. |
| Przedmioty mityczne | Dodaje lub usuwa każdy z 11 przedmiotów mitycznych (3 bronie, hełm, tarcza, 6 akcesoriów) i ustawia dowolny poziom. |
| Postać | Siła ciosu, zdrowie, kradzież życia, regeneracja zdrowia, szansa na trafienie krytyczne, obrażenia krytyczne, unik i szybkość chodu. |
| Zakupy | Bez reklam, Soul Pass, Crystal Pass i oferta Chaotycznej duszy. |
| Żetony wydarzeń | Pozwalają przedłużyć wydarzenie za żeton zamiast kupować przedłużenie. |
| Resetowanie | Od razu udostępnia codzienną skrzynię VIP, uzupełnia wyczerpane punkty pojawiania się potworów i drzew oraz resetuje użycie kodu promocyjnego. |
| Naprawa czasu | Jeśli przestawiłeś zegar do przodu i z powrotem, kamienie zaklinania, geody, bilety na bossów i darmowe przedmioty ze sklepu przestają przychodzić. Znajduje liczniki zablokowane w przyszłości i cofa je do dzisiaj. |

### Jak używać

#### 1. Pobierz plik

1. Całkowicie zamknij grę.
2. Otwórz na telefonie menedżerem plików folder `Android/data/com.multicastgames.butcher/files`.
3. Zachowaj kopię pliku `game_data.bin` jako kopię zapasową.
4. W edytorze wybierz ten plik przyciskiem **Wybierz plik**.

#### 2. Edytuj

Wpisz liczby, które chcesz, i włącz to, co chcesz odblokować. Wszystko, czego nie ruszasz, zostaje bez zmian.

#### 3. Odłóż plik

1. Upewnij się, że gra jest zamknięta.
2. Pobierz nowy `game_data.bin` przyciskiem **Pobierz**.
3. Wrzuć plik do tego samego folderu, zastępując stary.
4. Uruchom grę.

**Uwaga:** niektóre wersje Androida nie pozwalają menedżerom plików otwierać folderu `Android/data`. Wtedy przenieś plik na komputer i z powrotem przez USB (ADB).

### O kodach promocyjnych

- Gra sprawdza datę kodu według czasu światowego (UTC), więc ten sam kod działa w tej samej chwili w każdym kraju.
- Strona zawsze pokazuje dwa kody ważne w tej chwili; oba działają. Dopóki strona jest otwarta, kody odświeżają się same.
- **Gra pozwala każdemu kontu wykorzystać tylko jeden kod promocyjny – raz na zawsze.** Potem każdy inny kod jest oznaczany jako „nieprawidłowy”. Aby wpisać nowy, włącz „Użycie kodu promocyjnego” w sekcji Resetowanie i wgraj zapis z powrotem na telefon.

### Ważne

- Przed edycją zawsze zrób kopię zapasową.
- Bardzo duże wartości postaci mogą zepsuć grę.
- To narzędzie jest nieoficjalne i nie ma związku z twórcą gry. Jest przeznaczone do osobistego użytku w trybie jednoosobowym, na własne ryzyko.
- Jeśli gra pobierze dane z serwera (zapis w chmurze, testy A/B), niektóre zmiany mogą zostać cofnięte.
- Narzędzie jest przeznaczone na Androida. Na iPhonie zapis gry jest niedostępny.

---

## Русский

Небольшой инструмент в браузере для Butcher Hero (Android). Он делает две вещи:

1. **Показывает действующие промокоды.** Где бы вы ни находились, он показывает два кода, которые работают в игре прямо сейчас. Одно касание копирует код.
2. **Редактирует сохранение игры (`game_data.bin`).** Открывает файл и показывает значения. Вы меняете что хотите и скачиваете новый файл, который игра примет.

Страница доступна на 8 языках: турецком, английском, немецком, французском, итальянском, польском, русском и корейском. Язык выбирается автоматически по языку телефона, его можно сменить в меню вверху.

Ничего устанавливать не нужно. Страница полностью работает на вашем телефоне, сохранение никуда не отправляется. Считаются только посещения страницы (GoatCounter).

### Что можно изменить

| Раздел | Что делает |
|---|---|
| Алмазы и VIP | Задаёт количество алмазов и уровень VIP (8000 очков = VIP 10). |
| Души | Обычные, большие, огромные, элитные, великие, божественные и хаотические души. |
| Материалы | Магическая пыль, жеоды и камни зачарования. |
| Острова | Одним касанием открывает все острова до выбранного (17 островов). Ворота к этим островам открываются автоматически, дальнейшие остаются закрытыми. |
| Кузнец | Открывает персонажа, который затачивает предметы. Здесь же задаются монеты кузнеца. |
| Мифические предметы | Добавляет или удаляет каждый из 11 мифических предметов (3 оружия, шлем, щит, 6 аксессуаров) и задаёт любой уровень. |
| Персонаж | Сила удара, здоровье, вампиризм, регенерация здоровья, шанс критического удара, критический урон, уклонение и скорость ходьбы. |
| Покупки | Без рекламы, Soul Pass, Crystal Pass и предложение «Хаотическая душа». |
| Жетоны событий | Позволяют продлить событие за жетон вместо покупки. |
| Сброс | Делает ежедневный сундук VIP доступным сразу, восстанавливает опустевшие точки появления монстров и деревьев и сбрасывает использование промокода. |
| Исправление времени | Если вы переводили часы вперёд и обратно, камни зачарования, жеоды, билеты на боссов и бесплатные товары в магазине перестают приходить. Находит таймеры, застрявшие в будущем, и возвращает их на сегодня. |

### Как пользоваться

#### 1. Возьмите файл

1. Полностью закройте игру.
2. Откройте на телефоне файловым менеджером папку `Android/data/com.multicastgames.butcher/files`.
3. Сохраните копию файла `game_data.bin` как резервную.
4. В редакторе выберите этот файл кнопкой **Выбрать файл**.

#### 2. Измените

Введите нужные числа и включите то, что хотите открыть. Всё, чего вы не касаетесь, остаётся как было.

#### 3. Верните на место

1. Убедитесь, что игра закрыта.
2. Скачайте новый `game_data.bin` кнопкой **Скачать**.
3. Положите файл в ту же папку, заменив старый.
4. Запустите игру.

**Примечание:** некоторые версии Android не пускают файловые менеджеры в папку `Android/data`. В этом случае перенесите файл на компьютер и обратно по USB (ADB).

### О промокодах

- Игра проверяет дату кода по мировому времени (UTC), поэтому в один и тот же момент во всех странах работает один и тот же код.
- Страница всегда показывает два кода, действующих прямо сейчас; работают оба. Пока страница открыта, коды обновляются сами.
- **Игра позволяет каждому аккаунту активировать только один промокод за всё время.** После этого любой другой код считается «недействительным». Чтобы ввести новый, включите «Использование промокода» в разделе «Сброс» и верните сохранение на телефон.

### Важно

- Перед редактированием всегда делайте резервную копию.
- Очень большие значения персонажа могут сломать игру.
- Этот инструмент неофициальный и не связан с разработчиком игры. Он предназначен для личного использования в одиночной игре, на ваш страх и риск.
- Если игра загружает данные с сервера (облачное сохранение, A/B-тесты), некоторые изменения могут откатиться.
- Инструмент предназначен для Android. На iPhone доступа к сохранению игры нет.

---

## 한국어

Butcher Hero(Android)를 위한 작은 브라우저 도구입니다. 두 가지 일을 합니다.

1. **사용 가능한 프로모션 코드를 보여 줍니다.** 세계 어디에 있든 지금 게임에서 작동하는 코드 두 개를 보여 줍니다. 한 번 누르면 코드가 복사됩니다.
2. **게임 저장 파일(`game_data.bin`)을 편집합니다.** 파일을 열어 값을 보여 줍니다. 원하는 것을 바꾸고, 게임이 받아들이는 새 파일을 다운로드하면 됩니다.

페이지는 8개 언어로 제공됩니다: 터키어, 영어, 독일어, 프랑스어, 이탈리아어, 폴란드어, 러시아어, 한국어. 휴대폰 언어에 맞춰 자동으로 선택되며, 위쪽 메뉴에서 바꿀 수 있습니다.

설치할 것은 없습니다. 페이지는 전부 휴대폰에서 실행되며, 저장 파일은 어디에도 전송되지 않습니다. 페이지 방문 횟수만 집계됩니다(GoatCounter).

### 편집할 수 있는 항목

| 항목 | 기능 |
|---|---|
| 보석 및 VIP | 보석 수와 VIP 레벨을 정합니다(8,000포인트 = VIP 10). |
| 영혼 | 일반, 큰, 거대한, 정예, 위대한, 신성한, 혼돈의 영혼. |
| 재료 | 마법 가루, 정동석, 마법 부여석. |
| 섬 | 선택한 섬까지 모든 섬을 한 번에 엽니다(17개 섬). 그 섬으로 가는 관문은 자동으로 열리고, 그 이후 관문은 닫힌 채로 남습니다. |
| 대장장이 | 아이템을 연마하는 캐릭터를 엽니다. 대장장이 코인도 여기서 설정합니다. |
| 신화 아이템 | 신화 아이템 11개(무기 3개, 투구, 방패, 액세서리 6개)를 하나씩 추가하거나 제거하고, 원하는 레벨로 설정합니다. |
| 캐릭터 | 공격력, 체력, 흡혈, 체력 재생, 치명타 확률, 치명타 피해, 회피, 이동 속도. |
| 구매 | 광고 제거, 소울 패스, 크리스탈 패스, 혼돈의 영혼 상품. |
| 이벤트 토큰 | 구매하지 않고 토큰을 써서 이벤트 기간을 늘릴 수 있습니다. |
| 초기화 | 일일 VIP 상자를 바로 열 수 있게 하고, 소진된 몬스터와 나무 생성 지점을 다시 채우며, 프로모션 코드 사용 기록을 지웁니다. |
| 시간 복구 | 시계를 앞으로 돌렸다가 되돌리면 마법 부여석, 정동석, 보스 티켓, 상점 무료 아이템이 더 이상 들어오지 않습니다. 미래에 멈춘 타이머를 찾아 오늘로 되돌립니다. |

### 사용 방법

#### 1. 파일 가져오기

1. 게임을 완전히 종료합니다.
2. 휴대폰의 파일 관리자로 `Android/data/com.multicastgames.butcher/files` 폴더를 엽니다.
3. `game_data.bin` 파일의 사본을 백업으로 보관합니다.
4. 에디터에서 **파일 선택** 버튼으로 이 파일을 고릅니다.

#### 2. 편집하기

원하는 숫자를 입력하고, 열고 싶은 항목의 스위치를 켭니다. 건드리지 않은 항목은 그대로 유지됩니다.

#### 3. 다시 넣기

1. 게임이 꺼져 있는지 확인합니다.
2. **다운로드** 버튼으로 새 `game_data.bin`을 받습니다.
3. 같은 폴더에 넣어 기존 파일을 덮어씁니다.
4. 게임을 실행합니다.

**참고:** 일부 Android 버전에서는 파일 관리자로 `Android/data` 폴더에 들어갈 수 없습니다. 이 경우 USB(ADB)로 컴퓨터를 통해 파일을 옮기세요.

### 프로모션 코드 안내

- 게임은 코드의 날짜를 세계 표준시(UTC) 기준으로 확인합니다. 그래서 같은 시각에는 모든 나라에서 같은 코드가 작동합니다.
- 페이지는 항상 지금 사용할 수 있는 코드 두 개를 보여 주며, 둘 다 작동합니다. 페이지를 열어 두면 코드가 자동으로 갱신됩니다.
- **이 게임은 계정마다 프로모션 코드를 평생 단 한 번만 사용할 수 있게 합니다.** 한 번 사용한 뒤에는 다른 코드가 모두 ‘잘못된 코드’로 표시됩니다. 새 코드를 입력하려면 에디터의 초기화에서 ‘프로모션 코드 사용 기록’을 켜고 저장 파일을 휴대폰에 다시 넣으세요.

### 중요

- 편집하기 전에 반드시 백업하세요.
- 캐릭터 값에 너무 큰 숫자를 넣으면 게임이 망가질 수 있습니다.
- 이 도구는 비공식이며 게임 개발사와 관련이 없습니다. 개인적인 싱글 플레이 용도이며, 사용에 따른 책임은 사용자에게 있습니다.
- 게임이 서버에서 데이터를 받아 오면(클라우드 저장, A/B 테스트) 일부 변경 사항이 되돌아갈 수 있습니다.
- 이 도구는 Android용입니다. iPhone에서는 게임 저장 파일에 접근할 수 없습니다.

---

✦ Bıçağı **musterlog** bileydi, [Claude](https://claude.ai) tuttu.

✦ **musterlog** sharpened the knife, [Claude](https://claude.ai) held it.
