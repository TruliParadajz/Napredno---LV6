# Instalacija
Potrebno je imati instaliranu MongoDB bazu podataka

Instalarati module sa npm install 

Pokrenuti mongoDB sa naredbom mongod (C:\Program Files\MongoDB\Server\{verzija}\bin), u slučaju errora da ne može pronaći  C:\data\db samo kreirati taj folder na traženoj lokaciji

Pokrenuti aplikaciju sa npm start

U pregledniku otvoriti http://127.0.0.1:3000

# Upotreba
Aplikacija pri pokretanju otvara stranicu dobrodošlice

Napravljena je schema za novi objekt zvan `Projects`

Pristupa im se sa rutom http://127.0.0.1:3000/blobs

Novi objekt se dodaje sa http://127.0.0.1:3000/blobs/new 

Nakon unosa vodi vas na index stranicu gdje imate `Show`, `Edit` ili `Delete` 
