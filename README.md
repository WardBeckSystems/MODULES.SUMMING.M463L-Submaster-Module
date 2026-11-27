# M463L Submaster Module · Summing

Ward-Beck Systems M463L, 1974|7. Wiki page: [M463L on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/PAGES/M463L.html)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 96 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 10 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 16 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 448 |
| [PHOTOS/](PHOTOS/) | photographs of the module | 6 |
| [SOFTWARE/](SOFTWARE/) | program listings, firmware, the plugin | 1 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 25 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 76 |

<!-- module data: tools/module_specs.py, tools/forum_quotes.py -->

**On the WBSps forum (2006|39 - 2014|47):** [1 topic](FORUM.md): what owners and technicians said about it.

## Specifications

From the technical data sheet: [1974 - M463L - P003 - 1-1.jpg](MANUALS/1974%20-%20M463L%20-%20P003%20-%201-1.jpg) page 1 (read by OCR; check against the page). As data: [`Specifications.json`](Specifications.json).

| | |
|---|---|
| **Gain** | +18 dB +/ -0.5 dB. (bridging gain) (With fader dB &quot;in-hand&quot; position. |
| **Frequency response** | 0.25 dB from 20 Hz to 20 kHz. (Equalizer bypass position. |
| **Noise** | dB below dBm nominal output level 20Hz to 20 kHz) |
| **Harmonic distortion** | Less than 25% from Hz 20 kHz +28 dBm less Typically less than 0.05% across mos&quot; bandwidth) |
| **Source impedances** | Summing 30,000 ohms balanced Direct: 600 ohms less balanced |
| **Input impedances** |  |
| &nbsp;&nbsp;Summing | Less than Direct: 30,000 ohms ohms |
| **Output impedance** | Less than 100 ohms (at outputs 8-109A amplifiers only) 8-109F |
| **Load impedance** | 600 ohms balanced (at insertion point and DIRECT output) |
| **Output level** | dBm nominal insertion +8 dBm nominal DIRECT output +30 dBm maximum (at outputs 8-109F 8-109A amplifiers only |
| **Phasing** | Input and outpu terminals designated by numbers are in phase. |
| **Power requirements** | volts dc, 100 MA nominal 300 MA maximum |
| **Ambient temperature** | degrees Celsius. |
| **Dimensions** | wide 14.5&quot; high 6.5&quot; deep (41 mm 360 Mm 165 Mm) |
| **Weight** | (1150 gms) |

## Circuit description

From [1974 - M463L - Submaster Module (2).pdf](MANUALS/1974%20-%20M463L%20-%20Submaster%20Module%20(2).pdf) pages 4-9 (read by OCR; check against the pages). As data: [`CircuitDescription.json`](CircuitDescription.json).

<details><summary>Read it</summary>

M46 3 L SlIB MASTER MODULE

The M463L is a comb in.'l lion SUBMASTE R/ EOUAL1ZER module, deli g ned to accept combined or mixed leeds from previous ly assigned mi &quot; ing

1c han n e l inputs. As maybe required. the un;1 processes the mi &quot; ed signal, eQualize&quot; i t and routes i l to thea p prop r i ate points within the con sole system.

The signal ori gna lin g from Ih e external mixing net worl&lt; i s applied to the edge connector P l. pins 1 and A and &quot; u bseque n t ly coo nec t&quot;, tot hes u mm ing cur ren l nodes oft h e 4 _141 summing ampl ll i er. to fa c il it ll t e -oeevre teSt; n g. a direc l Input Is prolli ded on P l. pins 17 and U.

EOUAL IZE R Se clio n

The output o f the 4 _141 &quot; u mm ing amplifier; 5 roul e d to one oft hen or mall y closed cont a cl, o f the EOUAL I ZER INSERT 5 wl lCh SW13 10 allow bypass ing of the equalizer. Addll ion ally, the 4 _141 output i s fed 10 2 1, Ihe first o f four cascaded summing amplifier, 21 Ih rough

Z I through Z4 &quot; er lle II' mixing and isolation amplifiers. They are used tom i x the primary in P UI signal with a c o r.-ectlon signal d erlv.. d from the outputS oft h.. 4 _ 126 filter n &quot;t wor l&lt;s. re 'u lt lng in raising 0.lo we ring l he level 0 1 s e tee i e e portions oft he audio spectrum. Additionally, they i,o la lethe filter network ' from each other lind preVen lin tera c tion between them, re,ull ing in e eeu e ere and repeatable eQual i zing perfo.-ma n.ce.

The CU T/BOO S T controls R2 1. R2 2 and R23 feed an In -p h ase or OUIOfph llse proportion a l signal 10 the buffer amplifiers Z5.26 and Z8 respective ly. The level o f l he, i g na l fed to lhe buffers Is dep.. n dent 00 the CUT/BOOST control $e !l ing with maximum level occur ring a t ei l her end oft he po len tiome le r, aod a null selling a t the potent iome ter mid -pos i ti on. Full clockwise or full c ou nten;lockw i s e pot &quot;&quot; li o meier selling &quot; will r e ' UI I Int h e maximum e q ulltiza tion o f +15 d Band -15 dB respect i vel y.

The outputs o f buffer amplifiers Z 5, Z6 lind Z8 are !&quot;OUle d 10 th..

4-126 printed Circuit board whleh con l lli n s Ih re e band pa&quot;, fillers

correspond ing 10 each 01 the three sections oft h e equalizer. Each

CIRCUlT DESCRIPTION

ban dp ass filt..... pass.. s only apo...t ion oft hes ' g na l d eliv.. red to it f rem th.. buff.. r, with the c.. nt er frequency and bandwidth deter mined by th.. FRE OUENCY, &quot;0&quot; and PEA K/sHELF controls.

The HIGH FREQUENCY equalization i s continuously adjustable from 1.6 to 25 kHz and i s control l..d by 1'11/1'12.1'12 1 d.. termin.. s the amount of CUT or BOOST. A total range from -15 to +15 dB isp rovid ed. With SWl l depressed the unit will produce a high frequency SHELVING characteristic. When SWll is ret eased, both positive o r negative PEAKING can be obtained. The Q control 1'1 3 is effect i v eon ly with SWl lin the PEA KING mode and covers a c ee cr e rra nge of 2 to 10.

The MID FR EOUE NCY equal iz a ti o n i sad j u s ted by 1'1 4/1'15, cover ing a frequency range from 0.4 to 6.4 kHz. c U T/BOOST i s control led by 1'122.1'16 adjusts the c -rec to-. Positive o r negative bet I -shaped PEA KING equalization i sap p l i cable int h e mid-frequency range.

The LOW FRECl UE NCY equalization operates similarly tot h e high frequency &quot; ec t ion. R?/RS adjusts the frequency range f r-om 25 to 400 H z. CUT or BOOST are con tr-olle&lt;:l by 1'123, C b y 1'1 9 and SW12 determines the choice of either SHELVING o r PEAKING characteristics.

The threes i g na l s which le &quot;ve the 4 _126 filter are &quot;correct ions ign als&quot; e lth erin ~pha s e or 16 0 degrees QUt _of _ph as e with the equalizer input and b andp a&quot; s limited a s determined by the equalizer section and contr-o l &quot; ell ing s. These &quot; c orr ec ti o n &quot;,gnals &quot; a...e then &quot; u mme d together with the p...i mary (in put) s; g n alb y the operational amp l i fie rs 21, 22 and 2 4 thus form ing the eq u.allz eo outputs i g na l.

This con c e p t o fad dIng a correction signal together with the inc om ing signal to form thee qua l i zeds i g n ali s directly responsible forth e low noise and distortion capabilities oft his unit.

T h.. compounds i g na las gen era ted along the entire processing ch.!lin appears a t the output of Z4. From here I t i s rout.. d too n e of then orm ally open contacts 01 the EClUALI ZER INSERTs wItch SW13.

Thus, with SW13 depressed, t h.. equalized signal is fed tot h.. output

:;~~i f:: r a:t~ ~O:t~ d. Ina d d i t ion, a&quot; SW13 is depressed, the LED indi

8-109A OUl p...11 Amplifier and INSERT

The 8-109A amplifier raises I hes, g n a l 10 -10 dBm nominally. The o u l P u l Is ac llvely balanced and fed tot fre &quot;tn s e.. t point &quot; a t p,n s 22 and Z o f mce ure c cone c tc.. P I. This point i s usually connected to II ' no..m&quot;ll e d' set o fIns e &quot; l Jacks, with the OUlp ul side eco eec re e 10 the l u bm &quot;,n e.. fade...

The OUlpul o f Ih e balanced lade.. Is..e lu rned 10 the module via pins 14 and R o f P I. The feed for I h e PREFADE REVERBERATION SEND IRS), Ih e P REF ADE F DL D8 ACK (FBI and the PREFACE PUBliC ADDRESS (PAl channel.. 1$ broug h l OUI a l P I, pi n$ 20 and X and O('lgi...a les nornlall y from l he inputs ide o f l he h de...

An e &gt;&lt;le.....a l s la lei npul Is pl&quot;'Ov lded a l c,,&quot; n ec lo r P2, pins 8 and J. The st e te $lg...a l Is;...j ect e c In place of Ih e reg u la.. signal wh........ el ay KI is ee t tv ete e, Trim POI RU2 serves to cal lbra le Ih estate level.

8 - I 09 F Boos l er AmE.!.!..!.!.!!::

This amplifier o pe.. ales wll h again o f 33 dB. It..ec o ve..s l h e 1!'od B &quot;in hand &quot; Ion In cur..ed b y the fad era n d provides add i lion a l gain 10 produce a noml nll l level o f +8 dBm a t l iS oulp u l.

A DIRECT OUl p ul from l he 8_ 10 91'&quot; amp l Hl...... i$ provided a l conn ecl O&quot; P2, pins 12 and N. Aside from o lh e.. U5e.. wl l hln a given console sys lem, the DIRECT OUl pu l feeds Ihe s u bm as te.. VU me le.. and 5&lt;'!f'VeS a5 tte l ak e-off point for motIllori ng.

~as l e r Ou l Puts and PAN Conlro l

Two left and I wo..; ghl OUIPU IS ere also fed by the 8 -109 F OUIP u l

signal. They are rou led via PAN $ w l tch SWU and PAN &lt;:0&lt;\11&quot;01 R24 10

R2 7, followed b y l our MASTER ASSIGNMENT SWITCHES S W22 10 S\'I25. The

WAR DSEC K SYBTEMB L.TD.

**CIRCUIT OESCR IP TI ON**

ma. ler OUIPUI S are CO....l ecled 10 the approp ri ale module OUlpU I I~ i_...a l. via s u mmi...g e lO&quot;ork re, ls tors 10 b e comb l...ee w lll'l f~s from Oll'ler....bmasle r mi&gt;d g cl'la....... Ie •

Auxiliary O...lp...l.

I... addl liO&lt;'\, a SOL.O OIJIPU I I. available via SWI6, 10 allow setec r tve mO&lt;'\ilo ri...g of Ihe perl ic:u lars u b maS le r channel. Olher feeds o rigi _ n&amp;ling from tt-e 8-109F emp l i fler lire supplied 10 Iha POS TFAOE RS, F B, a...d PAc b e...n el s.

PRE/POST Se le c lo r Sw it cha. and L.a v e l Co r&quot;rol s

PRE/ POST. e lec lion o f Ih e RS, Faa n d P A channels is facilitated by s wl lc hes SW18, SWI9, SW20 lind $ W4 respect iv e l y; each, wl lc his followed by its a s socllll ed level con lro l. The outputs oft h e level controls are fed tot h e $u mm ln g OUlputs via IndIvidual a ssl g n men l switch e • • Following 11'1 10 assign men t, w il che s, Ih e s e OUtpu l S are fed tot heir app rop ria l e mixing bUSeS v lll summing resistors.

Au xl tia ry Control FunC llons

DC control coni llCI S are provided on the SOLO and PA assignment... llches top e rm, ' external mu ti...g and sel ec live con lrol funC lions as maybe required.

Power Supply O&quot;,coup ll...g

An aClive pow&quot;,r supply decoup li...g nelwork c:ol'l$i stlng of 01 Ih rough 06 provides a high degree of Isolalion between Ih a &quot;&quot;'631.. and Ih e +/-25 v o l! supply rail '. TheIr a n s lSl 0r5 05 and 06 serve as Ihe cu.....,...1 monitors and wll l Iimi l Ih e e....... ent flo.. ing th rcu g h the pa.&quot; Iran s ls tors OJ a...d 04 int he even l Ih a l excessive power supply demands. h ou l d arise a. a result of compone&quot;' l failure,

**FREOUENCY RESPONSE CHARACTERISTICS**

LOW FREQUENCY section Hod e: SHELVING.

US se.

CUT/B OOST: -e

FREQUENtT: 2 5 &amp; 400 Hz.

**III III**

VI y 1'----'

\ III LOW FREQUENCY section -.,I I 1:

xeee:

PEAKING.

CUT/ BOOST: tIS ea. -e jf

FREQUErttY: 2S &amp; 400 Hz.

**I'I ! I**

Q: 2.

-&quot;:10'&quot;,~ &quot;It-fO&gt;.

**FREOUENCY RESPONSE CHARACTERISTICS**

MID FREQUENCY section CUT/B OOST: tI Ssa.

FREQUENCY: 0.4 &amp; 6.4 kHz.

Q: Z.

HID FREQUENCY section BOOST: +3 to +15 dB, in 3 dB steps. Q: 2.

FREQUENCY: 1 kHz.

CUT: -6 &amp; -15 dB. Q: 10.

FREQUENCY: 2 kHz. -&quot;'&quot;HI

</details>

<!-- /module data -->

## Photos

_Photographs of the module itself: front, back, inside, racked._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKV0ttSWV1aGo1MnM/view?resourcekey=0-oVsp5JjMeXfKONMGsXJ8zg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKV0ttSWV1aGo1MnM&resourcekey=0-oVsp5JjMeXfKONMGsXJ8zg" width="240" alt="1974 - M463L - 1.jpg"></a><br><sub>1974|7 · 1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKeDN0WUYxNXJVNzg/view?resourcekey=0-QKNi-pthCq--eS2A3lWe2w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKeDN0WUYxNXJVNzg&resourcekey=0-QKNi-pthCq--eS2A3lWe2w" width="240" alt="1974 - M463L - 2.jpg"></a><br><sub>1974|7 · 2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZnFaLUlLam14ZVU/view?resourcekey=0-vZ9qqj9Fboysef9RPf4WgQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZnFaLUlLam14ZVU&resourcekey=0-vZ9qqj9Fboysef9RPf4WgQ" width="240" alt="1974 - M463L - 3.jpg"></a><br><sub>1974|7 · 3</sub></td></tr>
</table>

## Mechanical

_Mechanical drawings: front panels, cover plates, metalwork and hardware (-03- drawings), AutoCAD files, each with its `(EXTRACTED).svg` vectors; `<module> - front panel.svg` is the front panel as vectors._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKanZ3eWhrdWpmYnM/view?resourcekey=0-VeakbVaBRjpU8ZT3cNCWkQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKanZ3eWhrdWpmYnM&resourcekey=0-VeakbVaBRjpU8ZT3cNCWkQ" width="240" alt="1974 - M463L - 463-04-023 - ENG SUBMA STER MODULE.jpg"></a><br><sub>1974|7 · 463-04-023 - ENG SUBMA STER MODULE · <a href="MECHANICAL/1974%20-%20M463L%20-%20463-04-023%20-%20ENG%20SUBMA%20STER%20MODULE%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYkduUWE3QjdITWM/view?resourcekey=0-eeZBk_PA1dkvFJRNYocqJg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYkduUWE3QjdITWM&resourcekey=0-eeZBk_PA1dkvFJRNYocqJg" width="240" alt="1974 - M463L - 463-04-024 - OUTPUT AMP UPPER LEGEND.jpg"></a><br><sub>1974|7 · 463-04-024 - OUTPUT AMP UPPER LEGEND · <a href="MECHANICAL/1974%20-%20M463L%20-%20463-04-024%20-%20OUTPUT%20AMP%20UPPER%20LEGEND%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

## Schematics

_Electrical drawings: schematics (-02-), functional diagrams (-01-), component layouts (-06-), wiring (-09-), PCB files (.pcb .dsn), and beside each scan its `(EXTRACTED).svg`: the vectors traced from it._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKejVDN09nZUtBM3c/view?resourcekey=0-6hLEe_rB9uNNOAc6zep_XQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKejVDN09nZUtBM3c&resourcekey=0-6hLEe_rB9uNNOAc6zep_XQ" width="240" alt="1974 - M463L - 4-126-02-001 - IOK COMBINED COMBINED VALLE VALUE.jpg"></a><br><sub>1974|7 · 4-126-02-001 - IOK COMBINED COMBINED VALLE VALUE · <a href="SCHEMATICS/1974%20-%20M463L%20-%204-126-02-001%20-%20IOK%20COMBINED%20COMBINED%20VALLE%20VALUE%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZ3F1NUd2eVdmeFU/view?resourcekey=0-fiwvodS3K11REyJ5BHPtIg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZ3F1NUd2eVdmeFU&resourcekey=0-fiwvodS3K11REyJ5BHPtIg" width="240" alt="1974 - M463L - 4-126-06-001 - ISSMOD ICKD USED.jpg"></a><br><sub>1974|7 · 4-126-06-001 - ISSMOD ICKD USED · <a href="SCHEMATICS/1974%20-%20M463L%20-%204-126-06-001%20-%20ISSMOD%20ICKD%20USED%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUkRzOG9wX3pMMWc/view?resourcekey=0-m_80A6hU33z-w3PeInlqBg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUkRzOG9wX3pMMWc&resourcekey=0-m_80A6hU33z-w3PeInlqBg" width="240" alt="1974 - M463L - 4-126-06-001 - SOCCKES ADDEI.jpg"></a><br><sub>1974|7 · 4-126-06-001 - SOCCKES ADDEI · <a href="SCHEMATICS/1974%20-%20M463L%20-%204-126-06-001%20-%20SOCCKES%20ADDEI%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbEUtR3IzZWd5Y28/view?resourcekey=0-FCMB_QBpqbBuJJaMkYPmcQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbEUtR3IzZWd5Y28&resourcekey=0-FCMB_QBpqbBuJJaMkYPmcQ" width="240" alt="1974 - M463L - 4-136-06-019 - JIS JII.jpg"></a><br><sub>1974|7 · 4-136-06-019 - JIS JII · <a href="SCHEMATICS/1974%20-%20M463L%20-%204-136-06-019%20-%20JIS%20JII%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQXVwLVhoajNhR1U/view?resourcekey=0-lXcS9BOEjsbvZ4A3Sdxn8w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQXVwLVhoajNhR1U&resourcekey=0-lXcS9BOEjsbvZ4A3Sdxn8w" width="240" alt="1974 - M463L - 4-141-02-001 - TORY SELECTED JAL VALE.jpg"></a><br><sub>1974|7 · 4-141-02-001 - TORY SELECTED JAL VALE · <a href="SCHEMATICS/1974%20-%20M463L%20-%204-141-02-001%20-%20TORY%20SELECTED%20JAL%20VALE%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcC0xdk55SEpoMm8/view?resourcekey=0-GlGUxrvIXfEuoLBsp5mLOA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcC0xdk55SEpoMm8&resourcekey=0-GlGUxrvIXfEuoLBsp5mLOA" width="240" alt="1974 - M463L - 4-141-02-001.jpg"></a><br><sub>1974|7 · 4-141-02-001 · <a href="SCHEMATICS/1974%20-%20M463L%20-%204-141-02-001%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKaEtPaTF0RnAyZms/view?resourcekey=0-WgMw6KployscV3PnLELDLA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKaEtPaTF0RnAyZms&resourcekey=0-WgMw6KployscV3PnLELDLA" width="240" alt="1974 - M463L - 4-141-06-001 - ARE FACTORY SELECTED.jpg"></a><br><sub>1974|7 · 4-141-06-001 - ARE FACTORY SELECTED · <a href="SCHEMATICS/1974%20-%20M463L%20-%204-141-06-001%20-%20ARE%20FACTORY%20SELECTED%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMDA2VVRwYmRwTlE/view?resourcekey=0-yqpL12IQbyEwBiu8T_D-qg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMDA2VVRwYmRwTlE&resourcekey=0-yqpL12IQbyEwBiu8T_D-qg" width="240" alt="1974 - M463L - 4-141-06-001 - OPL ZOO RII.jpg"></a><br><sub>1974|7 · 4-141-06-001 - OPL ZOO RII · <a href="SCHEMATICS/1974%20-%20M463L%20-%204-141-06-001%20-%20OPL%20ZOO%20RII%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYWJhYUJyZWNZMmM/view?resourcekey=0-GS_fVdM6ROuPyHq2eK1glA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYWJhYUJyZWNZMmM&resourcekey=0-GS_fVdM6ROuPyHq2eK1glA" width="240" alt="1974 - M463L - 463-01-011 - CONTROL SOLO SOLO CONTROL SOLO COMMON CONTROL.jpg"></a><br><sub>1974|7 · 463-01-011 - CONTROL SOLO SOLO CONTROL SOLO COMMON CONTROL · <a href="SCHEMATICS/1974%20-%20M463L%20-%20463-01-011%20-%20CONTROL%20SOLO%20SOLO%20CONTROL%20SOLO%20COMMON%20CONTROL%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMWduQXpwdlo2bVE/view?resourcekey=0-rmM1QD8AZlB8rGmPccdlZA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMWduQXpwdlo2bVE&resourcekey=0-rmM1QD8AZlB8rGmPccdlZA" width="240" alt="1974 - M463L - 463-01-011 - INSERT INSERT JACKS FADER.jpg"></a><br><sub>1974|7 · 463-01-011 - INSERT INSERT JACKS FADER · <a href="SCHEMATICS/1974%20-%20M463L%20-%20463-01-011%20-%20INSERT%20INSERT%20JACKS%20FADER%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZnVIYXhWRGhzWWs/view?resourcekey=0-13UPCt-BpV16uMGgOrzBGQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZnVIYXhWRGhzWWs&resourcekey=0-13UPCt-BpV16uMGgOrzBGQ" width="240" alt="1974 - M463L - 463-02-011 - ATE BELLI SUB.jpg"></a><br><sub>1974|7 · 463-02-011 - ATE BELLI SUB · <a href="SCHEMATICS/1974%20-%20M463L%20-%20463-02-011%20-%20ATE%20BELLI%20SUB%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKLVlPZGMtSlpIejg/view?resourcekey=0-RFryXxunG8yyjQ8WAHmskA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKLVlPZGMtSlpIejg&resourcekey=0-RFryXxunG8yyjQ8WAHmskA" width="240" alt="1974 - M463L - 8-109-02-002 - OUTPUT AMPLIFIER.jpg"></a><br><sub>1974|7 · 8-109-02-002 - OUTPUT AMPLIFIER · <a href="SCHEMATICS/1974%20-%20M463L%20-%208-109-02-002%20-%20OUTPUT%20AMPLIFIER%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMFV2NGp4a3VVaVU/view?resourcekey=0-6yFkbX2KL4ESKuzRDnTsbQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMFV2NGp4a3VVaVU&resourcekey=0-6yFkbX2KL4ESKuzRDnTsbQ" width="240" alt="1974 - M463L - 8-109-02-002 - RII RIZ.jpg"></a><br><sub>1974|7 · 8-109-02-002 - RII RIZ · <a href="SCHEMATICS/1974%20-%20M463L%20-%208-109-02-002%20-%20RII%20RIZ%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcFhPTDFvcjU5c2s/view?resourcekey=0-u5lMfI9zUOafFzORTD5joA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcFhPTDFvcjU5c2s&resourcekey=0-u5lMfI9zUOafFzORTD5joA" width="240" alt="1974 - M463L - 8-109-02-007 - RII RIZ.jpg"></a><br><sub>1974|7 · 8-109-02-007 - RII RIZ · <a href="SCHEMATICS/1974%20-%20M463L%20-%208-109-02-007%20-%20RII%20RIZ%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKb1daZFlKU1RRSGM/view?resourcekey=0-08ggQSH3dVT3rM-bvaofKg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKb1daZFlKU1RRSGM&resourcekey=0-08ggQSH3dVT3rM-bvaofKg" width="240" alt="1974 - M463L - 8-109-06-002 - RAS COMPONENT LAYOUT.jpg"></a><br><sub>1974|7 · 8-109-06-002 - RAS COMPONENT LAYOUT · <a href="SCHEMATICS/1974%20-%20M463L%20-%208-109-06-002%20-%20RAS%20COMPONENT%20LAYOUT%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVXlOMTNjSHNmMVk/view?resourcekey=0-2xu8AYykKJGb8wEaB41LRQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVXlOMTNjSHNmMVk&resourcekey=0-2xu8AYykKJGb8wEaB41LRQ" width="240" alt="1974 - M463L - 8-109-06-002.jpg"></a><br><sub>1974|7 · 8-109-06-002 · <a href="SCHEMATICS/1974%20-%20M463L%20-%208-109-06-002%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcmFlZnFNeG4yN1E/view?resourcekey=0-Vta-_GHsSOhVtN6wyMBVSQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcmFlZnFNeG4yN1E&resourcekey=0-Vta-_GHsSOhVtN6wyMBVSQ" width="240" alt="1974 - M463L - 8-109-06-007 - BOOSTER AMPLIFIER.jpg"></a><br><sub>1974|7 · 8-109-06-007 - BOOSTER AMPLIFIER · <a href="SCHEMATICS/1974%20-%20M463L%20-%208-109-06-007%20-%20BOOSTER%20AMPLIFIER%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMThKY01DNWllZTQ/view?resourcekey=0-BTOPlySjq4iBtzjxHToZsw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMThKY01DNWllZTQ&resourcekey=0-BTOPlySjq4iBtzjxHToZsw" width="240" alt="1974 - M463L - 8-109-06-007 - DRI ENG.jpg"></a><br><sub>1974|7 · 8-109-06-007 - DRI ENG · <a href="SCHEMATICS/1974%20-%20M463L%20-%208-109-06-007%20-%20DRI%20ENG%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVGFESkUyMzFINGM/view?resourcekey=0-qZ4nntvpAIr8T5yWfrikrA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVGFESkUyMzFINGM&resourcekey=0-qZ4nntvpAIr8T5yWfrikrA" width="240" alt="1976 - M463L - 4-126-02-001 - EQUALIZER FILIER ISCALE AMPLIFIER SCHEMATX.jpg"></a><br><sub>1976|9 · 4-126-02-001 - EQUALIZER FILIER ISCALE AMPLIFIER SCHEMATX · <a href="SCHEMATICS/1976%20-%20M463L%20-%204-126-02-001%20-%20EQUALIZER%20FILIER%20ISCALE%20AMPLIFIER%20SCHEMATX%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

Not on Google Drive yet: `1974 - 4-141-02-001 - 4-141 SUMMING AMPLIFIER SCHEMATIC - DRN DM - ISS 8.jpg`, `1978 - 8-109-02-002 - 8-109 A OUTPUT AMPLIFIER SCHEMATIC - DRN GEB - ENG MRW - ISS 1.jpg`, `1978 - 8-109-02-007 - 8-109F BOOSTER AMPLIFIER SCHEMATIC - DRN GEB - ENG MRW - ISS 1.jpg`, `19xx - 8-109-02-002.jpg`

## Pinouts

_Pinouts: the RTO-144 edge connector (connection sheets, connector layouts and rear views, strapping), and the pinout / connections drawings made from them. The module root `RTO.json` lists every contact._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdHNCWGtlN1BZWVU/view?resourcekey=0-BQwdUwlnuAheNIgajHw-NA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdHNCWGtlN1BZWVU&resourcekey=0-BQwdUwlnuAheNIgajHw-NA" width="240" alt="1974 - M463L - 461-03-015 - COMPONENT SIDF NOTES LEGEND CONNECTOR PIN MOUNTED.jpg"></a><br><sub>1974|7 · 461-03-015 - COMPONENT SIDF NOTES LEGEND CONNECTOR PIN MOUNTED · <a href="PINOUTS/1974%20-%20M463L%20-%20461-03-015%20-%20COMPONENT%20SIDF%20NOTES%20LEGEND%20CONNECTOR%20PIN%20MOUNTED%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKOGlqc2NURkN5MU0/view?resourcekey=0-PSEUonWy-rouH9ZDafOWbw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKOGlqc2NURkN5MU0&resourcekey=0-PSEUonWy-rouH9ZDafOWbw" width="240" alt="1974 - M463L - 463-04-024 - CONNECTOR REAR VIEW.jpg"></a><br><sub>1974|7 · 463-04-024 - CONNECTOR REAR VIEW · <a href="PINOUTS/1974%20-%20M463L%20-%20463-04-024%20-%20CONNECTOR%20REAR%20VIEW%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

Not on Google Drive yet: `M463L - RTO-144 Connections.pdf`

## RTO-144 pinout

Read from 1 pinout picture (each its own `.pinout.json` beside it). Every contact, with where it was read: [`RTO.json`](RTO.json). How a picture becomes this table: [the pinout decision tree](https://github.com/WardBeckSystems/WBSps.ca/blob/main/2026/Engineering/PINOUTS.md).

| Pin | Signal | Kind | Port | Confidence |
|---|---|---|---|---|
| 1 | INTERNAL CONNECTION | other |  | high |
| 2 | GROUND | ground |  | high |
| 3 | LEFT 1 OUT | out | LEFT 1 OUT L | high |
| 4 | LEFT 2 OUT | out | LEFT 2 OUT L | high |
| 5 | RIGHT 1 OUT | out | RIGHT 1 OUT R | high |
| 6 | RIGHT 2 OUT | out | RIGHT 2 OUT R | high |
| 7 | GROUND | ground |  | high |
| 8 | SLATE IN | in | SLATE IN | high |
| 9 | N/C | nc |  | high |
| 10 | INTERNAL CONNECTION | other |  | high |
| 11 | INTERNAL CONNECTION | other |  | high |
| 12 | DIRECT OUTPUT | out | DIRECT OUTPUT | high |
| 13 | INTERNAL CONNECTION | other |  | high |
| 14 | INTERNAL CONNECTION | other |  | high |
| 15 | SLATE CONTROL | control_in | SLATE CONTROL | high |
| 16 | INTERNAL CONNECTION | other |  | high |
| 17 | INTERNAL CONNECTION | other |  | high |
| 18 | CONTROL COMMON | ground |  | high |
| 19 | -25 V | power |  | high |
| 20 | 25 V COM | ground |  | high |
| 21 | +25 V | power |  | high |
| 22 | CHASSIS | ground |  | high |
| A | INTERNAL CONNECTION | other |  | high |
| B | GROUND | ground |  | high |
| C | LEFT 1 OUT | out | LEFT 1 OUT L | high |
| D | LEFT 2 OUT | out | LEFT 2 OUT L | high |
| E | RIGHT 1 OUT | out | RIGHT 1 OUT R | high |
| F | RIGHT 2 OUT | out | RIGHT 2 OUT R | high |
| H | GROUND | ground |  | high |
| J | SLATE IN | in | SLATE IN | high |
| K | N/C | nc |  | high |
| L | INTERNAL CONNECTION | other |  | high |
| M | INTERNAL CONNECTION | other |  | high |
| N | DIRECT OUTPUT | out | DIRECT OUTPUT | high |
| P | INTERNAL CONNECTION | other |  | high |
| R | INTERNAL CONNECTION | other |  | high |
| S | N/C | nc |  | high |
| T | PA CONTROL | control_in | PA CONTROL | high |
| U | INTERNAL CONNECTION | other |  | high |
| V | SOLO CONTROL | control_in | SOLO CONTROL | high |
| W | INTERNAL CONNECTION | other |  | high |
| X | INTERNAL CONNECTION | other |  | high |
| Y | +24 V | power |  | high |
| Z | INTERNAL CONNECTION | other |  | high |

## Manuals and documents

_Manuals and manual pages, price lists, RTO-144 connection sheets, brochures, ads and other document scans._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSmtNRGZWdW9COXM/view?resourcekey=0-u4_8Q2V2---lUayPo2-cwg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSmtNRGZWdW9COXM&resourcekey=0-u4_8Q2V2---lUayPo2-cwg" width="240" alt="1974 - M463L - P001 - Title Page.jpg"></a><br><sub>1974|7 · P001 - Title Page</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKLW10OFpnWXhzRmM/view?resourcekey=0-e7vLOA4MK7IwTkoFMLd9Jw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKLW10OFpnWXhzRmM&resourcekey=0-e7vLOA4MK7IwTkoFMLd9Jw" width="240" alt="1974 - M463L - P002.jpg"></a><br><sub>1974|7 · P002</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKS0V4QTBFR2RhRFE/view?resourcekey=0-FiNV7BaX7GVHCdNH3qUtDw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKS0V4QTBFR2RhRFE&resourcekey=0-FiNV7BaX7GVHCdNH3qUtDw" width="240" alt="1974 - M463L - P003 - 1-1.jpg"></a><br><sub>1974|7 · P003 - 1-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQ2gzMHdCeWowOUE/view?resourcekey=0-J2EVAKv2m_3E6OoNHRGyhQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQ2gzMHdCeWowOUE&resourcekey=0-J2EVAKv2m_3E6OoNHRGyhQ" width="240" alt="1974 - M463L - P004 - 2-1.jpg"></a><br><sub>1974|7 · P004 - 2-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQlJvR3FseGJycjg/view?resourcekey=0-JQe6BJHr8nbD6bJQuFqjnA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQlJvR3FseGJycjg&resourcekey=0-JQe6BJHr8nbD6bJQuFqjnA" width="240" alt="1974 - M463L - P005 - 2-2.jpg"></a><br><sub>1974|7 · P005 - 2-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRDNkdUJRUkh4akk/view?resourcekey=0-RFMy5Q2B70iA81MHF6eSmw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRDNkdUJRUkh4akk&resourcekey=0-RFMy5Q2B70iA81MHF6eSmw" width="240" alt="1974 - M463L - P006 - 2-3.jpg"></a><br><sub>1974|7 · P006 - 2-3</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbDFGTHp1SUR6Q1E/view?resourcekey=0-QPPPcV568YDXGTaSArNWCQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbDFGTHp1SUR6Q1E&resourcekey=0-QPPPcV568YDXGTaSArNWCQ" width="240" alt="1974 - M463L - P007 - 2-4.jpg"></a><br><sub>1974|7 · P007 - 2-4</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKb0c0ejJUaGhJekk/view?resourcekey=0-VSuO9f1DPoOLFAXhwN8EyQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKb0c0ejJUaGhJekk&resourcekey=0-VSuO9f1DPoOLFAXhwN8EyQ" width="240" alt="1974 - M463L - P008 - 3-1.jpg"></a><br><sub>1974|7 · P008 - 3-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbkVheVJmMWdfVlE/view?resourcekey=0-QVCDcEvxHK_qPaDWCU4htw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbkVheVJmMWdfVlE&resourcekey=0-QVCDcEvxHK_qPaDWCU4htw" width="240" alt="1974 - M463L - P009 - 3-2.jpg"></a><br><sub>1974|7 · P009 - 3-2</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZzNEeExYOXRjWVE/view?resourcekey=0-22WS-L0t1nqloXeZaEuQzw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZzNEeExYOXRjWVE&resourcekey=0-22WS-L0t1nqloXeZaEuQzw" width="240" alt="1974 - M463L - P010 - 3-3.jpg"></a><br><sub>1974|7 · P010 - 3-3</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRURSSUVyTVpaSkE/view?resourcekey=0-bXAyu6HK5PsDxqJKsXiJ4g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRURSSUVyTVpaSkE&resourcekey=0-bXAyu6HK5PsDxqJKsXiJ4g" width="240" alt="1974 - M463L - P011 - 4-1.jpg"></a><br><sub>1974|7 · P011 - 4-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMVJ2T0MxNlZNOW8/view?resourcekey=0-UQnEe1y8Fd72gOYS6wBvLw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMVJ2T0MxNlZNOW8&resourcekey=0-UQnEe1y8Fd72gOYS6wBvLw" width="240" alt="1974 - M463L - P012 - 4-2.jpg"></a><br><sub>1974|7 · P012 - 4-2</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKN3YwWmlsWkFCcXM/view?resourcekey=0-QvSJoGOBG76nw3iOus3W7A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKN3YwWmlsWkFCcXM&resourcekey=0-QvSJoGOBG76nw3iOus3W7A" width="240" alt="1974 - M463L - P013 - 4-3.jpg"></a><br><sub>1974|7 · P013 - 4-3</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZXAxRW1mbUhaMkk/view?resourcekey=0-vwb24wANLCGpZEuqGS7ttA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZXAxRW1mbUhaMkk&resourcekey=0-vwb24wANLCGpZEuqGS7ttA" width="240" alt="1974 - M463L - P014 - 4-4.jpg"></a><br><sub>1974|7 · P014 - 4-4</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMHdvWkZudmt1S1U/view?resourcekey=0-_qFUMBML77YsVtB9DVzaGA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMHdvWkZudmt1S1U&resourcekey=0-_qFUMBML77YsVtB9DVzaGA" width="240" alt="1974 - M463L - P015 - 4-5.jpg"></a><br><sub>1974|7 · P015 - 4-5</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWTZNS1N0M0dWekk/view?resourcekey=0-OQFETo_qYMoiONjdjQBebQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWTZNS1N0M0dWekk&resourcekey=0-OQFETo_qYMoiONjdjQBebQ" width="240" alt="1974 - M463L - P016 - 4-6.jpg"></a><br><sub>1974|7 · P016 - 4-6</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKN0UxZ0M4dUlpdmM/view?resourcekey=0-RDZbaQabmPxkHU7Uy2z74Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKN0UxZ0M4dUlpdmM&resourcekey=0-RDZbaQabmPxkHU7Uy2z74Q" width="240" alt="1974 - M463L - P017 - 4-7.jpg"></a><br><sub>1974|7 · P017 - 4-7</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVVFJTml6aF9OMWc/view?resourcekey=0-Uxn8l4yNQEN0HafafsfXTQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVVFJTml6aF9OMWc&resourcekey=0-Uxn8l4yNQEN0HafafsfXTQ" width="240" alt="1974 - M463L - P018 - 4-8.jpg"></a><br><sub>1974|7 · P018 - 4-8</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYXNBZnpYeGRVSmM/view?resourcekey=0-PJehJlWR0V8dKHRT3DVB4A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYXNBZnpYeGRVSmM&resourcekey=0-PJehJlWR0V8dKHRT3DVB4A" width="240" alt="1974 - M463L - P019 - 4-9.jpg"></a><br><sub>1974|7 · P019 - 4-9</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKR0t2VEJZSUhzVXM/view?resourcekey=0-7q_c0kZEjqIEU1plruiYlA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKR0t2VEJZSUhzVXM&resourcekey=0-7q_c0kZEjqIEU1plruiYlA" width="240" alt="1974 - M463L - P020 8-109.jpg"></a><br><sub>1974|7 · P020 8-109</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKX1VrOEoxcmM0Rm8/view?resourcekey=0-Lha0OH8tID5Aa0lydniIOw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKX1VrOEoxcmM0Rm8&resourcekey=0-Lha0OH8tID5Aa0lydniIOw" width="240" alt="1974 - M463L - P021 - 8-109-1-1.jpg"></a><br><sub>1974|7 · P021 - 8-109-1-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWG5SNVpGek1JczQ/view?resourcekey=0-c3bGGRtUx4REu9z5KDRHmw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWG5SNVpGek1JczQ&resourcekey=0-c3bGGRtUx4REu9z5KDRHmw" width="240" alt="1974 - M463L - P022 - 8-109-1-2.jpg"></a><br><sub>1974|7 · P022 - 8-109-1-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWXRGSER4Z2VZUjg/view?resourcekey=0-mEgo4HzWAssWNPYvs9muVQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWXRGSER4Z2VZUjg&resourcekey=0-mEgo4HzWAssWNPYvs9muVQ" width="240" alt="1974 - M463L - P023 - 8-109-2-1.jpg"></a><br><sub>1974|7 · P023 - 8-109-2-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKOVhIS1l0dHZTOFk/view?resourcekey=0-iKCXHrvfdWx4Ke9-gFDYWg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKOVhIS1l0dHZTOFk&resourcekey=0-iKCXHrvfdWx4Ke9-gFDYWg" width="240" alt="1974 - M463L - P024 - 8-109-2-2.jpg"></a><br><sub>1974|7 · P024 - 8-109-2-2</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTEhSMFN4X1lnSjg/view?resourcekey=0-51aI3iimlChrQy4-0Vfs7A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTEhSMFN4X1lnSjg&resourcekey=0-51aI3iimlChrQy4-0Vfs7A" width="240" alt="1974 - M463L - P025 - 8-109-2-3.jpg"></a><br><sub>1974|7 · P025 - 8-109-2-3</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNGNLVHZ2c2pzSnc/view?resourcekey=0-DkpuvXz-fODJn3c2X4IAkQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNGNLVHZ2c2pzSnc&resourcekey=0-DkpuvXz-fODJn3c2X4IAkQ" width="240" alt="1974 - M463L - P026 - 8-109-2-4.jpg"></a><br><sub>1974|7 · P026 - 8-109-2-4</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQ0pTTjJiTU5yOEk/view?resourcekey=0-I38P4wx8KdToHSF039nWHA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQ0pTTjJiTU5yOEk&resourcekey=0-I38P4wx8KdToHSF039nWHA" width="240" alt="1974 - M463L - P027 - 8-109-2-5.jpg"></a><br><sub>1974|7 · P027 - 8-109-2-5</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKa0czbEh6YUxTbEE/view?resourcekey=0-XEZsNkLn7SdFxDDc12-tPg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKa0czbEh6YUxTbEE&resourcekey=0-XEZsNkLn7SdFxDDc12-tPg" width="240" alt="1974 - M463L - P029 - 4-141 1-1.jpg"></a><br><sub>1974|7 · P029 - 4-141 1-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKczd0bHpDNjh4TVE/view?resourcekey=0-kNmITs38ID8QVi9zM3mtKw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKczd0bHpDNjh4TVE&resourcekey=0-kNmITs38ID8QVi9zM3mtKw" width="240" alt="1974 - M463L - P030 - 4-141 2-1.jpg"></a><br><sub>1974|7 · P030 - 4-141 2-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTHZHbTg0SWJreW8/view?resourcekey=0-mDME9LkUakKI8S-2QSeGRA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTHZHbTg0SWJreW8&resourcekey=0-mDME9LkUakKI8S-2QSeGRA" width="240" alt="1974 - M463L - P031 - 4-141 2-2.jpg"></a><br><sub>1974|7 · P031 - 4-141 2-2</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVjZVSWVRSVRYczA/view?resourcekey=0-kamRw63cppr8Cm3nWkCtZA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVjZVSWVRSVRYczA&resourcekey=0-kamRw63cppr8Cm3nWkCtZA" width="240" alt="1974 - M463L - P033 - 4-126 1-1.jpg"></a><br><sub>1974|7 · P033 - 4-126 1-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKN3Z1cHIzOTE1c1k/view?resourcekey=0-I3wPD2kPs0fwFK2OcTT7SA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKN3Z1cHIzOTE1c1k&resourcekey=0-I3wPD2kPs0fwFK2OcTT7SA" width="240" alt="1974 - M463L - P034 - 4-126 2-1.jpg"></a><br><sub>1974|7 · P034 - 4-126 2-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVU9RYjVfcllXN0E/view?resourcekey=0-gtf5fRdcwtSjcG7Z3mBylA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVU9RYjVfcllXN0E&resourcekey=0-gtf5fRdcwtSjcG7Z3mBylA" width="240" alt="1974 - M463L - P035 - 4-126 2-2.jpg"></a><br><sub>1974|7 · P035 - 4-126 2-2</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMGdjaVhmajFIeVk/view?resourcekey=0-BlOI_KinBQCzS81MayRr0w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMGdjaVhmajFIeVk&resourcekey=0-BlOI_KinBQCzS81MayRr0w" width="240" alt="1974 - M463L - P036 - 4-126 2-3.jpg"></a><br><sub>1974|7 · P036 - 4-126 2-3</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWHQwc3ZsV2pfSEk/view?resourcekey=0-bsryibIPx4YqAgKNmrHDKA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWHQwc3ZsV2pfSEk&resourcekey=0-bsryibIPx4YqAgKNmrHDKA" width="240" alt="1974 - M463L - P037 - 6-1.jpg"></a><br><sub>1974|7 · P037 - 6-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRUwzWjd5TFNyd2M/view?resourcekey=0-FVV0dvwuwrcoL81gE3FJRw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRUwzWjd5TFNyd2M&resourcekey=0-FVV0dvwuwrcoL81gE3FJRw" width="240" alt="1974 - M463L - P038 - 6-2.jpg"></a><br><sub>1974|7 · P038 - 6-2</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVGxoVFFUenU5OUk/view?resourcekey=0-ga5e9QZW9SWU0sjO0nwACw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVGxoVFFUenU5OUk&resourcekey=0-ga5e9QZW9SWU0sjO0nwACw" width="240" alt="1974 - M463L - P039 - 6-3.jpg"></a><br><sub>1974|7 · P039 - 6-3</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKLWtFUEhHQVlBbUU/view?resourcekey=0-57_UsKZ5bUMg2YEskkaQ4Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKLWtFUEhHQVlBbUU&resourcekey=0-57_UsKZ5bUMg2YEskkaQ4Q" width="240" alt="1974 - M463L - P042 - LB463-02-011 001.jpg"></a><br><sub>1974|7 · P042 - LB463-02-011 001</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUThaVEdmQ3NueFE/view?resourcekey=0-rEyaTr5EghCDAnAZqSgQ5g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUThaVEdmQ3NueFE&resourcekey=0-rEyaTr5EghCDAnAZqSgQ5g" width="240" alt="1974 - M463L - P042 - LB463-02-011 002.jpg"></a><br><sub>1974|7 · P042 - LB463-02-011 002</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYmEtaFdvaVJURms/view?resourcekey=0-9o35tBrXLsz3M7QNs-AClg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYmEtaFdvaVJURms&resourcekey=0-9o35tBrXLsz3M7QNs-AClg" width="240" alt="1974 - M463L - P042 - LB463-02-011 003.jpg"></a><br><sub>1974|7 · P042 - LB463-02-011 003</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYU5GcGlKcF9ZRFE/view?resourcekey=0-j-xyZbc_AKTqZOasNyMwcw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYU5GcGlKcF9ZRFE&resourcekey=0-j-xyZbc_AKTqZOasNyMwcw" width="240" alt="1974 - M463L - P042 - LB463-02-011 004.jpg"></a><br><sub>1974|7 · P042 - LB463-02-011 004</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZmQ2VktGOVFocWs/view?resourcekey=0-aVSHZ7diM0U5BB70aWQpGA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZmQ2VktGOVFocWs&resourcekey=0-aVSHZ7diM0U5BB70aWQpGA" width="240" alt="1974 - M463L - Submaster Module (2).pdf"></a><br><sub>1974|7 · Submaster Module (2)</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYk9tY2FPaGtqSTQ/view?resourcekey=0-U_yrrxt5qyqnnUCDxpLo8w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYk9tY2FPaGtqSTQ&resourcekey=0-U_yrrxt5qyqnnUCDxpLo8w" width="240" alt="1974 - M463L - Submaster Module.pdf"></a><br><sub>1974|7 · Submaster Module</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVlhjeDFDYnViUEE/view?resourcekey=0-PDOxTUGRQG9kNJOEk6eR3w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVlhjeDFDYnViUEE&resourcekey=0-PDOxTUGRQG9kNJOEk6eR3w" width="240" alt="1983 - M463L - P028 - 4-141.jpg"></a><br><sub>1983|16 · P028 - 4-141</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTXZDZHVrQ0xjUk0/view?resourcekey=0-rC25pHe1mye2W7GncvXVfQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTXZDZHVrQ0xjUk0&resourcekey=0-rC25pHe1mye2W7GncvXVfQ" width="240" alt="1983 - M463L - P032 - 4-126.jpg"></a><br><sub>1983|16 · P032 - 4-126</sub></td></tr>
</table>

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [1974 - 4-141-02-001 - 4-141 SUMMING AMPLIFIER SCHEMATIC - DRN DM - ISS 8.kicad_sch](KICAD/1974%20-%204-141-02-001%20-%204-141%20SUMMING%20AMPLIFIER%20SCHEMATIC%20-%20DRN%20DM%20-%20ISS%208.kicad_sch)
- [1974 - M463L - 4-126-02-001 - IOK COMBINED COMBINED VALLE VALUE.kicad_sch](KICAD/1974%20-%20M463L%20-%204-126-02-001%20-%20IOK%20COMBINED%20COMBINED%20VALLE%20VALUE.kicad_sch)
- [1974 - M463L - 4-141-02-001 - TORY SELECTED JAL VALE.kicad_sch](KICAD/1974%20-%20M463L%20-%204-141-02-001%20-%20TORY%20SELECTED%20JAL%20VALE.kicad_sch)
- [1974 - M463L - 4-141-02-001.kicad_sch](KICAD/1974%20-%20M463L%20-%204-141-02-001.kicad_sch)
- [1974 - M463L - 463-01-011 - CONTROL SOLO SOLO CONTROL SOLO COMMON CONTROL.kicad_sch](KICAD/1974%20-%20M463L%20-%20463-01-011%20-%20CONTROL%20SOLO%20SOLO%20CONTROL%20SOLO%20COMMON%20CONTROL.kicad_sch)
- [1974 - M463L - 463-01-011 - INSERT INSERT JACKS FADER.kicad_sch](KICAD/1974%20-%20M463L%20-%20463-01-011%20-%20INSERT%20INSERT%20JACKS%20FADER.kicad_sch)
- [1974 - M463L - 463-02-011 - ATE BELLI SUB.kicad_sch](KICAD/1974%20-%20M463L%20-%20463-02-011%20-%20ATE%20BELLI%20SUB.kicad_sch)
- [1974 - M463L - 8-109-02-002 - OUTPUT AMPLIFIER.kicad_sch](KICAD/1974%20-%20M463L%20-%208-109-02-002%20-%20OUTPUT%20AMPLIFIER.kicad_sch)
- [1974 - M463L - 8-109-02-002 - RII RIZ.kicad_sch](KICAD/1974%20-%20M463L%20-%208-109-02-002%20-%20RII%20RIZ.kicad_sch)
- [1974 - M463L - 8-109-02-007 - NDMINAL VALUE.kicad_sch](KICAD/1974%20-%20M463L%20-%208-109-02-007%20-%20NDMINAL%20VALUE.kicad_sch)
- [1974 - M463L - 8-109-02-007 - RII RIZ.kicad_sch](KICAD/1974%20-%20M463L%20-%208-109-02-007%20-%20RII%20RIZ.kicad_sch)
- [1974 - M463L - Submaster Module (2) p11.kicad_sch](KICAD/1974%20-%20M463L%20-%20Submaster%20Module%20(2)%20p11.kicad_sch)
- [1974 - M463L - Submaster Module (2) p42.kicad_sch](KICAD/1974%20-%20M463L%20-%20Submaster%20Module%20(2)%20p42.kicad_sch)
- [1974 - M463L - Submaster Module (2) p61.kicad_sch](KICAD/1974%20-%20M463L%20-%20Submaster%20Module%20(2)%20p61.kicad_sch)
- [1974 - M463L - Submaster Module p42.kicad_sch](KICAD/1974%20-%20M463L%20-%20Submaster%20Module%20p42.kicad_sch)
- [1974 - M463L - Submaster Module p53.kicad_sch](KICAD/1974%20-%20M463L%20-%20Submaster%20Module%20p53.kicad_sch)
- [1974 - M463L - Submaster Module p57.kicad_sch](KICAD/1974%20-%20M463L%20-%20Submaster%20Module%20p57.kicad_sch)
- [1974 - M463L - Submaster Module p61.kicad_sch](KICAD/1974%20-%20M463L%20-%20Submaster%20Module%20p61.kicad_sch)
- [1974 - M463L - Submaster Module p65.kicad_sch](KICAD/1974%20-%20M463L%20-%20Submaster%20Module%20p65.kicad_sch)
- [1976 - M463L - 4-126-02-001 - EQUALIZER FILIER ISCALE AMPLIFIER SCHEMATX.kicad_sch](KICAD/1976%20-%20M463L%20-%204-126-02-001%20-%20EQUALIZER%20FILIER%20ISCALE%20AMPLIFIER%20SCHEMATX.kicad_sch)
- [1978 - 8-109-02-002 - 8-109 A OUTPUT AMPLIFIER SCHEMATIC - DRN GEB - ENG MRW - ISS 1.kicad_sch](KICAD/1978%20-%208-109-02-002%20-%208-109%20A%20OUTPUT%20AMPLIFIER%20SCHEMATIC%20-%20DRN%20GEB%20-%20ENG%20MRW%20-%20ISS%201.kicad_sch)
- [1978 - 8-109-02-007 - 8-109F BOOSTER AMPLIFIER SCHEMATIC - DRN GEB - ENG MRW - ISS 1.kicad_sch](KICAD/1978%20-%208-109-02-007%20-%208-109F%20BOOSTER%20AMPLIFIER%20SCHEMATIC%20-%20DRN%20GEB%20-%20ENG%20MRW%20-%20ISS%201.kicad_sch)
- [19xx - 8-109-02-002.kicad_sch](KICAD/19xx%20-%208-109-02-002.kicad_sch)
- [M463L.kicad_sym](KICAD/M463L.kicad_sym)
- [index.html](KICAD/index.html)

## Software

- [index.html](SOFTWARE/index.html)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)
