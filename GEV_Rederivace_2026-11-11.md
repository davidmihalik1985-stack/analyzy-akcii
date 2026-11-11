# GE VERNOVA (GEV): RE-DERIVACE VSTUPNÍHO PÁSMA (pravidlo G) | 2026-11-11

**Forenzní běh v6 | Jazyk: čeština | Entita: GE Vernova Inc., CIK 1996810 | Navazuje na baseline 19. 6. 2026, refresh 22. 7. 2026 a balíček rev. 3 z 28. 10. 2026**
**Režim: RE-DERIVACE. Staré pásmo $800 je suspendováno. Nové pásmo je odvozeno zdola z normalizovaného FCF 2027E. Cena slouží jen k závěrečnému srovnání. Není investiční poradenství.**

Značení: [PRIM] = 10-Q / 10-K / oficiální release a slidy | [SEK] = earnings call, baseline, refresh, balíček | [LIVE] = vyžaduje ověření v reálném čase | [ODHAD] = vlastní výpočet nebo úsudek.

---

## 0. Zdroje a mezery v datech

| Dokument | Typ | Stav |
|---|---|---|
| 10-Q Q3 2026 (`10_q_q3_26GEV.pdf`) | [PRIM] | Přečten celý (169k znaků, po Signatures). Několik tabulek (Note 17, rekonciliace s. 23) mělo rozházenou textovou vrstvu. Byly zrekonstruovány a ověřeny součty. |
| Q3 2026 Earnings Press Release, 3Q-26 Earnings Presentation (42 slidů) | [PRIM] | Přečteno celé |
| Q3 2026 earnings call (28. 10.) | [SEK] | Přečten celý (26 str.). Hlavička PDF chybně uvádí „Arista Networks", obsah je GEV. |
| 10-Q Q2 2026, release a slidy Q2, call Q2 | [PRIM]/[SEK] | Přečteno. Textová vrstva slidů Q2 je rozházená. |
| 10-K FY2025 | [PRIM] | **Jen do PDF str. 70/115 (Note 2).** Notes 3–25 (contract liabilities, warranty, dluh) chybí. |
| Baseline 19. 6., refresh 22. 7., balíček rev. 3 | [SEK] | Přečteno |
| Proxy DEF 14A / Form 4 | — | **Form 4 v knihovně nejsou, proxy zůstává nečitelná (OCR, viz refresh 1.1).** |
| Tržní cena | [LIVE] | Bez živých dat. Jako orientační bod slouží $797,04 (close 10. 11. 2026) z hlavičky přepisu Q3 callu [SEK, metadata]. **Ověř ručně.** |

