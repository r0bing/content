---
title: "Blockchain-Bla-Bla"
description: "Blockchain-Technologien haben es irgendwie geschafft, ausgerechnet das Schlimmste aus beiden Welten zu vereinen ..."
date: "2022-02-04T20:00:00+01:00"
tags: 
  - "bitcoin"
  - "blockchain"
  - "krypto"
  - "dao"
  - "dezentralisierung"
  - "ethereum"
  - "nft"
  - "web3"
syndication_urls: ["https://social.tchncs.de/web/@r0bin/108346785063104658"]
---
Bei der Zukunft des Internets sind *Blockchains* und darauf aufbauende Systeme offenbar ein großes Ding. Warum das so ist? Ganz einfach:

Dank der **Dezentralisierung** sind die Daten in Blockchains auf vielen unterschiedlichen Servern verteilt, die wiederum von unzähligen Menschen und Organisationen betrieben werden. Diese Organisation der Daten steht im Gegensatz zur herkömmlichen Art, bei der ein einziges Unternehmen alle Daten auf dessen Servern speichert. Und gleichzeitig sorgt die **Unveränderlichkeit** der Daten in einer Blockchain dafür, dass diese nicht wie in konventionellen Datenbanken noch nachträglich geändert oder gar gelöscht werden können.

Allerdings fällt auf, dass zwischen Theorie und heutigem Ist-Zustand wesentliche Unterschiede bestehen; dass gerade Befürwortende Blockchain-basierter Technologien oft zwischen diesen beiden Bereichen hin- und herwechseln, je nachdem, wie es ihrem Argument dient. Ein Beispiel: Bei der theoretischen Frage, ob eine der großen Handelsplattformen den Umtausch der Bitcoins eines Dissidenten in Euro oder Dollar stoppen könne, möglicherweise auf Anordnung einer Regierung, wird behauptet, dass dies in der Theorie kein Problem darstellt. Schließlich gäbe es ja noch andere Börsen, die einen Umtausch akzeptieren können.

Wenn man aber dann die Frage stellt, wie diese Ökosysteme mit jemandem umgehen, der ein NFT <cite>[^1]</cite> aus kinderpornografischen Inhalten erstellt, dann wird auf Lösungen verwiesen, die nur deshalb Lösungen sind, weil sie auf der enorm zentralisierten Natur dieser Marktplätze beruht. Das NFT wird ganz einfach von *OpenSea* und anderen Börsen gestrichen, sodass die große Mehrheit der Menschen, dieses zum Glück nie zu Gesicht bekommt.

