# Kendime Notlar

## 1. Reguler Expression

|Meta karakter|Açıklama|
|:----:|:----|
|.|Satır başlangıcı hariç herhangi bir karakterle eşleşir.|
|[ ]|Köşeli parantezler arasında bulunan herhangi bir karakterle eşleşir.|
|[^ ]|Köşeli parantez içerisinde yer alan `^` işaretinden sonra girilen karakterler haricindeki karakterlerle eşleşir.|
|*|Kendisinden önce yazılan karakterin sıfır veya daha fazla tekrarı ile eşleşir.|
|+|Kendisinden önce yazılan karakterin bir veya daha fazla olan tekrarı ile eşleşir.|
|?|Kendisinden önce yazılan karakterin varlık durumunu opsiyonel kılar.|
|{n,m}|Kendisinden önce yazılan karakterin en az `n` en fazla `m` değeri kadar olmasını ifade eder.|
|(xyz)|Verilen sırayla `xyz` karakterleriyle eşleşir.|
|&#124;| Karakterden önce veya sonra verilen ifadelerin herhangi biriyle eşleşebilir. İfadeye Yada anlamı katar.|
|&#92;|<code>[ ] ( ) { } . * + ? ^ $ \ &#124;</code> özel karakterin aranmasını sağlar.|
|^|Girilen verinin başlangıcını ifade eder.|
|$|Girilen verinin sonunu ifade eder.|
