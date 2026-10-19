# MICRON TECHNOLOGY (MU) — RE-DERIVACE PÁSMA v6 | 2026-10-19

**Standard v6 | Jazyk: čeština | Entita: Micron Technology, Inc., CIK 723125 (ověřeno na titulce 10-K FY2026: fiscal year ended September 3, 2026, 53 týdnů)**
**Režim: David MU NEDRŽÍ. Staré pásmo $750 je zrušeno pravidlem F. Nové pásmo je odvozené z 10-K a normalizace přes cyklus, ne z ceny. Není investiční doporučení; výstup slouží výhradně pro interní rozhodování Davida.**

Značení: [PRIM] = 10-K / 10-Q | [SEK] = proxy, transkripty, vyjádření managementu | [LIVE] = tržní data | [ODHAD] = vlastní výpočet nebo úsudek.

---

## 0. NEJDŮLEŽITĚJŠÍ: CO TENTO BĚH NEUMÍ (přečti první)

Verdikt v sekci 9 je **použitelný, ale s vědomými mezerami**. Dvě z nich zasahují přímo osy 2 a 5.

| Mezera | Rozsah | Dopad |
|---|---|---|
| **10-K FY2026: Item 8 (výkazy a Notes) chybí** | Text z Drive končí v MD&A (Critical Accounting Estimates, PDF str. ~80 ze 130). Rozvaha, výkaz CF, Notes (Note 16 Revenue and Customer Contract Liabilities, zásoby, PP&E, D&A, pohledávky, Note 9 Debt) nejsou v extraktu. EDGAR je z prostředí blokovaný (curl 403 z proxy). `download_file_content` pro 8 MB PDF shodilo MCP spojení. | Osa 2 (účtování SCA) stojí na 10-Q FQ3 [PRIM] a MD&A, ne na Note 16 z 10-K. Osa 5 nemá absolutní hodnoty pohledávek, odpisů ani objem „consideration payable to customers". Pásmo tím nepadá, ale jistota v ose 5 je nižší. |
| **10-K FY2026: Item 1 (Business), 1C, 2 nečteno celé** | Přečteno: MD&A celé, Item 5 celý, Risk Factors přes diff proti FY2025 a klíčová slova. | Diff rizik je odstavcový, ne slovo po slovu. Drobná změna formulace uvnitř dlouhého odstavce mi mohla uniknout. |
| **Hlavní call FQ4 (30. 9.): Q&A useknuté** | Soubor končí uprostřed otázky Harlana Sura (JPMorgan, po pěti analytících). | TOP 5 neodpovězených otázek (sekce 8) vychází z hlavního callu + post-callu FQ4 (ten je kompletní). Co se v useknuté části ještě ptalo, nevím. |
| **Nepřečteno** | 10-Q FQ1 a FQ2 FY2026, call FQ1 FY2026, call FQ4 FY2025, 10-K FY2025 mimo diff rizik. Call FQ2 (18. 3.) ve složce není vůbec. FQ3 call ve složce je **post-call** (Q&A s CBO, COO, CFO), ne hlavní call s prepared remarks. | Test přesnosti guidance napříč 4 cally je neúplný (viz sekce 8). |
| **Historie FY2019–FY2021** | Ve složkách není. Dostupné jsou jen FY2022–FY2026 ([PRIM] z 10-K FY2024 a FY2026). | Normalizace stojí na pětiletém okně FY2022–FY2026 včetně dna FY2023. Delší okno by pásmo pravděpodobně nezvedlo (FY2019–21 byly standardní cyklické roky), ale nemám to z dokumentu. |
| **Cena [LIVE]** | Nemám tržní data. Použit snímek stockanalysis.com ve složce: **$878,84, close 16. 10. 2026 (−5,63 %)** [SEK, snímek 19. 10. 06:52]. Web search ceny z 19. 10. nenašel. | Aktuální cenu ověř ručně. Pásma níže jsou v absolutních $, takže poloha vůči nim se dá přepočítat okamžitě. |
| **Form 4 po srpnu** | EDGAR blokovaný. Web search nenašel žádné Form 4 Mehrotry ze září/října 2026. | Neznamená „žádné prodeje", znamená „nenalezeno sekundárně". Ověř ručně na EDGARu (CIK 723125). |
| **CXMT IPO ($8,5 mld.), 2. továrna v Pekingu, Apple waiver** | V žádném dokumentu složek ani v 10-K. | Použito jen jako kontext ze zadání, nic nestojí na těchto tvrzeních (pravidlo A). |

**Čtyři čísla ze zadání neodpovídají dokumentům:**
1. **„$22 mld. projektovaných depozit (FQ3)"** je stav z června. Aktuálně: finanční závazky zákazníků **$32 mld., „vast majority cash deposits"** (call FQ4 [SEK]); přijaté depozity v roce **$12,75 mld.** [PRIM, 10-K, financing CF]; depozity na rozvaze k FQ4 **$12,7 mld.** [SEK, CFO]. Z 32 mld. je tedy zatím skutečně v bance zhruba 40 %, zbytek jsou pohledávky z budoucích plateb zákazníků.
2. **„GM vrchol ~81 %"** je celoroční průměr FY2026 (81 % [PRIM]). Vrchol kvartální je **87 % ve FQ4** a guidance FQ1 FY27 je **86,25 %** [SEK].
3. **„Mehrotra Form 4 červenec $37,3 mil."**: sekundární zdroj (MarketBeat) uvádí 28. 7. 2026 prodej 31 285 akcií za ~$926,83 = ~$29,0 mil. a po prodeji 313 218 akcií. Rozdíl může být součet více Form 4. Neověřeno v primárním zdroji.
4. **„Capex program $100+ mld."**: z 10-K plyne capex FY2026 **$30,7 mld. hrubý, ~$27,4 mld. po státních pobídkách** (−$3,32 mld.), FY2027 H1 ~$25 mld. a H2 vyšší [PRIM/SEK]. Součet přes roky $100+ mld. v dokumentech nevidím jako jedno číslo.

