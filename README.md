# ZOO
Acest proiect propune dezvoltarea unei aplicații web pentru un portal de informații a unei grădini zoologice. Această aplicație va cuprinde și funcționalități mai complexe pentru gestiunea informațiilor din baza de date. In această bază de date va exista o evidență a animalelor, a tichetelor de intrare și alte informații despre animale.
Astfel, s-a decis implementarea  unui site a unei grădini zoo din India, care oferă atât informații despre animalele găzduite, dar și permite introducerea în baza de date informații despre tichetele de intrare vândute. Acestea se împart in mai multe categorii: pentru adulți, pentru copii, pentru indieni și pentru străini.

Specificațiile proiectului vor ține cont și de cerințele utilizatorului. Se ține cont că această aplicație este pentru 2 categorii de clienți: indieni (având în vedere că grădina zoo este în India) și străini. Design-ul trebuie să fie sugestiv pentru a fi ușor de navigat de către oricine, indiferent de cunoștințele tehnice ale utilizatorului.
Informațiile din baza de date sunt stocate în mai multe tabele, fiecare cu un rol bine stabilit. Avem nevoie de tabele pentru memorarea tichetelor de intrare, a animalelor găzduite și a informațiilor care vor fi afișate pe o pagina de pe site. De menționat este faptul că vânzarea tichetelor se poate face doar prin administrator. Utilizatorii nu pot să își creeze cont sau să cumpere bilete de intrare direct de pe site.

Pentru a implementa site-ul am folosit mai multe limbaje de programare și medii de programare. Codul a fost scris cu ajutorul Microsoft Visual Studio Code.
Limbajele de programare principale folosite au fost: PHP, HTML, CSS, JavaScript, jQuery și diferite plugin-uri prin utilizarea Bootstrap. 
Pentru crearea tabelelor și popularea lor am generat codul SQL în Data Modeler și am folosit phpMyAdmin ca server XAMPP. Structura a fost realizată folosind elemente de PHP și HTML, iar costumizarea site-ului a fost realizată folosing CSS și JavaScript.


