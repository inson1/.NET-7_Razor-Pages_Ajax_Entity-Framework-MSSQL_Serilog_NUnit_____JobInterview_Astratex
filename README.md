# .NET-7_Razor-Pages_Ajax_Entity-Framework-MSSQL_Serilog_NUnit_____JobInterview_Astratex

Kalkulačka

![image](https://user-images.githubusercontent.com/75314629/223372439-b1af167c-b78a-421c-babd-af1739b293fa.png)

Zadání:

Vytvořte webovou stránku s jednoduchou kalkulačkou, která umožňuje základní početní operace (sčítání, odčítání, násobení, dělení) dvou čísel s desetinnými místy.

Součástí kalkulačky bude také historie operací, kdy se při načtení stránky zobrazí posledních deset operací.

Ačkoli se jedná o jednoduchou aplikaci, proveďte její zpracování tak, jako by se jednalo o větší projekt, který se bude v budoucnu rozšiřovat. Zohledněte tedy udržitelnost kódu.

Aplikaci vytvořte pomocí Visual Studio. Můžete využít libovolné šablony pro C# projekt a libovolnou technologii (MVC, Razor Pages, WebForms, …).

Požadavky:

• Při práci s kalkulačkou nesmí docházet k přenačítání stránky.

• Každý provedený výpočet bude logován do databáze.

• Výsledek výpočtu bude po kliknutí na „spočítat“ zobrazen na displeji a celý výpočet
v historii.

• Aplikace by měla být vhodně rozvrstvena.

• Oddělte logiku kalkulačky tak, ať je možná implementovat do jiného projektu a ať je schopna vracet chybové zprávy do metody: void SendError(Exception exception);

• Umožňěte nastavit kalkulačku tak, ať vrací celá čísla.

• Oddělte datovou vrstvu.

Co nemusíte řešit:

• Vzhled – bylo by hezké kalkulačku trochu graficky upravit, ale není to to, co je zde důležité. Kalkulačka tedy nemusí vypadat tak, jako je vyobrazeno zde.

• Nemusíte logovat chybové stavy aplikace. Pouze chyby sbírejte do metody SendError, která nebude nic vykonávat.

Něco navíc:

• Vytvořte Unit test pro logiku výpočtu.

• Logovat chybové zprávy do souboru
