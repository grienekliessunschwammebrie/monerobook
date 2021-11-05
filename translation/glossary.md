Glossar

Konto

Konten wurden als Teil des Subadressen-Systems erstellt. Eine Brieftasche hat einen Seed. Von diesem Seed werden die privaten Spend- und View-Schlüssel der primären Adresse abgeleitet. Von diesen privaten Schlüsseln werden Subadressen abgeleitet. Subadressen werden in Konten gruppiert.

Diese primäre Adresse ist die erste Adresse des ersten Kontos in der Brieftasche.

Jedes Konto verfügt über ein eigenes Guthaben und kann mit mehreren Unteradressen verknüpft sein. Da es sich bei Konten nur um Gruppierungen von Unteradressen handelt, gibt es so etwas wie eine Kontoadresse nicht (es sei denn, Sie zählen die erste Unteradresse im Konto als "Kontoadresse").

Da Konten und Subadressen deterministisch aus dem Seed abgeleitet werden, müssen Sie nur den Seed kennen, um die Struktur der Konten/Subadressen wiederherzustellen, wenn Sie eine Wallet wiederherstellen (obwohl alle Bezeichnungen, die Sie den Konten/Subadressen zuweisen, separat notiert werden müssen).
Adresse

Wenn Sie Monero an jemanden senden, benötigen Sie nur eine Information, und zwar die Monero-Adresse. Eine öffentliche Monero-Adresse besteht aus 95 Zeichen, die mit einer "4" beginnen.
Luftspalt

Ein Air Gap, Air Wall oder Air Gapping ist eine Netzwerksicherheitsmaßnahme, die auf einem oder mehreren Computern eingesetzt wird, um sicherzustellen, dass ein sicheres Computernetzwerk physisch von ungesicherten Netzwerken, wie dem öffentlichen Internet oder einem ungesicherten lokalen Netzwerk, isoliert ist.

Der Name leitet sich von der Technik ab, mit der ein Netz geschaffen wird, das physisch (mit einer konzeptionellen Luftlücke) von allen anderen Netzen getrennt ist. Die Luftlücke ist nicht unbedingt wörtlich zu nehmen, da Netze, die spezielle kryptografische Geräte verwenden, die Pakete über nicht vertrauenswürdige Netze tunneln und dabei Schwankungen in der Paketrate oder -größe vermeiden können, als Luftlücke betrachtet werden können, da Computer auf gegenüberliegenden Seiten der Lücke nicht kommunizieren können.
ASIC

Ein anwendungsspezifischer integrierter Schaltkreis (Application-Specific Integrated Circuit, ASIC) ist ein integrierter Schaltkreis (IC), der für einen bestimmten Zweck angepasst wurde und nicht für den allgemeinen Gebrauch bestimmt ist. Ein ASIC ist zum Beispiel ein Chip, der für ein digitales Diktiergerät oder einen hocheffizienten Bitcoin-Miner entwickelt wurde.
ASIC-Resistenz

ASIC-Resistenz bezieht sich auf Maßnahmen, die von einigen Kryptowährungen ergriffen werden, um sicherzustellen, dass ihr Mining-Algorithmus nicht mit diesen speziellen Geräten kompatibel ist. Siehe Kapitel 4, 5 und 6, um mehr darüber zu erfahren, wie die Monero-Gemeinschaft aktiv sicherstellt, dass unser CryptoNight-Algorithmus nur für CPU- und GPU-Miner zugänglich ist.
Bitmonero

BitMonero, früherer Name für das Monero-Projekt, siehe Kapitel 1. Einige alte Referenzen sind immer noch enthalten; zum Beispiel werden Protokolle und die Blockchain standardmäßig im Ordner ~/.bitmonero gespeichert.
Block

Ein Block ist ein Container mit Transaktionen, wobei im Durchschnitt alle 2 Minuten ein neuer Block zur Blockchain hinzugefügt wird.

Blöcke enthalten auch eine spezielle Art von Transaktion, die Coinbase-Transaktion, die neu erstellte Monero zum Netzwerk hinzufügt. Blöcke werden durch den Prozess des Minings erstellt. Der Knoten, der den Block erfolgreich schürft, sendet ihn an alle mit ihm verbundenen Knoten, die den Block anschließend erneut senden, bis das gesamte Monero-Netzwerk ihn erhalten hat.
Blockchain