# Interfața Web:
# HOME
Pagina principala este index.php din folderul destinat interacțiunii cu utilizatorul. Se pot observa variate informații/imagini încărcate în baza de date prin intermediul tabelei tblanimal cu ajutorul interfeței administratorului, la secțiunea Animals Info.
![image](https://user-images.githubusercontent.com/124103696/236634355-5e21836a-0d15-4802-aff5-882622c777d5.png)
![image](https://user-images.githubusercontent.com/124103696/236634500-52e99211-de62-45fa-afd8-b5ac76bd0c3c.png)
![image](https://user-images.githubusercontent.com/124103696/236634510-7633ae96-7792-464c-96fd-404ba216a57e.png)
![image](https://user-images.githubusercontent.com/124103696/236634518-15c72a3a-7625-4ea3-9429-661077af1191.png)

# ABOUT
Această pagină este about.php dintre paginile destinate utilizatorilor și va afișa informația scrisă de către administrator în platforma dedicată lui de acces. Această interfață se află la secțiunea Page a documentației și se folosește de tabela tblpage.
 ![image](https://user-images.githubusercontent.com/124103696/236634524-8d06c3cd-9e8d-4320-977d-c1a2a27416f1.png)
![image](https://user-images.githubusercontent.com/124103696/236634529-032dfe91-d908-43d1-b52e-dd11baa9fcec.png)

 
# CONTACT
Această pagină este contact.php dintre paginile destinate utilizatorilor și va afișa informația scrisă de către administrator în platforma dedicată lui de acces. Această interfață se află la secțiunea Page a documentației și se folosește de tabela tblpage.
 ![image](https://user-images.githubusercontent.com/124103696/236634534-a7eb0b24-c9e5-4e2c-ae2b-138920028a30.png)

 
# ANIMALS
Această pagină este animals.php. Dacă o dăm click pe una dintre imaginile cu animale vom fi redirecționați către o pagină cu mai multe informații despre animalul ales. Acea pagină este animal-detail.php. Se pot observa variate informații/imagini încărcate în baza de date prin intermediul tabelei tblanimal cu ajutorul interfeței administratorului, la secțiunea Animals Info.
 ![image](https://user-images.githubusercontent.com/124103696/236634544-328cba55-7cd9-4447-87df-6ad165a6c7f7.png)
![image](https://user-images.githubusercontent.com/124103696/236634549-cbb7bcf4-e835-4b1c-9edb-e6746116d85f.png)

 
# ADMIN – INTERFAȚĂ LOGIN
Aceasta se folosește de tabela tbladmin pentru a oferi acces doar celor care au datele de logare corecte inregistrate în baza de date. Aceasta este pagina index.php din folderul destinat paginilor pentru administrator.
 ![image](https://user-images.githubusercontent.com/124103696/236634557-664442bc-1022-47a9-9276-86418ca5c9e3.png)

# ADMIN – DASHBOARD
Aceasta este prima pagină cu care administratorul se întâlnește. În Dashboard vor fi afișate cele mai recente rapoarte. Această pagina este dashboard.php din folderul aferent interfeței pentru admin.
 ![image](https://user-images.githubusercontent.com/124103696/236634568-b2993b7c-65f6-47cf-80a3-b64146e6de0e.png)

# ADMIN – ANIMALS INFO
La fel cum s-a menționat mai sus, această secțiune oferă posibilitatea de a adăuga/modifica informații dupa bunul plac. Aceste pagini sunt: add-animals.php, manage-animals.php, changeimage.php.
Add animals
 ![image](https://user-images.githubusercontent.com/124103696/236634581-638bd6c8-d92d-4400-992f-a127250069d3.png)
 
Manage Animals
 ![image](https://user-images.githubusercontent.com/124103696/236634590-920a1408-2a23-4b92-a59e-a3e386387f68.png)

# ADMIN – TICKET OPTIONS
Această secțiune ofera posibilitatea de a vizualiza, adăuga și modifica informațiile de pe ticketele deja vândute. Paginile sunt: edit-ticket.php, manage-foreigners-ticket.php, manage-normal-ticket.php, manage-ticket.php, add-foreigners-ticket.php, add-normal-ticket.php, view-foreigner-ticket.php, view-normal-ticket.php.
Ticket Categories
 ![image](https://user-images.githubusercontent.com/124103696/236634601-3654ab77-3ef9-47b4-a9a6-22eeab71ad8c.png)

Add Ticket (Indian Ticket / Foreigner Ticket)
 ![image](https://user-images.githubusercontent.com/124103696/236634604-9fcee371-3274-4123-9ae4-b961b5529881.png)

Manage Ticket (Indian Ticket / Foreigner Ticket)
 ![image](https://user-images.githubusercontent.com/124103696/236634612-76a9211c-959f-4735-a4b4-93adaa8980bf.png)

# ADMIN – PAGE
Aceste pagini conțin informațiile care vor fi afișate pe site. Paginile sunt: aboutus.php și contuctus.php.
About Us
 ![image](https://user-images.githubusercontent.com/124103696/236634622-11feb296-b687-43e4-bde2-2367127d645a.png)
 
Contact Us
 ![image](https://user-images.githubusercontent.com/124103696/236634629-d172fcfc-4c99-4875-afb9-1a041f53584a.png)

# ADMIN – REPORTS (INDIAN TICKET / FOREIGNER TICKET)
Aici se vor afișa rapoartele detaliate cu privire la vânzarea ticketelor intr-un interval de timp ales. Paginile sunt: between-dates-foreignerreports.php, between-dates-normalreports.php, foreigner-bwdates-reports-details.php, normal-bwdates-reports-details.php.
 ![image](https://user-images.githubusercontent.com/124103696/236634635-4db051c0-2fa6-4e32-b62b-7bab8f4471c3.png)

# ADMIN – SEARCH (INDIAN TICKET / FOREIGNER TICKET)
Administratorul poate să caute un ticket in funcție de ID-ul unic al fiecăruia. 
Pagina este: normal-search.php.
![image](https://user-images.githubusercontent.com/124103696/236634642-e742530b-35ec-469b-9415-942647c00aef.png)
 
# ADMIN – OPTIONS
Aici sunt toate opțiunile și setările de utilizator pe care administratorul le poate face propriului său cont. Paginile sunt: profile.php, reset-password.php. 
 ![image](https://user-images.githubusercontent.com/124103696/236634649-3b4602b2-3552-4d6f-bf0e-ed60b35797a4.png)

# ADMIN PROFILE
 ![image](https://user-images.githubusercontent.com/124103696/236634654-1d0a58cd-3712-4f1a-b206-34900a3471ce.png)

# ADMIN MANAGE PASSWORD
 ![image](https://user-images.githubusercontent.com/124103696/236634658-e7c16c61-362a-4a2e-b603-9bb8f196ac43.png)


