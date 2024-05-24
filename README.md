# İnsan Kaynakları Projesi Veritabanı Modellemesi
## Projenin Amacı
Sistemimiz üç temel kullanıcı türüne sahiptir. Sistem personeli, İş Arayanlar ve İş verenler. Sistem personeli : Projenizde çalışan kişiler. Örneğin Kariyer.Net personeli.
<br>**Req 1 : İş Arayanlar sisteme kayıt olabilmelidir.** <br>
<br>Kabul Kriterleri:<br>
•	Kayıt sırasında kullanıcıdan ad, soyad, tcno, doğum yılı, e-Posta, şifre, şifre tekrarı bilgileri istenir.<br>
•	Tüm alanlar zorunludur. Kullanıcı bilgilendirilir.<br>
•	Mernis doğrulaması yapılarak sisteme kayıt gerçekleştirilir.<br>
•	Doğrulama geçerli değilse kullanıcı bilgilendirilir.<br>
•	Daha önce kayıtlı bir e-posta veya tcno var ise kayıt gerçekleşmez. Kullanıcı bilgilendirilir.<br>
•	Kayıdın gerçekleşmesi için e-posta doğrulaması gerekir.<br>



**Req 2 : İş verenler sisteme kayıt olabilmelidir.<br>**
Kabul Kriterleri:<br>
•	Kayıt sırasında kullanıcıdan şirket adı, web sitesi, web sitesi ile aynı domaine sahip e-posta, telefon, şifre, şifre tekrarı bilgileri istenir. Burada amaç sisteme şirket olmayanların katılmasını engellemektir.<br>
•	Tüm alanlar zorunludur. Kullanıcı bilgilendirilir.<br>
•	Şirket kayıtları iki şekilde doğrulanır. Kayıdın gerçekleşmesi için e-posta doğrulaması gerekir. HRMS personelinin onayı gerekmektedir.<br>
•	Daha önce kayıtlı bir e-posta var ise kayıt gerçekleşmez. Kullanıcı bilgilendirilir.<br>
**Req 3 : Sisteme genel iş pozisyonu isimleri eklenebilmelidir. Örneğin Software Developer, Software Architect.**<br>
