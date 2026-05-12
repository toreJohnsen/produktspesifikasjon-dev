#### Trafikkmengde

Gir informasjon om representativ trafikkmengde for en strekning

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>senterlinje</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Gir linje/kurve som geometrisk representerer objektet.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Kurve</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>ådtTotal</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Angir total årsdøgntrafikk.  Representativt for gitt strekning.  Gjennomsnittsverdi.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Real</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>ådtAndelLangeKjøretøy</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Angir hvor stor andel (i prosent) av kjøretøyene som er definert som lange.  Kjøretøy med lengde større eller lik 5,6 meter defineres som lange kjøretøy.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Real</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>årGjelderFor</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Angir hvilket år trafikkdataene gjelder for</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Real</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>grunnlagForÅDT</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Angir hva som er grunnlag for ÅDT-verdien</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>GrunnlagForÅDT</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- NorTraf<br />- NorTraf Kommune – Fra NorTraf Kommune<br />- Ferjedatabanken<br />- Telling og skjønn – Basert på telling og skjønn<br />- Skjønn – Basert på skjønn<br />- Vegorama</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>ådtStart</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Angir årsdøgntrafikk i start av gitt strekning.  Inkl tunge kjøretøy</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Real</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>ådtSlutt</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Angir årsdøgntrafikk i slutt av gitt strekning.  Inkl tunge kjøretøy</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Real</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
Veglenke

### Kodelister

#### «Enumeration» GrunnlagForÅDT

**Definisjon:** Angir hva som er grunnlag for ÅDT-verdien

Profilparametre i tagged values

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">asDictionary</th>
      <td>false</td>
    </tr>
  </tbody>
</table>

Koder

<table class="code-list-table">
  <thead>
    <tr>
      <th>Kodenavn:</th>
      <th>Definisjon:</th>
      <th>Kodeverdi:</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>NorTraf</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>NorTraf Kommune</td>
      <td>Fra NorTraf Kommune</td>
      <td></td>
    </tr>
    <tr>
      <td>Ferjedatabanken</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Telling og skjønn</td>
      <td>Basert på telling og skjønn</td>
      <td></td>
    </tr>
    <tr>
      <td>Skjønn</td>
      <td>Basert på skjønn</td>
      <td></td>
    </tr>
    <tr>
      <td>Vegorama</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>