Eine Blockchain ist eine verteilte Datenbank, die kontinuierlich mit einer Aufzeichnung aller Transaktionen wächst, die mit einer bestimmten Kryptowährung stattgefunden haben. Diese Datenbank wird oft als Hauptbuch bezeichnet, da die Daten eine große Liste von Transaktionen enthalten, die stattgefunden haben. In Monero werden diese Transaktionen alle 2 Minuten (im Durchschnitt) in Blöcken zusammengefasst, und alle Miner und Knoten im Netzwerk haben Kopien dieser Blöcke.
Bulletproofs

Bulletproofs sind ein neues mathematisches System für überprüfbare maskierte Transaktionsbeträge. Bulletproofs schrumpft die Transaktionsgröße um ~80% und reduziert damit die Gebühren drastisch.
Ändern Sie

Monero, die als Teil einer Transaktion verschickt werden und auf Ihr Konto zurückkehren, anstatt an einen anderen Empfänger zu gehen.
Coinbase-Transaktion

Eine spezielle Art von Transaktion, die in jedem Block enthalten ist und eine kleine Menge an Monero enthält, die an den Miner als Belohnung für seine Mining-Arbeit gesendet wird.
Befehlszeilenschnittstelle

Ein Command Line Interface (oder CLI) ist eine textbasierte Schnittstelle, die zur Eingabe von Befehlen über ein Terminal verwendet wird. Sie können die offizielle Monero CLI (kostenlos und quelloffen) unter https://getmonero.org/downloads/ herunterladen.
Konsens

Konsens beschreibt eine Eigenschaft von verteilten Netzwerken wie Monero, bei denen sich die meisten Teilnehmer an die Regeln halten und somit schlechte Teilnehmer ausschließen.
Kryptowährung

Eine digitale Währung, bei der Verschlüsselungstechniken verwendet werden, um die Generierung von Währungseinheiten zu regeln und den Geldtransfer zu verifizieren, und die normalerweise unabhängig von einer Zentralbank funktioniert.

Kryptografische Signatur

Eine kryptografische Methode zum Nachweis des Eigentums an einer Information sowie zum Nachweis, dass die Information nach dem Signieren nicht verändert wurde.
Decoys

Bei der Konstruktion einer Monero-Transaktion bezieht sich der Begriff "Decoy" auf eine Ausgabe (die nicht dem Spender gehört), die pseudo-zufällig aus der Blockchain ausgewählt wird, um als Mix-In für die Ringsignatur zu dienen. Siehe Abschnitt 5.4.3.
Stückelungen

Eine Stückelung ist eine genaue Beschreibung eines Währungsbetrags. Sie ist oft eine Untereinheit der Währung. Zum Beispiel ist ein Cent traditionell 1/100 einer bestimmten Währungseinheit.

Monero-Stückelungsnamen fügen SI-Präfixe hinzu, nachdem das anfängliche "mo" weggelassen wurde, um die Verwendung zu erleichtern. Die kleinste Einheit von Monero ist 1 Piconero (0,000000000001 XMR). Der Plural für Monero ist moneroj.

Name 	Base 	10 Amount
piconero 	10⁻¹² 	0.000000000001
nanonero 	10⁻⁹ 	0.000000001
micronero 	10⁻⁶ 	0.000001
millinero 	10⁻³ 	0.001
centinero 	10⁻² 	0.01
decinero 	10⁻¹ 	0.1
monero 	10⁰ 	1
decanero 	10¹ 	10
hectonero 	10² 	100
kilonero 	10³ 	1,000
meganero 	10⁶ 	1,000,000

Schwierigkeitsgrad

Die Schwierigkeit ist ein Netzwerkparameter, der sich darauf auswirkt, wie lange die Schürfer brauchen, um neue Blöcke zu finden, indem er die Messlatte für den Hashwert, der für die Fertigstellung eines Blocks erreicht werden muss, anhebt oder senkt. Wenn mehr Schürfer dem Netzwerk beitreten, erhöht sich die Schwierigkeit, um zu verhindern, dass Blöcke zu schnell entdeckt werden (und umgekehrt, wenn die Hash-Rate des Netzwerks sinkt).
Verschlüsselung

In der Kryptografie ist Verschlüsselung der Prozess, bei dem Nachrichten oder Informationen so verschlüsselt werden, dass nur autorisierte Parteien die gesendeten Daten entschlüsseln und lesen können. Die Verschlüsselung selbst verhindert nicht das Abfangen von Nachrichten, sondern verweigert dem Abfangjäger den Zugang zum Inhalt der Nachricht.
Gebühren

