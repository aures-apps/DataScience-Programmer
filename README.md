# DataScience - Zadání cvičení pro pozici Programmer
Vytvořte jednoduché webovky pomocí Flasku.
Webovou stránku nadesignujte jako jednoduché zadání platby přes internetové bankovnictvní.
Aplikaci připravte tak, aby se v budoucnu mohla dále jednoduše rozšiřovat.

Uživatel bude fungovat pouze na jedné stránce, kde bude vidět Navbar, formulář (pro zadání platby) a footer.
V Navbaru můžou být blank odkazy.
V pravém rohu bude dynamické aktualní datum a kdo má a svátek. Informaci o tom kdo má svátek čerpejte z tohoto API: https://app.swaggerhub.com/apis/nekvapil/InternationalNamedayAPI/3.0.0


Je zapotřebí zakomponovat input field pro částku v CZK, element pro výběr výchozí měny a finální přepočítanou čásku.
K získání aktuálních měnových kurzů použijte tento odkaz: https://www.cnb.cz/cs/financni-trhy/devizovy-trh/kurzy-devizoveho-trhu/kurzy-devizoveho-trhu/denni_kurz.txt

Jaké ostatní informace bude uživatel zadávat je na vás.

Animace, popup okna ani validace input fieldů nejsou zapotřebí.
	
Formátovat v css můžete přes vlastní vytvořené CSS classy nebo přes libovolný framework - Bootstrap atd.
V případě použítí frameworku, upravte některé classy pomocí vlastního CSS souboru.
Pro práci s oběma odkazy použijte Python knihovnu Requests.
Pro další práci s měnovými kurzy použijte Python.
