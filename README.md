# Zadání úkolu

Pomocí knihovny [Flask](https://flask.palletsprojects.com/en/1.1.x/) v Pythonu
vytvořte jednoduchou webovou aplikaci, která bude obsahovat pouze jednu stránku.
Tuto stránku nastylizujte do podoby platebního příkazu v internetovém bankovnictví.
Webovou aplikaci připravte tak, aby se v budoucnu mohla dále jednoduše rozšiřovat.

Webová stránka musí obsahovat následující:

- hlavičku s navigační lištou (může obsahovat prázdné odkazy),
- v pravém horním rohu:
	- aktualní datum,
	- informaci o tom, kdo má v daný den svátek,
- formulář pro zadání platby s následujícími komponenty:
	- pole pro zadání částky v CZK,
	- element pro výběr měny,
	- pole pro částku přepočítanou do cizí měny,
- patičku.

Doplňující informace:

- Jaké ostatní informace bude uživatel zadávat, je na vás.
- Animace, vyskakovací okna ani validace vstupních hodnot nejsou zapotřebí.
- Formátovat v CSS můžete přes vlastní třídy anebo přes libovolný framework.
V případě použítí frameworku upravte některé třídy pomocí vlastního CSS souboru.
- Odkazy:
  - Informaci o tom, kdo má v daný den svátek, čerpejte z [tohoto API](https://app.swaggerhub.com/apis/nekvapil/InternationalNamedayAPI/3.0.0).
  - K získání aktuálních měnových kurzů použijte [tento odkaz](https://www.cnb.cz/cs/financni-trhy/devizovy-trh/kurzy-devizoveho-trhu/kurzy-devizoveho-trhu/denni_kurz.txt).
  - Pro práci s oběma odkazy použijte knihovnu [Requests](https://docs.python-requests.org/en/master/).

Projekt můžete zaslat i nekompletní, například pokud si nebudete vědět rady s jednou z uvedených technoloogií.