[^1]: Vgl. Dieter Petereit, „Was sind NFT? Wir erklären den Krypto-Hype“, [https://t3n.de/news/krypto-nft-ethereum-art-collectibles-1356849/](https://t3n.de/news/krypto-nft-ethereum-art-collectibles-1356849/)

Warum sollte der Dissident bei einer solchen Vorgehensweise dann aber noch Hoffnung haben, seine Coins bei anderen Börsen tatsächlich in Euro umwandeln zu können?

In diesem Text soll es darum gehen, wie diese Technologien heute in der Praxis funktionieren und eben nicht, wie sie in einer zukünftigen Welt möglicherweise stattfinden könnten.

## Dezentralität

Freunde der Blockchain heben oft den eingangs erwähnten dezentralen Charakter hervor. Und ja, im Gegensatz zu populären Diensten, sprich *Facebook*, *Google* oder *iCloud*, werden die Daten hier nicht auf Servern gespeichert, die einem einzigen Unternehmen gehören. Genauso klar ist, dass die allermeisten Dienste, die wir täglich nutzen, nun mal zentralisiert strukturiert sind. Allerdings glaube ich, dass das tatsächliche Ausmaß der Dezentralisierung im Web3 <cite>[^2]</cite> überschätzt wird. Die Daten auf der Blockchain selbst sind zwar dezentralisiert, zumindest auf den populären Blockchains, aber ungefähr da hört dann auch schon die Dezentralisierung auf. Denn wenn ich nun beispielsweise eine dApp <cite>[^3]</cite> auf einer bestimmten Blockchain erstellen möchte, muss ich normalerweise auf eine der wenigen APIs <cite>[^4]</cite> zurückgreifen, die abermals von einzelnen, zentralen Unternehmen wie *Alchemy* entwickelt wurden. Was bleibt mir also übrig, wieder oder vielmehr weiterhin Vertrauen in die relativ wenigen, zentralen Plattformen zu setzen?

[^2]: Vgl. Jürgen Geuter, „The Third Web“, [https://tante.cc/2021/12/17/the-third-web/](https://tante.cc/2021/12/17/the-third-web/)
[^3]: Vgl. Paul Wackerow, „Introduction to dapps“, [https://ethereum.org/en/developers/docs/dapps/](https://ethereum.org/en/developers/docs/dapps/)
[^4]: Vgl. Wikipedia, „Programmierschnittstelle“, [https://de.wikipedia.org/wiki/Programmierschnittstelle](https://de.wikipedia.org/wiki/Programmierschnittstelle)

{{< figure src="/img/essays/blockchain/hfsp.gif" title="Quelle: giphy.com" link="https://giphy.com/gifs/cryptomkg-crypto-meme-gif-have-fun-staying-poor-bgbgVPLFmaQdEGIsxG" >}}

So, jetzt habe ich im Internet gelesen, ich bliebe arm, würde ich nicht in Kryptowährungen investieren. Also entscheide ich mich zwischen den vier, fünf großen Handelsplattformen wie *Coinbase*, *Binance* oder *Bitpanda*, bei denen ich meine Euros gegen Ether, Bitcoin oder andere Kryptowährungen tauschen kann. Sollte ich NFTs kaufen oder gar verkaufen wollen, gelingt mir das wohl am besten bei OpenSea. Der Marktplatz war Ende 2021 für mehr als 95 % des NFT-Handels verantwortlich. <cite>[^5]</cite> Und wenn ich dann noch einer DAO <cite>[^6]</cite> beitreten möchte, weil wenn schon Web3, dann auch richtig, müsste ich wahrscheinlich ganz auf die Blockchain verzichten, um mit anderen Gleichgesinnten zu interagieren. Stattdessen nutzen wir einfach *Discord*: eine zentralisierte, (zumindest noch) blockchainlose Chat-Plattform, die auf von Google gemieteten Servern läuft. Selbst dezentrale Teile des Web3 sind überraschend zentralisiert. Als Anfang Dezember 2021 weite Teile der *Amazon Web Services* (aws) ausfielen, ging die selbsternannte „largest decentralized exchange by trading volume“ *dYdX* mit ihr down. <cite>[^7]</cite> Und nochmal kurz zurück zu NFTs: Hier werden in der Regel übrigens nicht die Bilddaten selbst auf der Blockchain gespeichert, sondern bloß die URL, die auf ein anderswo gespeichertes Bild verweist. Anderswo heißt dann oft Hallo Web 2.0, Hallo *Google Cloud*, Hallo *Dropbox*.

[^5]: Vgl. Scott Nover, „What Coinbase’s entry into the NFT market means for OpenSea“, [https://qz.com/2073503/coinbase-poses-a-threat-to-openseas-nft-dominance/](https://qz.com/2073503/coinbase-poses-a-threat-to-openseas-nft-dominance/)
[^6]: Vgl. Cathy Hackl, „What Are DAOs And Why You Should Pay Attention“, [https://www.forbes.com/sites/cathyhackl/2021/06/01/what-are-daos-and-why-you-should-pay-attention/](https://www.forbes.com/sites/cathyhackl/2021/06/01/what-are-daos-and-why-you-should-pay-attention/)
[^7]: dYdX, „dYdX V4 – Full Decentralization“, [https://dydx.exchange/blog/v4-full-decentralization](https://dydx.exchange/blog/v4-full-decentralization)

## Unveränderlichkeit

Zurück zur Annahme, dass, sobald etwas in die Blockchain geschrieben wurde, es nicht mehr geändert oder gelöscht werden kann. Eine Transaktion ist endgültig und kann nur von der Person am anderen Ende rückgängig gemacht werden. Mein affen.jpg ist mein affen.jpg und wenn ich es an eine andere Person übertrage, gehört es ihr.

Naja, nicht wirklich. Ein frühes und bemerkenswertes Beispiel ist der Fall von *The Dao*, einem Projekt, das oft als die erste DAO überhaupt bezeichnet wird. Im Juni 2016 nutzten Angreifer:innen eine Sicherheitslücke aus, um 3,6 Millionen ETH (damals umgerechnet 50 Millionen US-Dollar) der 11,5 Millionen ETH (rund 160 Millionen US-Dollar) des Projekts zu stehlen. Daraufhin wurde die Ethereum-Blockchain einfach „hard forked“, d. h., die Gelder wurden auf eine Wiederherstellungsadresse zurückgesetzt, sodass sie dann zurückgegeben werden konnten. <cite>[^8]</cite> Solche Vorkommnisse sind keine Seltenheit: Projekte können, wenn sie technisch dazu in der Lage sind, Angriffe „rückgängig“ machen, bevor Hacker:innen gestohlene Token in eine andere Währung umwandeln. Sogenannte Token-Swaps oder -Forks stellen Snapshots dezentraler Finanzprojekte wieder her, wobei die ursprünglichen Bestände der User:innen zurückgesetzt werden und der Wert der gestohlenen Token auf 0 sinkt. <cite>[^9]</cite>

[^8]: Vgl. Wikipedia, „The DAO (organization)“,[https://en.wikipedia.org/wiki/The_DAO_(organization)](https://en.wikipedia.org/wiki/The_DAO_(organization))
[^9]: Vgl. Chris Williams, „$8.2M Lost as Visor Finance Suffers Latest DeFi Hack“, [https://cryptobriefing.com/8-2m-lost-visor-finance-suffers-latest-defi-hack/](https://cryptobriefing.com/8-2m-lost-visor-finance-suffers-latest-defi-hack/)

Und hey, der Mythos der Dezentralisierung kann sich auch mit dem der Unveränderlichkeit überschneiden: Und zwar bei NFTs. Mein affen.jpg ist nur so lange mein affen.jpg, bis eine der zentralen Börsen entscheidet, dass es gar nicht rechtmäßig mir gehört. Sie frieren sie einfach ein, meine kleinen Äffchen. In einer wirklich unveränderlichen, dezentralisierten Welt, in der der Code das Gesetz ist („code is law“) und keine zentrale Instanz eingreifen kann, wäre die Übertragung des Vermögenswerts endgültig, ganz unabhängig davon, wie sie schlussendlich erfolgt ist. Bei Diebstählen prominenter und zumeist teurer NFTs wie den *Bored Apes*, kann eine Börse wie OpenSea, wenn sie hinreichend davon überzeugt ist, dass ein NFT-Transfer nicht rechtmäßig war, diesen einfrieren, sodass er dort nicht mehr gehandelt werden kann. Klar, man könnte es nun an kleineren, weniger genutzten Börsen versuchen, aber fun habe ich da eher nicht mehr – I’m staying poor. Ähnliches gilt bei Kryptowährungen: Wenn zentrale Börsen davon überzeugt sind, dass Token unrechtmäßig übertragen wurden, werden die Adressen, die diese Token enthalten, markiert und können nicht mehr gehandelt werden.

## The worst of both worlds

Blockchain-Technologien haben es irgendwie geschafft, ausgerechnet das Schlimmste aus beiden Welten zu vereinen: ein bisschen dezentralisiert, ein bisschen unveränderlich, aber eigentlich beides auch nicht wirklich. Die Unveränderlichkeit besteht darin, dass, wenn ich meine Token dummerweise Betrüger:innen sende, diese unveränderlich futsch sind. Es gibt keine Instanz, die eingreifen und entscheiden kann, dass die Transaktion ungültig war. Auf der anderen Seite bedeutet es, dass Daten, die in eine Blockchain geschrieben werden, egal wie abscheulich sie auch sein mögen, dort grundsätzlich für immer verbleiben. Es liegt dann einzig an den Plattformen, sie nicht freizugeben. Und zu guter Letzt besteht immer die Gefahr (der Notwendigkeit) eines Hard Fork: Die Menschen, die sich damals bei The DAO dafür entschieden hatten, bei der ursprünglichen, „ungeforkten“ Version zu bleiben, wurden mit (Ethereum-Classic-)Token zurückgelassen, die heute hundertmal weniger wert sind als die geforkte Version, Ethereum.

{{< detail-tag "**Quellenverzeichnis**" >}}

dYdX (2022): dYdX V4 – Full Decentralization. In: dydx.exchange.  
URL.: [https://dydx.exchange/blog/v4-full-decentralization](https://dydx.exchange/blog/v4-full-decentralization)  
[Abgerufen: 22.01.2022\].

Geuter, Jürgen (2021): The Third Web. In: tante.cc.  
URL.: [https://tante.cc/2021/12/17/the-third-web/](https://tante.cc/2021/12/17/the-third-web/)  
[Abgerufen: 11.01.2022\].

Hackl, Cathy (2021): What Are DAOs And Why You Should Pay Attention. In: forbes.com.  
URL.: [https://www.forbes.com/sites/cathyhackl/2021/06/01/what-are-daos-and-why-you-should-pay-attention/](https://www.forbes.com/sites/cathyhackl/2021/06/01/what-are-daos-and-why-you-should-pay-attention/)  
[Abgerufen: 15.01.2022\].

Nover, Scott (2021): What Coinbase’s entry into the NFT market means for OpenSea. In: qz.com.  
URL.: [https://qz.com/2073503/coinbase-poses-a-threat-to-openseas-nft-dominance/](https://qz.com/2073503/coinbase-poses-a-threat-to-openseas-nft-dominance/)  
[Abgerufen: 15.01.2022\].

Petereit, Dieter (2022): Was sind NFT? Wir erklären den Krypto-Hype. In: t3n.de.  
URL.: [https://t3n.de/news/krypto-nft-ethereum-art-collectibles-1356849/](https://t3n.de/news/krypto-nft-ethereum-art-collectibles-1356849/)  
[Abgerufen: 20.01.2022\].

Wackerow, Paul (2022): Introduction to dapps. In: ethereum.org.  
URL.: [https://ethereum.org/en/developers/docs/dapps/](https://ethereum.org/en/developers/docs/dapps/)  
[Abgerufen: 11.01.2022\].

Wikipedia (o.J.a): Programmierschnittstelle. In: wikipedia.org.  
URL.: [https://de.wikipedia.org/wiki/Programmierschnittstelle](https://de.wikipedia.org/wiki/Programmierschnittstelle)  
[Abgerufen: 11.01.2022\].

Wikipedia (o.J.b): The DAO (organization). In: wikipedia.org.  
URL.: [https://en.wikipedia.org/wiki/The_DAO_(organization)](https://en.wikipedia.org/wiki/The_DAO_(organization))  
[Abgerufen: 11.01.2022\].

Williams, Chris (2021): $8.2M Lost as Visor Finance Suffers Latest DeFi Hack. In: cryptobriefing.com.  
URL.: [https://cryptobriefing.com/8-2m-lost-visor-finance-suffers-latest-defi-hack/](https://cryptobriefing.com/8-2m-lost-visor-finance-suffers-latest-defi-hack/)
[Abgerufen: 21.01.2022\].

{{< /detail-tag >}}