**ARM-8:** Davidův odhad nového pásma v zadání **chybí** (pole „David doplní při zadávání" zůstalo prázdné). Srovnání odhad × výstup tedy neprovádím. Doplň ho do chatu před čtením sekce 3.

**Rozpor v zadání ohledně pozice:** Balíček rev. 3 tvrdí, že GEV „NENÍ držena" a $800 je „čekající pásmo". Baseline 19. 6. ale uvádí „Vstupní cena (DCA) $800, dnes ~$910 = +13,8 % nad vstupem" a refresh 22. 7. „+34–38 % nad vstupem $800, pozice". Stav pozice potvrď ručně. Na odvození pásma to vliv nemá.

---

## 1. TL;DR VERDIKT

1. **Obrat Wind NENÍ prokázaný jako strukturní. Je převážně položkový.** Q3 +$72M [PRIM] táhly nižší náklady offshore projektů a **refundace dříve placených cel** (nekvantifikováno). FY ztráta se přitom **rozšířila** na −$400 až −500M. Q4 nese údržbu přetaženou z roku 2027 a Vineyard settlement. Do FCF 2027E proto Wind vstupuje jako bear −$400M / base −$150M / bull +$150M.
2. **FCF guidance $16–17 mld. normalizovat NELZE.** Za 9M vzrostly contract liabilities (zálohy) o **+$19,5 mld.**, víc než celé FCF $15,3 mld. [PRIM]. **FCF bez záloh za 9M je −$4,2 mld.** Zálohy tvoří ~120 % celoroční guidance [ODHAD].
3. **Normalizované FCF 2027E: bear $2,7 / base $5,5 / bull $9,0 mld.** Na akcii (266M akcií) to je $10 / $20,7 / $33,7. FCF z provozu bez záloh: $2,7 / $3,8 / $5,0 mld. [ODHAD].
4. **Férová hodnota (DCF 2027–31, WACC 9 %): bear ~$230 / base ~$515 / bull ~$720.** Váženě 25/50/25 vychází ~$495.
5. **Nové pásmo: plné $480 / hlubší $400 / krizové $250.** Bear scénář plně unese jen krizové patro, viz ARM-6.
6. **Staré pásmo $800 nikdy nebylo odvozeno z FCF.** Baseline ho vede jako „vstupní cenu (DCA)" bez výpočtu. Proti fundamentu je nadsazené o ~65 %.
7. **Cena ~$797 [LIVE]** odpovídá ~38,5× base normalizovaného FCF 2027E a ~56× FCF z provozu. Zhruba to je náš **bull** scénář při WACC 8,5 % ($804). Trh tedy oceňuje bull scénář.
8. Power a Electrification jsou kvalitní a cenová síla je doložená (Power: přírůstková marže 54 % v Q3). Problém je v kvalitě cash flow a v tom, že **buyback $5,3 mld. za 9M financují zálohy, ne provoz**.

---

## 2. OSY 1–7

### OSA 1: Wind. Práh prošel, ale je obrat strukturní?

**Fakta [PRIM]:**
- Q3 2026 segment EBITDA **+$72M (2,6 %)** vs. −$61M (−2,3 %) v Q3 2025. Organicky +$97M (3,6 %). Revenue $2 741M (+4 %, org. +3 %).
- 9M 2026 EBITDA **−$585M** (−9,4 %) vs. −$373M. Kvartální řada: Q1 −382, Q2 −275, Q3 +72.
- Q2 guidance pro Q3 zněla „approximately break-even" [PRIM, slidy Q2 / SEK call Q2]. Skutečnost práh překonala o ~$72M.
- **Čím byl zisk dosažen** (10-Q MD&A s. 30): *„primarily at Offshore Wind due to lower project costs, and at Onshore Wind due to the impact of tariff recoveries and Onshore Wind services due to higher transactional volume, partially offset by Onshore Wind equipment due to lower volume in North America."* Release: *„lower project costs at Offshore Wind as well as the impact of tariff recoveries and higher services at Onshore Wind"*.
  - **Tariff recoveries** jsou zpětné úhrady dříve zaplacených cel, tedy z definice jednorázová položka. **Částka není zveřejněna** [PRIM: NOT FOUND].
  - **Nižší offshore náklady** odrážejí kvartál bez nových cost updates („higher deliveries and lower project updates"). Offshore revenue Q3 $273M vs. $195M. Neznamená to strukturně ziskový offshore. 10-Q výslovně: *„At Offshore Wind, we continue to experience pressure related to our project costs and execution timelines."*
  - **Onshore služby** jsou jediná strukturní složka. Call Q3 (Strazik): podobné meziroční zlepšení služeb čeká i v 2027 [SEK].
- **Proč se FY ztráta rozšířila na −$400 až −500M** (call Q3, Parks [SEK]): *„accelerate scheduled maintenance from 2027 into the fourth quarter … These incremental service costs, along with the Vineyard Wind settlement, more than offset the impact of additional onshore volume."* Strazik přitom označil dopad Vineyard settlementu za *„very modest negative P&L impact"*. **Mezi CEO a CFO je tu interní nesoulad**, protože settlement je zároveň uváděn jako důvod rozšíření ztráty.
- **Vineyard Wind:** spor uzavřen v Q3 („commercial resolution", release: „resolved all outstanding litigation") [PRIM]. Podmínky ani částka nezveřejněny. Commissioning se dokončí „early 2027". Dogger Bank 10-Q Q3 nezmiňuje. Call Q3 uvádí *„one more year to go in the offshore execution in the North Sea"* [SEK].
- **Incremental contract losses offshore 9M 2026: 10-Q Q3 je NEZVEŘEJŇUJE** [PRIM: NOT FOUND]. Srovnání s $637M za FY2025 (potvrzeno 10-K Note 2; FY2024 $1 005M, FY2023 $379M) proto nejde provést. **Je to datová mezera, ne pozitivní signál.**
- **Zbývající backlog:** Wind RPO $19 952M (−$1,7 mld. YTD) = equipment $7 584M (−14 % y/y) + services $12 368M. Pokles je „primarily due to a decrease at Offshore Wind" [PRIM]. Samostatné offshore RPO zveřejněno není.
- **Q4 implikace:** −400 až −500 − (−585) = **+$85 až +185M**. Q4 nese přetaženou údržbu 2027 a settlement, ale také sezónně nejvyšší onshore dodávky (revenue Q4 ~$2,4–2,55 mld. [ODHAD]). **Realismus: spodní polovina (+$85–120M) je dosažitelná, horní konec je nejistý** [ODHAD]. Q3 bez cel by byl odhadem blízko nuly.
- **Výhled 2027 od managementu** [SEK]: číselná guidance pro Wind neexistuje. Strazik: *„continue to evaluate how we invest in this business for value and/or … create value with this business in whatever is the smartest way possible"*. To je první náznak strategických opcí (prodej, JV). Od ledna 2027 přichází nový šéf Wind.

**Verdikt OSA 1 [ODHAD]:** Jde o **jeden ziskový kvartál tažený z velké části položkami** (cla a absence offshore cost updates). Strukturní obrat potvrdí teprve **Q4 ≥ +$85M a zároveň Q1 2027 ≥ 0** bez jednorázovek. Wind do FCF 2027E: **bear −$400M** (opakování 2026, offshore tail-risk) / **base −$150M** / **bull +$150M**. Bear je záměrně horší než pásmo −$200M až 0 ze zadání. Historie resetů (FY2025: prosinec −$400M → skutečnost −$598M; FY2026: −$400M → −$400 až −500M) konzervativnější práh neospravedlňuje.

### OSA 2: Orders a backlog momentum

**Fakta [PRIM]:**
- Orders Q3 **$29 291M** (+96 % org.). Power $21 780M (+178 %), Electrification $5 371M (+6 % GAAP / **−9 % org.**), Wind $2 140M (+17 % / +16 % org.).
- **Power $21,8 mld.:** equipment $17,97 mld. (~4×, +304 %), services $3,81 mld. (+12 %, Gas + Nuclear) [slidy]. Plynové turbíny 112 ks / **16,6 GW** v Q3 (Q3'25: 29 ks / 7,4 GW). 9M 262 ks / 36,7 GW [10-Q]. Mix: 55 heavy-duty (21 HA) + 57 aeroderivátů [release]. Nuclear a hydro orders samostatně zveřejněny nejsou.
- **Datacentra vs. utility** [SEK call]: *„approximately 100 customers in 25 different countries, of which approximately 80% are traditional customers and 20% are for data centers"*. Není jasné, zda jde o podíl zákazníků, GW nebo dolarů. Stejný poměr zazněl na Q1 i Q2 callu. **Dolarový podíl DC na Power orders zveřejněn není.**
- **Price vs. volume:** release uvádí „higher volume and price". Q3 orders byly *„north of 20 points"* nad Q4 2025 (částečně díky mixu aero a 60 Hz). FY2026 cena za kW plynových orders bude *„approximately 50% higher"* než FY2025 [SEK, Strazik]. **V Q4 čeká management nižší $/kW** (méně aero, víc 50 Hz).
- **RPO $196 721M** (+$20,4 mld. QoQ; equipment $104 054M, services $92 667M). Power $130 854M, Electrification $46 148M, Wind $19 952M [PRIM]. Timing equipment RPO: 33 % do 1 roku, 60 % do 2 let, 97 % do 5 let. **Cesta k $200+ mld. v Q4** chce +$3,3 mld. netto. Při Q4 jako „největším order kvartálu roku" (vč. Barmer HVDC ~$1,5 mld.) je to vysoce pravděpodobné [ODHAD].
- **GW (release Q3):** podepsáno 11 GW (8 GW SRA + 3 GW orders), **konvertováno 13 GW SRA → orders** (Q2: 10 GW), dodáno 5 GW. **Backlog 53 → 64 GW, SRA 63 → 58 GW**, celkem 116 → 122 GW. **Poprvé backlog GW > SRA GW.** To je kvalitativní zlom a podíl nezávazných rezervací klesl z 56 % (Q1) na 48 %.
- **Cíl ≥130 GW:** Q4 potřebuje netto +8 GW, tedy hrubé podpisy ~13 GW při ~5 GW dodávek. Strazik čeká *„probably 13+ GW in the fourth quarter"*. 2027 kvartály „more likely to feel like 3Q and 4Q" (~11–13 GW) [SEK]. Prodány už jsou sloty pro **2032**.
- **Electrification book-to-bill ~1,4 vs. 1,7 v Q2** [PRIM]. Zpomalení je reálné, organicky −9 % y/y kvůli vysoké srovnávací bázi (velké synchronní kompenzátory v Q3'25). DC orders Electrification: >$6 mld. YTD, z toho ~$1,4 mld. v Q3 (Q2 $2,7 mld.) [SEK]. **Q3 DC orders klesly QoQ zhruba o polovinu.**
- **Framework agreements:** v dokumentech Q2 ani Q3 **pro Power nezmíněny**. Poslední údaj je Q1: 0 uzavřených z 30–35 jednání [SEK, refresh]. Uzavření aspoň jednoho **nelze potvrdit**. Q3 call zmiňuje ~80 framework agreements jen u Trench.

**Verdikt OSA 2:** Momentum je silné a kvalitativně lepší (konverze SRA, backlog GW > SRA). **Varovné signály:** Electrification orders −9 % org., DC orders v Electrification QoQ ~−48 %, Power $/kW v Q4 nižší.

### OSA 3: Power a Electrification nesou valuaci

**Power [PRIM]:** revenue $6 067M (+25 %), EBITDA $1 297M, **21,4 % (+800 bps; org. 21,0 %, +830 bps)**. Důvod: *„favorable price and higher volume at Gas Power, partially offset by the impact of inflation"*. 9M marže 19,0 %. FY guidance 19–21 % implikuje Q4 ~19–25 % [ODHAD z callu].

- **ARM-1, přírůstková marže Power:** Q3 ΔEBITDA $646M / ΔRevenue $1 204M = **54 %** (9M: 49 %; FY2025 vs. FY2024: 39 %). Přírůstková marže 54 % při 21% průměru znamená, že **velká část nárůstu revenue je čistá cena**. Cenové zvýšení propadá do EBITDA téměř celé, volume samo by přineslo jen ~25–35 % [ODHAD].
- **Udržitelnost:** cena je zabudovaná v backlogu (orders H1'26 >20 % nad Q4'25, FY26 ~+50 % y/y). Dodávky z těchto orders proběhnou 2027–2029, takže marže má ze samotného backlogu tailwind [ODHAD]. Jednorázové efekty v Power 10-Q ani release neuvádí. Rizika: mix (aero s vyšším $/kW se v Q4 snižuje), inflace a náklady rampy (pracovníci „in training mode", call Q2). Strazik: *„no reason to think that the second half of this year isn't the right way to start to think about our projection into 2027"* [SEK]. Číselný cíl 2027/2028 není. 2030 guidance padne na Capital Markets Day (datum oznámí v lednu).
- **„SRA +10–20 bodů nad backlogem" — OPRAVA:** benchmarkem jsou **Q4 2025 orders**, ne backlog (call Q2: *„dollar per kW … higher end of the range of 10 to 20 points versus Q4 2025 orders"*). Platí to a v Q3 to bylo překonáno (>20 bodů). Přímé srovnání ceny SRA s cenou backlogu zveřejněno není.

**Electrification [PRIM]:** revenue $3 862M (+51 %, org. +16 %), EBITDA $739M, **19,1 % (+400 bps)**. Organicky 17,9 % (+470 bps). FY guidance revenue $14,5–15,0 mld. (Prolec ~$3,1 mld.), marže 18–20 % „trending toward the higher end".
- **ARM-1:** Q3 přírůstková marže GAAP 27 % (zředěno akvizicí), **organicky 48 %** (9M org. 42 %). Prolec v Q3 vydělal EBITDA $212M na revenue $945M (22,4 %) [10-Q]. Na slidech je $216M.
- Cenová síla je nižší než v Power (Parks: *„positive pricing … slightly less growth rate than Power"*, HVDC „stabilized") [SEK]. Strazik: jump-off H2 2026 ~20 %, k marži >30 % do 2030 „directionally in the neighborhood" [SEK]. Ber to jako aspiraci, ne guidance.
- **Prolec [PRIM]:** PPA (purchase price allocation) je stále **preliminary**, finalizace nejpozději v Q1 2027. Celková consideration $9 614M (cash $5 212M po refundaci $42M + přecenění 50% podílu $4 402M). **Goodwill $5 222M**, tj. postupně snížen measurement-period úpravami (Q1 $5 473M → Q2 $5 313M → Q3 $5 222M). Intangibles $4 172M. **Impairment žádný.** GAAP pre-tax Q3 −$5M, YTD −$171M (amortizace step-upu). Integrace podle CEO „outperforming", orders $900M za transformátory v USA [SEK]. **Impairment signál: žádný.** Snižování goodwillu jde opačným směrem (méně goodwillu = méně rizika impairmentu).

### OSA 4: Kvalita FCF a FCF 2027E (jádro re-derivace)

**Dekompozice CFO 9M 2026 [PRIM, 10-Q cash flow statement s. 7]:**

| Položka ($M) | 9M 2026 | 9M 2025 |
|---|---|---|
| **CFO** | **16 737** | 2 508 |
| z toho Δ contract liabilities (zálohy) | **+19 511** | +2 419 |
| Δ receivables | −1 667 | +563 |
| Δ inventories | −2 052 | −1 047 |
| Δ contract assets | −345 | −656 |
| Δ accounts payable | +1 522 | +566 |
| Ostatní provozní | −675 | −693 |
| **Výdělková část CFO** (CFO − všechny WC řádky) | **~443** | — |
| Capex (PP&E + software) | −1 430 | −606 |
| **FCF (non-GAAP)** | **15 307** | 1 902 |
| **FCF bez Δ záloh** | **−4 204** | −517 |

- Výdělkovou část CFO zatížily **cash taxes $2 681M** (vs. daňový náklad $1 123M; Q3 samo $1 423M) a **mimořádné penzijní výdaje ~$0,87 mld.** (dobrovolný příspěvek $516M + transfer retiree závazků $353M) [PRIM].
- **[ODHAD]:** Vysoké cash taxes velmi pravděpodobně souvisejí se zálohami (US daňové právo zdaňuje advance payments nejpozději v následujícím roce). Pokud se zálohy začnou rozpouštět, část daní se vrátí v nižších cash taxes. Firma to nekvantifikuje.
- **SRA zálohy jsou součástí contract liabilities** (10-Q MD&A: *„driven by down payments on orders and slot reservation agreements at Power"*). Samostatná částka SRA záloh zveřejněna **není**.
- Contract liabilities podle segmentu k 30. 9. 2026: Power $33 163M (z $16 527M), Electrification $9 976M, Wind $2 529M. Celkem current **$45 669M** (12/2025 $25 774M, 12/2024 $17 587M) [PRIM].
- **CL / LTM revenue: 50 % (12/2024) → 68 % (12/2025) → 104 % (9/2026)** [ODHAD]. Návrat na úroveň 12/2025 (68 %) by znamenal **odliv ~$15,7 mld.**, víc než celá čistá hotovost ($16,8 mld. cash − $2,8 mld. dluh = $13,9 mld.).
- **Řada FCF bez záloh** [ODHAD z PRIM]: FY2024 −$1,1 mld., FY2025 −$4,3 mld., H1'26 −$3,8 mld., 9M'26 −$4,2 mld.

**FY guidance $16–17 mld.: kolik ze záloh?** Q4 implikuje FCF jen **$0,7–1,7 mld.** (vs. $5,4 mld. v Q3). Management už v Q2 avizoval nižší H2, protože SRA konvertují. Při Q4 Δ záloh ~0 až +$1 mld. vychází FY Δ záloh **~$19,5–20,5 mld., tj. ~120 % guidance**. **FCF z provozu za FY2026 ≈ −$3 až −4 mld. striktně, po očištění o mimořádné daně, penze a náběh WC zhruba +$1 mld.** [ODHAD].

**Normalizované FCF 2027E [ODHAD]** (skript `model/dcf2.py` ve scratchpadu; 2026E revenue ~$47 mld.):

| ($ mld.) | Bear | Base | Bull | Zdůvodnění |
|---|---|---|---|---|
| Power revenue / marže | 26,2 / 19 % | 27,4 / 21 % | 28,2 / 23,5 % | 2026E ~$23,8 mld.; kapacita 5 GW/Q = 20 GW/rok; marže = H2'26 jump-off |
| Electrification revenue / marže | 15,9 / 18,5 % | 17,0 / 19,5 % | 17,7 / 21 % | 2026E $14,75 mld.; Prolec 12 měsíců |
| Wind EBITDA | −0,40 | −0,15 | +0,15 | OSA 1 |
| Corporate | −0,65 | −0,60 | −0,55 | FY26 guidance −0,45 až −0,50 + rezerva |
| **Adj. EBITDA 2027E** | **6,9** | **8,3** | **9,9** | marže 13,7 / 15,9 / 18,4 % |
| Cash daně (23 % × (EBITDA − D&A 1,75)) | −1,2 | −1,5 | −1,9 | normalizovaná ETR, bez daní ze záloh |
| Capex | −2,3 | −2,0 | −1,8 | program $6 mld. 2025–28 **vč.** $1 mld. Prolec; 2026 ~$2 mld. |
| WC mimo zálohy (−15 % Δrevenue) | −0,5 | −0,8 | −1,0 | zásoby +25 % YTD |
| Penze, úroky, ostatní | −0,25 | −0,25 | −0,25 | |
| **FCF z provozu (bez záloh)** | **2,7** | **3,8** | **5,0** | |
| Δ zálohy (FCF ze záloh) | −3,0 až 0 | +3,5 | +8,0 | |
| Započteno do normalizovaného FCF | 0 % | 50 % | 50 % | zálohy ≠ vlastní hotovost (ARM-5) |
| **Normalizované FCF 2027E** | **2,7** | **5,5** | **9,0** | |
| na akcii (266M) | **$10,0** | **$20,7** | **$33,7** | |
| Reportované FCF 2027E (op + celé Δ záloh) | −0,3 až 2,7 | 7,3 | 13,0 | pro srovnání s budoucí guidance |
| **Cash odliv Trench (closing konec 2027)** | ~$4,5 mld. cash + $4,5 mld. dluh | | | mimo FCF 2027E; ve valuaci jako úprava −$3,0 / −$0,5 / 0 mld. |

**Explicitní oddělení:** **FCF z provozu 2027E base $3,8 mld.** je to, co firma vydělá. **FCF ze záloh base +$3,5 mld.** je float, který je třeba odpracovat dodávkami. Při zpomalení objednávek se otočí do záporu.

### OSA 5: Rozvaha, kapitálová alokace a Trench

- **Dluh:** $2 826M (senior notes $2,6 mld.: 2031 4,25 %, 2036 4,875 %, 2056 5,5 %) [PRIM]. Revolver $3 mld. + trade finance $3 mld. jsou nečerpané. Fitch upgrade na **A-** (12. 8. 2026). Po Trench +~$4,5 mld. vychází hrubý dluh ~$7,3 mld. **Dluh / EBITDA 2027E (vč. Trench ~$0,6 mld.): base 0,8×, bear ~1,0×** [ODHAD]. **Cíl <1× drží v base, v bearu je na hraně.** Tvrzení managementu, že „zůstane net cash", platí jen díky hotovosti ze záloh.
- **Trench [PRIM 10-Q Item 5/8-K + slidy]:** smlouva z 25. 10. 2026 s **Triton Partners** (ne se Siemensem, viz tabulka oprav), **~€8,0 mld. fixní cena** (= $9,0 mld. při 1,12, tedy **EUR/USD expozice**). Financování „equally between cash and debt", closing koncem 2027, regulace + konzultace se zaměstnanci. Customary termination fee, částka nezveřejněna, splatná nejdřív v H2 2027. Trench podle slidů: revenue $1,4 / 1,6 / 1,9 mld., EBITDA $0,5 / 0,6 / 0,7 mld. (~33 / 35 / 36 %), FCF $0,2 / 0,3 / 0,4 mld. (2026E / 2027E / 2028E). Firm RPO $2,6 mld. z „~$5 mld." (zbytek tvoří framework agreements). Cost synergie $50–100M do 2030, revenue synergie nekvantifikovány. Čísla Trench sestavila GEV z dat Trench a s GAAP nejsou rekonciliovatelná.
- **Férová, nebo prémiová cena? [ODHAD]:** 13× EBITDA 2028E, **18× EBITDA 2026E, 6,4× EV/revenue 2026E, 22,5× FCF 2028E (yield 4,4 %)**. Prolec stál $9,6 mld. při revenue ~$3,1 mld. 2026 (**~3,1× EV/revenue**, ne 3,3–4,8×) a ~13–14× EBITDA. Na revenue je Trench zhruba dvojnásobně dražší, na EBITDA srovnatelný díky marži 35 % vs. ~22 %. **Cena je plná, ne výhodná.** Hodnotu přidá jen tehdy, pokud se marže 36 % a růst mid-teens udrží. V base ji modeluji jako mírně hodnotu ničící (−$0,5 mld.), v bearu −$3 mld. (EUR/USD, integrace, cyklus).
- **Buyback $20 mld. vs. kvalita FCF:** 9M buyback $5 274M + dividendy $406M = **$5,68 mld.** při **FCF bez záloh −$4,2 mld.** [PRIM]. **Návrat kapitálu je ze 100 % financován zálohami zákazníků.** Odkupy proběhly za průměrně $949 (Q3), $952 (Q2) a $924 (říjen) [SEK/PRIM]. To je ~80–85 % nad base férovou hodnotou ~$515 [ODHAD]. Life-of-program $9,9 mld. při průměru ~$635. Zbývá $10,1 mld. autorizace.
- **Zásoby:** $10 429M → $12 692M (Q2) → **$13 045M** (+25 % YTD, rychleji než revenue 9M +22 %) [PRIM]. **Warranty:** $1 573M → $1 595M → **$1 665M** (+5,8 % YTD) [PRIM], mírně rostoucí, bez alarmu. Rollforward (provize, čerpání) zveřejněn není. Supply-chain finance payables $1 542M → $2 111M (+37 %) [PRIM] je drobný signál natahování závazků.
- **Další [PRIM]:** service agreements *„net unfavorable changes in estimated profitability of $293 million"* (9M). IRS audit 2016–2020 může vyvolat závazky vůči GE (neúčtováno).

### OSA 6: AI capex kontext [SEK]/[ODHAD]

- **Výplach 22. 10.:** hlavička přepisu Q2 uvádí close $827,42 (−10,64 %) k 22. 10. 2026 [SEK, metadata]. Vertiv −7 % a Eaton −6 % v knihovně ověřit nelze [LIVE].
- **Q3 realita:** rekordní orders $29,3 mld. K otázce na finanční stres zákazníků a exity ze SRA (Arcaro) Strazik odpověděl: *„No, David, we are not … no change in our cash terms … very strong balance sheets"* [SEK].
- **Expozice:** ~20 % plynových GW (nebo zákazníků) tvoří datacentra a DC orders Electrification >$6 mld. z $18,8 mld. YTD (~32 %). **Hrubý odhad: DC ≈ 20–25 % celkových orders (~$20–25 mld./rok)** [ODHAD].
- **Stres 20–30% zpomalení DC orders [ODHAD]:**
  - **Orders:** −$4–7,5 mld./rok.
  - **Revenue a EBITDA 2027:** revenue téměř beze změny (backlog: 60 % equipment RPO do 2 let), EBITDA −$0,1–0,2 mld.
  - **Zálohy:** při ~27 % záloh na orders (9M: Δ záloh $19,5 mld. / orders $71,9 mld.) **−$1,1 až −2 mld.** Reportované FCF 2027E base tak klesne z $7,3 na ~$5,3–6,2 mld.
  - **2028–29:** revenue −$3–5 mld., EBITDA −$0,6–1,0 mld.
  - **Cíl 130 GW:** DC tvoří ~20 % podpisů, takže Q4 podpisy by klesly o ~0,5–0,8 GW, na **~129–130 GW. Na hraně, ne kolaps.**
  - **Hodnota:** −$40 až −60 na akcii vůči base [ODHAD].
  - **Zásadní riziko je až druhé kolo:** utility zpomalí, protože DC poptávka tvoří část jejich plánů. To pokrývá bear.

### OSA 7: Governance

**Form 4 ani čitelná proxy v knihovně nejsou, takže insider prodeje kolem Q2/Q3 a u ATH ~$1 175 nelze ověřit.** Z [PRIM] je k dispozici jen toto:
- 10-Q Q3 Item 5: v Q3 žádný director ani officer nezaložil ani neukončil 10b5-1 plán.
- Exhibity 10.1 *Resignation Agreement with Kenneth Parks* (CFO) a 10.2 *Offer Letter with Claire McDonough*.

Call Q3 potvrzuje, že CFO i šéf Wind se mění v lednu 2027 [SEK]. **Výměna CFO v okamžiku vrcholu záloh a první guidance 2027 je bod ke sledování, ne obvinění.**

---

## ARM pravidla

**ARM-1 (přírůstková marže, ΔEBITDA / Δrevenue y/y) [ODHAD z PRIM]:**

| Segment | Q3 2026 | 9M 2026 | FY25 vs. FY24 |
|---|---|---|---|
| Power | **54 %** | 49 % | 39 % |
| Electrification GAAP / organicky | 27 % / **48 %** | 27 % / 42 % | 36 % |
| Wind | 141 % (zisk rostl rychleji než revenue, tedy náklady a položky, ne volume) | n/m | n/m |
| Celkem adj. EBITDA | 42 % | 34 % | — |

Růst reálně teče do **Power (cena)** a do **organické Electrification**. Prolec ředí (22 % marže). Wind „zisk" nevzniká z růstu revenue.

**ARM-2 (cenová síla):**
- Power orders Q3 > +20 bodů nad Q4'25, FY26 $/kW ~+50 % y/y [SEK]. Release a 10-Q: „favorable price … partially offset by inflation" [PRIM]. Price/cost spread je jasně kladný (přírůstková marže 54 %).
- Prodávají se sloty 2032 a management nemění platební podmínky (zálohy). To je silný důkaz vyjednávací pozice.
- Konkurence: Q3 dokumenty Siemens Energy nezmiňují. Omezení orders konkurentem za 2030 zaznělo v otázce na Q1 callu, bez jména [SEK, refresh].
- **Trench neprodává Siemens, ale Triton** [PRIM]. Úvaha „co prodej Siemensem říká o ceně" nemá oporu v dokumentech. Z dokumentů plyne jen to, že private-equity prodávající realizoval exit za 18× EBITDA 2026E, tedy prodej na vrcholu cyklu [ODHAD].

**ARM-3 (realismus guidance) [ODHAD]:**

| Guidance | Skóre | Zdůvodnění |
|---|---|---|
| FY2026 celkově | **7/10** | +2: 9M dodáno a Q4 revenue $13,4–14,4 mld. je v souladu se sezónností. +2: čtyři zvýšení guidance v řadě (leden, duben, červenec, říjen). +1: FCF guidance je konzervativní (Q4 jen $0,7–1,7 mld.). +2: backlog $197 mld. pokrývá Q4. −1: horní konec marže vyžaduje Q4 adj. EBITDA ~19 %. −1: Wind historie resetů. −1: Q4 Power marže v rozpětí 19–25 % je široké pásmo. |
| FY2026 Wind (−$400 až −500M) | **4/10** | Q4 musí dodat +$85–185M při nákladech přetažené údržby. Q3 stál na nekvantifikovaných clech. Dvě historické revize k horšímu. |
| FY2027 (implikovaný rámec: H2'26 jump-off, backlog >$200 mld., GW rostou) | **6/10** | Backlog dává viditelnost revenue (+), číselná guidance není (−), mění se CFO (−), maržový tailwind z cen je zabudovaný (+). |
| Nominální FCF 2027 ve výši 2026 (~$16 mld.) | **2/10** | Vyžadovalo by další Δ záloh ~$12–13 mld. Management sám avizoval, že SRA konverze snižují H2 FCF. |

**ARM-4 (valuace bez EBITDA):**
- Čistý zisk 9M 2026 GAAP $6 687M (EPS $24,81). Jednorázové položky pre-tax: Prolec remeasurement **$3 992M**, Proficy **$366M** (ne $330M), Financial Services $86M, China XD **$264M zisk** (proceeds ~$0,7 mld.), settlement gain penzí $84M. Proti nim stojí inventory step-up −$106M, separace −$92M a restrukturalizace −$109M [PRIM].
- **Očištěný čistý zisk 9M ≈ $2,2 mld. ($8,2/akcii), GAAP EPS tedy tvoří z ~67 % jednorázovky** [ODHAD: (adj. EBITDA − D&A) × 0,77, bez úrokového výnosu z hotovosti ze záloh].
- Očištěný EPS 2027E: bear $14,8 / base $19,0 / bull $23,7 [ODHAD]. Valuace v sekci 3 stojí na FCF, ne na EBITDA.

**ARM-5 (kvalita rozvahy):** zálohy ≠ vlastní hotovost. Přebytek záloh nad normou 12/2025 (~$15,7 mld.) převyšuje čistou hotovost ($13,9 mld.). **Ve valuaci proto čistou hotovost počítám jako 0.** Citlivost na zpomalení objednávek viz OSA 6. Trench se financuje 50 % hotovostí, která sama pochází ze záloh.

**ARM-6 (prostor pro chybu):** Bear férová hodnota je $230 (rozpětí $196–255 dle WACC 8,5–10 %). **Bear plně unese jen krizové patro.** Plné patro omezuje ztrátu v bearu na ~52 % a stojí na vážené hodnotě. Proto doporučuji **plné patro jen jako první tranši**, viz sekce 3.

---

## 3. NOVÉ VSTUPNÍ PÁSMO

### Odvození férové hodnoty [ODHAD]
DCF 2027–2031 (roční FCF dle scénáře, revenue 2031 bear $58 / base $71 / bull $79 mld., marže EBITDA 15 / 20 / 21,5 %, capex $2,1–2,2 mld., float započten 0 / 50 / 50 %). Terminální růst 3 / 3,5 / 4 %, WACC 9 %. Čistá hotovost = 0 (ARM-5). Úprava Trench −$3,0 / −$0,5 / 0 mld. 266M akcií (bez započtení budoucích buybacků).

| Scénář | Norm. FCF 2027E / akcii | FV @ WACC 8,5 % | **FV @ 9 %** | FV @ 10 % | Implikovaný P/FCF 2027E |
|---|---|---|---|---|---|
| Bear | $10,0 | $255 | **$232** | $196 | 23× |
| Base | $20,7 | $568 | **$515** | $433 | 25× |
| Bull | $33,7 | $804 | **$723** | $601 | 21× |
| Vážená 25/50/25 | — | — | **~$496** | — | — |

Citlivost base na započtený podíl záloh: 0 % → $475, 50 % → $515, 100 % → $555. Terminální hodnota tvoří ~80 % EV, takže **závěr je citlivý na WACC víc než na rok 2027.**

### Tři patra

| Patro | Cena | Odvození | P/FCF (base norm.) / FCF yield | P/FCF z provozu (base) | Bear: FCF yield / pokles k bear FV |
|---|---|---|---|---|---|
| **Plné pásmo** | **$480** (rozpětí 460–500) | Vážená férová hodnota $496, zaokrouhleno dolů. Base FV −7 %. | 23× / **4,3 %** | 34× / 2,9 % | 2,1 % / −52 % |
| **Hlubší pásmo** | **$400** | Base FV $515 s 22% bezpečnostní marží (≈ base FV při WACC 10 %) | 19× / **5,2 %** | 28× / 3,5 % | 2,5 % / −42 % |
| **Krizové pásmo** | **$250** | ≈ bear FV ($232–255): cena, při které i bear vydělá náklady kapitálu | 12× / **8,3 %** | 18× / 5,6 % | **4,0 %** / ~0 % |

**Doporučené použití [ODHAD, ne poradenství]:**
- **Plné patro:** jen první tranše (≤ 1/3 cílové velikosti), protože bear neunese.
- **Hlubší patro:** jádro pozice.
- **Krizové patro:** dokupování bez omezení.

### Srovnání se starým pásmem $800 a vysvětlení rozdílu
- Baseline z 19. 6. **$800 neodvozovala**. Uvádí ho jako „Vstupní cena (DCA) $800" vedle pesimistického scénáře $600–700 a bullish $1 200–1 400. **Žádný výpočet z FCF v baseline není.**
- Nové plné patro **$480 je o 40 % níž**. Rozdíl vysvětlují tři věci:
  1. **Normalizace FCF:** nominální guidance $16–17 mld. (~$60/akcii) nahrazuje normalizované FCF 2027E $20,7/akcii. Přes 100 % nominálního FCF jsou zálohy.
  2. **Čistá hotovost $13,9 mld. (~$52/akcii) se nezapočítává**, protože jde o hotovost ze záloh.
  3. **Trench je oceněn jako plná, ne výhodná transakce.**
- Proti tomu fundament od června výrazně zesílil: Power marže 16 → 21 %, backlog $163 → $197 mld., backlog GW > SRA. **Bez těchto zlepšení by base FV vyšla pod $400.**
- **Cena ~$797 [LIVE]** ≈ bull FV při WACC 8,5 %. Odpovídá 38,5× base normalizovaného FCF 2027E (yield 2,6 %) a 42× očištěného EPS 2027E base. Trh tedy oceňuje bull scénář včetně trvalého floatu.

---

## 4. FALZIFIKOVATELNÉ PRAHY PRO Q4 2026 PRINT (leden 2027)

**Pásmo se znovu SUSPENDUJE (nutná re-derivace), pokud nastane cokoli z tohoto:**

| # | Test | Práh suspendace | Směr |
|---|---|---|---|
| 1 | **Wind Q4 EBITDA** | < +$85M (FY ztráta > $500M), nebo další rozšíření ztrátové guidance pro 2027 | Bear Wind −$400M se stává base, bear −$600M, pásmo −$20–30 |
| 1b | Wind Q4 ≥ +$85M **a** Q1 2027 ≥ 0 bez cel a settlementů | Dva ziskové kvartály = kandidát na strukturní obrat | Base Wind 0, bull +$300M, pásmo +$10–15 |
| 2 | **Δ contract liabilities v Q4** | Záporná o více než −$2 mld., nebo FY FCF < $16 mld. | Začíná se rozpouštět float, bear se stává base |
| 3 | **Gas GW pod kontraktem** | < 128 GW (minutí cíle ≥130), nebo pokles backlog GW | Konverze SRA slábne |
| 4 | **RPO** | < $200 mld. (minutí vlastního výroku) | Momentum |
| 5 | **Power Q4 marže** | < 19 % (spodní konec implikovaného pásma) | Base marže 21 % pro 2027 neplatí |
| 6 | **Guidance 2027 (leden)** | Power marže < 20 %, nebo FCF 2027 guidance < $6 mld. bez vysvětlení floatu. Opačně FCF 2027 guidance ≥ $12 mld. **bez** rozpadu na zálohy a provoz = varovný signál pro kvalitu výkaznictví | Re-derivace |
| 7 | **Electrification orders** | Organicky záporné druhý kvartál v řadě, nebo book-to-bill < 1,2 | DC zpomalení se potvrzuje |
| 8 | **Trench milníky** | Změna ceny nebo struktury, regulační podmínky (remedies), oznámení financování ≠ ~50/50, EUR/USD > 1,25 (cena > $10 mld.), výsledky Trench 2026 < $1,4 mld. revenue / $0,5 mld. EBITDA | Úprava Trench ve valuaci |
| 9 | **Prolec PPA (finalizace Q1 2027)** | Goodwill impairment, nebo úprava > $500M | Kvalita M&A |
| 10 | **Kapitálová alokace** | Buyback > $2 mld./kvartál při záporném FCF bez záloh, nebo buyback financovaný dluhem | Ničení hodnoty při ceně nad FV |
| 11 | **Cash taxes** | Pokud Q4 rozpouští zálohy a cash taxes neklesají, hypotéza „daně ze záloh" padá | Kvalita výdělkového CFO |

---

## 5. TABULKA OPRAV (zadání vs. [PRIM])

| # | Zadání / balíček | Hodnota v zadání | Skutečnost [PRIM] | Zdroj | Stav |
|---|---|---|---|---|---|
| 1 | CFO 9M 2026 (OSA 4) | ~$16,8 mld. | **$16 737M (~$16,7 mld.)**. $16,8 mld. je hotovost k 30. 9. ($16 764M). | 10-Q s. 7, release | **OPRAVA** |
| 2 | Capex (OSA 4) | ~$6 mld. 2025–28 **+** $1 mld. Prolec | $6 mld. 2025–28 **včetně** $1 mld. Prolec 2026–28 | release Q3 | **OPRAVA** (dvojí započtení) |
| 3 | Trench prodávající (ARM-2) | „prodej Trench Siemensem" | Prodávající je **Triton Partners**, ~€8,0 mld. fixní cena | 10-Q Q3 Item 5 | **OPRAVA** |
| 4 | Proficy (ARM-4) | $330M | **$366M** pre-tax (9M; Q1 uváděl $330M) | release s. 8, 10-Q CF | **OPRAVA** |
| 5 | China XD (ARM-4) | +$0,6 mld. | Proceeds ~$0,7 mld. (investing), **zisk 9M $264M** (interest & investment income) | 10-Q | **ZPŘESNĚNÍ** |
| 6 | SRA cena (OSA 3) | +10–20 bodů **nad backlogem** | +10–20 bodů **vs. Q4 2025 orders**; Q3 >20 bodů | call Q2, Q3 [SEK] | **OPRAVA benchmarku** |
| 7 | Prolec EV/revenue (OSA 5) | ~3,3–4,8× | **~3,1×** ($9 614M / revenue 2026 ~$3,1 mld.); ~2,8× na annualizovaném základě | 10-Q Note 8, guidance | **OPRAVA** |
| 8 | Prolec PPA (OSA 3) | „PPA finalizace" | Purchase price allocation (ne power purchase agreement), preliminary, do Q1 2027. Goodwill $5 222M (snížen z $5 473M) | 10-Q Q3 Note 8 | **ZPŘESNĚNÍ** |
| 9 | Adj. EBITDA | „15,4 %, +690 bps org." | 15,4 % je reportovaná marže (+730 bps). **+690 bps platí pro adj. organickou marži** (7,8 → 14,7 %) | release s. 2 | **ZPŘESNĚNÍ** |
| 10 | Electrification orders | $5,4 mld., book-to-bill ~1,4 | Sedí, ale **−9 % org.** (+6 % GAAP) y/y | release | **DOPLNĚNÍ** (zadání pokles neuvádí) |
| 11 | Wind orders | +16 % | +16 % org., +17 % GAAP | release | OK |
| 12 | Počet zvýšení guidance | „potřetí letos" (signály) vs. „čtvery v řadě" (ARM-3) | Q3 dokumenty počet neuvádějí. Doložitelná zvýšení v 2026: duben, červenec, říjen (+ leden vůči prosinci 2025 dle refreshe [SEK]) = 3, resp. 4 | — | **INTERNÍ NESOULAD ZADÁNÍ** |
| 13 | Wind incremental contract losses 9M 2026 (OSA 1) | předpoklad, že Note je uvádí | **10-Q Q3 je nezveřejňuje** | 10-Q Q3 | **MEZERA** |
| 14 | Framework agreements (OSA 2) | stav k Q3 | V Q2 ani Q3 dokumentech pro Power **nezmíněny** | — | **MEZERA** |
| 15 | Kapacitní cesta 20 → 30 GW (balíček) | 20 → 30 GW | Q2 call: 20 GW (5 GW/Q od Q3'26) → 24 GW 2028 → 30 GW 2030. Q3 dokumenty jen „5 GW quarterly run rate" | call Q2 [SEK] | OK (SEK) |
| 16 | Reakce akcie +3 % po výsledcích | +3 % | V knihovně neověřitelné | — | **[LIVE]** |
| 17 | ATH ~$1 175 (červenec) | $1 175 | Jen [SEK] balíček z 17. 7. | — | **[LIVE]** |
| 18 | Výplach 22. 10. GEV −10,6 % | −10,6 % | $827,42, −10,64 % (metadata přepisu Q2) | [SEK] | OK. Vertiv a Eaton **[LIVE]** |
| 19 | Buyback autorizace | $10 → $20 mld. (říjen) | Sedí (28. 10. 2026). Zbývá $10,1 mld. | release, 10-Q | OK |
| 20 | 9M návrat kapitálu | $5,7 mld. | Sedí: $5 274M buyback + $406M dividendy | 10-Q | OK |
| 21 | Stav pozice | „GEV NENÍ držena" | Baseline a refresh: „vstup $800" | [SEK] | **INTERNÍ NESOULAD**, ověř |
| 22 | Ostatní čísla ze sekce „PRVNÍ SIGNÁLY" | Orders $29 mld. (+96 %), Power $21,8 mld. (+178 %), revenue $12,6 mld. (+27 %/+18 %), EPS $4,81, NI $1,3 mld. (10,2 %), backlog $197 mld. (+$20 mld.), Power 21,4 % (+800), Electrification 19,1 % (+400), Wind +$72M (2,6 %) vs. −$61M, 116 → 122 GW, ≥130 GW, FCF Q3 $5,4 mld., CFO Q3 $6,1 mld., cash $16,8 mld., FY guidance (revenue $46,5–47,5 mld., marže 13,5–14,5 %, FCF $16–17 mld. z $11,5–12,5, Power 19–21 %/19–21 %, Electrification horní konec 18–20 %), Wind FY −$400 až −500M (dříve ~−$400M), 9M −$585M, Trench $9,0 mld. / 13× / 50:50 / konec 2027 / $1,4 → 1,9 mld. / 33 → 36 % / synergie $50–100M / <1× | **Vše potvrzeno** | release, slidy, 10-Q | OK |

---

*GEV re-derivace pásma, 11. 11. 2026. Forenzní běh v6. Model: `model/dcf2.py` (scratchpad sezení). Všechny [ODHAD] položky jsou úsudek analytika z uvedených [PRIM] dat. Není investiční poradenství.*
