# Teststoff

#### Elektronische Wandler

- AD-Wandler

  =>	[Analog-Digital-Umsetzer.pdf](./pdf/Analog-Digital-Umsetzer.pdf) 

- DA-Wandler

  =>	[Digital-Analog-Wandler.pdf](./pdf/Digital-Analog-Wandler.pdf) 

#### Mikrofone

- Referate

  =>	[Tauchspulenmikrofon.pdf](./pdf/mikrofone/Tauchspulenmikrofon.pdf) 

  =>	[Baendchenmikrofon.pdf](./pdf/mikrofone/Baendchenmikrofon.pdf) 

  =>	Kondensatormikrofon

  =>	Elektretmirkofon

  =>	[Piezomikrofon.pdf](./pdf/mikrofone/Piezomikrofon.pdf) 

  =>	[Kohlemikrofon.pdf](./pdf/mikrofone/Kohlemikrofon.pdf) 

  =>	[Kohlemikrofon2.pdf](./pdf/mikrofone/Kohlemikrofon2.pdf) 

- Skizzen

#### Theorie 

<hr>

#### 1.3 Signalwandler

Der Begriff Signalwandler (Scan Converter) beschreibt einen in der Videotechnik verwendeten, Umsetzung. Er wandelt ein einkommendes Videosignal eventuell in ein digitalsignal um, speichert es zwischen und gibt es in einem anderen Format wieder aus. (z.B.: VGA in FBAS)

<u>Unterschieden wird zwischen:</u>

**Upconverter:** Skalieren auf höhere Auflösung (z.B.: Pal zu XGA)

**Downconverter:** Skalieren auf niedrige auflösung



### 2. Umwandlung von Schall in elektrische Signale

Ein Mikrofon ist ein Schallwandler der den wechselnden Schalldruck, des Luftschalls in ein elektrisches Signal umsetzt.

Es gibt auch Wandler für Festkörper und Flüssigkeitsschall.

Bei jeder Art von Mikrofon, folgt eine Membran den Schalldruck, oder der Schalldruckänderung.

Das jeweilige verwendete Wandlerprinzip bestimmt Maßgeblich die Qualität des Mikrofon Signals.

Diese ist beschrieben durch folgende Eigenschaft.

##### 1. Rauschabstand

Das Signal-rausch-Verhältnis (Signal-Noise-Ratio) ist definiert als:
$$
SNR = 10 * lg( \frac{Nutzsignalleistung}{Rauschleistung})dB = 10 lg ( \frac{Psignal}{Prauschen})dB
$$
Als logarithmisch dargestelltes Verhältnis von Größen gleicher Maßeinheit ist SNR dimensionslos (Pseudoeinheit dB, Dezibel => logarithmische Verhältniszahl)

##### 2. Impulstreue

Die Impulstreue beschreibt, wie gut der zeitliche Verlaut des Schallereignisses in eine der Spannungen gewandelt wird.

Die Impulstreue ist besser, wenn die Membran leichter ist.

Die Impulstreue ist besser, wenn die Membran leichter ist.

Die mechanische Trägheit der Membran wirkt dann nicht so Signalverfälschend.

##### 3. Klirrfaktor

Maß für unerwünschte Verzerrungen eines ursprünglich Sinusförmigen Signals, welche durch nichtlineares Verhalten einer Baugruppe (Verstärker, AD-, DA- Wandler) oder eines Gerätes (Mirkofon, Verstärker) verursacht wird.

Die durch die nichtlinearen Verzerrungen des Audiosignals verursachten Oberschwingungen werden als unangenehme höherfrequente Geräusche wahrgenommen die an ein Klirren erinnern.



##### Frequenzzugang

Verhältnis der Amplitude bzw. Phasen von Eingangssignal und Ausgangssignal in Abhängigkeit von der Frequenz, dargestellt in einem Bode-Diagramm.