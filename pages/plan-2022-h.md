# Bemanning høst 2022


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
</style><input id="myInput" class="form-control me-2" type="search" placeholder="Search" aria-label="Search" onkeyup="myFunction('myInput', 'myTable')"><table class="course_staff_table table table-sm" id="myTable"><tbody><tr><td rowspan="3" ><a href="https://www.ntnu.no/studier/emner/DCSG1001">DCSG1001</a></td>
<td ><b>Infrastruktur: grunnleggende ferdigheter</b></td></tr>
<tr><td class="details" >Gjøvik, &#126;91 students.</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/jia-chun.lin">Jia-Chun Lin</a> emneansvarlig</td></tr></tbody>
<tbody><tr><td rowspan="3" ><a href="https://www.ntnu.no/studier/emner/DCSG1002">DCSG1002</a></td>
<td ><b>Cybersikkerhet og teamarbeid</b></td></tr>
<tr><td class="details" >Gjøvik, &#126;89 students.</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/erjon.zoto">Erjon Zoto</a> emneansvarlig</td></tr></tbody>
<tbody><tr><td rowspan="4" ><a href="https://www.ntnu.no/studier/emner/DCSG2001">DCSG2001</a></td>
<td ><b>Sammenkoblede nettverk og nettverkssikkerhet</b></td></tr>
<tr><td class="details" >Gjøvik, &#126;87 students.</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/eigil.obrestad">Eigil Obrestad</a> emneansvarlig</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/ernst.g.gran">Ernst Gunnar Gran</a> lærer</td></tr></tbody>
<tbody><tr><td rowspan="4" ><a href="https://www.ntnu.no/studier/emner/DCSG2900">DCSG2900</a></td>
<td ><b>Bacheloroppgave Bachelor i digital infrastruktur og cybersikkerhet</b></td></tr>
<tr><td class="details" >THESIS, Gjøvik, &#126;60 students.</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/erik.hjelmas">Erik Hjelmås</a> emneansvarlig</td></tr>
<tr><td colspan="2" >Geir Ove Rosvold lærer</td></tr></tbody>
<tbody><tr><td rowspan="4" ><a href="https://www.ntnu.no/studier/emner/HMS0010">HMS0010</a></td>
<td ><b>HMS-kurs for 1. årsstudenter Gjøvik</b></td></tr>
<tr><td class="details" >HMS, Gjøvik, &#126;150 students.</td></tr>
<tr><td colspan="2" >Lise Margrethe Konow Linnerud lærer</td></tr>
<tr><td colspan="2" >Pål Erik Endrerud lærer</td></tr></tbody>
<tbody><tr><td rowspan="3" ><a href="https://www.ntnu.no/studier/emner/IDATG2202">IDATG2202</a></td>
<td ><b>Operativsystemer</b></td></tr>
<tr><td class="details" >Gjøvik, &#126;170 students.</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/erik.hjelmas">Erik Hjelmås</a> emneansvarlig</td></tr></tbody>
<tbody><tr><td rowspan="4" ><a href="https://www.ntnu.no/studier/emner/IIK3100">IIK3100</a></td>
<td ><b>Etisk hacking og penetrasjonstesting</b></td></tr>
<tr><td class="details" >Gjøvik, Trondheim</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/siriya">Laszlo Erdodi</a> emneansvarlig</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/siriya">Laszlo Erdodi</a> lærer</td></tr></tbody>
<tbody><tr><td rowspan="6" ><a href="https://www.ntnu.no/studier/emner/IIK5000">IIK5000</a></td>
<td ><b>Digital juss og forretningsvirksomhet</b></td></tr>
<tr><td class="details" >FE, Gjøvik, Trondheim</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/haraldov">Harald Øverby</a> emneansvarlig</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/iwona.windekilde">Iwona Maria Windekilde</a> lærer</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/katrien.demoor">Katrien Rachel W de Moor</a> lærer</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/haraldov">Harald Øverby</a> lærer</td></tr></tbody>
<tbody><tr><td rowspan="4" ><a href="https://www.ntnu.no/studier/emner/IIKG1001">IIKG1001</a></td>
<td ><b>Cybersikkerhet og datanettverk</b></td></tr>
<tr><td class="details" >Gjøvik, &#126;108 students.</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/erjon.zoto">Erjon Zoto</a> emneansvarlig</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/jia-chun.lin">Jia-Chun Lin</a> lærer</td></tr></tbody>
<tbody><tr><td rowspan="4" ><a href="https://www.ntnu.no/studier/emner/IIKG2001">IIKG2001</a></td>
<td ><b>Software Security</b></td></tr>
<tr><td class="details" >Gjøvik, &#126;85 students.</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/christian.johansen">Christian Johansen</a> emneansvarlig</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/basel.katt">Basel Katt</a> lærer</td></tr></tbody>
<tbody><tr><td rowspan="3" ><a href="https://www.ntnu.no/studier/emner/IIKG3000">IIKG3000</a></td>
<td ><b>Introduksjon til informasjonssikkerhet og personvern</b></td></tr>
<tr><td class="details" >K-emne, Gjøvik, &#126;30 students.</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/nils.kalstad">Nils Kalstad</a> emneansvarlig</td></tr></tbody>
<tbody><tr><td rowspan="3" ><a href="https://www.ntnu.no/studier/emner/IIKG3005">IIKG3005</a></td>
<td ><b>Infrastructure as Code</b></td></tr>
<tr><td class="details" >Gjøvik, &#126;71 students.</td></tr>
<tr><td colspan="2" >Boye Holden emneansvarlig</td></tr></tbody>
<tbody><tr><td rowspan="3" ><a href="https://www.ntnu.no/studier/emner/IIKG3010">IIKG3010</a></td>
<td ><b>Project Work for Exchange Bachelor Students</b></td></tr>
<tr><td class="details" >FE, Gjøvik, &#126;3 students.</td></tr>
<tr><td colspan="2" >Marius Pedersen lærer</td></tr></tbody>
<tbody><tr><td rowspan="3" ><a href="https://www.ntnu.no/studier/emner/IIKG3020">IIKG3020</a></td>
<td ><b>Introduksjon til hendelseshåndtering</b></td></tr>
<tr><td class="details" >Gjøvik, Trondheim, &#126;36 students.</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/marie.moe">Marie Elisabeth Gaup Moe</a> emneansvarlig</td></tr></tbody>
<tbody><tr><td rowspan="4" ><a href="https://www.ntnu.no/studier/emner/IIKG3021">IIKG3021</a></td>
<td ><b>Campusnettverk og Internettarkitektur</b></td></tr>
<tr><td class="details" >Gjøvik, &#126;16 students.</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/eigil.obrestad">Eigil Obrestad</a> emneansvarlig</td></tr>
<tr><td colspan="2" >Jon Langseth lærer</td></tr></tbody>
<tbody><tr><td rowspan="3" ><a href="https://www.ntnu.no/studier/emner/IIKG4000">IIKG4000</a></td>
<td ><b>Fordypningsemne - individuelt</b></td></tr>
<tr><td class="details" >FE, Gjøvik, &#126;2 students.</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/raghavendra.ramachandra">Raghavendra Ramachandra</a> emneansvarlig</td></tr></tbody>
<tbody><tr><td rowspan="4" ><a href="https://www.ntnu.no/studier/emner/IMT3841">IMT3841</a></td>
<td ><b>Praksis ved CERN innen IT</b></td></tr>
<tr><td class="details" >Gjøvik, &#126;2 students.</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/erik.hjelmas">Erik Hjelmås</a> emneansvarlig</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/erik.hjelmas">Erik Hjelmås</a> lærer</td></tr></tbody>
<tbody><tr><td rowspan="3" ><a href="https://www.ntnu.no/studier/emner/IMT4113">IMT4113</a></td>
<td ><b>Introduction to Cyber and Information Security Technology</b></td></tr>
<tr><td class="details" >Gjøvik, &#126;80 students.</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/patrick.bours">Patrick Adrianus Bours</a> emneansvarlig</td></tr></tbody>
<tbody><tr><td rowspan="5" ><a href="https://www.ntnu.no/studier/emner/IMT4114">IMT4114</a></td>
<td ><b>Introduction to Digital Forensics</b></td></tr>
<tr><td class="details" >Gjøvik, &#126;100 students.</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/jan.w.johnsen">Jan William Johnsen</a> emneansvarlig</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/andrii.shalaginov">Andrii Shalaginov</a> lærer</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/jan.w.johnsen">Jan William Johnsen</a> lærer</td></tr></tbody>
<tbody><tr><td rowspan="5" ><a href="https://www.ntnu.no/studier/emner/IMT4115">IMT4115</a></td>
<td ><b>Introduksjon til informasjonssikkerhetsledelse</b></td></tr>
<tr><td class="details" >Gjøvik, Trondheim, &#126;120 students.</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/grethe.ostby">Grethe Østby</a> emneansvarlig</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/bernhard.hammerli">Bernhard Markus Hämmerli</a> lærer</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/grethe.ostby">Grethe Østby</a> lærer</td></tr></tbody>
<tbody><tr><td rowspan="4" ><a href="https://www.ntnu.no/studier/emner/IMT4123">IMT4123</a></td>
<td ><b>System Security</b></td></tr>
<tr><td class="details" >Gjøvik, &#126;40 students.</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/christian.johansen">Christian Johansen</a> emneansvarlig</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/basel.katt">Basel Katt</a> lærer</td></tr></tbody>
<tbody><tr><td rowspan="7" ><a href="https://www.ntnu.no/studier/emner/IMT4128">IMT4128</a></td>
<td ><b>Socio-technical Systems Enabled Crime</b></td></tr>
<tr><td class="details" >Gjøvik, &#126;20 students.</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/erjon.zoto">Erjon Zoto</a> emneansvarlig</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/mazaher.kianpour">Mazaher Kianpour</a> emneansvarlig</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/erjon.zoto">Erjon Zoto</a> lærer</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/mazaher.kianpour">Mazaher Kianpour</a> lærer</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/stewart.kowalski">Stewart James Kowalski</a> lærer</td></tr></tbody>
<tbody><tr><td rowspan="8" ><a href="https://www.ntnu.no/studier/emner/IMT4203">IMT4203</a></td>
<td ><b>Kritisk infrastruktur  - sikkerhet</b></td></tr>
<tr><td class="details" >Gjøvik, Trondheim, &#126;70 students.</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/sokratis.katsikas">Sokratis Katsikas</a> emneansvarlig</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/alessio.baiocco">Alessio Baiocco</a> lærer</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/georgios.spathoulas">Georgios Spathoulas </a> lærer</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/mehari.g.msgna">Mehari Gebrehaweriya Msgna</a> lærer</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/sunil.chaudhary">Sunil Chaudhary</a> lærer</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/stephen.wolthusen">Stephen Wolthusen</a> lærer</td></tr></tbody>
<tbody><tr><td rowspan="3" ><a href="https://www.ntnu.no/studier/emner/IMT4204">IMT4204</a></td>
<td ><b>Intrusion Detection in Physical and Virtual Networks </b></td></tr>
<tr><td class="details" >Gjøvik, Trondheim, &#126;40 students.</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/slobodan.petrovic">Slobodan Petrovic</a> emneansvarlig</td></tr></tbody>
<tbody><tr><td rowspan="3" ><a href="https://www.ntnu.no/studier/emner/IMT4205">IMT4205</a></td>
<td ><b>Research Project Planning</b></td></tr>
<tr><td class="details" >Gjøvik, &#126;60 students.</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/raghavendra.ramachandra">Raghavendra Ramachandra</a> emneansvarlig</td></tr></tbody>
<tbody><tr><td rowspan="3" ><a href="https://www.ntnu.no/studier/emner/IMT4210">IMT4210</a></td>
<td ><b>Computational Forensics</b></td></tr>
<tr><td class="details" >Gjøvik, &#126;30 students.</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/katrin.franke">Katrin Franke</a> emneansvarlig</td></tr></tbody>
<tbody><tr><td rowspan="4" ><a href="https://www.ntnu.no/studier/emner/IMT4214">IMT4214</a></td>
<td ><b>Cyber Intelligence</b></td></tr>
<tr><td class="details" >Gjøvik, &#126;20 students.</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/geir.dyrkolbotn">Geir Olav Dyrkolbotn</a> emneansvarlig</td></tr>
<tr><td colspan="2" >Roger Johnsen lærer</td></tr></tbody>
<tbody><tr><td rowspan="3" ><a href="https://www.ntnu.no/studier/emner/IMT4215">IMT4215</a></td>
<td ><b>Specialization Project</b></td></tr>
<tr><td class="details" >FE, Gjøvik, &#126;5 students.</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/raghavendra.ramachandra">Raghavendra Ramachandra</a> emneansvarlig</td></tr></tbody>
<tbody><tr><td rowspan="3" ><a href="https://www.ntnu.no/studier/emner/IMT4217">IMT4217</a></td>
<td ><b>Introduction to Data Privacy</b></td></tr>
<tr><td class="details" >Gjøvik, &#126;20 students.</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/staal.vinterbo">Staal Amund Vinterbo</a> emneansvarlig</td></tr></tbody>
<tbody><tr><td rowspan="3" ><a href="https://www.ntnu.no/studier/emner/IMT4303">IMT4303</a></td>
<td ><b>Content-based Indexing and Retrieval</b></td></tr>
<tr><td class="details" >Gjøvik, &#126;5 students.</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/sule.yildirim">Sule Yildirim-Yayilgan</a> emneansvarlig</td></tr></tbody>
<tbody><tr><td rowspan="3" ><a href="https://www.ntnu.no/studier/emner/IMT4305">IMT4305</a></td>
<td ><b>Image Processing and Analysis</b></td></tr>
<tr><td class="details" >Gjøvik, &#126;5 students.</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/sule.yildirim">Sule Yildirim-Yayilgan</a> emneansvarlig</td></tr></tbody>
<tbody><tr><td rowspan="3" ><a href="https://www.ntnu.no/studier/emner/IMT4905">IMT4905</a></td>
<td ><b>Experience-based Master's Thesis</b></td></tr>
<tr><td class="details" >THESIS, Gjøvik, &#126;10 students.</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/katrin.franke">Katrin Franke</a> emneansvarlig</td></tr></tbody>
<tbody><tr><td rowspan="3" ><a href="https://www.ntnu.no/studier/emner/MIS4900">MIS4900</a></td>
<td ><b>Masteroppgave informasjonssikkerhet</b></td></tr>
<tr><td class="details" >THESIS, Gjøvik, &#126;30 students.</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/slobodan.petrovic">Slobodan Petrovic</a> emneansvarlig</td></tr></tbody>
<tbody><tr><td rowspan="6" ><a href="https://www.ntnu.no/studier/emner/TTM4105">TTM4105</a></td>
<td ><b>Aksess- og transportnett</b></td></tr>
<tr><td class="details" >Trondheim, &#126;61 students.</td></tr>
<tr><td ></td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/elissar.khloussy">Elissar Khloussy</a> lærer</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/steinar.bjornstad">Steinar Bjørnstad</a> lærer</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/kalpanie.mendis">Handunneththi V. Kalpanie Mendis</a> stipendiat</td></tr></tbody>
<tbody><tr><td rowspan="6" ><a href="https://www.ntnu.no/studier/emner/TTM4110">TTM4110</a></td>
<td ><b>Pålitelighet og ytelse med simulering</b></td></tr>
<tr><td class="details" >Trondheim, &#126;76 students.</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/yuming.jiang">Yuming Jiang</a> emneansvarlig</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/katrien.demoor">Katrien Rachel W de Moor</a> lærer</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/yuming.jiang">Yuming Jiang</a> lærer</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/jonathan.k.eriksen">Jonathan Komada Eriksen</a> stipendiat</td></tr></tbody>
<tbody><tr><td rowspan="6" ><a href="https://www.ntnu.no/studier/emner/TTM4137">TTM4137</a></td>
<td ><b>Informasjonssikkerhet i trådløse nett</b></td></tr>
<tr><td class="details" >Trondheim, &#126;52 students.</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/anamaria.costache">Anamaria Costache</a> emneansvarlig</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/anamaria.costache">Anamaria Costache</a> lærer</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/ruxandra.olimid">Ruxandra-Florentina Olimid-Nencioni</a> lærer</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/sonu.k.jha">Sonu Kumar Jha</a> stipendiat</td></tr></tbody>
<tbody><tr><td rowspan="4" ><a href="https://www.ntnu.no/studier/emner/TTM4158">TTM4158</a></td>
<td ><b>Pålitelighets- og ytelsesdesign</b></td></tr>
<tr><td class="details" >Trondheim, &#126;5 students.</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/yuming.jiang">Yuming Jiang</a> emneansvarlig</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/yuming.jiang">Yuming Jiang</a> lærer</td></tr></tbody>
<tbody><tr><td rowspan="7" ><a href="https://www.ntnu.no/studier/emner/TTM4160">TTM4160</a></td>
<td ><b>Design av cyber-fysiske systemer</b></td></tr>
<tr><td class="details" >Trondheim, &#126;15 students.</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/peter.herrmann">Peter Michael Herrmann</a> emneansvarlig</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/amirhosein.taherkordi">Amirhosein Taherkordi</a> lærer</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/ergys.puka">Ergys Puka</a> lærer</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/peter.herrmann">Peter Michael Herrmann</a> lærer</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/hafiz.a.asad">Hafiz Areeb Asad</a> stipendiat</td></tr></tbody>
<tbody><tr><td rowspan="8" ><a href="https://www.ntnu.no/studier/emner/TTM4165">TTM4165</a></td>
<td ><b>Digital økonomi</b></td></tr>
<tr><td class="details" >K-emne, Gjøvik, Trondheim, Ålesund, &#126;164 students.</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/iwona.windekilde">Iwona Maria Windekilde</a> emneansvarlig</td></tr>
<tr><td colspan="2" >Anniken Susanne Thoresen Karlsen lærer</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/haraldov">Harald Øverby</a> lærer</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/iwona.windekilde">Iwona Maria Windekilde</a> lærer</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/katrien.demoor">Katrien Rachel W de Moor</a> lærer</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/kaja.ystgaard">Kaja Fjørtoft Ystgaard</a> stipendiat</td></tr></tbody>
<tbody><tr><td rowspan="5" ><a href="https://www.ntnu.no/studier/emner/TTM4175">TTM4175</a></td>
<td ><b>Introduksjon til kommunikasjonsteknologi og digital sikkerhet</b></td></tr>
<tr><td class="details" >Trondheim, &#126;71 students.</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/kraemer">Frank Alexander Kraemer</a> emneansvarlig</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/siriya">Laszlo Erdodi</a> lærer</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/kraemer">Frank Alexander Kraemer</a> lærer</td></tr></tbody>
<tbody><tr><td rowspan="6" ><a href="https://www.ntnu.no/studier/emner/TTM4185">TTM4185</a></td>
<td ><b>Sikkerhet og robusthet i IKT system</b></td></tr>
<tr><td class="details" >K-emne, Trondheim, &#126;117 students.</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/yuming.jiang">Yuming Jiang</a> emneansvarlig</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/karin.bernsmed">Karin Bernsmed</a> lærer</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/yuming.jiang">Yuming Jiang</a> lærer</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/lise.millerjord">Lise Millerjord</a> stipendiat</td></tr></tbody>
<tbody><tr><td rowspan="6" ><a href="https://www.ntnu.no/studier/emner/TTM4195">TTM4195</a></td>
<td ><b>Blokkjede-teknologier og kryptovalutaer</b></td></tr>
<tr><td class="details" >Trondheim, &#126;117 students.</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/mattia.veroni">Mattia Veroni</a> lærer</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/jonathan.k.eriksen">Jonathan Komada Eriksen</a> lærer</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/mattia.veroni">Mattia Veroni</a> stipendiat</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/jonathan.k.eriksen">Jonathan Komada Eriksen</a> stipendiat</td></tr></tbody>
<tbody><tr><td rowspan="4" ><a href="https://www.ntnu.no/studier/emner/TTM4240">TTM4240</a></td>
<td ><b>Avansert nettverkskontroll og administrasjon</b></td></tr>
<tr><td class="details" >Trondheim, &#126;60 students.</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/thomas.zinner">Thomas Zinner</a> emneansvarlig</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/otto.wittner">Otto Jonassen Wittner</a> lærer</td></tr></tbody>
<tbody><tr><td rowspan="4" ><a href="https://www.ntnu.no/studier/emner/TTM4250">TTM4250</a></td>
<td ><b>Avanserte internett-teknologier - Nettsystemer, fordypningsemne</b></td></tr>
<tr><td class="details" >FE, Trondheim</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/thomas.zinner">Thomas Zinner</a> emneansvarlig</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/thomas.zinner">Thomas Zinner</a> lærer</td></tr></tbody>
<tbody><tr><td rowspan="3" ><a href="https://www.ntnu.no/studier/emner/TTM4502">TTM4502</a></td>
<td ><b>Kommunikasjonsteknologi, fordypningsprosjekt</b></td></tr>
<tr><td class="details" >THESIS, Trondheim, &#126;48 students.</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/haraldov">Harald Øverby</a> emneansvarlig</td></tr></tbody>
<tbody><tr><td rowspan="7" ><a href="https://www.ntnu.no/studier/emner/TTM4536">TTM4536</a></td>
<td ><b>Avansert etisk hacking - Informasjonssikkerhet, fordypningsemne</b></td></tr>
<tr><td class="details" >FE, Trondheim, &#126;140 students.</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/danilo.gligoroski">Danilo Gligoroski</a> emneansvarlig</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/danilo.gligoroski">Danilo Gligoroski</a> lærer</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/sahana.sridhar">Sahana Sridhar</a> stipendiat</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/mattia.veroni">Mattia Veroni</a> stipendiat</td></tr>
<tr><td ><a href="https://www.ntnu.no/ansatte/sonu.k.jha">Sonu Kumar Jha</a> stipendiat</td></tr></tbody></table>