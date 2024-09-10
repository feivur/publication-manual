# Významné body publikace Android aplikace na trhu Play

Měli byste začít registrací účtu vývojáře [dokumentace](https://support.google.com/googleplay/android-developer/answer/6112435). Je důležité zaregistrovat **organizační** vývojářský účet, nikoli osobní vývojářský účet.

Proces vytváření nové aplikace je popsán v nápovědě Google [dokumentace](https://support.google.com/googleplay/android-developer/answer/9859152).
V podstatě musíte proklikat několik formulářů, odpovědět na otázky týkající se účelu aplikace a souladu s mnoha právními požadavky.
Chcete-li navrhnout stránku aplikace, budete si muset připravit snímky obrazovky ze zařízení a další grafické zdroje.

Důležité poznámky, které je třeba vzít v úvahu. Bez nich vám bude zveřejnění odepřeno. Nezapomeňte, že před zveřejněním bude aplikace zkontrolována pozornými a vybíravými lidmi na Googlu.

1. Při navrhování stránky aplikace je důležité nahrát snímky obrazovky pořízené konkrétně z vaší aplikace. Kontrolou neprojdete, pokud rozhraní aplikace nebude obsahovat obrazovky, které jste uvedli na snímcích obrazovky.
2. Pokud žádáte o funkci **Místní oznámení**, pro sekci **Oprávnění služby na popředí** musíte nahrát video z obrazovky a nahlas vyslovit následující text: „Používáme oprávnění služby na popředí pro služba na pozadí pro příjem oznámení z našeho video serveru, když není k dispozici internet. Jedná se o náhradu za oznámení push pro místní síť."
3. V části **Advertising ID** uveďte, že používáte inzertní ID pro **analytiku**.
4. Pro sekce **Bezpečnost dat** a **Zásady ochrany osobních údajů** budete muset umístit text zásad ochrany osobních údajů **na své stránky** a poskytnout odkaz na tuto stránku.
5. Vyplnění sekce **Hodnocení obsahu** je možné pouze po nahrání sestavení aplikace do konceptu vydání.
6. Pokud vaše aplikace nemá demo server, může Google vyžadovat testovací účet pro kontrolu aplikace. Předejte jim tato data pro připojení: URL http://136.243.144.109:8000/asip-api, přihlašovací root, heslo root.
7. Pokud jste si místo účtu organizace zaregistrovali osobní účet, před publikováním aplikace budete muset provést uzavřené testování. Musí se jí zúčastnit minimálně 20 zařízení po dobu minimálně 14 dnů po sobě. Testování na simulátorech nebude fungovat, jsou potřeba skutečná zařízení. Google navrhuje hledat je téměř na ulici, hledat dobrovolníky mezi přáteli, známými a na fórech. V konzole musíte vytvořit seznam účtů testovacích zařízení. Po publikování aplikace v uzavřeném testovacím kanálu pošlete testerům odkaz na aplikaci, aby si ji nainstalovali. Podrobnosti [dokumentace](https://support.google.com/googleplay/android-developer/answer/14151465). Nejabsurdnější požadavek.

_Zeptejte se na nejasné aspekty publikace a my tento návod ihned doplníme o odpovědi_