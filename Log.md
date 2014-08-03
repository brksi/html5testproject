U ovom fajlu cemo cuvati ideje.
------------------------------------------------
03.08.2014 12.35
Ideja, napraviti webaplikaciju koja ce biti vrlo jednostavna, multi jezicna (da podrzava vise jezika primer hrvatski nemacki, engleski), bitno da se jezik u bilo kom trenutku moze promeniti. 
 
Aplikacija ce upisivati u bazu podataka vreme I datum prijave I odjave radnika. 
 
Zamisao da na GUI bude dva tastera jedna za prijavu jedan za odjavu. 
radnik da bi se prijavio mora da klikne dugme prijava a zatim mu se otvara novi prozor (view) gde moze da unese svoj pin kod. 
Kada potvrdi pin kod, webcamera pravi sliku I cuva je u direktorijum posebno za svakog radnika. 
Ovo je zbog zloupotrebe pin koda.  
Pin kod treba 2x radnik da se unese zbog mogucnost greske prilikom unosa.
Program uporedjuje ova dva i ako su ista cuva datum i vreme u bazu.

Pin kod treba da se sastoji od 4 broja.
Posle cemo ovo da sirimo na barcod, Rfid itd.

BAza podataka tabela radnik 
User_id
User_sifra(interna sifra)
User_name
User_lastname
User_OU_ID (organization Unit)
User_mail
User_adresa
User_mesto
User_dateOfBirth
User_gender



