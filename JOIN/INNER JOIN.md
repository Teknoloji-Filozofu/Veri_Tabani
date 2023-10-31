link: [[Database]]
tags: #

---

``` sql

SELECT sütun_ismi
FROM tablo_1
INNER JOIN tablo_2
ON tablo1.sütun_ismi = tablo_2.sütun_ismi;

SELECT 
	a.name,
	a.surname,
	a.age,
	b.sales,
	b.customer_name,
	b.customer_surname
FROM sales_22015 AS a
INNER JOIN customer_22015 AS b
ON a.customer_id = b.customer_id
ORDER BY customer_id;
	
``` 


SQL-Join, iki ya da daha fazla tablonun birbirleriyle belli şartlar altında birleşmesinden ve bu birleşim sonucu verilerin işlenmesinden oluşur. Bu birleşim, tabloların kolonları üzerinden yapılır ve buradan verilerin ilişkilendirilmesi sonucu oluşur.

**Inner-Join:** Birleştirilen tablolarda **eşleşen** değerlere sahip kayıtları döndürür. Burada eşleyen kelimesinin altını çiziyorum çünkü sadece eşleşen değerlerin bize döneceği konusu önemli.

**Left Join:** Left join sözcüğü ile solda bulunan tablodaki (ilk seçtiğimiz tablo) tüm kayıtlar ile sağdaki tablodaki eşleşen kayıtları bize döndürür.

**Right Join:** Right join yapısı, left join yapısının aynısıdır, sadece öncelik alınan tablonun konumu değişiyor.

**Full Join:** Full join yapısı, isminden de anlaşılacağı üzere tüm verileri getiren bir yapıdır.

---
link: [[Database]]
tags: #