**Pozor na pasti v souborech (ověřeno z obsahu):** snímky stockanalysis mají v hlavičce „NYSE: ANET" / „Arista Networks (ANET)". Je to artefakt webu, obsah je Micron (CFO Murphy, FQ4 2026, 30. 9. 2026). MU je na Nasdaq. Soubor `MU_call_FY2026-Q3_transcript.pdf` je post-call z 24. 6. 2026.

---

## 1. VERDIKT V KOSTCE

- **Při ceně ~$879 MU nesplňuje žádnou ze tří úrovní.** Vážená férová hodnota z normalizovaných zisků vychází **~$720** (rozpětí $640–$775 podle vah scénářů), tedy cena je asi **+22 % nad ní**.
- **Nové pásmo [ODHAD]: zajímavá ≤ $650, atraktivní ≤ $520, výjimečná ≤ $410.** Do zajímavé zóny chybí −26 %.
- **Co cena implicitně věří:** že ~65 % hrubá marže na tržbách ~$140 mld. (tedy zhruba FY2026 objem) je trvalá přes cyklus. Management slibuje pro FQ1 FY27 marži 86 %, ale historická pětiletá hrubá marže vážená tržbami je 58 % včetně supercyklu a **30 % bez něj** (FY22–FY25).
- Pásmo $750 vs. nový střed ~$720: **shoda je náhodná.** Staré pásmo bylo cenový práh, nové je vážený průměr tří scénářů a vstupní úrovně jsou hluboko pod ním (marže bezpečnosti).
- **Největší jednotlivý faktor:** doba trvání rentového období (kolik čtvrtletí zůstane marže >60 %). Posun 10 procentních bodů pravděpodobnosti ze scénáře „cyklus jako vždy" do „SCA = strukturální změna" hýbe férovou hodnotou o ~$80.

---

## 2. FAKTICKÉ UKOTVENÍ [PRIM]

### 2.1 Výsledky FY2022–FY2026 (USD mil.)

| | FY2022 | FY2023 | FY2024 | FY2025 | FY2026 |
|---|---|---|---|---|---|
| Tržby | 30 758 | 15 540 | 25 111 | 37 378 | **133 188** |
| Hrubý zisk | 13 898 | (1 416) | 5 613 | 14 873 | **107 504** |
| Hrubá marže | 45 % | **−9 %** | 22 % | 40 % | **81 %** |
| Provozní zisk | n/d | n/d | 1 304 | 9 770 | **99 340** |
| Čistý zisk | 8 687 | **(5 833)** | 778 | 8 539 | **84 969** |
| Efektivní daň | 9,3 % | n/d | 36,4 % | 11,6 % | 14,8 % |

Zdroje: FY2022–FY2024 z výkazu v 10-K FY2024; FY2024–FY2026 z MD&A 10-K FY2026. **Dno cyklu FY2023 definuje spodek:** tržby −49 %, hrubá marže −9 %, čistá ztráta $5,8 mld. FY2024 obsahoval $987 mil. přínosu z prodeje dříve odepsaných zásob (reálná FY2024 marže byla níže než 22 %).

**Pětiletá statistika [ODHAD, aritmetika z výše]:**
- Hrubá marže vážená tržbami FY22–FY25 (bez supercyklu): **30,3 %**. FY22–FY26: **58,0 %**.
- Čistý zisk: průměr FY22–FY25 **$3,0 mld./rok**; FY22–FY26 součet $97,1 mld. (průměr $19,4 mld.), z toho FY2026 je 87 %.
- **Davidovo zadání „normalizovaná GM 40–45 %" je tedy štědré.** Dosáhly ho jen dva roky z pěti (FY22 45 %, FY25 40 %). Je to předpoklad, že HBM mix, konsolidace na tři dodavatele a SCA zvedly dno nad čtyřletý průměr 30 %. V pásmu to beru jako střední případ scénáře 1, ne jako pesimistický.

### 2.2 Dekompozice FY2026: cena vs. objem [PRIM s rekonciliací]

| | Tržby | Cena (ASP) | Objem (bity) | Kontrola |
|---|---|---|---|---|
| DRAM FY26 | +252 % (×3,52) | ~+180 % (×2,80) | mid-20 % (×1,25) | 2,80 × 1,25 = 3,50 ✓ |
| NAND FY26 | +274 % (×3,74) | ~+200 % (×3,00) | mid-20 % (×1,25) | 3,00 × 1,25 = 3,75 ✓ |
| DRAM FY25 | +62 % (×1,62) | low-40 % (×1,42) | mid-teen (×1,15) | 1,42 × 1,15 = 1,63 ✓ |

**Podíl ceny na růstu tržeb [ODHAD, logaritmický rozklad]: DRAM FY26 ~82 %, NAND FY26 ~83 %, DRAM FY25 ~72 %.** Dvouletě: ASP DRAM ~×3,98 a bity ~×1,44 vs. FY2024. **Zhruba čtyři pětiny růstu je cyklická cena, jedna pětina strukturální objem.** To je jádro důvodu, proč normalizace dává zisk řádově pod výkazným.