Jede Transaktion beinhaltet eine Gebühr, die von dem Miner eingezogen wird, der die Transaktion in einen abgeschlossenen Block aufnimmt. Benutzer mit Transaktionen mit hoher Priorität können eine relativ hohe Gebühr erheben, um den Minern einen Anreiz zu geben, die Transaktion früher zu bestätigen.
Fungibilität

In der Wirtschaftswissenschaft ist Fungibilität die Eigenschaft eines Gutes oder einer Ware, deren einzelne Einheiten im Wesentlichen austauschbar sind. Kryptowährungen mit transparenten Ledgern fehlt diese Eigenschaft, da jeder Coin eine einzigartige Geschichte hat, deren Verlauf öffentlich aufgezeichnet wird. Monero erreicht die Fungibilität durch die Kombination mehrerer Datenschutztechnologien, die verhindern, dass diese schädlichen Informationen auf der Blockchain gespeichert werden, und macht so alle Moneroj ununterscheidbar.
Fluffige Blöcke

Ein Block setzt sich aus einem Header und Transaktionen zusammen. Fluffy Blocks enthalten nur einen Header, eine Liste von Transaktionsindizes und alle Transaktionen, die dem Knoten, der den Block empfängt, fehlen könnten. Dies spart Bandbreite, da die Knoten möglicherweise bereits über die meisten oder alle Transaktionen im Block Bescheid wissen und diese nicht erneut gesendet werden müssen.
I2P

Das I2P Netzwerk bietet einen starken Schutz der Privatsphäre bei der Kommunikation über das Internet. Viele Aktivitäten, die im öffentlichen Internet ein Risiko für die Privatsphäre darstellen würden, können innerhalb von I2P anonym durchgeführt werden.
Integrierte Adresse

Eine integrierte Adresse ist eine Adresse, die mit einer verschlüsselten 64-bit Zahlungs-ID kombiniert ist. Eine rohe integrierte Adresse ist 106 Zeichen lang.
Kovri

Kovri ist eine C++ Implementierung des I2P Netzwerks. Kovri befindet sich derzeit in intensiver, aktiver Entwicklung und ist noch nicht mit Monero integriert. Wenn Kovri in Ihren Monero-Knoten integriert ist, werden Ihre Transaktionen sicherer als je zuvor sein.
Bergbau

Der Prozess der kryptographischen Berechnung eines mathematischen Beweises für einen Block, der eine Anzahl von Transaktionen enthält, die dann der Blockchain hinzugefügt werden.

Mining ist der verteilte Prozess der Bestätigung von Transaktionen im öffentlichen Hauptbuch aller Transaktionen, auch bekannt als Blockchain. Monero-Knoten verwenden die Blockchain, um legitime Transaktionen von Versuchen zu unterscheiden, Münzen, die bereits an anderer Stelle ausgegeben wurden, erneut auszugeben.

Monero wird ausschließlich durch Proof of Work betrieben. Es verwendet einen Mining-Algorithmus, der das Potenzial hat, effizient auf Milliarden von existierenden Geräten (jede moderne x86-CPU und viele GPUs) angewendet zu werden. Monero verwendet den CryptoNight Proof of Work (PoW) Algorithmus, der für den Einsatz in gewöhnlichen CPUs und GPUs konzipiert ist.

Die Smart-Mining-Funktion ermöglicht transparentes CPU-Mining auf dem Computer des Nutzers, weit entfernt von der faktischen Zentralisierung von Mining-Farmen und Pool-Mining, und verfolgt damit Satoshi Nakamotos ursprüngliche Vision einer echten P2P-Währung.
Mnemonic Seed

Eine Phrase mit 13 oder 25 Wörtern, die zur Sicherung eines Monero-Kontos verwendet wird und in mehreren Sprachen verfügbar ist. Diese 25-Wort-Phrase (13 Wörter im Fall von MyMonero) enthält alle Informationen, die benötigt werden, um Gelder von einem Monero-Konto einzusehen und auszugeben.
Monero

Die privatste Kryptowährung.

Knotenpunkt

Ein Gerät im Internet, auf dem die Monero-Software läuft, mit einer vollständigen Kopie der Monero-Blockchain, das das Monero-Netzwerk aktiv unterstützt.
OpenAlias

