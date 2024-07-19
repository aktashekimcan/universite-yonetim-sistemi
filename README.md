# universite-yonetim-sistemi

Bu tür bir sistem için oluşturulabilecek basit bir Class diyagramını  açıklayacağım. Bu örnekte, "Üniversite", "Departman", "Ofis" ve "Çalışan" olmak üzere dört ana sınıf bulunmaktadır. İlişkiler ve kardinaliteler (birlikteliklerin nicelikleri) ile bu yapıyı tanımlayacağım.

Üniversite Sınıfı:

Üniversitenin içinde birden fazla departman bulunur.
Üniversitenin içinde birden fazla ofis bulunur.
Üniversitenin içinde birden fazla çalışan bulunur.
Departman Sınıfı:

Her departmanın içinde birden fazla ofis bulunur.
Bir departman bir üniversiteye bağlıdır.
Ofis Sınıfı:

Bir ofis bir departmana bağlı olabilir veya doğrudan üniversiteye bağlı olabilir.
Bir ofiste birden fazla çalışan bulunabilir.
Çalışan Sınıfı:

Her çalışan bir ve yalnız bir ofiste çalışır.
Çalışanlar ya profesör ya da memur olarak sınıflandırılabilir.


![Class Diagram](./class_diagram.png)


Açıklamalar:
1..*: "Bir üniversitenin bir veya daha fazla departmanı/ofisi/çalışanı olabilir."
1: "Her departman/ofis bir üniversiteye veya departmana bağlıdır."
1..1: "Her çalışan sadece bir ofiste çalışır."
Bu yapı temel bir Class diyagramını yansıtır ve gerçek uygulama ihtiyaçlarına göre genişletilebilir veya modifiye edilebilir. Özellikle "Çalışan" sınıfı altında "Profesör" ve "Memur" gibi alt sınıflar tanımlanabilir.