Náklady na bit: COGS FY26 $25,7 mld. vs. $19,5 mld. (FY24) při objemu ×1,44 → **náklad na bit −9 % za dva roky** (−13 % po očištění FY24 o $987 mil.) [ODHAD]. Management přitom avizuje růst nákladu na bit (HBM trade ratio, greenfield).

### 2.3 Segmenty FY2026 [PRIM]

| BU | Tržby | Podíl | Provozní marže |
|---|---|---|---|
| CMBU (cloud) | 43 085 | 32 % | 72 % |
| CDBU (core data center) | 37 592 | 28 % | 79 % |
| MCBU (mobile/client) | 36 601 | 27 % | 80 % |
| AEBU (auto/embedded) | 15 886 | 12 % | 71 % |

Všechny čtyři segmenty mají provozní marži 71–80 %. **I „spotřebitelský" MCBU (PC/telefony) je na 80 %**, a to při poklesu bitů (tržby +209 % „zčásti kompenzováno nižšími bity, dodávky přesměrovány jinam"). FQ4: GM CMBU 83 %, CDBU 90 %, MCBU 90 %, AEBU 84 % [SEK]. HBM (v CMBU) je tedy marginálně **méně** ziskové než konvenční DRAM; management zvedá HBM ceny pro CY2027 „významně", aby mezeru zúžil.

### 2.4 Cash flow a bilance [PRIM]

- OCF FY26 **$89,7 mld.** (FY25 $17,5 mld.); investiční výdaje $30,7 mld. hrubé; státní pobídky $3,3 mld.
- Hotovost a investice **$73,45 mld.**, dluh $5,2 mld., čistá hotovost $68,3 mld. [SEK]. Splaceno dluhu $10,0 mld.
- Zpětný odkup v FY26: jen $650 mil. (2,5 mil. akcií) + $1,13 mld. na daň z RSU; dividenda $0,15/akcii/čtvrtletí.
- **Nová autorizace zpětných odkupů $35,16 mld. od 9. 12. 2026** (základ: ~$2,16 mld. zbylo + 100 % adjusted FCF FQ4 $33,2 mld. − dividendy). CHIPS dohody omezují odkupy do 9. 12. 2026 a pak vázány na FCF po odečtu grantů [PRIM, Item 5].
- Pillar Two: Singapurské pobídky čistě přinesly $2,21 mld. (**$1,93 na akcii**). Z toho odvozený počet zředěných akcií ~1,145 mld. → **GAAP EPS FY26 ≈ $74,2** [ODHAD]. Management uvádí non-GAAP EPS $75,52 (+811 %) [SEK].

---

## 3. OSA 1: NORMALIZOVANÁ ZISKOVOST [JÁDRO]

### 3.1 Co říká guidance (pro FY2027) [SEK]
FQ1 FY27: tržby $61,5 mld. ±1,5, GM ~86,25 %, opex ~$2,06 mld., EPS **$38,15 ±1**, ~1,15 mld. akcií, daň ~15,5 %. FQ1 označeno za **podlahu marže roku**. Opex FY27 +$2,5 mld. Capex FQ1 ~$11,5 mld., H1 ~$25 mld., H2 vyšší. Odhad FY27 EPS při sekvenčním růstu tržeb ~$165–$170 [ODHAD z extrapolace guidance, ne vyjádření firmy]. To je **P/E ~5,2× při $879**.

**Fiskální past (nové zjištění):** FY2026 měl **53 týdnů** [PRIM] a FQ4 byl **14týdenní** (FQ3 skončil 28. 5., rok 3. 9.: 98 dní) [odvozeno z 10-Q a 10-K]. FQ1 FY27 je 13týdenní. Reportovaný růst FQ4 +31 % q/q (z $41,4 na $54,2 mld.) tedy obsahuje ~7 % z extra týdne; tržby na týden: **$3,87 mld. → $4,73 mld. (FQ1 guide) = +22 %**, ne +13,5 %, jak by to vypadalo z reportovaných čísel. Pro pásmo to nic nemění, ale pro srovnání FQ1 vs. FQ4 ano (viz prahy v sekci 9e).

### 3.2 Normalizace přes cyklus: tři scénáře

Rámec: per-share volný cash flow (po capexu, bez toku depozit) FY27–FY31 diskontovaný 10 %, terminální hodnota z normalizovaného EPS na konci okna, plus čistá hotovost po odečtu depozit **$48/akcii** (($68,3 − $12,7) / 1,15) [ODHAD]. Všechny hodnoty jsou [ODHAD], cílem je ukázat strukturu, ne přesnost.

| | S1: cyklus jako vždy | S2: prodloužená těsnost, měkké přistání | S3: SCA = strukturální změna |
|---|---|---|---|
| Příběh | Ceny se vrací ze ~2029 (první velké nové čisté místnosti: ID1 polovina 2027, ID2 konec 2028, Hiroshima, Singapur NAND, Tongluo), konkurence investuje stejně | Těsnost do 2029–30, SCA floory drží, GM klesá po schodech na 55–60 % | GM 65–70 % trvale, konkurence disciplinovaná, trade ratio HBM + greenfield drží náklad na bit nahoře |
| FCF/akcii FY27, 28, 29, 30, 31 ($) | 100, 95, 45, 12, 8 | 100, 110, 95, 70, 55 | 105, 125, 125, 115, 110 |
| Normalizované EPS (terminál) | $18 × 13 | $40 × 14 | $85 × 14 |
| Hodnota 1 akcie | **~$410** | **~$730** | **~$1 225** |
| Váha [ODHAD] | 35 % | 45 % | 20 % |

