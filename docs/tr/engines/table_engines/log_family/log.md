---
machine_translated: true
machine_translated_rev: e8cd92bba3269f47787db090899f7c242adf7818
toc_priority: 33
toc_title: "G\xFCnl\xFCk"
---

# Günlük {#log}

Motor günlük motorları ailesine aittir. Günlük motorlarının ortak özelliklerini ve farklılıklarını görün [Log Engine Ailesi](log_family.md) makale.

Log differsar differsit fromma [TinyLog](tinylog.md) bu küçük bir dosyada “marks” sütun dosyaları ile bulunur. Bu işaretler her veri bloğuna yazılır ve belirtilen satır sayısını atlamak için dosyayı okumaya nereden başlayacağınızı gösteren uzaklıklar içerir. Bu, tablo verilerini birden çok iş parçacığında okumayı mümkün kılar.
Eşzamanlı veri erişimi için, okuma işlemleri aynı anda gerçekleştirilebilirken, yazma işlemleri okur ve birbirlerini engeller.
Günlük altyapısı dizinleri desteklemez. Benzer şekilde, bir tabloya yazma başarısız olursa, tablo bozulur ve Okuma bir hata döndürür. Günlük altyapısı, geçici veriler, bir kez yazma tabloları ve sınama veya gösteri amaçları için uygundur.

[Orijinal makale](https://clickhouse.tech/docs/en/operations/table_engines/log/) <!--hide-->
