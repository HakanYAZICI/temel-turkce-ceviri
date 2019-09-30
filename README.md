# temel-turkce-ceviri
Uygulamalar için temel Türkçe çeviri yardımcısı. Laravel projelerinize direk olarak aktarabilirsiniz, csv ile çeviri ve ofis programlarında düzenleyebilirsiniz.


<h2>Laravel'e Dil Dosyası Olarak Ekleme</h2>

İlk önce sitenin dilini tanımlıyoruz. Örneğin Route dosyası içinde "tr.siteadi.com" gibi istekleri Türkçe dilinde göstermek için kullanabilirsiniz. 
<pre> App::setLocale("tr");</pre>

Daha sonra dosyamızı Laravel projemizde "resources/lang/" klasörü altında tr isminde bir klasör oluşturup "tr-general.php" dosyamızı içine kopyalıyoruz.

Daha sonra view dosyalarında aşağıdaki biçimde kullanabilirsiniz.
<pre>@lang("tr-general.succes")
@lang("tr-general.october")</pre>