**Vážená férová hodnota: ~$718 → $720.** Citlivost vah: 25/50/25 → $775; 45/40/15 → $661; 45/45/10 → $636. **Rozpětí $640–$775.**

Normalizovaná marže scénáře 1 (42,5 % GM, tržby ~$65 mld. při bitech ×1,75 vs. FY25 a ASP na úrovni FY25, opex ~$10 mld., daň 15,5 %) dává čistý zisk ~$15 mld. a EPS ~$13. Terminál $18 počítá s mírně lepším cyklem. Pokud by se GM vrátila na čtyřletý průměr 30 %, S1 padá k ~$330 a vážená hodnota o ~$30.

### 3.3 Sanity check: co musí cena $879 věřit o permanenci vysoké marže
Při terminálním násobku 14× a čisté hotovosti $48/akcii potřebuje cena **normalizovaný čistý zisk ~$68 mld.** (EPS ~$59). Při opex ~$12 mld. a dani 15,5 % to znamená hrubý zisk ~$93 mld.:
- při **GM 80 %** tržby ~$116 mld.,
- při **GM 65 %** tržby ~$143 mld. (zhruba FY26),
- při **GM 42,5 %** tržby ~$218 mld. (o ~65 % víc než rekordní FY26, bez dalšího růstu ceny nereálné).

**Cena tedy věří buď, že 65 % marže na objemu FY26 je trvalý stav, nebo že tržby při 40 % marži vyrostou o dvě třetiny. Obojí je daleko od čtyřletého průměru FY22–FY25.**

### 3.4 Pravidlo B: kolik z AI hodnoty připadá akcionářům MU
Nordhaus-kotva ~3 % [ODHAD, kotva ze zadání]. Převedeno: normalizovaný zisk $190 mld. (FY27 run-rate) odpovídá 3% podílu jen při celkovém ročním AI přebytku ~**$6,3 bil.**; normalizovaný zisk ~$20 mld. (S1/S2) při ~**$0,7 bil.** Žádné z čísel nelze z dokumentů ověřit. Pravidlo B mi dává jen měřítko poměru: **současné zisky vyžadují, aby jeden dodavatel jedné komponenty zachytil řádově víc než typický inovátor v dlouhodobých datech.** To podporuje, že vysoké renty přitahují konkurenci a vyjednávací tlak zákazníků, a proto drží S1 na 35 %.

---

## 4. OSA 2: ARCHITEKTURA SCA [PRIM + SEK]

**Co dokumenty říkají:**
- Take-or-pay, závazné objemy, víceletá doba (mimo auto obvykle 5 let, SCA do 2031 už podepsány) [SEK]. 26 SCA celkem, 10 nových za FQ4, kryjí **>35 % tržeb do 2030**; cíl ~50 % „ale může být méně" [SEK].
- Ceny: ~3/4 SCA tržeb má definovaný rámec (fix nebo floor/ceiling), ~1/4 se vyjednává periodicky podle trhu [SEK].
- **Ceiling u největších dohod „aproximuje tržní cenu v 2. kvartálu CY2026"** a floor drží po celou dobu [PRIM, 10-Q FQ3, MD&A]. FQ4 call: nové SCA se vyjednávají na vyšších cenách. Ve FQ4 přitom ceny DRAM vzrostly o high-teens % a NAND o ~30 % q/q [SEK]. **Starší SCA s ceilingem tedy dnes nejspíš prodávají pod spotem [ODHAD]** (zákazník drží call opci na cenu, MU drží prodanou call). Vlastní výklad, firma to neříká.
- **Floor GM firma nikdy nečísluje.** „I při floor cenách marže výrazně nad jakýmkoli cyklickým vrcholem" [PRIM, MD&A 10-K] — minulý kvartální vrchol je mimo dokumenty složek, takže práh nelze změřit.

**Účtování [PRIM 10-Q FQ3 Note 14 + 10-K MD&A]:**
- Depozity = **contract liabilities**, „primarily included in other noncurrent liabilities" (10-Q), v CF jako **financing** ($12,75 mld. proceeds, 10-K). **Neinflují OCF ani FCF**, to je čisté.
- Vrací se zákazníkovi „v druhé polovině doby", **„nearly all between 2029 and 2031"** [PRIM, 10-K]. Sadana: „není to prepaid revenue … nebude to poměrně rozpuštěno." Depozit tedy není záloha na zboží, slouží jako zajištění.
- Při nesplnění minim může MU depozit **zadržet zcela nebo zčásti** (10-K) a je „jedním z dostupných remedií, ne jediným" (Sadana). Letters of credit od třetích bank: **$7 mld.** k 3. 9. 2026 (přístup jen při defaultu).
- RPO: **$5 mld. k 28. 5.** [PRIM, 10-Q] → **~$150 mld. k FQ4** [SEK, CFO]. Skok 30× za jeden kvartál. Důvody mohou být legitimní (10 nových SCA, 10-Q do RPO počítal jen smlouvy s fixem/bandem), ale **definici a rekonciliaci ověřit v Note 16 10-K, kterou jsem nečetl.**

