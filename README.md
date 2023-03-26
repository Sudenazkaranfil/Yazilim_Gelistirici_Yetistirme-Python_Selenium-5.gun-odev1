# Yazilim_Gelistirici_Yetistirme-Python_Selenium-5.gun-odev1

@pytest.fixture: Pytest test çerçevesi için bir öğe oluşturur ve herhangi bir test öncesinde veya sonra belirli bir koşulu veya veriyi ayarlamak veya temizlemek için kullanılabilir. Selenium testleri için @pytest.fixture kullanarak örneğin, webdriver örneği oluşturulabilir veya önceden belirlenmiş bir URL açılabilir. Bu, testlerin her biri için aynı başlangıç noktasına sahip olmalarını sağlar ve tekrar kullanılabilir kod blokları sağlar.


@pytest.mark.parametrize: Pytest test çerçevesi içinde aynı test kodunun farklı parametrelerle çalıştırılmasını sağlar. Bu dekoratör, test fonksiyonlarının birden fazla kez çalıştırılmasını ve farklı girdi parametreleriyle test edilmesini sağlar. 

@pytest.mark.skip: Pytest test çerçevesi içinde belirli bir testin atlanmasını sağlar. Bu dekoratör, testin çalıştırılmamasını ve sonuç raporunda görüntülenmemesini sağlar.

@pytest.mark.xfail: Pytest test çerçevesi içinde bir testin bilerek başarısız olacağını ve bu nedenle hatalı sonuç vermeyeceğini belirtmek için kullanılır. 

@pytest.mark.timeout: dekoratörü, pytest test çerçevesi içinde belirli bir testin belirli bir zaman aşımı süresini geçmesini engellemek için kullanılır. Bu dekoratör, testin belirtilen süre içinde tamamlanması gerektiğini belirtir ve aksi halde test otomatik olarak sonlandırılır.
