# Loginės formulės

Loginė formulė - reiškinys, gautas baigtinį skaičių kartų pavartojus loginių operacijų ženklus bei skliaustus loginiams kintamiesiems jungti.

### Formalus apibrėžimas
- loginės konstantos k ir t yra loginės formulės;
- loginiai kintamieji (pavyzdžiui, p,q,r,s ir t. t.) yra loginės formulės;
- jei Q yra loginė formulė, tai (¬Q) taip pat yra loginė formulė;
- jei P ir Q yra loginės formulės, tai (P∆Q) yra loginė formulė, kur ∆ žymi bet kurią dvinarę loginę jungtį (pavyzdžiui, ^, v, →, ↔,+ , | ,…).

### Pastaba
- Kad supaprastintume formulių užrašymą, mes įvedame kai kurių loginių operacijų atlikimo tvarką ir kai kur skliaustus praleidžiame. Loginės operacijos bus atliekamos tokia tvarka: ¬, , , likusios (tos likusios būtinai bus skliaudžiamos). Taip pat nerašome išorinių skliaustų, pavyzdžiui, rašome ne (p→q), o p→q.
- Konjunkcija ^ ir disjunkcija v geriau skliausti.

### Formulė 
- Q(p, q) := ¬p→(q^¬(qvp))
![[Pasted image 20220906132643.png]]

### Formulės interpretacija

- Jei į loginę formulę įeina n loginių kintamųjų, tai jos teisingumo lentelė turės 2^n eilučių.
- Jei loginė formulė A priklauso nuo kintamųjų p1, p2, …, pn, tai ją žymėsime A(p1, p2, …, pn).

#### Apibrėžimas 
Tegu A(p1, p2, …, pn) yra loginė formulė. Tada konkretus kintamųjų p1, p2, …, pn reikšmių rinkinys vadinamas formulės A interpretacija.