**Drží „quasi-SaaS" teze? Ne doslova.** SaaS má recurring revenue bez nutnosti prodat fyzické bity za cenu, která se mění. SCA je **zajištěný prodej fyzického zboží s cenovým koridorem**. Je to silné pro volatilitu (floor + take-or-pay na ~35 % tržeb), ale: (i) ceiling dává upside zákazníkovi, (ii) 65 % tržeb je mimo SCA a vystaveno spotu, (iii) depozit je **dluhem vůči zákazníkovi** ($12,7 mld. dnes, až ~$30 mld. při plném inkasu, splatnost 2029–31 — přesně v době, kdy hrozí cyklický zlom a vysoké capexy).

### Pravidlo C: kdo platí a z čího
Dokumenty říkají: SCA zahrnují „some hyperscalers" (Sadana, FQ3), v 26 smlouvách jsou „small to large" odběratelé a existují ve všech BU včetně MCBU [SEK]. **Jmenovitě nikdo, ani rozdělení podle financování nejde z dokumentů sestavit.** Pozorování:
1. **$7 mld. letters of credit** u části smluv ukazuje, že minimálně někteří protistrany potřebují bankovní kredit (v hyperscalerské cash-rich verzi by LC nebyla potřeba) [ODHAD, úsudek].
2. **Kapitálově financované řetězce (laby, neo-cloudy, vendor financing)** se v SCA mohou skrývat, aniž by to firma uvedla. Z toho plyne konkrétní test: poměr inkasovaných depozit ($12,7 mld.) k přislíbeným ($32 mld. celkem, „vast majority cash") a vývoj v čase. Pokud se inkaso zastaví, signalizuje to problém protistrany.
3. Z výstupu pro 2027 je přes 75 % „committed" (SCA i non-SCA zákazníci, včetně POs) [SEK]. Non-SCA objednávky nejsou take-or-pay, takže „committed" tam znamená slabší závazek než u SCA.

---

## 5. OSA 3: UDRŽITELNOST MARŽÍ

- **Management sám říká, že náklad na bit poroste:** HBM trade ratio (více křemíku na bit), LPDRAM, greenfield bez leverage na stávající kapacitě, start-up náklady ($100–200 mil./čtvrtletí navíc v 2027, Murphy) [SEK, FQ3 post-call]. Další $1 mld. ročně na incentive comp, start-up a ostatním [SEK, FQ4 call].
- **FQ1 guidance poznámka CFO:** „single-digit sekvenční růst bitů a **double digit for cost** pro DRAM i NAND" [SEK, FQ4 post-call, doslovný přepis]. Formulace je nejednoznačná (zda jde o růst nákladu na bit, nebo je přepis zkomolený). Pokud jde o růst nákladu na bit o >10 % q/q, je to zásadní údaj pro marži, proto ho dávám do otázek k vyjasnění na FQ1 callu.
- **Podlaha marže „FQ1" je slib**: FQ2 by měl mít vyšší GM než FQ1 (CFO). Selhání tohoto slibu je okamžitý signál (sekce 9e).
- **Nabídka vs. poptávka v 10-K versus cally:** v 10-K (risk factors) zůstává: „Efforts by us and our competitors to align supply to long-term customer agreements could contribute to industry supply exceeding demand if customers were to breach..." [PRIM] — tj. vlastní riziko, že SCA se samy staví na kapacitu, která se může vrátit jako přebytek. Cally: „nemáme line of sight, kdy se nabídka a poptávka vyrovnají" (opakovaně). **Jazyk calls je jednostranně pozitivní, 10-K uvádí obojí.**
- **Capex trajektorie:** FY25 $15,9 mld. → FY26 $30,7 mld. hrubé (původní plán navyšován v červnu na ~$27 mld. net) → FY27 H1 ~$25 mld. a H2 vyšší; analytici rozumí >$50 mld. [SEK]. Většina navýšení je **výstavba čistých místností pro konec 2028+** [SEK]. Bity z nich půjdou do trhu přesně v okně, kde S1 předpokládá zlom.
- **Čínská konkurence a export tradeoff**: viz sekce 6.

---

## 6. OSA 4: CXMT / ČÍNA (pravidlo A — přísně)

**Diff risk factors FY2026 vs. FY2025 [PRIM]:**
- Věta „…hrozba rostoucí konkurence a přebytku nabídky DRAM a NAND díky významným investicím čínské vlády a státních entit, jako CXMT a YMTC" je **doslova beze změny** v obou ročnících. Jmenovitě uvedeni Samsung, SK hynix, Kioxia, Sandisk, CXMT, YMTC — beze změny.
- Nové/rozšířené oproti FY25: odkaz na **Section 301 šetření (20. 2. 2026)** v obchodní rizikové části; formulace o „novém a navrhovaném exportním omezení produktů podporujících AI aplikace" a o riziku pro nákup vzácných zemin. Změněný odstavec o struktuře tržeb: „asi třetina tržeb FY26 od zákazníků se sídlem mimo USA, ~70 % tržeb z produktů expedovaných mimo USA" (podíl samotné Číny 10-K v přečtených částech neuvádí).
- **Žádná eskalační formulace k CXMT v 10-K tedy není.** Dle pravidla v zadání (eskalace v risk factors = okamžitá re-derivace) tento test dnes **nespouští**.

**Co říká management [SEK, max úroveň dle pravidla A]:** expozice vůči Číně **single-digit % v FY27** (Bhatia); technologické vedení „alespoň dva uzly před čínskou konkurencí" (DeBoer); CXMT/YMTC prodávají „převážnou většinu v Číně" a mimo Čínu je neviděli (Sadana, červen). **Jde o sebehodnocení konkurenta, ne o nezávislý benchmark.** Neověřitelné → pracuje se scénáři: v S1 je CXMT jedním z důvodů zlomu cen v letech 2029+.

---

## 7. OSA 5: KVALITA ZISKU

| Položka | Co vím [PRIM/SEK] | Hodnocení |
|---|---|---|
| OCF vs. zisk | OCF $89,7 mld. vs. čistý zisk $85,0 mld. (1,06×). FQ4: OCF $44,0 mld. vs. provozní zisk $44,6 mld. | Konverze solidní, ale zčásti z **neuhrazených daní a mezd**: nárůst závazků „mostly related to income and other taxes" a **nekurentní splatná daň z Pillar Two** [PRIM]. |
| Pohledávky | „Significant increase in receivables due to higher revenue" [PRIM, MD&A]. Absolutní hodnota **chybí** (Item 8). | Neověřeno. Priorita pro doplnění. |
| Zásoby | FQ4 $10,4 mld., DIO **129 dní (+9 sekvenčně)**; zahrnují node end-of-life build-ahead a výrobní část navýšených incentive comp, jejíž dopad půjde do COGS ve FQ1 (~**$1 mld.**) [SEK]. | Při rostoucích cenách LCNRV riziko nehrozí. DIO >120 při deklarované „extrémní těsnosti" je zajímavé (sekce 8). |
| „Consideration payable to customers for pricing adjustments" | Růst ostatních běžných závazků „mainly from higher consideration payable to customers for pricing adjustments" [PRIM, MD&A]. Částka v extraktu **není**. | Nová položka: cenové úpravy/slevy zákazníkům rostou. Může jít o price protection u distributorů (Critical Accounting Estimates), nebo o retroaktivní úpravy v SCA. Ověřit v Note. |
| GAAP vs. non-GAAP | EPS $75,52 (non-GAAP) vs. ≈ $74,2 (GAAP odvozeno) [ODHAD]. Rozdíl ~2 %. | Spread je malý — zisk není zdobený. |
| Daň | Pobídky Singapur čistě $2,21 mld. ($1,93/akcii); ETR 14,8 % → 15,5 % v FY27 [PRIM/SEK]. | Normalizovaná daň je ~15,5 %; použito. |
| Odpisy vs. capex | Capex $30,7 mld.; **odpisy FY26 v extraktu nejsou.** CHIPS granty a 35% ITC se účtují **jako snížení účetní hodnoty aktiv a následně odpisů** [PRIM, Critical Accounting Estimates] → odpisy i COGS jsou nižší, než kdyby šlo o grant do výnosu. | Under-depreciation test nelze dokončit. Dopad pobídek na marži je pozitivní a **nenormalizovatelný** bez Note 15. |
| 53. týden | FY26 = 53 týdnů (~+1,9 % tržeb) [PRIM]. | Meziroční růst je nadsazen ~2 p. b.; v roce 2027 bude srovnávací základna tvrdší. |

---

## 8. ROZPORY MANAGEMENTU [SEK] A OTÁZKY

**Rozpory a anti-patterny:**
1. **„Cenová koridor" jako ochrana vs. ceiling u Q2 2026 cen:** SCA se prodávají jako stabilita, ale ceiling aproximuje cenu z 2. čtvrtletí, kdy FQ4 ceny dál rostly o high-teens (DRAM) a ~30 % (NAND). Zákazník koupil call za cenu Q2; firma se vzdala části upsidu (viz sekce 4).
2. **„Customers asking for more supply" vs. „modestly lower content growth than prior expectations"** (CEO, FQ4). Zároveň MCBU bity klesají druhý kvartál po sobě a PC/telefony mohou mít „double-digit unit declines" [SEK]. Poptávková elasticita se objevuje na okraji. Management ji rámuje jako „customers ship more units".
3. **„Disciplined" vs. capex ×2:** FY27 capex vyšší než dříve plánováno, „pull forward of equipment spending", většina navýšení je konstrukce na 2028+ [SEK]. Disciplína je deklarovaná, ne měřitelná. Navíc nejde o kapacitu, jež by byla vybavena „when needed" — ale o rozhodnutí postavit.
4. **„We do not have line of sight to when supply and demand will return to balance"** (opakovaně v FQ4 i FQ3). Podobný jazyk „strukturální změny" se v odvětví opakuje v každém horním bodě cyklu [ODHAD, obecný úsudek; v přečtených dokumentech neověřeno, pouze dno FY2023 je doložené v sekci 2.1].
5. **Guidance přesnost** [SEK]: FQ4 tržby, GM a EPS „exceeded the high end of guidance" (CEO). Jedna dostupná datová řada (FQ4); kompletní test FQ1–FQ3 chybí (nepřečteno). Pozitivní, ale **konzervativní guidance při rostoucích cenách není důkaz kvality, jen rostoucího trhu.**
6. **Kompenzace [SEK, proxy FY2025, VH 15. 1. 2026]:** STI = 50 % profitability (adjusted non-GAAP NI nebo non-GAAP operating margin), zbytek strategické/ESG; PRSU: **50 % rTSR vs SOX (55. percentil), 25 % HBM3E+ podíl/bity, 25 % DC SSD podíl/bity** s „higher of revenue-based share or bit shipments", stretch: NAND FCF a **expanze výroby DRAM v USA**. **Žádná metrika ROIC ani návratnost kapitálu.** Odměňuje se podíl, objem a expanze, tedy přesně to, co v cyklu produkuje nadkapacitu. Zisky FY2026 pak spustily jednorázové zvýšení incentive comp pro všechny zaměstnance ve FQ4 a $300 mil. komunitních investic (opex +$1,1 mld. q/q).
7. **Insider prodeje:** 10b5-1 prodeje Mehrotry v 2026 (květen 40 000 ks / $21,5 mil., červen ~$38 mil. dohromady, 28. 7. 31 285 ks ≈ $29 mil.) [SEK, sekundární]. Záměrně nehodnotím jako signál, plán je předem daný. Zároveň září 2026: **nové manažerské jmenování** (Bhatia President/COO, DeBoer President/CTPO) [SEK].

**TOP 5 otázek bez odpovědi:**
1. **Jaká je GM při floor cenách?** „Výrazně nad minulým vrcholem" zaznělo třikrát, číslo nikdy.
2. **Kdo jsou protistrany a kolik z $32 mld. už dorazilo?** Depozity $12,7 mld. na rozvaze vs. $32 mld. závazků; LC $7 mld.; podíl hyperscalerů vs. kapitálově financovaných není.
3. **Co se stane při nesplnění?** „Zadržet všechno nebo část depozitu" je jediná uvedená konkrétní sankce; zda existovala nějaká dohoda o změně nebo odklad, není.
4. **Součet kapacit 2028–2030:** jaký je očekávaný růst průmyslových DRAM bitů v CY2029 po otevření ID1, ID2, Hiroshimy, Tongluo, Singapuru + kapacity SK hynix a Samsung? Management dává jen CY2026–2028 (low-20s % DRAM, mid-20s % NAND).
5. **RPO $150 mld. a rekonciliace** s $5 mld. v 10-Q FQ3: jaká definice, jaká doba, kolik z toho je fixní cena vs. floor.

---

## 9. VERDIKT — NOVÉ PÁSMO [ODHAD] (hlavní výstup)

**(a) Férová hodnota a sanity check.** Vážená férová hodnota **~$720** (rozpětí $640–$775). Sanity check (3.3): cena $879 věří v trvalých ~65 % hrubé marže na ~$140 mld. tržeb. Čtyřletý průměr GM bez supercyklu je 30 %, Davidovo zadání 40–45 %.

**(b) Tři úrovně** (marže bezpečnosti vůči ~$720 a vztah k scénářům):

| Úroveň | Cena | Logika | Podmínky platnosti (osy 1–2) |
|---|---|---|---|
| **Zajímavá** | **≤ $650** | ~10 % pod váženou férovou hodnotou, cena = S1 + zhruba 3/4 cesty k S2 | FQ1 FY27 GM ≥ 85 %; FQ2 guide GM ≥ FQ1; přijaté depozity ≥ $12 mld. a nerostou dispute; žádná eskalace CXMT v rizicích |
| **Atraktivní** | **≤ $520** | ~28 % pod FV; cena = S1 + ~1/3 cesty k S2 (trh platí 60 %+ pravděpodobnost „cyklu jako vždy") | Všechny výše + SCA kryjí ≥ 35 % tržeb, RPO ≥ $150 mld., DIO klesá |
| **Výjimečná** | **≤ $410** | = hodnota S1; za SCA/strukturální opci neplatíš nic | Všechny výše + inkaso depozit pokračuje k $25 mld.+ |

Aktuální $879 je +35 % nad horní hranicí první úrovně. **Do „zajímavé" chybí −26 %.**

**(c) Symetrický test (à la NVDA revize 18. 9.).** Kalibrace: posun 10 p. b. pravděpodobnosti S1 → S3 mění FV o **+$80**; opačně −$80.
- **Pásmo posune NAHORU (+$80 každých 10 p. b.):** (i) SCA kryjí >45 % tržeb a floor GM zveřejněn nad 70 %; (ii) FQ2 guide GM výrazně nad FQ1 při stabilní ceně; (iii) depozity dorazí k $25 mld.+ bez storna; (iv) konkurence (SK hynix, Samsung) veřejně drží capex discipline a potvrdí SCA-like kontrakty v dokumentech, (v) velká část nových SCA bez ceilingu.
- **Pásmo posune DOLŮ (−$80):** (i) FQ2 guide GM ≤ FQ1; (ii) q/q ASP DRAM pod +5 % při rostoucích bitech; (iii) DIO >140 při „extrémní těsnosti"; (iv) pokles inkasa depozit nebo jakýkoli dispute / zadržení; (v) další zvýšení capexu bez odpovídajícího SCA; (vi) eskalace CXMT v rizicích; (vii) opakované zrušení/„despec" HBM u velkého zákazníka potvrzené v číslech (zatím pouze zvěsti, management popírá).

**(d) Podmínky platnosti pásma.** Pásmo platí, dokud (1) FQ1 FY27 GM ≥ 85 %, (2) 10-K/10-Q nezmění definici RPO ani nepřidají storno, (3) risk factors nepřidají eskalační formulaci k CXMT/YMTC nebo exportu do Číny, (4) cena depozit nezačne klesat. **Okamžitá re-derivace**, pokud nastane cokoli z (2)–(3) nebo pokud management sníží FQ1 guidance GM pod 84 %.

**(e) Prahy pro FQ1 FY27 (~polovina prosince 2026, 13týdenní kvartál)**

| Metrika | Guidance | Práh „potvrzuje" | Práh „zpochybňuje" |
|---|---|---|---|
| Tržby | $61,5 mld. ±1,5 | ≥ $60 mld. | < $58 mld. |
| GM | ~86,25 % | ≥ 85 %; FQ2 guide ≥ FQ1 | < 84 %, nebo FQ2 guide < FQ1 (rozbíjí „Q1 = floor") |
| EPS non-GAAP | $38,15 ±1 | ≥ $37 | < $35 |
| DIO | 129 dní (FQ4) | < 125 | > 140 |
| Depozity na rozvaze | $12,7 mld. | rostou k $20 mld.+ | stagnují |
| SCA | 26 smluv, >35 % tržeb | ≥ 30 smluv, pokrytí ≥ 40 % | pokles pokrytí nebo zrušení |
| Capex | FQ1 ~$11,5 mld., H1 ~$25 mld. | v plánu | zvýšení bez nových SCA |
| Odkupy | autorizace $35,16 mld. od 9. 12. | skutečná realizace | jen autorizace bez nákupů |
| Bity q/q | single-digit | ≥ mid-single | pokles |

Pro srovnání na týden (kvůli 14 vs. 13 týdnům): FQ4 $3,87 mld./týden, FQ1 guide $4,73 mld./týden.

**(f) Co kandidaturu diskvalifikuje:** (1) zjištění v Note 16 / Item 8, že SCA obsahují odstoupení, force-majeure či cenovou renegociaci, kterou management nezveřejnil; (2) deklarované snížení floor marže; (3) rozpory mezi RPO $150 mld. a Note; (4) selhání platby protistrany nebo opakované zadržování depozitu; (5) tvrdá eskalace obchodních omezení vůči Číně, která zasáhne 10-K jazyk (nová formulace) nebo vstup do uzlu.

**(g) Pravidlo D (tchajwanský agregát, PENDING).** MU má v Tchaj-wanu velkou část operací (DRAM a HBM výroba, nově Tongluo za $1,8 mld. od PSMC) [PRIM]; podíl tchajwanských wafer výstupů nelze z přečtených stránek vyčíslit. Při stropu 35 % a stávajícím ASML + AVGO ≈ 2,5 % rámce je volného místa dost, takže strop MU **sám neblokuje**; verdikt je ale **podmíněn rozhodnutím o stropech (PENDING)**, protože se mění způsob započtení (podle sídla vs. podle provozní expozice). Velikost případné tranše proto formuluji podmíněně: dokud rozhodnutí o stropech nepadne, počítat s konzervativnější velikostí, než by dávala samotná cenová úroveň (konkrétní číslo nechávám na Davidově rámci, tu konvenci neznám). **Při ceně nad $650 se otázka velikosti nestaví.**

**Shrnutí jednou větou:** MU je mimořádně ziskový kvalitní cyklik se skutečnou, ale ne zdokumentovaně trvalou strukturální změnou (SCA); při $879 cena platí za trvalost, kterou čtyřletá historie nepodporuje, nová pásma jsou **$650 / $520 / $410**, nejbližší datový bod je FQ1 FY27 v polovině prosince, a doplnění Item 8 a Note 16 pásmo nejspíš nezmění, pokud potvrdí popsané. Odhalí-li storno, renegociaci nebo jinou definici RPO, posune se dolů.

---

## 10. AUDIT PROVEDENÉ PRÁCE

- **Ověřeno přímo ve zdroji:** tržby, GM, provozní a čistý zisk FY2024–FY2026, segmentové tržby a marže, DRAM/NAND ASP/bit dekompozice, CF a likvidita, depozity $12,75 mld. a LC $7 mld., autorizace $35,16 mld., 53týdenní rok, risk factor diff CXMT/CAC, text SCA v 10-Q FQ3 (RPO $5 mld., ceiling Q2'26, $22 mld. a $18 mld. cash), FY2022–FY2023 z 10-K FY2024, metriky odměňování z DEF 14A (FY2025, VH 15. 1. 2026, ročník správný).
- **Převzato z transkriptů [SEK]:** 26 SCA, >35 % tržeb, $32 mld. závazků, RPO ~$150 mld., FQ4 čísla (GM 87 %, tržby $54,2 mld., EPS $33,42, DIO 129, depozity $12,7 mld.), guidance FQ1, single-digit Čína, „dva uzly" náskok.
- **[ODHAD] (vlastní aritmetika/úsudek):** GAAP EPS ≈ $74,2 (z $2,21 mld. a $1,93), tržní kapitalizace ~$1,01 bil., podíly cena/objem, váhy a hodnoty scénářů, tři úrovně pásma, týdenní normalizace FQ4 vs. FQ1, Nordhaus převody, výklad ceilingu jako prodané call opce.
- **Citlivost modelu:** hodnoty scénářů jsou citlivé na diskont (10 %), terminální násobky (13–14×) a profil FCF; model ukazuje strukturu a ne přesnost. Váhy 35/45/20 jsou úsudek, ne měření.
- **Nezískáno:** viz sekce 0 (Item 8, Note 16, EDGAR, Form 4, FQ1/FQ2 podklady).
- **Konflikt se zadáním:** čtyři čísla (depozita, GM vrchol, Form 4, capex) opravena podle dokumentů, viz sekce 0.

*Není investiční doporučení. Výstup slouží výhradně pro interní rozhodování Davida.*
