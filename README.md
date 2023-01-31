Projekti nimi : Osaühingute vorm
Projeti Kirjeldus: Lõin veebirakenduse Django veebirakenduste loomiseks mõeldud vabavararaamistikus. Andmebaasi lõin kasutades PostgreSQL. Veebileht koosneb kolmest leheküljest:
	1 :  Avaleht
	2 :  Osaühingute andmete vaade
	3 :  Osaühingute registreerimise vorm
Avalehel on otsingumootor, mis peaks leidma andmebaasist osaühinguid ning nendele klikkides peaks viima Osaühingu andmete vaate leheküljele. Otsingumootorit õigesti tööle ei saanud, ilmselt jäi nii ajast kui teadmistest puudu.
Osaühingute andmete vaade kuvab juba registreerituid osaühinguid.
Osaühingute registreerimise vorm laseb registreerida osaühinguid. Sellel lehel peaks olema võimalik lisada juriidilisi või füüsilisi isikuid, aga ei saanud radio-buttonitega tööle, et kuvaks vastavat valikut tehes õige vormi.
Registreerides sellel lehel osaühinguid salvestab see registreeritud osaühingu andmebaasi ja kuvab neid Osaühingu andmete vaates.


Kuidas installida ja käivitada:
	a. Installi requirements.txt
		1. Terminalis minna vastavasse kausta kuhu on projekt alla laetud. Kaustas minna application kausta sisse.
    (cd Osaühingute_vorm, cd application)
		2. Aktiveeri virtuaalkeskkond
		3. Terminalis (olles application kaustas) and käsklus: pip install -r requirements.txt  
	b. Käivitamine :
		1. Terminalis peaks asuma application kaustas
		2. Kohaliku serveri käivitamine terminalis: "python manage. py runserver"
		3. Kopeerida URL brauserisse.
# Webapp
