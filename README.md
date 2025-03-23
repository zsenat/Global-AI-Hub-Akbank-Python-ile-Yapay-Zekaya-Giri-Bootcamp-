# Global-AI-Hub-Akbank-Python-ile-Yapay-Zekaya-Giri-Bootcamp-
Global AI Hub Akbank Python ile Yapay Zekaya Giriş Bootcamp Projem.
Proje Açıklaması 
Bir metro ağı üzerinde en hızlı rotayı ve en az aktarma gerektiren rotayı bulmak için geliştirilmiştir. Başlangıç ve hedef istasyonları belirtir.
A* algoritması yardımıyla en kısa sürede ulaşabileceği rotayı bulur. 
Projede Kullandığımız Teknolojiler Kütüphaneler 
Python: Projenin temel programlama dili. 
heapq: Öncelik kuyruğu (priority queue) veri yapısını yönetmek için kullanıldı. 
collections: Veri yapılarını daha verimli yönetmek için kullanıldı. 
BFS Algoritması (Breadth-First Search) 
BFS algoritması, en az aktarma gerektiren rotayı bulmak için kullanılmıştır. 
Bu algoritma, genişlik öncelikli arama yaparak en kısa düğüm yolunu keşfetmeye çalışır. 
Başlangıç istasyonu kuyruğa eklenir. 
Kuyruğun başındaki istasyon ziyaret edilir ve komşuları kuyruğa eklenir. 
Hedef istasyon bulunana kadar süreç devam eder. 
BFS, kenar ağırlıklarını dikkate almadan, adım sayısını en aza indirmek için tercih edilmiştir. 
A* Algoritması 
A* algoritması, en hızlı rotayı bulmak için kullanılmıştır. Bu algoritma, tahmini maliyet fonksiyonunu kullanarak en kısa sürede hedefe ulaşılmasını sağlar. Başlangıç istasyonu bir öncelik kuyruğuna eklenir. Her iterasyonda, en düşük toplam maliyetli istasyon seçilir. Komşu istasyonları değerlendirir. Hedef istasyon bulunduğunda algoritma sonlanır. A* algoritması, metro ağındaki yolculuk en kısa olan süreyi bulmak için uygundur. Projeyi tamamlarken kullandığım notlarım.
images/1.sayfa.jpg
images/2.sayfa.jpg
images/3.sayfa.jpg
images/4.sayfa.jpg
Bu projeyi geliştirmek için farklı ulaşım araçları otobüs tramvay vb. eklenebilir. Mobil bir uygulama haline getirileblir bunun için bir arayüz eklenebilir.Kullanıcı kullanacağı toplu taşıma aracını seçer ve gitmek istediği yeri yazarak yolculuk süresini öğreneblir.