Im Grunde ist OpenAlias ein TXT-DNS-Eintrag für einen FQDN (vollqualifizierter Domainname). Das Monero Core Team hat einen Standard namens OpenAlias veröffentlicht, der viel besser lesbare Adressen ermöglicht und das Zooko-Dreieck "quadriert". OpenAlias kann für jede Kryptowährung verwendet werden und ist bereits in Monero implementiert.
Zahlungs-ID

Die Zahlungs-ID ist ein beliebiger und optionaler Transaktionszusatz, der aus 32 Byte (64 hexadezimale Zeichen) oder 8 Byte (im Falle von integrierten Adressen) besteht.

Die Zahlungs-ID wird normalerweise verwendet, um Transaktionen bei Händlern und Börsen zu identifizieren: Angesichts der in Monero eingebauten Datenschutzfunktionen, bei denen für eingehende Transaktionen in der Regel eine einzige öffentliche Adresse verwendet wird, ist die Zahlungs-ID besonders nützlich, um eingehende Zahlungen mit Benutzerkonten zu verknüpfen.

Seit der Version 0.9 von Hydrogen Helix können Zahlungs-IDs verschlüsselt und in eine Zahlungsadresse eingebettet werden, die als Integrierte Adresse bezeichnet wird (tatsächlich ist es die Integration zwischen der Zahlungs-ID und der Monero-Adresse). Die Zahlungs-IDs dieses Typs sollten 64-Bit groß sein und werden mit einem zufälligen Einmalschlüssel verschlüsselt, der nur dem Sender und dem Empfänger bekannt ist.

Es wird empfohlen, den Befehl integrated_address der offiziellen Wallet zu verwenden, um automatisch integrierte Adressen zu erzeugen, die kompakte Zahlungs-IDs enthalten. Wenn Sie die Befehlszeile verwenden möchten, können Sie Zahlungs-IDs wie folgt generieren:

$ openssl rand -hex 8

$ openssl rand -hex 32

Pedersen-Zusage

Pedersen Commitments sind kryptografische Algorithmen, die es einem Prover erlauben, sich auf einen bestimmten Wert festzulegen, ohne diesen zu verraten oder ihn ändern zu können.

Wenn Sie Monero ausgeben, werden der Wert der Inputs, die Sie ausgeben, und der Wert der Outputs, die Sie senden, verschlüsselt und sind für jeden außer dem Empfänger der Outputs undurchsichtig. Pedersen Commitments ermöglichen es Ihnen, Monero zu versenden, ohne den Wert der Transaktionen preiszugeben. Pedersen-Verpflichtungen ermöglichen es auch, zu überprüfen, ob die Transaktionen auf der Blockchain gültig sind und Monero nicht aus der Luft gegriffen ist.

Solange die verschlüsselten Ausgabebeträge, die eine Ausgabe für den Empfänger und eine Wechselgeldausgabe zurück an den Absender umfassen, und die unverschlüsselte Transaktionsgebühr der Summe der ausgegebenen Eingaben entsprechen, handelt es sich um eine legitime Transaktion und es kann bestätigt werden, dass Monero nicht aus der Luft gegriffen ist.

Pedersen-Verpflichtungen bedeuten, dass die Summen als gleich verifiziert werden können, aber der Monero-Wert jeder der Summen und der Monero-Wert der einzelnen Inputs und Outputs sind unbestimmbar. Pedersen-Verpflichtungen bedeuten auch, dass sogar das Verhältnis von einem Input zu einem anderen oder von einem Output zu einem anderen unbestimmbar ist.

Es ist unklar, welche Eingänge wirklich ausgegeben werden, da die Ringsignatur sowohl die echten Eingänge, die ausgegeben werden, als auch die Lockvogel-Eingänge auflistet, daher weiß man nicht, welche Pedersen-Verpflichtungen addiert werden müssen. Das ist in Ordnung, denn die RingCT-Ringsignatur muss nur beweisen, dass für eine Kombination der Eingaben die Ausgaben gleich der Summe der Eingaben sind. Aus mathematischen Gründen ist dies unmöglich zu fälschen.
Ring-Signaturen

