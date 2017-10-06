# box
Je spletna stran za shranjevanje datotek. (Cloud)
Uporabnik se lahko prijavi (signup) in nato vpiše (login). Pri vsaki prijavi uproabnik na strežniku (v mapi files)
dobi svojo mapo (ime mape je njegovo uporabniško ime), ki jo lahko vidi le on.

Nalaganje datotek je sedaj možno preko Drag'n'drop funkcije (uporabil sem odprtokodno knjižnico "Dropzone.Js"), ali pa s klasičnim oknom. Datoteke, ki so na strežniku, je možno predogledati (slike, tekstovne datoteke, oz. to kar podpira uporabnikov brskalnik);
prevzeti (download) in zbrisati. Za enkrat je možno zgolj ustvariti podmape, a bom hitro dodal tudi funkcijo, da se lahko v poljubno mapo naložijo datoteke.

Za varnost je poskrbljeno z uporabo sej ter gesla so, seveda hashirana. Za enkrat, ker delam samo na localhost-u uporabniškega imena in gesla za mysql nisem spremenil.

Kasneje bom dodal, potrditev prijave (signupa) preko e-pošte, tako bom lahko tudi (bolj varno) dodal deljenje map (in datotek) z drugimi uporabniki. 

Za enkrat se z CSS-om (o.z Bootstrapom) nisem ukvarjal
