# Bemanning vår 2023


<script>
  function myFunction(searchFieldID, tableID) { 
    var input, filter, table, tbodys, tbody, i, txtValue;
    input = document.getElementById(searchFieldID);
    filter = input.value.toUpperCase();
    table = document.getElementById(tableID);
    tbodys = table.getElementsByTagName("tbody");
    // Loop through all table rows, and hide those who don't match the search query
    for (i = 0; i < tbodys.length; i++) {
      tbody = tbodys[i]
      if (tbody) {
        txtValue = tbody.textContent || tbody.innerText;
        if (txtValue.toUpperCase().indexOf(filter) > -1) {
          tbodys[i].style.display = "";
        } else {
          tbodys[i].style.display = "none";
        }
      }
    }
  }
</script><style>
  .course_staff_table td {
    font-size: 0.875em;
  }
  td.details {
    color: lightgray;
  }
</style><input id="myInput" class="form-control me-2" type="search" placeholder="Search" aria-label="Search" onkeyup="myFunction('myInput', 'myTable')"><table class="course_staff_table table table-sm" id="myTable"><tbody><tr><td rowspan="3" ><a href="https://www.ntnu.no/studier/emner/DCSG1005">DCSG1005</a></td>
<td ><b>Infrastruktur: sikre grunntjenester</b></td></tr>
<tr><td class="details" >Gjøvik</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/erik.hjelmas">Erik Hjelmås</a> emneansvarlig</td></tr></tbody>
<tbody><tr><td rowspan="4" ><a href="https://www.ntnu.no/studier/emner/DCSG1006">DCSG1006</a></td>
<td ><b>Datakommunikasjon og nettverk</b></td></tr>
<tr><td class="details" >Gjøvik</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/ernst.g.gran">Ernst Gunnar Gran</a> lærer</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/eigil.obrestad">Eigil Obrestad</a> lærer</td></tr></tbody>
<tbody><tr><td rowspan="3" ><a href="https://www.ntnu.no/studier/emner/DCSG2003">DCSG2003</a></td>
<td ><b>Robuste og skalerbare tjenester </b></td></tr>
<tr><td class="details" >Gjøvik</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/kyrre.begnum">Kyrre Matthias Begnum</a> lærer</td></tr></tbody>
<tbody><tr><td rowspan="3" ><a href="https://www.ntnu.no/studier/emner/DCSG2005">DCSG2005</a></td>
<td ><b>Risikostyring</b></td></tr>
<tr><td class="details" >Gjøvik</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/gaute.wangen">Gaute Bjørklund Wangen</a> lærer</td></tr></tbody>
<tbody><tr><td rowspan="3" ><a href="https://www.ntnu.no/studier/emner/DCSG2900">DCSG2900</a></td>
<td ><b>Bacheloroppgave Bachelor i digital infrastruktur og cybersikkerhet</b></td></tr>
<tr><td class="details" >THESIS, Gjøvik, &#126;60 students.</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/erik.hjelmas">Erik Hjelmås</a> emneansvarlig</td></tr></tbody>
<tbody><tr><td rowspan="3" ><a href="https://www.ntnu.no/studier/emner/HMS0010">HMS0010</a></td>
<td ><b>HMS-kurs for 1. årsstudenter Gjøvik</b></td></tr>
<tr><td class="details" >HMS, Gjøvik, &#126;150 students.</td></tr>
<tr><td colspan="2" >Hilde Bakke emneansvarlig</td></tr></tbody>
<tbody><tr><td rowspan="3" ><a href="https://www.ntnu.no/studier/emner/IIK6510">IIK6510</a></td>
<td ><b>Digtial sikkerhet - behov</b></td></tr>
<tr><td class="details" >EVU, Gjøvik, &#126;20 students.</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/nils.kalstad">Nils Kalstad</a> emneansvarlig</td></tr></tbody>
<tbody><tr><td rowspan="3" ><a href="https://www.ntnu.no/studier/emner/IIK6511">IIK6511</a></td>
<td ><b>Digtial sikkerhet - risikostrying</b></td></tr>
<tr><td class="details" >EVU, Gjøvik, &#126;20 students.</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/nils.kalstad">Nils Kalstad</a> emneansvarlig</td></tr></tbody>
<tbody><tr><td rowspan="3" ><a href="https://www.ntnu.no/studier/emner/IIK6512">IIK6512</a></td>
<td ><b>Digtial sikkerhet - ledelse og organisasjon</b></td></tr>
<tr><td class="details" >EVU, Gjøvik, &#126;20 students.</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/nils.kalstad">Nils Kalstad</a> emneansvarlig</td></tr></tbody>
<tbody><tr><td rowspan="3" ><a href="https://www.ntnu.no/studier/emner/IIK6513">IIK6513</a></td>
<td ><b>Digtial sikkerhet - teknologi </b></td></tr>
<tr><td class="details" >EVU, Gjøvik, &#126;20 students.</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/nils.kalstad">Nils Kalstad</a> emneansvarlig</td></tr></tbody>
<tbody><tr><td rowspan="3" ><a href="https://www.ntnu.no/studier/emner/IIK6514">IIK6514</a></td>
<td ><b>Introduksjon til digital sikkerhet -innføring</b></td></tr>
<tr><td class="details" >EVU, Gjøvik, &#126;20 students.</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/nils.kalstad">Nils Kalstad</a> emneansvarlig</td></tr></tbody>
<tbody><tr><td rowspan="3" ><a href="https://www.ntnu.no/studier/emner/IIK6515">IIK6515</a></td>
<td ><b>Introduksjon til digital sikkerhet - risikostyring</b></td></tr>
<tr><td class="details" >EVU, Gjøvik, &#126;20 students.</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/nils.kalstad">Nils Kalstad</a> emneansvarlig</td></tr></tbody>
<tbody><tr><td rowspan="3" ><a href="https://www.ntnu.no/studier/emner/IIK6520">IIK6520</a></td>
<td ><b>Grunnleggende cyber- og informasjonssikkerhet for lærere</b></td></tr>
<tr><td class="details" >EVU, Gjøvik, &#126;20 students.</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/nils.kalstad">Nils Kalstad</a> emneansvarlig</td></tr></tbody>
<tbody><tr><td rowspan="3" ><a href="https://www.ntnu.no/studier/emner/IIK6521">IIK6521</a></td>
<td ><b>Anvendt cyber- og informasjonssikkerhet for lærere</b></td></tr>
<tr><td class="details" >EVU, Gjøvik, &#126;20 students.</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/nils.kalstad">Nils Kalstad</a> emneansvarlig</td></tr></tbody>
<tbody><tr><td rowspan="3" ><a href="https://www.ntnu.no/studier/emner/IIKG3010">IIKG3010</a></td>
<td ><b>Project Work for Exchange Bachelor Students</b></td></tr>
<tr><td class="details" >FE, Gjøvik, &#126;3 students.</td></tr>
<tr><td colspan="2" >Hilde Bakke emneansvarlig</td></tr></tbody>
<tbody><tr><td rowspan="3" ><a href="https://www.ntnu.no/studier/emner/IIKG4000">IIKG4000</a></td>
<td ><b>Fordypningsemne - individuelt</b></td></tr>
<tr><td class="details" >FE, Gjøvik, &#126;2 students.</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/raghavendra.ramachandra">Raghavendra Ramachandra</a> emneansvarlig</td></tr></tbody>
<tbody><tr><td rowspan="3" ><a href="https://www.ntnu.no/studier/emner/IIKG4001">IIKG4001</a></td>
<td ><b>EiT</b></td></tr>
<tr><td class="details" >EIT, Gjøvik</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/stewart.kowalski">Stewart James Kowalski</a> emneansvarlig</td></tr></tbody>
<tbody><tr><td rowspan="5" ><a href="https://www.ntnu.no/studier/emner/IMT4016">IMT4016</a></td>
<td ><b>Eksperter i team - Digital communities and welfare</b></td></tr>
<tr><td class="details" >EIT, Gjøvik, &#126;30 students.</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/basel.katt">Basel Katt</a> emneansvarlig</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/basel.katt">Basel Katt</a> lærer</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/erjon.zoto">Erjon Zoto</a> lærer</td></tr></tbody>
<tbody><tr><td rowspan="5" ><a href="https://www.ntnu.no/studier/emner/IMT4116">IMT4116</a></td>
<td ><b>Reverse Engineering and Malware Analysis</b></td></tr>
<tr><td class="details" >Gjøvik, Trondheim, &#126;120 students.</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/geir.dyrkolbotn">Geir Olav Dyrkolbotn</a> emneansvarlig</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/geir.dyrkolbotn">Geir Olav Dyrkolbotn</a> lærer</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/sergii.banin">Sergii Banin</a> lærer</td></tr></tbody>
<tbody><tr><td rowspan="4" ><a href="https://www.ntnu.no/studier/emner/IMT4124">IMT4124</a></td>
<td ><b>Cryptology</b></td></tr>
<tr><td class="details" >Gjøvik, &#126;30 students.</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/slobodan.petrovic">Slobodan Petrovic</a> emneansvarlig</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/karen.parish">Karen Parish</a> lærer</td></tr></tbody>
<tbody><tr><td rowspan="3" ><a href="https://www.ntnu.no/studier/emner/IMT4125">IMT4125</a></td>
<td ><b>Network Security</b></td></tr>
<tr><td class="details" >Gjøvik, &#126;50 students.</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/stephen.wolthusen">Stephen Wolthusen</a> emneansvarlig</td></tr></tbody>
<tbody><tr><td rowspan="4" ><a href="https://www.ntnu.no/studier/emner/IMT4126">IMT4126</a></td>
<td ><b>Biometrics </b></td></tr>
<tr><td class="details" >Gjøvik, &#126;30 students.</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/patrick.bours">Patrick Adrianus Bours</a> emneansvarlig</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/christoph.busch">Christoph Busch</a> lærer</td></tr></tbody>
<tbody><tr><td rowspan="3" ><a href="https://www.ntnu.no/studier/emner/IMT4127">IMT4127</a></td>
<td ><b>Security Management Metrics</b></td></tr>
<tr><td class="details" >Gjøvik, &#126;30 students.</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/laura.georg">Laura Georg</a> emneansvarlig</td></tr></tbody>
<tbody><tr><td rowspan="3" ><a href="https://www.ntnu.no/studier/emner/IMT4129">IMT4129</a></td>
<td ><b>Risk Management for Information Security</b></td></tr>
<tr><td class="details" >Gjøvik, &#126;20 students.</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/einar.snekkenes">Einar Arthur Snekkenes</a> emneansvarlig</td></tr></tbody>
<tbody><tr><td rowspan="4" ><a href="https://www.ntnu.no/studier/emner/IMT4130">IMT4130</a></td>
<td ><b>Cybercrime Investigation</b></td></tr>
<tr><td class="details" >Gjøvik, &#126;40 students.</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/lasse.overlier">Lasse Øverlier</a> emneansvarlig</td></tr>
<tr><td colspan="2" >Jeffery David Hamm lærer</td></tr></tbody>
<tbody><tr><td rowspan="5" ><a href="https://www.ntnu.no/studier/emner/IMT4133">IMT4133</a></td>
<td ><b>Data Science for Security and Forensics </b></td></tr>
<tr><td class="details" >Gjøvik, &#126;30 students.</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/kyle.porter">Kyle Porter</a> emneansvarlig</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/andrii.shalaginov">Andrii Shalaginov</a> lærer</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/kyle.porter">Kyle Porter</a> lærer</td></tr></tbody>
<tbody><tr><td rowspan="4" ><a href="https://www.ntnu.no/studier/emner/IMT4213">IMT4213</a></td>
<td ><b>Cyber Tactics </b></td></tr>
<tr><td class="details" >Gjøvik, &#126;20 students.</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/geir.dyrkolbotn">Geir Olav Dyrkolbotn</a> emneansvarlig</td></tr>
<tr><td colspan="2" >Roger Johnsen lærer</td></tr></tbody>
<tbody><tr><td rowspan="3" ><a href="https://www.ntnu.no/studier/emner/IMT4215">IMT4215</a></td>
<td ><b>Specialization Project</b></td></tr>
<tr><td class="details" >FE, Gjøvik, &#126;5 students.</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/raghavendra.ramachandra">Raghavendra Ramachandra</a> emneansvarlig</td></tr></tbody>
<tbody><tr><td rowspan="3" ><a href="https://www.ntnu.no/studier/emner/IMT4905">IMT4905</a></td>
<td ><b>Experience-based Master's Thesis</b></td></tr>
<tr><td class="details" >THESIS, Gjøvik, &#126;10 students.</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/katrin.franke">Katrin Franke</a> emneansvarlig</td></tr></tbody>
<tbody><tr><td rowspan="3" ><a href="https://www.ntnu.no/studier/emner/MIS4900">MIS4900</a></td>
<td ><b>Masteroppgave informasjonssikkerhet</b></td></tr>
<tr><td class="details" >THESIS, Gjøvik, &#126;30 students.</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/slobodan.petrovic">Slobodan Petrovic</a> emneansvarlig</td></tr></tbody>
<tbody><tr><td rowspan="6" ><a href="https://www.ntnu.no/studier/emner/TTM4100">TTM4100</a></td>
<td ><b>Kommunikasjon - Tjenester og nett</b></td></tr>
<tr><td class="details" >Trondheim, &#126;576 students.</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/norvald.stol">Norvald Stol</a> emneansvarlig</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/bv">Bjørn Jonny Villa</a> lærer</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/norvald.stol">Norvald Stol</a> lærer</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/karolikv">Faiga M. Alawad</a> stipendiat</td></tr></tbody>
<tbody><tr><td rowspan="6" ><a href="https://www.ntnu.no/studier/emner/TTM4115">TTM4115</a></td>
<td ><b>Design av kommuniserende systemer</b></td></tr>
<tr><td class="details" >Trondheim, &#126;90 students.</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/kraemer">Frank Alexander Kraemer</a> emneansvarlig</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/amirhosein.taherkordi">Amirhosein Taherkordi</a> lærer</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/peter.herrmann">Peter Michael Herrmann</a> lærer</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/hafiz.a.asad">Hafiz Areeb Asad</a> stipendiat</td></tr></tbody>
<tbody><tr><td rowspan="7" ><a href="https://www.ntnu.no/studier/emner/TTM4133">TTM4133</a></td>
<td ><b>Mobile nett og tjenester</b></td></tr>
<tr><td class="details" >Trondheim, &#126;61 students.</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/david.palma">David Fonseca Palma</a> emneansvarlig</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/david.palma">David Fonseca Palma</a> lærer</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/eirik.folstad">Eirik Larsen Følstad</a> lærer</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/kashif.mehmood">Kashif Mehmood</a> stipendiat</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/kalpanie.mendis">Handunneththi V. Kalpanie Mendis</a> stipendiat</td></tr></tbody>
<tbody><tr><td rowspan="7" ><a href="https://www.ntnu.no/studier/emner/TTM4135">TTM4135</a></td>
<td ><b>Anvendt kryptografi og nettverksikkerhet</b></td></tr>
<tr><td class="details" >Trondheim, &#126;246 students.</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/colin.boyd">Colin Alexander Boyd</a> emneansvarlig</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/bor.dekock">Bor de Kock</a> lærer</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/bor.dekock">Bor de Kock</a> stipendiat</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/lise.millerjord">Lise Millerjord</a> stipendiat</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/jonathan.k.eriksen">Jonathan Komada Eriksen</a> stipendiat</td></tr></tbody>
<tbody><tr><td rowspan="4" ><a href="https://www.ntnu.no/studier/emner/TTM4180">TTM4180</a></td>
<td ><b>Nettverkshåndtering</b></td></tr>
<tr><td class="details" >Trondheim, &#126;43 students.</td></tr>
<tr><td colspan="2" >Kjersti Moldeklev lærer</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/ali.esmaeily">Ali Esmaeily</a> stipendiat</td></tr></tbody>
<tbody><tr><td rowspan="5" ><a href="https://www.ntnu.no/studier/emner/TTM4191">TTM4191</a></td>
<td ><b>Grunnleggende kommunikasjonsteknologi og -sikkerhet for SmartGrid</b></td></tr>
<tr><td class="details" >Trondheim</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/norvald.stol">Norvald Stol</a> emneansvarlig</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/bv">Bjørn Jonny Villa</a> lærer</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/patrick.bours">Patrick Adrianus Bours</a> lærer</td></tr></tbody>
<tbody><tr><td rowspan="6" ><a href="https://www.ntnu.no/studier/emner/TTM4200">TTM4200</a></td>
<td ><b>Datanettverk</b></td></tr>
<tr><td class="details" >Trondheim, &#126;63 students.</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/david.palma">David Fonseca Palma</a> emneansvarlig</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/david.palma">David Fonseca Palma</a> lærer</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/stanislav.lange">Stanislav Lange</a> lærer</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/abdulmajid.a.murad">Abdulmajid Murad</a> stipendiat</td></tr></tbody>
<tbody><tr><td rowspan="3" ><a href="https://www.ntnu.no/studier/emner/TTM4850">TTM4850</a></td>
<td ><b>Eksperter i team - Fremtidens brukeropplevelser i en hverdag preget av digitalisering</b></td></tr>
<tr><td class="details" >EIT, Trondheim, &#126;33 students.</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/katrien.demoor">Katrien Rachel W de Moor</a> emneansvarlig</td></tr></tbody>
<tbody><tr><td rowspan="3" ><a href="https://www.ntnu.no/studier/emner/TTM4905">TTM4905</a></td>
<td ><b>Kommunikasjonsteknologi, masteroppgave</b></td></tr>
<tr><td class="details" >THESIS, Trondheim</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/haraldov">Harald Øverby</a> emneansvarlig</td></tr></tbody></table>