In der Kryptografie ist eine Ringsignatur eine Art von digitaler Signatur, die von jedem Mitglied einer Gruppe von Benutzern, die alle über Schlüssel verfügen, durchgeführt werden kann. Eine mit einer Ringsignatur unterzeichnete Nachricht wird also von einer Person aus einer bestimmten Gruppe von Personen bestätigt. Eine der Sicherheitseigenschaften einer Ringsignatur besteht darin, dass es rechnerisch nicht möglich sein sollte, festzustellen, welcher der Schlüssel der Gruppenmitglieder zur Erstellung der Signatur verwendet wurde.

Eine Ringsignatur könnte beispielsweise verwendet werden, um eine anonyme Unterschrift von "einem hochrangigen Beamten des Weißen Hauses" zu liefern, ohne zu verraten, welcher Beamte die Nachricht unterzeichnet hat. Ring-Signaturen eignen sich für diese Anwendung, weil die Anonymität einer Ring-Signatur nicht widerrufen werden kann und weil die Gruppe für eine Ring-Signatur improvisiert werden kann (keine vorherige Einrichtung erforderlich).

Eine Ringsignatur verwendet Ihre Kontoschlüssel und eine Reihe von öffentlichen Schlüsseln (auch Outputs genannt), die mit Hilfe einer dreieckigen Verteilungsmethode aus der Blockchain gezogen werden. Im Laufe der Zeit können vergangene Outputs mehrfach verwendet werden, um mögliche Unterzeichner zu bilden. In einem Ring möglicher Unterzeichner sind alle Ringmitglieder gleich und gültig. In Monero werden Ringsignaturen verwendet, um den Absender der Transaktion zu verschleiern, indem mehrere mögliche Eingaben für die Transaktion (einschließlich Lockvögel) referenziert werden.
Ringgröße

Die Ringgröße bezieht sich auf die Gesamtzahl der möglichen Unterzeichner in einer Ringsignatur. Wenn für eine bestimmte Transaktion eine Ringgröße von 11 gewählt wird, bedeutet dies, dass es zusätzlich zu Ihrem "echten" Output 10 Decoy-Outputs gibt.

Stealth-Adresse

Stealth-Adressen sind ein wichtiger Bestandteil der Monero innewohnenden Privatsphäre. Sie ermöglichen und erfordern, dass der Absender für jede Transaktion im Namen des Empfängers eine zufällige, einmalige Adresse erstellt. Der Empfänger kann nur eine Adresse veröffentlichen, aber alle seine eingehenden Zahlungen gehen an eindeutige Adressen auf der Blockchain, wo sie weder mit der veröffentlichten Adresse des Empfängers noch mit den Adressen anderer Transaktionen in Verbindung gebracht werden können. Durch die Verwendung von Stealth-Adressen können nur der Absender und der Empfänger feststellen, wohin eine Zahlung gesendet wurde.
Tail-Emission

Monero Block Rewards werden niemals auf Null fallen. Die Block-Belohnungen werden schrittweise sinken, bis die Tail Emission Ende Mai 2022 beginnt. Zu diesem Zeitpunkt werden die Rewards auf 0,6 XMR pro Block festgelegt.
Transaktionen

Ein kryptographisch signierter Container, der den Transfer von Monero an einen Empfänger (oder mehrere Empfänger) beschreibt.

Die Parameter einer Transaktion enthalten eine oder mehrere Empfängeradressen mit entsprechenden Geldbeträgen und einen Ringgrößenparameter, der die Anzahl der an die Transaktion gebundenen Ausgänge angibt. Je mehr Ausgänge verwendet werden, desto höher ist der Grad der Verschleierung, aber das hat auch seinen Preis. Da eine Transaktion mit mehr Ausgängen größer wird, sind die Transaktionsgebühren höher.

Es ist möglich, eine Transaktion offline durchzuführen, was zusätzliche Vorteile für den Datenschutz bietet.

Eine Transaktion kann durch die Verwendung einer optionalen Transaktions-ID eindeutig identifiziert werden, die in der Regel durch eine 32-Byte-Zeichenkette (64 hexadezimale Zeichen) dargestellt wird.
Wallet

Ein Monero-Konto, oder Wallet, speichert die Informationen, die zum Senden und Empfangen von Moneroj notwendig sind. Zusätzlich zum Senden und Empfangen speichert die Monero-Wallet-Software einen privaten Verlauf Ihrer Transaktionen und ermöglicht es Ihnen, Nachrichten kryptografisch zu signieren. Sie enthält auch Monero-Mining-Software und ein Adressbuch.

